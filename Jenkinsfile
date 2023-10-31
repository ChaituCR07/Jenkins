pipeline{
	agent any
	stages {
		stages('Checkout'){
			steps {
				checkout scm
			}
		}
		stages {
			steps {
				bat 'start mvn clean package'
			}
		}
	}
}