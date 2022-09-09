FROM openresty/openresty:centos7

LABEL maintainer="Manoa Ratefiarison <manoa@ratefiarison.com>"

RUN yum -y install rpm-build redhat-rpm-config rpmdevtools \
    gcc make perl systemtap-sdt-devel \
    openresty-zlib-devel openresty-openssl111-devel openresty-pcre-devel

RUN mkdir -p ~/rpmbuild/{BUILD,RPMS,SOURCES,SPECS,SRPMS}