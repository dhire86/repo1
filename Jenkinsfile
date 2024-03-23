pipeline {
    agent any

    tools {
        // Install the Maven version configured as "M3" and add it to the path.
        maven "testmaven"
    }

    stages {
        stage('compilecodescm') {
            steps {
                echo " this is code compile for pipeline 4 through github"
            }
        }
    
    stage('Testunitscm') {
            steps {
                echo " this is code unit test for pipeline 4 through github"
            }
    }
    stage('Package4') {
            steps {
                echo " this is code  package for pipeline 4 through github"
            }
        }
    }
}
