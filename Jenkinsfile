node {
    // some block
    stage('build') {
    // some block
        git branch: 'main', url: 'https://github.com/ahmedahdarf/MonPremierProjetJava.git'
   // sh '''javac src/Main.java&&  cd src && java Main'''
    }
    stage('run') {
        sh '''javac src/Main.java&&  cd src && java Main'''
    }
}