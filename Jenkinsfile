pipeline {
    //Can Run master or Slave
    agent: any

    stages {
        stage('build') {
            sh 'ant -f build.xml -v'
        }
    }
}
