# 573-jenkinsfile1
Pipeline Project with jenkinsfile

pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
    }
}
