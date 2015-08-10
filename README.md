http://trustsaude.github.io/blog/

#### Dependencies
    sudo npm install -g harp

#### Writing a new article

1. Create new file in `_src/articles`.
2. Add metadata of article in `_src/articles/_data.json`.
3. Run `harp server` from inside `_src` and keep iterating until article finished.

#### Deploying

1. Run `sh _compile`.
2. Run `harp server` not from `_src` folder, but from top level folder now. 
3. If everything ok, then run `sh _deploy` and you're all done.
