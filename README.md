Unsubscribe-Gateway
===================

Webapp agent for unsubscribing from E-Mail lists

## Idea

**Simple** webapp that can be used to perform and track "unsubscribe" operations for both URL links and E-Mail based unsubscribe.

The purpose/benefit would be to:

  - Track the history of unsubscribe attempts to see if you've tried to do it more than once, etc
  - For those systems that only allow unsubscribe via sending an E-Mail, the system will make it easy to send from the address they will be looking for, since many people receive from multiple alias addresses (i.e. info@mycompany.com)
  - Compile a phishing database and automatically check to see if the unsubscribe link/address itself is actually a bogus/scam, or otherwise harmful/malicious

In the beginning, the interface for this could be a simple form to paste in the unsubscribe address/info.

Later on, the system could be expanded to allow simply forwarding a spam/junk mail to a special, per-account address which will automatically attempt to parse the unsubscribe info and perform it. This could also be provided as an IMAP account so users could simply drag/drop e-mails in their mail client, w/o requiring a lot of thought/effort, and the system will just DWIW...

I bet that there is already something out there along these lines... 
