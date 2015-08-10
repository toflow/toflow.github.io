http://trustsaude.github.io

#### Dependencies
    sudo npm install -g harp

#### Writing a new post

1. Create new file in `_src/public/posts`.
2. Add metadata of post in `_src/public/posts/_data.json`.
3. Run `harp server` from inside `_src` and keep iterating until post finished.

#### Deploying

1. Run `sh _compile`.
2. Run `harp server` not from `_src` folder, but from top level folder now. 
3. If everything ok, then run `sh _deploy` and you're all done.
