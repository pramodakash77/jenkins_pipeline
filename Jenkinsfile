pipeline {
	agent none 
 
	stages {
		stage ('STAGE 1') {
			agent { label 'slaveforc' }
			steps {
				sh 'sleep 10'
			}	
		}
		stage ('STAGE 2') {
			agent { label 'slaveforjava' }
			steps {
				sh 'sleep 10'
			}	
		}
		stage ('STAGE 3') {
			agent { label 'slaveforc' }
			steps {
				sh 'sleep 10'
			}	
		}
		stage ('STAGE 4') {
			agent { label 'master' }
			steps {
				sh 'sleep 10'
			}	
		}
	}
}
