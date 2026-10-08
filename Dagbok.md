
On October 7, 2026, I was in class and manually entering commands into PowerShell.

First, I created new groups: Innkaup, Sala, Yfirstjorn, and Allir.
I did this using the `New-LocalGroup -Name ...` command.
Next, I ran the `Get-LocalGroup` command to verify that everything was working correctly.

Then, I added the users and assigned them to their respective groups.

After that, I created folders for each of the groups.

Next, I granted the groups permissions to access these folders.

Then, I configured the password policies.

Finally, I executed `Set-NetFirewallProfile -Profile Domain,Private,Public -DefaultInboundAction Block`.
