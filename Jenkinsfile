pipeline{
	agent any
	stages {
		stage('Checkout'){
			steps {
				checkout scm
			}
		}
		stage('Build') {
			steps {
				bat 'start mvn clean package'
			}
		}
	}
}