# TrelloRestApi
### Rest API project that simulates all possible features of Trello, a project management application, through the Postman tool.

<hr>

#### Description:
<p style="text-align: justify;">The Rest API project called <b>TrelloRestApi</b> is a Trello test project (project management application), which simulates all possible functionalities of this project management application through the <b> Postman </b> tool as described below:</p>
- Features of Actions;</br>
- Features of Applications;</br>
- Features of Batch;</br>
- Features of Boards;</br>
- Features of Cards;</br>
- Features of Checklists;</br>
- Features of CustomFields;</br>
- Features of Emoji;</br>
- Features of Enterprises;</br>
- Features of Labels;</br>
- Features of Lists;</br>
- Features of Members;</br>
- Features of Notifications;</br>
- Features of Organizations;</br>
- Features of Plugins;</br>
- Features of Search;</br>
- Features of Tokens;</br>
- Features of Webhooks.</br>

<hr>

#### Features:
<p style="text-align: justify;">The Rest API called here <b>TrelloRestApi</b> has for each set of service classes many endpoints of the most varied types of services available.</p> 
<p style="text-align: justify;">Combined with the service testing tool available in endpoint format called <b>Postman</b>, the Trello API Documentation is available with all the details not only of the endpoints, but also all of Trello's extra documentation.</p>
<p style="text-align: justify;">Each set of <b>TrelloRestApi</b> service classes has many endpoints of the most varied types of services and are divided as follows:</p>

