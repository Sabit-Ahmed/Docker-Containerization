This repository contains the practice codes and files based on the Docker Handbook by Farhan Hasin Chowdhury. The Handbook link: https://www.freecodecamp.org/news/the-docker-handbook/
  
Resource links:
Docker Doc: https://docs.docker.com/
Docker Handbook: https://www.freecodecamp.org/news/the-docker-handbook/ 
Updated Handbook: https://docker.farhan.info/
Docker and Container basics: https://code.visualstudio.com/docs/remote/containers  
Containerization basics: https://developers.redhat.com/blog/2018/02/22/container-terminology-practical-introduction/  
Network between containers: https://www.digitalocean.com/community/questions/how-to-ping-docker-container-from-another-container-by-name?fbclid=IwAR3QlTN9ih4UQITQ-aK_DNcK6mP5SPkx_kVkJGQh5UrcxNyRzhsVNGgGxO4  
Creating git repositiory: https://gist.github.com/alexpchin/dc91e723d4db5018fef8  
  
*Problem: Docker desktop stopped working  
Solution: Enabling virtualization, checking if Hyper-V installed on windows. 
Solution links:  
https://docs.microsoft.com/en-us/virtualization/hyper-v-on-windows/quick-start/enable-hyper-v  
https://support.hp.com/us-en/document/bph07110  
  
*Problem: Absolute path when running Docker  
Possible solutions for windows: 
*//c/user/rest_of_the_path (Using lowercase and escape)  
*%cd% (when using cmd)  
*${PWD} (when using powershell) 
Solution links:  
https://stackoverflow.com/questions/40213524/using-absolute-path-with-docker-run-command-not-working  
https://stackoverflow.com/questions/7250130/how-to-stop-mingw-and-msys-from-mangling-path-names-given-at-the-command-line#34386471  
  
*Problem: File sharing is off:  
solution and explanation: possibly the docker desktop gui app has been updated. There is a option called file sharing. The files of a particular directory must be shared. Otherwise the container will not be run using the host machine. That means containers will not be able access host machine resource.  
The file sharing option might not be there for some other variant of the docker desktop app. Need to figure out properly. There is WSL2 option instead of file sharing.  
According to Docker Docs : "The File sharing tab is only available in Hyper-V mode, because in WSL 2 mode and Windows container mode all files are automatically shared by Windows."  
Solution links:  
https://stackoverflow.com/questions/62045513/docker-run-rm-v-getting-error-response-from-daemon-status-code-not-ok-but  
https://docs.docker.com/docker-for-windows/#file-sharing  
  
*Problem: Docker desktop GUI is not opening though it runs on the background.  
  

*Problem: Git pull and push  
Solution links:  
https://stackoverflow.com/questions/18588974/git-prevents-pushing-after-amending-a-commit  
https://docs.github.com/en/github/using-git/dealing-with-non-fast-forward-errors  
https://stackoverflow.com/questions/24357108/git-updates-were-rejected-because-the-remote-contains-work-that-you-do-not-have  
https://docs.github.com/en/github/using-git/pushing-commits-to-a-remote-repository

  
*Problem: Adding Linebreaks in README.md  
Solution links: https://stackoverflow.com/questions/24575680/new-lines-inside-paragraph-in-readme-md  

  
*Problem: OCI runtime exec failed: exec failed: container_linux.go:344: starting container process  
Solution: install ping package to a certain directory with bash command-line#34386471  
Solution links:  
https://stackoverflow.com/questions/55378420/oci-runtime-exec-failed-exec-failed-container-linux-go344-starting-container

    
*Problem: denied: requested access to the resource is denied : docker  
Sloution links: https://stackoverflow.com/questions/41984399/denied-requested-access-to-the-resource-is-denied-docker


Kubernetes Handbook: https://www.freecodecamp.org/news/the-kubernetes-handbook/#installing-kubernetes 
Managing MongoDB on docker with docker-compose: https://medium.com/faun/managing-mongodb-on-docker-with-docker-compose-26bf8a0bbae3 
Run Docker containers with Azure Container Instances (Microsoft Course): Run Docker containers with Azure Container Instances 
Deploying Docker containers on Azure: Deploying Docker containers on Azure: https://docs.docker.com/cloud/aci-integration/ 
Simple App with Flask, SQLAlchemy and Docker: https://hmajid2301.medium.com/implementing-sqlalchemy-with-docker-cb223a8296de 
Dockerizing a Flask-MySQL app with docker-compose: https://medium.com/@shamir.stav_83310/dockerizing-a-flask-mysql-app-with-docker-compose-c4f51d20b40d 
Deploy and Secure a React — Flask App With Docker and Nginx: https://medium.com/swlh/deploy-and-secure-a-react-flask-app-with-docker-and-nginx-768ca582863b 
Microsoft Courses for Data Science: https://docs.microsoft.com/en-us/learn/browse/?products=azure%2Cdynamics-365%2Cm365%2Cpower-platform&roles=business-owner 


Farhan Hasin Chowdhury (GitLab): https://gitlab.com/fhsinchy 
Data Science: https://datasinsightsbd.gitbook.io/dsbook/domain-knowledge