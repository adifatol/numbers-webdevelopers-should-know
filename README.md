# Numbers every web developer should know

Here are the __numbers that every web developer should know__!

This is still work in progress. 
Everyone is welcomed to contribute, just fork the repo and do a PR when you have something to add/fix!

## Summary

 - average response time for a HTTP request should start from ~ 150 ms
 - an average server with ~4 cores & 4 GB RAM should support:
   - __from__ 500 ~ 1000 req / sec Apache
   - __from__ 2000 ~ 5000 req / sec Nginx
   - __from__ 10 ~ 100 inserts / sec MySQL/PostgreSQL
   - __from__ 100 ~ 1000 selects / sec MySQL/PostgreSQL
 - an average request time from one server to another (same network) should be 10 ~ 50 ms
 - php concurrent threads from 50 ~ 100k

A __Request__
 
 See the [X-Ray of a request](benchmarks/request.md)

## Web servers
  [waiting for summary](benchmarks/webservers.md)

## Databases

  ### RDBMS
    https://mariadb.org/performance-evaluation-of-mariadb-10-1-and-mysql-5-7-4-labs-tplc/
    [waiting for summary]
  ### NOSQL
    [waiting for summary]

## Services (Redis, Memcached etc)
  [waiting for summary]

## Programming Languages, interpretors
  [waiting for summary]

## Frameworks
  [waiting for summary]

## Libraries
  [waiting for summary]

## Resources
A list of resources that inspired the data above or where you can find more details:

 - https://www.techempower.com/benchmarks/#section=data-r15&hw=ph&test=fortune
