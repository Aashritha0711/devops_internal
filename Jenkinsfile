pipeline{
  triggers{
    pollSCM("* * * * *")
  }
  stages{
    stage build{
      ./build.sh
      echo "Build succesful"
    }
    stage test{
      echo "Testing succesful"
    }
  }}
