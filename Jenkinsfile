pipeline {
    agent any
    tools {
        maven 'MAVEN'
    }
    stages {

        stage ("git Checkout") {
            steps {
                git branch:'master', url:"${git_url}"
            }
        }
        stage ("bulid") {
            steps
                  {
                    sh "mvn -B -DskipTests clean package"
                }

        }

    }

}
