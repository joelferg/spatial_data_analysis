# Environmental Studies 402: Spatial Data Analysis


## Virtual Environment
This github repository will be home to all things code for the course. The first thing you'll need to do is set up a virtual environment to hold the packages we'll use. Navigate to the directory in which you want your virtual environment to live (I put all mine in `~/venv/`) and make a new virtual environment using `python3 venv -m sda`. Activate it using `source sda/bin/activate`, then navigate to the directory holding the github repo on your local machine and run `pip install -r spatial_data_analysis.txt`. Your environment is now set up!

The next thing to do is register your new virtual environment with Jupyter. Run `python -m ipykernel install --user --name=sda --display-name "Spatial Data Analysis"` and you should be set! Now if you start a Jupyter notebook with `jupyter notebook` and go to make a new notebook you should see "Spatial Data Analysis" as one of the options.

## Thursday lectures

Thursday lectures will be conducted using jupyter notebooks. These notebooks will be posted the night before the lecture, so you can look at the material ahead of time, follow along, and tweak the code if you like during class. These will show up in the `/lectures/` directory. To see them, simply pull the github repo to your local machine after I've pushed them on Wednesday night, or go to the [github site](https://github.com/joelferg/spatial_data_analysis) and download it directly. 

## Homework assignments

Homework assignments will appear in the `/hw/` directory. You'll be able to access them similar to how you access the Thursday lectures. I will let you know (either in class or via Canvas/email) when I have pushed the homeworks.