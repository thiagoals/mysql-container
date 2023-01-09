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
				sh 'cd mysql-container'
				sh 'docker-compose up -d'
			}
		}
	}
}
