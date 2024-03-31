# capstone-project-1-DevOps

You have been hired as a Sr. DevOps Engineer in Abode Software. They want to
implement DevOps Lifecycle in their company. You have been asked to
implement this lifecycle as fast as possible. Abode Software is a product-based
company and their product is available on this GitHub link.
https://github.com/MiksVeg/DevOPs-Project.git

**Following are the specifications of the lifecycle:**
1. Install the necessary software on the machines using a configuration
   management tool
2. Git workflow has to be implemented
3. CodeBuild should automatically be triggered once a commit is made to master branch or develop branch.
a. If a commit is made to master branch, test and push to prod
b. If a commit is made to develop branch, just test the product, do not push to prod
4. The code should be containerized with the help of a Dockerfile. The Dockerfile should be built every time there is a push to GitHub.
5. Use the following pre-built container for your application: hshar/webapp
   The code should reside in '/var/www/html'
6. The above tasks should be defined in a Jenkins Pipeline with the following


**jobs:**
a. Jobl : build
b. Job2 : test
c. Job3 : prod
