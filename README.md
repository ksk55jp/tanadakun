#Tanada kun
```bash
brew upgrade
rbenv versions
rbenv install 2.3.4
mkdir tanadakun
cd tanadakun
rbenv local 2.3.4
bundle init
gem install bundler
vim Gemfile
gem "rails", "4.2.3"
bundle install --path vendor/bundle --jobs=4
```bash
