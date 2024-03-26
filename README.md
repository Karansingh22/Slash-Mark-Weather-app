
## Setup
npm install
npm start

if you get error like this 
Error message "error:0308010C:digital envelope routines::unsupported"
 
Then we have two ways to resolve this problem !!


 1. Downgrade to Node.js v16.

You can reinstall the current LTS version from Node.js’ website.

You can also use nvm. For Windows, use nvm-windows.

2. Enable legacy OpenSSL provider.

On Unix-like (Linux, macOS, Git bash, etc.):
export NODE_OPTIONS=--openssl-legacy-provider

On Windows command prompt:
set NODE_OPTIONS=--openssl-legacy-provider!



On PowerShell:
$env:NODE_OPTIONS = "--openssl-legacy-provider"


[Screenshot (230)](https://github.com/Karansingh22/Slash-Mark-Weather-app/assets/121443798/e0285451-dd60-4859-a854-46511b9defc6)
