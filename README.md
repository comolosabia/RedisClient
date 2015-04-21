# RedisClient


This is a redis client GUI tool written based on Java SWT and Jedis. It's my objective to build the most convenient redis client GUI tool in the world. In the first place, it will facilitate in editing redis data, such as: add, update, delete, search, cut, copy, paste etc.

![My image](https://github.com/caoxinyu/RedisClient/raw/master/src/main/resources/screen.png)

--------

## Features

**Windows Explorer style UI**

**Multiple Redis version adaptive**

 1. Manage redis server, support server password authentication
 2. Manage redis data favorite
 3. Manage redis data
 	* New redis data: string, list, hash, set, sorted set
 	* Rename redis data 
 	* Delete redis data
 	* Update redis data
 	* Cut, copy paste redis data
 	* Import, export redis data
 	* Search redis data
 	* Order redis data by key, data type, size
 	* Navigation history
 	* Support time to live
 	* Support paging query redis data
 	* Support multiple selection to delete, cut, copy, export redis data
 	* Support flat view and hierarchy view to list redis data
 	* Support multiple language, now support English and Chinese


## Install & run for 64 bit Linux
 1. Download the runable jar file [redisclient-linux.x86_64.1.5.jar](https://github.com/comolosabia/RedisClient/blob/linux-x86_64/release/redisclient-linux.x86_64.1.5.jar?raw=true)
 2. Run the redisclient-linux.x86_64.1.5.jar, input `java -jar redisclient-linux.x86_64.1.5.jar`. 
 
## Install & run for RPM based (7) 64 bit Linux
 1. Download the runable jar file [redis-client-1.5-1.el7.x86_64.rpm](https://github.com/comolosabia/RedisClient/blob/linux-x86_64/release/redis-client-1.5-1.el7.x86_64.rpm?raw=true)
 2. Install the redis-client-1.5-1.el7.x86_64.rpm, input `rpm -ivh redis-client-1.5-1.el7.x86_64.rpm`. 
 3. Run the application from `Application/Programming/Redis Client` menu.

## Install & run for Windows
For Windows, please switch [branch](https://github.com/caoxinyu/RedisClient/tree/master)

## Install & run for 32 bit Linux
For Linux 32 bits, please switch [branch](https://github.com/caoxinyu/RedisClient/tree/linux)

## Donate
 
If you find this software useful and would like to support it, you can do so simply by scanning my Alipay two-dimension code and donating whatever you like.

![My code](https://github.com/caoxinyu/RedisClient/raw/master/src/main/resources/code.png)
 
