

node('master')

{

stage('ContinuousDownload_master')
         {
git 'https://github.com/saba728/maven.git'
}

stage('Continuousbuild_master')
         {
   sh label: '', script: 'mvn package'
        }
}
