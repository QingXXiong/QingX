
----

Stat:

1. Who are you?

- You are a translator with unknown experience using online CAT tools

2. What do you have? (exp/skills)

- You are familiar with translation basics
- You don't know, or you are unfamiliar with how to use Smartcat

3. What do you want from me?

- You need info about using Smartcat for translation

4. What's my purpose?

- Show how to use Smartcat for translation, need to cover common parts for translation and commonly used actions in the editors, +/- provide troubleshooting info.

----

# Use Smartcat for translation

## What's inside

- Overview
- Create a project
- Work with the Smartcat editor
- Set up your translation memory
- Set up your glossary
- Work with machine translation

## Overview

In this tutorial, we describe how to use the Smartcat tool for:

- Creating a project for your client's work with Smartcat.
- Learning the key features in the Smartcat editor for quality and efficiency.
- Setting up machine translation, translation memories, and glossaries for productivity.

Before you start, you need:

- A Smartcat account for translators, or else create it [here](smartcat.com/app/sign-up).
- A basic knowledge about translation, like source and target languages, handling translation segments.
- A bit of experience using [web apps](techtarget.com/searchsoftwarequality/definition/Web-application-Web-app).
- A sample document in PDF, DOCX, or [a file format supported by Smartcat](help.smartcat.com/translating-files-in-different-formats/1539645-file-formats-supported-in-smartcat?).

## Create a project

### Upload files

1. [Sign in](smartcat.com/app/sign-in) to your account.
2. In the dashboard, click __Tasks__, then you'll go to the __My tasks__ page.
3. Click __Create a project__.
4. Upload your sample.

In the __New project__ page, you'll see your sample uploaded. If you failed to upload, check out [File upload issues](help.smartcat.com/translating-files-in-different-formats/1539144-cannot-upload-a-file-to-a-project?).

Next to the document's name, Click the wheel icon, and you'll see a bunch of options available based on your file format. You can check these options as needed, so Smartcat knows how to prepare your file, like splitting into segments, including translatable elements. Lots of the times, you can use the preset settings, or else check [Settings for uploading popular file formats](help.smartcat.com/translating-files-in-different-formats/1539832-settings-for-uploading-popular-file-formats?).

Ignore the __Do no parse__ option.

For __Translation Memories__, upload your memory in TMX or SDLTM format. If you don't know about translation memory, now, just leave it alone.

Under __Reference file__, add reference files, like style guides, source documents, or any files helpful to translation.

To add more documents for translation, a translation memory, or a reference file, click __ADD__. To remove any file, hover over the file name, you'll see a bin icon, click it to remove.

Now, click __NEXT__, and go to the __New project__ page, there it's about project settings. Click __BACK__ if needed, and you won't lose anything already done.

### Customize settings for your project

Customize these settings:

1. For __Project name__, enter a name for your project. The default is your file's name.
2. For __Deadline__, choose the date for delivery. Note you can specify hours and minutes, which is handy for a tight deadline. Click the deadline or the cross icon to re-specify.
3. For __Source language__ and __Target language__, select _one_ source and _one or multiple_ targets from the dropdown lists. You can enter a language to search.
4. For __comments__, enter any useful information, like project instructions, notes, or queries.

For __Use machine translation__, check this option if you need a reference for understanding the source or translation speed. If you know little about machine translation, now, just leave it alone.

Under __Advanced settings__, We have:

1. __TRANSLATION MEMORIES__.
2. __GLOSSARIES__.
3. __QUALITY ASSURANCE__, it's a list of low-level errors for QA. Select as needed. For each error, you have three options:

   a. __Ignore errors__, do nothing. Enable it for errors that are inapplicable to your project. Say, no space needed in the target

   b. __Notify about errors__, display a warning. Enable it for errors that require attention but may be a false alarm. Say, no number needed in the target, although the source has.

   c. __Require error correction__, need actions. Enable it for errors requiring actions for translation quality. Say, wrong spelling of a well-known acronym.

