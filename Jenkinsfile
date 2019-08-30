def GetMePath;
node
{
    stage('checggkout')
    {
        git credentialsId: 'Premcj', url: 'https://github.com/premcj/GitHubv1.git'
        GetMePath =pwd()
    }
    stage('Got my code')
    {
        echo GetMePath;
    }
}
