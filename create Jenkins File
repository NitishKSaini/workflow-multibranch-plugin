pipeline {
    agent any
    tools {
        maven 'MAVEN'
    }
    stages {
      stage ("bulid") {
            steps
                  {
                    sh "mvn -B -DskipTests clean package"
                }

        }

    }

}
