pipeline {
    agent any
    parameters {
        string(name: 'NAME', defaultValue: 'World', description: 'Person name')
    }
    stages {
        stage('Hello') {
            steps {
                echo "Hello ${params.NAME}!"
            }
        }
        stage('List all files') {
            steps {
              ls -a
            }
        }
    }
}
