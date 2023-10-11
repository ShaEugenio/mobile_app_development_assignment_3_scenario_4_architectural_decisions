# Push Notification Service Provider

## Status
Proposed

## Context
We are debating on which service provider to use for our transportation app development. it is essential for us to have a push notification system for the ride confirmation, driver updates, and announcements. It is included in our criteria that the support for both iOS and Android platforms are available. Additionally, features like personalization and message targeting should also be included.  

## Decision
We have chosen to use Firebase Cloud messaging (FCM) as our push notification service provider. With Firebase Cloud Messaging, it provides robust support for iOS and Android platforms, with this we are able to meet the project's requirement for cross-platform compatibility. It also offers advanced features, like personalization, message targeting, that will enhance our ability to engage users effectively. 

## Consequences/Rationale
Since we have decided to use FMC for a push notifications, we are anticipating that we can meet the app's requirement for the timely and personalized user notifications, which can enhance the app's experiences for the passengers and drivers. Although it has some good features, it is required to have development effort and ongoing maintenance to ensure reliable notification delivery. We also need to follow the guidelines of FMC's in order to maximize the benefits.  

Decision record template by Michael Nygard