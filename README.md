Task Description:
💢Job1 :- If a Developer pushes their code to dev1 branch then Jenkins will fetch from dev1 and deploy on dev1_docker environment.
💢Job2 :- If Developer push to master branch then Jenkins will fetch from master and deploy on master_docker environment.
💢Job3 :- Jenkins will check (test) for the website running in the dev1_docker environment. If it is running fine then Jenkins will merge the dev1 branch to master branch and trigger JOB#2.