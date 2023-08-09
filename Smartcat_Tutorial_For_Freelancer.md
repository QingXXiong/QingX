
----

Stat:

1. Who are you?

- You are a translator with unknown experience using online CAT tools.

2. What do you have? (exp/skills)

- You know translation basics like source and target languages.
- You know little or a little about how to use Smartcat.

3. What do you want from me?

- You want to know about using Smartcat for translation.

4. What can I do for you?

- Show how to use Smartcat for translation: cover common features for translation and common actions in the editors, +/- provide troubleshooting info.

----

# Use Smartcat for translation

## What's inside

- Overview
- Create your project
- Work with the Smartcat editor
- Set up your translation memory
- Set up your glossary
- Work with machine translation
- 

## Overview

In this tutorial, we describe how to use the Smartcat tool for:

- Creating a project for your client's job.
- Learning key features in the Smartcat editor for quality and efficiency.
- Setting up machine translation, translation memories, and glossaries for productivity.

Before starting, you need:

- A Smartcat account for translators, or else create it [here](smartcat.com/app/sign-up).
- A basic knowledge about translation, like source and target languages or handling translation segments.
- A bit of experience using [web apps](techtarget.com/searchsoftwarequality/definition/Web-application-Web-app).
- At least one sample file in PDF, DOCX, or [a file format supported by Smartcat](help.smartcat.com/translating-files-in-different-formats/1539645-file-formats-supported-in-smartcat?).

## Create your project

### Upload files

1. [Sign in](smartcat.com/app/sign-in) to your account.
2. In Smartcat Dashboard, click __Tasks__, to enter the __My tasks__ project list page.
3. Click __CREATE PROJECT__.
4. Click __SELECT A FILE__ to upload your sample.

Note: If you want to create a project template, click __SKIP__.

On the __New project__ page, you'll see the sample uploaded. If you failed to upload, check out [File upload issues](help.smartcat.com/translating-files-in-different-formats/1539144-cannot-upload-a-file-to-a-project?).

Next to the file's name, click the wheel icon to see a bunch of options available based on a file format. Select these options for your need, so Smartcat knows how to prepare your file for translation, like splitting into segments, including translatable elements. Often, you can use the preset settings, or else check [Settings for uploading popular file formats](help.smartcat.com/translating-files-in-different-formats/1539832-settings-for-uploading-popular-file-formats?).

Ignore the __Do not parse__ option.

For __Translation Memories__, upload your memory in TMX or SDLTM format. If you know little about translation memory, leave it alone for now.

For __Reference files__, add reference files, like style guides, source files, or any files helpful to translation.

To add more files for translation, a translation memory, or a reference file, click __ADD__. To remove any file, hold the pointer over a file name, and you'll see a bin icon, then click it to remove.

Now, click __NEXT__, then go to the __New project__ page, there it's about project settings. Click __BACK__ if you need, and you won't lose anything already done.

### Customize settings for your project

Customize these settings:

1. For __Project name__, enter a name for your project. The default is your file's name, if any.
2. For __Deadline__, select the date for delivery. Note you can specify hours and minutes, a handy tool for a tight deadline. Click the deadline or the cross icon to re-specify.
3. For __Source language__ and __Target language__, select _one_ source and _one or more_ targets from the dropdown lists. Enter something in the fields to search for a language.
4. For __comments__, enter any useful information, like project instructions or client's notes.

For __Use machine translation__, if you need a reference for understanding the source or speeding up translating, check this option. If you know little about machine translation, leave it alone for now.

If turning on __Advanced settings__, you have:

1. __TRANSLATION MEMORIES__.
2. __GLOSSARIES__.
3. __QUALITY ASSURANCE__: a list of low-level errors for QA check, select them for your need. For each error, you have three options:

   a. __Ignore errors__: do nothing. Select it for errors inapplicable to your project. Say, no space needed before and after parentheses.

   b. __Notify about errors__: show a warning. Select it for errors that need your attention but may be a false alarm. Say, no number needed in the target though the source has.

   c. __Require error correction__: need actions. Select it for errors you have to correct. Say, wrong spelling of a well-known acronym.

4. __PRE-TRANSLATION__. What's it? Stay tuned!

Now, click __FINISH__ to create your project. Then you'll go to the project page.

### Navigate the project page

