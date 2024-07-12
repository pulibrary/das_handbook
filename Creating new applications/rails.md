---
layout: default
title: Creating a new Rails application
---
# Checklist for creating a new DACS rails application

- [ ] The application has a github repo in the pulibrary organization.
- [ ] The application uses `main` as the default branch
- [ ] The application uses postgresql (e.g. when creating your application, you use the `-d postgresql` option for `rails new`)
- [ ] The application does not use rails' default javascript pipeline (e.g. when creating your application, you use the `--skip-javascript --skip-asset-pipeline` options for `rails new`)
- [ ] The application does not use spring (e.g. when creating your application, you use the `--skip-spring` options for `rails new`)
- [ ] The application has a .tool-versions file to specify the version of ruby and any other languages used in the project.  This is useful for developers who use [asdf](https://asdf-vm.com/) or [rtx](https://github.com/jdxcode/rtx).  `rails new` automatically creates a .ruby-version file for developers who use [rvm](https://rvm.io/) or [rbenv](https://github.com/rbenv/rbenv).
- [ ] The application uses lando to create a local development postgres server, using [this lando commit example](https://github.com/pulibrary/rails-template/commit/8e96b42f274cab990c6c64bf582e4c85feededcc) as a guide.
- [ ] The application does not use Minitest (e.g. when creating your application, you use the `-T` option for `rails new`)
- [ ] The application uses rspec (using the [rspec-rails procedures](https://github.com/rspec/rspec-rails) to install it)
- [ ] The application has a circleci configuration at .circleci/config.yml (CircleCI provides an [example rails application CircleCI config file](https://circleci.com/developer/orbs/orb/circleci/ruby#usage-ruby_rails_sample_app)).
- [ ] The application uses the [axe-core-rspec gem](https://github.com/dequelabs/axe-core-gems) and includes an accessibility spec that checks for accessibility.
- [ ] The application is using [rubocop](https://github.com/rubocop/rubocop) 
