pipeline {
agent any


stages {
stage('Checkout') {
steps {
checkout scm
}
}


stage('Build & Package') {
steps {
bat 'mvn clean package'
}
}
}
}