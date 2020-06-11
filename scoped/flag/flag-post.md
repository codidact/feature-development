**Name**  
Flag a post

----

**Actor**  
Signed-in user with trust level to raise flags (TL0 for answers on own questions, TL1 for all other posts)

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

User hovers over the "flag" control on a post and sees a tooltip explaining what flags are for.

User selects flag control.
  - If user is TL0 and has reached the limit of pending flags, user sees message about that with link to help and use case ends here.  (TL0 can only flag stuff on the user's own question, so those other pending flags are already on this page -- we're not blocking the user from reporting spam elsewhere on the site.)

  - Otherwise, a list of flag reasons appears with short explanations and a selector.  The reasons vary by context:

    - For an answer: spam, rude, does not answer the question (message should include something to the effect of "don't flag for being wrong"), other (with textbox, required)
    - For a question: spam, rude, needs author's attention, off topic, other (with textbox, required)

If user has another pending flag on this post already, that option is grayed out and a "you have already flagged with this reason" message appears with the description.

User chooses a flag reason, fills in the textbox if "other", and chooses "submit".

Flag is recorded.  User receives a dismissible message along the lines of "thanks for the flag, and if you can suggest ways to improve this post, please leave a comment".


----

**Notes**

Duplicates are not included in question flags; see duplicate.md.

The "needs attention" and "off topic" post flags don't include sub-reasons like for hold votes, but the short explanations should cover those cases.  See hold.

We aren't preventing somebody from raising more than one flag type on a post.  We are not supporting revoking or switching flags for MVP.

Wireframe: https://www.figma.com/file/WBtO6UJ7Mi832OOH0Ny0gV/post-flags?node-id=0%3A1
