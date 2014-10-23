FROM onesysadmin/grails:1.1.1-SNAPSHOT

ENV GWT_HOME /usr/local/gwt-linux-1.5.3
ENTRYPOINT ["grails"]

# Install GWT
RUN cd /usr/local && wget -O - --quiet --no-check-certificate https://github.com/asans/appdist-archive/blob/master/gwt/gwt-linux-1.5.3.tar.bz2?raw=true | tar xjf -
