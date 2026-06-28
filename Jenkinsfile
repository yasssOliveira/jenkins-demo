stage('Build em Docker') {
    steps {
        bat '''
        docker run --rm ^
        -v "%WORKSPACE%":/workspace ^
        -w /workspace ^
        maven:3.9.9-eclipse-temurin-21 ^
        mvn clean compile
        '''
    }
}

stage('Testes em Docker') {
    steps {
        bat '''
        docker run --rm ^
        -v "%WORKSPACE%":/workspace ^
        -w /workspace ^
        maven:3.9.9-eclipse-temurin-21 ^
        mvn test
        '''
    }
}