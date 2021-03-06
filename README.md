# Tips for development productivity in Ruby on Rails

## Application new

When you want to create new Rails application, please use application templates:

  * [thoughtbot/suspenders](https://github.com/thoughtbot/suspenders) : A Rails template with thoughtbot standard defaults, ready to deploy to Heroku
  * [morizyun/rails5_application_template](https://github.com/morizyun/rails5_application_template) : Simple Rails template with community standard defaults

## Git Integration

### Git Hook Manager: overcommit

  * Repository
    * [overcommit](https://github.com/brigade/overcommit)
  * Outline
    * A fully configurable and extendable Git hook manager
  * Features
    * Run automatically static analysis like Rubocop, hamlint or etc when you do "git commands".
    * Run automatically security checker like Brakeman, bundler-audit or etc when you do "git commands".
    * Enforce a rule about git configuration, commit message.
    * Prevent a mistake for git command
  * Configuration Sample
    * [.overcommit.yml](https://github.com/morizyun/rails5_application_template/blob/master/root/.overcommit.yml)

### GitHub Review Support Tool : pronto

  * Repository
    * [pronto](https://github.com/mmozuras/pronto)
  * Outline
    * Quick automated code review of your changes in GitHub/GitLab/BitBucket
  * Features
    * Created to be used on pull requests with GitHub, but also works locally and integrates with GitLab and Bitbucket

## Static Code Analysis

### Rubocop

  * Repository
    * [rubocop](https://github.com/bbatsov/rubocop)
  * Outline
    * A Ruby static code analyzer, based on the community Ruby style guide.
  * Features
    * Enforce many of the guidelines outlined in the community Ruby Style Guide
  * Configuration Sample
    * [.rubocop.yml](https://github.com/morizyun/rails5_application_template/blob/master/root/.rubocop.yml)
    
### Fasterer

  * Repository
    * [fasterer](https://github.com/DamirSvrtan/fasterer)
  * Outline
    * Fasterer will suggest some speed improvements which you can check in detail at the fast-ruby repo.

## RSpec

  * [RSpec::Core Cheat Sheet](http://www.rubypigeon.com/posts/rspec-core-cheat-sheet/)

## Improving performance in ActiveRecord

### Finding Lazy Query

  * [bullet](https://github.com/flyerhzm/bullet) : Help to kill N+1 queries and unused eager loading
  * [activerecord-cause](https://github.com/joker1007/activerecord-cause) : Logs where ActiveRecord actually loads record

### Improving DB Query

  * [activerecord-precount](https://github.com/k0kubun/activerecord-precount) : N+1 count query killer for ActiveRecord
  * [activerecord-import](https://github.com/zdennis/activerecord-import) : Extraction of the ActiveRecord::Base#import functionality
  * [upsert](https://github.com/seamusabshere/upsert) : Upsert / Transparently creates functions (UDF)

### Improving DB Schema

  * [flag_shish_tzu](https://github.com/pboling/flag_shih_tzu) : Bit fields for ActiveRecord
  * [counter_culture](https://github.com/magnusvk/counter_culture) : Turbo-charged counter caches for your Rails app

### Using DB View

  * [scenic](https://github.com/thoughtbot/scenic) : Versioned database views for Rails

## Profiler

### Rails Profile

  * [New Relic](https://newrelic.com/) : Application performance monitoring
  * [peek-rblineprof](https://github.com/peek/peek-rblineprof) : Peek into how much each line of your Rails application takes throughout a request
  * [rack-mini-profiler](https://github.com/MiniProfiler/rack-mini-profiler) : Profiler for your development and production Ruby rack apps
  * [rack-lineprof](https://github.com/kainosnoema/rack-lineprof) : Rack middleware for easy line-by-line profiling using rblineprof

### Ruby Profile

  * [stackprof](https://github.com/tmm1/stackprof) : A sampling call-stack profiler for ruby 2.1+
  * [memory_profiler](https://github.com/SamSaffron/memory_profiler) : memory_profiler for ruby

## View Cache

### Fragment Cache

  * [Fragment Cache](http://edgeguides.rubyonrails.org/caching_with_rails.html#fragment-caching) : It is useful for example global navigation or sidebar.

### Action Cache

  * [actionpack-action_caching](https://github.com/rails/actionpack-action_caching) : Action caching for Action Pack
 
### Page Cache

  * [actionpack-page_caching](https://github.com/rails/actionpack-page_caching) : Static page caching for Action Pack

## GitLab

  * [Continuous Integration, Delivery, and Deployment with GitLab](https://about.gitlab.com/2016/08/05/continuous-integration-delivery-and-deployment-with-gitlab/)

## Special Thanks

  * https://speakerdeck.com/toshimaru/speeding-up-rails
  * https://speakerdeck.com/a_matsuda/3x-rails

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
