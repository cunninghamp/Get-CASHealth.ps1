# Get-CASHealth.ps1 - Exchange Server 2013 Client Access Health Check

This PowerShell script checks the health of each Exchange 2013 client protocol by making a web request for the /healthcheck.htm file in each virtual directory.

Results are output to console. Future plans include output to HTML and email.

## Usage
```
.\Get-CASHealthCheck.ps1
```

## Credits
Written by: Paul Cunningham

Find me on:

* My Blog:	http://paulcunningham.me
* Twitter:	https://twitter.com/paulcunningham
* LinkedIn:	http://au.linkedin.com/in/cunninghamp/
* Github:	https://github.com/cunninghamp

For more Exchange Server tips, tricks and news check out Exchange Server Pro.

* Website:	http://exchangeserverpro.com
* Twitter:	http://twitter.com/exchservpro

Additional credits and references:
http://www.bhargavs.com/index.php/2014/03/17/ignoring-ssl-trust-in-powershell-using-system-net-webclient/
