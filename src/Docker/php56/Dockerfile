FROM centos:7

RUN yum -y update
RUN yum -y install http://rpms.famillecollet.com/enterprise/remi-release-7.rpm \
    && yum -y install --enablerepo=remi-php56 php php-mysql php-gd php-mbstring php-xml php-mcrypt
RUN curl -sS https://getcomposer.org/installer | php -- --install-dir=/usr/bin --filename=composer
