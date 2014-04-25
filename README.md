RIT_Hack
========

You are now on the generate_app branch. You can see a basic Rails directory structure. There's a lot of stuff, but don't worry. For now, the only directories you care about are app/ and db/. app/ is where almost all of your application logic will be stored, including the models, views, and controllers. db/migrate/ is where your migrations will be stored. Migrations specify how database rows should be represented as, or "migrated to," code objects. Migrations will be generated along with your scaffold.

## generate_app - How to generate your first Scaffold
Within your Nitrous terminal, type the following commands:
- cd workspace/RIT_Hack
- rails generate scaffold \[ModelName\] \[field_name\]:\[field_data_type]
- Here's an example:
- rails generate scaffold User name:string admin:boolean
