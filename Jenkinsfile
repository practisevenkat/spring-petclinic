node {
    stage('scm'){
        git 'https://github.com/practisevenkat/spring-petclinic.git'
    }
    stage('build'){
    sh 'mvn package'
    }
}