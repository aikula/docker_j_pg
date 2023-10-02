FROM jupyter/scipy-notebook:latest

#RUN apt-get install -y --no-install-recommends \
#        wget curl git nano \  
#	; \
#	rm -rf /var/lib/apt/lists/*

#RUN apt-get update
#RUN /usr/bin/python3 -m pip install --upgrade pip
#RUN apt-get --yes install graphviz

# Install dependencies (for advanced authentication and spawning)

COPY requirements.txt /tmp/
RUN pip install --requirement /tmp/requirements.txt

#RUN chmod -R 777 /home