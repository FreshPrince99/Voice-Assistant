# Voice-Assistant
Created a voice assistant using livekit.io playground interface

Initializing the environment:

# LiveKit Assistant

First, create a virtual environment, update pip, and install the required packages:

```
$ python3 -m venv .venv
$ source .venv/bin/activate
$ pip install -U pip
$ pip install -r requirements.txt
```

You need to set up the following environment variables:

```
LIVEKIT_URL=wss://vander-kmfwqxl2.livekit.cloud
LIVEKIT_API_KEY=APIAWVb747RiF2g
LIVEKIT_API_SECRET=0RXXNuQNPAWp08qrcp6HQlqcRX1gFqJj12i8Beba7Tb
DEEPGRAM_API_KEY=e83b36b1da578f2349b1b70054d46640314613e7
OPENAI_API_KEY=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
```

Then, run the assistant:

```
$ python3 assistant.py download-files
$ python3 assistant.py start
```

Finally, you can load the [hosted playground](https://agents-playground.livekit.io/) and connect it.