node('master') 
{
    stage('Continuous Download') 
	{
    git 'https://github.com/harshasri-del/maven.git'
	}
    stage('Continuous Build') 
	{
    sh label: '', script: 'mvn package'
	}
}
