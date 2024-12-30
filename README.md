# Hell's Voyager Translation
The repository to store all translations of Hell's Voyager.

> [!WARNING]
> all original translation files (english) may change their content, thus requiring a revision or even being redone entirely, and every time these changes are made, RKS (@5rks) will notify you on the discord server in the contributors channel. So if you don't have the patience to revise or redo the entire translation, wait until RKS gives notice that this is the last change and that one will be kept for the final game.

## Translating correctly the texts of Hell's Voyager
### Organization
The file of translation is a .csv archive, that is a spreadsheet separeted by comma. You can use any app/site to create your translations. I particularly recommend [Google Sheets](https://docs.google.com/spreadsheets) (Excel will break non-english characters).
- **First column** - Here is where the **keys** are located. They are the "name" of the text. For example, if the game is trying to write the option to start the game, it will pull the "init_menu_new_game" key, and when you run the game in English, the text "New game" will appear on the screen, or if you run the game in Portuguese, "Novo jogo" will appear, and so on. The first line must be written "Keys", just to standardize;
- **Next columns** - Here is the translated texts, with always the first line being the name of the language (on the way it's written in their own language);
- You just need to have 2 columns, keys and language, respectively, but you can add a third column called "Notes" to write down any observations about the texts, or you can create a new file (called [abbreviation of the language](https://www.loc.gov/standards/iso639-2/php/English_list.php) + [abbreviation of the country in capital](https://www.iban.com/country-codes) + `_notes.txt`, `_notes.odt` or any type of text file) to put those remarks about game terms or anything else you think is good to write down to remember. If you want to translate more languages, you have to create another file to your other translation column. But remember that the first column must ***always*** be the key column.

![image](https://github.com/user-attachments/assets/f9040bf2-fb77-45b4-b258-70fac5330fb6)

<sub>Example of what your translation spreadsheet should look like</sub>

### Workflow
- Something good you could do is make the translation and test it in-game, changing the texts straight from English (file `enUS_gametext.csv`), for example. If the language you're translating uses characters differents of the “common” ones (such as those used in English), let RKS (@5rks) know on the game server which language you're translating into, and he will add support for that language to the game as quickly as he can.

### Code words
In the spreadsheet of translation, you going to see some strange words, here are the explication and usage of all of them.
- **{0}, {1}, {2}...** - This is a word of replacement, for texts in which parts of it can change depending on the context in game. For example, the key "term_heavy_infusion_a" returns "Heavy {0}" in english, this is for the weapons in the game, which can change their properties, and consequently their name. So this "{0}" will be replaced by the name of the weapon, such as a "Heavy Sword";
- **\[n]** - This is used to go to the next line.

### Text Variations
- In some moments of the translation you will see the keys with almost the same name, but with the suffix "m_one", "f_one", "m_two" or "f_two", such as happens in the keys of the infusions. Those are inflections of the noun, such as in gender (masculine or feminine) or number (singular or plural). The "m_one" singular masculine, "f_one" singular feminine, "m_two" plural masculine and "f_two" plural feminine.
- You'll also find the suffixes "one", "two", "few", "many" and "other". They differ a lot in each language, so check out the [Language Plural Rules Document](https://www.unicode.org/cldr/charts/43/supplemental/language_plural_rules.html) to get a better understanding of how each one works in your language.

### Proper names
Here is the list of proper names of areas, characters, items, etc. I prefer that you just transliterate them. If there are any problems with the translation, such as names meaning something wrong in your language, or some kind of double entendre, please contact RKS (@5rks) on Discord to discuss a good adaptation for these name.
- Mounds;
- Moundzian;
- Massaru;
- Meitsuro;
- Otsumoshita;
- Huozue;
- Vuikur;
- Huoko;
- Noctarogar;
- Kiabass;
- Zopa;
- Falon;
- Vinsir;
- Fingran;
- Connor Sant'Anna;
- Drensriel;
- Doalpus;
- Alreeis;
- Astrina;
- Eldaron;
- Grumyin;
- Gustav;
- Ardiflower (singular) or Ardiflowers (plural). You can translate to the translation of a minor form of "ardent" (or just "ardi" if you prefer) together with the translation of "flowers". Let me know in "translation-chat" on Discord how the translation turned out.

## Characters speaking in a more sophisticated/ancient way
- Hell's Voyager is set in a different world from ours and in an older era, right in the transition between ancient and contemporary times, so some characters in the game will speak in a more sophisticated/ancient way, while others will speak more colloquially. If your language has an “old way” of speaking and it's not too difficult to understand for a average speaker of the language, please, follow the way the characters have to speak, but if the “old way” of your language is too complex for a average speaker or maybe doesn't even exist, it's fine to keep the standard way of speaking for all the characters.
  
List of the way each character speaks:

| Character | Way of speaking |
| - | - |
| Mounds | Sophisticated |
| Meitsuro | Sophisticated |
| Grumyin | Mixed |
| Gustav | Colloquial |

## Send the translation to the repository
1. Download the [`enUS_gametexts.csv`](https://github.com/5RKS/Hells_Voyager_Translation/blob/main/enUS_gametexts.csv) and translate all the text to the language that you want to translate the game;

![image](https://github.com/user-attachments/assets/90ab0415-a654-447c-879a-40647a2820b2)

2. After changing the archive for entire to the language that you want to translate the game, return to the repository and click on "add files" and then "create new file";

![image](https://github.com/user-attachments/assets/3fe8e58a-7de4-4604-aa74-fa878e44e825)

3. Name the file the [abbreviation of the language](https://www.loc.gov/standards/iso639-2/php/English_list.php) + [abbreviation of the country in capital](https://www.iban.com/country-codes) + "_gametexts.csv", like `ptPT_gametexts.csv` for the Portuguese of Portugal translation, for example;

![image](https://github.com/user-attachments/assets/1b885445-ce00-410c-9aa3-6c5b6f81c943)

4. Save the file that you translated as .csv, open the .csv and copy all (Ctrl+A and then Ctrl+C);

![image](https://github.com/user-attachments/assets/440a78e5-f892-49f4-bbc5-34bc91b22f92)

5. Paste on the file you are creating on GitHub;

![image](https://github.com/user-attachments/assets/3aa07bca-2769-463a-a222-d11c1246ca65)

6. Click on "Commit changes...";

![image](https://github.com/user-attachments/assets/dd08dc9a-5f7b-4748-9b9f-8812c5202223)

7. Create a name and description to the propose, making it clear that this is a translation propose, and click on "Propose changes";

![image](https://github.com/user-attachments/assets/156ef999-eb99-4ea2-b579-193fbdd689cb)

8. Now click on "Create pull request";

![image](https://github.com/user-attachments/assets/3715d75a-70da-4fa9-a795-adb353906b44)

9. Click again on "Create pull request"

![image](https://github.com/user-attachments/assets/9e9e1a40-0e2c-4c1b-8278-dc2fa85fd53c)

10. And it's done! Wait for RKS approve or reject your pull request, if you want, you can ping him (@5rks) in "translation-chat" on Discord, probably he will see your pull request much faster.

![image](https://github.com/user-attachments/assets/2502d616-5307-4b13-abf4-c8d52b0f1770)


> [!IMPORTANT]
> ***After RKS approve your translation***, Ping the him (@5rks) in "translation-chat" on Discord and say how you want your name to appear in the credits. If you don't say anything, RKS will put your GitHub or Discord nickname in the credits.

## FAQ
### 1. Why do some texts have quotation marks at the beginning and end, but others don't?
.csv archives works with commas, so if the text have commas, you need to put that whole text in quotation marks, so that the file doesn't identify it as another text. So while you're editing texts, always remember to put those with commas in quotation marks, or put all the texts in quotation marks, it also works.

### 2. How do I know which texts have been changed, added or deleted?
In the repository commits, when you click on the commit you want to analyze, you can see the changes of the files, where you can see the changes, additions or deletions.

![image](https://github.com/user-attachments/assets/2dd904a3-c341-42ad-b356-c2550863cdb8)

> [!NOTE]
> ***ALWAYS*** remember to close the quotation marks, otherwise this will happen in the game:

![image](https://github.com/user-attachments/assets/b4b8ba40-7078-4bab-8a84-91538fe86d3d)
<sub>This happens in the game if you don't close a quotation</sub>
