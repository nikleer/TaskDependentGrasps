# TaskDependentGrasps

This repository hosts three datasets for the purpose of making task-dependent grasp pose predictions. We have retrieved this data through crowdsourcing studies carried out on [Amazon MTurk](https://www.mturk.com/) as described in our publication [A Study on the Influence of Task Dependent Anthropomorphic Grasping Poses for Everyday Objects](https://ieeexplore.ieee.org/abstract/document/10000198) (link to the [PDF](https://www.dfki.de/fileadmin/user_upload/import/12852_Humanoids22_43_C.pdf)). This work is provided under the **MIT License**.

Each dataset is structured similarly and contains the following columns:

Data         | Explanation
-------------|----------------
Task         | Represents the task we have collected the data for
GraspType    | Grasp type that received the responses (MediumWrap, Lateral, Tripod, Writing)
Object       | The corresponding object the responses were collected for
Responses    | Number of responses for a specific grasp type (max. 20)
Instruction  | Instruction that was provided to the study participants

We have retrieved the above data for the tasks "hold" (see [holdStudyResults.CSV](https://github.com/nikleer/TaskDependentGrasps/blob/main/holdStudyResults.CSV)), "pick" (see [pickStudyResults.CSV](https://github.com/nikleer/TaskDependentGrasps/blob/main/pickStudyResults.CSV)) and a concrete task specifically related to each individual object (see  [objectSpecificStudyResults.CSV](https://github.com/nikleer/TaskDependentGrasps/blob/main/objectSpecificStudyResults.CSV)).
