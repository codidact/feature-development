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

Trusted user: comment is posted, notifications possible.  
Untrusted user: message displayed about not being able to comment yet.

Either way, user is on the same page, and if a new comment was posted, thread is expanded such that new comment is visible.

----

**Basic flow**

Case 1: reply in thread (user is trusted)

- User has previously expanded a thread.
- User selects "reply" control on some comment in that thread.
- Textbox appears (consider help text or pop-up for new users).
- If user has 5 or fewer comments left for the day, show a notice with number remaining.
- User types comment.  As the length limit approaches, a "countdown" appears so user knows when a comment is getting too long.  (Example: Twitter.)
- User selects "add" control.  If comment is too long, show message saying so and leave the user in the edit state.  Otherwise, post comment and display in place.  **Note:** this might insert the new comment somewhere other than the end, if reply chains within a thread have forked.  Or do we want comments to be posted in strict time order within threads (ignore sub-threads becuase we're not formatting them)?
- See also "notifications".

Case 2: reply to top-level comment where thread is collapsed (user is trusted)
- User selects "reply".
- Thread is expanded and message is shown to the effect of "please read the other replies first in case your point has already been made".
- Textbox appears at end of thread.
- Rest as for case 1.

Case 3: user is not trusted
- User selects "reply".
- A message appears about not having the comment privilege yet, with a link to the help on trust levels.

Notifications: the following people receive a notification of the new comment:
- person being replied to
- person who started the thread (i.e. poster of the top-level comment) (can be muted)
- post author (can be muted)

For future consideration: *aggregate* notification to question author if post is an answer, so instead of getting pinged on every comment in every thread on every answer, you get a roll-up notification about comments on answer by SoAndSo (one per answer) no more often than, say, once an hour.  This is not MVP!


----

**Notes**

We need to craft the messages/guidance for the user to both convey information and be friendly.  Text in this use case is the gist, not the literal messages.

----

**Related use cases**

comments/mute.md
comments/moderate.md



