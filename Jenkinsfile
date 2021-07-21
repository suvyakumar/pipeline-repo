pipeline {
			agent any  
			stages {
				stage('STAGE1') {	
					when {
						branch 'main' 
					}
					         steps {
							sh '''
							echo "Build is running"
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






