# Zimbra
These scripts will help you automatically deploy and update the SSL certificates for the Zimbra mail server.

Don't forget to enter a variable DOMAIN="your-domain"

For install use command:

wget -qO $HOME/zimbra-ssl-cert-install.sh https://raw.githubusercontent.com/starnodes/Zimbra/main/zimbra-ssl-cert-install.sh

chmod +x $HOME/zimbra-ssl-cert-install.sh

$HOME/zimbra-ssl-cert-install.sh

For auto update install use command:

wget -qO /etc/cron.weekly/certupdate https://raw.githubusercontent.com/starnodes/Zimbra/main/zimbra-ssl-cert-update.sh

chmod +x /etc/cron.weekly/certupdate
