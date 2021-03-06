**Name**  
Create answer

----

**Actor**  
Signed-in user

----

**Subject area**  
Any open question page

----

**Preconditions**  
User is signed in and permitted to post (not rate-limited).

----

**Termination outcome**  
User is on the starting question page viewing the new answer.

----

**Basic flow**

- User reads the question and (ideally) the other answers, reaching the bottom of the page.

- If the question has a pending duplicate suggestion:
  - Before the "add answer" control, user sees notice like: "This question has been marked as a possible duplicate. Before you answer, please check the other question to see if your answer fits better there."

- If the question has pending hold votes:
  - Before the "add answer" control, User sees notice like "This question might {need more information, not be on-topic}.  Please review the question before answering,"

- User selects the "add answer" control (button?).

- A new page appears showing the question in the top portion and an answer area in the bottom portion, each scrollable.  If the user is TL0 or this is the user's first answer, additional short help appears.

- User reads the help and clicks into the answer textbox.

- User types an answer, referring to the question as needed.

- Optional: user chooses "preview" to see how the post will appear (unless we are doing an automatic in-page preview already, in which case we don't need this).

- User clicks "post" button.

- User is taken to the question page, positioned at the new answer.

----

**Notes**

The goal of the answer interface is to make it easy to see the question while you answer, without having to page past other answers and comments.

Should the help be based on "new answerer"/trust level, or should it always be there until dismissed?

