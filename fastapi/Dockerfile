FROM python:3.13-slim

WORKDIR /HW3-Assigned

COPY * ./

RUN pip install -r requirements.txt

EXPOSE 8000

CMD fastapi run fastapi/extract_save_data.py --server.address 0.0.0.0