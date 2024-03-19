pipeline {
    agent any

    stages {
        stage('Check mi_nginx_nuevo Connection') {
            steps {
                sh "curl -IsS http://desktop_mi_nginx_nuevo_1:80"
            }
        }
        stage('Check sonarqube2 Connection') {
            steps {
                sh "curl -IsS http://desktop_sonarqube2_1:9000"
            }
        }
        stage('Check confident_shamir Connection') {
            steps {
                sh "curl -IsS http://desktop_confident_shamir_1:80"
            }
        }
        stage('Check wonderful_goldberg Connection') {
            steps {
                sh "curl -IsS http://desktop_wonderful_goldberg_1:80"
            }
        }
        stage('Check nginx Connection') {
            steps {
                sh "curl -IsS http://desktop_nginx_1:80"
            }
        }
    }
}

