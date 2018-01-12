#### git
```bash
echo "# flask_movie" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/py-demo/flask_movie.git
git push -u origin master
```

#### virtualenv
```base
virtualenv venv --python=python3
```

#### pip install 
````bash
pip install flask
````

#### pip list
```base
pip list --format=columns
```

<pre>
Package      Version
------------ -------
click        6.7    
Flask        0.12.2 
itsdangerous 0.24   
Jinja2       2.10   
MarkupSafe   1.0    
pip          9.0.1  
setuptools   38.4.0 
Werkzeug     0.14.1 
wheel        0.30.0 
</pre>

- 安装或升级：

> pip freeze > requirements.txt


- 导入\安装：
> pip install -r requirements.txt

#### structure
<pre>
manage.py
app
  models.py
  conf
    config.py
  admin
    forms.py
    views.py
  home
    forms.py
    views.py
  template
    admin
      index.html
    home
      index.html
  static
    css
      app.css
    js
      app.js
</pre>