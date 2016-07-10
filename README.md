# Tips for development productivity in Ruby on Rails

## Application new

When you want to create new Rails application, please use application templates:

  * [morizyun/rails5_application_template](https://github.com/morizyun/rails5_application_template)
  * TBE

## overcommit

  - Repository
    - **[overcommit](https://github.com/brigade/overcommit)**
  - Outline
    - A fully configurable and extendable Git hook manager
  - Features
    - Run automatically static analysis like Rubocop, hamlint or etc when you do "git commands".
    - Run automatically security checker like Brakeman, bundler-audit(now PR) or etc when you do "git commands".
    - Enforce a rule about git configuration, commit message.
    - Prevent a mistake for git command
  - Configuration Sample
    - **[.overcommit.yml](https://github.com/morizyun/rails5_application_template/blob/master/root/.overcommit.yml)**

## Rubocop

  - Repository
    - **[overcommit](https://github.com/bbatsov/rubocop)**
  - Outline
    - A Ruby static code analyzer, based on the community Ruby style guide.
  - Features
    - Enforce many of the guidelines outlined in the community Ruby Style Guide
  - Configuration Sample
    - **[.rubocop.yml](https://github.com/morizyun/rails5_application_template/blob/master/root/.rubocop.yml)**

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
