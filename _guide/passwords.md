---
title: Managing Passwords and Logins
last_modified_at: 2017-06-11T19:21:00-04:00
permalink: /guide/passwords/
---
2FA
https://www.turnon2fa.com/tutorials/how-to-turn-on-2fa-for-twitter/
https://www.eff.org/deeplinks/2013/05/howto-two-factor-authentication-twitter-and-around-web
http://lifehacker.com/5938565/heres-everywhere-you-should-enable-two-factor-authentication-right-now
https://twofactorauth.org/

DropBox
Apple
Yahoo
Microsoft
Twitter
Facebook
Google
Slack
WordPress
LinkedIn
Steam
BANKS!


Sharing accounts with family and friends

Don’t store 2FA and backup codes in your password manager
The point of the emergency codes is to give access to a site when you lose the password, the authenticator app, or the phone. If you place your emergency codes (or the secret OTP seed if you stored that) in 1Password, then regardless of whether you sync your 1Password database out of your phone or not, if your 1Password database is compromised, then your 2FA accounts are compromised. Your 2FA needs your password and your timed OTP -- these are the two factors we need to gain access to a site. If both factors are tied together, neatly placed together so that having one entails having the other, then this begs the question why we need them both. Remember that 2FA's sole raison d'être is to make knowing a password not enough to gain access. You place them together, and it's exactly as if gaining access to your password is enough to gain access to your site. It is then simpler to cancel 2FA and rely on the password alone. If you place your passwords as well as your 2FA keys under one master password, you have a single factor authentication, not a two-factor authentication.

Yes, anyone who has the secret key can use it to generate one-time passwords for your account. It should be treated in the same way as a password for a site that doesn't have 2FA. It's more secure mostly because the user doesn't get to choose it, and so can't use a weak password or a password they've used on another site.
In particular, I would advise against storing 2FA secret keys in the same place as you store passwords. If you do, then anyone who compromises that store has got both factors. If you use a password manager for your passwords, use a different program for your 2FA codes.
