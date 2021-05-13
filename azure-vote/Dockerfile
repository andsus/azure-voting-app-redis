FROM tiangolo/uwsgi-nginx:python3.8-alpine
RUN pip install redis --trusted-host pypi.org --trusted-host pypi.python.org --trusted-host=files.pythonhosted.org
RUN apk --no-cache add curl
ADD /azure-vote /app
