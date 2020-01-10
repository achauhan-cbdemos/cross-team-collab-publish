pipeline {
    agent any

    stages {
        stage('Npm Example') {
            steps {
                echo 'new npm package got published'
                publishEvent simpleEvent('cloudbees-js@1.0.0')
            }
        }
    }
}
