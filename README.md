# covid19
Visualizing the COVID-19 data to gain insight into how the world stands.  

Data exploration and preparation done in `jupyter-notebook` and website made using Jekyll and hosted here:  
* https://kylehounslow.github.io/covid19/  
  
## Data Sources
* [Johns Hopkins CSEE Github](https://github.com/CSSEGISandData/COVID-19)

## Running Jupyter Notebooks:
**Either run locally using `docker-compose`**  
```bash
docker-compose build notebooks
docker-compose run notebooks
```
**Or open in Google Colab:**  
* Canada Bar Chart: [notebooks/EDA-Canada.ipynb](https://colab.research.google.com/github/kylehounslow/covid19/blob/master/notebooks/EDA-Canada.ipynb)  
* World Bar Chart: [notebooks/EDA-World.ipynb](https://colab.research.google.com/github/kylehounslow/covid19/blob/master/notebooks/EDA-World.ipynb)

## Useful COVID-19 Visualization websites
### World
* https://coronavirus.jhu.edu/map.html
* https://ourworldindata.org/coronavirus  
* https://www.learnfromdata.ai/corona_outbreak  

### Canada 
* https://virihealth.com/  



## Example Bar Chart Race using Flourish
[https://public.flourish.studio/visualisation/1726960/](https://public.flourish.studio/visualisation/1726960/)  

Data generated using [notebooks/EDA-World.ipynb](notebooks/EDA-World.ipynb)  
The data is output as `world_covid19_M_D_YY.csv`

