FlaskIntroduction
This repo has been updated to work with Python v3.8 and up.

How To Run
Install virtualenv:
$ pip install virtualenv
Open a terminal in the project root directory and run:
$ virtualenv env
Then run the command:
$ .\env\Scripts\activate
Then install the dependencies:
$ (env) pip install -r requirements.txt
Finally start the web server:
$ (env) python app.py
This server will start on port 5000 by default. You can change this in app.py by changing the following line to this:

if __name__ == "__main__":
    app.run(debug=True, port=<desired port>)
Contributing
Since this is a repository for a tutorial, the code should remain the same as the code that was shown in the tutorial. Any pull requests that don't address security flaws or fixes for language updates will be automatically closed. Style changes, adding libraries, etc are not valid changes for submitting a pull request.
