pipeline {
    agent any
    tools{
        JDK "jdk"
        Maven "mvn"
    }

    stages {
        stage('deploy project') {
            steps {
                sh '''
                mvn --version
                java --version
               mvn clean install 
               mvn deploy
            '''
}
}

}
}