4. __PRE-TRANSLATION__.

Now, click __Finish__ to create your project. Then you'll go to the project page.

### Navigate the project page

Once created, a project will appear on the __My Tasks__ page with __Status__ as __Created__. You can access project settings by either:

1. Hovering over your project and clicking __go to project__.
2. Clicking your project.

With more to talk, we follow Step 1. Everything is the same if you follow Step 2.

The project page falls into these tabs:

- Settings, where you can change project settings.
- Files, where you can manage files for translation, say, downloading translated documents, deleting a file.
- Statistics, where you can view and download a report about this project.
- Linguistic assets, where you can manage translation memories, machine translation and glossaries.
- Pre-translation, where you can set up rules for automatic translation.

Here are the things you need now:

- If you need a QA report for your documents, go to __Settings__ > __QA Check__. Here you can run and download a QA check for specified documents.
- If you need to update your translations with a new version, go to __Files__ > Select the document to be updated > __UPLOAD__ > __Update translation__.
- If you need to download translations, select the translated document, then click the download icon. We often use these options:

  - TMX.
  - XLIFF.
  - Bilingual DOCX.
  - Resulting files.

Remember TMX and XLIFF are file formats to store and exchange translations. Click the download icon > __Special formats__ > __TMX__ > __Export as__. In the pop window, you have:

- __Include tags?__. We use tags to keep stuff like formats and codes. You can treat tags as buttons and move around (not click) them for anything like bold and italics. Select this option if you don't need a final translation.
- __Export mode__. Choose which version of Trados for your TMX file. Learn more about Trados [here](trados.com).

A bilingual DOCX file is a Word document with the source and target side by side in a table.

## Work with the Smartcat editor

To access the editor, you can either:

- On the project page, click a file.
- On the __My tasks__ page, click a project, hover over a file, then click __Open__.

The Smartcat editor falls into four key sections you commonly use for translation:

- Translation editor.
- Toolbar.
- CAT panel.
- Settings.

### Translation editor

To use the Translation editor:

