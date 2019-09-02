# NicksToolbox
This is my package. 

In order to install it, run
```bash
$ pip install nickstoolbox
$ python 
>>> import nickstoolbox as ns 
```

## Functions and Classes

### ns.HowsMyMemory()
Prints the current time, and how much memory is being used 

### ns.EndCode()
Prints that the code ended along with the timestamp in which it ended 


### ns.Scatter(x,y,z,c='b',marker='o',depthshade=True,xlabel='',ylabel='',zlabel=''):

### ns.ViewAvailableFonts():
Prints the available fonts for Matplotlib 

### ns.ScatterWithHist(x, y, scatterstyle='bo', bin_no = None, cx = 'red', cy = 'cyan',alphaVal=0.5):
This plots your xy plots but also puts in the histogram distribution of the x values on the x-axis and the histogram distribution of the y values on the y-axis.
This was originally suggested by Dr. Gari Clifford as a sanity check to make sure that your data was properly distributed.

### ns.ActivateLatex():

### ns.SetTicks(size=20):

### ns.FlattenList(input_list):

### ns.flatten(input_list):

### ns.DrawBoundary(x,y):

### class SendEmail():