pipeline {
    agent any

    stages {
        stage('Example') {
            steps {
                echo 'sending helloWorld'
                publishEvent event:jsonEvent('{"eventName":"helloWorld"}'), verbose: true
            }
        }
    }
}
