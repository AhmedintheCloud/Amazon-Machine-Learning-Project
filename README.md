# Amazon-Machine-Learning-Project
In this project I utilized Amazon Textract, Comprehend and Bedrock to analyze texts and images 
This demonsration calls for me to have access to the Anthropic Claude 3 Haiku model so requested access for that before I got started.
After my request was granted, I started by creating an notebook instance in AWS Sagemaker 
IAM will automatically create a role for your notebook instance but you will need to add the permissions to gain full access to Textract, Bedrock and Comprehend 
<img width="1353" height="504" alt="Screenshot 2025-08-29 231836" src="https://github.com/user-attachments/assets/ad519954-3cdc-42da-ba4a-2725d413aa38" />

Once my notebook instance fully intialzed, I launched the JupyterLAb and opened a new lab to post my textract.py code.
<img width="1418" height="139" alt="image" src="https://github.com/user-attachments/assets/b64868ba-0fdc-4289-9db4-021a38df67e4" />

I added an image of a sixten bar rap lyric to the directory on the left hand side and made sure to save all documents before running the code.
![raplyrics](https://github.com/user-attachments/assets/af6c43a3-0751-4b5d-8780-615a22de9863)

The textract.py will analyze the image's text and essentailly generate a copy of its own 
<img width="1920" height="1080" alt="Screenshot (1)" src="https://github.com/user-attachments/assets/a7f8189a-12cb-4247-b5b5-24796cc8bd7b" />

Next I tested out the textract and comprehend python code by adding an image of a handwritten poem. Textract will analyze the picture again and copy it and comprehend essentially summarizes the image in one word based off its human characterics 
<img width="1704" height="770" alt="Screenshot 2025-08-29 234713" src="https://github.com/user-attachments/assets/b2aa2b5b-2489-439c-80b8-9b7250883ec5" />

Finally when implementing the Amazon Bedrock python code, I was able to see how the generative AI is not only able to analyze an image through but piece together the text and characters in the picture to make sense of it 
<img width="1594" height="707" alt="Screenshot 2025-08-30 002449" src="https://github.com/user-attachments/assets/c119142b-489f-46b0-8fc1-d3b1c76b0318" />

