```mermaid
sequenceDiagram
participant Attacker
participant BotNet
participant Firewall
participant WebServer

Attacker ->>+ BotNet: I would like to test your bots!
Attacker ->>+ BotNet: Give me your best infected hosts.
BotNet -->> Attacker: Giving access to the 5 infected bots...
Attacker ->>+ BotNet: Launch the DDoS toward this WebServer.
BotNet -->> Attacker: Processing command from Attacker...
BotNet -->> Attacker: Process Successful.
BotNet -->> Firewall: Sending infected hosts to WebServer..
Firewall ->>+ BotNet: Hey, what do you think you're doing?
Firewall ->>+ BotNet: Why is there so many users coming from you?!
Firewall -->> BotNet: Cancelling your access requests..
Firewall -->> WebServer: Sending report of processes, including the attempted DDoS..
WebServer ->>+ Firewall: Thank you, Firewall! I am so grateful that I have you installed!!
BotNet ->>+ Attacker: Attacker, the planned DDoS was unsuccessful for the WebServer.
Attacker ->>+ BotNet: What?! This botnet is so unreliable..
Attacker ->>+ BotNet: I'll get you next time, WebServer!!

```

## Documentation
### Steps:
1. Attacker uses a command and control server to communicate with the chosen Botnet.
2. Attacker then sends the launch command from the command and control server to the botnet to start the DDoS attack.
3. The botnet will then send bots to send an attack traffic to the WebServer.
4. However, since there was a Firewall implemented, there will be a layer of security to notice the suspicious activity from IPs.
5. The firewall then blocks the suspicious IPs to prevent further harm from the attempted DDoS attack.