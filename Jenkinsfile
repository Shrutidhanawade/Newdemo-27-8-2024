pipeline {
    agent any
    tools{
        jdk "jdk"
        maven "mvn"
    }

    stages {
        stage('deploy project') {
            steps {
                 withEnv(["JAVA_HOME=/usr/lib/jvm/java-17-openjdk-amd64"]) {
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
}
