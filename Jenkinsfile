node('master') 
{
    stage('Continuous Download_loans') 
	{
    git 'https://github.com/harshasri-del/maven.git'
	}
    stage('Continuous Build_loans') 
	{
    sh label: '', script: 'mvn package'
	}
    
}
