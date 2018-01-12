#### github
```bash
echo "# flask_movie" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/py-demo/flask_movie.git
git push -u origin master
```

#### virtualenv
````baah
virtualenv --python=python3 venv
````

#### structure
````bash
App.py
conf
  config.py
static
  css
  js
template
  admin
  home
````