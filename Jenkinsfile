pipeline {
    agent any
    tools{
        jdk "jdk"
    }

    stages {
        stage('Build') {
            steps {
                // Assuming your Java file is in the root of the repository
                sh 'java HelloWorld.java'
            }
        }
        
    }
}


