node {
    stage 'Checkout'

    checkout scm

    stage 'echo-stage'
    echo "welcome to jenkins-test"
    
    def test_value = 'ole'

    stage 'test-value test'
    echo "My value is ${test_value}"

    
    stage 'END'

    echo "End task"
}    
