FROM python:3.9

RUN mkdir -p "/home/test"
RUN touch /home/test/sample.txt

EXPOSE 8000

CMD ["sh","-c", "cd /home/test && python -m http.server"]
