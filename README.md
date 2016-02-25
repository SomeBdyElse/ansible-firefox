ansible-firefox
===============
[![Build Status](https://travis-ci.org/hellofresh/ansible-firefox.svg?branch=master)](https://travis-ci.org/hellofresh/ansible-firefox)

An ansible role that installs multiple version of firefox. 

### Role Variables
```yaml
firefox_version         : 
                            - "40.0"
                            - "37.0"
# default version of firefox
firefox_default         : "{{ firefox_version[0] }}"
firefox_link_dir        : "/usr/local/bin"
firefox_instalL_dir     : "/opt/firefox/"
firefox_tmp_dir         : "/tmp/firefox"
```

## License
MIT

### Contributors
* [Adham Helal](https://github.com/ahelal)
