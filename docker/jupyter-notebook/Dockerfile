FROM jupyter/scipy-notebook:x86_64-2023-10-20

# Install python packages
COPY ./requirements.txt /etc/notebook/requirements.txt
RUN pip3 install -r /etc/notebook/requirements.txt

EXPOSE 80 443

CMD ["jupyter", "notebook"]