After you are done creating a project, it will show on the __My Tasks__ project list page with __Status__ as __Created__. Go to project settings via one of two options:

1. Hold the pointer over your project and click __GO TO PROJECT__ to enter a new project page.
2. Click your project to stay on the same page.

With more things to dive into, we always follow Option 1.

The project page falls into these tabs:

- __Settings__: change the settings you did before.
- __Files__: manage files for translation, say, downloading translated files, deleting files.
- __Statistics__: view and download a word count report about this project's files.
- __Linguistic assets__: manage translation memories, machine translation, and glossaries.
- __Pretranslation__: set up rules for applying automatic translation to a project's source files.

Here are the things to do:

- To run QA and download an error report for your translations:
  - Go to __Settings__ > __QA CHECK__ > select translated files > __Run A CHECK__, then click __CLOSE__ to close the popup windows. In a while, a dialog will pop up to tell you QA is done.
  - Do the same steps as running QA, then click __DOWNLOAD__. Wait until see a message, then click __Download__ to get an error report in XLSX.
- To update your translations: go to __Files__ > Select the file for updating > __UPLOAD__ > __Update translation__, then click __SELECT__ in the new page. After uploading it, click __UPDATE TRANSLATION__.

Note: you need to upload translations in XLIFF.

- To download your translations: select the translated file, then click the download icon. We often use these formats for download translations:

  - TMX.
  - XLIFF.
  - Bilingual DOCX.
  - Resulting files.

Remember, TMX and XLIFF are file formats to store and exchange translations.

Click the download icon > __Special formats__ > __TMX__ > __Export as__. In the pop window:

- __Include tags?__. We use tags to hide stuff like formats and codes. You can treat tags as buttons and move around (not click) them to apply anything like bold and italics to translations. If you don't need final translations, select this option.
- __Export mode__. Select which version of Trados for your TMX file. If you need to know more about Trados, learn more[here](trados.com).

A bilingual DOCX file is a Word file with the source and target side by side in a table. Resulting files are the final translations with the same format, layout, or other things as the sources.

After selecting the above settings, click __EXPORT__ to get your translations.

## Work with the Smartcat editor

To enter the editor, do one of two steps:

- On the project page, click a file.
- On the __My tasks__ project list page, click a project, hold the pointer over a file, then click __OPEN__.

The Smartcat editor falls into four key sections you commonly use for translation:

- The Translation editor.
- The Toolbar.
- The CAT widget.
- The Settings.

### The translation editor

To use the Translation editor:

