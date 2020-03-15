**Name**  
Respond to OP edit after duplicate suggestion (not as owner)

----

**Actor**  
User with TL3 (vote to close) who is not the author.

----

**Subject area**  
Question that has received a duplicate vote.  

----

**Preconditions**  
Somebody has suggested that the question is a duplicate (see duplicate.md), and a low-trust-level author has edited in response (see duplicate-OP.md).

----

**Termination outcome**  
Page updated to either confirm or remove the duplicate notice.  
If the user took action, it counts as a review.  

----

**Basic flow**

- User sees a notice on a question: "Possible duplicate of (link)", with comment text if provided, plus that the author has edited, and "Does the edit fix the problem? (Y/N)".

- User reads the current form of the question and looks at the suggested dupe(s).

- If user agrees with the author that this is no longer a duplicate:
  - User clicks on "yes"/"fixed"/whatever our label is.
  - The duplicate notice is removed from the question (for all viewers) but logged in the history.
  - Author receives a notification of the status change.

- If user disagrees with the author and thinks it is still a duplicate:
  - User clicks on "no"/"dupe"/whatever our label is.
  - User is prompted for an optional comment to explain what's still wrong.
  - The duplicate notice changes from "possible dupe" language to "has been marked as a dupe by the community" language.  The comment (if supplied) is shown, anonymized, as for on-hold votes.  The notice includes a link to help topic on duplicates.
  - The question no longer accepts answers and "[duplicate]" is appended to the title.
  - Author receives a notification of the status change.


