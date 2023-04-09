# Codeserver on Sagemaker Notebook with GPU

Repo with a cloudformation template that creates a sagemaker notebook on a GPU instance with code-server pre-installed.

## 1. Click the button to launch the cloudformation stack and follow the steps.

[![launch-stack.png](assets/launch-stack.png)](https://console.aws.amazon.com/cloudformation/home#/stacks/new?stackName=codeserver-on-sagemaker-notebook-with-gpu&templateURL=https://public-assets-vincent-claes.s3.eu-west-1.amazonaws.com/codeserver-on-sagemaker-notebook-with-gpu/codeserver-on-sagemaker-notebook-with-gpu.yml)

## 2. Specify the instance type.
![cfn.png](assets/cfn.png)

- ml.p3.2xlarge
- ml.p3.8xlarge
- ml.p3.16xlarge
- ml.p3dn.24xlarge
- ml.g4dn.xlarge >> Fast launch
- ml.g4dn.2xlarge
- ml.g4dn.4xlarge
- ml.g4dn.8xlarge
- ml.g4dn.12xlarge
- ml.g4dn.16xlarge
- ml.g5.xlarge
- ml.g5.2xlarge
- ml.g5.4xlarge
- ml.g5.8xlarge
- ml.g5.12xlarge
- ml.g5.24xlarge
- ml.g5.48xlarge

More info on the GPU instances [here](https://docs.aws.amazon.com/dlami/latest/devguide/gpu.html?utm_source=pocket_reader)


## 3. Open as Jupyter / JupyterLab

![sm.png](assets/sm.png)

## 4. Open code-server on Sagemaker.

![code-server.png](assets/code-server.png)

## 5. Specify the Python Interpreter

- Go to Command Palette (CMD + Shift + P) 
- Search for "Python Interpreter"
![search-interpreter.png](assets/search-interpreter.png)
- Select the interpreter from the available Kernels
![interpreter.png](assets/interpreter.png)
- Happy coding!