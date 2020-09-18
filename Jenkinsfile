pipeline {
	agent { label 'master' }
 
	stages {
		stage ('makefile') {
			steps { 
				build 'c-project'
				//*echo 'This is slaveforc node with STAGE 1'
				//sh 'sleep 10'
			}	
		}
		stage ('maven') {
			steps {
				build 'job2'
				//echo 'This is slaveforjava with STAGE 2'
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
