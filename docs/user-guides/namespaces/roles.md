---
sidebar_position: 2
sidebar_label: Roles
---

# Roles

Roles define the access levels for a [member](./members/about_members.md)
within a namespace. Roles are hierarchical, meaning users with higher roles
inherit the permissions of those with lower roles.

When a namespace is created, the user who creates it is automatically
designated as the **owner**. The owner holds the highest level of permissions
within the namespace and is responsible for managing all aspects, including
member management.

The following roles can be applied to members:

- **Owner**: The creator of the namespace, with the highest level of
  permissions. Owners can perform all actions, including accessing billing
  information.
- **Administrator**: Administrators have full access to the namespace and can
  perform nearly all actions that the owner can, except for accessing billing
  information.
- **Operator**: Operators can perform basic operations on devices within the
  namespace.
- **Observer**: Observers can connect to and view details about devices and
  their sessions but cannot create API keys.

