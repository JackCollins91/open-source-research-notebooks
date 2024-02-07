# Open Source Research Notebooks
A collection of Jupyter Notebooks that demo and can be used during investigations to run command line tools, scripts, and methods. We aim to help open source researchers, journalists, and fact-checkers use command line tools and code projects for digital investigations.

### Is this for me?
If you've used Jupyter notebooks before you should be good to navigate this right away.

If Jupyter Notebooks/Google Colaboratory don't ring any bells, you should know they are one of the easiest ways to interact with code and the command line, in essence they look like an interactive website where you execute one cell at a time to run a piece of code, you can also edit the pieces of code to adapt them to your needs. 

There's plenty of good tutorials about Jupyter Notebooks and the environments you can run them in (like Google Colab or Binder.org), we do advise you to spend 5min doing that. Additionally, we created a simple notebook that you can [view](TODO), [run on Google Colab](TODO), or [run on Binder](TODO) that shows the core skills needed to understand what this is all about!

### Why Notebooks?
Jupyter Notebooks
- make it easier to install and run software (less "this does not work on my machine" errors)
- make it safer to run unknown code, when you run it on a Notebook service like [Google Colaboratory](https://colab.google/) or [Binder](https://mybinder.org/)
- make it simpler to document specific code uses: they combine styled documentation with code
- are quick to make and easy to use after you understand how to click through the code cells and edit any custom input
- can run bash commands (command line) as well as code (Python and more)

# Available Notebooks
The top part of the table consists of tools and methods developed at Bellingcat; the bottom part of community developed tools and methods.
|           **Notebook**            | **Level**               | **Description**                                          | **Notebook links**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | **Tags**                               |
| :-------------------------------: | ----------------------- | -------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | -------------------------------------- |
| **Telegram Phone Number Checker** | ![easy][easy-badge]     | Check if phone numbers have associated Telegram accounts | [![Colab][colab-badge]](https://colab.research.google.com/github/bellingcat/open-source-research-notebooks/blob/main/notebooks/bellingcat/telegram-phone-number-checker.ipynb) [![Binder][binder-badge]](https://mybinder.org/v2/gh/bellingcat/open-source-research-notebooks/main?labpath=notebooks%2Fbellingcat%2Ftelegram-phone-number-checker.ipynb) [![Kaggle Notebook][kaggle-badge]](https://kaggle.com/kernels/welcome?src=https://github.com/bellingcat/open-source-research-notebooks/blob/main/notebooks/bellingcat/telegram-phone-number-checker.ipynb) [![Jupyter Notebook][jupyter-badge]](notebooks/bellingcat/telegram-phone-number-checker.ipynb) | `scraping`, `social-media`, `telegram` |
|   **Wayback Google Analytics**    | ![easy][easy-badge]     | Uncover historical analytics ids via the Wayback Machine | [![Colab][colab-badge]](https://colab.research.google.com/github/bellingcat/open-source-research-notebooks/blob/main/notebooks/bellingcat/wayback-google-analytics.ipynb) [![Binder][binder-badge]](https://mybinder.org/v2/gh/bellingcat/open-source-research-notebooks/main?labpath=notebooks%2Fbellingcat%2Fwayback-google-analytics.ipynb) [![Kaggle Notebook][kaggle-badge]](https://kaggle.com/kernels/welcome?src=https://github.com/bellingcat/open-source-research-notebooks/blob/main/notebooks/bellingcat/wayback-google-analytics.ipynb) [![Jupyter Notebook][jupyter-badge]](notebooks/bellingcat/wayback-google-analytics.ipynb)                     | `wayback-machine`, `google-analytics`  |
|         **Geoclustering**         | ![medium][medium-badge] | Find clusters of incidents from a CSV of incidents       | [![Colab][colab-badge]](https://colab.research.google.com/github/bellingcat/open-source-research-notebooks/blob/main/notebooks/bellingcat/geoclustering.ipynb) [![Binder][binder-badge]](https://mybinder.org/v2/gh/bellingcat/open-source-research-notebooks/main?labpath=notebooks%2Fbellingcat%2Fgeoclustering.ipynb) [![Kaggle Notebook][kaggle-badge]](https://kaggle.com/kernels/welcome?src=https://github.com/bellingcat/open-source-research-notebooks/blob/main/notebooks/bellingcat/geoclustering.ipynb) [![Jupyter Notebook][jupyter-badge]](notebooks/bellingcat/geoclustering.ipynb)                                                                 | `ai`, `clustering`, `gis`              |
|        **vk-url-scraper**         | ![medium][medium-badge] | Scrape data and download media from VKontakte URLs       | [![Colab][colab-badge]](https://colab.research.google.com/github/bellingcat/open-source-research-notebooks/blob/main/notebooks/bellingcat/vk-url-scraper.ipynb) [![Binder][binder-badge]](https://mybinder.org/v2/gh/bellingcat/open-source-research-notebooks/main?labpath=notebooks%2Fbellingcat%2Fvk-url-scraper.ipynb) [![Kaggle Notebook][kaggle-badge]](https://kaggle.com/kernels/welcome?src=https://github.com/bellingcat/open-source-research-notebooks/blob/main/notebooks/bellingcat/vk-url-scraper.ipynb) [![Jupyter Notebook][jupyter-badge]](notebooks/bellingcat/vk-url-scraper.ipynb)                                                             | `scraping`, `social-media`             |
|                 -                 | -                       | -                                                        | -                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | -                                      |
|        **OpenAI Whisper**         | ![easy][easy-badge]     | AI audio/video transcription and translation             | [![Colab][colab-badge]](https://colab.research.google.com/github/bellingcat/open-source-research-notebooks/blob/main/notebooks/community/whisper.ipynb) [![Binder][binder-badge]](https://mybinder.org/v2/gh/bellingcat/open-source-research-notebooks/main?labpath=notebooks%2Fcommunity%2Fwhisper.ipynb) [![Kaggle Notebook][kaggle-badge]](https://kaggle.com/kernels/welcome?src=https://github.com/bellingcat/open-source-research-notebooks/blob/main/notebooks/community/whisper.ipynb) [![Jupyter Notebook][jupyter-badge]](notebooks/community/whisper.ipynb)                                                                                             | `ai`, `speech-recognition`             |
|            **Holehe**             | ![easy][easy-badge]     | Find accounts associated with an email                   | [![Colab][colab-badge]](https://colab.research.google.com/github/bellingcat/open-source-research-notebooks/blob/main/notebooks/community/holehe.ipynb) [![Binder][binder-badge]](https://mybinder.org/v2/gh/bellingcat/open-source-research-notebooks/main?labpath=notebooks%2Fcommunity%2Fholehe.ipynb) [![Kaggle Notebook][kaggle-badge]](https://kaggle.com/kernels/welcome?src=https://github.com/bellingcat/open-source-research-notebooks/blob/main/notebooks/community/holehe.ipynb) [![Jupyter Notebook][jupyter-badge]](notebooks/community/holehe.ipynb)                                                                                                 | `digital-footprint-tracing`            |
|            **Maigret**            | ![easy][easy-badge]     | Find accounts associated with a username                 | [![Colab][colab-badge]](https://colab.research.google.com/github/bellingcat/open-source-research-notebooks/blob/main/notebooks/community/maigret.ipynb) [![Binder][binder-badge]](https://mybinder.org/v2/gh/bellingcat/open-source-research-notebooks/main?labpath=notebooks%2Fcommunity%2Fmaigret.ipynb) [![Kaggle Notebook][kaggle-badge]](https://kaggle.com/kernels/welcome?src=https://github.com/bellingcat/open-source-research-notebooks/blob/main/notebooks/community/maigret.ipynb) [![Jupyter Notebook][jupyter-badge]](notebooks/community/maigret.ipynb)                                                                                             | `digital-footprint-tracing`            |
|  **Wayback Machine Downloader**   | ![easy][easy-badge]     | Download an entire website from the Wayback Machine.     | [![Colab][colab-badge]](https://colab.research.google.com/github/bellingcat/open-source-research-notebooks/blob/main/notebooks/community/wayback-machine-downloader.ipynb) [![Binder][binder-badge]](https://mybinder.org/v2/gh/bellingcat/open-source-research-notebooks/main?labpath=notebooks%2Fcommunity%2Fwayback-machine-downloader.ipynb) [![Kaggle Notebook][kaggle-badge]](https://kaggle.com/kernels/welcome?src=https://github.com/bellingcat/open-source-research-notebooks/blob/main/notebooks/community/wayback-machine-downloader.ipynb) [![Jupyter Notebook][jupyter-badge]](notebooks/community/wayback-machine-downloader.ipynb)                 | `wayback-machine`                      |
|           **ExifTool**            | ![medium][medium-badge] | Extract and analyse file metadata tags                   | [![Colab][colab-badge]](https://colab.research.google.com/github/bellingcat/open-source-research-notebooks/blob/main/notebooks/community/exiftool.ipynb) [![Binder][binder-badge]](https://mybinder.org/v2/gh/bellingcat/open-source-research-notebooks/main?labpath=notebooks%2Fcommunity%2Fexiftool.ipynb) [![Kaggle Notebook][kaggle-badge]](https://kaggle.com/kernels/welcome?src=https://github.com/bellingcat/open-source-research-notebooks/blob/main/notebooks/community/exiftool.ipynb) [![Jupyter Notebook][jupyter-badge]](notebooks/community/exiftool.ipynb)                                                                                         | `digital-forensics`, `metadata`        |
|           **Deepface**            | ![medium][medium-badge] | AI face comparison and analysis                          | [![Colab][colab-badge]](https://colab.research.google.com/github/bellingcat/open-source-research-notebooks/blob/main/notebooks/community/deepface.ipynb) [![Binder][binder-badge]](https://mybinder.org/v2/gh/bellingcat/open-source-research-notebooks/main?labpath=notebooks%2Fcommunity%2Fdeepface.ipynb) [![Kaggle Notebook][kaggle-badge]](https://kaggle.com/kernels/welcome?src=https://github.com/bellingcat/open-source-research-notebooks/blob/main/notebooks/community/deepface.ipynb) [![Jupyter Notebook][jupyter-badge]](notebooks/community/deepface.ipynb)                                                                                         | `ai`, `image-analysis`                 |


- ![easy][easy-badge] Entry level notebooks, you need only know how to run cells and edit specific values
- ![medium][medium-badge] Notebooks that require higher technical know-how, or previous setups
- ![advanced][advanced-badge] Notebooks that require technical understanding or adapting code





<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[colab-badge]: https://colab.research.google.com/assets/colab-badge.svg
[binder-badge]: https://mybinder.org/badge_logo.svg
[kaggle-badge]: https://kaggle.com/static/images/open-in-kaggle.svg
[jupyter-badge]: https://img.shields.io/badge/jupyter-.ipynb%20file-orange
[easy-badge]: https://img.shields.io/badge/easy-%234CAF50?style=for-the-badge
[medium-badge]: https://img.shields.io/badge/medium-%23FF9800?style=for-the-badge
[advanced-badge]: https://img.shields.io/badge/advanced-%23F44336?style=for-the-badge