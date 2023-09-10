# unraid_ssh_hardening

Works with DocGyver SSH Config Tool Plugin:

*  Disable Permit Root Login and Password Authentication
*  Use a TCP Random Port
*  In case the password is still promtted add this to sshd_config:
   *  UsePAM no
   *  ChallengeResponseAuthentication no

Script can be Cron using user scripts plugin to Array Start (The script is addapted to that Cron)

REMEMBER: Keep securely the key with a passphrase or using other methods, like Windows encrypt file to an user login, as well backup the key.

If you have a domain bought you can permit login only from a Record A, only put your IP in domain panel when you want access (Remeber DNS takes a little bit to be updated)
