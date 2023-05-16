pipeline {
    agent any
    environment {
        APP = "testing-passport"
        DATE = "${sh(script:'date +%d-%m-%Y_%H_%M', returnStdout: true).trim()}"
    }
    stages {
        stage('TEST JOB'){

            steps {
                sh "echo test ${APP} ${Date} "
            }
        }
    }
}
