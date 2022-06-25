pipeline {
	agent none
	options {
		timeout(60)
		timestamps()
		ansiColor('css')
	}
	stages {
		stage ('Build Docker Image') {
		  agent { label 'docker-linux' }
			steps {
				echo("Hello from the custom container")
			}
		}
	}
}
