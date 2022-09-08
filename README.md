# CMPG_323_Project2-26934620

## Instructions to interact:
### When a page error occurs:
- Seeing Swagger.json file

Make sure the url contains /swagger/v2/swagger.json at the end.
- Testing

Make sure the url ends with /swagger/index.html to be able to interact, via Swagger, with the API.

### Authentication:
1. Normal registration:
  - Type in a username
  - Make sure the email is in the rigt format
  - The password must atleast contain a capital letter, number and symbol (make sure it is also long enough)

2. Registration for Admin:
  - Same as normal registration but indicate in the username that it is a admin role for the database

3. Login:
  - Use the Username and Password you already registered with
  - You have to login to get a token to use for authentication
  - Once you have logged in, copy the token (exclude the parentheses)
  - Click on one off the slot simbols to open the 'Available authorizations' window
  - In the textbox type 'Bearer' [space] and then your token
  - Click 'Authorize' and then close

4. Work further:
  - Click on "Try it out'
  - Type in what you want to change
  - Click on 'Execute'
