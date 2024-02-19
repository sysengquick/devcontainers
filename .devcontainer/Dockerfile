FROM python:3.11

RUN python3 -m pip install 'ansible-core<2.14' ansible-lint fqdn

# Create the vscode user
RUN useradd -m -s /bin/bash vscode
