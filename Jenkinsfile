pipeline {
    agent {
    docker {
            image 'python:latest'
        }
    }
    stages {

        stage('Build') {
            steps {
                echo "fffkukuku"
                script {
                    sh 'python -m py_compile sources/add2vals.py sources/calc.py'
                }
            }
        }

        stage('Test') {

            steps {
                sh 'py.test --verbose --junit-xml test-reports/results.xml sources/test_calc.py'
            }
            post {
                always {
                    junit 'test-reports/results.xml'
                }
            }
        }
    }
}