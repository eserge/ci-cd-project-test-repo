#!/usr/bin/env groovy

pipeline {

    agent { docker { image 'python:3.12.1' } }
    stages {
        stage('Build') {
            steps {
                echo 'Building...'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing...'
            }
        }
    }
}
