node {
    docker.image('maven').inside('-p 3000:3000') {
        stage('Build') {
            sh 'mvn clean package'
        }

        stage('Test') {
            sh 'mvn test'
        }

    }
}
