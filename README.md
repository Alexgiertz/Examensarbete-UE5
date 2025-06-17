# AI Assistant – Unreal Engine Component

**IMPORTANT:** This repository only includes the Unreal Engine portion of the project.  
To run the system, you must install and configure **EchoWhisperAPI**, created by Archangel4031. Follow the instructions below.

---

## Setup Instructions for EchoWhisperAPI

### Written tutorial by Archangel4031:
[https://github.com/archangel4031/EchoWhisperAPI](https://github.com/archangel4031/EchoWhisperAPI)

### Video tutorial by Archangel4031:
[https://www.youtube.com/watch?v=0sRt-dmOQAg](https://www.youtube.com/watch?v=0sRt-dmOQAg)

---

## Switching LLM Versions

To change which LLM is used:

1. In **Command Prompt / PowerShell**, enter:  
   `ollama pull [insert LLM version]`
2. Navigate to:  
   `\EchoWhisperAPI\EchoWhisperAPI\config.ini`
3. Under the `[LLM Query]` section, locate the line:  
   `selected_model = llama3.2:1b-instruct-q4_K_S`
4. Modify it to:  
   `selected_model = [insert LLM version]`

---

## Personalisation Variables

To view or modify the learner personalisation variables:

- Open the **Unreal Engine 5 scene**.
- Select the **NPC** (Default actor name is **BP_Pia1**).
- In the **Details** panel, look for variable fields under the actor’s attributes.

These predefined variables are used to tailor the assistant’s responses.

---

## Additional Notes

- All components run **locally** – no external hosting or internet access is required.
- **Text-to-speech (TTS)** is optional and can be toggled within the engine.

---

