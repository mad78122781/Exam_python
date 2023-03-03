<center>Mamadou Aliou Diallo</center>

<style>
    body{
        background-opacity: 0.5;
        background-color: white;
        color: black;
    }
</style>

# Content
- What is Plotly?
- Why Plotly?
- How to install ?
- How is plotpy structured ?

**I. Plotpy VS Matplotlib**

**II. Some modules of plotly**

**III. How plotpy works**

![Logo plotly >](./Images/plotly_logo.png =900x200)

**What is Plotly:** 

*Plotly*, before being a well-known Python library, is a Montreal-based company founded by four people. Its objective is to develop visualization tools as well as data analysis tools.  
The company's productions are diverse and varied. The Python Dash framework, which allows the development of web applications, is one of them. It offers web applications deployed through a web browser allowing to share online data visualization. Chart studio is another example of tools created by the company. It is a software infrastructure allowing to store charts on an interface in a public or private way. The public mode makes available to all users various pre-designed charts that can be downloaded.
Among the different tools and libraries that Plotly provides in the field of statistics and data analysis, we will, in the following article, focus on the famous Plotly library.  
Thanks to the development of different APIs, Plotly is a library available in several programming languages, including Python (plotly.py), Java (plotly.js), R, Julia, Matlab, etc. It allows to realize complex and varied graphs. In the following, we will focus on Plotly in Python because it is the most popular language in Machine Learning, in addition to being one of the easiest to learn.
Plotly is an open-source Python module that is used for data visualization and supports various graphs such as line graphs, scatter plots, bar graphs, histograms, areas, etc.
![Illustration de quelques graph]()

**Why plotpy:**

Plotly uses javascript behind the scenes and is used to create interactive plots where we can zoom in on the graph or add additional information like hover data and more. 

*Some advantages of plotly:*

- Plotly has hover tool capabilities that allow us to detect any outliers or anomalies in a large number of data points.  
- It is visually appealing and can be accepted by a wide range of audiences.  
- This allows for endless customization of our graphics, making our plot more meaningful and understandable to others.

**How to install plotly:**  
We should install plotly as it is not integrated in python. To do this we run this command in our terminal.  
```
pip install plotly 
```

![Installing plotly](./Images/Install.PNG)

**How is plotly structured:**   
There are three main modules in Plotly  
- plotly.plotly serves as an interface between the local machine and Plotly. It contains functions that require a response from the Plotly server.
- The plotly.graph_objects module contains the objects (figure, layout, data and plot definition such as scatterplot, line graph) that are responsible for creating the plots. The figure can be represented as dict or instances of plotly.graph_objects.Figure and these are serialized as JSON before being passed to plotly.js. Figures are represented as trees where the root node has three top layer attributes - data, layout and frames and the named nodes called "attributes".
- The plotly.tools module contains various tools in the form of functions that can enhance the Plotly experience.

**I. Plotpy VS Matplotlib:**

Python already has a graphics library, much older than Plotly, called Matplotlib. This one also allows to create various graphics in a few lines of code and seems to be rather exhaustive.  
>So the question one might ask is, how does Plotly differ from Matplotlib? What is the added value of Plotly?  

The answer lies in the additional modes that Plotly offers. Indeed, unlike Matplotlib, Plotly is a collaborative and interactive library. Thanks to Chart studio, it offers a web service and a collaborative mode which, as mentioned above, allows to download and save data charts on a personal account. It is the interaction with the different servers of Plotly that allows the creation of this web service and the collaborative mode. However, it is possible to activate a mode (by importing the offline package) that allows to prevent the distribution of graphs on the cloud and to make them accessible only on the local. Thus, the connection between the different Plotly servers is interrupted and the collaborative mode stopped.  
Moreover, the visualization of data with Plotly is more advanced than with Matplotlib. It offers the creation of more than 40 different types of graphs, ranging from classic graphs to interactive graphs, animations or 3D graphs.    
![Illustration de quelques graph]()
Apart from the great simplicity of use and the important capacity of customization of the graphs, another great advantage of Plotly is the ability to detect outliers in a database even in the case of a very large one. In fact, with Plotly it is possible to get information about the data by simply pointing the mouse on the graph. Thus, by reading the graph, one can locate and recover the outliers.  
![Illustration de la différence entre plotly et matplotlib]()

**II. Some modules of plotly**

In this section we will introduce some important Plotly libraries, each of which provides additional tools.

- plotly.offline is a library that allows you to keep graphs on your local computer and generate them offline by opening them in your web browser.  
![Exemple a l'appuie]()
- The plotly.graph_objects module contains the objects (figure, layout, data and plot definition such as scatterplot, line graph) that are responsible for creating the plots. The figure can be represented as dict or instances of plotly.graph_objects.Figure and these are serialized as JSON before being passed to plotly.js. Figures are represented as trees where the root node has three top layer attributes - data, layout and frames and the named nodes called "attributes".  
![Exemple a l'appuie]()