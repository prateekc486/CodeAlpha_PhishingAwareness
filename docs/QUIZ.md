# Phishing Awareness Quiz

Ten scenario questions. Questions 1 to 5 are the ones in the slide deck; questions 6 to 10 are extras for self-study. Choose an answer first, then open the answer under each question.

All names and addresses are fictional (`.example` domains cannot belong to a real organisation).

---

### Question 1
An SMS says your account will be blocked in 2 hours unless you update KYC through a link. What do you do?

- A. Click the link quickly so the account stays open
- B. Reply with your account details to confirm
- C. Ignore the link and check with the bank's official app or number

<details>
<summary>Answer</summary>

**C.** Urgency plus a link is a classic smishing pattern. Check with the bank through its official app or number, never through the message.
</details>

---

### Question 2
Which address is the real login page for Example Bank (`examplebank.example`)?

- A. `https://examplebank.example.verify-now.example/login`
- B. `https://login.examplebank.example`
- C. `https://examp1ebank.example/login`

<details>
<summary>Answer</summary>

**B.** The owner is the part before the first single slash, read right to left. B ends in `examplebank.example`. A belongs to `verify-now.example`, and C swaps the letter l for the digit 1.
</details>

---

### Question 3
A caller says they are from the police, that you are under "digital arrest", and demands money over a video call. What is this?

- A. A scam. Real agencies never demand money over a video call
- B. A legal process you must obey
- C. A routine bank security check

<details>
<summary>Answer</summary>

**A.** This is vishing, mixing fear and authority. Hang up, do not pay, and report it by calling 1930 or at cybercrime.gov.in.
</details>

---

### Question 4
Your manager emails you to urgently change a supplier's bank details before today's payment. What is the best first step?

- A. Do it, because the manager is busy and it is urgent
- B. Reply to the same email to confirm
- C. Confirm by calling a number you already have, not one from the email

<details>
<summary>Answer</summary>

**C.** Attackers control the email thread, so replying to it proves nothing. Verify payment changes through a second, trusted channel. This is the business email compromise (BEC) pattern.
</details>

---

### Question 5
Someone on the phone says they are from your bank and asks you to read out the OTP you just received. What do you do?

- A. Read it out, because they are from the bank
- B. Refuse, hang up and call the bank's official number
- C. Read out only the last three digits

<details>
<summary>Answer</summary>

**B.** An OTP is a key to your money. Banks never ask for it, and sharing any part of it helps the attacker.
</details>

---

### Question 6 (bonus)
You get an email from `support@examplebank-security.example` with the button text "Open your statement". Hovering over the button shows `http://statement-view.example/x7Qz`. What does this tell you?

- A. Nothing, button text and link are always the same
- B. The link does not lead to the bank's own domain, so it is suspicious
- C. The link is safe because it is short

<details>
<summary>Answer</summary>

**B.** What a button says and where it goes can be different. The real destination does not belong to the bank, so do not click. Open the bank's app or type its address yourself.
</details>

---

### Question 7 (bonus)
You see a QR code sticker on a parking payment machine that asks you to scan and pay. The sticker looks like it was pasted over the original. What should you do?

- A. Scan it. QR codes are always safe
- B. Do not scan it; use the official app or pay another way, and tell the operator
- C. Scan it but do not enter any details

<details>
<summary>Answer</summary>

**B.** A pasted-over QR code is a known quishing trick. Scanning can open a fake payment page. Use an official channel and report the sticker.
</details>

---

### Question 8 (bonus)
A message that appears to come from your CEO asks you to quickly buy gift cards and send the codes. The CEO says they are in a meeting and cannot talk. What is this?

- A. A reasonable request from a busy boss
- B. A common impersonation scam: confirm with the CEO by phone or in person
- C. A test you should ignore without telling anyone

<details>
<summary>Answer</summary>

**B.** Pressure, authority and a reason why you "cannot call" are classic signs. Verify through a known channel, and report the message to your IT team so others are warned too (not "ignore it").
</details>

---

### Question 9 (bonus)
Your phone shows several login approval prompts for your work account, and you did not try to sign in. A message then arrives: "This is IT, please approve the prompt to stop the alerts." What do you do?

- A. Approve it to make the alerts stop
- B. Deny every prompt, change your password and report it to IT
- C. Ignore everything and do nothing

<details>
<summary>Answer</summary>

**B.** This is MFA fatigue combined with impersonation. Never approve a prompt you did not start. Someone probably has your password, so change it and report the incident.
</details>

---

### Question 10 (bonus)
A website has a padlock in the address bar. Does that mean it is safe to enter your bank details?

- A. Yes, the padlock means the site is verified as honest
- B. No, it only means the connection is encrypted; check the address itself
- C. Yes, but only on mobile

<details>
<summary>Answer</summary>

**B.** Attackers can get padlocks too. The padlock says the connection is private, not that the site belongs to who you think it does.
</details>

---

## Score yourself

| Score | Meaning |
|-------|---------|
| 9-10 | Strong. You can help others spot scams |
| 6-8 | Good. Review the questions you missed and the cheat sheet |
| 0-5 | Re-read the [training module](TRAINING_MODULE.md), then try again |
