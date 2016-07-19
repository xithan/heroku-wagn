source 'http://rubygems.org'


gem 'wagn' #, :path => 'vendor/wagn'


gem 'pg'
# Use Unicorn or Thin as server
# gem 'unicorn'
# gem 'thin'




Dir.glob( 'mod/**{,/*/**}/Gemfile' ).each do |gemfile|
  instance_eval File.read(gemfile)
end
