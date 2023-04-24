# Raft
A simplified implementation of Raft consensus algorithm
-  Node's task is data storing, there is one leader in nodes which they must agree on in the step, then the leader is responsible for synchronization, it receives 3 data then syncs data with others
-  Client's task is data sending, it chooses a node randomly and send its data.
