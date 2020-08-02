# task3
CI/CD automation using kubernetes 
https://medium.com/@manishdwarkas912/ci-cd-automation-using-jenkins-in-kubernetes-pod-e284f4c7c6d0?sk=aa847bdab251c0618738691b174fc3ac
1.Create container image that’s has Jenkins installed using docker file Or You can use the Jenkins Server on RHEL 8/7
2. When we launch this image, it should automatically start the Jenkins service in the container.
3. Create a job chain of job1, job2, job3 and job4 using build pipeline plugin in Jenkins
4. Job1: Pull the Github repo automatically when some developers push the repo to Github.
5. Job2 :
1. By looking at the code or program file, Jenkins should automatically start the respective language interpreter installed image container to deploy code on top of Kubernetes ( eg. If code is of PHP, then Jenkins should start the container that has PHP already installed )
2. Expose your pod so that testing team could perform the testing on the pod
3. Make the data to remain persistent ( If server collects some data like logs, other user information )
6. Job3: Test your app if it is working or not.
7. Job4: if the app is not working, then send email to the developer with error messages and redeploy the application after code is being edited by the developer
checkout the above medium for full solution
