pipeline {
    agent any
    stages{
    stage ('sample1'){
        steps{
        echo 'Building...'
        bat 'python part1.py'
            }
    }
    stage ('sample2'){
        steps{
        echo 'Using maven'
        bat 'mvn package'
        }
    }
}
}
