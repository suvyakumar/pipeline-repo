pipeline {
			agent none  
			stages {
				stage('BUILD') {
					parallel{
						stage('BUILD1') {
							agent {label 'label1'}
					         steps {
						sh '''
							pwd
							sleep 5
							echo This is the fist stage: BUILD
						'''
					}	
				}
						stage('BUILD2') {
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
}






