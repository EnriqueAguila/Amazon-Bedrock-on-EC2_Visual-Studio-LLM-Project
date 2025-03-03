# Amazon Bedrock on EC2 Visual Studio
![VS Bedrock](https://github.com/user-attachments/assets/e14f709b-67ce-4bff-a2b2-5e9b9fd98773)

### Amazon Bedrock is a service offered by Amazon Web Services (AWS) to facilitate the development of Generative AI applications.

Generative artificial intelligence (Generative AI) plays a critical role in Amazon Bedrock, enabling developers to create applications with breakthrough capabilities that were previously impossible.
But what is generative AI?
Generative AI is a type of artificial intelligence that can create new content and ideas, including conversations, stories, images, videos and music, and helps us innovate. Like all artificial intelligence, this one works with machine learning or ML models. However, Generative AI is powered by very, very large models that are pre-trained on large collections of data and are known as base models or fundamental models (FM). Recent advances in machine learning have led to the emergence of fundamental models containing billions of parameters or variables.

Recent advances in generative artificial intelligence (generative AI) have been largely driven by processors.
Within Amazon Web Services (AWS), unprecedented computing power is offered. Among the main ones are the Trainium2 and Graviton4 processors, developed for machine learning scenarios and execution of AI-based applications, these solutions are based on ARM architecture.

Amazon Trainium2 – This is a custom-designed AI accelerator chip built by Amazon specifically for training large machine learning models, particularly core models (FM) and large language models (LLM) with trillions of parameters. Trainium2 stands out for accelerating the training process of these complex models.
Graviton4 is a powerful CPU architecture designed by Amazon specifically for its cloud services and can benefit Amazon Bedrock in several ways:
• Improved cost-effectiveness: Graviton4 processors offer a better price-performance ratio compared to previous generations. This means that running generative AI applications on Amazon Bedrock models powered by Graviton4 could potentially be more cost-effective.

• Possible performance gains for specific tasks: While Graviton4 is not designed specifically for AI training like Trainium2, some generative AI tasks within Amazon Bedrock applications could benefit from its performance improvements. This could include tasks that rely heavily on general computing power rather than specialized AI acceleration.
• Trainium2 delivers up to 50% training cost savings over comparable Amazon EC2 instances and is designed for machine learning workloads. Trainium2 was built to train and deploy ultra-large Generative AI models with hundreds of miles of millions of parameters.
![EC2](https://github.com/user-attachments/assets/be8aee3f-3509-4c42-a0fe-f0dbe1889fb5)

In the next installment we will see more about Amazon Bedrock.

## Prerequisites
An AWS account
Visual Studio Code installed on your system

### AWS IAM Setup
1. Create an IAM Group :
o Navigate to IAM in AWS and create a new group named demo.
o Add BedrockReadOnlyAccesspermission to the group.

2. Create Custom IAM Policies :
o Create an inline policy for the demogroup that includes readinvokepermissions for Bedrock models.

3. Create a Service Account :
o Create a user named svc-bedrockand add it to the demogroup.

4. Generate API Keys :
o Navigate to serviceBedrocksecuritycredentialsand create
new access keys.

### Configure Access to Bedrock Models

1. Access Bedrock in the AWS Console :
o Go to the Bedrock service and navigate to Model Access.

2. Manage model access:
o Select and add the models you want to access, such as llama, Amazon titan, Anthropic, etc.

### Set up local environment

1. Set up AWS credentials:
o Edit the .aws/credentials file with the access key and secret key obtained above.

2. Set region settings:
o Modify the .aws/config file to specify the desired AWS region.

### Developing the application
1. Setup in Visual Studio Code:
o Open Visual Studio Code and prepare the application that will invoke the AI ​​models.

2. Use Bedrock Helper:
o Implement a helper module to manage the invocation of different AI models with different parameters.

3. Invoke AI models:
o Run the application to invoke AI models and process their responses.

### In the webserver folder you right click to create Newfolder
You put websites
In the terminal you put cd bedrock-main

```
docker network create donut-net
```
```
pip install virtualenv
```
```
python -m venv ./venv
```
```
. venv/bin/activate
```

### It appears in the root at the beginning of the line (venv)
```
git clone https://github.com/EnriqueAguila/Bedrook455.git
```
```
cd Bedrook455
```
```
cd bedrock-main
```
```
pip install boto3
```
```
pip install rich
```
```
python app.py
```

### In the file line 20 you change the prompt again
```
python app.py
```
### Starting bedrock.py comes out, the text sausage comes out and you apply this command:
```
python autorun.py
```
### Select a model comes out:
you press 3 or 5
it asks you:

Why is sky blue?

### And it answers
```
python manage.py migrate
```
```
chmod -R a+w ../donutwebsite
```












Ingeniero Enrique Aguilar Martinez
