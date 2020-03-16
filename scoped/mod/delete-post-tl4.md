**Name**  
Delete post (TL4)

----

**Actor**  
Signed-in user with TL4 (deputy)

----

**Subject area**  
Any post (see preconditions)

----

**Preconditions**  
Post must be eligible for deletion at this level; one of:
  - answers below some score threshold
  - questions that have been on hold for more than N days
  - posts with spam or rude flags


----

**Termination outcome**  
Post is deleted (see details below).


----

**Basic flow**  

User sees a post and (if there are flags) an indicator of outstanding flags.  Outstanding flags work as for the lock case.

User decides post should be deleted.  User chooses "moderate" control and, from there, chooses "delete".  (If the post is not eligible for deletion, this option isn't selectable and there's a short message with the option explaining why not.)

User chooses "apply" (or whatever we call it) to complete the deletion.  The following things happen:

- Post is not visible to those below this TL (except the author can always see).
- The post is rendered in a way that indicates deleted status, for those who casn see deleted posts.
- A notice is added to the post saying who deleted it and when.
- Deletion is added to post history.


----

**Notes**  

We haven't specified community deletions yet, so I put the control on the "moderate" menu.  If we do community delete votes later we should move this control for consistency.

Should deletions by TL4 users emit flags to TL5 (elected mods)?

Should outstanding spam or rude flags be auto-resolved?


