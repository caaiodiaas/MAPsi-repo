# MAPsi-repo
Repository of elements relating to the MAPsi project

## Database

The figure below presents a diagram with all project entities, as well as their relationships, attributes and attribute types.

![db](assets/db_model.png)

The elements presented in the database figure refer to the following parts:
- Supervisors:tb_supervisor;
- Patients: tb_patient;
- Collaborators: tb_collaborator;
- Programs: tb_program;
- Evaluations: tb_evaluation;
- Protocols: tb_protocol;
- Skills: tb_skill;
- Collaborators and programs relationship: tb_colalborator_program;
- Skills and programs relationship: tb_skill_program;
- Evaluation and skills relationship: tb_skillrating;
  
From these connections, it is visible that there are many "one-to-many" relationships in the model, with some exceptions in which the relationship must be "many-to-many" and the existence of an auxiliary entity is necessary to implement this relationship, as in list of programs and collaborators (“tb_program” and “tb_skill”), in which the entity "tb_skill_program" is responsible for storing the identifiers of both, enabling this relationship.
