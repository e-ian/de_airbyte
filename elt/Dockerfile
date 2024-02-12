FROM python:3.8-slim

# install PostgreSQl command-line tools
RUN apt-get update && apt-get install -y postgresql-client

COPY elt_script.py .

# set the default command to run the ELT script
CMD [ "python", "elt_script.py" ]
