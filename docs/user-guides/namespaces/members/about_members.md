---
sidebar_position: 1
---

# About Members

Members are users who have been granted access to contribute to a namespace.
They play a crucial role in collaborative environments by enabling multiple
users to work together within the same namespace.

Each member is assigned a specific [role](TODO) that defines their access level
and permissions within the namespace. Roles are hierarchical, with users in
higher roles inheriting the permissions of those in lower roles.

:::tip
When a namespace is created, the user who creates it is automatically
designated as the **owner**. The owner holds the highest level of permissions
within the namespace and is responsible for managing all aspects, including
member management.
:::

## Invitation and Status

Members can have one of two statuses: **pending** or **accepted**. Members with
a **pending** status cannot perform any actions until they accept the
invitation. Users can accept the invitation via an invitation email.

:::note
In *enterprise* and *community* instances, users are automatically assigned an
**accepted** status upon invitation.
:::

## API Key Generation

Members can generate [API keys](TODO) for programmatic access to the namespace.
They are only able to create API keys with permissions equal to or lower than
their own role.
