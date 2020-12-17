## Build the image based on python3 
FROM python:3 

## Copy all the packages 
COPY . /app

## Change the default folder 
WORKDIR /app 

## Install all packages 
RUN pip install -r requirements.txt 

## Default port is 5000

EXPOSE 5000 

## When container is started Run the application 
CMD ["/bin/sh", "-c", "python /app/app.py"]