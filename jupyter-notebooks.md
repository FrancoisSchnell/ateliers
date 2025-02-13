
# 📖 Atelier Jupyter notebooks

## 🔎 What ?
- 📓 **[paper notebook](https://img.notionusercontent.com/s3/prod-files-secure%2Fdf6eca03-e878-42ae-a432-dececbe15ba9%2F856029d5-b55e-4424-b766-db5457f88db9%2FUntitled.png/size/w=1060?exp=1739458759&sig=5PIvIZlvIviKYqp6XpdAhzsPKjmzW_LSjs7VC2GJkew)** (free form but difficult to replicate, share, collaborate, not for big data or big calculus)
-  💻 **digital notebook** (**pdf ?** not easy to edit, collaborate, calculate...  **Html ?** not easy to read-edit... )
- 🪐 **Jupyter notebook**
	- inspiration : Matlab, Sage, Mapple, Mathematica...
	- But automatically in a HMTL page + server + kernel
	- IPynotebook (2011), Jupyter notebook (2014)
	- open format : .ipynb from [json](https://en.wikipedia.org/wiki/JSON#Syntax)
	- extensible with extensions
	- [examples](https://gist.github.com/ocoyawale/54d92fd4bf92508a2a6e482b5fa480fd)

## 🧑‍🤝‍🧑 Who, Why ?
- **researchers** (2018 : 2.5M notebooks on Github, [Nature](https://www.nature.com/articles/d41586-018-07196-1))
- **teachers** (Practical work, [measuring the speed of sound](https://www.youtube.com/watch?v=6Ir5wv18xhk&t=137s), [Learning Python](https://colab.research.google.com/drive/1RgvNaEXa7Aqnn8uc1fdYxymGnCfD9Bom?usp=sharing))
- **data journalists** ([Covid inquiry](https://www.rue89strasbourg.com/la-surmortalite-en-alsace-pendant-la-periode-covid-vue-depuis-les-chiffres-de-linsee-177809))
- **you** ?
## 🧰 How ?
### 📌 Local 
- 🐍 python 3 
	- `pip install notebook pandas matplotlib`
	-  launch in console : `jupyter notebook` or `python -m notebook`
	- use Visual Studio Code and extension Copilot
-  🐍 [anaconda](https://www.anaconda.com/)
### 🌐 Online 
- 🥇 [colab.research.google.com](https://colab.research.google.com/) (great for learning, with gemini ai)
- [Jupyter Hub](https://jupyter.org/hub) (Open source, local server)
- [Kaggle](https://www.kaggle.com/code)
### 📚 Libraries
- 🪐 [Jupyter](https://jupyter.org/) 🥧 [Numpy](https://numpy.org/) 🐼 [Pandas](https://pandas.pydata.org/) 📊 [Matplotlib](https://matplotlib.org/)
- 🔲 cells of code versus [markdown](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
##  🎯 Challenge
### ⛵ Titanic inquiry
👉 Goals :
- use the csv file (data) : [http://mob.u-strasbg.fr/lab/titanic.csv](https://www.google.com/url?q=http%3A%2F%2Fmob.u-strasbg.fr%2Flab%2Ftitanic.csv)
- find the youngest and oldest passengers
- plot the age demographic
- plot a pie of the number of passengers per class
- find the survival probability depending of the class, the sex, and age.

🏆 Result :
- Jupyter [notebook](https://colab.research.google.com/drive/1u28fouG3Lor8ehJM8yy6wYL6tPih-utx) (Colab)
- screencast : [old](https://www.youtube.com/watch?v=FNDWAybVPcc) (without ai)