pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                script {
                    echo 'Hello World'
                    sh "docker ps"
                    sh 'echo "FROM hello-world" > Dockerfile'
                    docker.build("hello")
                    sh "docker image ls"
                }
            }
        }
    }
}
