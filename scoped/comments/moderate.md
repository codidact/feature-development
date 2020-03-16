**Name**  
Moderate comments

----

**Actor**  
User with moderator trust level (TL5).  (This use case is not about raising flags but handling them and/or deleting/locking comments/threads.)

----

**Subject area**  
Post with comment thread(s).

----

**Preconditions**  
Moderator privilege.

----

**Termination outcome**  
Comment state updated as applicable.

----

**Basic flow**

General: comments that have been flagged have a visual indicator of this status.

Option 1: delete comment
- User clicks on "delete" control next to a comment.
  - If comment is a leaf node, delete it.
  - If comment has replies, prompt for "delete replies too?" and either do it or not depending on response.
  - If comment is the start of the thread, prompt for "this will delete the entire thread (ok/cancel)".
- If any deleted comments have outstanding flags, validate them.

Option 2: archive thread (applies only to whole thread)
- User clicks on "archive thread" control next to a thread (can be expanded or collapsed).
- If this is the first time, show message: archived threads are still visible to users at trust level (whatever) but are not shown by default; if you want it to be gone, delete instead (ok/cancel).
- Thread state changed to archived: no new replies, has some visual indicator of status when shown.

Option 3: preserve comment
- User clicks on the "decline" control next to a flagged comment.
- Flag is dismissed and flag indicator for that comment is changed to the "not flagged" state.

