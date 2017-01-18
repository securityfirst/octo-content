[Title]: # (Jitsi)
[Difficulty]: # ()
[Order]: # (5)

# JITSI TOOL GUIDE

## Jitsi Tool Guide  
Secure Audio, Video and Instant Messaging

**Lesson to read: [Making a Call](umbrella://lesson/making-a-call)**  
**Download Location:** [https://jitsi.org/Main/Download](https://jitsi.org/Main/Download)  
**Computer requirements** All Windows Versions, Mac OS X, Ubuntu, Linux  
**Version used in this guide:** Jitsi 2.4  
**License:** Free and Open-Source Software  
**Level:** Beginner  
**Time required:** 15-20 minutes

### 1.1 Getting started

**Using Jitsi will give you:**   
? A secure alternative to Skype that encrypts calls, messages and video all the way from your computer to the recipient's computer.   
? The ability to register various accounts that you may already have (such as Facebook, MSN, Google Talk or Yahoo Messenger), with Jitsi and use it to communicate in them simultaneously.   
? The ability to communicate securely and simultaneously with other programs recommended in this app such as Pidgin, Adium and ChatSecure. 

### 2.1 How to Install Jitsi

To install Jitsi, perform the following steps:

**Step 1.** Double click ?jisi-2.4-latest-x86.exe?; the _Open File - Security Warning_ dialogue box may appear. If it does, click ?Next? to activate the _Windows Installer_ screen, followed by the _Welcome to the Jitsi Setup Wizard_ window.

**Step 2.** Click ?Next? to activate the _End User License Agreement_ window; check the _I accept the terms in the License Agreement_ option to enable the _Next_ button, and then click ?Next? to activate the _Destination Folder_ window.

**Step 3.** Click ?Next? to activate the _Additional Tasks_ window and accept the default settings as presented.

**Note:** Enabling the _Auto-start when computer restarts or reboots_ option may slow down the overall function of your computer, especially if you already have multiple applications configured to run when your computer starts up.

**Step 4.** Click ?Next? to activate the _Ready to Install Jitsi_ window, and then click ?Install? to activate the _Installing Jitsi_ window displaying the installation progress bar.

**Step 5.** Click ?Finish? to complete the installation process and automatically launch the **Jitsi** _Sign in_ window as follows:
![image](tool_jitsi1.png)

**Note:** In some instances, installing and launching Jitsi for the first time triggers a _Windows Security Alert_ prompt screen, as shown below. 

**Step 6.** Select both **Private** and **Public** networks check-boxes, and then click _Allow access_*** to see the _Jitsi Sign in window_ or main user interface window.
![image](tool_jitsi2.png)

### 2.2 How to Add Accounts in Jitsi

Please note that even with Jitsi encryption, account providers like Google or Facebook are monitoring the very fact that you are communicating (and perhaps with whom you are communicating), and may share this information with third-parties, such as corporations or governments. Therefore it is perhaps best to avoid using those accounts for very sensitive communication even with Jitsi encryption. 

### 2.2.1 How to Add a Gmail/Google Account

**Note:** The example which follows is based on a Google Talk account, the set-up process for the other communication protocols is similar. Communications or some encryption features may not work between users of different account providers (like Facebook, Gmail, Yahoo, etc.). However, they should work when communicating between two accounts from the same provider.

**Step 1.** Select **Start > Jitsi** or double-click the Jitsi desktop icon to open Jitsi.

**Step 2.** In the _sign in_ window, type in the username and password of the Gmail account you would like to use for chat purposes, so that it resembles the following:
![image](tool_jitsi3.png)

 **Note:** You can add multiple accounts using different protocols at the same time.

**Step 3.** Click ?Sign in? to activate your account chat window.

**Note:** If you closed _Sign in_ window, or you want to add another account, you can add it by selecting **_File > Add new account..._** menu. In the new window select **Network** as _Google Talk_ and type in the user name and password of the Gmail account as shown on the image below:
![image](tool_jitsi4.png)

To verify that you have registered your Gmail account with Jitsi, perform the following steps:

**Step 1.** Select **Tools > Options** in the menu to activate the following window:
![image](tool_jitsi5.png)

**Note:** If you are using 2-step verification to protect access to your Gmail account, when you try to log in from Jitsi with your regular password you may see a message like the one below. To log in using Jitsi, you will need to generate an "application-specific password". See Google's [instructions on how to do this](https://support.google.com/accounts/answer/185833?hl=en).

### 2.2.2 Registering new Jabber/XMPP or SIP account and adding it to Jitsi


Jabber/XMPP and SIP are open standards of text and voice communication. There are many servers that offer free accounts which you can use with Jitsi. Below we are recommending some of the servers that you could use for sensitive communication. 

? **Riseup.net** Jabber/XMPP account

If you have account on the Riseup.net secure email service (located in the USA) you may use this account also to communicate over Jabber/XMPP network by adding this account to Jitsi - see below on how to add existing Jabber/XMPP account.

? **Jabber.ccc.de** and other Jabber/XMPP accounts

You can register an account on Jabber.ccc.de server (located in Germany) by taking following steps:

**Step 1.** In Jitsi, select **_File > Add new account..._** in the menu. In the new window, select **_Network:_ XMPP** and check the _Create a new XMPP account*** option_. In _*Server_, type jabber.ccc.de, type in the XMPP username you would like to create, and fill in the _Password_ and _Confirm_ password fields so that it resembles the following:
![image](tool_jitsi6.png)

**Step 2.** Click **Add**. After successful registration you will be presented with a window similar to that above.

If the username which you requested is already taken by somebody else, the registration process will fail with the message _We failed to create your account due to the following error: Could not confirm data_. You can try again by repeating the process and selecting a different username.

**Note** that if you do not log in to your jabber.ccc.de for longer than 12 months your account will be automatically removed from the server and the username will become available for registration by other people.

? **ostel.co** SIP account

**SIP** accounts cannot be registered from within the Jitsi program. The **ostel.co** server (located in USA) offers [registration on their web page](https://ostel.co/users/sign_up). Select a username, password and provide your existing email address and click the _Sign up_ button on the web page. After successful registration come back to Jitsi program. Select **_File > Add new account..._** in the menu, select **Network: SIP**, type in your username (e.g. terence.the.tester@ostel.co) and the password you created during the web registration and click **_Add_**. See following image for reference:
![image](tool_jitsi7.png)

? **Adding existing Jabber/XMPP or SIP account to Jitsi**

If you already have Jabber/XMPP or SIP account you can add it to Jitsi by selecting **_File > Add new account..._** in the menu and selecting the appropriate Network (either XMPP or SIP depending on the account type).

2.2.3 How to Add a Facebook Account

Facebook has two settings that you may need to change before Jitsi can connect to your Facebook Chat.

? **Facebook Username**

Facebook requires a username for Jitsi to connect to Facebook chat. Many Facebook users already have a username. To check your username, log in to your Facebook account: your username is what appear in the location bar of your browser after _https://www.facebook.com/_ when you view your Timeline or Page. Your username is also in your Facebook email address for your personal account (ex: username@facebook.com). You can see or change the username or get one by going to your _Account Settings > General_ section or by visiting [https://www.facebook.com/username](https://www.facebook.com/username). To set username Facebook may ask you for your account verification which may require sending SMS to a mobile phone number which you will need to provide to Facebook in the process of verification.

? **App Settings**

Facebook?s ?application platform? must be turned on before **Jitsi** can connect to Facebook Chat. Visit your Facebook _Account Settings > Apps_ section and check that the setting for Apps you use is turned On. This turns "application platform" on for your account.

**Note** that that turning Facebook?s "application platform" opens up much of your Facebook data to third-party application developers. This data is available not only to the Facebook applications that you use, but also Facebook applications used by any of your friends. After turning on Facebook?s "application platform", be sure to check the settings under "Apps others use". This setting allows you to hide some personal information from applications used by your friends. Unfortunately, Facebook does not offer settings to hide all personal information. Certain categories of information (like your friend list, gender, or info you have made public) are visible as long as Facebook?s "application platform" is turned "on". It is up to you to determine whether this is an acceptable tradeoff of your privacy.

Now you are prepared to add your Facebook account to Jitsi. To do this follow the steps below:

**Step 1.** From the main menu select **_File > Add New Account..._**

**Step 2.** In the Add New Account dialogue, **Network** menu choose _Facebook_, enter your username and password and Click **"Add"**
![image](tool_jitsi8.png)

### 2.3 How to change password for account with Jitsi

It is important element of security to know how to change the password for each account that one has. Many of the accounts that you can use with Jitsi offer changing password as a part of their settings, which are accessible over web interface. However some Jabber/XMPP and SIP account will not have any web interface to manage them. You can change password for those account using Jitsi by following steps below:

**Step 1.** Select **_Tools > Options_** in the menu, select the **_Accounts_** tab

**Step 2.** Click on **_Edit_** button on the bottom to activate a new window.

**Step 3.** Click on **_Change account password_
 to activate _Change account password_ window.


Step 4.** Enter new password and Re-enter password and click on **_OK_** button to close this window.

**Step 5.** Close Account Registration Wizard.

### 2.4 How to configure Jitsi to improve it's security

### 2.4.1 Disable and remove call and chat history

Jitsi by default stores information about the incoming and outgoing voice/video calls and the history of your text chats -- all messages that you sent and received. You can access voice/video calls by clicking on the clock icon on the main Jitsi window:
![image](tool_jitsi9.png)

You can see the text chat history by clicking on the egg-timer like icon in the text chat window while chatting with a contact:
![image](tool_jitsi10.png)
Even if you encrypt the text chat with OTR all the text messages you send and receive are stored on your computer in open text format.


 To prevent Jitsi collecting this information (and remove already gathered data), you and your contact should take the following steps.

**To disable Jitsi from collecting the information:**

**Step 1.** Select **_Tools > Options**_ in the menu, select the **_General_** tab and uncheck the **_Log chat history_** option.

**Step 2.** in the _Options_ window, first **select the Advanced** tab, then **select the _Logging_** section, and then **uncheck the _Enable packet logging_** option as shown below:
![image](tool_jitsi11.png)

Your changes will take effect after you restart Jitsi.

**To remove already collected information about your calls and text messages:**

**Step 1.** Quit Jitsi.

**Step 2.** Remove the entire log history folder _history_ver1.0_ from the Jitsi user profile folder. You can remove a sub-folder of _history_ver1.0_ if you want to dispose of only part of the history. The location of the _user profile_ and _log history_ folders depends on the operating system:

? On Windows XP and earlier, this is located in _C:\Documents and Settings\&lt;Windows login/user name&gt;\Application Data\Jitsi\history_ver1.0_  
? On Windows Vista, 7, 8, this is _C:\Users\&lt;Windows login/user name&gt;\AppData\Roaming\Jitsi\history_ver1.0_  
? Mac OS X: from your home folder _~/Library/Application Support/Jitsi/history_ver1.0_  
? Linux: from your home folder _~/.jitsi/history_ver1.0_

See the [Secure Deleting lesson](umbrealla://lesson/safely-deleting) for more on how to dispose of information securely.

### 2.4.2 Require private messaging when text chatting

It is recommended that you set Jitsi up to require private and encrypted text messaging using OTR encryption whenever possible. To do this, select **_Tools > Options_** in the menu, select the **_Security_** tab, select the **_Chat_ sub-tab and check 
_Require private messaging_** at the bottom of the screen.

### 2.4.3 Protect passwords to your accounts with master password

It is best not to let Jitsi remember passwords to your accounts. If you decide otherwise for ease of use anybody who gets access to your computer will be able to log in to your accounts by simply starting Jitsi. It will also be possible to view your passwords in the Options window. It is therefore **strongly recommended** to protect passwords to your accounts with good master password. Once you set up the master password, Jitsi will ask you for it upon starting the program.

**Step 1.** Open the Options window by selecting **_Tools > Options_** in the menu, select the **_Security_** tab and **_Passwords_** sub-tab, and check **_Use a master password_** to activate the **_Master Password_** window.

**Step 2.** In the new window, type in your password. For more on creating a strong password, see the **[Password lesson](umbrella://lesson/passwords)**.

**Step 3. Click _OK_** to confirm the password and activate a new window which should say **_Master Password successfully set up_**. Click "**OK
" to close it and come back to the _Options_ window which should resemble below:
![image](tool_jitsi12.png)


Note:** The **_Change Master Password_** button lets you change the master password and the **_Saved Passwords..._** button lets you access the list of passwords remembered by Jitsi and remove them if need be.

### Jitsi - Add contacts and communicate text & voice

### 3.1 Add contacts (buddies) to Jitsi

After adding at least one account to Jitsi and logging in, you are ready to add your contacts and communicate with them.

**Step 0.** Open the Jitsi main window by selecting **_Start > Jitsi_** or double-clicking the Jitsi desktop icon.

**Step 1.** Select **_File > Add contact..._** which will open the following window:
![image](tool_jitsi13.png)

**Step 2.** Select which of your accounts you would like to add this contact to (for example _terance.the.tester@jit.si_).

**Optional:** You may also add the contact to a group among your other contacts. However, first you must create the group. You can do this by selecting **_File > Create group...**_ from the menu).

Type in your contact's user name or address into the **_ID or Number_** field (for example, _sally.the.doer@jit.si_).

You can choose the name or nickname for the contact, which will be visible in your contacts list in the Jitsi main window; type it into the **_Display name_** field.

**Step 3.** Click on _Add_ to close the _Add contact_ window and come back to Jitsi main window. In your contact list you will now see your new contact added with the note "Waiting for authorisation".

**Step 4.** When your contact (sally.the.doer@jit.si) logs in to her account, a pop-up window will inform her that you have requested to add her to your list of contacts:

Your contact has a choice of selecting the _Ignore_ option, in which case your request will continue awaiting authorisation; _Deny_, in which case you will receive information that your request was rejected; and _Authorise_, in which case you will receive information that your contact has accepted your authorisation request, and the entry for your contact in your contact list will become active.

### 3.2 Text chat (Instant Messaging) with OTR encryption

Now that you added and authorised your contact, you can click on their name in the contact list and initiate text conversation, voice or video calls, and desktop sharing, by choosing the relevant icon under their name:
![image](tool_jitsi14.png)

Step 1. We will now explore one of Jitsi's most important features: the ability to text chat securely, encrypting your messages with OTR. OTR functions in a similar manner to GPG/PGP described in other chapters in this toolkit. Just as with PGP, before you and your contact can encrypt your communications, you both need to configure Jitsi to generate your encryption keys. You can do this by selecting **_Tools > Options_** menu and selecting the **_Security_** tab and **_Chat_** sub-tab. You will then see a window similar to one shown in the image below:
![image](tool_jitsi15.png)

**Step 2.** Next, click the **_Generate_** button. As a result you will see the fingerprint of the key that has been generated:
![image](tool_jitsi16.png)

One key is generated per account. You only need to do this again if you add a new account or install Jitsi on another device and do not move the existing keys to it.

Now you are ready to communicate:

**Step 3.** Select a contact from Jitsi main window and click on the _send message_ icon (first from the left under the contact's name) to open a text chat window:
![image](tool_jitsi17.png)

Note the _Encrypt chat with OTR_ icon, the open padlock on the right-top side of the window. This inconspicuous symbol informs you whether the chat is encrypted or not. Now the lock is open (there is a tiny space between handle and the body of the lock!).

**Step 4.** Click on the **_Encrypt chat with OTR**_ icon. Note the changes in the window:
![image](tool_jitsi18.png)


Observe that the padlock is now locked. This means that whatever messages you and your contact send to each other are encrypted. Note the message that this is an _unverified private_ conversation and that you should _authenticate_ sally.the.doer@jit.si.

**Step 5.** Click on the link **_authenticate sally.the.doer@jit.si_** to open the _Authenticate Buddy_ window:
![image](tool_jitsi19.png)

Note the message that encourages you to compare the fingerprints of your keys with your contact over another channel (not this text chat). In doing this, you can be more certain that you are communicating with your contact and not somebody else. A good choice for key comparisons is to do it face to face, or via video or voice communication as these provide easier means to authenticate the identity of the other person. After you compare fingerprints, select the option **_I have verified_** the fingerprint from the pull-down menu and click on **_Authenticate Buddy_**:
![image](tool_jitsi20.png)

Closing the _Authenticate Buddy_ window returns you to the chat window.
![image](tool_jitsi21.png)

Note that padlock no longer includes the orange triangle with the white exclamation mark. This means that you have authenticated your contact. **The authentication should be done only once per contact.** If the triangle with exclamation mark returns, it means that you are chatting to somebody who you have not yet authenticated. This can happen when your contact moves to another device with another encryption key (another installation of Jitsi, or another OTR enabled program, etc.). In this case you will need to re-authenticate each other again to be sure of the identity of person with whom you communicate.

Jitsi allows you to text chat with more than one person in the same time. OTR encryption will only work when chatting to one person.

### 3.3 Voice and video chat with ZRTP encryption

Jitsi offers voice and video chats which can be independently encrypted with open standard called ZRTP. In order to initiate the chat you need to

**Step 1.** Click on the contact in Jitsi contact list and click on the voice (second icon from the left under the contact's name) or video (third) icon. A new window will appear indicating that Jitsi is establishing the connection:
![image](tool_jitsi22.png)

Your contact will see an incoming call notification.

**Step 2.** If your contact accepts the call you will receive information that you are connected:
![image](tool_jitsi23.png)

**Note** the red open padlock. This means that your call is not yet encrypted with ZRTP.

**Step 3.** Wait... Your and your contact's programs are establishing an encrypted connection, which may take a moment. If they succeed you will see the letters _zrtp_ appear against an orange background with a closed padlock like below. If they don't succeed in establishing a connection, you still can chat but without encryption. You can disconnect, restart Jitsi and try again to see if this time the programs will connect with encryption. ZRTP may not work in calls between accounts from different providers (such as between Google and Jit.si).
![image](tool_jitsi24.png)

**Step 4.** Observe the section under the letters _zrtp_ and padlock with the message "Compare with partner" followed by 4 characters. Read these letters to your contact and ask if she sees the same characters. If she does, it means that your communication is encrypted and nobody is interfering with it. You can click **_Confirm_**. The orange _zrtp_ field will turn green:
![image](tool_jitsi25.png)

**Step 5.** You may close the black confirmation section of the window by clicking on the white x sign on upper-right part of the black section:

Jitsi lets you voice and video chat with more than one person. Note that with this communication, ZRTP encryption can be engaged between initiator of the call and other parties, but not between parties themselves.