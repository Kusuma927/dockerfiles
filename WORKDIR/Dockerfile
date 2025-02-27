FROM almalinux:9
RUN mkdir /tmp/work-dir-daemon
RUN cd /tmp/work-dir-daemon
RUN pwd
RUN echo "Hello from WORK DIR" > hello.txt
USER expense
CMD ["sleep", "100"]
 
