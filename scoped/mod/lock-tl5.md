**Name**  
Lock post (TL5, moderator)

----

**Actor**  
Signed-in user with TL5 (elected moderator)

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
Any pending lock flags from TL4 users are resolved.  


----

**Basic flow**

User sees a post, either locked or normal, and (if there are flags) an indicator of outstanding flags.  (Moderators see the flags indicator on all posts.)

User selects the "outstanding flags" indicator and sees an in-page list of the flags.  If the post was locked by a TL4 user, this includes the auto-flag for the lock.  (The mod flags interface is described more in mod/see-flags.md.)

User reviews everything and decides to lock the post.  As at TL4, user chooses "moderate" control and, from there, "lock". If post is already locked, option is "modify lock" (see unlock.md for details).

The interface for specifying a lock is the same as at TL4 except that there is a new duration, "permanent".

User chooses type(s) and duration.  Outcomes are the same as at TL4 except no auto-flag is raised and any pending lock flags are resolved.


**Alternate flows**  

- User decides to delete the post instead.  See the delete use case.
- User decides a locked post should not be locked.  See the unlock use case.


----

**Notes**  

The flag interface is basically "Monica's Flag ToC" userscript: https://github.com/Shog9/flagtools.

Should there be any new lock types for TL5? 



