# mininet



Tasks

Additional “dpctl add-flow” command to the ones described on slide №6 to make a ping to h3 possible from h1 and h2.
Find and compare controller generated flow table with the one which was created by hand.
Command to create topology is:  sudo mn --topo single,3 --mac --switch ovsk --controller remote
Answer the question: Is it efficient to replicate the flow tables by hand? In what situations this may be required? Elaborate your answer!
Find and write out the controller generated flow rules for communication between h1 and h2.
Command to create topology is: sudo mn --topo linear,3 --controller remote --switch ovsk --mac
Find and write out the controller generated flow rules for communication between h1 and h4.
Command to create topology is: sudo mn --topo tree,depth=3,fanout=2 --controller remote --switch ovsk --mac
