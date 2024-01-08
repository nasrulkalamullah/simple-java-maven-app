node {
    docker.image('maven:3.9.0') {
        stage('Build') {
            sh 'mvn clean package'
        }

        stage('Test') {
            sh 'mvn test'
        }

    }
}
