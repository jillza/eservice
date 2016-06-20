FROM lukaszkinder/apache-php-oci8-pdo_oci

RUN apt-get update \
    && apt-get install -y unzip \
    && apt-get clean -y

RUN apt-get install -y php5-memcached memcached