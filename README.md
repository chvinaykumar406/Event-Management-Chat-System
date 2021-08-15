# Event-Management-Chat-System
-> An event posting and chatting application allows users to sign-up and create event-specific chat threads.
-> Events are identified by a keyword and stored within a red-black tree organized by keyword. Events with the same keyword are stored in a linear linked list and      are accessible in O(log N) time.
-> Events can be displayed and their corresponding chat when queried by keyword. Operator overloading implements common functions for LLL           insertion/display/replication and relational operators for comparison between users and events.
-> Chat histories are stored within a dynamically created external data file per event.
