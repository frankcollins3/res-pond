# Res Pond ------------> {...respond}
#### actual problem worth solving:
// personal but: my preference is to check email later in day because I take 10 min breaks b/w hours. 
if I check email, sometimes it can trigger pattern of:  {checkEmail() && checkIndeed}.repeat() 

Why Res Pond ? play on words.
respond: job offers are responding.
res pond -> make a pool of those responses.

#### attempted solution:
👍 Gmail API: -> (assumed to exist but never used)
leverage GMAIL api to check inbox

👍 ChatGPT API -> never used but seen chatGPT spit out example code seems feasible
maybe use chatGPT for an edge case well cover in a sec.

🚨 Amazon SimpleEmailService: 
vpn? to contact me through email 
// lol leaving the fact that I considered email on the readME as undiscernsome human error: the problem is I don't check the email. bottleneck proposition

👍 Twilio | other VPN
instead of emailing the user of this tool, send a text!

The aformentioned edge case navigates distinguishment.
It's probably quite easy to loop and return "indeed" || "linkedin emails"
but what of jobs that reach back from company email which wouldn't mention linkedin|indeed i.e. "salesOffice, NY, NY" ->
Edge case is chatGPT accommodating that obstacle by making sense of non-jobBoard emails and sending them, as user could expect w/ job-board emails, in same format.

../ meta approach:
separate concerns by having work-only email that doesn't include personal subscriptions and other

// building startup so no current time available to build this tool so open-sourcing idea for any to take and improve. 
