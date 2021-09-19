# Privacy-Preservation-of-Hidden-Sensitive-Data
This is sample coding for the article of "A Hybrid Approach for Privacy Preservation of IIoT Data"

Please note that this code has been prepared for an academic research.
The dataset is publicly available from the following link: "https://www.kaggle.com/wasuratme96/iiot-data-of-wind-turbine"
The algorithm has been prepared on Windows operating system with Jupyter 6.3.0.

To run the GAN functions, you need to activate gan from Anaconda-Prompt Screen as defined below:
$conda activate gan
$conda install -c pytorch pytorch=1.4.0
$conda install matplotlib jupyter
$python -m ipykernel install --user --name gan

After that point, you need to open Jupyter Notebook by running Jupyter notebook. 
Create a new Notebook by clicking New and then selecting gan.

You need to use the following libraries:
pip install plotly_express==0.4.0
pip install CTGAN
pip install pandas
pip install seaborn
