FROM python:2.7
ENV PYTHONUNBUFFERED 1
RUN mkdir /code
WORKDIR /code
ADD requirements.txt /code/
RUN pip install -r requirements.txt
ADD dev_requirements.txt /code/
RUN pip install -r dev_requirements.txt
ADD load_test/ /code/
