pipeline {
    agent any

 

    stages {
        stage('Cloning') {
            steps {
                
                git branch: 'Devlop', url: 'https://github.com/sumit-mishra27/jenkins-assignment-1.git'

           
                sh " cp /var/lib/jenkins/workspace/jenkins-assignment-1/* /root/jenkinsAssignment-1"

            }

        }
    }
}