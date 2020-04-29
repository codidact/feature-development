**Name**  
View individual question

----

**Actor**  
Any user

----

**Subject area**  
Any question page (in any category), which a user reached from a question list, from a link in a profile, from a direct link, or maybe other sources.

----

**Preconditions**  
None

----

**Termination outcome**  
No changes from this use case specifically

----

**Basic flow**

User is on a page for an individual question.

User sees the question title, question body, tags, user card for author, link to edit history with timestamp of last edit.  If question has notices (duplicate suggestions, hold, etc) those are shown too.  Page also shows answers, sorted by score.

Things user can do from here:

- User chooses "summarize answers" control and page updates to show a summary view below the question and above the first answer.  This view is like the answers part of the summary shown for expand-question.md -- for each answer:
  - up/down votes
  - author
  - last-modified date
  - opening couple lines

- After expanding the answer summary, user selects one of the answers to jump to it.

- User scrolls through the page reading answers.

- If user is TL4 or higher, user sees deleted answers.  Deleted answers are shown after all undeleted ones and, within that, in score order.  Deleted answers have some visual difference to indicate their status.

- User might take actions on the page covered in other use cases (vote, flag, edit, comment, add answer).



