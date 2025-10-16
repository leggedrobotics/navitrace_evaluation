# NaviTrace Evaluation

This repository contains example code on how to evaluate models on our benchmark [NaviTrace](https://leggedrobotics.github.io/navitrace_webpage/), including model inference via API and the score calculation.
The benchmark consists of a validation split and a test split with hidden ground-truths.
If you want to see how your model scores on the test set or want to submit your model to the leaderboard, check out this [Hugging Face Space](https://huggingface.co/spaces/leggedrobotics/navitrace_leaderboard).

## Setup

1. Clone this repository `git clone https://github.com/leggedrobotics/navitrace_evaluation.git`
2. Create and activate a Python 3.10 environment with your preferred tools
3. `pip install -r ./requirements.txt`
4. Prepare an API key and base URL for the model that you want to evaluate

## Usage

- Run the notebook `src/run_evaluation.ipynb`, e.g. with `jupyter lab src/run_evaluation.ipynb`
