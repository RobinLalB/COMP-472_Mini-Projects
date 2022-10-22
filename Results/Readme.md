Instructions:
- Open the .ipynb notebook in Jupyter
- The code can be ran in one go by selecting "restart the kernel, then re-run the whole notebook"
	- This will run all the models sequentially, including the versions with embeddings
	- This will not run the 2.5 (no stop words) and 3.8 (different embedding models)
	- The output files will be created in the .ipynb directory

- To run the 2.5 - No stop words version:
	- Delete line 2 in the cell following "Process Dataset (NO STOP WORDS VERSION)"
	- Re-run all the code
	
- To run the 3.8 - Different embedding models version(s):
	- Uncomment one of the gensim embedding models in the cell following "Embeddings" and comment out the two others
	- Re-run the remaining cells

- Notes on MLPs:
	- It is possible to interrupt the Base MLPs to get results faster.