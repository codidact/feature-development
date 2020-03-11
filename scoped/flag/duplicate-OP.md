**Name**  
Respond to duplicate suggestion (as owner)

----

**Actor**  
Question author

----

**Subject area**  
Question that has a duplicate suggestion.  
Inbound navigation could be from a notification or from normal browsing.

----

**Preconditions**  
Somebody has raised a duplicate suggestion (see duplicate.md).

----

**Termination outcome**  
Author has responded to the suggestion and page has been updated.

----

**Basic flow**

- User sees a notice on the question about a possible duplicate.  Message links to help about duplicates and, for each duplicate suggestion, shows a link to the other question and any comments left by people who voted for that duplicate.  These comments are with the notice, are not regular comments, and are not signed.

- User clicks on a duplicate link, reviews the question, and makea s decision.  (Might repeat for other suggestions, if more than one.)

- User returns to the original question page.

- If user agrees it's a dupe:
    - User clicks on the "agree" control.
    - Notice is replaced with a notice saying that this question has been marked as a duplicate and the author has accepted this (need to word that cleanly).  Links for all suggested dupes are included.  The flag comments previously shown to the author are removed from the notice.  The corresponding comments (in the comment section) are deleted.
    - Question is closed -- no new answers, "(duplicate)" added to end of title.  (Note that the word "closed" does not appear in the UI here.)

- If user disagrees:
    - User clicks on the "disagree" control.
    - A notice appears on the page recommending the user edit to explain why it's not a dupe.  The notice includes an edit link.

    - If user clicks the edit link:
        - It's the usual edit interface, except that "My question is not a duplicate of (link) because" has been inserted at the bottom and (ideally) the cursor is positioned there.  If there's more than one dupe suggestion, do this for each and position cursor at the first.
        - If the user is TL2, when user submits the edit, the duplicate notice is removed from the question (for all viewers) but logged in the history.
        - If the user is TL0 or TL1, the duplicate notice remains and the user sees a message along the lines of "thanks for your edit; the community will review to see if it's not a dupe any more" (not those words).

    - If user does not edit: "possible duplicate" notice remains for all users.  The edit notice remains for the author (so the author can come back and edit later).

