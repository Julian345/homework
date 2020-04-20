Types of transparency

a)
1.Access transparency: Every operating system has a different low-level architecture. Acces transparency means that differences in data representation should be hidden. Also the way how objects are accessed by different machines should not be visibile for an user.
2.Location transparency: Users cannot tell where data or a process is physically located.
3.Relocation transparency: A user will not notice if an object is moved from one location to another by the system. For example: if Wikipedia would send all data to another datacenter, the user will not notice that and see the same data in the browser as before.
4.Migration transparency: The system can support the mobility of processes and resources initiated by users. For example: Users can make a conversation with a mobile phone while walking on an street(changing his place)
5.Replication transparency: It can be usefull to replicate a resource in order to increase the availability or the performance. It is also possible, that a duplicate of a process can be used if the origin precess failed. The user should not notice, if replicated object are existing. It is nescessary that all replicas have the same name. Replication transparency is normally combindes with location transparency
6.Concurrency transparency:If two users acces the same data for example in a database, it is importent to take care about consistancy. This can be achieved though locking mechanisms…that just one juser has exclusive access or with transactions,but this can be difficult if scalability is an issue
7.Failure transparency:A user or an application should not notice if some piece of the system fails or does not work properly. Often this is difficult.

b)
1.In cross plattform applications, each operating system has rules for the design and how to show data. In this case differences in data representation are not a problem.(access transparency)

2.example: I think it is also depending on the level of security that the system should have, witch kinds of transparency should be achieved. In some cases it is not a problem, when a user notice, that the location of an object has changed(relocation transparency)

3.A system can be designed that users should never change data – so the users have „read only“ rights for example the homepage https://heilkraeuter.de/lexikon/. In this case, the concorrency transparency is not nescessairy.


Development Pitfalls


During design time, it is important to think about the dispersion across a network, otherwise a system can be needlessly complex.
-Often, a reliable notwork does not exist
-A network is often not secured enough and not homogeneous
-It is possible that the topology can change
-Normally  the latency is not zero
-There is a limited bandwidth
-It exists cost for transport
-Often systems can have mkultiple administrators

 Type of Communication
a)	Persistant asynchronous communication
b)	Persistant synchronous communication
c)	Transient asynchronous communication
d)	Receipt-based transient synchronous communication
e)	Delivery-based transient synchronous communication at message delivery
f)	Response-based transient synchronous communication


