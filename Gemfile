source "http://rubygems.org"
# group :development do
#   # gem "mysql"
#   # gem "json_pure", "1.4.3"
#
#
#   # gem "datamapper",        "1.0.0"
#   # gem "dm-migrations",     "1.0.0"
#   # gem "dm-sqlite-adapter", "1.0.0"
#
#   # mongo requirements
#     # gem "mongo",     "1.0.1"
#     # gem "mongo_ext", "0.19.3"
#     # gem "bson_ext",  "1.0.1"
# end

group :development do
  gem "rake", ">= 12.3.3"
  gem "ruby-debug"

  gem "bundler"
  gem "jeweler"

  gem "json_pure"

  #ORM's
  gem "activerecord", "6.1.7.1"
  gem "datamapper",           "1.0.0"
    gem "dm-migrations",      "1.0.0"
    gem "dm-sqlite-adapter",  "1.0.0"
  gem "mongoid", "2.0.0"
    gem "tzinfo", "0.3.61"
  gem "mongo_mapper",         "0.8.2"
  gem "couch_potato",         "0.3.0"
  gem "sequel",               "~>3.21.0"
  #gem "ibm_db"  # I don't want to add this dependency, even as a dev one since it requires DB2 to be installed
end

group :test do
  gem "rspec"
  gem "rspactor"
  gem "rcov"
  gem "ZenTest"
end

group :cucumber do
  gem "cucumber", ">= 4.0.0"
  gem 'sqlite3-ruby'
end
