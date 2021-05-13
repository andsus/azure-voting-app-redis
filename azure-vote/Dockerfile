FROM tiangolo/uwsgi-nginx-flask:python3.6
RUN pip install redis --trusted-host pypi.org --trusted-host pypi.python.org --trusted-host=files.pythonhosted.org
RUN apk --no-cache add curl
ADD /azure-vote /app
