node {
    docker.image('maven').inside(''-v /root/.m2:/root/.m2'') {
        stage('Build') {
            sh 'mvn clean package'
        }

        stage('Test') {
            sh 'mvn test'
        }

    }
}
