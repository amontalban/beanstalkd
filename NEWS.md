This is beanstalkd version 1.6, a bugfix release.

As always, there will be no incompatible protocol changes until version 2.0.
A client written for version 1.6 will work unmodified with any later 1.x
release of beanstalkd.


News
----

- line-buffered stdout, even when not on a tty; closes #116
- remove obsolete startup method; closes #100
- wake up waiting clients when unpausing a tube; fixes #113
- fix build on FreeBSD 9; closes #111
- fix build and tests on clang; closes #110
- better flag parsing (with tests)
- binlog: better warning message when open fails
- support for better tar compatibility; closes #93
- fix cpu use on freebsd and darwin; closes #96
- fix compile error on linux with kernel 2.6.18
- update outdated usage text

Full list of changes in this release (includes authorship information):  
<http://github.com/kr/beanstalkd/compare/v1.5...v1.6>


Our Urls
--------

Download the 1.6 tarball directly:  
<https://github.com/downloads/kr/beanstalkd/beanstalkd-1.6.tar.gz>

Learn all about beanstalk:  
<http://kr.github.com/beanstalkd/>

Talk about beanstalk development or use at:  
<http://groups.google.com/group/beanstalk-talk>


Bugs
----

Please report any bugs to:  
<http://github.com/kr/beanstalkd/issues>
