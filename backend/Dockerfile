FROM python:3.6.3-slim-stretch
WORKDIR /bbct
ADD . /bbct
RUN pip install -r requirements.txt
EXPOSE 8000
CMD ["python", "manage.py", "runserver"]
