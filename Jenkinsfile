pipeline {
	agent { label 'master' }
 
	stages {
		stage ('c_code') {
			steps { 
				build 'c_PROGRAME'
				//*echo 'This  slaveforc node with STAGE 1'
				//sh 'sleep 10'
			}	
		}
		stage ('java_code') {
			steps {
				build 'java_programe'
				//echo 'This  slaveforjava with STAGE 2'
				//sh 'sleep 10'
			}	
		}
		/*stage ('STAGE 3') {
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
		}*/
	}
}
