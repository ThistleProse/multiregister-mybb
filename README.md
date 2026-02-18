Google-Translate English version of this epic myBB mod.

<h1># Multiregister</h1>
This plugin allows your users to register new characters effortlessly – directly through the UserCP! No need to log out: simply enter the character name, password, and any required profile fields during registration, and you're good to go. The email address and settings are automatically transferred from the active character. Depending on whether the Account Switcher plugin is enabled, the newly created account will be directly linked to the master account of the current account (or to the master account itself if none exists). The following settings are configured in the AdminCP:

<ul>
<li> Enable/disable Account Switcher
<li> Default user group for newly created accounts
</ul>

<h1>Plugin ACP</h1>
<ul>
<li>Upload the plugin file to the specified folder <b>inc/plugins</b>.
<li>Upload the language file to the specified folder <b>inc/languages/english</b>.
<li>The plugin must now be installed and activated in the Admin CP under <b>Configuration - Plugins</b>.
<li>Configuration -> Settings -> Plugin Settings -> Multiregister to set Account Switcher link, and Default Usergroup.
</ul><br />

The plugin is now ready for use.
The navigation of the UserCP contains a link to the corresponding page:
usercp.php?action=multiregister

<h1>Templates</h1>
The following templates are added by this plugin:
<ul>
<li>usercp_multiregister
<li>usercp_multiregister_master
<li>usercp_nav_multiregister
</ul>

<h1>Previews</h1><br />

<center><img width="744" height="297" alt="Screenshot 2026-02-18 194026" src="https://github.com/user-attachments/assets/2a8ae627-65c5-400c-9f8f-3c9d4edcaf66" /></center>

User CP:
<center><img width="924" height="398" alt="Screenshot 2026-02-18 194000" src="https://github.com/user-attachments/assets/0f36502e-0ab8-497a-9f8d-8bc4d68d6512" /></center>

The plugin was tested under the latest MyBB version and in active forum use. No errors occurred during initial tests; however, it is still recommended to back up the database before installation and first use. 

