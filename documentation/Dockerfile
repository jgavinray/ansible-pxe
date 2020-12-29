FROM python:3.8.7
COPY ./ /docs
WORKDIR /docs
RUN pip install mkdocs
RUN pip install mkdocs-material
CMD ["mkdocs", "serve", "-a", "0.0.0.0:8000"]
