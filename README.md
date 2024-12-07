For example, if you want to change the skin of the Meme Lord (the first character):

download the repository and place it in your mod folder: C:\Users\YOUR-USER-NAME\AppData\LocalLow\Cr3 Studio\Meme Mayhem\Mods.

Go to the folder you've just installed and navigate to scripts
Open the file Trigger.lua.txt with a text editor (I suggest using Visual Studio Code, but Notepad will work too).

To change the name of the first character, Meme Lord, look for this line:
Api:CreateCharacter("changeyour_mod_name_here1", "naysayer")
Change "changeyour_mod_name_here1" to your desired name, but keep the quotes:
Api:CreateCharacter("MySuperCoolNewName", "naysayer")

Do the same for the line just below:
local character_data = Api:GetCharacterData("changeyour_mod_name_here1")

Now that you've changed the file data with your new name, you'll need to change the graphics.

For your icon picture, create a 320x320 PNG file in 72dpi with a transparent background and name it character_reskin1.png.

For your main skin, create a 700x700 PNG file in 72dpi with a transparent background and name it character_reskin_high_res1.png.

Place these two PNG files in textures

Et voila!

Run Meme Mayhem, go to the mod section, and check your work.

This example is only for the Meme Lord. If you want to change the other characters, follow the same steps but use the corresponding numbers (e.g., character_reskin2.png for the second character, character_reskin3.png for the third, etc.).

Happy modding!

Maybe there's is a way to create automated functions to help
