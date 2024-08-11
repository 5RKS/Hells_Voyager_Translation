# Hell's Voyager Translation
The repository to store all translations of Hell's Voyager.

## Warning
The game is not yet complete, so much of the text will probably change several times between now and release. I therefore recommend that you only start translating when RKS (the creator ofHell's Voyager) says that the game is complete.

## Guide to how translate correctly the texts in Hell's Voyager
There is some rules that you must follow, and some details that you have to be careful.

### Organization
The file of translation is a .csv archive, that is a spreadsheet separeted by comma. You can use any app/site to create your translations. I particularly recommend [Google Sheets](https://docs.google.com/spreadsheets) or [Excel](https://www.microsoft.com/microsoft-365/excel).
- **First column** - Here is where the **keys** are located. They are the "name" of the text. For example, if the game is trying to write the option to start the game, it will pull the "init_menu_new_game" key, and when you run the game in English, the text "New game" will appear on the screen, or if you run the game in Portuguese, "Novo jogo" will appear, and so on. The first line must be written "KEYS", in capital letters, just to standardize;
- **Next columns** - All the others columns can be used as the translated texts, with always the first line being the name of the language (on the way it's written in their own language);
- You just need to have 2 columns, keys and language, respectively. But if you want to translate more languages, you can add another column next to your other translation column, but remember that the first column must ***always*** be the key column.

![image](https://github.com/user-attachments/assets/1443edf8-fe2f-432b-82c6-8625f422466b)
<sub>Example of what your translation spreadsheet should look like</sub>

### Code words
In the spreadsheet of translation, you going to see some strange words, here are the explication and usage of all of them.
- **{0}, {1}, {2}...** - This is a word of replacement, for texts in which parts of it can change depending on the context in game. For example, the key "term_heavy_infusion_a" returns "Heavy {0}" in english, this is for the weapons in the game, which can change their properties, and consequently their name. So this "{0}" will be replaced by the name of the weapon, such as a "Heavy Sword".
- **\[n]** - This is used to go to the next line.

### Proper names
Here is the list of proper names of areas, characters, items, etc. So, if you find than, don't translate, just put them in the text without changing your writing, changing only to the alphabet of the language.
- Mounds;
- Moundzian;
- Massaru;
- Meitsuro;
- Ravi de Santana 'RKS';
- Freak Luke;
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

## Send the translation to the repository
1. After you finish the translation, save it as the abbreviation of your translation *set 1* + "_gametexts.csv" (you can find the correct abbreviation of your translation [here](https://wikipedia.org/wiki/List_of_ISO_639_language_codes)). Like "en_gametexts.csv" for the english translation, for example. 
2. 
