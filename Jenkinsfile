// Declarative //
pipeline {
    agent { 'shared-agent' } 

    stages {
        stage('Example') {
            steps {
                echo 'sending helloWorld'
                publishEvent simpleEvent('helloWorld')
            }
        }
    }
}
