
# AWS CloudFormation Demo

This AWSome repository contains all the source code from my presentation at AWS User Group Lviv Meetup


## Run Locally

Clone the project

```bash
  git clone https://github.com/Forfend/aws-usergroup-cfn.git
```

Go to the project directory

```bash
  cd aws-usergroup-demo
```
Create stacks from templates

```bash
  aws cloudformation create-stack --stack-name example-stack --template-body file://cfn/exampple.yaml --parameters file://cfn/parameters/example-parameters.json
```
Update stack

```bash
  aws cloudformation create-stack --stack-name example-stack --template-body file://cfn/exampple.yaml --parameters file://cfn/parameters/example-parameters.json
```


## Docs

 - [What is CloudFormation](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/Welcome.html)
 - [Building blocks](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/template-anatomy.html)
 - [Nested Stacks](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/using-cfn-nested-stacks.html)
 - [StackSets](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/what-is-cfnstacksets.html)
 - [Helper Scripts](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/cfn-helper-scripts-reference.html)

