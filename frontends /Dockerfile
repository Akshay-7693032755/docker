FROM  centos:7

LABEL   devops = "Akshay_c"

Run    yum  install httpd -y 
copy index.html /var/www/html/
run  chmod 777 -r /var/www/
run chmod 644 /var/www/html/index.html

Expose  80
CMD httpd -DFORGROUND

