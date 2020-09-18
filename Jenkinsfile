pipeline {
	agent none 
 
	stages {
		stage ('STAGE 1') {
			agent { label 'slaveforc' }
			steps {
				echo 'This is slaveforc with STAGE 1'
				sh 'sleep 10'
			}	
		}
		stage ('STAGE 2') {
			agent { label 'slaveforjava' }
			steps {
				echo 'This is slaveforjava with STAGE 2'
				sh 'sleep 10'
			}	
		}
		stage ('STAGE 3') {
			agent { label 'slaveforc' }
			steps {
				echo 'This is slaveforc with STAGE 3'
				sh 'sleep 10'
			}	
		}
		stage ('STAGE 4') {
			agent { label 'master' }
			steps {
				echo 'This is master with STAGE 4'
				sh 'sleep 10'
			}	
		}
	}
}
