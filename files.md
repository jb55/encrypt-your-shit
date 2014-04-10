## Encrypting files

Putting stuff on Dropbox is about the same as mailing your harddrive directly to the NSA. This is a guide to protect sensitive documents/files.

This is a follow up to my previous email about encrypting your emails. The programs I described in my previous email can also be used to easily encrypt and decrypt files when emailing or sharing on dropbox. It's pretty straightforward:

Once [gpgtools](https://gpgtools.org) is installed (see email.md to see how to get up and running), you can encrypt a file right from the Services menu:

<img src="https://i.cloudup.com/tV2TNzGIEI-2000x2000.png" width="50%" height="50%"/>

Click "encrypt file" and then you will be presented with a list of people you can encrypt to:

<img src="https://i.cloudup.com/tqAVMShNfR-2000x2000.png" width="50%" height="50%"/>

If you have noone in this list you have to get their PGP key. You can get mine by typing "gpg --recv-keys 0x6d3e2004415af4a3" on the command line or by opening "GPG Keychain Access" and opening "Retrieve from Keyserver" or "Search for key". You will be able to find me and Ari as we're both on distributed keyservers.

<img src="https://i.cloudup.com/JHALiePhxd-1200x1200.png" width="50%" height="50%"/>

Once the file is encrypted it will generate a "filename.txt.gpg" file which is an encrypted file that only you and the recipients can open. If they have gpgtools installed they can simply double click it to open it. Make sure its not opened in the dropbox folder itself or it will get automatically synced to dropbox, defeating the whole point of this.

Just a heads up, let me know if anyone has any questions.