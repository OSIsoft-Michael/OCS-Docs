---
uid: community-invite
---

# Invite a tenant to a community

To allow another tenant to join your community, you must complete a three-way handshake that includes the following steps:

1. A [community administrator](xref:ccRoles#community-administration) from the establishing tenant, also known as the community owner, sends an email invitation to a tenant administrator from another tenant. 

1. The tenant administrator from the invited tenant accepts the invitation.

1. The community administrator who issued the invitation confirms it, allowing the partner to begin participating in the community. The community is private; users outside of your community cannot access it without an invitation.

**Note:** These instructions are written for the community owner who is *sending* the invition. For instructions for the tenant administator *receiving* the invitation, see <xref:community-accept-invite>.

## Prerequisites for sending community invitations

To send a community invitation, you must meet the follow prerequisites:

- Your user account must be assigned [community administration](xref:ccRoles#community-administrators-preview) permissions.

- Your business partner must already have a tenant in OSIsoft Cloud Services (OCS).

- You must have the email address for the Tenant Administrator from the tenant you are inviting. 

## Step 1: Invite a tenant to the community

To invite another tenant to the community, follow these steps:

1. In the left pane, select **Data Management** > **Communities**.

1. Find the community you want to invite another tenant to and select **Details**.

1. On the **Tenants** tab, select **Invite Tenant**.

1. Enter the email address of the Tenant Administrator for the tenant you would like to invite. Then select **Invite**.

  An email is sent to the invited Tenant Administrator.

## Step 2: Wait for invited tenants to accept invitation

After you send an invitation to another tenant, wait for its tenant administrator to accept the email invitation.

**Tips:** 

- Share <xref:community-accept-invite> with the invited tenant administrator for instruction.

- If the invited tenant administrator does not receive the initial email invitation, you can resend it to them. For instructions, see [Resend email invitation](#resend-email-invitation). 

## Step 3: Confirm the invitation

To confirm an invitation, follow these steps:

1. In the left pane, select **Data Management** > **Communities**.

1. On the `Communities` overview page, find the community that you have invited another tenant to and select **Details**.

1. On the `Community Details` page, select the **Invitations** tab.

1. Select an invitation with a status of **Invitation Accepted**.

1. On the `Invitation Details` pane, select **Confirm Tenant**. When prompted for confirmation, select **Confirm Tenant** again.

  The invitee's tenant is now part of the community.

## Resend email invitation

If you invite another tenant to the community but its Tenant Administrator does not receive the invitation email, you can resend it. To resend an invitation, follow these steps:

1. In the left pane, select **Data Management** > **Communities**.

1. On the `Communities` overview page, find the community that you have invited another tenant to and select **Details**.

1. On the `Community Details` page, select the **Invitations** tab.

1. Find the **Invitation Recipient** who has not received the email invitation with a **Status** of `Invitation Pending`. Select the recipient, and then select **Resend Invitation**.