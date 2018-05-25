# Rails 5.2 with Bootstrap 4.x

A super simple rails app to show how to implement bootstrap 4. These steps worked on macOS. Please, submit a Pull Request if you find something needed for other OS.

**1)** Gemfile

    # Add these gems. Rails is not including jQuery by default.
    # You need to include it to use all bootstrap options.
    gem 'bootstrap'
    gem 'jquery-rails'
    
**2)** app/assets/javascripts/application.js  
_jquery3, popper, and bootstrap are the ones for bootstrap_

```javascript
//= require jquery3
//= require popper
//= require bootstrap

//= require rails-ujs
//= require activestorage
//= require turbolinks
//= require_tree .
```

**3)** app/assets/stylesheets/application.scss

```scss
@import 'bootstrap';
```

**4)** Run `bundle` and restart your server
