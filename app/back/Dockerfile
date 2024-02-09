FROM python:3.8

WORKDIR /app

COPY . /app

RUN pip install -r requirements.txt

EXPOSE 5000

ENV CURRENT_ENVIRONMENT development

CMD ["python3", "-m", "flask", "run", "--host=0.0.0.0"]