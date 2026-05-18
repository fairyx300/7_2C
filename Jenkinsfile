pipeline{
    agent any
    stages{
        stage('Build'){
            steps{
                echo 'Building with Maven...'
            }
        }
        stage('Unit and Integration Tests'){
            steps{
                //https://www.practitest.com/resource-center/blog/best-unit-testing-tools/
                echo 'Unit Testing with xUnit.net ...'
                //https://testomat.io/blog/integration-testing-tool/
                echo 'Integration Testing with JMeter...'
            }
        }
        stage('Code Analysis'){
            steps{
                //https://cycode.com/blog/top-10-code-analysis-tools/
                echo 'Analyzing code with SonarQube...'
            }
        }
        stage('Security Scan'){
            steps{
                //https://www.endorlabs.com/learn/best-code-security-tools
                echo 'Scanning for vulnerabilities with Snyk...'
            }
        }    
        stage('Deploy to Staging'){
            steps{
                echo 'Deploying to staging environment with AWS EC2...'
            }
        }
        stage('Integration Tests on Staging'){
            steps{
                //https://medium.com/@crissyjoshua/how-to-run-automated-tests-on-staging-websites-without-breaking-your-release-cycle-3ae9916c77ba
                echo 'Running integration tests on staging with Selenium...'
            }
        }
        stage('Deploy to Production'){
            steps{
                echo 'Deploying to production environment with AWS EC2...'
            }
        }
        // test1
        
    }
}