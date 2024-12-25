Jenkins 
https://github.com/jenkinsci/docker/blob/master/README.md
https://www.jenkins.io/doc/tutorials/tutorial-for-installing-jenkins-on-AWS/

docker pull jenkins/jenkins:lts-jdk17
docker run -d -v jenkins_home:/var/jenkins_home -p 8080:8080 -p 50000:50000 --restart=on-failure jenkins/jenkins:lts-jdk17
/var/jenkins_home/secrets/initialAdminPassword

Jenkins helm for kubernetes
https://github.com/jenkinsci/helm-charts
helm repo add jenkins https://charts.jenkins.io
helm repo update

jenkins pipeline : https://trainingportal.linuxfoundation.org/learn/course/introduction-to-jenkins-lfs167/pipeline-jobs/pipeline-jobs?page=18
                  https://www.jenkins.io/doc/book/pipeline/

Prometheus Monitoring: https://plugins.jenkins.io/prometheus/
