source 'https://rubygems.org'

group :test do
  gem 'facter', (ENV['FACTER_GEM_VERSION'] || '~> 2.0'),           require: false
  gem 'puppet-lint-classes_and_types_beginning_with_digits-check', require: false
  gem 'puppet-lint-leading_zero-check',                            require: false
  gem 'puppet-lint-trailing_comma-check',                          require: false
  gem 'puppet-lint-unquoted_string-check',                         require: false
  gem 'puppet-lint-variable_contains_upcase',                      require: false
  gem 'puppet-lint-version_comparison-check',                      require: false
  gem 'puppetlabs_spec_helper',                                    require: false
  gem 'rspec-puppet-facts',                                        require: false
  gem 'rubocop',                                                   require: false
end

puppetversion = ENV['PUPPET_VERSION'] || '~> 5.0'
gem 'puppet', puppetversion
