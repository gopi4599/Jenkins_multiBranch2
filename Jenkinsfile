node('master') 
{
    stage('Continuous Download_loans') 
	{
    git 'https://github.com/sunildevops77/maven.git'
	}
    stage('Continuous Build-Loans') 
	{
    sh label: '', script: 'mvn package'
	}
