# A Complete Guide to an Interactive Geographical Map using Python

Ever wondered how these beautiful geographical maps are created? Our World in Data has an extensive collection of interactive data visualizations on aspects dedicated to the global changes in health, population growth, education, culture, violence, political power, technology and several things that we care about. These visualizations help us understand how and why the world has changed over the last few decades. I was intrigued with this wealth of information and motivated to dive deeper.

# Directory Layout

```
.
├── README.md
├── bokeh-app
│   ├── data
│   │   ├── countries_110m
│   │   │   ├── ne_110m_admin_0_countries.README.html
│   │   │   ├── ne_110m_admin_0_countries.VERSION.txt
│   │   │   ├── ne_110m_admin_0_countries.cpg
│   │   │   ├── ne_110m_admin_0_countries.dbf
│   │   │   ├── ne_110m_admin_0_countries.prj
│   │   │   ├── ne_110m_admin_0_countries.shp
│   │   │   └── ne_110m_admin_0_countries.shx
│   │   └── poverty.csv
|	|
│   └── world_poverty_literacy.ipynb
```

# Running the sample

## Step 1 : Execute Code 

Open `world_poverty_literacy.ipynb` file and rull all cells.

## Step 3 : Start bokeh server

In the browser using the jupyter notebook go to the `Terminal` 

```
bokeh serve --show world_poverty_literacy.ipynb
```
## Step 4 : Browse the interactive map

The interactive map is rendered by bokeh server which can be browsed at `http://localhost:5006/`
