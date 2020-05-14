//SCRIPTED
/*node {
	stage('Build') {
		echo "Build"
	}
	stage('Test') {
		echo "Test"
	}
	stage('Integration Test') {
		echo "Integration Test"
	}
}*/
//Declartive
pipeline{
	agent any
	stages {	
		stage ('Build'){
			steps {
				echo "Build"
				
			}
		}
		stage ('Test'){
			steps {
				
				echo "Test"
				
			}
		}
		stage ('Integration Test'){
			steps {
				echo "Integration Test"
			}
		}
	} post{
		always{
			echo 'Im awesome. I run always'
		}
		success{
			echo 'I run when you are successful'
		}
		always{
			echo 'i run when you fail'
		}
	}
}
