## PGP

Everyone here really needs to know about this.

If you were wondering what the pgp thing in my signature is, it's a part of my pgp public key fingerprint. You can use it to retrieve my pgp public key from keyservers. For example,

    $ gpg --recv-keys 0x415AF4A3

on the terminal will import my public key. Once you have it you can start sending me encrypted email.

PGP is really handy for sending important data to people you know over email, For example:

* Passwords
* Bitcoin addresses or private keys
* Sensitive agreements or negotiations

It's also useful for:

* Confirming that a message comes from the person they say it is (that's what the signature.asc is attached to my emails)
* Signing documents
* Signing software
* Signing hashes of things

This is important because we now know NSA collects all of the information worldwide in bulk and is now sitting plaintext in a database somewhere in the USA. They tap into internet backbones to do this. It also means if some competitor happens to know some NSA contractor you might as well be tweeting your emails to the world. Email is not secure.

Lastpass uses the same mechanism behind the scenes when transferring passwords.

Edward Snowden uses this message to talk to journalists. It works.

### Setting up PGP (OSX)

1. Goto https://gpgtools.org/
2. Download GPG suite
3. Open terminal and type gpg --recv-keys 0x415AF4A3 to get my public key
4. You can now send encrypted email to me in Mail.app. Awesome.
5. If you don't use mail.app you are doing it wrong.
6. Open GPG keychain access and click new to generate a new key for yourself. Make sure to click upload key so it's easy to gpg --recv-keys your short id.


### Setting up PGP (Windows)

Fuck if I know probably something like this http://www.gpg4win.org/

Your system is probably already backdoored by the NSA anyways though have fun.


Q: GPG, PGP, which is it?

A: Yes


You're welcome