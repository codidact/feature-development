**Name**  
Ask question when rate-limited

----

**Actor**  
Signed-in user

----

**Subject area**  
Any page in a category that accepts questions (Q&A, Meta, others defined by the site).

----

**Preconditions**  
User is TL0 or TL1.

----

**Termination outcome**  
User is on original page.

----

**Basic flow**

- User clicks on "ask question" button.

- If user has reached limit for questions/day:
    - User sees notice like "You've already asked N questions today and can ask a new question again in N hours.  In the meantime, please address any responses you've received on your other questions (link).  For more information on rate limits see (help link). (friendly closing)"
    - User clicks on one of those links for more info, or dismisses the notice.

- If user has not reached limit for questions/day but has reached the time-based rate limit:
    - User sees notice like "Please wait (N minutes) after your last question before asking another.  In the meantime (...).  For more info (...). (friendly closing)"
    - User clicks on one of those links for more info, or dismisses the notice.


----

**Notes**

Intercept the attempted question as early as possible -- when the user starts, not when the user has already written a question and tries to submit it.  Not only is this less frustrating for the user, but it means we don't have to implement a "save draft for later" flow.

For the back end: what's the earliest point where we could catch this if the user were to bypass the "ask" button and use a direct URL?  How do we block that? 

