# tinymce_moodlemedia

What is the change?
-------------------
1. Courses only under root category will have the option to add moodlemedia.
2. Anybody who does not have access right to change course content (such as students) won't able to use moodlemedia
3. Moodlemedia icon is available only in real course structure. Even when you are in category level or site home or updating message for maintenance mode (they are not a moodle course), you won't be able to see the moodlemedia icon in toolbar.


How to upgrade
--------------
1. Download the dev branch from https://github.com/bashet/tinymce_moodlemedia as zip.
2. Unzip and rename the directory as "moodlemedia".
3. Make sure all the child directory (lang,pix,tinymce and files on the same level) are at first step accessible inside the "moodlemedia" directory.
4. Copy the "moodlemedia" directory into clip board.
5. Go to docroot/lib/editor/tinymce/plugins
6. Replace the "moodlemedia" directory with new one.
7. Login to Moodle as Site Administrator
8. Please follow the procedure to upgrade the plugin as Administrator.

Note: This plugin comes with original installation (means it's part of core code). We need to be extra careful when we do the next upgrade of Moodle.



