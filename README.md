# Anniversary-project
Using Data Science methods and techniques to construct a restaurant recommender in Vancouver for inexperienced people in relationship for their anniversary.



## Contributors
* Viet Anh Duong:
Constructed model, implemented experiments, filtered data, handled visualization.

* Maruku Nguyen:
Modelized evaluation metric, collected data.


## Set up
Requirements: Git, Python 3.8.8, and Jupyter Notebook installed on your machine.


To replicate our results, the requirements Python packages are specified in requirements.txt. To install: 

(Optional) A virtual machine is highly recommended. Set up guidance:
* With conda:
```bash
conda create -n venv python=3.8.8
```
```bash
conda activate venv
```
```bash
conda install --file requirements.txt
```

* Without conda:
```bash
python3 -m venv venv
```
```bash
souce venv/bin/activate
```
```bash
pip3 install -r requirements.txt
```



## Analysis
```bash
jupyter lab
```
* Run `data_handler.ipynb` in Jupyter Notebook to replicate the results and and the model.