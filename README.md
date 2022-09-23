## Install
### Clone the repository
```bash
git clone github.com/mkpdev/therapia_test_Task
cd therapia_test_Task
```

### Check your Ruby version
```bash
ruby -v
```
use ruby -3.0.2
If not installed, install the right ruby version using rvm (it could take a while):
```bash
rvm install "ruby-3.0.2"
```

### Update database.yml file
In database.yml file, edit the database configuration as required.
### Initialize the database
```ruby
rails db:create db:migrate db:seed
```
### Serve
```ruby
rails s

