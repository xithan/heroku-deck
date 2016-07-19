source 'http://rubygems.org'
ruby '2.2.2'

gem 'wagn'

gem 'pg'
# Use Unicorn or Thin as server
# gem 'unicorn'
# gem 'thin'




Dir.glob( 'mod/**{,/*/**}/Gemfile' ).each do |gemfile|
  instance_eval File.read(gemfile)
end