- **Actions**
- - [<b style="color: green;">GET</b>] Get an Action
- - [<b><font color="blue">PUT</font></b>] Update an Action
- - [<b><font color="red">DEL</font></b>] Delete an Action
- - [<b><font color="green">GET</font></b>] Get a specific field on an Action
- - [<b><font color="green">GET</font></b>] Get the Board for an Action
- - [<b><font color="green">GET</font></b>] Get the Card for an Action
- - [<b><font color="green">GET</font></b>] Get the List for an Action
- - [<b><font color="green">GET</font></b>] Get the Member of an Action
- - [<b><font color="green">GET</font></b>] Get the Member Creator of an Action
- - [<b><font color="green">GET</font></b>] Get the Organization of an Action
- - [<b><font color="blue">PUT</font></b>] Update a Comment Action
- - [<b><font color="green">GET</font></b>] Get Action's Reactions
- - [<b><font color="SandyBrown">POST</font></b>] Create Reaction for Action
- - [<b><font color="green">GET</font></b>] Get Action's Reaction
- - [<b><font color="red">DEL</font></b>] Delete Action's Reaction
- - [<b><font color="green">GET</font></b>] List Action's summary of Reactions
- **Applications**
- -  [<b><font color="green">GET</font></b>] Get Application's compliance data
- **Batch**
- - [<b><font color="green">GET</font></b>] Batch Requests
- **Boards**
- - [<b><font color="green">GET</font></b>] Get Memberships of a Board
- - [<b><font color="green">GET</font></b>] Get a Board
- - [<b><font color="blue">PUT</font></b>] Update a Board
- - [<b><font color="red">DEL</font></b>] Delete a Board
- - [<b><font color="green">GET</font></b>] Get a field on a Board
- - [<b><font color="green">GET</font></b>] Get Actions of a Board
- - [<b><font color="green">GET</font></b>] Get a Card on a Board
- - [<b><font color="green">GET</font></b>] Get boardStars on a Board
- - [<b><font color="green">GET</font></b>] Get Checklists on a Board
- - [<b><font color="green">GET</font></b>] Get Cards on a Board
- - [<b><font color="green">GET</font></b>] Get filtered Cards on a Board
- - [<b><font color="green">GET</font></b>] Get Custom Fields for Board
- - [<b><font color="green">GET</font></b>] Get Labels on a Board
- - [<b><font color="SandyBrown">POST</font></b>] Create a Label on a Board
- - [<b><font color="green">GET</font></b>] Get Lists on a Board
- - [<b><font color="SandyBrown">POST</font></b>] Create a List on a Board
- - [<b><font color="green">GET</font></b>] Get filtered Lists on a Board
- - [<b><font color="green">GET</font></b>] Get the Members of a Board
- - [<b><font color="blue">PUT</font></b>] Invite Member to Board via email
- - [<b><font color="blue">PUT</font></b>] Add a Member to a Board
- - [<b><font color="red">DEL</font></b>] Remove Member from Board
- - [<b><font color="blue">PUT</font></b>] Update Membership of Member on a Board
- - [<b><font color="blue">PUT</font></b>] Update emailPosition Pref on a Board
- - [<b><font color="blue">PUT</font></b>] Update idEmailList Pref on a Board
- - [<b><font color="blue">PUT</font></b>] Update showListGuide Pref on a Board
- - [<b><font color="blue">PUT</font></b>] Update showSidebar Pref on a Board
- - [<b><font color="blue">PUT</font></b>] Update showSidebarActivity Pref on a Board
- - [<b><font color="blue">PUT</font></b>] Update showSidebarBoardActions Pref on a Board
- - [<b><font color="blue">PUT</font></b>] Update showSidebarMembers Pref on a Board
- - [<b><font color="SandyBrown">POST</font></b>] Create a Board
- - [<b><font color="SandyBrown">POST</font></b>] Create a calendarKey for a Board
- - [<b><font color="SandyBrown">POST</font></b>] Create a emailKey for a Board
- - [<b><font color="SandyBrown">POST</font></b>] Create a Tag for a Board
- - [<b><font color="SandyBrown">POST</font></b>] Mark Board as viewed
- - [<b><font color="green">GET</font></b>] Get Enabled Power-Ups on Board
- - [<b><font color="SandyBrown">POST</font></b>] Enable a Power-Up on a Board {Deprecated}
- - [<b><font color="red">DEL</font></b>] Disable a Power-Up on a Board {Deprecated}
- - [<b><font color="green">GET</font></b>] Get Power-Ups on a Board
- **Cards**
- - [<b><font color="SandyBrown">POST</font></b>] Create a new Card
- - [<b><font color="green">GET</font></b>] Get a Card
- - [<b><font color="blue">PUT</font></b>] Update a Card
- - [<b><font color="red">DEL</font></b>] Delete a Card
- - [<b><font color="green">GET</font></b>] Get a field on a Card
- - [<b><font color="green">GET</font></b>] Get Actions on a Card
- - [<b><font color="green">GET</font></b>] Get Attachments on a Card
- - [<b><font color="SandyBrown">POST</font></b>] Create Attachment On Card
- - [<b><font color="green">GET</font></b>] Get an Attachment on a Card
- - [<b><font color="red">DEL</font></b>] Delete an Attachment on a Card
- - [<b><font color="green">GET</font></b>] Get the Board the Card is on
- - [<b><font color="green">GET</font></b>] Get checkItems on a Card
- - [<b><font color="green">GET</font></b>] Get Checklists on a Card
- - [<b><font color="SandyBrown">POST</font></b>] Create Checklist on a Card
- - [<b><font color="green">GET</font></b>] Get checkItem on a Card
- - [<b><font color="blue">PUT</font></b>] Update a checkItem on a Card
- - [<b><font color="red">DEL</font></b>] Delete checkItem on a Card
- - [<b><font color="green">GET</font></b>] Get the List of a Card
- - [<b><font color="green">GET</font></b>] Get the Members of a Card
- - [<b><font color="green">GET</font></b>] Get Members who have voted on a Card
- - [<b><font color="SandyBrown">POST</font></b>] Add Member vote to Card
- - [<b><font color="green">GET</font></b>] Get pluginData on a Card
- - [<b><font color="green">GET</font></b>] Get Stickers on a Card
- - [<b><font color="SandyBrown">POST</font></b>] Add a Sticker to a Card
- - [<b><font color="green">GET</font></b>] Get a Sticker on a Card
- - [<b><font color="blue">PUT</font></b>] Update a Sticker on a Card
- - [<b><font color="red">DEL</font></b>] Delete a Sticker on a Card
- - [<b><font color="blue">PUT</font></b>] Update Comment Action on a Card
- - [<b><font color="red">DEL</font></b>] Delete a comment on a Card
- - [<b><font color="blue">PUT</font></b>] Update Custom Field item on Card
- - [<b><font color="blue">PUT</font></b>] Update Multiple Custom Field items on Card
- - [<b><font color="green">GET</font></b>] Get Custom Field Items for a Card
- - [<b><font color="SandyBrown">POST</font></b>] Add a new comment to a Card
- - [<b><font color="SandyBrown">POST</font></b>] Add a Label to a Card
- - [<b><font color="SandyBrown">POST</font></b>] Add a Member to a Card
- - [<b><font color="SandyBrown">POST</font></b>] Create a new Label on a Card
- - [<b><font color="SandyBrown">POST</font></b>] Mark a Card's Notifications as read
- - [<b><font color="red">DEL</font></b>] Remove a Label from a Card
- - [<b><font color="red">DEL</font></b>] Remove a Member from a Card
- - [<b><font color="red">DEL</font></b>] Remove a Member's Vote on a Card
- - [<b><font color="blue">PUT</font></b>] Update Checkitem on Checklist on Card
- - [<b><font color="red">DEL</font></b>] Delete a Checklist on a Card
- **Checklists**
- - [<b><font color="SandyBrown">POST</font></b>] Create a Checklist
- - [<b><font color="green">GET</font></b>] Get a Checklist
- - [<b><font color="blue">PUT</font></b>] Update a Checklist
- - [<b><font color="red">DEL</font></b>] Delete a Checklist
- - [<b><font color="green">GET</font></b>] Get field on a Checklist
- - [<b><font color="blue">PUT</font></b>] Update field on a Checklist
- - [<b><font color="green">GET</font></b>] Get the Board the Checklist is on
- - [<b><font color="green">GET</font></b>] Get the Card a Checklist is on
- - [<b><font color="green">GET</font></b>] Get Checkitems on a Checklist
- - [<b><font color="SandyBrown">POST</font></b>] Create Checkitem on Checklist
- - [<b><font color="green">GET</font></b>] Get a Checkitem on a Checklist
- - [<b><font color="red">DEL</font></b>] Delete Checkitem from Checklist
- **CustomFields**
- - [<b><font color="SandyBrown">POST</font></b>] Create a new Custom Field on a Board
- - [<b><font color="green">GET</font></b>] Get a Custom Field
- - [<b><font color="blue">PUT</font></b>] Update a Custom Field definition
- - [<b><font color="red">DEL</font></b>] Delete a Custom Field definition
- - [<b><font color="green">GET</font></b>] Get Options of Custom Field drop down
- - [<b><font color="SandyBrown">POST</font></b>] Add Option to Custom Field dropdown
- - [<b><font color="green">GET</font></b>] Get Option of Custom Field dropdown
- - [<b><font color="red">DEL</font></b>] Delete Option of Custom Field dropdown
- **Emoji**
- - [<b><font color="green">GET</font></b>] List available Emoji
- **Enterprises**
- - [<b><font color="green">GET</font></b>] Get an Enterprise
- - [<b><font color="green">GET</font></b>] Get auditlog data for an Enterprise
- - [<b><font color="green">GET</font></b>] Get Enterprise admin Members
- - [<b><font color="green">GET</font></b>] Get signupUrl for Enterprise
- - [<b><font color="green">GET</font></b>] Get Users of an Enterprise
- - [<b><font color="green">GET</font></b>] Get Members of Enterprise
- - [<b><font color="green">GET</font></b>] Get a Member of Enterprise
- - [<b><font color="green">GET</font></b>] Get whether an organization can be transferred to an enterprise.
- - [<b><font color="green">GET</font></b>] Get a bulk list of organizations that can be transferred to an enterprise.
- - [<b><font color="blue">PUT</font></b>] Decline enterpriseJoinRequests from one organization or a bulk list of organizations.
- - [<b><font color="green">GET</font></b>] Get ClaimableOrganizations of an Enterprise
- - [<b><font color="green">GET</font></b>] Get PendingOrganizations of an Enterprise
- - [<b><font color="SandyBrown">POST</font></b>] Create an auth Token for an Enterprise.
- - [<b><font color="blue">PUT</font></b>] Transfer an Organization to an Enterprise.
- - [<b><font color="blue">PUT</font></b>] Update a Member's licensed status
- - [<b><font color="blue">PUT</font></b>] Deactivate a Member of an Enterprise.
- - [<b><font color="blue">PUT</font></b>] Update Member to be admin of Enterprise
- - [<b><font color="red">DEL</font></b>] Remove a Member as admin from Enterprise.
- - [<b><font color="red">DEL</font></b>] Delete an Organization from an Enterprise.
- - [<b><font color="green">GET</font></b>] Bulk accept a set of organizations to an Enterprise.
- **Labels**
- - [<b><font color="green">GET</font></b>] Get a Label
- - [<b><font color="blue">PUT</font></b>] Update a Label
- - [<b><font color="red">DEL</font></b>] Delete a Label
- - [<b><font color="blue">PUT</font></b>] Update a field on a label
- - [<b><font color="SandyBrown">POST</font></b>] Create a Label
- **Lists**
- - [<b><font color="green">GET</font></b>] Get a List
- - [<b><font color="blue">PUT</font></b>] Update a List
- - [<b><font color="SandyBrown">POST</font></b>] Create a new List
- - [<b><font color="SandyBrown">POST</font></b>] Archive all Cards in List
- - [<b><font color="SandyBrown">POST</font></b>] Move all Cards in List
- - [<b><font color="blue">PUT</font></b>] Archive or unarchive a list
- - [<b><font color="blue">PUT</font></b>] Move List to Board
- - [<b><font color="blue">PUT</font></b>] Update a field on a List
- - [<b><font color="green">GET</font></b>] Get Actions for a List
- - [<b><font color="green">GET</font></b>] Get the Board a List is on
- - [<b><font color="green">GET</font></b>] Get Cards in a List
- **Members**
- - [<b><font color="green">GET</font></b>] Get a Member
- - [<b><font color="blue">PUT</font></b>] Update a Member
- - [<b><font color="green">GET</font></b>] Get a field on a Member
- - [<b><font color="green">GET</font></b>] Get a Member's Actions
- - [<b><font color="green">GET</font></b>] Get Member's custom Board backgrounds
- - [<b><font color="SandyBrown">POST</font></b>] Upload new boardBackground for Member
- - [<b><font color="green">GET</font></b>] Get a boardBackground of a Member
- - [<b><font color="blue">PUT</font></b>] Update a Member's custom Board background
- - [<b><font color="red">DEL</font></b>] Delete a Member's custom Board background
- - [<b><font color="green">GET</font></b>] Get a Member's boardStars
- - [<b><font color="SandyBrown">POST</font></b>] Create Star for Board
- - [<b><font color="green">GET</font></b>] Get a boardStar of Member
- - [<b><font color="blue">PUT</font></b>] Update the position of a boardStar of Member
- - [<b><font color="red">DEL</font></b>] Delete Star for Board
- - [<b><font color="green">GET</font></b>] Get Boards that Member belongs to
- - [<b><font color="green">GET</font></b>] Get Boards the Member has been invited to
- - [<b><font color="green">GET</font></b>] Get Cards the Member is on
- - [<b><font color="green">GET</font></b>] Get a Member's custom Board Backgrounds
- - [<b><font color="SandyBrown">POST</font></b>] Create a new custom Board Background
- - [<b><font color="green">GET</font></b>] Get custom Board Background of Member
- - [<b><font color="blue">PUT</font></b>] Update custom Board Background of Member
- - [<b><font color="red">DEL</font></b>] Delete custom Board Background of Member
- - [<b><font color="green">GET</font></b>] Get a Member's customEmojis
- - [<b><font color="SandyBrown">POST</font></b>] Create custom Emoji for Member
- - [<b><font color="green">GET</font></b>] Get a Member's custom Emoji
- - [<b><font color="green">GET</font></b>] Get Member's custom Stickers
- - [<b><font color="SandyBrown">POST</font></b>] Create custom Sticker for Member
- - [<b><font color="green">GET</font></b>] Get a Member's custom Sticker
- - [<b><font color="red">DEL</font></b>] Delete a Member's custom Sticker
- - [<b><font color="green">GET</font></b>] Get Member's Notifications
- - [<b><font color="green">GET</font></b>] Get Member's Organizations
- - [<b><font color="green">GET</font></b>] Get Organizations a Member has been invited to
- - [<b><font color="green">GET</font></b>] Get Member's saved searched
- - [<b><font color="SandyBrown">POST</font></b>] Create saved Search for Member
- - [<b><font color="green">GET</font></b>] Get a saved search
- - [<b><font color="blue">PUT</font></b>] Update a saved search
- - [<b><font color="red">DEL</font></b>] Delete a saved search
- - [<b><font color="green">GET</font></b>] Get Member's Tokens
- - [<b><font color="SandyBrown">POST</font></b>] Create Avatar for Member
- - [<b><font color="SandyBrown">POST</font></b>] Dismiss a message for Member
- - [<b><font color="green">GET</font></b>] Get a Member's notification channel settings
- - [<b><font color="blue">PUT</font></b>] Update blocked notification keys of Member on a channel
- - [<b><font color="green">GET</font></b>] Get blocked notification keys of Member on this channel
- - [<b><font color="blue">PUT</font></b>] Update blocked notification keys of Member on a channel
- - [<b><font color="blue">PUT</font></b>] Update blocked notification keys of Member on a channe
- **Notifications**
- - [<b><font color="green">GET</font></b>] Get a Notification
- - [<b><font color="blue">PUT</font></b>] Update a Notification's read status
- - [<b><font color="green">GET</font></b>] Get a field of a Notification
- - [<b><font color="SandyBrown">POST</font></b>] Mark all Notifications as read
- - [<b><font color="blue">PUT</font></b>] Update Notification's read status
- - [<b><font color="green">GET</font></b>] Get the Board a Notification is on
- - [<b><font color="green">GET</font></b>] Get the Card a Notification is on
- - [<b><font color="green">GET</font></b>] Get the List a Notification is on
- - [<b><font color="green">GET</font></b>] Get the Member a Notification is about (not the creator)
- - [<b><font color="green">GET</font></b>] Get the Member who created the Notification
- - [<b><font color="green">GET</font></b>] Get a Notification's associated Organization
- **Organizations**
- - [<b><font color="SandyBrown">POST</font></b>] Create a new Organization
- - [<b><font color="green">GET</font></b>] Get an Organization
- - [<b><font color="blue">PUT</font></b>] Update an Organization
- - [<b><font color="red">DEL</font></b>] Delete an Organization
- - [<b><font color="green">GET</font></b>] Get field on Organization
- - [<b><font color="green">GET</font></b>] Get Actions for Organization
- - [<b><font color="green">GET</font></b>] Get Boards in an Organization
- - [<b><font color="green">GET</font></b>] Retrieve Organization's Exports
- - [<b><font color="SandyBrown">POST</font></b>] Create Export for Organizations
- - [<b><font color="green">GET</font></b>] Get the Members of an Organization
- - [<b><font color="blue">PUT</font></b>] Update an Organization's Members
- - [<b><font color="green">GET</font></b>] Get Memberships of an Organization
- - [<b><font color="green">GET</font></b>] Get a Membership of an Organization
- - [<b><font color="green">GET</font></b>] Get the pluginData Scoped to Organization
- - [<b><font color="green">GET</font></b>] Get Tags of an Organization
- - [<b><font color="SandyBrown">POST</font></b>] Create a Tag in Organization
- - [<b><font color="blue">PUT</font></b>] Update a Member of an Organization
- - [<b><font color="red">DEL</font></b>] Remove a Member from an Organization
- - [<b><font color="blue">PUT</font></b>] Deactivate or reactivate a member of an Organization
- - [<b><font color="SandyBrown">POST</font></b>] Update logo for an Organization
- - [<b><font color="red">DEL</font></b>] Delete Logo for Organization
- - [<b><font color="red">DEL</font></b>] Remove a Member from an Organization and all Organization Boards
- - [<b><font color="red">DEL</font></b>] Remove the associated Google Apps domain from a Workspace
- - [<b><font color="red">DEL</font></b>] Delete the email domain restriction on who can be invited to the Workspace
- - [<b><font color="red">DEL</font></b>] Delete an Organization's Tag
- - [<b><font color="green">GET</font></b>] Get Organizations new billable guests
- **Plugins**
- - [<b><font color="green">GET</font></b>] Get a Plugin
- - [<b><font color="blue">PUT</font></b>] Update a Plugin
- - [<b><font color="SandyBrown">POST</font></b>] Create a Listing for Plugin
- - [<b><font color="green">GET</font></b>] Get Plugin's Member privacy compliance
- - [<b><font color="blue">PUT</font></b>] Updating Plugin's Listing
- **Search**
- - [<b><font color="green">GET</font></b>] Search Trello
- - [<b><font color="green">GET</font></b>] Search for Members
- **Tokens**
- - [<b><font color="green">GET</font></b>] Get a Token
- - [<b><font color="green">GET</font></b>] Get Token's Member
- - [<b><font color="green">GET</font></b>] Get Webhooks for Token
- - [<b><font color="SandyBrown">POST</font></b>] Create Webhooks for Token
- - [<b><font color="green">GET</font></b>] Get a Webhook belonging to a Token
- - [<b><font color="blue">PUT</font></b>] Update a Webhook created by Token
- - [<b><font color="red">DEL</font></b>] Delete a Webhook created by Token
- - [<b><font color="red">DEL</font></b>] Delete a Token
- **Webhooks**
- - [<b><font color="SandyBrown">POST</font></b>] Create a Webhook
- - [<b><font color="green">GET</font></b>] Get a Webhook
- - [<b><font color="blue">PUT</font></b>] Update a Webhook
- - [<b><font color="red">DEL</font></b>] Delete a Webhook
- - [<b><font color="green">GET</font></b>] Get a field on a Webhook

<hr>

#### Image:
![alt text](image.png)

<hr>

#### Credits:
This project made in Postman was based on the following course:
- https://www.udemy.com/course/postman-the-complete-guide/

The API Documentation is based on the following link:
- https://developer.atlassian.com/cloud/trello/rest/api-group-actions/

About Trello and API Keys:
- https://developer.atlassian.com/cloud/trello/guides/rest-api/api-introduction/
- https://trello.com/app-key

<hr>

This project was created by **Alexandre Rodrigues da Silva**.