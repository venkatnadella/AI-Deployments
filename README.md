# AI-Deployments
Will be deploying some simple AI applications as per our Assignments in Deployment of AI Solutions course.

**•	Overview of the project**
  a simple machine learning application, containerized using Docker, and deployed on GitHub. This exercise will help you understand the principles of   
  containerization, version control, and basic machine learning application development.



**•	Instructions to build and run the Docker container**

  #initially make a local repo of this git repository. 

  Then Build the Docker image with the following command:
  sudo docker build -t ml-app . 

  Next Run the Docker container with the following command:
  sudo docker run -p 4000:80 ml-app 

  you can now open your browser and navigate to http://localhost:4000 to see the running application.



**•	Instructions to test the ML endpoint**

   Test the /predict endpoint using curl or Postman by sending a POST request with JSON data:
   curl -X POST http://localhost:4000/predict -H "Content-Type: application/json" -d '{"input": [5.1, 3.5, 1.4, 0.2]}
   {"input": [5.1, 3.5, 1.4, 0.2]} are the inputs. 

  

**•	Any other relevant information about the project**

    Apart from these, it could be benificial if you personally research on iris dataset and learn how machine learning algorithms work. 

The End. 
Thank you!
