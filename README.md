# comfy-temporal-stability

# Install

pip install -r "requirements.txt"

# How to run

Start ComfyUI.

Put your video files in video directory. All files have to be named 000.png where 000 is the frame number. 001.png, 002.png, 003.png etc.

Tweak config.py to your liking.

Either run "run.bat" or "python main.py" from command line.

When re-running please delete output and ebsynth directories before firing it up again.

# How to do custom comfyui workflows

Enable developer options in comfyui and then save workflow api.

Save it to the root.

Change config to point to it.

For now you need to modify the values in comfyui.py. 

sampler = "14"
positive_input = "6"
negative_input = "7"
image_input = "10"

Set the numbers to whatever they're in the workflow_api.json