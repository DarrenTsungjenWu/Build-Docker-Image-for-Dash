FROM python:3.8

RUN mkdir -p /Dash-master/Dash

WORKDIR /Dash-master/Dash

COPY requirements.txt /Dash-master/Dash
RUN pip install --no-cache-dir -r requirements.txt

COPY . /Dash-master/Dash

EXPOSE 8070

CMD ["python", "Dash-py.py"]
