
# Please run all the code in google colabs T4 GPU

## Problem statement 2
To run this, you will need to save the Hugging face token in colab as HF_TOKEN and grant the notebook access to it. 
You can create a read token from [here](https://huggingface.co/settings/tokens)

## Problem statement 5
I have decided to scrape youtube for this. This peice of code will give you information about a channel when given the channels id. 
You will need an API key which can be generated [here](https://support.google.com/googleapi/answer/6158862?hl=en)

You can input any channel ID for scraping, but the processing time will increase proportionally to the number of videos published by that channel.

Get the channel id of any youtube channel by going to the channels main page, right click and select view page source. 
This will open another page. Here search(ctrl+f) for ?channel_id= The string after that will be channel id.
