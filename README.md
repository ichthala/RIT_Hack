RIT_Hack
========

You are now on the first_scaffold branch.

## first_scaffold - How to generate subsequent scaffolds that include model attributes
- Within your Nitrous terminal, type the command to scaffold.
- What should that command look like? Let's say we want a User model with a name and an admin field.
- rails generate scaffold User name:string admin:boolean
- The format is: rails generate scaffold \[ModelName\] \[field_name\]:\[field_data_type\] ...
- You don't need to add every possible column now. You can add more as you develop your project.
