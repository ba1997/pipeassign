pipeline {
	agent none 
	stages {
		stage('Build') { 
			agent { label 'master' }
			steps {
				sh 'https://github.com/ba1997/assign1.git'
			}
		}
