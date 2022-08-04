FROM python:3.8.13-buster

RUN pip install -U platformio
RUN pio upgrade --dev
# To get the test platforms
RUN pip install PyYaml
#ENV PATH /code/buildroot/bin/:/code/buildroot/tests/:${PATH}
