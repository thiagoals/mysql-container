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
				sh 'docker-compose up -d'
			}
		}
	}
}
