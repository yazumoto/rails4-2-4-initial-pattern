# rails4-2-4-initial-pattern
This is initial pattern of Rails4.2.4. Installed rspec, pry, mysql2 etc.

## Installed gems
- rspec : This is most important gem you have to install first. Make less bugs.
- factory_girl : DB management tool for spec. You can create test data easily!
- mysql2 : gem for mysql. Currently mysql2 0.4.x has bugs so installed 0.3.20.
- erd : This gem can output your er diagram easily. run 'erd'. 
- pry : Debug tool. You can have strongest debug tool now!
- spring : rails, rake, rspec smoothly!
- etc...

## Usage
Clone this repository and change remote to your repository. You can also fork this repository if you want.
```
git clone https://github.com/seteen/rails4-2-4-initial-pattern.git
mv rails4-2-4-initial-pattern <your app name>
cd <your app name>
git remote set-url origin <your repo url>
bundle install --path vendor/bundle
# setup your db. and modify config/database.yml
```
Now you can start developing!
