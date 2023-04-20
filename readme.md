Preparation
-----------
- create repo
    - python as ignore
- Clone
- python -m venv venv
  - Activate it
- pip install --upgrade pip (IF NEEDED)
- pip install mkdocs-material


Setup
----------
1. Create a virtual environment
```python -m venv venv```

2. Install dependencies
```pip install -r requirements.txt```

3. Run
`mkdocs serve`

MK Docs setup
-------------
- Iniate docs `mkdocs new .`
- Run loacally `mkdocs serve`
- 

Apply theme
```
theme:
  name: material
```

Follow next steps to install `cinder` theme https://sourcefoundry.org/cinder/

install extensions
pip install mkdocs-material

publishing
----------
- create `.github/workflows` directory
- Create `ci.yml`
- paste from this sample
- Push chanes
- Settings>Pages>From branch>gh-pages

Resources
- [How to: Youtube](https://www.youtube.com/watch?v=Q-YA_dA8C20) 
- [Repo with demo](https://github.com/james-willett/mkdocs-material-youtube-tutorial)
- [Install custom theme](https://sourcefoundry.org/cinder/)
- [MK Docs material](https://squidfunk.github.io/mkdocs-material/)

