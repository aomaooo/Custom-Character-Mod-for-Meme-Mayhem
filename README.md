[Custom-Character-Mod-for-Meme-Mayhem](https://github.com/aomaooo/Custom-Character-Mod-for-Meme-Mayhem).
Download it and place it in your mod folder: `C:\Users\YOUR-USER-NAME\AppData\LocalLow\Cr3 Studio\Meme Mayhem\Mods`.

# Custom Character Mod Instructions

To customize the characters in the 

Trigger.lua.txt

 file, you need to edit specific lines for each character.

## Steps to Edit the File

1. Open the File: Open 

Trigger.lua.txt

 with a text editor (Visual Studio Code or Notepad).
2. Find the Lines: Locate the lines corresponding to the character you want to edit using the table below.
3. Edit the Character Name: Change `"change_name_here_for_X"` to your desired name, keeping the quotes.
4. Save the File: Save your changes.

## Example

If you want to change the name of the first character (Meme Lord):

1. Find the line:
   Api:CreateCharacter("change_name_here_for_MemeLord", "naysayer")
   Change it to:
   Api:CreateCharacter("MySuperCoolNewName1", "naysayer")

2. Find the line:
   local character_data = Api:GetCharacterData("change_name_here_for_MemeLord")
   Change it to:
   local character_data = Api:GetCharacterData("MySuperCoolNewName1")

## Graphics

For each character, you also need to provide the corresponding graphics. The PNG files are already pre-made in the `textures` folder. You just need to check the ones you want to change their appearance and overwrite them using strictly the same file name.

## Example for Graphics

For the first character (Meme Lord):

- Icon Picture: `1meme_lord.png`
- Main Skin: `1meme_lord_high_res.png`

Place these files in the `textures` folder.

## Character Lines to Edit

Character Number | Code Reference | Display Name in Game | Line to Edit | Value to Change
------------------|----------------|----------------------|--------------|----------------
1                | naysayer       | Meme Lord            | 2            | "change_name_here_for_MemeLord"
1                | naysayer       | Meme Lord            | 3            | "change_name_here_for_MemeLord"
2                | sakiko         | Pre-Bandleader       | 10           | "change_name_here_for_PreBandLeader"
2                | sakiko         | Pre-Bandleader       | 11           | "change_name_here_for_PreBandLeader"
3                | robot          | Perfect              | 18           | "change_name_here_for_Perfect"
3                | robot          | Perfect              | 19           | "change_name_here_for_Perfect"
4                | priest         | Filthy Priest        | 26           | "change_name_here_for_FlithyPriest"
4                | priest         | Filthy Priest        | 27           | "change_name_here_for_FlithyPriest"
5                | keg            | Keg                  | 34           | "change_name_here_for_Keg"
5                | keg            | Keg                  | 35           | "change_name_here_for_Keg"
6                | hachimi        | Jaws Jora            | 42           | "change_name_here_for_JawsJora"
6                | hachimi        | Jaws Jora            | 43           | "change_name_here_for_JawsJora"
7                | jonouchi       | Mystic Wheeler       | 50           | "change_name_here_for_MysticWheeler"
7                | jonouchi       | Mystic Wheeler       | 51           | "change_name_here_for_MysticWheeler"
8                | yaju           | Senpai               | 58           | "change_name_here_for_Senpai"
8                | yaju           | Senpai               | 59           | "change_name_here_for_Senpai"
9                | zard           | Salad Bunny          | 66           | "change_name_here_for_SaladBunny"
9                | zard           | Salad Bunny          | 67           | "change_name_here_for_SaladBunny"

---

Follow these steps for each character you want to customize. Happy modding!
