# Authentication Mechanisms

## Status
Proposed

## Context
We are deciding which authentication mechanisms to implement for both drivers and passengers. Our objective is to ensure secure access to the app in compliance with security requirements. The chosen mechanisms will include email/password, social login, and two-factor authentication (2FA). In order to control access to various app functionalities and user data, we will also need to define and enforce proper permission rules. The management of user access and the security of confidential data within the app depend heavily on authentication and authorization.

## Decision
We have decided to combine authentication mechanisms in our transportation app. Passengers and drivers will have the choice to confirm their identity through the straightforward process of entering their email address and password. We will also offer the ease of social login on websites like Facebook and Google. We will enforce two-factor authentication (2FA) for additional security, strengthening account protection, and satisfying the security requirement for both drivers and passengers. Users will only be able to access features and data relevant to their roles as a result of the implementation of authorization rules.

## Consequences/Rationale
We will implement these authentication mechanisms to align with the requirement for secure authentication and authorization in the transportation app. We are giving users the freedom to pick their preferred login methods. We will keep user accounts safer from unauthorized access by doing this. We are also adding another layer of protection with two-factor authentication. Sensitive data will be protected, and only authorized users will gain access to specific app functionalities with the implementation of appropriate authorization rules. This decision will result in the overall improvement of the security and effectiveness of the transportation app.

Decision record template by Michael Nygard