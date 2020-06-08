ARG BASE_CONTAINER=jupyter/base-notebook
FROM $BASE_CONTAINER

RUN conda install psycopg2 plotly dash textwrap

USER root

EXPOSE 8888
WORKDIR $HOME

# Configure container startup
ENTRYPOINT ["tini", "-g", "--"]
CMD ["start-notebook.sh"]