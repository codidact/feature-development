**Name**  
Unlock post (TL5, moderator)

----

**Actor**  
Signed-in user with TL5 (elected moderator)

----

**Subject area**  
Any locked post

----

**Preconditions**  
None

----

**Termination outcome**  
Page updated to remove lock.  
Change logged in post history, with attribution.  
Any pending lock flags from TL4 users are declined.


----

**Basic flow**

User sees a post that is locked and disagrees.

User chooses "moderate" control and, from there, "modify lock".

User sees the same lock dialogue as for locking a post; locks currently in place have their checkboxes checked.

User unchecks lock(s) to be removed.  (User could also choose other lock types here to change the lock, but that's not this use case.)

User chooses "change lock" or "done" or whatever we call that control.  The following things happen:

- The post is unlocked in the specified way(s).
- The notice is removed.  (If only some locks were removed, the notice is adjusted instead.)
- The unlocking is added to the post history (type and who unlocked).


----

**Notes**  

The flag interface is basically "Monica's Flag ToC" userscript: https://github.com/Shog9/flagtools.

Should there be any new lock types for TL5? 

This use case doesn't try to automatically handle any pending lock flags.  The user ought to explain the outcome to the flagger anyway.



