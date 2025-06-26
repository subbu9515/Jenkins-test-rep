pipeline {
    agent any

    parameters {
      choice choices: ['dev', 'prod'], name: 'test'
    }


    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                echo env.test
                sh 'env'
                sh 'cat test.txt'
            }
        }
    }
}
