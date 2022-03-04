FROM jupyter/scipy-notebook:33add21fab64

# Install python packages
COPY ./requirements.txt /etc/notebook/requirements.txt
RUN pip3 install -r /etc/notebook/requirements.txt

EXPOSE 80 443

CMD ["jupyter", "notebook"]
