source 'http://rubygems.org'


gem 'wagn'


gem 'mysql2', '0.3.20'
# Use Unicorn or Thin as server
# gem 'unicorn'
# gem 'thin'




Dir.glob( 'mod/**{,/*/**}/Gemfile' ).each do |gemfile|
  instance_eval File.read(gemfile)
end
