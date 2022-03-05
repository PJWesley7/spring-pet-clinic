node('ubuntu') {
    
    stage('vcs') {
        git 'https://github.com/PJWesley7/spring-pet-clinic.git'
    }
    
    stage('package') {
        sh 'mvn package'
    }
    
}
