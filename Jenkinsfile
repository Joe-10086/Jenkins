pipeline{
    agent any
    stages{
        stage("Build"){
            steps{
                echo "Building......."
            }
            post{
                success{
                    mail to: "f95656910@gmail.com",
                    subject: "Build status email",
                    body: "Build was successfull"
                }
            }
        }
    }
}
