

node('master')

{

stage('ContinuousDownload_master')
         {
git 'https://github.com/saba728/jenkins_multibranch.git'
}

stage('Continuousbuild_master')
         {
   sh label: '', script: 'mvn package'
        }
}
