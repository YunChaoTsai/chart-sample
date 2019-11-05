# Slightly Better Class Diagram

```nomnoml
[<abstract>Wagon|maxPeople:int;wheels:int|go();stop()]<:-[Car|start();stop()]
[Car]<:-[Pickup|maxCapacity:int|load()]
[Pickup]->[Trailer|wheels:int]

#fontSize: 10
#lineWidth: 1
```
