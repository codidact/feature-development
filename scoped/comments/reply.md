**Name**
Reply to Comment

----

**Actor**
Signed-in user

**Note:** anonymous user either doesn't see the "reply" affordance or is prompted to log in after clicking it (like we do for posts).

----

**Subject area**
Any post with at least one comment thread.

----

**Preconditions**
None (this use case addresses users with and without necessary trust level).

----

**Termination outcome**

Trusted user: comment is posted.  
Untrusted user: message displayed about not being able to comment yet.

Either way, user is on the same page, and if a new comment was posted, thread is expanded such that new comment is visible.

----

**Basic flow**

Case 1: reply in thread (user is trusted)

- User has previously expanded a thread.
- User selects "reply" control on some comment in that thread.
- Textbox appears (consider help text or pop-up for new users).
- User types comment.  As the length limit approaches, a "countdown" appears so user knows when a comment is getting too long.  (Example: Twitter.)
- User selects "add" control.  If comment is too long, show message saying so and leave the user in the edit state.  Otherwise, post comment and display in place.  **Note:** this might insert the new comment somewhere other than the end, if reply chains within a thread have forked.  Or do we want comments to be posted in strict time order within threads (ignore sub-threads becuase we're not formatting them)?

Case 2: reply to top-level comment where thread is collapsed (user is trusted)
- User selects "reply".
- Thread is expanded and message is shown to the effect of "please read the other replies first in case your point has already been made".
- Textbox appears at end of thread.
- Rest as for case 1.

Case 3: user is not trusted
- User selects "reply".
- A message appears about not having the comment privilege yet, with a link to the help on trust levels.

----

**Notes**

We need to craft the messages/guidance for the user to both convey information and be friendly.  Text in this use case is the gist, not the literal messages.



