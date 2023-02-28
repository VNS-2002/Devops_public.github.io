pipeline {
    agent any

    stages {
        stage('Git') {
            steps {
                git 'https://github.com/VNS-2002/Devops_public.git'
                bat 'javac hello.java'
                bat 'java hello'
                
                
            }
        }
    }
        
    
}
