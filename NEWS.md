This is beanstalkd version 1.8.

As always, there will be no incompatible protocol changes until
version 2.0. A client written for version 1.8 will work
unmodified with any later 1.x release of beanstalkd.

News
----

- correctly log command names in verbose mode
- correctly check for hangup during reserve
- add protocol.md
- fix tests on freebsd
- stricter format checking; fix format call errors
- Tolerate compilation without a Git repository.
- New command: kick-job.
- document missing tube stats fields; fixes #127

Full list of changes (includes authorship information):
<http://github.com/kr/beanstalkd/compare/v1.7...v1.8>

Our Urls
--------

Download the 1.8 tarball directly:
<https://github.com/downloads/kr/beanstalkd/beanstalkd-1.8.tar.gz>

Learn all about beanstalk:
<http://kr.github.com/beanstalkd/>

Talk about beanstalk development or use at:
<http://groups.google.com/group/beanstalk-talk>

Bugs
----

Please report any bugs to:
<http://github.com/kr/beanstalkd/issues>
