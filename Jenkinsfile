pipeline {
    agent { docker { image 'golang:1.23.4-alpine3.21' } }
    stages {
        stage('build') {
            steps {
                sh 'go version'
            }
        }

        stage('test') {
            steps {
                sh 'echo "executing test"'
            }
        }

        // stage('get the last tag'){
        //     steps {
        //         sh 'git tag --sort=-v:refname | head -n 1'
        //     }
        // }
    }
}