```python
import sys
!{sys.executable} -m pip install pandas
!{sys.executable} -m pip install beautifulsoup4
!{sys.executable} -m pip install requests
!{sys.executable} -m pip install geopy
!{sys.executable} -m pip install sklearn
!{sys.executable} -m pip install folium
!{sys.executable} -m pip install matplotlib
```

    Requirement already satisfied: pandas in /home/jupyterlab/conda/envs/python/lib/python3.6/site-packages (1.0.3)
    Requirement already satisfied: pytz>=2017.2 in /home/jupyterlab/conda/envs/python/lib/python3.6/site-packages (from pandas) (2019.3)
    Requirement already satisfied: python-dateutil>=2.6.1 in /home/jupyterlab/conda/envs/python/lib/python3.6/site-packages (from pandas) (2.8.1)
    Requirement already satisfied: numpy>=1.13.3 in /home/jupyterlab/conda/envs/python/lib/python3.6/site-packages (from pandas) (1.18.1)
    Requirement already satisfied: six>=1.5 in /home/jupyterlab/conda/envs/python/lib/python3.6/site-packages (from python-dateutil>=2.6.1->pandas) (1.14.0)
    Collecting beautifulsoup4
    [?25l  Downloading https://files.pythonhosted.org/packages/e8/b5/7bb03a696f2c9b7af792a8f51b82974e51c268f15e925fc834876a4efa0b/beautifulsoup4-4.9.0-py3-none-any.whl (109kB)
    [K     |████████████████████████████████| 112kB 3.2MB/s eta 0:00:01
    [?25hCollecting soupsieve>1.2 (from beautifulsoup4)
      Downloading https://files.pythonhosted.org/packages/05/cf/ea245e52f55823f19992447b008bcbb7f78efc5960d77f6c34b5b45b36dd/soupsieve-2.0-py2.py3-none-any.whl
    Installing collected packages: soupsieve, beautifulsoup4
    Successfully installed beautifulsoup4-4.9.0 soupsieve-2.0
    Requirement already satisfied: requests in /home/jupyterlab/conda/envs/python/lib/python3.6/site-packages (2.23.0)
    Requirement already satisfied: chardet<4,>=3.0.2 in /home/jupyterlab/conda/envs/python/lib/python3.6/site-packages (from requests) (3.0.4)
    Requirement already satisfied: urllib3!=1.25.0,!=1.25.1,<1.26,>=1.21.1 in /home/jupyterlab/conda/envs/python/lib/python3.6/site-packages (from requests) (1.25.8)
    Requirement already satisfied: certifi>=2017.4.17 in /home/jupyterlab/conda/envs/python/lib/python3.6/site-packages (from requests) (2020.4.5.1)
    Requirement already satisfied: idna<3,>=2.5 in /home/jupyterlab/conda/envs/python/lib/python3.6/site-packages (from requests) (2.9)
    Collecting geopy
    [?25l  Downloading https://files.pythonhosted.org/packages/53/fc/3d1b47e8e82ea12c25203929efb1b964918a77067a874b2c7631e2ec35ec/geopy-1.21.0-py2.py3-none-any.whl (104kB)
    [K     |████████████████████████████████| 112kB 25.5MB/s eta 0:00:01
    [?25hCollecting geographiclib<2,>=1.49 (from geopy)
      Downloading https://files.pythonhosted.org/packages/8b/62/26ec95a98ba64299163199e95ad1b0e34ad3f4e176e221c40245f211e425/geographiclib-1.50-py3-none-any.whl
    Installing collected packages: geographiclib, geopy
    Successfully installed geographiclib-1.50 geopy-1.21.0
    Collecting sklearn
      Downloading https://files.pythonhosted.org/packages/1e/7a/dbb3be0ce9bd5c8b7e3d87328e79063f8b263b2b1bfa4774cb1147bfcd3f/sklearn-0.0.tar.gz
    Requirement already satisfied: scikit-learn in /home/jupyterlab/conda/envs/python/lib/python3.6/site-packages (from sklearn) (0.20.1)
    Requirement already satisfied: numpy>=1.8.2 in /home/jupyterlab/conda/envs/python/lib/python3.6/site-packages (from scikit-learn->sklearn) (1.18.1)
    Requirement already satisfied: scipy>=0.13.3 in /home/jupyterlab/conda/envs/python/lib/python3.6/site-packages (from scikit-learn->sklearn) (1.4.1)
    Building wheels for collected packages: sklearn
      Building wheel for sklearn (setup.py) ... [?25ldone
    [?25h  Stored in directory: /home/jupyterlab/.cache/pip/wheels/76/03/bb/589d421d27431bcd2c6da284d5f2286c8e3b2ea3cf1594c074
    Successfully built sklearn
    Installing collected packages: sklearn
    Successfully installed sklearn-0.0
    Requirement already satisfied: folium in /home/jupyterlab/conda/envs/python/lib/python3.6/site-packages (0.5.0)
    Requirement already satisfied: requests in /home/jupyterlab/conda/envs/python/lib/python3.6/site-packages (from folium) (2.23.0)
    Requirement already satisfied: six in /home/jupyterlab/conda/envs/python/lib/python3.6/site-packages (from folium) (1.14.0)
    Requirement already satisfied: branca in /home/jupyterlab/conda/envs/python/lib/python3.6/site-packages (from folium) (0.4.0)
    Requirement already satisfied: jinja2 in /home/jupyterlab/conda/envs/python/lib/python3.6/site-packages (from folium) (2.11.1)
    Requirement already satisfied: chardet<4,>=3.0.2 in /home/jupyterlab/conda/envs/python/lib/python3.6/site-packages (from requests->folium) (3.0.4)
    Requirement already satisfied: urllib3!=1.25.0,!=1.25.1,<1.26,>=1.21.1 in /home/jupyterlab/conda/envs/python/lib/python3.6/site-packages (from requests->folium) (1.25.8)
    Requirement already satisfied: certifi>=2017.4.17 in /home/jupyterlab/conda/envs/python/lib/python3.6/site-packages (from requests->folium) (2020.4.5.1)
    Requirement already satisfied: idna<3,>=2.5 in /home/jupyterlab/conda/envs/python/lib/python3.6/site-packages (from requests->folium) (2.9)
    Requirement already satisfied: MarkupSafe>=0.23 in /home/jupyterlab/conda/envs/python/lib/python3.6/site-packages (from jinja2->folium) (1.1.1)
    Requirement already satisfied: matplotlib in /home/jupyterlab/conda/envs/python/lib/python3.6/site-packages (3.1.1)
    Requirement already satisfied: pyparsing!=2.0.4,!=2.1.2,!=2.1.6,>=2.0.1 in /home/jupyterlab/conda/envs/python/lib/python3.6/site-packages (from matplotlib) (2.4.6)
    Requirement already satisfied: python-dateutil>=2.1 in /home/jupyterlab/conda/envs/python/lib/python3.6/site-packages (from matplotlib) (2.8.1)
    Requirement already satisfied: numpy>=1.11 in /home/jupyterlab/conda/envs/python/lib/python3.6/site-packages (from matplotlib) (1.18.1)
    Requirement already satisfied: kiwisolver>=1.0.1 in /home/jupyterlab/conda/envs/python/lib/python3.6/site-packages (from matplotlib) (1.2.0)
    Requirement already satisfied: cycler>=0.10 in /home/jupyterlab/conda/envs/python/lib/python3.6/site-packages (from matplotlib) (0.10.0)
    Requirement already satisfied: six>=1.5 in /home/jupyterlab/conda/envs/python/lib/python3.6/site-packages (from python-dateutil>=2.1->matplotlib) (1.14.0)



```python
from bs4 import BeautifulSoup
from geopy.geocoders import Nominatim
from sklearn.cluster import KMeans
import requests
import pandas as pd
from pandas.io.json import json_normalize
import numpy as np
import folium
import matplotlib.cm as cm
import matplotlib.colors as colors
```


```python
!pip install lxml
```

    Requirement already satisfied: lxml in /home/jupyterlab/conda/envs/python/lib/python3.6/site-packages (4.5.0)



```python
# Get the HTML text from the wiki page
wiki_url = 'https://en.wikipedia.org/wiki/List_of_postal_codes_of_Canada:_M'
html_text = requests.get(wiki_url).text

# Extract the table data using BeautifulSoup
soup = BeautifulSoup(html_text)
table = soup.find('table')#, attrs={'class':'wikitable sortable'})
trs = table.find_all('tr')
```


```python
# Extract the text from all the table cells and add all rows
# to a list of rows.
rows = list()
for tr in trs:
    td = tr.find_all('td')
    row = [ele.text.strip() for ele in td]
    if row:
        # Ignore empty rows with no 'td',
        # applicable for the column headers row.
        rows.append(row)
        
# Convert the data to a pandas dataframe with 
# columns 'PostalCode', 'Borough', and 'Neighborhood'.
df = pd.DataFrame(rows,
                  columns=['PostalCode', 'Borough', 'Neighborhood'])
```


```python
# Remove rows with column 'Not assigned' for column 'Borough'
df = df[df.Borough != 'Not assigned']
df.reset_index(inplace=True, drop=True)
```


```python
df['Neighborhood'] = df.apply(
    lambda row: 
    row['Borough'] if row['Neighborhood'] == 'Not assigned' 
    else row['Neighborhood'],
    axis=1)
```

    /home/jupyterlab/conda/envs/python/lib/python3.6/site-packages/ipykernel_launcher.py:5: SettingWithCopyWarning: 
    A value is trying to be set on a copy of a slice from a DataFrame.
    Try using .loc[row_indexer,col_indexer] = value instead
    
    See the caveats in the documentation: https://pandas.pydata.org/pandas-docs/stable/user_guide/indexing.html#returning-a-view-versus-a-copy
      """



```python
df['Neighborhood'] = df['Neighborhood'].apply(lambda x: x.replace(', ', ',').split('/')).apply(', '.join)
```

    /home/jupyterlab/conda/envs/python/lib/python3.6/site-packages/ipykernel_launcher.py:1: SettingWithCopyWarning: 
    A value is trying to be set on a copy of a slice from a DataFrame.
    Try using .loc[row_indexer,col_indexer] = value instead
    
    See the caveats in the documentation: https://pandas.pydata.org/pandas-docs/stable/user_guide/indexing.html#returning-a-view-versus-a-copy
      """Entry point for launching an IPython kernel.



```python
# More than one neighborhood can exist in one postal code area.
# Combine rows with the same postal code into a single row.
# For example, in the table on the Wikipedia page, M5A is 
# listed twice and has two neighborhoods: Harbourfront and
# Regent Park. These two rows will be combined into one row
# with the neighborhoods separated with a comma.
df = df.groupby(['PostalCode', 'Borough'])['Neighborhood'].apply(', '.join).to_frame()
df.reset_index(inplace=True)
```


```python
df.head(12)
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>PostalCode</th>
      <th>Borough</th>
      <th>Neighborhood</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>M1B</td>
      <td>Scarborough</td>
      <td>Malvern ,  Rouge</td>
    </tr>
    <tr>
      <th>1</th>
      <td>M1C</td>
      <td>Scarborough</td>
      <td>Rouge Hill ,  Port Union ,  Highland Creek</td>
    </tr>
    <tr>
      <th>2</th>
      <td>M1E</td>
      <td>Scarborough</td>
      <td>Guildwood ,  Morningside ,  West Hill</td>
    </tr>
    <tr>
      <th>3</th>
      <td>M1G</td>
      <td>Scarborough</td>
      <td>Woburn</td>
    </tr>
    <tr>
      <th>4</th>
      <td>M1H</td>
      <td>Scarborough</td>
      <td>Cedarbrae</td>
    </tr>
    <tr>
      <th>5</th>
      <td>M1J</td>
      <td>Scarborough</td>
      <td>Scarborough Village</td>
    </tr>
    <tr>
      <th>6</th>
      <td>M1K</td>
      <td>Scarborough</td>
      <td>Kennedy Park ,  Ionview ,  East Birchmount Park</td>
    </tr>
    <tr>
      <th>7</th>
      <td>M1L</td>
      <td>Scarborough</td>
      <td>Golden Mile ,  Clairlea ,  Oakridge</td>
    </tr>
    <tr>
      <th>8</th>
      <td>M1M</td>
      <td>Scarborough</td>
      <td>Cliffside ,  Cliffcrest ,  Scarborough Village...</td>
    </tr>
    <tr>
      <th>9</th>
      <td>M1N</td>
      <td>Scarborough</td>
      <td>Birch Cliff ,  Cliffside West</td>
    </tr>
    <tr>
      <th>10</th>
      <td>M1P</td>
      <td>Scarborough</td>
      <td>Dorset Park ,  Wexford Heights ,  Scarborough ...</td>
    </tr>
    <tr>
      <th>11</th>
      <td>M1R</td>
      <td>Scarborough</td>
      <td>Wexford ,  Maryvale</td>
    </tr>
  </tbody>
</table>
</div>




```python
print("Dataframe shape: ", df.shape)
```

    Dataframe shape:  (103, 3)



```python

```
