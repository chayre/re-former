# Re-Former
Creating forms in Ruby on Rails apps utilizing the built-in helper methods. Two forms are created - new user (accessed via http://localhost:3000/users/new), which allows you to create a new user, and edit user (accessed via http://localhost:3000/cars/:id/edit) which allows you to edit a user, identified by the :id. New users are submitted to the create method in the Users controller; user edits are submitted to the update method in the Users controller.