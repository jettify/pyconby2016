### Tips and Tricks Writing Database Clients With Asyncio

My talk at PyCon Belarus'16

### Abstract

Asyncio - is young library for asynchronous network programming. For almost
two years asyncio community have written a lot of drivers to different
databases. Nevertheless, there are still a lot of libraries that need to be
ported or written from scratch. Lack of information on proper use and writing
code in asyncio slows down asyncio adoption. Nikolay will talk about how to
write your own client for database or message queue using asyncio and protocol
pipelining, also he will give overview of internals for most popular database
libraries: aiopg, aiomysql, aioredis and aioodbc as well as bunch of asyncio
tips and tricks.
