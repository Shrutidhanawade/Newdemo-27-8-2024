pipeline {
    agent any
    tools{
        jdk "jdk"
        maven "mvn"
    }

    stages {
        stage('deploy project') {
            steps {
                sh '''
               mvn clean install 
               mvn deploy
            "
}
}

}
}
