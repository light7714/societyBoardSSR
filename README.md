npm install --save express ejs mongoose express-session connect-mongodb-session bcryptjs connect-flash dotenv nodemailer nodemailer-sendgrid-transport express-validator multer

# todo
view folder
public folder 
add isLoggedIn in login controller
make logout controller fn
change all err handling
add paths to all links in navbar
check for confrim password
on reloading, post req sent again
check if email already exists in signup validation
add date and datetime validation
create event to not be visible till society is created, also clicking on avatar or visiting profile page through url should redirect to create society page when society isnt created (user isnt part of any group)
In 500 page, should see if impMessage exists, then show that only, otherwise show message (see postCreateSociety)
check if email of user2 and user3 already exists when creating society.
add frontend validation (remove novalidate)
give proper validation err msgs
check for success flash msg
if someone else's event id is entered manually, then handle later


Not Authenticated: Signup, login
Authenticated: Create Society, logout, avatar(profile page)
After creating society, create society to not be shown