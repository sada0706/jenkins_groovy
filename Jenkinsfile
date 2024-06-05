// Jenkinsfile
@Library('jenkins-library') _

pipeline {
    agent any
    stages {
        stage('Example') {
            steps {
                script {
                    exampleVar('World')
                    def exampleStep = new org.jenkinsci.plugins.ExampleStep(this)
                    exampleStep.greet('World')
                }
            }
        }
    }
}
