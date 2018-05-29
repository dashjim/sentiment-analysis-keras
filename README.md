# sentiment-analysis-keras
Using LSTM model for now.

This sample is based on a Kaggle dataset and can run directly with the Kaggle python3 docker image with its Jupyter Notebook.

If you have docker installed, you can run the code by executing the following line, it will first download the kaggle docker image if you didn't have it before , but this is going to require at least 16G disk space. And then it will start Jupyter Notebook in the current directory.

```
docker run --network='host' -v $PWD:/tmp/working -w=/tmp/working --rm -it kaggle/python:latest jupyter notebook --no-browser --allow-root --notebook-dir=/tmp/working 
```
