# CD12352 - Infrastructure as Code Project Solution
# Kate Kinninmont

## Spin up instructions
To spin up a stack, use the create-stack.sh script with 3 parameters - stack name, name of you yml template file, name of your json parameters file. For example: 
    
    ./create-stack.sh my-stack my-template.yml my-parameters.json

## Tear down instructions
To delete a stack, use the create-stack.sh script with 1 parameter. For example:

    ./delete-stack.sh my-stack

## Other considerations
You can also update a stack to make changes to an existing stack. Use the update-stack.sh script with 3 parameters - the name of the stack you want to update, the name of your udpated yml template files, the name of your update json parameters file. For example:

 ./update-stack.sh my-stack updated-template.yml updated-parameters.json

http://B-LoadBalanc-0kkHDQEOp4xZ-502632439.us-east-1.elb.amazonaws.com
