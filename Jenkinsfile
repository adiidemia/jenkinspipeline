pipeline {
	agent any
	
	stages {
		stage ('Compile Stage') {
			steps {
				bat 'mvn clean install'
				echo 'compilation stage finished'
				}
			}
		stage ('Test Stage') {
			steps {
				bat 'mvn clean test'
				echo 'test stage finished'
				}
			}
	    }
	}
