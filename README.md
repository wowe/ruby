ruby
====

learn Ruby
testing Git

I.  Doing demo application
1.  Create new application by executing command "rails new app"
2.  cd to app by executing command "cd app"
3.  Create controller by executing command "rails generate controller post"
4.  Create a response file with extension .erb by executing command "vim app/views/post/index.html.erb"
    4.1 content of index.html.erb file:
            <h1>Our Blog</h1>
            <p>Hello World</p>
5.  Create route for post controller by editing the config/routes.rb and add the "resources :post"
6.  Create model to work with DB by executing command "rails generate model post"

