**Name**  
Edit a question that is on hold

----

**Actor**  
Any user.

----

**Subject area**  
Question that is currently on hold.

----

**Preconditions**  
None

----

**Termination outcome**  


----

**Basic flow**

- User sees a question that is on hold and thinks it can be fixed.
- User chooses "edit" control as for any other post.
- If user is the author:
    - Proceed as in hold-OP.md.

- If user is TL3 (can cast reopen votes):
    - Usual edit interface, but with a notice at the top to the effect that this question is currently on hold, your edit will nominate it for reopening, and please take care to address the issues that were raised.  (We'll wordsmith that.)
    - User submits edit.
    - System records an "open" vote.
    - If open votes now equal hold votes, reopen as specified in hold-others.md.

- If user is below TL3:
    - Treat as ordinary edit; does not affect hold status.
    - Edit reviewers are shown a notice to the effect that this question has active hold votes and if the edit addresses the problem, cast an open vote.  (This will be further specified in the review-edit use case.)




