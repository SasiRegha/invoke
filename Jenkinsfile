@Library('jenkins-library@testbranch') _
my-shared-library@master

pipeline
{
	agent any 
	stages
	{
		stage('from jenkinsfile')
		{
			steps
			{
				echo "from jenkinsfile..."
			}
		}
		stage('from lib')
		{
			steps
			{
				fromLibarary()
				print()
			}
		}
	
	}
}
