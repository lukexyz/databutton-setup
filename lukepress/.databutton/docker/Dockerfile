FROM europe-west1-docker.pkg.dev/databutton/public/databutton-base:0.24.5

WORKDIR /app

ARG DATABUTTON_TOKEN

ENV PYTHONBUFFERED=1

ENV DATABUTTON_TOKEN=$DATABUTTON_TOKEN

COPY requirements.txt ./requirements.txt
RUN pip install -r requirements.txt

COPY . /app

ENTRYPOINT ["databutton"]
