----------------------------------------------------------------------------------------------------------------------------------

IMPORTANT: This repository only includes the Unreal Engine part of the project. To install EchoWhisperAPI (required) please
follow the steps bellow

----------------------------------------------------------------------------------------------------------------------------------

To install and run EchoWhisperAPI (required for the project to work) please refer to the tutorials by Archangel4031 below.

IMPORTANT: The tutorial uses the following LLM version: llama3.2:1b-instruct-q4_K_S
When the program was demonstrated it used the following version: llama3.1:8b
If you wish to use another LLM, instructions for this can be found further down in the document.

Written tutorial:
https://github.com/archangel4031/EchoWhisperAPI

Video tutorial:
https://www.youtube.com/watch?v=0sRt-dmOQAg&ab_channel=FireAngel

----------------------------------------------------------------------------------------------------------------------------------

If you wish to change LLM version, download the desired LLM through the CMD/Powershell by using "ollama pull [insert LLM version]"
Locate the file "config.ini", which can be found in \EchoWhisperAPI\EchoWhisperAPI
Under the section [LLM Query] edit the following line: "selected_model = llama3.1:8b" to "selected_model [insert LLM version]"

----------------------------------------------------------------------------------------------------------------------------------
