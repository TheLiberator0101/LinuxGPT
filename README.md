LinuxGPT

Script that integrates ChatGPT into Linux CLI

1.) Save the script as "ask" to your /usr/local/bin
<br>
2.) Make the script executable by running: 
<br>
&emsp;    - chmod +x ask
<br>
3.) Set the Environment Variable in a Secure File:
<br>
&emsp;    - echo 'export OPENAI_API_KEY="your_openai_api_key_here"' > ~/.openai_key
<br>
4.) Create a file to store your API key and set the appropriate permissions:
<br>
&emsp;    - chmod 600 ~/.openai_key
<br>
5.) Test script by asking a question:
<br>
&emsp;    - ask How do I integrate ChatGPT into the Linux CLI?
