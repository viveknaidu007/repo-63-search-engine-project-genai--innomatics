# repo-63-search-engine-project-genai--innomatics
here im developing a A.I model , where it will give informatoin about the query we typed based on its tarined data

#for dataset download : 
https://drive.google.com/drive/folders/1ZJtMu05v2QcFsL1M8y5NMWJFQ2bZCljC

#creating environent
conda create --name anyname python=3.10
conda activate anyname

#activating
conda activate anyname

#for removing any environemtn:
conda env remove --name nameofurenv

#install packages
pip install -r requirements.txt

pip install scikit-learn
pip install torch
pip install pandas
pip install numpy
pip install sentence-transformers
pip install chromadb

https://www.sbert.net/docs/pretrained_models.html
#above all are pretrained BERT models
#we can use any model based on our requirement

*************************************************************************************
steps 
* run the 1 file for getting the chunked_data.csv   
* run the 4 file for saving the model with embeddings         
* run the 5 file for creating chromadb and saving the embeddings locally 
* run app.py

#app.py
-this is our final file to run the code 

To run:
streamlit run app.py
ctrl + c , to stop

#note: 
after run the 5.chromadb.ipynb file , it will create chromafb folder and save the embeddings
so , now run the streamlit run app.p.py