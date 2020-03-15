**Name**  
Vote on a post

----

**Actor**  
Any signed-in user  
(reminder: TL0 to upvote answers to own question, TL1 to upvote, TL2 to downvote)

----

**Subject area**  
Individual question page.

----

**Preconditions**  
None (privilege and already-voted cases are addressed in the flow section).

----

**Termination outcome**  
Vote is recorded and shown on the page.

----

**Basic flow**

User has privilege to vote:

- User sees post along with current upvote/downvote counts.  The upvote and downvote controls do not show a current vote (user has not already voted).
- User clicks on upvote or downvote control.
- Vote count is updated and vote control is changed to indicate the user's vote.  
    - If the vote is on an answer and this vote changes the answer's ranking, the page does *not* update to move the answer.  (That would be jarring to the user currently on the page.)

Other cases:

- The user does not have the trust level to cast the vote: the control does not accept the vote, the score does not change, and the user receives a message about not being able to vote yet, with help link.

- The user has already voted: 
    - Clicking on the *same* vote control revokes the vote.  Score and control state are updated.
    - Clicking on the *other* vote control revokes the prior vote, casts the new one, and updates score and control state.

----

**Notes**

We have not specified any vote-locking.  This use case assumes you can change your vote at any time.

This use case does not include guidance for a user casting a downvote for the first time (e.g. a suggestion to leave a comment).  Should it?


