# keralajs-website
KeralaJs website: hexo site generator code

This is the site to generate website of keralajs website

# Using nvm
## install nvm
``` bash
curl https://raw.github.com/creationix/nvm/master/install.sh | sh
```
or
``` bash
wget -qO- https://raw.github.com/creationix/nvm/master/install.sh | sh
```
Are you windwos user?

[nvm-windows](https://github.com/coreybutler/nvm-windows)

or

[nvmw](https://github.com/hakobera/nvmw)

# Now install nvm 4
``` bash
nvm install 4
```
# Install hexo
``` bash
nvm use 4
```
``` bash
npm install hexo-cli -g
```
# Contribute
## clone
``` bash
git clone https://github.com/ajeebkp23/keralajs-website
```
``` bash
npm install
```

## Run hexo, see result
``` bash
hexo server
```
Go to [localhost:4000](http://localhost:4000)

# Add new post
``` bash
hexo new post "My good post"
```

# now change the post
Edit file 
```
vim source/_posts/My-good-post.md
```
or use admin
[admin](http://localhost:4000/admin/)

# Docs
[hexo.io](https://hexo.io/docs/)

[hexo-admin](https://github.com/jaredly/hexo-admin)
