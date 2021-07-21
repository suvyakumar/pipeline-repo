pipeline {
			agent any  
			stages {
				stage('STAGE1') {						
					         steps {
							 catchError(buildResult="SUCCESS",stageResult="FAILURE") {
						sh '''
							pwd
							sleep 5
							exit 1
						'''
						 }	
				           }
				stage('STAGE2') {						
					         steps {
						sh '''
							echo stage2 is building
							sleep 5
							
						'''
						 }	
				           }
			}
}
						/*stage('BUILD2') {
							agent {label 'label2'}
					         steps {
						sh '''
							pwd
							sleep 5
							echo This is the fist stage: BUILD
						'''
					}	
				}				
				stage('TEST') {
					agent any
					steps {
						sh '''
							pwd
							sleep 5
							echo This is the fist stage: TEST
						'''
					}	
				}				
				stage('DEPLOY') {
					agent any
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
} */






