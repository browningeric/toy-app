# Chapter 2 Exercises

1. The name is 'notice'. It disappears upon refresh.
2. It is still created despite having no email.
3. It's totally fine with that as well.
4. Yes, a message is displayed by default when a user is deleted.

1. User goes to '/users/x/edit'. Router directs user to correct controller. Controller talks to database and gets user information. User information is sent back to render.
2. users_controller.rb line 67
3. '/users/edit.html.erb'

1. Id is 'notice'; it disappears on refresh. 
2. New micropost with no user or content still works fine.
3. Works fine to post with >140 characters.

1. Messages greater than 140 chars now return an error state.
2. Id is 'error_explanation'

1. Nailed it.
2. Get the errors, so we're good.
3. Had to figure out colon first syntax, now good.