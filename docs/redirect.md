# Explanation

After a survey has been finished by a panelist, he/she should be redirected to us again where we will inform him about his status and provide additional information.<br />
Depending on the status a different page will be shown to the panelist.<br />
You should implement those URLs as redirects after a survey has been finished.<br />
If a survey has already been closed, the panelists should be redirected to us as well.<br />

**IMPORTANT: Those redirects do not affect the status. Both the redirect and the status should be the same, however both methods have to be implemented separately.**


# URLs

Please implement the following redirects:<br />

**Complete**<br />
`https://surveys.mobrog.com/?ID=43&return=complete`<br />

**Screenout**<br />
`https://surveys.mobrog.com/?ID=43&return=screenout`<br />

**Quotafull**<br />
`https://surveys.mobrog.com/?ID=43&return=quotafull`<br />

**Closed Survey**<br />
`https://surveys.mobrog.com/?ID=43&return=screenout&screenoutstatus=1`<br />







