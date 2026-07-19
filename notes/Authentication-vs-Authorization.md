# Authentication vs Authorization

## Authentication

Authentication verifies the identity of a user.

It answers the question:

> Who are you?

### Examples

- Password
- MFA
- Microsoft Authenticator
- Security Key
- Biometrics

---

## Authorization

Authorization determines what an authenticated user is allowed to access or perform.

It answers the question:

> What are you allowed to do?

### Examples

- Read
- Write
- Modify
- Delete
- Manage Resources

---

## Difference

| Authentication | Authorization |
|---|---|
| Verifies identity | Determines permissions |
| Answers "Who are you?" | Answers "What can you do?" |
| Happens before authorization | Happens after authentication |

## Example

A user logs in with a username, password, and MFA.

This is Authentication.

After successful authentication, Azure checks whether the user has permission to access a specific resource.

This is Authorization.

## Key Learning

Authentication verifies identity, while authorization controls access and permissions.
