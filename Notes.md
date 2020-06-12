C:\Tutorials\django-job-board>python -m venv venv

C:\Tutorials\django-job-board>cd venv

C:\Tutorials\django-job-board\venv>pip freeze
astroid==2.3.2
Babel==2.3.4
beautifulsoup4==4.8.2
certifi==2019.11.28
chardet==3.0.4
colorama==0.4.1
decorator==4.0.10
docutils==0.12
ebaysdk==2.1.5
feedparser==5.2.1
html2text==2016.9.19
idna==2.7
isort==4.3.21
Jinja2==2.10.1
lazy-object-proxy==1.4.3
libsass==0.20.0
lxml==4.4.2
Mako==1.0.4
MarkupSafe==0.23
mccabe==0.6.1
mock==2.0.0
num2words==0.5.6
ofxparse==0.16
passlib==1.6.5
pbr==5.4.4
Pillow==6.2.1
polib==1.1.0
psutil==5.7.0
psycopg2==2.8.5
pycodestyle==2.5.0
pydot==1.2.3
pylint==2.4.3
pyparsing==2.1.10
PyPDF2==1.26.0
pypi==2.1
pypiwin32==223
pyserial==3.1.1
python-dateutil==2.5.3
python-stdnum==1.12
pytz==2016.7
pyusb==1.0.0
pywin32==227
qrcode==5.3
reportlab==3.5.42
requests==2.20.0
six==1.12.0
soupsieve==1.9.5
suds-jurko==0.6
urllib3==1.24.3
vatnumber==1.2
virtualenv==16.7.9
vobject==0.9.3
Werkzeug==0.11.15
wkhtmltopdf==0.2
wrapt==1.11.2
xlrd==1.0.0
XlsxWriter==0.9.3
xlwt==1.3.0

C:\Tutorials\django-job-board\venv>pip install django


C:\Tutorials\django-job-board>venv\Scripts\activate

(venv) C:\Tutorials\django-job-board>
################################################
echo "# django-job-board" >> README.md
git init
git add .
git commit -m "first commit"
git remote add origin https://github.com/lahbibbichr/django-job-board.git
git push -u origin master
################################################

##############
## Model
python manage.py makemigrations
python manage.py migrate
##############