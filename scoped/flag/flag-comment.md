**Name**  
Flag a comment

----

**Actor**  
Signed-in user with trust level to raise flags (TL0 for comments anywhere on own questions, TL1 for all other posts)

----

**Subject area**  
Question page

----

**Preconditions**  
None

----

**Termination outcome**  
Flag submitted (unless prevented) and user sees a "thanks for your flag" message (dismissible).

----

**Basic flow**

User hovers over the "flag" control on a comment.

User selects flag control.
  - If user is TL0 and has reached the limit of pending flags, user sees message about that with link to help and use case ends here.  (TL0 can only flag stuff on the user's own question, so those other pending flags are already on this page -- we're not blocking the user from reporting spam elsewhere on the site.)

  - Otherwise, a list of flag reasons appears with short explanations and a selector: spam, rude, not needed, other (with textbox, required).  The "not needed" case covers both obsolete comments and tangents.

If user has another pending flag on this comment already, that option is grayed out and a "you have already flagged with this reason" message appears with the description.

User chooses a flag reason, fills in the textbox if "other", and chooses "submit".

Flag is recorded.  User receives a dismissible message along the lines of "thanks for the flag" (does not suggest commenting, unlike with post flags).


----

**Notes**

We aren't preventing somebody from raising more than one flag type on a comment.  We are not supporting revoking or switching flags for MVP.

