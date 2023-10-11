# WebSocket or Server-Sent

## Status
Proposed

## Context
We are still in debate on which technology we should use for establishing a real-time connection with the app server, to enable location updates.
With our decision process, we think that the Websocket and Server-Sent Events are potential technologies reaching our goal of real-time connection. Server-Sent Events provides options that utilizes HTTP and Websocket provides bidirectional communication features. 

## Decision
We have chosen to use WebSocket and implement it for real-time connection tracking. With WebSocket, it has met the project's requirement for seamless and real-time updates, due to having bidirectional and low-latency communication channel. With Websocket, we are able to track the driver and passenger locations efficiently. 

## Consequences/Rationale
We are anticipating that the app will delivering a real-time location update, improving user experiences, meeting the requirements for accurate tracking, since we have chosen Websocket. Balancing the load and plan for growth is important, making the system stay reliable even when more users join. 

Decision record template by Michael Nygard
