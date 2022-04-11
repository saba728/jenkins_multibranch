node('master')

{

stage('ContinuousDownload_loans')
         {
    git 'https://github.com/saba728/maven.git'
        }

stage('Continuousbuild_loans')
         {
   sh label: '', script: 'mvn package'
        }

}
