# vernemq_notes
Includes information about VerneMQ

# Start and Stop VerneMQ
Type command ```vernemq start```. If it is successful return no output.

# Check Broker is Running
Type command ```vernemq ping``` command. If it is running , ```pong``` will be shown in the terminal. 
Otherwise ```Node <NodeName> not responding to pings```

# List Current Sessions
Type command ```vmq-admin session show```. This will gonna show clientID and etc.

# Tracing Clients
Type command : ```vmq-admin trace client client-id=<client-id>```

# Status Page
Shows some information about Broker. Can be access via this [link](http://localhost:8888/status) if the Broker is running.
These are;
* Cluster Size
* Clients Online
* Publish Rate
* Message Queued
* Node Status and etc.
