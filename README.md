# COVID-19-FAQ
RASA CHATBOT - gives basic answer related to spread of COVID-19 virus. The rasa model is trained on covid data from WHO site.

Requirements :
python 3.6.7
rasa 1.0.1
Visual c++ build tools



Instructions for Installation:
#creating conda environment
conda create -n rasa python=3.6
#rasa is name of environment I have used
conda activate rasa


Installing dependencies:
pip install tensorflow

Create a directory where you want to store your project. Navigate to that directory. Use following command:
rasa train

model will get stored in models directory default location in the newly created folder for chatbot.

#Open browser
to get Chatbot UI run command rasa x.
Point to http://localhost:5005
Chat with the bot
