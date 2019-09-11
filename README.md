# AudioNet Hearing Screening Application
A very, simple, lightweight hearing screening in JavaScript to ensure that a participant's playback device can reproduce and the participant themselves can perceive a specified range of frequencies.

# Inputs and outputs
When a user opens the page, a dialog box will appear asking for their full name. This identifier is used in a hash function to generate the output code which you can use to verify if they passed or not.

The passing output code is an md5 hash of `"pass" + inputCode + inputCode`.
The failing output code is an md5 hash of `"fail" + inputCode + inputCode`.

e.g. A passing output code with inputCode="hello" is `md5("passhellohello")`, or rather `'afa8ed14c3237993406a436a92e17b1d'`.

An MD5 Hash Generator for reference can be found here: https://www.md5hashgenerator.com/

# Deployed Link
The application has been deployed to http://hearingscreen.ml/

