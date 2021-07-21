pipeline {
			agent any  
			stages {
				stage('BUILD') {
					parallel{
						stage('BUILD1') {
					         steps {
						sh '''
							pwd
							sleep 5
							echo This is the fist stage: BUILD
						'''
					}	
				}
						stage('BUILD2') {
					         steps {
						sh '''
							pwd
							sleep 5
							echo This is the fist stage: BUILD
						'''
					}	
				}				
				stage('TEST') {
					
					steps {
						sh '''
							pwd
							sleep 5
							echo This is the fist stage: TEST
						'''
					}	
				}				
				stage('DEPLOY') {
					
					steps {
						sh '''
							pwd
							sleep 5
							echo This is the fist stage: DEPLOY
						'''
					}	
				}
			}
		}
}
}






