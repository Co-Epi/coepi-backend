Notes to get up and running:

set up mac to latest ruby development environment
https://install-rails-mac.com/index.html (stop after "Install Rails")
This will install the latest version of ruby, rails, gem, and git. As of today that is:

* Ruby 2.7.0p0
* Rails 6.0.2.1
* Gem 3.1.2
* bundler 2.1.2
* git version 2.25.0

** For git - I highly recommend setting Multifactor Authentication up, but this will break git command line tools if you try to use https. Set up an SSH key and use the SSH url for git

if you run into issues with any of the above steps (particularly around nokogiri and installing other bits and pieces, this may help: https://medium.com/faun/macos-catalina-xcode-homebrew-gems-developer-headaches-cf7b1edf10b7 )



For local work within postgres, install/upgrade postgres to 12.2
https://www.robinwieruch.de/postgres-sql-macos-setup

(if you are working on creating your own rails app, note that you may need to install/upgrade yarn and Node.js

brew [upgrade|install] node
brew [upgrade|install] yarn

