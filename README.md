# Ansible-Role-JDK
Super Simple Role to install Java Development 8 kit in linux.

Role Variables
--------------
```
java_download_url: http://download.oracle.com/otn-pub/java/jdk/8u151-b12/e758a0de34e24606bca991d704f6dcbf/jdk-8u151-linux-x64.tar.gz
java_archive_name: jdk-8u151-linux-x64.tar.gz
java_root_dir: /usr/share/java-1.8.0
java_jdk_dir: "{{ java_root_dir }}/jdk1.8.0_151"
```

Example Playbook
----------------

    - hosts: YOUR-HOST-OR-GROUP
      roles:
    	- Ansible-Role-JDK

License
-------

MIT

Author - Rahul Sharma
------------

[Github](https://github.com/Rahulsharma0810)

[Facebook](https://www.facebook.com/rahulsharma0810)