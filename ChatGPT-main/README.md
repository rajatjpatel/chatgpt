


# Usage
## Installation
`pip3 install --upgrade revChatGPT`
`python3 -m playwright install`
## Usage
python3 -m revChatGPT
## Configuration (Optional)
All of these are optional
```json
{
  "session_token": "<token>",
  "proxy":"<proxy>",
  "accept_language": "en-US,en"
}
```
## Developer usage
Take a look at the [`main.py`](https://github.com/acheong08/ChatGPT/blob/main/src/revChatGPT/__main__.py)
### Basics
```python
from revChatGPT.revChatGPT import Chatbot

# Do some config
...

chatbot = Chatbot({
   # This could be blank but the dict should be here
})

chatbot.get_chat_response(prompt, output="text") #output=stream uses async generator
```


> Open the proxy first, run it, wait for the browser to close automatically for the first time, and immediately close the proxy. It is recommended to set a global shortcut key to press. If completed successfully, the browser will automatically open after the second time. The parameters can be obtained correctly.


If you have a cool project you want added to the list, open an issue.

# Disclaimers
This is not an official OpenAI product. This is a personal project and is not affiliated with OpenAI in any way. Don't sue me

