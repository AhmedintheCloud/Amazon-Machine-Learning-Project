# Amazon-Machine-Learning-Project
In this project I utilized Amazon Textract, Comprehend and Bedrock to analyze texts and images 
This demonsration calls for me to have access to the Anthropic Claude 3 Haiku model so requested access for that before I got started.
After my request was granted, I started by creating an notebook instance in AWS Sagemaker 
IAM will automatically create a role for your notebook instance but you will need to add the permissions to gain full access to Textract, Bedrock and Comprehend 
Once my notebook instance fully intialzed, I launched the JupyterLAb and opened a new lab to post my textract.py code.
I added an image of a sixten bar rap lyric to the directory on the left hand side and made sure to save all documents before running the code.
The textract.py will analyze the image's text and essentailly generate a copy of its own 
Next I tested out the textract and comprehend python code by adding an image of a handwritten poem. Textract will analyze the picture again and copy it and comprehend essentially summarizes the image in one word based off its human characterics 
Finally when implementing the Amazon Bedrock python code, I was able to see how the generative AI is not only able to analyze an image through but piece together the text and characters in the picture to make sense of it 
