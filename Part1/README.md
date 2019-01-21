###Part1: Thinking about elevators
---------------------------

Not for handing in, just for thinking about. Talk to other groups, assistants, or even people who have taken the course in previous years.

Brainstorm some techniques you could use to prevent a user from being hopelessly stranded, waiting for an elevator that will never arrive. Think about the [worst-case](http://xkcd.com/748/) behaviour of the system.
 - What if the software controlling one of the elevators suddenly crashes?
    - We can send an other lift.
    - Restart and pull from a backup.
    - Fault detection - New broadcast?
    -
 - What if it doesn't crash, but hangs?
    - We can send an other lift.
    - See Q/A over.
    - What is the difference??
 - What if a message between machines is lost?
    - Resend message
    - Check if message is received.
    - Backup
 - What if the network cable is suddenly disconnected? Then re-connected?
    - Initialize to a default setting
    - Stops at a given floor
    -  
 - What if a user of the system is being a troll?
    - Not sure
    - Set a timer if the elevator is jamed/stoped for too long.
    -
 - What if the elevator car never arrives at its destination?
    - Resend the message
    - Send a new car
    - fault detection mechanism 
