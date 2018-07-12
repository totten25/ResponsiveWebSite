pipeline {
  agent any
  stages {
    stage('Clone repository') {
      steps {
        svn 'https://128.1.0.52/svn/DSCI/tags-build/$svn_ins_version/@wealth'
      }
    }
  }
}