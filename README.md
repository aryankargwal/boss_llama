# Boss Llama 🦙
[![Made with - Tune Studio](https://img.shields.io/static/v1?label=Made+with&message=Tune+Studio&color=%236E18FB)](https://)
[![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)](https://www.python.org/)
[![PyPI license](https://img.shields.io/pypi/l/ansicolortags.svg)](https://pypi.python.org/pypi/ansicolortags/)
![Streamlit Badge](https://img.shields.io/badge/Streamlit-FF4B4B?logo=streamlit&logoColor=fff&style=flat-square)

Welcome to Boss Llama, an LLM aided Interview Simulation Web Application. The web-applications gives the users the ability to seamlessly integrate [Tune Studio](https://studio.tune.app/playground) and Streamlit for Smart Interview Simulation. This simple implementation aims to showcase handling textual data and basic web application workings such as creating and downloading reports and files using [Llama 3.1 70B](https://ai.meta.com/blog/meta-llama-3-1/), sourced from Tune Studio API. 

## Steps to Run
#### Clone the Repository
``` git clone https://github.com/aryankargwal/boss_llama.git```
#### Install Dependencies
``` pip install -r requirements.txt```
#### Run Streamlit Application
``` streamlit run app.py```
#### Put Tune Studio API Key
##### Download your Tune Studio API Key from `Personal>View API Keys`
<img src = "assets/1.png">

#### Tweak Parameters and Put Job Description
<img src = "assets/2.png">

#### Download Evaluation Report
<img src = "assets/3.png">

## Possible Features
- [ ] Upload Resume for personal interview
- [ ] VLM Integration

## Further Reading
- [Llama 3.1 Integration with Tune Studio](https://tunehq.ai/blog/tune-ai-integrates-latest-llama-3-1)
- [Finetuning on Tune Studio](https://tunehq.ai/blog/finetuning-llms)

## License
This repository is under the MIT License. Read more [here](LICENCE).

