## Install poshgit and oh-my-posh
choco install poshgit  
choco install oh-my-posh

## Save theme file
Ex. ~/oh-my-posh-themes/robbyrussel.min.omp.json

## Add this line in powershel profile
Import-Module posh-git  
oh-my-posh init pwsh --config ~/oh-my-posh-themes/robbyrussel.min.omp.json | Invoke-Expression

## Configure font
Install Literation Mono Nerd Font and set this as default in Poweshell
