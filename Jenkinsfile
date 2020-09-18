pipeline {
	agent { label 'changed_slave' }
 
	stages {
		stage ('STAGE 1') {
			steps {
				echo 'This is slaveforc node with STAGE 1'
				sh 'sleep 10'
			}	
		}
		stage ('STAGE 2') {
			steps {
				echo 'This is slaveforjava with STAGE 2'
				sh 'sleep 10'
			}	
		}
		stage ('STAGE 3') {
			steps {
				echo 'This is slaveforc with STAGE 3'
				sh 'sleep 10'
			}	
		}
		stage ('STAGE 4') {
			steps {
				echo 'This is master with STAGE 4'
				sh 'sleep 10'
			}	
		}
	}
}
