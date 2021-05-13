FROM tiangolo/uwsgi-nginx:python3.8-alpine
RUN pip install redis --trusted-host pypi.org --trusted-host pypi.python.org --trusted-host=files.pythonhosted.org
ADD /azure-vote /app
