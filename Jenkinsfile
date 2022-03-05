node('ubuntu') {
    
    stage('vcs') {
        git 'https://github.com/PJWesley7/Sample_jenkins_file.git'
    }
    
    stage('package') {
        sh 'mvn package'
    }
    
}
