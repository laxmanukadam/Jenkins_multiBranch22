node('built-in') 
{
    stage('Continuous Download_Dev') 
	{
    git 'https://github.com/sunildevops77/maven.git'
	}
    stage('Continuous Build_Dev') 
	{
    sh label: '', script: 'mvn package'
	}
}
