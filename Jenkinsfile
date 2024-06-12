
pipeline {

	agent any
	tools {
		maven 'maven'
		jdk 'jdk_17'
	}
	stages {
		stage('Build') {
			steps {
				sh 'mvn -B -DskipTests clean package'
			}
		}
	}
}
