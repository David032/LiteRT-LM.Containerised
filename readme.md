# LiteRT-LM.Containerised
A simple installer/wrapper for LiteRt-Lm that allows it to be run in a container
# How to use
Run the container, it's got an install script that installs litert-lm and gemma-4-e2b. 
Once that's done it works as per the [docs](https://developers.google.com/edge/litert-lm/cli/openai_server)
# Please note
This was a something I threw together very quickly, so it's fixed to use gemma-4-E2B. 
And since it's running in a container, it can't take advantage of GPU/NPUs on a raspberry pi 5
