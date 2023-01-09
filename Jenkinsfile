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
				sh 'cd mysql-container'
				sh 'docker-compose up -d'
			}
		}
	}
}
