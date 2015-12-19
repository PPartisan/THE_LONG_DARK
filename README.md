# THE LONG DARK mapping tool
A mapping tool for the game The Long Dark developed by [Hinterland Studio](http://hinterlandgames.com/)

Here is the current map for the new region, Timberwolf Mountain:
![topo map](https://cloud.githubusercontent.com/assets/11873158/11914245/5bbb196c-a67b-11e5-91c9-811cbda68b3d.png "Timberwolf Mountain Topo Map")


## 1 - Installation

At the moment, this script only works on Windows platform.  

In order to use the script, download or clone this repository.  

You will need a valid distribution of Python installed on your computer, alongside with matplotlib and numpy modules. If you don't even know what I'm talking about, just download the [Anaconda Distribution for Python 2.7](https://www.continuum.io/downloads) 

That's all! You are ready to map!

## 2 - Usage

To create the maps, you will have to open a command prompt (Windows key + X on my computer) and navigate to the directory where you downloaded TLD_Mapping_tool.py (hint: use "cd path/to/your/directory").

Then, type the following line to open the GUI:
> python TLD_Mapping_tool.py

Once the ( minimalistic ;-) ) window is opened, you will need to select the path to the screenshots (your Desktop) and the path for the created maps and coordinates files.

### 2.1 - Create a map while playing

To start an interactive mapping session, just click on "start mapping", and do not close the window.

Then, launch The Long Dark.

 All you need to do to start helping is to press f7 to activate mapping while in a sandbox game. The script will automatically take your coordinates every few seconds and append them to a file. Press f7 in order to stop mapping,, while indoors for example.
 
### 2.2 - Create topo maps from coordinates files
 
 Click on "create maps". The script will automatically create topo maps according to the screenshots and coordinates files, and save them to the desired location.
 
 
## Help me mapping!

In order to create an accurate topo map, I could use your help.

As an example, you could navigate to places you don't often visit, or try climbing as many summits as you can (beware of the nasty sprained ankles).

Once you mapped a lot of a region, please create a [new issue](https://github.com/loicNorgeot/THE_LONG_DARK/issues) with your coords.txt file appended, selecting the "Let me Help" label and specifying the region you mapped. I will add them to the existing base creating the maps and won't forget to thank you!

Here are the places I've currently been to in Timberwolf Mountain. The idea is to left blank as little as possible of this map:

![topo map](https://cloud.githubusercontent.com/assets/11873158/11914246/5d3d57a0-a67b-11e5-80b3-11e970d5d4c1.png "Timberwolf Mountain Path Map")
