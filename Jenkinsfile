pipeline{
	agent any
	stages {
		stage ('Logger'){
			steps{
				echo '---- MySQL Container ----'
			}
		}
		stage ('Docker compose'){
			steps{
				sh 'ls -l'
				sh 'docker -v'
			}
		}
	}
}
