# Azure Pipelines manual stage triggers

Demonstration of the [new feature in Azure Pipelines](https://learn.microsoft.com/en-us/azure/devops/release-notes/2024/sprint-243-update?WT.mc_id=DOP-MVP-5001655#manually-triggered-yaml-pipeline-stages) that supports using manual triggers on stages. This feature was released as part of Sprint 243/ 13th August 2024.

Read the official documentation for this feature in the section [Add a manual trigger](https://learn.microsoft.com/azure/devops/pipelines/process/stages?view=azure-devops&tabs=yaml&WT.mc_id=DOP-MVP-5001655#add-a-manual-trigger).

Note there is currently a limitation that a manually triggered stage cannot depend on any other stages. Other stages *can* depend on the manually triggered stage however.
