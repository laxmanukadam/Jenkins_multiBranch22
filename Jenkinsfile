node('built-in') 
{
    stage('Continuous Download_Dev') 
	{
    git 'https://github.com/laxmanukadam/Jenkins_multiBranch22.git'
	}
    stage('Continuous Build_Dev') 
	{
    sh label: '', script: 'mvn package'
	}
}
