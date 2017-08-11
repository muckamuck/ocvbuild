FROM centos:centos6.9
RUN yum -y groupinstall "Development Tools"
RUN yum -y install gcc-c++
RUN yum -y install cmake
COPY opencv.tgz /build/opencv.tgz
