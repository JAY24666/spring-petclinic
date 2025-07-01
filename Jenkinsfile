pipeline{
    agent any

    stages {
        stage("Build"){
            steps {
                sh "./mvnw install"
                sh "ls -lrt target/*.jar"
            }
    }
}
}