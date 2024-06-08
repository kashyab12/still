### Still
App notifications don't keep context outside themselves. On initial attempts I was trying to address the problem generally. However, solving the general problem requires some more legwork and thought. Rather, let's start simpler and pick a particular app (start with WhatsApp).
* Output data via a specific app which is contained within it's own module.
* Have a module which decides priority from which a reminder time maybe derived? Messaging apps for example have person level urgency for notification control, not message based. 
* Scale out modules for other apps and perhaps the generality will be understood.
