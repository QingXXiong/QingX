
----

Stat:

1. Who are you?

- You are a translator, PM, developer, or someone doing translation stuff.

2. What do you have? (exp/skills)

- You have experience using DeepL and memoQ.
- You know translation stuff.

3. What do you want from me?

- I want to integrate DeepL into memoQ, so I can use it for my translation workflow.

4. What's my purpose?

- Show _how to_ integrate DeepL into memoQ for translation.

----

# How can I use DeepL Pro in memoQ 8.5 or higher?

## What's inside

- Set up the DeepL Pro plugin
- Use the DeepL Pro plugin in the editor
- Use the DeepL Pro plugin for pre-translation

Before starting, you need:

- A DeepL Pro subscription - Advanced or Ultimate plan, or else get it [here](deepl.com/pro/select-country?cta=header-prices#team).
- [memoQ 8.5 or higher installed](memoq.com/products/memoq-translator-pro) with an active license.
- Your Authentication Key for DeepL Pro. To find the key, go to __Account__ > __Authentication Key__.

__Important__: If you have trouble using the DeepL plugin with memoQ, ensure updating memoQ either automatically or manually. For more information about updating memoQ, see [Check for updates](docs.memoq.com/current/en/Places/check-for-updates.html).

## Set up the DeepL Pro plugin

1. Open memoQ.
2. Go to __MT settings__ with either following way:

- In the top left corner of memoQ dashboard, find and click the book icon to enter __Resources console__. Then, on the left of popup window, scroll down to and click __MT settings__.
- Click a project on the dashboard, then, in the left of __Project home__, click __Settings__. Then, at the top of new page, click the __MT settings__ icon.

3. Click __Create/use new__ to create a new MT resource.
4. In the popup window, for __Name__, enter a name for the new MT resource, and for __Description__, describe the resource.
5. Click __OK__.

Note: You need to check a warning about our data privacy.

6. Below __Name/description__, select the entry you created.
7. At the bottom, click __Edit__, or double-click the entry to see the __Edit machine translation settings__ window.
8. In the __Service__ tab, select the DeepL MT Plugin.
9. Click the wheel icon on the right to see the __DeepL MT plugin settings__ window.
10. Do these:

- For __Authentication Key__, enter your key, then click __Log in__ to verify whether connecting to DeepL is OK.

- If you don't want to keep formatting and tags in the MT suggestions, deselect __Tranlate with formatting and inline tags__.

Note: If you select this option, DeepL might displace tags in the suggestions. Otherwise, you must insert tags manually.

- For __Request format__, choose __XML__ or __HTML__ as the format to send DeepL your sources.

Note: If you have a problem with the selected format, switch to another one.

- For __Formality__, choose how formal MT suggestions should be. The MT suggestions by DeepL are formal by default.
- For __Glossary__, select one or more glossaries you want to use with the plugin. For details about working with glossaries, see [Using glossaries on memoQ](docs.memoq.com/current/en/Places/deepl-mt-plugin-settings.html?Highlight=Glossary).

11. Click __OK__.

## Use the DeepL Pro plugin in the editor

1. Open a project with the language pairs supported.
2. Go to __MT settings__, following the second option for Step 2 in [Set up the DeepL Pro plugin](#set-up-the-deepl-pro-plugin).
3. For __Name/description__, select the DeepL plugin entry.
4. Click __Edit__ or double-click the entry.
5. In the __Service__ tab of popup window, select the DeepL MT Plugin.
6. In the __Settings__ tab, for __Translation results__, select an option fit for your need.
7. Click __OK__.
8. Back to __Project home__, click __Translation__, double-click a file to open the editor.
9. In the __Translation results__ pane, insert and edit an MT result suggested by the DeepL plugin for a segment. For how to use MT results, see [Use translation results](docs.memoq.com/current/en/Places/translation-editor.html).

## Use the DeepL Pro plugin for pre-translation

1. Go to __MT settings__, following the second option for Step 2 in [Set up the DeepL Pro plugin](#set-up-the-deepl-pro-plugin).
2. Go to the __Service__ tab, following Step 3-5 in [Use the DeepL Pro Plugin in the editor](#use-the-deepl-pro-plugin-in-the-editor), then select the DeepL MT Plugin.
3. In the __Settings__ tab, for __Pre-translation__, select the DeepL Pro plugin from the dropdown list.
4. Click __OK__.
5. Back to __Project home__, On the top of memoQ dashboard, click __Preparation__, then __Pre-translate__.
6. In the popup window, check __Use machine translation if there is no TM or corpus match__ to use machine translations.
7. Click __OK__.

Note: You can also do Step 5-7 above in the translation editor.

For further information about how to use the plugin, see [DeepL MT plugin settings](docs.memoq.com/current/en/Places/deepl-mt-plugin-settings.html) from the memoQ support.

_Source_: [How can I use DeepL Pro in memoQ 8.5 or higher?](support.deepl.com/hc/en-us/articles/360020709539-DeepL-for-memoQ-8-5-or-higher)
