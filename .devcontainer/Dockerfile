FROM ruby:2.7.4
FROM debian:bullseye-slim

# Install Ruby and RubyGems
RUN apt-get update && apt-get install -y ruby ruby-dev rubygems

# Install Bundler
RUN gem install bundler
