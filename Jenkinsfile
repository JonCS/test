node('node') {
    currentBuild.result = "SUCCESS"

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                sh javac Test.java
                sh java Test Jonathan 12
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
