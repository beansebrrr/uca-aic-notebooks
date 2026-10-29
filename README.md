# Artificial Intelligence for Creativity

I'm currently studying Computer Science in the University for the Creative Arts. This subject is making good use of Jupyter notebooks, so I'm taking it upon myself to set up a repository of my work and activities (I didn't like that additional files would erase themselves in Google Colab).

## Usage

I'm using [uv](https://docs.astral.sh/uv/) for my Python environment, and I do my work in Jupyter Lab. If you want to get a feel for my setup, try this:

1. Clone this repository and open a terminal within the folder
2. Run the following commands to set up the virtual environment

```shell
# Initialize the virtual environment
uv venv

# Activate the venv. It's either...
source .venv/bin/activate # for Linux and Mac, or...
.venv\Scripts\activate    # for Windows

# Download the project's dependencies
uv pip install -r pyproject.toml

# Activate the Jupyter Lab environment
uv run jupyter lab
```

3. Once you run `uv run jupyter lab`, the terminal may turn a little funky, but you'll also be redirected to `localhost:8888/lab`

There we goes. Welcome to my "I really disliked Google Colab but I didn't want to install Conda" setup
