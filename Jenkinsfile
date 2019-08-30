def GetMePath;
node
{
    stage('chcgnout')
    {
        git credentialsId: 'Premcj', url: 'https://github.com/premcj/GitHubv1.git'
        GetMePath =pwd()
    }
    stage('Got my code')
    {
        echo GetMePath;
    }
}
