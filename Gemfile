source 'http://rubygems.org'


gem 'wagn', :git => 'https://github.com/xithan/wagn', branch: 'heroku'


gem 'pg'
gem 'rails_12factor'
gem 'fog'
gem 'fog-aws'
gem "carrierwave", git: "https://github.com/carrierwaveuploader/carrierwave",
                   branch: "master"

# Use Unicorn or Thin as server
# gem 'unicorn'
# gem 'thin'




Dir.glob( 'mod/**{,/*/**}/Gemfile' ).each do |gemfile|
  instance_eval File.read(gemfile)
end
