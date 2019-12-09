# appengine
Google cloud app engine learning using python
Create project if not already created.
git clone https://github.com/Elayaraja-Dhanapal/appengine.git
cd appengine
#If you want test the app with virtual environment
#virtualenv --python python3 ~/envs/hello_world
#source ~/envs/hello_world/bin/activate
#pip install -r requirements.txt
#python main.py

gcloud app create
#No need to specify if you have already selected the project
gcloud app deploy app.yaml --project <project-name>
