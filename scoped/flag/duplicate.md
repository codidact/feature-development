**Name**  
Suggest duplicate

----

**Actor**  
Signed-in user 

----

**Subject area**  
Question

----

**Preconditions**  
None

----

**Termination outcome**  
Page updated with guidance for OP.  
Page updated (for flagger) to indicate that a flag/vote has been cast.

----

**Basic flow**

- User chooses "suggest duplicate" control.

- User is presented with two fields to populate: link to the duplicate (required) and comment (optional).  Guidance to user: latter is to explain more about why you think it's a duplicate, because sometimes it's not clear.

- User fills in link and optionally comment and chooses "submit".

- Page updates:
  - For the user: "suggest duplicate" control changes to indicate you've already done this.
  - For the OP: a message is added (above? below?) the question with a carefully-written, friendly message (TBD) about the possible dupe, along with the user-submitted comment, with agree/disagree controls.
  - For the public: comment is added: "Possible duplicate of (link)", with comment text if provided.

- OP and those who have answered the question receive notifications of the possible duplicate.

----

**Notes**

Yes, "duplicate" is intentionally not part of a "close" flow.  Duplicates are different and should be thought of as helping to get to an answer faster, not shutting a question down.

For front-end designers: assume that friendly message to the OP is 2-3 sentences, not just a one-liner, plus the comment(s).

If somebody starts to answer a question with a pending duplicate suggestion, we present a notice about that.  (This will be further described in an "answer" use case.)
