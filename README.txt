-----------------------------------------------------------------------------------------------------------------------------

IMPORTANT: This repository only includes the Unreal Engine portion of the project.
To run the system, you must install and configure EchoWhisperAPI, created by Archangel4031. Follow the instructions below:

Setup Instructions by Archangel4031:

Written tutorial:
https://github.com/archangel4031/EchoWhisperAPI

Video tutorial:
https://www.youtube.com/watch?v=0sRt-dmOQAg&ab_channel=FireAngel

-----------------------------------------------------------------------------------------------------------------------------

If you wish to use another LLM version, follow these instructions:

1. In Command Prompt/Powershell use the command: ollama pull [insert LLM version]

2. Navigate to: \EchoWhisperAPI\EchoWhisperAPI\config.ini

3. Under the [LLM Query] section, locate the line: selected_model = llama3.2:1b-instruct-q4_K_S

4. Modify the line to: selected_model = [insert LLM version]

-----------------------------------------------------------------------------------------------------------------------------

To view or modify the learner personalisation variables:

Select the NPC in the Unreal Engine 5 scene.

In the Details panel, locate the variable fields under the actor's attributes.

These predefined variables are used to tailor the assistant’s responses to the learner.

-----------------------------------------------------------------------------------------------------------------------------

Make sure all components are run locally (no external hosting required).

Text-to-speech is optional and can be toggled in the engine.

-----------------------------------------------------------------------------------------------------------------------------
