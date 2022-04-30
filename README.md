# Event-management-system
Creation of the webpage for Event management system
import flask
website=flask.Flask("_name_")
@website.route("/")
def my_index_page():
    return  flask.render_template("loginpage.html")

@website.route("/register")
def registerform():
    return flask.render_template("register form.html")

if _name=="main_":
    website.run(port=3000)
