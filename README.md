# IP-Proxy-Pool
Would be a ip proxies pool, nothing has done yet

## Some thoughts
- **IPs' storage**: File system? NoSQL? Relational DB?
    * File system: pickle? txt file?
    * NoSQL: Easy setup, fair performance(when num of ip not big), easy to add attribute
    * DB: Fixed schema, far from open to use, good performance(generally would be only one or two table)

- **Interface**: RESTful API? ~~Redis/Memcache?~~ ~~Or even class?~~
    * API: Easy to access, clean and good for other app 
    
- **Easy config to add more targets to crawl**
    * Dynamic best! Could done by read conf file constantly

- **Definately test proxy first!**

- **Use regrex to extra ip**

- **Personally want to use gevent, could compared to multi-thread, twisted is an other choice, NO TORNADO**

