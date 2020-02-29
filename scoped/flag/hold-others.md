**Name**
Respond to on-hold notice/status (not as owner)

----

**Actor**
User with TL3 (vote to close) who is not the author.

----

**Subject area**
Question that has received a hold vote.  

----

**Preconditions**
Somebody has voted to put the question on hold (see hold.md).

----

**Termination outcome**
Page updated (for user) to indicate that a vote has been cast.  
If vote threshold reached, question is put on hold (see below).

----

**Basic flow**

- User sees hold-votes notice on the question, along with "can't be answered" control (as usual) and "disagree" control.
- If user chooses "can't be answered": same flow as hold.md.
- If user chooses "disagree" control, "open" vote is recorded.

- If question now has enough votes to put on hold:
    - Question is put on hold (no more answers) and "[on hold]" is added to end of title.
    - Notice is updated to say that this question was put on hold by the community because (insert reasons that were already shown, as before) and is awaiting an edit.
    - Notification of the state change is sent to all answerers.

- If number of open votes now equals number of hold votes:
  - Hold notice is removed (for all viewers) but logged in the history.
  - Close/open votes are kept (and could be relevant if future close votes are cast).


----

**Notes**

We're making a distinction in the annotations in the title.  "Withdrawn" means the OP agreed to (and participated in) the closure.  "On hold" means the community did it.  I'm open to other vocabulary to (concisely) convey this.
