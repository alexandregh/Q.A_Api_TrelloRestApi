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
- - [<b style="color:green">GET</b>] Get an Action
- - [<b style="color:blue">PUT</b>] Update an Action
- - [<b style="color:red">DEL</b>] Delete an Action
- - [<b style="color:green">GET</b>] Get a specific field on an Action
- - [<b style="color:green">GET</b>] Get the Board for an Action
- - [<b style="color:green">GET</b>] Get the Card for an Action
- - [<b style="color:green">GET</b>] Get the List for an Action
- - [<b style="color:green">GET</b>] Get the Member of an Action
- - [<b style="color:green">GET</b>] Get the Member Creator of an Action
- - [<b style="color:green">GET</b>] Get the Organization of an Action
- - [<b style="color:blue">PUT</b>] Update a Comment Action
- - [<b style="color:green">GET</b>] Get Action's Reactions
- - [<b style="color:SandyBrown">POST</b>] Create Reaction for Action
- - [<b style="color:green">GET</b>] Get Action's Reaction
- - [<b style="color:red">DEL</b>] Delete Action's Reaction
- - [<b style="color:green">GET</b>] List Action's summary of Reactions
- **Applications**
- -  [<b style="color:green">GET</b>] Get Application's compliance data
- **Batch**
- - [<b style="color:green">GET</b>] Batch Requests
- **Boards**
- - [<b style="color:green">GET</b>] Get Memberships of a Board
- - [<b style="color:green">GET</b>] Get a Board
- - [<b style="color:blue">PUT</b>] Update a Board
- - [<b style="color:red">DEL</b>] Delete a Board
- - [<b style="color:green">GET</b>] Get a field on a Board
- - [<b style="color:green">GET</b>] Get Actions of a Board
- - [<b style="color:green">GET</b>] Get a Card on a Board
- - [<b style="color:green">GET</b>] Get boardStars on a Board
- - [<b style="color:green">GET</b>] Get Checklists on a Board
- - [<b style="color:green">GET</b>] Get Cards on a Board
- - [<b style="color:green">GET</b>] Get filtered Cards on a Board
- - [<b style="color:green">GET</b>] Get Custom Fields for Board
- - [<b style="color:green">GET</b>] Get Labels on a Board
- - [<b style="color:SandyBrown">POST</b>] Create a Label on a Board
- - [<b style="color:green">GET</b>] Get Lists on a Board
- - [<b style="color:SandyBrown">POST</b>] Create a List on a Board
- - [<b style="color:green">GET</b>] Get filtered Lists on a Board
- - [<b style="color:green">GET</b>] Get the Members of a Board
- - [<b style="color:blue">PUT</b>] Invite Member to Board via email
- - [<b style="color:blue">PUT</b>] Add a Member to a Board
- - [<b style="color:red">DEL</b>] Remove Member from Board
- - [<b style="color:blue">PUT</b>] Update Membership of Member on a Board
- - [<b style="color:blue">PUT</b>] Update emailPosition Pref on a Board
- - [<b style="color:blue">PUT</b>] Update idEmailList Pref on a Board
- - [<b style="color:blue">PUT</b>] Update showListGuide Pref on a Board
- - [<b style="color:blue">PUT</b>] Update showSidebar Pref on a Board
- - [<b style="color:blue">PUT</b>] Update showSidebarActivity Pref on a Board
- - [<b style="color:blue">PUT</b>] Update showSidebarBoardActions Pref on a Board
- - [<b style="color:blue">PUT</b>] Update showSidebarMembers Pref on a Board
- - [<b style="color:SandyBrown">POST</b>] Create a Board
- - [<b style="color:SandyBrown">POST</b>] Create a calendarKey for a Board
- - [<b style="color:SandyBrown">POST</b>] Create a emailKey for a Board
- - [<b style="color:SandyBrown">POST</b>] Create a Tag for a Board
- - [<b style="color:SandyBrown">POST</b>] Mark Board as viewed
- - [<b style="color:green">GET</b>] Get Enabled Power-Ups on Board
- - [<b style="color:SandyBrown">POST</b>] Enable a Power-Up on a Board {Deprecated}
- - [<b style="color:red">DEL</b>] Disable a Power-Up on a Board {Deprecated}
- - [<b style="color:green">GET</b>] Get Power-Ups on a Board
- **Cards**
- - [<b style="color:SandyBrown">POST</b>] Create a new Card
- - [<b style="color:green">GET</b>] Get a Card
- - [<b style="color:blue">PUT</b>] Update a Card
- - [<b style="color:red">DEL</b>] Delete a Card
- - [<b style="color:green">GET</b>] Get a field on a Card
- - [<b style="color:green">GET</b>] Get Actions on a Card
- - [<b style="color:green">GET</b>] Get Attachments on a Card
- - [<b style="color:SandyBrown">POST</b>] Create Attachment On Card
- - [<b style="color:green">GET</b>] Get an Attachment on a Card
- - [<b style="color:red">DEL</b>] Delete an Attachment on a Card
- - [<b style="color:green">GET</b>] Get the Board the Card is on
- - [<b style="color:green">GET</b>] Get checkItems on a Card
- - [<b style="color:green">GET</b>] Get Checklists on a Card
- - [<b style="color:SandyBrown">POST</b>] Create Checklist on a Card
- - [<b style="color:green">GET</b>] Get checkItem on a Card
- - [<b style="color:blue">PUT</b>] Update a checkItem on a Card
- - [<b style="color:red">DEL</b>] Delete checkItem on a Card
- - [<b style="color:green">GET</b>] Get the List of a Card
- - [<b style="color:green">GET</b>] Get the Members of a Card
- - [<b style="color:green">GET</b>] Get Members who have voted on a Card
- - [<b style="color:SandyBrown">POST</b>] Add Member vote to Card
- - [<b style="color:green">GET</b>] Get pluginData on a Card
- - [<b style="color:green">GET</b>] Get Stickers on a Card
- - [<b style="color:SandyBrown">POST</b>] Add a Sticker to a Card
- - [<b style="color:green">GET</b>] Get a Sticker on a Card
- - [<b style="color:blue">PUT</b>] Update a Sticker on a Card
- - [<b style="color:red">DEL</b>] Delete a Sticker on a Card
- - [<b style="color:blue">PUT</b>] Update Comment Action on a Card
- - [<b style="color:red">DEL</b>] Delete a comment on a Card
- - [<b style="color:blue">PUT</b>] Update Custom Field item on Card
- - [<b style="color:blue">PUT</b>] Update Multiple Custom Field items on Card
- - [<b style="color:green">GET</b>] Get Custom Field Items for a Card
- - [<b style="color:SandyBrown">POST</b>] Add a new comment to a Card
- - [<b style="color:SandyBrown">POST</b>] Add a Label to a Card
- - [<b style="color:SandyBrown">POST</b>] Add a Member to a Card
- - [<b style="color:SandyBrown">POST</b>] Create a new Label on a Card
- - [<b style="color:SandyBrown">POST</b>] Mark a Card's Notifications as read
- - [<b style="color:red">DEL</b>] Remove a Label from a Card
- - [<b style="color:red">DEL</b>] Remove a Member from a Card
- - [<b style="color:red">DEL</b>] Remove a Member's Vote on a Card
- - [<b style="color:blue">PUT</b>] Update Checkitem on Checklist on Card
- - [<b style="color:red">DEL</b>] Delete a Checklist on a Card
- **Checklists**
- - [<b style="color:SandyBrown">POST</b>] Create a Checklist
- - [<b style="color:green">GET</b>] Get a Checklist
- - [<b style="color:blue">PUT</b>] Update a Checklist
- - [<b style="color:red">DEL</b>] Delete a Checklist
- - [<b style="color:green">GET</b>] Get field on a Checklist
- - [<b style="color:blue">PUT</b>] Update field on a Checklist
- - [<b style="color:green">GET</b>] Get the Board the Checklist is on
- - [<b style="color:green">GET</b>] Get the Card a Checklist is on
- - [<b style="color:green">GET</b>] Get Checkitems on a Checklist
- - [<b style="color:SandyBrown">POST</b>] Create Checkitem on Checklist
- - [<b style="color:green">GET</b>] Get a Checkitem on a Checklist
- - [<b style="color:red">DEL</b>] Delete Checkitem from Checklist
- **CustomFields**
- - [<b style="color:SandyBrown">POST</b>] Create a new Custom Field on a Board
- - [<b style="color:green">GET</b>] Get a Custom Field
- - [<b style="color:blue">PUT</b>] Update a Custom Field definition
- - [<b style="color:red">DEL</b>] Delete a Custom Field definition
- - [<b style="color:green">GET</b>] Get Options of Custom Field drop down
- - [<b style="color:SandyBrown">POST</b>] Add Option to Custom Field dropdown
- - [<b style="color:green">GET</b>] Get Option of Custom Field dropdown
- - [<b style="color:red">DEL</b>] Delete Option of Custom Field dropdown
- **Emoji**
- - [<b style="color:green">GET</b>] List available Emoji
- **Enterprises**
- - [<b style="color:green">GET</b>] Get an Enterprise
- - [<b style="color:green">GET</b>] Get auditlog data for an Enterprise
- - [<b style="color:green">GET</b>] Get Enterprise admin Members
- - [<b style="color:green">GET</b>] Get signupUrl for Enterprise
- - [<b style="color:green">GET</b>] Get Users of an Enterprise
- - [<b style="color:green">GET</b>] Get Members of Enterprise
- - [<b style="color:green">GET</b>] Get a Member of Enterprise
- - [<b style="color:green">GET</b>] Get whether an organization can be transferred to an enterprise.
- - [<b style="color:green">GET</b>] Get a bulk list of organizations that can be transferred to an enterprise.
- - [<b style="color:blue">PUT</b>] Decline enterpriseJoinRequests from one organization or a bulk list of organizations.
- - [<b style="color:green">GET</b>] Get ClaimableOrganizations of an Enterprise
- - [<b style="color:green">GET</b>] Get PendingOrganizations of an Enterprise
- - [<b style="color:SandyBrown">POST</b>] Create an auth Token for an Enterprise.
- - [<b style="color:blue">PUT</b>] Transfer an Organization to an Enterprise.
- - [<b style="color:blue">PUT</b>] Update a Member's licensed status
- - [<b style="color:blue">PUT</b>] Deactivate a Member of an Enterprise.
- - [<b style="color:blue">PUT</b>] Update Member to be admin of Enterprise
- - [<b style="color:red">DEL</b>] Remove a Member as admin from Enterprise.
- - [<b style="color:red">DEL</b>] Delete an Organization from an Enterprise.
- - [<b style="color:green">GET</b>] Bulk accept a set of organizations to an Enterprise.
- **Labels**
- - [<b style="color:green">GET</b>] Get a Label
- - [<b style="color:blue">PUT</b>] Update a Label
- - [<b style="color:red">DEL</b>] Delete a Label
- - [<b style="color:blue">PUT</b>] Update a field on a label
- - [<b style="color:SandyBrown">POST</b>] Create a Label
- **Lists**
- - [<b style="color:green">GET</b>] Get a List
- - [<b style="color:blue">PUT</b>] Update a List
- - [<b style="color:SandyBrown">POST</b>] Create a new List
- - [<b style="color:SandyBrown">POST</b>] Archive all Cards in List
- - [<b style="color:SandyBrown">POST</b>] Move all Cards in List
- - [<b style="color:blue">PUT</b>] Archive or unarchive a list
- - [<b style="color:blue">PUT</b>] Move List to Board
- - [<b style="color:blue">PUT</b>] Update a field on a List
- - [<b style="color:green">GET</b>] Get Actions for a List
- - [<b style="color:green">GET</b>] Get the Board a List is on
- - [<b style="color:green">GET</b>] Get Cards in a List
- **Members**
- - [<b style="color:green">GET</b>] Get a Member
- - [<b style="color:blue">PUT</b>] Update a Member
- - [<b style="color:green">GET</b>] Get a field on a Member
- - [<b style="color:green">GET</b>] Get a Member's Actions
- - [<b style="color:green">GET</b>] Get Member's custom Board backgrounds
- - [<b style="color:SandyBrown">POST</b>] Upload new boardBackground for Member
- - [<b style="color:green">GET</b>] Get a boardBackground of a Member
- - [<b style="color:blue">PUT</b>] Update a Member's custom Board background
- - [<b style="color:red">DEL</b>] Delete a Member's custom Board background
- - [<b style="color:green">GET</b>] Get a Member's boardStars
- - [<b style="color:SandyBrown">POST</b>] Create Star for Board
- - [<b style="color:green">GET</b>] Get a boardStar of Member
- - [<b style="color:blue">PUT</b>] Update the position of a boardStar of Member
- - [<b style="color:red">DEL</b>] Delete Star for Board
- - [<b style="color:green">GET</b>] Get Boards that Member belongs to
- - [<b style="color:green">GET</b>] Get Boards the Member has been invited to
- - [<b style="color:green">GET</b>] Get Cards the Member is on
- - [<b style="color:green">GET</b>] Get a Member's custom Board Backgrounds
- - [<b style="color:SandyBrown">POST</b>] Create a new custom Board Background
- - [<b style="color:green">GET</b>] Get custom Board Background of Member
- - [<b style="color:blue">PUT</b>] Update custom Board Background of Member
- - [<b style="color:red">DEL</b>] Delete custom Board Background of Member
- - [<b style="color:green">GET</b>] Get a Member's customEmojis
- - [<b style="color:SandyBrown">POST</b>] Create custom Emoji for Member
- - [<b style="color:green">GET</b>] Get a Member's custom Emoji
- - [<b style="color:green">GET</b>] Get Member's custom Stickers
- - [<b style="color:SandyBrown">POST</b>] Create custom Sticker for Member
- - [<b style="color:green">GET</b>] Get a Member's custom Sticker
- - [<b style="color:red">DEL</b>] Delete a Member's custom Sticker
- - [<b style="color:green">GET</b>] Get Member's Notifications
- - [<b style="color:green">GET</b>] Get Member's Organizations
- - [<b style="color:green">GET</b>] Get Organizations a Member has been invited to
- - [<b style="color:green">GET</b>] Get Member's saved searched
- - [<b style="color:SandyBrown">POST</b>] Create saved Search for Member
- - [<b style="color:green">GET</b>] Get a saved search
- - [<b style="color:blue">PUT</b>] Update a saved search
- - [<b style="color:red">DEL</b>] Delete a saved search
- - [<b style="color:green">GET</b>] Get Member's Tokens
- - [<b style="color:SandyBrown">POST</b>] Create Avatar for Member
- - [<b style="color:SandyBrown">POST</b>] Dismiss a message for Member
- - [<b style="color:green">GET</b>] Get a Member's notification channel settings
- - [<b style="color:blue">PUT</b>] Update blocked notification keys of Member on a channel
- - [<b style="color:green">GET</b>] Get blocked notification keys of Member on this channel
- - [<b style="color:blue">PUT</b>] Update blocked notification keys of Member on a channel
- - [<b style="color:blue">PUT</b>] Update blocked notification keys of Member on a channe
- **Notifications**
- - [<b style="color:green">GET</b>] Get a Notification
- - [<b style="color:blue">PUT</b>] Update a Notification's read status
- - [<b style="color:green">GET</b>] Get a field of a Notification
- - [<b style="color:SandyBrown">POST</b>] Mark all Notifications as read
- - [<b style="color:blue">PUT</b>] Update Notification's read status
- - [<b style="color:green">GET</b>] Get the Board a Notification is on
- - [<b style="color:green">GET</b>] Get the Card a Notification is on
- - [<b style="color:green">GET</b>] Get the List a Notification is on
- - [<b style="color:green">GET</b>] Get the Member a Notification is about (not the creator)
- - [<b style="color:green">GET</b>] Get the Member who created the Notification
- - [<b style="color:green">GET</b>] Get a Notification's associated Organization
- **Organizations**
- - [<b style="color:SandyBrown">POST</b>] Create a new Organization
- - [<b style="color:green">GET</b>] Get an Organization
- - [<b style="color:blue">PUT</b>] Update an Organization
- - [<b style="color:red">DEL</b>] Delete an Organization
- - [<b style="color:green">GET</b>] Get field on Organization
- - [<b style="color:green">GET</b>] Get Actions for Organization
- - [<b style="color:green">GET</b>] Get Boards in an Organization
- - [<b style="color:green">GET</b>] Retrieve Organization's Exports
- - [<b style="color:SandyBrown">POST</b>] Create Export for Organizations
- - [<b style="color:green">GET</b>] Get the Members of an Organization
- - [<b style="color:blue">PUT</b>] Update an Organization's Members
- - [<b style="color:green">GET</b>] Get Memberships of an Organization
- - [<b style="color:green">GET</b>] Get a Membership of an Organization
- - [<b style="color:green">GET</b>] Get the pluginData Scoped to Organization
- - [<b style="color:green">GET</b>] Get Tags of an Organization
- - [<b style="color:SandyBrown">POST</b>] Create a Tag in Organization
- - [<b style="color:blue">PUT</b>] Update a Member of an Organization
- - [<b style="color:red">DEL</b>] Remove a Member from an Organization
- - [<b style="color:blue">PUT</b>] Deactivate or reactivate a member of an Organization
- - [<b style="color:SandyBrown">POST</b>] Update logo for an Organization
- - [<b style="color:red">DEL</b>] Delete Logo for Organization
- - [<b style="color:red">DEL</b>] Remove a Member from an Organization and all Organization Boards
- - [<b style="color:red">DEL</b>] Remove the associated Google Apps domain from a Workspace
- - [<b style="color:red">DEL</b>] Delete the email domain restriction on who can be invited to the Workspace
- - [<b style="color:red">DEL</b>] Delete an Organization's Tag
- - [<b style="color:green">GET</b>] Get Organizations new billable guests
- **Plugins**
- - [<b style="color:green">GET</b>] Get a Plugin
- - [<b style="color:blue">PUT</b>] Update a Plugin
- - [<b style="color:SandyBrown">POST</b>] Create a Listing for Plugin
- - [<b style="color:green">GET</b>] Get Plugin's Member privacy compliance
- - [<b style="color:blue">PUT</b>] Updating Plugin's Listing
- **Search**
- - [<b style="color:green">GET</b>] Search Trello
- - [<b style="color:green">GET</b>] Search for Members
- **Tokens**
- - [<b style="color:green">GET</b>] Get a Token
- - [<b style="color:green">GET</b>] Get Token's Member
- - [<b style="color:green">GET</b>] Get Webhooks for Token
- - [<b style="color:SandyBrown">POST</b>] Create Webhooks for Token
- - [<b style="color:green">GET</b>] Get a Webhook belonging to a Token
- - [<b style="color:blue">PUT</b>] Update a Webhook created by Token
- - [<b style="color:red">DEL</b>] Delete a Webhook created by Token
- - [<b style="color:red">DEL</b>] Delete a Token
- **Webhooks**
- - [<b style="color:SandyBrown">POST</b>] Create a Webhook
- - [<b style="color:green">GET</b>] Get a Webhook
- - [<b style="color:blue">PUT</b>] Update a Webhook
- - [<b style="color:red">DEL</b>] Delete a Webhook
- - [<b style="color:green">GET</b>] Get a field on a Webhook

<hr>

#### Image:
![alt text](image.png)

<hr>

#### Credits:
This project made in Postman was based on the following course:
- https://www.udemy.com/course/postman-the-complete-guide/

<hr>

#### Documentations:

Get Started Building On Trello
- https://developer.atlassian.com/cloud/trello/

Power-Up Admin Portal (Managing Power-Up)
- https://developer.atlassian.com/cloud/trello/guides/power-ups/managing-power-ups/

Generating an API key
- https://developer.atlassian.com/cloud/trello/guides/power-ups/managing-power-ups/#generating-an-api-key

The API Documentation is based on the following link:
- https://developer.atlassian.com/cloud/trello/rest/api-group-actions/

About Trello and API Keys:
- https://developer.atlassian.com/cloud/trello/guides/rest-api/api-introduction/
- https://trello.com/app-key

<hr>

#### Observation:
<p style="text-align: justify;">The tests with <b>Postman</b> carried out on the Trello application were only carried out on some endpoints. The objective is not to exhaustively test the Trello application but to serve as an example of running API tests in <b>Postman</b>.</p>
<p style="text-align: justify;">Additionally, there may be more tests to be created and executed in <b>Postman</b> if relevant.</p>

<hr>

This project was created by **Alexandre Rodrigues da Silva**.