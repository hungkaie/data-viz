# data-viz

I am a data scientist full of research spirit and enthusiasm. This project mainly uses notes written for myself to briefly record some content related to data visualization. Whether you are a data scientist, an AI algorithm engineer, or a statistician, you are welcome to communicate with me about data visualization, algorithms, or statistics!

# How to install packages in Python?
I recommend using [virtualenv](https://virtualenv.pypa.io/en/latest/).

1. Create virtual environment called "env".

  ```bash=
  $ virtualenv env
  ```

2. Activate the environment.
  - For linux user:
  
  ```bash=
  $ source env/bin/activate
  ```

  - For windows user:
  
  ```bash=
  $ .\env\Scripts\activate
  ```

3. Install packages in `requirements.txt`.

  ```bash=
  $ pip install -r requirements.txt
  ```

# How to install packages in R?
I recommend using [renv](https://rstudio.github.io/renv/index.html).

1. Open R project.

2. Install `renv` package.

  ```r=
  renv::init()
  ```

3. Reinstall packages in lock file.

  ```r=
  renv::restore()
  ```
