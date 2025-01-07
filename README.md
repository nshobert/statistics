# statistics
Inferential statistics content using Quarto website

Plan to use `quarto publish` approach - [docs](https://quarto.org/docs/publishing/github-pages.html#publish-command)

Strongly reference Dr. Ema Perkovic's [notes](https://emilijaperkovic.com/wp-content/uploads/2024/01/STAT_512_Lecture-Notes-Complete.pdf)

## Environment
1. If setting up from scratch, start with a Python 3.11 installation.
2. Create the virtual environment with    
`pipenv install --ignore-pipfile`   
to use the locked requirements.
3. Activate it
`pipenv shell`
4. The only requirement not managed by pip is quarto. Download and install it with   
`wget https://github.com/quarto-dev/quarto-cli/releases/download/v1.6.40/quarto-1.6.40-linux-amd64.deb`  
or maybe a more recent version.
5. Install it with   
`sudo dpkg -i quarto-1.6.40-linux-amd64.deb`   
updating the version number if necessary.
6. To generate the website files for the first time or after changes, enter the `my_site` directory and enter    
`quarto render`
7. To preview the site, use
`quarto preview`
