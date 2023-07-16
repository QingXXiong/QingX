
----
Stat:

1. Who are you?

- You are a translator, PM, developer, or someone doing translation stuff.

2. What do you have? (exp/skills)

- You have experience using DeepL and memoQ.
- You are familiar with the translation stuff.

3. What do you want from me?
  
- I want to integrate DeepL into memoQ so I can use it for my translation workflow.

4. What's my purpose?

- Show how to integrate DeepL into memoQ for translation

----

# How can I use DeepL Pro in memoQ 8.5 or higher?

## What's inside

- Set up the DeepL Pro plugin
- Use the DeepL Pro plugin in the editor
- Use the DeepL Pro plugin for pre-translation

Before you start, you need:

- A DeepL Pro subscription - Advanced or Ultimate plan, or else get it [here](https://www.deepl.com/pro/select-country?cta=header-prices#team).
- [memoQ 8.5 or higher installed](https://www.memoq.com/products/memoq-translator-pro) with an active license.
- Your Authentication Key for DeepL Pro. To find the key, go to Account > Authentication Key.

## Set up the DeepL Pro plugin

1. Open memoQ.
2. Go to __MT settings__ with either following way:

- In the top left corner, click __Resources console__, on the left of popup window, scroll down to and click __MT settings__.
- Click __Project home__, in the left bottom corner, click __settings__, then in the top, click the __MT settings__ icon.

3. Click __Create/use new__ to create a new MT resource.
4. In the popup window, under __Name__, enter a name for a new MT resource, and under __Description__, describe the resource,
5. Click __OK__.

Note: You need to check a warning about our data privacy.

6. Under __Name/description__, select the entry you created.
7. Click __Edit__ or double-click the entry, then you'll see the __Edit machine translation settings__ window.
8. Under the __Service__ tab, select the DeepL MT Plugin.
9. Click the wheel icon to the right.
10. Under __Authentication Key__, enter your key, then click __Log in__ to verify if you can connect to DeepL.

- If you don't want to keep formatting and tags in the MT suggestions, uncheck __Tranlate with formatting and tags__.

Note: If you check this option, tags in the suggestions might be displaced. Otherwise, you must insert tags manually.

- For __Request format__, choose __XML__ or __HTML__ as the format to send your source.

Note: If you have a problem with the chose format, switch to another one.

- For __Formality__, choose how formal MT suggestions should be. The MT suggestions by DeepL are formal by default.
- For __Glossary__, select one or more glossary to be used with the plugin. For details, see [Using glossaries](https://docs.memoq.com/current/en/Places/deepl-mt-plugin-settings.html?Highlight=Glossary).
- Click __OK__.

## Use the DeepL Pro plugin in the editor

1. Open a project with the language pairs supported.
2. Go to __MT settings__ as described at Step 2 in [Set up the DeepL Pro plugin](#set-up-the-deepl-pro-plugin).
3. Under __Name/description__, select the DeepL plugin entry.
4. Click __Edit__ or double-click the entry.
5. Under the __Service__ of popup window, select the DeepL MT Plugin.
6. Under the __Settings__ tab, set __Translation results__ to an option fit for your need.
7. Click __OK__.
8. Back to __Project home__, under __Translation__, double-click a file to open the editor.
9. In the __Translation results__ pane, click and edit an MT result suggested by the DeepL plugin for a segment. For how to use MT results, see [Use translation results](https://docs.memoq.com/current/en/Places/translation-editor.html).

## Use the DeepL Pro plugin for pre-translation

1. Go to __MT settings__ as described at Step 2 in [Set up the DeepL Pro plugin](#set-up-the-deepl-pro-plugin).
2. Go to the __Settings__ tab as described at Step 3-6 in [Use the DeepL Pro Plugin in the editor](#use-the-deepl-pro-plugin-in-the-editor), select the DeepL MT Plugin.
3. Under __Pre-translation__ of __Settings__ tab, select the DeepL Pro plugin from the dropdown list.
4. Click __OK__.
5. Back to __Project home__, under __Preparation__, click __Pre-translate__.
6. In the popup window, check __Use machine translation if there is no TM or corpus match__.
7. Click __OK__.

Note: You can also do Step 5-7 above in the translation editor.

__Important__: If you have trouble using the DeepL plugin with memoQ 8.5 or higher, ensure your plugin and memoQ are updated, either automatically or manually. For more information, see [Check for updates](https://docs.memoq.com/current/en/Places/check-for-updates.html).

For further information about how to use the plugin, see [DeepL MT plugin settings](https://docs.memoq.com/current/en/Places/deepl-mt-plugin-settings.html) from the memoQ support.

_Source_: [How can I use DeepL Pro in memoQ 8.5 or higher?](https://support.deepl.com/hc/en-us/articles/360020709539-DeepL-for-memoQ-8-5-or-higher)
