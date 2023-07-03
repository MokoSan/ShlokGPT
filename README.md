# Shlok-GPT

This repo hosts code that generates Sanskrit Shloks with AI and uses Text to Speech for the Shloks.This app is hosted [here](https://shlok-gpt.streamlit.app/).

## Getting Started Locally

### Prerequisites

1. Acquire an OpenAI Key by following instructions from here.
2. Acquire an API Key from [Narkeet](https://www.narakeet.com/).
3. Create a Supabase account from [here](https://supabase.com/), create a bucket called "shlok" and generate the Supabase Url and Key. Ensure that the policy for the "shlok" bucket is set to allow reads, writes, deletes and updates.

### How to Run Locally

1. Ensure you have python 3.8+.
2. Clone the repo: git clone https://github.com/MokoSan/ResumeChain.git.
3. Install [pipenv](https://pipenv.pypa.io/en/latest/) and run: ``pipenv shell``.
4. Ensure you install all the prerequistes.
4. Ensure you have streamlit in your path.
5. Copy the .env.example file into a .env file and enter your OpenAI API Key, Narkeet API Key, Supabase Url, Supabase Key.
6. To run: ``streamlit run shlok.py``.

## Contributions

Contributions are welcomed and encouraged! If you run into any problems, create issues on this repository.

## License

This project is licensed under the [MIT License](https://github.com/git/git-scm.com/blob/main/MIT-LICENSE.txt).