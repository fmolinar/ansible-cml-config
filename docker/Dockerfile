FROM python:3.8
RUN apt-get update
RUN pip install ansible==2.9.13
RUN pip install paramiko==2.7.2
RUN ansible-galaxy collection install cisco.nxos
RUN pip install 'pyats[full]'