- Click a segment to enter your translation in the target field.
- Next to a translation, click the tick icon or use `Command` (on macOS) or `Ctrl` (on Windows) + `Enter` to confirm the current segment.
- In the editor's top left corner, click __Search source__ or __Search target__ to search stuff. The thing you enter will show as a label, and click the cross icon to delete it.
- In the top right corner, click __Add filter__ to filter segments by specified criteria. You may often use __Segment status__ to check the translation status and locked segments. For other options, see [Filtering segments](help.smartcat.com/editor/1539659-filtering-segments?).
- Click the download icon to see download options in [Navigate the project page](#navigate-the-project-page).
- Click __Done__ to deliver your job. If you have unconfirmed segments or unsolved QA errors, the __Done__ button will be gray.

### The CAT widget

The CAT (Computer-aided translation) widget at the bottom of editor falls into these tabs:

- __Suggestions__: results from machine translation, matches in translation memories, and terms in glossaries.
- __Concordance search__: search in the source and target from translation memories.
- __Revisions__: the revised version of your translation for a segment.
- __QA checks__: detected issues by the rules you set up before.
- __Segment comments__: your comments for a segment.
- __Document comments__: your comments for the file.
- __Preview__: view the selected segment in the source file for context. Click three dots in the top right corner of tab to preview in a new browser window. In the editor, you can preview translations for _only_ HTML and subtitle files.

Later We'll get back to the __Suggestions__ tab. For more information about using other tabs, see [CAT tabs](help.smartcat.com/editor/1539449-editor-functionalities-overview?).

### Toolbar

For the toolbar at the top of editor, we'll walk through it from left to right with a table.

Things to remember for reading the table:

- "`Command`/`Ctrl` + ..." means `Command` is for macOS and `Ctrl` for Windows, and things following '+' are the same.
- "... or ..." means the shortcut before "or" is for macOS and the shortcut after "or" for Windows.
- The shortcuts in the table are common and useful ways to _start_ using functionalities.

| Functionality | What can you do | shortcut |
| :--- | :--- | :--- |
| Confirm segment | Confirm all or selected segments | hold `Command`/`Ctrl` to select segments, then use `Command`/`Ctrl` + `Enter` |
| Lock segment | don't allow editing segments | hold `Command`/`Ctrl` to select segments, then use `Command` + `Ctrl` + `L` or `Ctrl` + `Alt` + `L`|
| Go to the next unconfirmed segment | check unconfirmed segments | `F9` |
| Go to a segment by number | enter a segment number in the dialog and go to it | `Command`/`Ctrl` + `G` |
| Undo the last action | don't do the last action | `Command`/`Ctrl` + `Z` |
| Redo the last action | do the last action again | `Command` + `Shift` + `Z` or `Ctrl` + `Y` |
| Copy source to target | keep the source as the translation for a segment or for all empty segments | `Command` + `Shift` + `S` or `Ctrl` + `Insert` |
| Clear target | remove the current translation for a segment or all translated segments | `Command` + Left Arrow or `Alt` + `Del` |
| Replace | replace something in all target segments | `Command`/`Ctrl` + `H` |
| AI Actions | get AI suggestions for translating | click it |
| Insert a special character | insert a character you can't type quickly | `Command`/`Ctrl` + `Shift` + `I`|
| Change the case | capitalize letters | `Shift` + `F3` |
| Change a tag | put a tag into your translation | `F8` |
| Segment length limit | specify how many characters for all segment regardless which language | `Command`/`Ctrl` + `Shift` + `L` |
| Revert the segment to the previous stage | roll back the current version of translation to the last one | `Command` `Ctrl` + `R` or `Ctrl` + `Alt` + `R` |
| Open the custom dictionary | view your dictionary if any, otherwise add one | `Command` + `Option` + `T` or `Alt` + `Shift` + `T` |
| Concordance search | search in the source and target form translation memories | `Command`/`Ctrl` + `K` |
| Select the segments you want to merge | merge two more segments, but you need to split segments before merging them | hold `Command`/`Ctrl` to select the segments, then click this option |
| Place the cursor into the source text | break one segment into two, but you need to merge segments before splitting them | put your cursor on a segment, then click this option |

These actions are everyday things for a translator and are essential for speed and quality. You need to master at least the first ten actions.

Above the toolbar, from left to right:

- Click the Smartcat logo, then get back to:

  - The project page by clicking __Back to project__.
  - Smartcat Dashboard by __Home page__.
  - The __My Tasks__ project list page by __Projects__.
- Click the project name, and switch among projects available.
- Click the language pair, and switch among the pairs available.
- Click the file name, and switch among files available.
- Check your translation progress for words translated and percentage.

### Settings

In the top right corner of editor page, hold the pointer over __Settings__. Here you can customize:

- __Editor settings__: set up how the editor works for translation.
- __Dark mode__: turn on a dark look for all-nighters.
- __Fullscreen__: enter into a full-screen editor.
- __VIEW__: change the layout of CAT widget.

Don't confuse __Editor settings__ with __Settings__. Remember the __Auto-insertion__ and __Auto-propagation__ tabs in __Editor settings__. For other options, try changing them to see what fits you.

Click the question mark to view the help page. Heads-up: Smartcat might mess up its docs because some topics on the help page are not for translators and may be hard to get ideas.

## Set up your translation memory

When you are a kid, remembering things is easy. But growing older, you probably will say, "Darn, I forget it" a lot. What can you do? You need a notepad or something as a memory cue.

A translation memory \(TM\) is such a notepad. You translated something, and someone reviewed and approved it. It's good, now you want to reuse it for other projects. How can you do? Yeah, you put it into a TM.

A TM is handy for:

- Reusing translations for consistency in the same project.
- Reusing translations for speed and quality across different projects.
- Providing references on how to translate similar sources.

Remember TMX we talked about before? If a TM is a notepad, then the TMX format is a set of rules for writing on the pad, so you can easily find stuff. You may see a different rule like XLIFF, but TMX is universal and compatible with many popular CAT tools like Smartcat.

### Create a translation memory

To create a standalone TM:

1. Go to Smartcat Dashboard.
2. Click __Linguistic assets__.
3. In the top left corner of __My Linguistic assets__ page, ensure __Translation Memories__ is showing.
4. Click __CREATE TM__.
5. In the popup window:

   - For __TMX, SDLTM or XLSX file__, upload a TM file in TMX, SDLTM or XLSX. Leave it alone if you don't have any.
   - For __Name__, enter a name for your TM.
   - For __Source language__ and __target languages__, select from the dropdown list.
   - For __Subject__, select from the dropdown list.
   - For __Comment__, enter anything useful.

6. Click __Save__ to create your TM. In a while, your TM will show in the TM list.
7. Click your TM in the list to see these options:

   - __OVERWRITE TM__ or __UPDATE TM__ by uploading a file.
   - __EXPORT__ the TM to your computer. When exporting, selecting __Select export mode__ will show the same option as exporting translations.
   - __DELETE__ your TM and __EDIT__ settings done in Step 5.

To add a TM to your project:

1. Go to your project page, then __Linguistic assets__.
2. In the tab, click the __ADD__ button.
3. Select __Select an existing TM__.
4. Select the TM you created before. Note a TM's language pair must match a project's.
5. Click __ADD__ to see the TM in the list.
6. For __Disable__ on the right, click the cross icon to remove the TM from the project.

If you want to use a TM for language variants, turn on __With dialects__ for the TM.

If a segment's source in a file has 75% words same/similar to the one in TM, we say the segment has _75% match_. What about a match > 100%? Well, it means two segments are exactly the same and also have one or more same neighbor segments.

For __Threshold__, select a value to set a minimum match you need for matching precision.

For __Write__, if you have multiple TMs, select which one to save new translations. Only select the TM you created for the project, and don't use a standalone TM.

Note: if turning on __Write__ for a TM, you can't do Step 6 above to it.

You can also upload a TM in the __TRANSLATION MEMORIES__ tab. In the tab, click __ADD__, then select __Select an existing TM__ to add a standalone TM.

To create a TM for a project:

_Either_:

- Go to __Advanced settings__, which we discussed in [Customize settings for your project](#customize-settings-for-your-project).
- Click __ADD__, then select __Create a new TM__ to auto-create a TM with __Minimum match__ and the __Write__ option selected. Click the pencil icon to change the __Minimum match__ value, the same as the __Threshold__ value.

_Or_:

- Go to the __Linguistic assets__ tab from the project page.
- Click the __ADD__ button, then click __Create new__ or __Upload__. After that, everything is the same as you did in the section _To create a standalone TM_.

### Work with a translation memory

After adding a TM to your project, go to the Smartcat editor and click a segment. In the __Suggestions__ tab of CAT widget, if Smartcat finds a matched result meeting the threshold you specified, you'll see that result with a TM label and the match value.

In the editor, go to __Editor settings__ > __Auto-insertion__. The __Insert TM matches no less than:__ option is the same as __Threshold__ you specified before. This option means auto-inserting a translation for a segment with TM match >= a value when you click that segment. If you're sure a translation for the same source has no errors, select __Confirm 100% matches or higher__.

We bring up a buddy of TM match – _repetition_. A repetition means two or more segments in a project (probably in a file) are the same. Looks like a repetition is a >= 100% TM match. Think this way if you translate and confirm one of repetitions into a project TM.

We call __auto-inserting translations for repetitions__ _Propagation_. For both TM matches and repetitions, remember, the same segments might have different translations, especially when you localize software.

Smartcat marks repetitions by placing a down arrow sign in the leftmost place of a segment. If you think a repetition has a different translation, click the down arrow to give that segment a unique translation. Click the down arrow again to let that segment have an auto-inserted translation.

Note: "repetitions" = "segments with the same source."

Go to __Editor settings__ > __Auto-propagation__, and handle repetitions by setting up these options:

- __Enable auto-propagation__: select to auto-insert translations for repetitions. For __Direction__ in a file:

  - __Backward and forward__ means using one translation for all repetitions, no matter which repetition where you edited its translation.
  
     Suppose you have repetitions, A, B, C, D (the same thing is for the below examples). You confirmed all four segments. If selecting this option, editing one of them will update all.

  - __Forward only__ means using one translation for repetitions following the one where you edited its translation.

     You confirmed all four segments. If selecting this option, editing C will update C and D, _not_ A and B.

- __Propagate to segments with different case usages__: select to handle inconsistent cases for auto-inserting translations.

  - __Use the original case__ means using the case of source for each repetition.
  
    A starts with upper case, so does its translation; B starts with lower case, so does its translation.

  - __Use the case of the match__ means using one case for all repetitions.

    Suppose A and B start with upper case, but C and D with lower case. If you translate A first, B, C, and D will start with upper case; if you translate C first, A, B, and D start with lower case.

- __Propagate to confirmed segments__: select to update all repetitions' translations when editing the translation in one of repetitions, whether you confirmed them or not.
  
  You confirmed A, B, C, but not D. If selecting this option, editing B will also let A, C, and D auto-update. Otherwise, only D will auto-update.

  Note: in this case, a confirmed repetition remains confirmed.

- __Confirm auto-propagated segments__: select to auto-confirm repetitions, whether you confirmed them.

Propagation also has a buddy, called pre-translation, and we'll talk about it later.

## Set up your glossary

Think of a glossary as a dictionary for a subject and terms as words, then you can find definitions, examples, or translations for a term. We use a glossary to ensure accuracy and consistency.

To create a standalone glossary:

1. Go to Smartcat Dashboard, then click __Linguistic assets__.
2. In the top left corner of page, click the rounded button and select __Glossaries__.
3. Click __CREATE GLOSSARY__.
4. In the popup window:
  
   - For __Glossary name__, enter a name for your glossary.
   - For __Language 1__, select a language your glossary use. Click the plus sign to add more languages.
   - For __Comments__, enter any helpful information.

5. Click __Save__ to create your glossary. In a while, you'll see the glossary page.

Click __Back__ at the top to see your glossary in the list. Click it to manage.

On the glossary page:

- Click __ADD ENTRY__ to add a term.

  By default, you need to enter terms in different languages and give comments. To add multiple fields for a field name, click the plus icon in the field. You'll need this feature if a term has multiple translations or definitions. Click the tick icon to save an entry and the cross icon to remove.

- Click __UPLOAD__ to import terms into your glossary. In the popup window, select a file in XML or XLSX, select __Add terms__, then click __IMPORT__. Select __replace all terms__ to update all terms in the glossary.

- Click __DOWNLOAD__ to export your glossary in XLSX. You'll see a message telling you can download it.

  Notice something? To set up glossaries in XML or XLSX, click __DOWNLOAD__ to get a template, copy terms into it, then _do_ the __UPLOAD__ action.

Note: you can't change field names in the downloaded XLSX file.

- Click the wheel icon:

  - For __Glossary properties__, change the settings you did before, or delete the glossary.
  - For __Glossary structures__, manage field names and types for your glossary.

As a translator, you may not need complex options in __Glossary structures__. The default field setup is enough. But if you want to know more about setting up field names and types, check out [Structure of glossary](help.smartcat.com/glossaries/properties-and-structure-of-glossary/).

To add a glossary to a project:

1. Go to the project page, then click __Linguistic assets__.
2. In __Glossaries__, from the list of glossaries, select which one to use.
3. For __With dialects__, turn it on to use the glossary for language variants.
4. Click __SAVE__ to confirm.

Smartcat needs time to search for matched terms in a file. So, on the project page, you'll see a progress bar in a file, telling you Smartcat is searching for terms.

Note: if you add glossaries to a project and upload a file, Smartcat will auto-search for terms in the file.

### Work with a glossary

After adding a glossary to your project, go to the Smartcat editor and click a segment. In the __Suggestions__ tab of CAT widget, if a term matches something in the glossary, you'll see the entry with a TB (termbase) label and the highlighted term in the source of that segment.

Click an entry to check out the fields on the right. Click __Edit__ to edit your terms and __Go to terms__ to enter the glossary page.

To insert the translation of a term, put your cursor on where to insert, then click the entry for that term in __Suggestions__.

## Work with machine translation

You may think machine translation = Google Translate. Partly it's correct. We can edit results by machine translation (MT) to make translations more accurate and fluent. Many translators use MT to check whether their translations have errors like mistranslation or to get some ideas about wording.

But translation memories and glossaries are also big parts of MT. Plus, here comes AI that can learn and predict to help you translate, like translating a term right or picking a word that shines.

You need a translation service or engine (Google Translate is one) to get MT up and running. You can:

1. Go to Smartcat Dashboard, then click __Productivity services__.
2. Click __Machine translation__.
3. In the popup window, for __Pages__, select __20__. So, you can auto-translate 5,000 words (250 words per page).
4. Click __BUY__ to see the __Confirm your purchase__ window. Check out whether it's what you need.
5. Click __CARD OR PAYPAL__, then select a way to pay. Ask to pay via bank transfer by writing to [support@smartcat.com](support@smartcat.com).

After that, back to the __Productivity services__ page. For __Machine translation__, check your balance, that's, how many pages you can translate with MT.

What about you don't want to pay? Here is how:

1. Go to the project page.
2. In __Machine translation__ of the __Linguistic assets__ tab, select __Use for free with feedback__. Note choosing this option means you'll share data with an MT service.
3. On the right, click the wheel icon.
4. In __Yandex Free__, click __Add__ to add a target language Yandex supports.

Note: You can only select __Yandex Free__ for free MT.

5. Click __Save&Run__ to translate the project files with MT.

If you bought the pages:

1. On the right of __Paid service__, click the wheel icon.
2. Select one or more translation engines you like.
3. Click __Add__ to add a target language the translation engine supports.
4. Click __SAVE&RUN__.

Smartcat needs time to translate a file with MT. So, on the project page, you'll see a progress bar in a file, telling you Smartcat is applying MT.

Note: when you upload a file to a project with MT on, Smartcat will auto-apply MT to the file.

Now back to the project page, then click a file. In the editor, click a segment, and in the __Suggestions__ tab, you'll see MT entries with an MT label.

Click the pencil icon to view an MT result with the MT source. Click and insert an MT result for a segment's source.

### Run pre-translation

Pre-translation allows you to use your TM and MT (don't mix them up) together. Even better, you can specify how to auto-translate a segment with only numbers.

To run pre-translation for a project, you can:

1. Go to the project page.
2. In the __Pretranslation__ tab, click __ADD RULE__.
3. Select __SOURCE(NUMBERS ONLY)__ to auto-translate a segment with only numbers, that's, copy the source to the target.
4. Click __TRANSLATION MEMORIES__ to add a TM for auto-inserting.

   - For __Translation Memories__, select a TM from the dropdown list.
   - For __Minimum match percentage__, select a match value to only auto-insert translation for a segment with the value or higher.

     If you're confident about the TM, select a lower value, say, 75%. Otherwise, set a higher value to avoid wasting time correcting matched results.

   - For __Minimum TM segment Quality__, select which matched translation version to use.

     You'll often use _Reviewed_ or _Professionally edited_ for better quality. Select these two options if a reviewer edited the translations in your TM.

   - For __Minimum word count in a segment__, select the number of words to only auto-insert translation for segments with the value or higher.

5. Click __MACHINE TRANSLATION__ to add MT.
6. For each rule, select __Confirm segment__ to auto-confirm a segment after it has translation inserted.

   If an inserted translation needs no edits by you, select it to save time.

7. Click __SAVE&RUN__ to save the rules and run pre-translation. Or else click __SAVE ONLY__.

Smartcat applies the rules according to the order you set them. So, always first set a rule for TM and the most trustworthy TM. This way, Smartcat will apply the best translation available.

Note: when you upload a file to a project with pre-translation rules, Smartcat will auto-apply these rules to the file.

Now, go to the editor, then you'll see translations with a label like MT or TM in the target fields.

What about you want pre-translation for only some files? Or you want to use TM but not MT for some files?

Well, first, you need to remove all rules you set up in the __Pretranslation__ tab. Then go to the editor > __Editor settings__ > __Auto-insertion__, for the current file, do these actions in order:

- Select to auto-copy a source with _only numbers and non-alphabetic character_ into the target field.
- Select a match value to only auto-insert translation for a segment with the value or higher.
- Select to auto-insert MT results.

Note: after saving these settings, to auto-insert translation results, you need to click a segment. But pre-translations will auto-insert result segment by segment if a result is available.

Plus setting up glossaries, you have everything ready to start translating with the help of MT.

##