pipeline {
    agent any
    tools{
        jdk "jdk"
        maven "mvn"
    }

    stages {
        stage('deploy project') {
            steps {
                 sh 'echo $JAVA_HOME'
                sh '''
                 
                java --version
                mvn --version
               
               mvn clean install 
               mvn deploy
            '''
}
}

}
}
