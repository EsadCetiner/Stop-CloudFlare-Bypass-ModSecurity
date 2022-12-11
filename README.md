Stop CloudFlare Bypass ModSecurity
ModSecurity rules to stop attackers from bypassing Cloudflare 

This ruleset is intended to prevent a threat actor from bypassing Cloudflare
DISCLAIMER: This only provides basic protection against Cloudflare bypass, it will not prevent all bypass attempts

Installation is very straight forward

1. Clone the repo
``git clone https://github.com/EsadCetiner/Stop-CloudFlare-Bypass-ModSecurity/``

2. cd into the folder you downloaded
`` cd Stop-Cloudflare-Bypass-ModSecurity``

3. Copy the file into your ModSecurity folder, whereever that may be.

4. Include the rule file within ModSecurity ``Include 860-CloudflareBypass.conf``

5. Reload your web server (Restart if you are using Nginx)
