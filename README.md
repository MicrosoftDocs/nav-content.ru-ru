# nav-content
Welcome to the repository for the application help content for Dynamics NAV! Dynamics NAV is aimed at small and midsized businesses, and this repo gives you access to the source files that are used to build the application help that is shipped as part of the Help Server with Dynamics NAV. This repo enables you to take the Dynamics NAV help and customize it to suit your application. It also provides a way for you to actively contribute to the current Dynamics NAV content.

The content is available as markdown files (.md), where each file represents an article in the help. You can edit these markdown files, and then convert them to HTML files for application.

There are different repos in GitHub for the source content and each of the languages that Microsoft translates to. The *nav-content* repo contains the content in English (US). If you want access to the content in other languages, navigate to the relevant repo - the names follow this pattern: *nav-content.<language>-<country>*, such as [nav-content.da-DK](https://github.com/MicrosoftDocs/nav-content.da-DK) for the Danish version.

**NOTE**: Microsoft accepts pull requests to the *nav-content* repo only, not the language-specific repos. If you have feedback about translations, you can report a GitHub issue in the relevant repo.

The *live* branch has been updated in preparation for the upcoming release of Dynamics NAV 2018. If you want to source files for Dynamics NAV 2017, see the *Release* tab.

If you have any questions, please contact the Dynamics NAV User Assistance (UA) team at nav-olh@microsoft.com.

## Getting Started
1. Fork this repo

    You cannot work directly in the nav-content repo, so the first thing you need to do is create a fork of the repo under your GitHub account. A fork basically is copy of this repo that lets you work freely on the content without affecting the nav-content repo. For more information, see [Fork a Repo] (https://help.github.com/articles/fork-a-repo/)

2.  Install GitHub Desktop (optional) and clone your forked repo.

    GitHub Desktop makes is easy to work and collaborate with repos locally from your own desktop. For more information, see [GitHub Desktop](https://desktop.github.com/).   

2. Get hold of your favorite MarkDown editor, and start making changes.

    The help content is stored in the articles folder of the repo. Articles use a syntax for formatting text called GitHub Flavored Markdown. To learn more about working with markdown, see [Getting started with writing and formatting on GitHub](https://help.github.com/articles/getting-started-with-writing-and-formatting-on-github/).

3. Build the HTML files for the Dynamics NAV Help Server.


## Building the HTML files from the markdown files
One way you can build the HTML files is by using DocFX, which is an open source tool for converting markdown files. This section provides some guidance on how you can use DocFX to publish HTML files that use the same style as Dynamics NAV content.

1.  Install DocFX on your computer.

    For more information, see [DocFx](https://dotnet.github.io/docfx/).

2.  Specify the output folder in which to store the generated HTML files.

    By default the files will be saved in the folder *c:/output*. The output folder is set in the NAVdocfx.json file. If you want to change this folder, do the following:

    a. In the folder *[clone path]\nav-content\dynamics-nav-app\*, open the NAVdocfx.json file in your editor.  
    b.  Set the "dest:" parameter to your output folder, and save the changes.  

3.  Go to your desktop and open a command prompt.

3.  Go to the docfx installation folder.

4.  Run the following command:
    ```
    docfx "[clone path]\nav-content\dynamics-nav-app\NAVdocfx.json"'
    ```

The files are generated as .html files and stored in the specified output.

## Contributing to Dynamics NAV content
A benefit of GitHub is the ability for you to contribute to the core content that the Dynamics NAV UA team provides in the nav-content repo. For example, you might have a new article that you think would be beneficial or you might have a correction to an existing article. If you would like to contribute to the nav-content repo, you create what is called a *pull request* from your repo to the nav-content repo. The Dynamics NAV UA team will then review the request and include the changes as appropriate.

For example, to create a pull request to the nav-content repo by using GitHub Desktop, do the following:

1.  Commit the changes to your repo that you want to include in the pull request.
2.  Choose **Sync** to push the changes up to your repo on GitHub.
3.  When the sync is completed, choose **Pull Request**, and then choose send **Pull Request**.

**NOTE**: Microsoft accepts pull requests to the nav-content repo only, not the language-specific repos. If you have feedback about translations, you can report a GitHub issue in the relevant repo.

## Markdown Best Practices

### Properties and tags in articles
All topics should start with a YAML header with the title and author attributes as shown in the following example.

```
---
title: "How to: Change the Role Center"
author: MyGitHubAccount
---
```

### Headings
Use ```#``` for headings.

Examples:
```#``` Heading 1, looks like:
# Heading 1

```##``` Heading 2, looks like:
## Heading 2

```###``` Heading 3, looks like:
### Heading 3


### Bulleted lists
Use - to create bullets, for example:

The following options are available:
```
- first option
- second option
- third option
```

### Ordered lists
Use numbers for ordered lists. No space between the lines, we'll let the template take care of that.

```
1. In the **Search** box, enter **Payment Journal**, and then choose the related link.
2. In the **Payment Journal** window, on the first journal line, enter the relevant information about the payment entry.
3. To apply a single vendor ledger entry:
4. In the **Applies-to Doc. No.** field, choose the field to open the **Apply Vendor Entries** window.
```

### Bold and italics syntax
Use ```**bold**``` and ```*italics*```

### Tables
- For tables in the body, use the markdown syntax.

```
| To   | See                       |
|------|---------------------------|
|<text>|<link>|
| | |
| | |
```

- For nested tables in ordered and unordered lists use HTML-syntax. Markdown does not support tables very well. If you use the markdown syntax the list will be broken, the table will align left and list will be renumbered.

### Comment syntax
Useful for sections that are not ready and will not pass the build check.
```
<!-- Comments -->
```
Examples
```
<!-- [Managing Payables](payables-manage-payables.md)-->
<!-- This is a paragraph that spans more lines and I can just put the comment tag
at the beginning and end of it -->
```
### Links
Ordinary link to a different topic in the same folder

These links have the format ```[link text](filename.md)```.

Example:
```[Managing Payables](payables-manage-payables.md)```


### Link to a topic in a subfolder of the source topic

These links have the format ```[link text](subfolder/filename.md)```.

For example, you want to link to payables-manage-payables.md from ui-work-general-journals.md, where the folder structure is as follows:

- articles
    - ui-work-general-journals.md
- ManagePayables
    - payables-manage-payables.md

Here is the link:
```[Manage Payables](ManagePayables/payables-manage-payables.md)```

### Link to a topic in a different folder than source topic

These links have the format ```[link text](../folder/filename.md)```.

For example, you want to link to payables-manage-payables.md from receivables-manage-receivables.md, where the folder structure is as follows:

- articles
    - ManageReceivables
        - receivables-manage-receivables.md
    - ui-work-general-journals.md
    - ManagePayables
        - payables-manage-payables.md

Here is the link:
```[Manage Payables](../ManagePayables/payables-manage-payables.md)```

### Link to a place in the same article
From within an article, you can create a link to a specific heading in the same article. You can create the link like other links except with the following format:

```[link text](#target-heading)```

target-heading is the text of the heading that you want to link to, except it is all lowercase and spaces between words are replaced with hyphens. For example, here is the link:
```[How Autoscaling Works](#how-autoscaling-works)```

To the heading:
```## How Autoscaling Works```

### Link to a place in a different article
From an article, you can create a link to a specific heading in another article. You can create the link like other links except with the following format:

```[link text](targetarticlename#target-heading)```

targetarticlename is the file name of the article, including the .md file type.
target-heading is the text of the heading that you want to link to, except it is all lowercase and spaces between words are replaced with hyphens.

For example, to link to the heading "How Autoscaling Works" in the article Autoscaling.md", add the following code:
```[link text](Autoscaling.md#how-autoscaling-works)```

### Line breaks (soft return)
In the editor, add two blank spaces at the end of the sentence and hit return. This is used in the See Also list. (See Also must be heading 2.)

### Continue steps after a non-step para
Enter four spaces in front of the non-step para. Otherwise, the non-step para will restart the step sequence.

### TOC
This repo contains two TOC files. One is in MarkDown format and the other is in XML format. For the Dynamics NAV Help Server, you must use the XML file. For more information, see [Microsoft Dynamics NAV Help Server](https://msdn.microsoft.com/en-us/dynamics-nav/microsoft-dynamics-nav-help-server).

### Standard Phrases
All fields in Dynamics NAV have tooltips. Therefore, do not document fields in Help. To refer readers to the tooltips, use this standard phrase where relevant:    
"Choose a field to read a short description of the field or link to more information."
**Note**: The product name is represented by placeholders, called INCLUDES. In most cases, use the short name for the product, "Dynamics NAV", and use this placeholder: ```[!INCLUDE[d365fin](includes/d365fin_md.md)]```. As you can see, this is the placeholder for the online version of Dynamics NAV, but due to translation costs, we have chosen to use the same placeholder for Dynamics NAV but change the value of it in the *includes* folder.

### File naming

#### Rules
- No spaces or punctuation characters. Use hyphens to separate the words in the file name.
- Use all lowercase letters
- No more than 80 characters
- Use action verbs that are specific such as develop, buy, build, troubleshoot. No -ing words.
- No small words - don't include a, and, the, in, or, etc.
- Country-specific article file names are prefixed with the country code. Example: "ca-" for Canada.
- All files must be in markdown and use the .md file extension.

#### Examples

|Topic title |Naming  |
|------------|--------|
|How to: Select a Company|ui-how-select-company.md|
|Enter Criteria in Filters|ui-enter-criteria-filters.md|
|Troubleshooting: Record Locked by Another User|ui-troubleshoot-record-locked-another-user.md|
|Changing Role Center|ui-change-role-center.md|
|Set Up Currencies|finance-setup-currencies.md|
|How to: Set Up Purchasers|purchases-how-setup-purchasers.md|
|Understanding Session Timeouts|admin-understand-session-timeouts.md|
|Manage Data Encryption|admin-manage-data-encryption.md|
|How to: Work With GIFI Codes in Canada|ca-finance-work-GiFI-codes.md|

Naming consists of the following elements: ```<country prefix>-<category prefix>-<topic title>.<extension>```

### Country-specific content
To simplify content localization and translation, country-specific articles live in the same folder ```/dynamics-nav-app``` as the articles for the generic product. We distinguish country-specific article file names by a country prefix. However, we are moving towards having local functionality descriptions in country-specific subfolders under ```/dynamics-nav-app/LocalFunctionality```.

## Code of Conduct
This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.
