# Contribution Guide

You can contribute to this repository by [adding a new language](#adding-a-new-language) to this repository, or [adding/improving translations](#editing-translation-files) to existing languages. To work with this repository, follow the steps below:

1.  Fork this repository.
1.  Add or modify the files.
1.  Submit a Pull Request so I can marge the changes.

After that, I will do the rest of works to maintain the repository.

##  How this Repository Works

On each release, all `.aul2` files, under each language folder, are concatenated into a single file `<language name>.sigma-axis.aul2`.

Optionally, each language folder can contain a file named `README.md`, which will be included to each release file as the name `<language name>.README.md`. It is intended to contain essential information such as a translated installation guide to users.

##  Adding a New Language

1.  Duplicate the `Template` folder as the name of the language you add (such as `简体中文`).
1.  [Edit the contained `.aul2` files](#editing-translation-files).
1.  Optionally you can add `README.md` to that folder.

Each template `.aul2` file is translated into English. Your work will be to translate them into the new language.

It is *NOT* necessary to translate *ALL* files and entries --- you can leave some and hopefully someone else may translate.

##  Editing Translation Files

1.  Translate lines in `.aul2` file.

    - Each line is of the form `Japanese Parameter Name=Translated Parameter Name`.
    - Do not modify the line of the form `[Japanese Script Name]`.
    - A comment line starts with `#`.

1.  Add your name to the `Translator(s)` at the head of each file.

    - You can also contain an URL to your account or website.

# Thank You

Thank you in advance for your contribution! I appreciate your work so my scripts will be used by more people worldwide.
