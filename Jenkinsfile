node('built-in') 
{
    stage('Continuous Download_Master') 
	{
    git 'https://github.com/laxmanukadam/Jenkins_multiBranch22.git'
	}
    stage('Continuous Build_Master') 
	{
    sh label: '', script: 'mvn package'
	}
}
