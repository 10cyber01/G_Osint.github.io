[Passer à la version française 🇫🇷](index.md)


# [SOCMINT] Profiling & Social Engineering: How I tracked down an "anonymous" Instagram account using LinkedIn nostalgia

## The Challenge
The other day, I challenged someone who was absolutely convinced their Instagram account was completely untraceable. Their logic? No last name on the profile, no profile picture, and a totally random username.

Yet, it took me **well under 30 minutes** to find it. And no, it didn't require any complex hacking tools. I simply combined **SOCMINT** (Social Media Intelligence) with a bit of psychology, aka social engineering.

---

## Step 1: Hit a wall with direct search
At first, I tried the classic approach: searching directly for their first and last name on Insta, or obvious variations (like `Firstname.Lastname`).

Unsurprisingly, that led nowhere. The boundary between their public and private life was well-maintained. When pure technical methods fail, that's your cue to shift gears, change your mindset, and look into the target's psychology.

---

## Step 2: The LinkedIn reflex and the nostalgia card
So, I headed over to LinkedIn. It’s the ultimate goldmine for OSINT because everyone willingly lays out their entire background without a second thought. Plus, the math is simple: with over 30 million users in France—more than half the working population—the odds of my target being there were sky-high.

While analyzing their profile, I intentionally ignored their recent jobs and skipped straight to their education history. In cybersecurity, we constantly say that humans are the primary vulnerability. So, I played a highly effective psychological card: nostalgia. When people look back fondly on their past, they often end up following people or places they used to be connected with—in this case, their old school.

Bingo! Scrolling all the way to the bottom of the page, I hit the exact key piece of evidence I needed: the name of their primary school.

---

## Step 3: The funnel technique
Armed with this intel, I went back to Instagram to narrow things down:

1. **Find the school:** I looked up the official account of their former primary school (which happened to have an active page).
2. **Scrape the followers:** Let's be real, what adult still follows their old primary school? Very few, except for the nostalgic ones. So, I went through the school's follower list.
3. **The cross-reference:** Amidst the profiles, one suspicious account caught my eye: no photo, no name. However, the username started exactly with the **beginning of their first name**.

By cross-referencing the city, the school, and that specific string of letters, there was no room left for doubt. The account was identified.

---

## 🧠 The Social Engineering Connection
People often think social engineering is all about manipulating someone over the phone or via email. In reality, the bulk of the work happens during this passive reconnaissance phase.

For an attacker, finding a private Instagram account is a goldmine:
* **Targeted Spear-Phishing:** Knowing which school the target attended allows a hacker to create a spoofed account of a former classmate from back then to strike up a conversation, build trust, and eventually drop a malicious link.
* **Password hints:** Even on a private account, a bio or featured highlights can give away hobbies, pet names, or key milestones. These are exactly the types of information people reuse for their passwords or security questions.

---

## Conclusion
The takeaway from this quick investigation is that technical measures aren't everything: security relies heavily on the human factor. You can hide your name and blur your face, but your security posture will still collapse if you leave breadcrumbs about your interests or your past.

We can try to hide behind all the aliases and technical configurations in the world, but at the end of the day, our memories will always give us away. In OSINT, you quickly realize that someone's nostalgia isn't a private garden... it's just their biggest security flaw.
