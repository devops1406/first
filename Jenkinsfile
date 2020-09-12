pipeline {
  agent {
    node {
      label 'node2'
    }

  }
  stages {
    stage('Stage 1') {
      parallel {
        stage('Stage 1') {
          steps {
            echo 'This Stage 1'
          }
        }

        stage('Par. Stage1') {
          steps {
            echo 'Pralled to Stage1'
          }
        }

        stage('Pare STge1') {
          steps {
            echo 'Paralled Stafe'
          }
        }

      }
    }

    stage('Stage 2') {
      steps {
        echo 'This is stage 2'
      }
    }

    stage('Stage 3`') {
      steps {
        echo 'Sateg 3'
      }
    }

  }
  environment {
    MyName = 'Chetan'
  }
}