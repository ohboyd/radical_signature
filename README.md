# Radical Signature
A sophisticated email signature, for the less bar**bear**ic

# Instructions for setting this up with a mac mail client

- Copy the html file and open it in your text editor to edit/replace the information with your own

- Once you have the signature how you want it, copy that html and open your email preferences

- Select Signatures and create a new email signature, but don't put in too much effort (we're just going to overwrite this in a moment)

- Open finder
  1. Head to the menu bar at the top of your screen and select ‘Go’ 
  2. Hold down the ‘option’ key, and you should see ‘Library’ appear as an option in the ‘Go’ menu
  3. Select ‘Library’ 

- Navigate to Mail, then choose the most recent V folder (probably V5 if you’re using High Sierra)

- Within that directory, navigate to MailData/Signatures, and open the most recently modified `.mailsignature` file with TextEdit (this will be the one you just created)

- Replace the html text there with the html you just edited, being sure to leave all the critical information at the top (Content-Transfer-Encoding, Content-Type, Message-Id, and the Mime-Version)

- Save the new html in TextEdit, and then you can close that file

- Be sure to select that same signature in the finder window, right-click on it, and select ‘Get Info’

- Click on ‘Locked,’ so it doesn’t get overwritten while using mail in the future

- Then, restart your mail application, and try to send a test email 

# Note

You wont be able to see this signature displayed within the email preferences, but don't worry--it will be visible within the body of an email

**Unsupported Mail Recipients:**
 - Outlook 2007
