Nginx-Pagespeed-Deb
===================

Readymade Nginx Pagespeed Deb. I do not have time to go through the complex rocket launch like upload method on Launchpad. I have added sig (nginx_1.6.2-5+trusty0.dsc.sig) on some files to indicate that they are original.

content of :

`15.125.77.166/nginx-pagespeed/rebuildnginx/`

````
nginx-1.6.2                              nginx_2014.12-0ubuntu2-nginxubuntu1_source.build
nginx_1.6.2-5+trusty0_all.deb            nginx-common_1.6.2-5+trusty0_all.deb
nginx_1.6.2-5+trusty0_amd64.changes      nginx-doc_1.6.2-5+trusty0_all.deb
nginx_1.6.2-5+trusty0_amd64.changes.sig  nginx-extras_1.6.2-5+trusty0_amd64.deb
nginx_1.6.2-5+trusty0.debian.tar.gz      nginx-extras-dbg_1.6.2-5+trusty0_amd64.deb
nginx_1.6.2-5+trusty0.dsc                nginx-full_1.6.2-5+trusty0_amd64.deb
nginx_1.6.2-5+trusty0.dsc.sig            nginx-full-dbg_1.6.2-5+trusty0_amd64.deb
nginx_1.6.2-5+trusty0_source.build       nginx-light_1.6.2-5+trusty0_amd64.deb
nginx_1.6.2-5+trusty0_source.changes     nginx-light-dbg_1.6.2-5+trusty0_amd64.deb
nginx_1.6.2.orig.tar.gz

````

wget the required file, run :
    
```` 
add-apt-repository ppa:nginx/stable
apt-get update -y
apt-get install nginx-common && sudo dpkg --install nginx-full_1.6.2-5+trusty0_amd64.deb 

````

It has all the stuffs like normal Ubuntu apt version of Nginx. Plus your Nginx.    
  
