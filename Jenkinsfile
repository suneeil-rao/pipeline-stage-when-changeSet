pipeline{
    agent any

    stages{
        stage('Build'){
            when{
                       changeset glob: "*.js"
                }
            steps{
                 echo "########### Hello world Change Set *.js file"
            }
        }
    }
}

