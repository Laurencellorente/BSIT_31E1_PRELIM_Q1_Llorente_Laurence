1. Why did you use inheritance?

\- because all transport types are vehicles. They share common characteristics, so having a base Vehicle avoids repeating the code and makes the program more organized



2\. Why did you use interfaces?

\- because they describe what an object can do. Different vehicles have different abilities, such as driving, flying, or sailing.



3\. Can Helicopter inherit from both Vehicle and Airplane? Why or why not?

-No. In C#, a class can inherit from only one base class. Since Helicopter already inherits from Vehicle, it cannot also inherit from Airplane.





4\. Why can Helicopter implement both IFlyable and IDriveable?

\- Because a class can have implement multiple interface in c#. because a helicopter can fly and drive so both iflyable and idriveable wil still function like a vehicle



5\. If a Submarine can both sail and dive, how would you design it?

\- for me a submarine can still be vehicle and can be a isaliable and idiveable interface, it keeps the design organized and follows that can create

