FROM python:3.11
WORKDIR /app
COPY  . /app
RUN pip install -r requeriments.txt
EXPOSE 5000

CMD ["jupyter", "notebook", "--ip=0.0.0.0", "--port=8888", "--no-browser", "--allow-root"]
#CMD ["python", "mlflow_nb.ipynb"]
