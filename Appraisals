appraise "rails-5.2" do
  gem "rails", github: "rails/rails", branch: '5-2-stable'
end

appraise "rails-6.0" do
  gem "rails", github: "rails/rails", branch: '6-1-stable'
  if RUBY_VERSION < "2.6"
    gem 'puma', '~> 5.6'
    gem "capybara", '~> 3.35.0'
  elsif RUBY_VERSION < "2.7"
    gem 'puma', '~> 5.6'
    gem "capybara", '~> 3.37.0'
  else
    gem 'puma'
    gem "capybara"
  end
end

appraise "rails-6.1" do
  gem "rails", github: "rails/rails", branch: '6-1-stable'
  if RUBY_VERSION < "2.6"
    gem 'puma', '~> 5.6'
    gem "capybara", '~> 3.35.0'
  elsif RUBY_VERSION < "2.7"
    gem 'puma', '~> 5.6'
    gem "capybara", '~> 3.37.0'
  else
    gem 'puma'
    gem "capybara"
  end
end
