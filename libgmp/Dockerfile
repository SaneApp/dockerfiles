FROM ubuntu
MAINTAINER Ian Duncan <ian@iankduncan.com>
RUN apt-get update
RUN apt-get install -y libgmp10
RUN ln -s /usr/lib/x8ls6_64-linux-gnu/libgmp.so.10 /usr/lib/libgmp.so.3
RUN ln -s /usr/lib/x86_64-linux-gnu/libgmp.so.10 /usr/lib/libgmp.so
