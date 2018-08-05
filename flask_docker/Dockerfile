FROM python:alpine
MAINTAINER Sujay Pillai<sujayopillai@gmail.com>

COPY . /src
WORKDIR /src
RUN pip install -r requirements.txt
EXPOSE 5000
ENTRYPOINT ["python"]
CMD ["app.py"]
