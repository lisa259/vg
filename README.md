**Video Game Ontology**

Using the knowledge we obtained from the Knowledge and Data course which are
about describing data using RDF, RDFS, OWL and querying data using SPARQL, we
are able to create a data visualization application which contains an analysis
of a dataset about video games. Our application can be accessed through a
jupyter notebook.

The objective of this project is information that is related to video games. In
this project, you will. We combined ontologies that we found about video games
from [Schema](https://schema.org/VideoGame) and
[**VideoGameOntology**](https://github.com/dgarijo/VideoGameOntology/blob/master/GameOntologyv3.owl)
with a dataset that is collected from [Video game test
data](https://www.kaggle.com/andrewolney/videogametestdata). By using the
information that we obtained online, we are able to create the visualizations
presented in this notebook.

Our submitted notebook is saved in such a manner that all the desired outputs
have been displayed. Do note that an active internet connection is required, and
the notebook needs to be *trusted* in order to display the map in section 4. But
please follow the guide below in the case you want to run the notebook yourself:

For our notebook, we made use of GraphDB repositories and JupyterLab, which runs
on Python 3. We made use of the python libraries ipython_sparql_pandas, pandas,
seaborn, matplotlib and folium. Please be sure to have these packages installed
in order to be able to run the jupyter notebook.

**Installation**

**GraphDB Installation**

To have a local repository, install the GraphDB application:
<https://www.ontotext.com/products/graphdb/graphdb-free/>

**Python Installation**

You need to have at least Python 3.8 installed on your computer and you can find
all the information: https://www.python.org/downloads/. To check if python is
installed, run the following command on your local terminal:

enter the following command:

python -V

**Jupyter Installation**

You can find a complete installation documentation of jupyter on
https://jupyter.org/install. Make sure to install pip from
https://pip.pypa.io/en/stable/installation/. Jupyterlab is used to access the
notebook.

**Jupyterlab Installation**

For a local installation on the terminal run:

​​\$ pip install jupyterlab

**Access the jupyter lab**

Running in a local installation:

​​\$ jupyter lab

**Package Installation**

To make the graphs visible, make sure all necessary python libraries are
installed, if any are missing, run:

\$ pip install pandas

\$ pip install ipython-sparql-pandas

\$ pip install folium

\$ pip install seaborn

\$ pip install matplotlib

**Running our notebook**

1.  Be sure to have Jupyterlab, Python, GraphDB installed

2.  Create a local repository on GraphDB

3.  Import all turtle files into the GraphDB repository:

-   CSV_Triples.ttl

-   K&D_Final_Project_Ontology.ttl

-   Inferred_Triples_Protege.ttl

-   Imported_Triples_DBPedia.ttl

1.  Open Jupyter from your local terminal.

2.  Have access to our notebook -- K&D_Final_Project.ipnyb.

3.  Make sure all necessary packages are installed with pip. (See above)

4.  In the notebook, replace the url endpoint in all queries with your graphDB
    endpoint.

5.  Run the cells in the specified order to get all the results.

**Descriptions of visualizations**

**Table**

1.1 A table with the ten most popular games and their descriptions.

1.2 A table with the top ten games and their descriptions according to user
ratings.

1.3 A table with the top ten games and their descriptions according to critic
ratings.

**Bar Chart**

2.1 A bar chart to visualize data about the ratings and the game console.

2.2 A bar chart to visualize data about the ratings and the genre.

**Scatter plot**

3.1 A scatter plot to represent the sales of video games and its user rating.

3.2 A scatter plot to represent the sales of video games and its critic rating.

3.3 A scatter plot to represent the sales of video games and its average rating.

**Map**

4.1 A world map of the sales of a video game per country or area where the sales
of the video game are expressed by the color of the area.

4.2 A World map that presents of the location video game publisher and developer
headquarters and their total profit.

**Contribution**

The project is created by Lisa Beek, Taina Aloha, Divabelle Bayuputri, Ashilla
Fryda Risautami. Please contact us if you have any questions regarding the
project.
