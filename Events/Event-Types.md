# Event Types

## Event Object Common Properties
The event objects have the same structure.

| Attribute Name | Description |
| --- | --- |
| Id | Unique identifier for the event. |
| Action | The action that was performed. |
| Type | The type of event. |
| Actor | The user that triggered the event. |
| Actor.Id | The unique identifier for the actor. |
| Actor.Login | The username of the actor. |
| Actor.DisplayName | The display name of the actor. |
| Actor.AvatarUrl | The URL of the actor's profile image. |
| Actor.Url | The REST API URL used to retrieve teh user object, which includes additional user information. |
| Actor.Type | Type of actor. |
| Url | The REST API URL for fetching the event. |
| Event | Identifies the actual type of event that occurred, |
| Payload | The event payload object is unique to the event types. |
| Public | Whether the event is visible to all users. |
| CreatedAt | The date and time when the event was triggered. It is formatted according to ISO 8601. |
