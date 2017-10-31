### Vue.js People App

1. install gems:
```gem 'vuejs-rails'```
```gem 'jquery-rails'```

2. bundle

3. Add ```//= require vue``` to your application.js file (i.e. app/assets/javascripts/application.js) on the line before //= require_tree .

4. Create this file: 
```config/initializers/vue_config.rb```

5. Add ```Vue.development_mode = true``` to the *vue_config.rb* file
(Set this to false if you are pushing to production) Then run ```rake tmp:cache:clear``` in the terminal after changing this development_mode flag

6. 