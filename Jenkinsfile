env.DOCKER_REGISTRY = 'raxer'
pipeline {
    agent any 
    stages {
        stage('Hello World') { 
            steps {
                sh "whoami"
            }
        }
        stage('Get File Github') { 
            steps {
                sh "echo $DOCKER_REGISTRY"
            }
        }
    }
}
