pipeline {
    agent any
    stages {
        stage('git repo & clean') {
            steps {
               /*bat "rmdir  /s /q TicketBookingServiceJunitTesting"
                bat "git clone https://github.com/kishancs2020/TicketBookingServiceJunitTesting.git"
                bat "mvn clean -f TicketBookingServiceJunitTesting"*/
                echo "Start"
            }
        }
        stage('install') {
            steps {
                //bat "mvn install -f TicketBookingServiceJunitTesting"
                echo "Instal"
            }
        }
        stage('test') {
            steps {
               // bat "mvn test -f TicketBookingServiceJunitTesting"
                echo "Test"
            }
        }
        stage('Build') {
            steps {
                //bat "mvn package -f TicketBookingServiceJunitTesting"
                echo "Build"
            }
        }
    }
}
