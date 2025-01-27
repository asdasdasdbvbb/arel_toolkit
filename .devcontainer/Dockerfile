FROM "mcr.microsoft.com/devcontainers/ruby:3.2"
COPY Gemfile Gemfile.lock arel_toolkit.gemspec .
COPY lib/arel_toolkit/version.rb ./lib/arel_toolkit/
RUN gem install bundler:2.4.10
RUN bundle install

