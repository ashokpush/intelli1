
node('master') 
{
    stage('ContinuousDownload-master') 
    {
        git 'https://github.com/ashokpush/intelli1.git'
    }
    stage('ContinuousBuild-master') 
    {
        sh 'mvn package'
    }
   
}

    
