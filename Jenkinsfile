pipeline {
			agent { label 'label1' }  
			stages {
				stage('BUILD') {
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

