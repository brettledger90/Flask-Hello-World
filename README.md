part 1
How to use:

Clone repo
run command "$ flask run"
go to server
------------------------------------------------------------
part 2
investigated how the Jinja2 Templating Engine works in Flask.  I explored template inheritance as well.

Create new mock users 
use render_template() to render the specified content
create conditionals and loops to help direct
implement template inheritance
-------------------------------------------------------------
part 3 
included from each section in the tutorial: | Introduction to Flask-WTF └`flask-wtf` is installed, imported, and used in app/forms.py | Configuration └ config.py exists and is home to a class named Config. └app.config.from_object() is used to import Config in app/__init__.py | User Login Form └ app/forms.py exists and is home to the LoginForm class. └ LoginForm inherits from FlaskForm └ LoginForm has the following attributes: username, password, remember_me, submit └ StringField, PasswordField, BooleanField, SubmitField are imported from `wtforms` . | Form Templates └app/templates/login.html contains code from tutorial | Form Views └app/routes.py contains code from tutorial for login route └app/templates/base.html contains anchor tag for "login/" endpoint | Receiving Form Data └app/routes.py contains updated logic for receiving form data in login view. └app/templates/base.html contains code to accommodate flashed messages | Improving Field Validation └app/templates/login.html contains code for logic for displaying error messages on form | Generating Links └app/templates/base.html adapted to use `url_for()` └app/routes.py adapted to use `url_for()`


