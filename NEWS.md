# Highlights

- removed dependency on libevent
- no more autotools; to build beanstalkd, just type "make"
- incremental binlog compaction; fixes #43
- removed flag -d; alternatives are in the "adm" directory

# More News

- switch to MIT license
- remove DEBUG compile flag
- more interesting make examples in README
- change default CFLAGS
- verbose mode; closes #52
- properly timeout reserve-with-timeout; fixes #78
- document that EPOLLRDHUP was introduced in Linux 2.6.17.
- read beanstalkd 1.4.6's log format for compatibility
- report size of attempted read for WAL read errors
- accurately report position of WAL file errors
- add file index to job stats
- clarify behavior of cumulative stats; closes #81
- adding support for counting deletes on a tube
- delete command now deletes delayed jobs
- fix segfault; closes #71
- bsd build fix; PATH_MAX is defined in limits.h
- bsd build fix; echo -n is not portable
- do not read in STATE_WAIT; fixes #22
- document the new binlog stats
- redo the WAL code, improving style
- more careful binlog read checking
- in log recovery, recompute delay with current time; fixes #62
- provide and document more system admin tools
- support systemd socket activation

Full list of changes in this release (includes authorship information):
<http://github.com/kr/beanstalkd/compare/v1.4.6...v1.5>
