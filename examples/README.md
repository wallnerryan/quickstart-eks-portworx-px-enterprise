## How to use examples

Only use these stacks **AFTER** you deploy Portworx QuickStart

Step 1 - Click create new stack from CloudFormation Console.
Step 2 - Fill in Stack Name
Step 3 - Fill in `KubeManifestConfig` with value of `KubeManifestLambdaArn` from the outputs in the stack with description `Deploys Lambda functions required for the AWS EKS Quick Start`.
Step 4 - Fill in `The s3 path to the KubeConfig.` with value of `KubeConfigPath` in the ouputs of your main Portworx Stack with the description that starts with `Deploys Portworx Enterprise`.
Step 5 - Fill in or accept defaults of any other parameters and click `Next` ,`Next`, and `Create Stack`!

After deploying the example, use the Bastion host to use `kubectl` and see your new resources deployed.