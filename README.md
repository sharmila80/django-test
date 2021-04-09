# django-test

## Install

For local instance:

```sh
git clone ssh://git@bitbucket.be-md.ncbi.nlm.nih.gov:9418/dbgap/dbgap-public-utils.git
cd django-test
virtualenv -p python3 ve && source ve/bin/activate
pip install -r requirements.txt -e .
cd mytest
manage.py migrate
```

## Run

Use unique port:

```
manage.py runserver 0.0.0.0:<select_port_number>
```

Access application at:

```
http://<server_name_or_ip>:<selected_port>/
```