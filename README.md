 # Polars Essentials Training Exercises
 
 This repository contains the exercises for the Polars Essentials training course.
 
 ## Getting Started

 We recommend using [uv](https://docs.astral.sh/uv/) for fast and reliable dependency management.

 ### Option 1: Using uv (Recommended)

 ```bash
 # Install uv if you haven't already
 curl -LsSf https://astral.sh/uv/install.sh | sh  # On macOS/Linux

 git clone https://github.com/TNieuwdorp/polars-essentials.git
 cd polars-essentials
 uv sync
 uv run jupyter lab
 ```

 ### Option 2: Using standard pip

 If you prefer not to use `uv`, you can use standard `pip`:

 ```bash
 git clone https://github.com/TNieuwdorp/polars-essentials.git
 cd polars-essentials
 python -m venv .venv
 source .venv/bin/activate  # On Windows use `.venv\Scripts\activate`
 pip install .
 jupyter lab essentials-day-1.ipynb
 ```
