// Jenkinsfile for Java/Spring Application 


properties([
  parameters([
        string(name: 'Major Version', defaultValue: '0'),
		string(name: 'Minor Version', defaultValue: '0'),
		string(name: 'Patch Version', defaultValue: '0')
            ])
       ])

pipeline {
    agent any
    environment {
        SonarLogin = "test"
        SonarPassword = "test"
        tags_extra = "test"
    }
    stages {
        stage('Code Clean/lint') {
            steps {
                echo "tags_extra: ${tags_extra}"
            }
        }
        stage('Compile') {
            steps {
                echo "tags_extra: ${tags_extra}"
            }
        }
        stage('Test') {
            steps {
                echo "tags_extra: ${tags_extra}"
            }
        }
        stage('Code Coverage') {
            steps {
                echo "tags_extra: ${tags_extra}"
            }
        }
        stage('SonarQube Analysis') {
            steps {
                echo "tags_extra: ${tags_extra}"
            }
        }
        stage('Publish to Nexus') {
            steps {
                echo "tags_extra: ${tags_extra}"
            }
        }
        stage('Docker Push Image') {
            steps {
                echo "tags_extra: ${tags_extra}"
            }
        }
    }
    post {

        always {
            echo 'One way or another, I have finished'
          }
        success {
            echo 'I succeeeded!'
        }
        failure {
            echo 'I failed :('
        }
    }
}
