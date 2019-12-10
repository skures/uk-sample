// Declarative //
pipeline {
    agent { label 'shared-agent' } 

    stages {
        stage('Example') {
            steps {
                echo 'sending helloWorld'
                publishEvent simpleEvent('helloWorld')
            }
        }
    }
}
