**Name**  
Respond to on-hold notice/status (as owner)

----

**Actor**  
Question author

----

**Subject area**  
Question that has received a hold vote.  
Inbound navigation could be from a notification or from normal browsing.

----

**Preconditions**  
Somebody has voted to put the question on hold (see hold.md).

----

**Termination outcome**  
Author has responded to the suggestion and page has been updated.

----

**Basic flow**

- User sees a notice on the question about the issue.  Message links to appropriate help and shows the comments (if any) left by voters.  These comments are with the notice, are not regular comments, and are not signed.  Notice includes controls for "I will edit" and "withdraw question".

- If user chooses edit: 
    - It's the usual edit interface but make sure the hold notice is visible on the page too (so the user can consult it).
    - If the user is TL2, when user submits the edit, the hold notice is removed (for all viewers) but logged in the history.  (But see next item.)
    - If the user is TL0 or TL1, or the user has previously edited in response to a hold notice and the question got another hold vote after the edit, the hold notice remains and the user sees a message along the lines of "thanks for your edit; the community will review to see if that addresses the issue" (not those words).

- If user chooses withdraw:
    - Question is put on hold (no more answers) and "[withdrawn]" is added to end of title.


----

**Notes**

Yes, any edit by the OP, if not a new or inexperienced user, counters the hold.  This could be abused and maybe we'll need to impose an "amount of diff" limit later, but let's start with this and assume that most edits are well-intentioned.  People can vote again or flag for moderator attention if a real problem is brewing.  Also, the OP can remove hold status via an edit only once; if the first edit wasn't good (the question got another hold vote), further edits can't change the question's status.

Should withdrawn questions be removed from the default question list?  
Should answerers be notified of the change in state?





