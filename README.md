# aws-devops
* ansible/example2
  
  aws cloudformation create-stack --capabilities CAPABILITY_IAM --stack-name jenkins --template-body file://jenkins-cf.template --parameters ParameterKey=KeyPair,ParameterValue=xxxxxxxx
