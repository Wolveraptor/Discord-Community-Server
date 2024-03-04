# Embedded Messages
Libertas vel Mors Discord community server JSON files for embedded messages for use with the Red Discord Bot embedutils cog.

## About Embedded Messages
These are JSON files that are used for embedded messages with [Red Discord Bot](https://github.com/Cog-Creators/Red-DiscordBot) that uses the [embedutils](https://github.com/AAA3A-AAA3A/AAA3A-cogs/tree/main/embedutils) cog by [AAA3A](https://github.com/AAA3A-AAA3A/AAA3A-cogs).

* Information about Red Discord Bot can be found here: https://github.com/Cog-Creators/Red-DiscordBot
* Information about the embedutils cog can be found here: https://github.com/AAA3A-AAA3A/AAA3A-cogs/tree/main/embedutils
* Information about additional cogs created by AAA3A can be found here: https://github.com/AAA3A-AAA3A/AAA3A-cogs
* Information about additional cogs for Red Discord Bot can be found here: https://index.discord.red/

## Items to Note

Color Hex Codes:
* J.A.R.V.I.S.
    * ```#1563dd```
* F.R.I.D.A.Y.
    * ```#c80b52```
* E.D.I.T.H.
    * ```#22d599```
* Veronica
    * ```#db8215```

The above color hex codes will be used for the embedded message color depending on the bot that the embedded message will be sent as.

Icons:
* Libertas vel Mors Server Icon
    * ```https://raw.githubusercontent.com/Wolveraptor/Libertas-vel-Mors---Discord-Community-Server/main/Images/libertas_vel_mors_server_icon.png```

    ![alttext](/Images/libertas_vel_mors_server_icon.png)

* J.A.R.V.I.S. Icon
    * ```https://raw.githubusercontent.com/Wolveraptor/Libertas-vel-Mors---Discord-Community-Server/main/Images/libertas_vel_mors_jarvis_icon.png```

    ![alttext](/Images/libertas_vel_mors_jarvis_icon.png)

* F.R.I.D.A.Y. Icon
    * ```https://raw.githubusercontent.com/Wolveraptor/Libertas-vel-Mors---Discord-Community-Server/main/Images/libertas_vel_mors_friday_icon.png```

    ![alttext](/Images/libertas_vel_mors_friday_icon.png)

* E.D.I.T.H. Icon
    * ```https://raw.githubusercontent.com/Wolveraptor/Libertas-vel-Mors---Discord-Community-Server/main/Images/libertas_vel_mors_edith_icon.png```

    ![alttext](/Images/libertas_vel_mors_edith_icon.png)

* Veronica Icon
    * ```https://raw.githubusercontent.com/Wolveraptor/Libertas-vel-Mors---Discord-Community-Server/main/Images/libertas_vel_mors_veronica_icon.png```

    ![alttext](/Images/libertas_vel_mors_veronica_icon.png)

The above icons will be used when creating and sending embedded messages.

## Embedded Message Generation
Embedded messages are created online by using the [EmbedUtils](https://embedutils.com/) GUI and once the embedded message is created a JSON file is created in this repository that the embedutils cog can use and the bot can post the embedded message.

1. Open a web browser and navigate to: https://embedutils.com/

    ![alttext](/Images/embedutils_url.png)

2. Click on the broom icon to clear the pre-populated information from the GUI builder.

    ![alttext](/Images/embedutils_broom_icon.png)

3. Build the embedded message with the GUI builder.

    ![alttext](/Images/embedutils_gui_build_message_1.png)
    ![alttext](/Images/embedutils_gui_build_message_2.png)

4. Click on the JSON icon to view the JSON code for the embedded message generated with the GUI.

    ![alttext](/Images/embedutils_json_icon.png)

5. Click on the copy icon to copy the generated JSON code for the embedded message.

    ![alttext](/Images/embedutils_copy_icon.png)

6. Create a new json file in the repository that corresponds to the channel the embedded message will be sent in and paste the copied JSON code.
    * The repository is structured to match the category and channel layout of the Libertas vel Mors Discord server with the exception of the "Images" folder which contains images used for documentation.

7. Stage, commit, and push changes to the repository.

8. Copy the URL of the JSON file from this repository.

8. Go to the staff "bot spam" channel and use the embedutils cog to send the created embedded message.
    * J.A.R.V.I.S. help menu for sending a new embedded message can be found below.

    ![alttext](/Images/jarvis_help_embedutils_pastebin.png)

    * J.A.R.V.I.S. help menu for editing a previously sent embedded message can be found below.

    ![alttext](/Images/jarvis_help_embedutils_edit.png)

    * Example command for sending a new embedded message to the "announcements" channel: `j?embedutils pastebin https://github.com/Wolveraptor/Libertas-vel-Mors---Discord-Community-Server/blob/main/Embedded%20Messages/announcements/rules.json`

    ![alttext](/Images/jarvis_embedutils_pastebin.png)

    * Example command for editing a previously sent embedded message in the "announcements" channel: `j?embedutils edit https://discord.com/channels/1190406648259432448/1190418929412231298/1194641948582088704 pastebin https://github.com/Wolveraptor/Libertas-vel-Mors---Discord-Community-Server/blob/main/Embedded%20Messages/announcements/rules.json`

    ![alttext](/Images/jarvis_embedutils_edit_pastebin.png)