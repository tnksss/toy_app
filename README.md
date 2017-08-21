# Chapter 2: A toy app
## Section 2.2.1 - A user tour
1 - Create a new user, then use your browser’s HTML inspector to determine the CSS id for the text “User was successfully created.” What happens when you refresh your browser?  
>  A: a <p> tag have a id="notice" | The <p> tag still exists, but is omit in view page.

2 - What happens if you try to create a user with a name but no email address?  
>  A: A new user is created without email anyway.  

3 - What happens if you try create a user with an invalid email address, like “@example.com”?  
>  A: A new user is created with a invalid email anyway.  

4 - Destroy each of the users created in the previous exercises. Does Rails display a message by default when a user is destroyed?  
>  A: In the same <p> tag with id="notice" "The user was successfully destroyed"

## Section 2.2.2 - MVC in action
1 - By referring to Figure 2.11, write out the analogous steps for visiting the URL /users/1/edit.  
>  A:

2 - Find the line in the scaffolding code that retrieves the user from the database in the previous exercise.  
>  A:

3 - What is the name of the view file for the user edit page?  
>  A:  

## Section 2.3.1 - A micropost microtour
1 - Create a new micropost, then use your browser’s HTML inspector to determine the CSS id for the text “Micropost was successfully created.” What happens when you refresh your browser?  
>  A:

2 - Try to create a micropost with empty content and no user id.  
>  A:

3 - Try to create a micropost with over 140 characters of content (say, the first paragraph from the Wikipedia article on Ruby).
>  A:

4 - Destroy the microposts from the previous exercises.  
>  A:

## Section 2.3.2 - Putting the _micro_ in microposts.
1 - Try to create a micropost with the same long content used in a previous exercise (Section 2.3.1.1). How has the behavior changed?  
>  A:

2 - Use your browser’s HTML inspector to determine the CSS id of the error message produced by the previous exercise. 
>  A: 

## Section 2.3.4 - A user `has_many` microposts  
1 - Edit the user show page to display the content of the user’s first micropost. Confirm by visiting /users/1 that it worked.  
>  A:  

2 - The code in Listing 2.16 shows how to add a validation for the presence of micropost content in order to ensure that microposts can’t be blank. Verify that you get the behavior shown in Figure 2.16.   
>  A:

3 - Update Listing 2.17 by replacing FILL_IN with the appropriate code to validate the presence of name and email attributes in the User model.  
>  A:

## Section 2.3.5 - Deploying the toy app  
1 - Create a few users on the production app.  
>  A:  

2 - Create a few production microposts for the first user.  
>  A:

3 - By trying to create a micropost with content over 140 characters, confirm that the validation from Listing 2.13 works on the production app.  
>  A:










