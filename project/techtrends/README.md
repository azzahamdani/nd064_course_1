# TechTreds Web Application

This is a Flask application that lists the latest articles within the cloud-native ecosystem.

## Run 

To run this application there are 2 steps required:

1. Initialize the database by using the `python init_db.py` command. This will create or overwrite the `database.db` file that is used by the web application.
2.  Run the TechTrends application by using the `python app.py` command. The application is running on port `3111` and you can access it by querying the `http://127.0.0.1:3111/` endpoint.

# Step1 Best practice for application
[x] An existing article is retrieved. The title of the article should be recorded in the log line.
[x] A non-existing article is accessed and a 404 page is returned. 
[x] The "About Us" page is retrieved.
[x] A new article is created. The title of the new article should be recorded in the logline.
[x] healthz
[x] metrics

# Step2 Docker for Application Packaging
[x] Dockerfile
[x] Docker commands 
[x] Docker-Run-Local screenshot
