# Ruby & Rails Workshops Vagrant Box

Basic Vagrant Box setup on Windows 10 x64 created using below instructions: 

1. [Set up basic "clean box" with vagrant](https://gorails.com/guides/using-vagrant-for-rails-development)
2. [Set up rails tools using this instructions](https://gorails.com/setup/ubuntu/14.04)
3. create myapp under `/vagrant` dir (watch out, `/vagrant` is not the same dir as `~/vagrant`) using following 
   commands:

   cd /vagrant
   rails new myapp
   rails server

4. Create rails hello world with following tutorial:

* http://guides.rubyonrails.org/getting_started.html


## Links

Useful links that helped me resolve problems:

* http://stackoverflow.com/questions/27627286/cant-connect-localhost3000-ruby-on-rails-in-vagrant  
* http://stackoverflow.com/questions/27799260/rails-4-2-server-port-forwarding-on-vagrant-does-not-work  
* http://stackoverflow.com/questions/17853850/vagrant-vm-not-created-when-trying-to-create-box-from-existing-vm  
* http://stackoverflow.com/questions/18528717/vagrant-shared-and-synced-folders
* http://stackoverflow.com/questions/23543866/vagrant-package-how-to-save-changes-to-new-box
* http://stackoverflow.com/questions/22181325/saving-and-sharing-changes-made-to-vagrant-box
* https://www.vagrantup.com/docs/cli/package.html
* http://superuser.com/questions/635256/copy-vagrant-box-locally

Futher to read

* http://ebarnouflant.com/posts/7-convert-a-virtualbox-ova-vm-into-a-vagrant-box


## Setup

HOST OS: Windows 10 x64
GUEST OS: Ubuntu 14.04 (Trusty Thar, ubuntu/trusty64)

----