- Under the source column, click a source segment to insert a translation in the target column.
- Next to the translation, click the tick icon or command/control + enter to confirm the current translation.
- In the editor's top left corner, click __Search source__ or __Search target__ to search stuff.
- In the top right corner, click __Add filter__ to filter segments with specified conditions. We often use __Segment status__ to check the translation status and locked segments. For other options, see [Filtering segments](help.smartcat.com/editor/1539659-filtering-segments?).
- Click the download icon, and you can see download options as we talk in [Navigate the project page](#navigate-the-project-page).
- Click __Done__ to deliver your job. If you have unconfirmed segments, the __Done__ button will be gray.

### CAT panel

The CAT (Computer-aided translation) panel consists of the tabs:

- Suggestions: results from machine translation, matches in translation memories, and terms in glossaries.
- Concordance search: search in the source and target.
- Revisions: the revised version of your translation for a segment.
- QA checks: issues by the rules you set up previously.
- Segment comments: your comments for a segment.
- Document comments: your comments for the document.
- Preview: the real-time, in-editor view of your translated document. Click three dots in the top right corner of tab to preview in a new browser window.

Later We'll be back to __Suggestions__ tab. For other tabs, if you need more information, see [CAT Panel](/help.smartcat.com/editor/1539449-editor-functionalities-overview?)

### Toolbar

We'll walk through the toolbar from left to right with a table.

| Name | What can you do   | shortcut |
| :--- | :---              | :---     |
| Confirm all segments | Set all segments as Confirmed | command/control + enter |
| Lock segments | don't allow editing for segments | click a segment|
| Go to the next unconfirmed segment | check unconfirmed segments | F9 |
| Go to a segment by number | enter a segment number in the dialog | command/control + G |
| Undo the last action | don't do the last action | command/control + Z |
| Redo the last action | do the last action again | command/control + shift + Z |
| Copy source to target | keep the source as the translation for a segment or for all empty segments | command/control + shift + S |
| Clear target | remove the current translation for a segment or all translated segments | command/control + left arrow |
| Replace | replace something in all target segments | command/control + H |
| Insert a special character | insert a character you can't type quickly | command/control + shift + H |
| Change the case | capitalize letters | command/control + shift + F3 |
| Change a tag | put a tag into your translation | command/control + F8 |
| Segment length limit | specify how many characters for all segment regardless which languages | command/control + shift + L |
| Revert the segment to the previous stage | roll back the current version of translation to the last one | command/control + shift + R |
| Open the custom dictionary | check your dictionary if any, otherwise you can add one | command/control + option + T |
| Concordance search | search the source and target | command/control + K |
| Select the segments you want to merge | merge two more segments, you need to split segments before merging them | click this option and hold control, then select the segments |
| Split the segment | break one segment into two | put your cursor on a segment, then click this option |

These actions are everyday things for a translator and are essential for speed and quality. You need to master at least the first ten actions.

In the top of the toolbar, from left to right, you can:

- Click the Smartcat logo, and you can get back to:

  - The project page by clicking __Back to project__.
  - The Smartcat home page by __Home page__.
  - The task list page by __Projects__.
- Click the project name, and switch among projects available.
- Click the language pair, and switch among the pairs available.
- Click the file name, and switch among files available.
- Check your translation progress for words translated and percentage.

### Settings

In the top right corner of editor page, hover over find __Settings__. Here you can customize:

- Editor settings.
- Dark mode.
- Full screen.
- View: layout of the CAT panel.

Don't confuse __Editor settings__ with __Settings__. Remember the __Auto-insertion__ and __Auto-propagation__ tabs under __Editor settings__. For other options, try changing them to see what fits for you.

## Set up your translation memory

When you are a kid, remembering things are easy. But as you grow older, you probably will say "darn, I forget it" a lot. Now, you need a note pad or something as a reminder.

A translation memory \(TM\) is such a note pad. You translate something, it gets reviewed and passed. You want to reuse it for other projects, how can you do? Yeah, you put it into a TM.

A TM is handy for:

- Reusing translations for consistency in the same project.
- Reusing translations for speed across different projects.
- Providing references of how to translate similar sources.

Remember TMX we talked about before? If a TM is a note pad, then the TMX format is indeed a set of rules for writing on the pad. You may see a different rule like XLIFF, but TMX is universal and compatible with many popular tools.

### Create a translation memory

To create a standalone TM:

1. Go to the Smartcat dashboard.
2. Click __Linguistic assets__.
3. In the top right corner, click the box and switch to __Translation Memories__.
4. Click __CREATE TM__.
5. In the popup window:

   - Upload a file in TMX, SDLTM or XLSX if you have one.
   - For __Name__, enter a name for your TM.
   - For __Source language__ and __target languages__, select from the dropdown list.
   - For __Subject__, select from the dropdown list.
   - For __Comment__, enter anything as needed.

6. Click __Save__ to create your TM. You'll see your TM in the list.
7. Click your TM from the list, then you can:

   - __Overwrite TM__ or __Update TM__ by uploading a file.
   - __Export__ your TM to your computer.
   - __DELETE__ your TM and __EDIT__ settings above. You can only edit a TM's name here.

To add a TM to your project:

1. Go to your project page.
2. Under __Linguistic assets__, click the __Add__ box.
3. Choose __Select an existing TM__.
4. Select the TM you created before. Note a TM's language pair must match a project's.
5. Click __Add__, and you'll see the TM in the list.
6. Under __Disable__, click the cross icon to remove the TM.

If you want to use your TM for language variants, enable __With dialects__ for your TM.

When a source segment in a project has 75% words same/similar to the one in TM, we say the segment has _75% match_. Choose __Threshold__ to set a minimum match as needed. What about a match > 100%? Well, it means two segments are exactly the same and also have one or more same neighbor segment.

For __Write__, if you have multiple TMs, choose which one to save new translations. Note you can only select the TM you created for the project.

You can also upload a TM under __Translation Memories__ as we talk about in [Upload files](#upload-files).

To create a TM for a project, you can:

Either:

- Go to __Advanced settings__ as we talk about in [Customize settings for your project](#customize-settings-for-your-project).
- Choose __Select an existing TM__ you created before. Or choose __Create a new TM__ to auto-create a TM with __Minimum match__.

Or:

- Go to the __Linguistic assets__ tab from the project page.
- Click the __Add__ box, then click __Add new__ or __Upload__. Then everything is the same as we do in the section _To create a standalone TM_.

### Work with a translation memory

Once adding a TM to your project, go to the Smartcat editor and click a segment. Under the __Suggestions__ tab of CAT panel, if Smartcat finds a match meeting the threshold you specified, you'll see that result labeled as TM and the matched part.

In the editor, go to __Editor settings__ > __Auto-insertion__. The __Insert TM matches no less than:__ option is the same as __Threshold__ you specified before. This option means auto-inserting a translation with TM match >= a value. If you're sure about a translation with exactly the same source, select __Confirm 100% matches or higher__.

We bring up a buddy of TM match – _repetition_. A repetition means two or more segments in a project (probably in a file) are exactly the same. Looks like a repetition are a > 100% TM match. You think this way if one of repetition is translated and confirmed into your TM.

We call auto-inserting repetitions _Propagation_. For both TM matches and repetitions, remember exactly the same segments might have different translations.

Under the __Auto-propagation__ tab, you can handle repetitions by setting up these options:

- __Enable auto-propagation__: select to auto-insert repetitions. For __Direction__ in a file:

  - __Backward and forward__ means using one translation for all the repetitions.
  - __Forward only__ means using one translation for the following repetitions.

- __Propagate to segments with different case usages__: select to handle inconsistent cases once they are propagated.

  - __Use the original case__ means using the case of source for the repetition.
  - __Use the case of the match__ means using one case for all the repetitions.

- __Propagate to confirmed segments__: select to update repetitions even they are confirmed.
- __Confirm auto-propagated segments__: select to auto-confirm repetitions.

Propagation also has a buddy, called pre-translation, we'll talk about it later.

## Set up your glossary

Think of a glossary as a dictionary for a subject and terms as words, then you can find definitions, examples, or translations for a term. We use glossary to ensure accuracy and consistency.

To create a standalone glossary:

1. Go to the __Linguistic assets__ tab.
2. In the top right corner, click the box and switch to __Translation Memories__.
3. Click __CREATE GLOSSARY__.
4. In the popup window:
  
   - Under __Glossary name__, enter a name for your glossary.
   - Under __Language 1__, select a language your glossary use. Click the plus sign to add more languages.
   - Under __Comments__, enter any helpful information.

5. Click __Save__ to create your glossary. You'll see your glossary created in a moment.

Click __Back__ in the top, and you'll see your glossary in the list. Click your glossary from the list to manage.

In your glossary page:

- Click __ADD ENTRY__ to add a term. Under each field, enter things as needed. If you click the plus icon in a field, you can add multiple versions for the same entry. You need this if a term has multiple translations or definitions. Click the tick icon to save and the cross icon to remove an entry.

- Click __UPLOAD__ to import terms into your glossary. In the popup window, choose a file in XML or XLSX, select __Add terms__, then click __IMPORT__. But how? See below. Select __replace all terms__ to update all terms in the glossary with a new version.

- Click __DOWNLOAD__ to export your glossary in XLSX. You'll see a message telling you can download. Notice something? If you have no clue about setting up glossaries in XML or XLSX, use this option to get a template for the __UPLOAD__ option. Download this template before uploading to avoid errors.

- Click the wheel icon, you can:

  - Under __Glossary properties__, change the settings you did before or delete the glossary.
  - Under __Glossary structures__, manage the fields for your glossary.

As a translator, you might not need many complex options under __Glossary structures__. The default fields are enough. But if you want to know more, check out [Structure of glossary](help.smartcat.com/glossaries/properties-and-structure-of-glossary/).

To add a glossary to a project:

1. Go to the project page.
2. Under __Linguistic assets__, go to __Glossaries__.
3. From the list of glossaries, check which one to use.
4. For __With dialects__, enable if you want to use the glossary for language variants.
5. Click __SAVE__ to confirm.

### Work with a glossary

Once adding a glossary to your project, go to the Smartcat editor and click a source segment. Under the __Suggestions__ tab of CAT panel, if a term is in the glossary, you'll see the entries labeled with TB (termbase) and the terms highlighted in that segment.

Click an entry to check out the fields on the right. Click __Edit__ to edit your terms and __Go to terms__ to go to the glossary page.

If you want to insert the translation of a term, put your cursor on where to insert, then click the entry for that term under __Suggestions__.

## Work with machine translation

You may think machine translation = Google Translate? Partly it's correct, we rely on machine translation (MT) to handle a large volume of work quickly without putting down quality. However, translation memories and glossaries are also big parts of MT. Also, here comes AI that can learn and predict.

You need a translation service or engine (Google Translate is one) to get MT. You can:

1. Click __Productivity services__.
2. Click __Machine translation__.
3. In the popup window, under __Page__, choose __20__ or more. This allows you to auto-translate 50,000 words.
4. Click __Buy__, you'll see a __Confirm your purchase__ window.
5. Click __CARD OR PAYPAL__, then choose a way to pay. You can also pay via bank transfer.

Once done, you'll be back to the __Productivity services__ page. Under __Machine translation__, check your balance.

What about you don't want to pay? Here is how:

1. Go to the project page.
2. Under __Machine translation__ of the __Linguistic assets__ tab, select __Use for free with feedback__. Note choosing this option means you'll share data with an MT service.
3. To the right, click the wheel icon, and you can add a language _only_ under __Yandex Free__.
4. Add __Save&Run__.

If you bought the pages, do:

1. To the right of __Paid service__, click the wheel icon.
2. Choose one or more translation engine you like.
3. Click __Add__ to add a target language the translation engine supports.
4. Click __SAVE&RUN__.

Now back to the project page, click a file. In the editor, click a segment, and under the __Suggestions__ tab, you'll see MT entries labeled with MT.

Click the pencil icon to view the MT result along with the MT service info. Click to insert an MT result for a source segment.

### Run pre-translation

Pre-translation allows you to use your TM and MT (don't mix them up) together. Even better, you can specify how to auto-translate a segment with only numbers.

To run pre-translation for a project, you can:

1. Go to the project page.
2. Under the __Pretranslation__ tab, choose where you want to insert a translation.
3. For __SOURCE(NUMBERS ONLY)__, choose to auto-translate a segment with only numbers, that's, copy the source to the target.
4. Click __ADD RULE__ > __TRANSLATION MEMORIES__ to add a TM for auto-inserting.

   - Under __Translation Memories__, choose a memory from the dropdown list.
   - For __Minimum match percentage__, choose a match value, so only auto-insert translation for a source segment with the value or higher. If you're confident about the TM, choose a higher value, say, 90%. Otherwise, set a lower value to avoid errors.
   - For __Minimum TM segment Quality__, choose which matched translation version to use. We often use _Reviewed_ or _Professionally edited_ for quality.
   - For __Minimum word count in a segment__, choose a number of words so only auto-insert translation for segments with the value or higher.

5. Click __ADD RULE__ > __TRANSLATION MEMORIES__ to add MT.
6. Select __Confirm segment__ to auto-confirm a segment once it has translation inserted.
7. Click __SAVE&RUN__ to save the rules and run pre-translation, otherwise, click __SAVE ONLY__.