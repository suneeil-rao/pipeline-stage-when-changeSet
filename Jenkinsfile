pipeline{
    agent any

    stages{
        stage('Build'){
            when{
                       changeSet glob: "*.js"
                }
            steps{
                 echo "########### Hello world Change Set *.js file"
            }
        }
    }
}

