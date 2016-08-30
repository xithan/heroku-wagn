source 'http://rubygems.org'


gem 'wagn', :git => 'https://github.com/xithan/wagn', branch: 'heroku'


gem 'pg'
gem 'rails_12factor'
gem 'fog'
gem 'fog/aws'

# Use Unicorn or Thin as server
# gem 'unicorn'
# gem 'thin'




Dir.glob( 'mod/**{,/*/**}/Gemfile' ).each do |gemfile|
  instance_eval File.read(gemfile)
end
