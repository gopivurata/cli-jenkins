pipeline {
    agent  { label 'NODE' }
    
    stages {
        stage('git') {
            steps {
               git branch: 'main', url: 'https://github.com/gopivurata/cli-jenkins.git'
            }

        }
        stage('sh file run') {
            steps {
                sh './cli-ec2.sh'
            }

        }
        
     }
     

}