# Getting Started

Perform `make install` to install dependencies

```bash
$ make install
ansible-galaxy install -r requirements.yml
- downloading role 'postgresql', owned by geerlingguy
- downloading role from https://github.com/geerlingguy/ansible-role-postgresql/archive/1.3.2.tar.gz
- extracting geerlingguy.postgresql to /home/yomateod/.ansible/roles/geerlingguy.postgresql
- geerlingguy.postgresql (1.3.2) was installed successfully
pip install --upgrade botocore boto3 boto
Requirement already up-to-date: botocore in /home/yomateod/.local/lib/python2.7/site-packages
Requirement already up-to-date: boto3 in /home/yomateod/.local/lib/python2.7/site-packages
Requirement already up-to-date: boto in /home/yomateod/.local/lib/python2.7/site-packages
Requirement already up-to-date: jmespath<1.0.0,>=0.7.1 in /home/yomateod/.local/lib/python2.7/site-packages (from botocore)
Requirement already up-to-date: python-dateutil<2.7.0,>=2.1 in /home/yomateod/.local/lib/python2.7/site-packages (from botocore)
Requirement already up-to-date: docutils>=0.10 in /home/yomateod/.local/lib/python2.7/site-packages (from botocore)
Requirement already up-to-date: s3transfer<0.2.0,>=0.1.10 in /home/yomateod/.local/lib/python2.7/site-packages (from boto3)
Requirement already up-to-date: six>=1.5 in /home/yomateod/.local/lib/python2.7/site-packages (from python-dateutil<2.7.0,>=2.1->botocore)
Requirement already up-to-date: futures<4.0.0,>=2.2.0; python_version == "2.6" or python_version == "2.7" in /home/yomateod/.local/lib/python2.7/site-packages (from s3transfer<0.2.0,>=0.1.10->boto3)
```