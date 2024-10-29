# Quarto Docs

## Installation
* Download and install: https://quarto.org/docs/get-started/
* Python installation: 
```{shell}
conda create --name quarto
conda activate quarto
conda install jupyter matplotlib plotly pandas pyaml
```
## Generating docs
Inside this folder
```
conda activate quarto
quarto render
```
Add changes in `../docs` folder to Git to publish


## Editing inside Nvim
General tutorial: https://quarto.org/docs/get-started/hello/neovim.html
* Install quarto nvim plugin. https://github.com/quarto-dev/quarto-nvim 
* `conda activate quarto` before starting nvim
* Inside nvim and quarto folder, issue command `QuartoPreview`
* Preview (that updates) will be opened in default browser

