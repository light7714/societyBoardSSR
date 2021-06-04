npm install --save express ejs mongoose express-session connect-mongodb-session bcryptjs connect-flash dotenv nodemailer nodemailer-sendgrid-transport express-validator multer

# todo

change all err handling
**IMP** check for confrim password
on reloading, post req sent again
add date and datetime validation
In 500 page, should see if impMessage exists, then show that only, otherwise show message (see postCreateSociety)
check if email of user2 and user3 already exists when creating society.
add frontend validation (remove novalidate)
give proper validation err msgs
check for success flash msg
**IMP** get 404 page
if someone else's event id is entered manually, then handle later


Not Authenticated: Signup, login
Authenticated: Create Society, logout, avatar(profile page)
After creating society, create society to not be shown