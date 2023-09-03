pipeline{
      agent{ docker {image 'ubuntu'}}
      stages{
         stage{   
        steps('build')
              {
                sh 'git --version'
              }
             }
}
}
