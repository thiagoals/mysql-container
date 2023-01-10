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
				sh 'sudo docker compose up -d'
			}
		}
	}
}
