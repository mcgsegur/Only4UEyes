# Only4UEyes
A tamper-proof encrypted portable Notepad that only requires a webbrowser to "run" and that allows you to keep sensitive information (such as passwords) fully protected. It was developed in HTML + Javascript, and so it is distributed and runs in its source code format in any browser (desktop, notebook or cellphone).It writes and reads its data files using a "composition" of a user chosen "password" AND the current "souce-code" (HTML + javascript) signature, that it evaluates on every run. Thus, if someone changes the source code ("tamper" with the code), the previous data files will not be decrypted anymore using only the original password- only the original code (web-page) will allow someone to recover the original data with the correct password. There is a "validation data file" available with the distribution that alows you to validate the program before using it, so that you do not risk giving up your password to an altered program. For your data safety, you can generate your own validation file with a known contents to be able to check the program later, before using it, to avoid disclosing your passwords to a possibly altered ("tampered with") program.
It is also provided an "importBrowserCSVPasswords" program that allows you to import data that you can export from the passwords stored in your browsers (firefox, chrome or Edge). Search in the internet how to do the "export" for each browser in the CSV format, and them use the "importBrowserCSVPasswords" to open these files. To import to "Only4UEys", just use copy/paste from the "importBrowserCSVPasswords" screen. Perform these "import" operation in a secure environment, as during the "export" your sensitive information will be "on the clear". These programs were projected for my personal use in the safest way possible, but to make tampering hardest for "people with eval intensions", both programs, although in a souce code distribution, are heavily obfuscated.
The idea of signing the data encoded with the source code is fully disclosed here, and this I think is the great contribution of this implementation, and its implementation is trivial. So if you want to use this idea/software as is, go ahead, but it will be a little hard to reuse this source code in another implementation.

Just a note.... if you change the program souce code by just adding a single "space" character in it (if you know a bit of HTML or javascript in a way not to destroy the program) the program may still be operational and then will only decrypt the files it encrypts------ thus you can have your personal version of the program that only works for the files it writes/reads (the program becomes part of the key to access the data......KEEP COPIES OF THE ALTERED PROGRAM!)
Good Luck!
