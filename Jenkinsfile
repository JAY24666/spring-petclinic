pipeline{
    agent any

    stage{
        stage("Build"){
            steps {
                sh "./mvnw install"
                sh "ls -lrt target/*.jar"
            }
    }
}
}