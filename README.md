# aws Notes
Never forget these pre-flight checklists before making changes to infrastructure

When changing a website-DNS entries, protect your E-Mails MX-Records with your life! 

[NOV 24th, I just screwed up my EMAIL]![Screenshot 2022-11-24 at 4 20 47 AM](https://user-images.githubusercontent.com/30084404/203759443-38b965fc-fbc7-4380-b336-2d9b8ceda778.png)

[NOV 25th, I just fixed my EMAIL] What fixed my problem? Using a DNS Lookup Tool showed that there was no response from any NameServer which meant that something was up with my NameServer configuration. 

I went and double checked and made sure they were the same and they were not so I then updated it, waited an hour or so until the domain details were updated then the domain verification succeded and all the lost emails trickled in over a few hours.

What did you learn Noryev? Protect your MX records with your life and dont fuck with your Name server unless you have too... which i did have too so maybe go figure out why the name server changed? I did not re-create any hosted zone or anything. If anything, I deleted the records... Look more into this

-clean all this up
