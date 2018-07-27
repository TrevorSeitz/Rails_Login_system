# README

This is a Ruby on Rails Login system using Omniauth Identity and Github. Other third party options are available but not implemented.  

This app provides a database and web interface for users to create an user account and log in to a basic home page.

This is not intended to be a full login system for commercial use. It is a sample only.


This app was built with Ruby on Rails, using the Omniauth Gem. The thin gem was used for https access.

Usage: After checking out the repo, run bundle install to install Ruby gem dependencies. You can start a secure ruby server using the thin start --ssl command shotgun and navigate to https://localhost:3000 in your browser.  To use the github functionality you must register and app with github and add the key and secret to the .env file

Contributing Bug reports and pull requests are welcome on GitHub at https://github.com/TrevorSeitz/Rails_Login_system.  

License The app is available as open source under the terms of the MIT License.
