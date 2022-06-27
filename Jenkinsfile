pipeline {

agent any

stages {

stage('Build') {

steps {


  bat 'javac Prime.java'
  bat 'java -version'

}

}

stage('Run') {

steps {


  bat 'java Prime'
}
}
}
}
