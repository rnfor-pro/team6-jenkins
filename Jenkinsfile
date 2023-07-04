pipeline {
	agent any 
		stages{
			stage('1-make a left'){
				steps{
				checkout scmGit(branches: [[name: '*/main']], extensions: [], userRemoteConfigs: [[credentialsId: 'github-creds', url: 'https://github.com/rnfor-pro/team6-jenkins.git']])
				}
			}
			stage('2-make a right'){
				steps{
					sh 'echo "walk..."'
				}
			}
			stage('3-make another left'){
				steps{
					sh 'echo "walk...."'
				}
			}
			stage('4-cross the street'){
				steps{
					sh 'echo "walk...."'
				}
			}
		}
}
