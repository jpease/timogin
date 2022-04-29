# timogin

## Prerequisites
* Ruby (tested with 3.1.2)
* Gems: Bundler, Jekyll, Webrick

While you can satisfy the above in many ways, assuming you have [Homebrew](https://brew.sh) installed, here is one way:

1. `$ brew install asdf`
2. `$ asdf plugin add ruby https://github.com/asdf-vm/asdf-ruby.git`
3. `$ asdf install ruby latest`
4. `$ gem install bundler jekyll`
5. `$ git clone git@github.com:jpease/timogin.git`
6. `$ cd timogin`
7. `$ bundle add webrick`

## Run locally

1. `$ bundle exec jekyll serve`
2. Local preview at: http://127.0.0.1:4000/

