source "http://rubygems.org"
gemspec

gem "rake"
gem "moped", "~> 1.3.0"
gem "moped-turbo", "~> 0.0.1"

git "git://github.com/rails/rails.git" do
  gem "activemodel"
end

group :test do
  gem "rspec", "~> 2.11"

  unless ENV["CI"]
    gem "guard"
    gem "guard-rspec"
    gem "rb-fsevent"
  end
end
