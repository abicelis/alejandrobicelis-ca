# alejandrobicelis.ca Jekyll site

Upstream changes come from [andrewbanchich/forty-jekyll-theme](https://github.com/andrewbanchich/forty-jekyll-theme) into the `master` branch.

Branch `alejandrobicelis-ca-site` pulls these changes, and contains my modifications to make it `alejandrobicelis.ca`


# Running locally on macOS

Note: Following [this guide](https://jekyllrb.com/docs/installation/macos/)

```bash
# Install chruby and ruby-install using Homebrew
brew install chruby ruby-install xz

# Install latest stable version of Ruby
ruby-install ruby 3.1.3

# Configure shell to automatically use chruby
nano ~/.profile

##### Append this below #####

## RUBY
# Include chruby in PATH
source /opt/homebrew/opt/chruby/share/chruby/chruby.sh
source /opt/homebrew/opt/chruby/share/chruby/auto.sh

# Using chruby, Make ruby-3.1.3 (installed with ruby-install) the default, instead of macOS's ruby
chruby ruby-3.1.3

##### End Append #####

# ~~~~ Relaunch your shell so ~/.profile does it's thing ~~~
# Running ruby -v should return the version of ruby installed by ruby-install, not the default macOS ruby.

# Install jekyll
gem install jekyll

# Clone site repo and checkout correct branch
git clone git@github.com:abicelis/alejandrobicelis-ca.git
cd alejandrobicelis-ca
git checkout alejandrobicelis-ca-site

# Launch site locally - only localhost access
bundle exec jekyll serve --livereload

# Or, to access site using other devices in the same net (Note: Ensure --host IP is correct)
bundle exec jekyll serve --livereload --host 192.168.10.85

```


# Deploying to Ubuntu 22.04
```bash
# Instal dependencies
sudo apt-get install ruby-full build-essential zlib1g-dev

# Avoid installing RubyGems packages (called gems) as the root user.
echo '# Install Ruby Gems to ~/gems' >> ~/.bashrc
echo 'export GEM_HOME="$HOME/gems"' >> ~/.bashrc
echo 'export PATH="$HOME/gems/bin:$PATH"' >> ~/.bashrc
source ~/.bashrc




```


# Credits

Original repository [andrewbanchich/forty-jekyll-theme](https://github.com/andrewbanchich/forty-jekyll-theme)