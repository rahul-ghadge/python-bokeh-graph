# python-bokeh-graph

Display different kind of graphs using `bokeh` library with some static data.
Using `pandas` to reading data from `bokeh`'s official repository.

###bokeh.sampledata
The sampledata module can be used to download data sets used in Bokeh examples. Which we have used here.
The simplest way to download the data is to use the execute the command line program:

> bokeh sampledata  

Alternatively, the download function described below may be called programmatically.(Use python console)

> import bokeh.sampledata  

> bokeh.sampledata.download()

By default, data is downloaded and stored to a directory `$HOME/.bokeh/data`. (**_The directory is created if it does not already exist._**)

**Create virtual environment so we can run this app in it using below commands:**

> `cd path-to/python-bokeh-graph`

> `sudo python3 -m virtualenv venv`

> `source venv/bin/activate`

> `pip3 install -r requirements.txt`

> run any file from graphs package

> run `world-population.py`

After running the files, it will create `*.html` under **`template`** repository. Just open those files in browser like below:

**Periodic Table:**  
http://localhost:63342/python-bokeh-graph/template/periodic.html?_ijt=v3im356q6rejgmtbdjqc2pjce5  
![Periodic Table](https://github.com/rahul-ghadge/python-bokeh-graph/blob/master/static/bokeh_plot-1.png)


**Hexbin Graph:**  

![Periodic Table](https://github.com/rahul-ghadge/python-bokeh-graph/blob/master/static/hexbin.png)
