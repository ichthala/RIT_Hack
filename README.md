RIT_Hack
========

You are now on the first_scaffold branch. A basic User scaffold (Model, View, and Controller components) has been created for you. Check app/models, app/controllers, and app/views to see what new files were added. Now you can add more scaffolds to represent any kind of resource you want.

## first_scaffold - How to generate subsequent scaffolds that include model attributes
- Within your Nitrous terminal, type the command to scaffold.
- What should that command look like? Let's say we want a List model with a name and a count field.
- rails generate scaffold List name:string count:integer
- The format is: rails generate scaffold \[ModelName\] \[field_name\]:\[field_data_type\] ...
- You don't need to add every possible column now. You can add more as you develop your project.
