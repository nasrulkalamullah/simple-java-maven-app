node {
    docker.image('maven:3.9.0').inside('-v /root/.m2:/root/.m2') {
        stage('Build') {
            sh 'mvn clean package'
        }

        stage('Test') {
            sh 'mvn test'
        }

    }
}
