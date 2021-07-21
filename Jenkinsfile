pipeline {
			agent any  
	parameters {
		choice(name: 'TARGET_ENV', choice: ['test','prod'], description: 'target environment to deploy')
						   }
						   environment {
							   DEPLOY_TO = "${TARGET_ENV}"
						   }
						   stages {
							   stage('DEPLOY_TEST') {
								   when 
								   {
									   environment name: 'DEPLOY_TO', value: 'test'
								   }
								   steps {
									   echo "DEPLOY TO TEST ENVIRONMENT"
									   sh 'sleep 5'
								   }
							   }
							   stage('DEPLOY_PROD') {
								   when 
								   {
									   environment name: 'DEPLOY_TO', value: 'prod'
								   }
								   steps {
									   echo "DEPLOY TO PRODUCTION ENVIRONMENT"
									   sh 'sleep 5'
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






