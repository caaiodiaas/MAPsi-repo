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

## TAM questions

Below are the questions asked for evaluation by the Technology Acceptance Model

Regarding the development of programs:
- Using the MAPsi system will facilitate the development of skills programs:
- The development of skills programs is:
- The development of skills programs in the MAPsi system was:
- Learning how to develop skills programs in the MAPsi system is:

Regarding the registration of evaluations
- Using the MAPsi system will facilitate recording patient assessments:
- The record of patient assessments is:
- The registration of patient assessments in the MAPsi system was:
- Learning how to record patient assessments in the MAPsi system is:

As for patients
- Using the MAPsi system will facilitate the recording of clinic patient data:
- The recording of patient data is:
- The registration of patients in the MAPsi system was:
- Learning how to register patients in the MAPsi system is:

As for collaborators
- Using the MAPsi system will facilitate the recording of data from clinic employees:
- The record of employee data is:
- The registration of employees in the MAPsi system was:
- Learning how to register employees in the MAPsi system is:

As for supervisors
- Using the MAPsi system will facilitate the recording of data from the company's supervisors:
- The data record of the company's supervisors is:
- The registration of supervisors in the MAPsi system was:
- Learning how to register supervisors in the MAPsi system is:

Regarding protocols
- Using the MAPsi system will facilitate the storage of protocols and their respective abilities:
- The record of protocols and their respective abilities is:
- The registration of protocols and skills in the MAPsi system was:
- Learning how to register protocols and skills in the MAPsi system is:

Regarding the MAPsi system
- In general, the system will be useful for the company's functionalities:
- In general, the use of the system is:
- In general, learning how to use the system is:
