pipeline {
    agent any
    environment {
	PATH = '/opt/maven/bin'
    }
    stages {
        stage ('build') {
	    steps {
	        sh 'maven clean install'
	    }
        } 
    }
}

