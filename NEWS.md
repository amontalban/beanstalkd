This is beanstalkd version 1.7, a bugfix release.

As always, there will be no incompatible protocol changes until
version 2.0. A client written for version 1.7 will work
unmodified with any later 1.x release of beanstalkd.

News
----

- fix tests on big-endian machines
- fix several issues identified by Coverity Scan
- always read pending data; fixes #129
- fix crash when closing connections
- count puts like any other command

Full list of changes (includes authorship information):  
<http://github.com/kr/beanstalkd/compare/v1.6...v1.7>

Our Urls
--------

Download the 1.7 tarball directly:  
<https://github.com/downloads/kr/beanstalkd/beanstalkd-1.7.tar.gz>

Learn all about beanstalk:  
<http://kr.github.com/beanstalkd/>

Talk about beanstalk development or use at:  
<http://groups.google.com/group/beanstalk-talk>

Bugs
----

Please report any bugs to:
<http://github.com/kr/beanstalkd/issues>
