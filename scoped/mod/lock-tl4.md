**Name**  
Lock post (TL4)

----

**Actor**  
Signed-in user with TL4 (deputy)

----

**Subject area**  
Any post

----

**Preconditions**  
None

----

**Termination outcome**  
Page updated with lock changes (depending on lock type).  
Change logged in post history, with attribution.  
Flag is automatically raised (if you're willing to lock you should be willing to flag).


----

**Basic flow**

User sees a post and (if there are flags) an indicator of outstanding flags.

User selects the "outstanding flags" indicator and sees a summary of the types and numbers of flags raised, excluding "other" flags and their text but including comment flags as one group.  (Example: "3 spam, 2 rude, 1 off-topic, 12 comment flags".)

User reviews post and/or comments and decides there's a problem.  User chooses "moderate" control and, from there, chooses "lock".

User sees an in-page dialogue for lock type (checkboxes) and duration.  Each lock type is accompanied by a short description of what it does.  Duration is 1, 2, or 3 days.  Types are:
  - no new comments
  - content lock (no new edits)

User chooses one or more types and a duration.  The following things happen:

  - The post is locked in the specified way(s).
  - A notice about the lock is added, focusing on what is blocked (for example, "this post is not accepting comments at this time").
  - For users at TL4 or higher only, the notice includes when the lock will expire.
  - The lock is added to the post history (type and who locked, not duration).
  - A flag about the lock is automatically raised for mod (TL5) attention.
  - If user applied a comment lock, a notice appears saying something like "remember to flag any inappropriate comments".


----

**Notes**  

When/if we add auto-flags, these would be included (for example, "N edits in 24 hours", "rollback war", "N edits by one person".)

Any other lock types we want to make available to users at this level?  (TL4 is one level below elected moderators.)

Max duration is 3 days because that should allow enough time for moderator review, but do we need to allow longer?  Do we want to allow users at this level to perma-lock posts (subject to unlocking by others)?

Historical locks are excluded here.

Locks do not block voting.

Locks do not block new answers.  If you think a question should be closed, vote for that.
