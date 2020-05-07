pipeline {
    agent any

    tools {
        maven "Maven 3.6.3"
    }

    stages {
        stage('Example') {
           steps{
              // Run the maven build
              sh "Hello world"
           }
        }
    }
    post {
        always {
            echo "toujours hello"
        }
    }
}
