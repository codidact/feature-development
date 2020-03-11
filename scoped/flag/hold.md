**Name**  
Suggest hold (first vote)

----

**Actor**  
Signed-in user with trust level to vote to close/reopen (TL3)

----

**Subject area**  
Question

----

**Preconditions**  
None

----

**Termination outcome**  
Page updated with guidance for OP.  
Notification sent to OP.  
Page updated (for user) to indicate that a vote has been cast.

----

**Basic flow**

- User chooses "can't be answered" control.  (That is not a literal text string; we need to think how to convey this.)

- User is presented with choices and guidance for how to use them:
  - Needs your attention + textbox (required)
  - Off topic + textbox (optional)

- User chooses an option, writes an explanation in the textbox, and submits.

- Page updates:
  - For the user: "can't answer" control changes to indicate you've already done this.
  - For the OP: a message is added (above? below?) the question with a carefully-written, friendly message (TBD) about the issue, along with the user-submitted comment and an "edit now" link/button/prompt.  (Need to do something here for the off-topic case.)
  - For the public: comment is added: "The community has requested more information" + comment or "This question might not be on-topic here" + comment.  (Need to massage that text, but that general idea.)

- Author receives a notification that the question needs more input or is off topic.

- Hold-vote tally is started.

----

**Notes**

Yes, "duplicate" is intentionally not part of a "close" flow.  See duplicate.md.

Reference: https://forum.codidact.org/t/question-closure-in-mvp/106/32?u=cellio

For front-end designers: assume that friendly message to the OP is 2-3 sentences, not just a one-liner, plus the comment(s).

Maybe the "needs attention" and "off topic" reasons should expand to offer some baked-in specific cases.  This needs more thought.

Anonymous close reasons are an experiment, to be evaluated after some use.
