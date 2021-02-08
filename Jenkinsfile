node {
    stage('Clone') {
        git credentialsId: '3d541dbc-360a-401d-b780-4e7a5964daaf', url: 'https://github.com/KingRulian/hello-world-java.git'
    }
    stage('Build') {
        sh '''
        javac HelloWorld.java
        '''
    }
    stage('Run') {
        sh '''
        java HelloWorld
        '''
    }
}
