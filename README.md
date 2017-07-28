You can click on the notebook file above to view it. To get this running locally, do this on your terminal:

0. Have `git` installed (if you haven't, do `sudo dnf install git` or `sudo apt install git`, depending on your OS).
1. Clone this repo (`git clone https://github.com/Ed-von-Schleck/marina_nlp.git`)
2. Change the directory (`cd marina_nlp')
3. Make a python virtual environment (`python3 -m venv nlp`)
4. Activate it (`source nlp/bin/activate')
5. Install the dependencies (`pip install -r requirements.txt`)
6. Install spacy language models (`python -m spacy download en` - replace the last word with `de` or another language code if you want to use that as well)
7. Start the jupyter notebook (`jupyter notebook`)
