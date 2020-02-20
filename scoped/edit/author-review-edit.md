**Name**
Review edit (author, after notification)

----

**Actor**
Author of post that has a pending edit suggestion.

----

**Subject area**
Any

----

**Preconditions**
Author has received a notification about the edit.

----

**Termination outcome**
Author has approved or rejected the edit and is on the page with the post that had the edit suggestion.  The post history contains the edit if applied.

Not MVP: post history shows rejected edits in some way (link to suggested edit and rejection reason?).

----

**Basic flow**

- Author clicks on the notification of the suggested edit.
- Author is shown a diff (exact form TBD), the same view that is shown in post history.  This diff includes the edit reason and the editor's usercard.  There are two controls, "accept" and "reject".
- Author chooses:
  - Accept: edit is applied, "edit accepted" event is logged (counts toward trust levels and might be shown on user profile).
  - Reject: textbox appears and author is prompted to explain the rejection (and told it will be public).  Author types a reason and submits.  "Edit rejected" event is logged.  TBD: notification to editor?
- Page is refreshed to show the final state of the post.


