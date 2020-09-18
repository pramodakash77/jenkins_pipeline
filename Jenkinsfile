pipeline {
	agent none

	stages {
		parallel {
		stage ('c_code') {
			agent { label 'node1' }
			steps {
			  	git 'https://github.com/pramodakash77/c_code.git'
					sh 'make'
				echo 'This is slaveforc node with STAGE 1'
						sh 'sleep 10'
			}
		}
		stage ('Java Project') {
			agent { label 'node2' }
			steps {
				git 'https://github.com/pramodakash77/java_code.git'
				sh 'mvn clean install'
			}
		}
		
		}	
	}
}
