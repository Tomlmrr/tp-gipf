pipeline {
  agent any

node {
  withGradle {
    sh './gradlew' -D https.proxyHost=proxy1-rech -D https.proxyPort=3128
