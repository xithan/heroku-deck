source 'http://rubygems.org'
ruby '2.3.1'

gem 'wagn', path: "vendor/wagn"
gem 'pg'
gem 'rails_12factor'
gem 'fog'
gem 'fog-aws'
gem "carrierwave", git: "https://github.com/carrierwaveuploader/carrierwave",
    branch: "master"
gem "delayed_job_active_record"

Dir.glob('mod/**{,/*/**}/Gemfile').each do |gemfile|
  instance_eval File.read(gemfile)
end

gem "mysql2"

