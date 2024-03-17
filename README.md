# Mono Repo Checkout 
This repo is the source for a test of a mono-repo workflow where one repo is used to pull and test the contents of another repo (this one) 

## Theory
Through the sparse checkout feature we should be able to set up multiple submodules, with each submodule pointing to specific path in the mono-repo instead of pulling in the entire thing. Allowing for people to edit files without needing to pull the ENTIRE thing. 