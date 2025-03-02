pipeline {
	agent any
	stages {
		stage ('Build')
		{
		steps {
			sh ''' sleep 5 '''
		}
		}
		stage ('Test')
		       {
			       steps {
				       sh ''' sleep 5'''
			       }
		       }
		       stage ('Deploy')
		       {
			       steps{
				       sh ''' echo "This is a Deploy Stage" '''
			       }
		       }
		       stage('My-stage')
		       {
			       steps{
			       }
		       }
	}
}	
	
