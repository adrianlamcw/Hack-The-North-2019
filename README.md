Hack the North: SurveyMonkey’s API Challenge Winner
Project Name: Just-Your-Feedback

Video of project
https://www.youtube.com/watch?v=BxJxPFECzqQ

Project Summary:
Based on SurveyMonkey’s Developer API Challenge, our group has created a Machine Learning Model which can be utilized by end-users to automate the submission of Survey responses. The machine learning algorithm was imported using the ImageAI Python Library. Using this library, we were able to train the Machine Learning model using Supervised Learning with 500+ images. After several implementations and re-iterations, the model was able to recognize hand gestures from the user. Our live-demonstration displays a Survey for user's experience with Hack the North Hackathon. Based on the user's hand gesture response on the embedded webcam, an automated submission is made and recorded. 

Technologies Utilized:
Python, Pyramid (Web Framework), ImageAI (Python Library for Machine Learning Algorithms), JavaScript, HTML, CSS, JSON, SurveyMonkey's Developer API.

Developer Notes:
Activate the virtual environment by running `source pyenv/bin/activate` from the project root.
**NOTE: To leave a virtual environment, simply run `deactivate` from within the virtual enviroment.**

## Install Requirements
Run `pip install -e .`. This installs all the Python packages specified in the `setup.py` file.

## Run Waitress Server
Run `pserve development.ini --reload`. 
