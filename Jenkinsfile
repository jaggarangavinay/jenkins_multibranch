node('builtin') 
{
    stage('Continuous Download_loans') 
	{
    git 'https://github.com/jaggarangavinay/maven.git'
	}
    stage('Continuous Build_loans') 
	{
    sh label: '', script: 'mvn package'
	}
   
}
