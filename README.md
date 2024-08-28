# Hello
## Simple Multisynq Application
"Hello"is an example of a simple Multisynq applicaton. It creates a counter that counts up once
per second. Clicking on it resets it to zero. The counter is replicated across the network and
will respond to clicks from any user in the same session, which will reset the counter to zero
for everyone. The current value of the counter is automatically saved in a snapshot to the cloud.
Thus, if you leave and rejoin the app with the same session ID, you will simply pick up the 
count where you left off before.