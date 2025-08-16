This repository is the final project regarding the Practice: Software Development (Python) at the PLUS University. 

The repository is an exploration of:
 - How to retrieve Windy data from [Earth Data Hub](https://platform.destine.eu/services/service/earth-data-hub/)
 - How to pre-process and load the data on your notebook.
 - How to create windy plots and windy animations using the well-known library: Matplotlib
 - Inovating at Windy animations by using Manim Library.

Prince
- Creating of Wind plots, using Matplotlib and its extension as Cartopy.
- Introduces the colorbar and title to the plot.
  
## Installation 

```bash 
git clone https://github.com/emanuel-gf/Windy-Matplotlib-Manim-GeoViz.git
cd windy-matplotlib-Manim-Geoviz
```

2. Create and Activate a environment 

You can do it by using conda or using uv

```bash 
conda create -n manim python==3.13.3
conda activate manim
```

3. Install Dependencies
```bash
pip install -r requirements.txt
```

4. Set up your credentials by creating a .env file in the root directory of your project.

```bash
# In case linux or mac
touch .env

# In case windows
wsl touch .env 
#consider install wsl in windows if you do not have, it's a windows subsystem for linux
```

then, inside the .env file

```bash
earth_hub_key = your_earth_hub_key
```

