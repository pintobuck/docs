---
title: How to Edit Template Text (Gantry 4)
description: How to edit text settings for your RocketTheme template.
breadcrumb: /joomla:Joomla/!basic:Basic Tutorials/!how_to_edit_template_text.md:How to Edit Template Text

---

Introduction
-----
Some words used in our template's frontend are set via the language file for that template. Other commonly modified statements (such as the copyright, Scroll To Top, and Login Panel) are set within Gantry and can be changed through the backend without accessing any files directly.

Below, we will outline the two primary methods for changing custom language strings on our template's frontend.

### Changing the Template Frontend and Backend Text
Words that are used in the template frontend, such as Text Size are set via our language file.

1. Open en-GB.tpl_rt_(template name).ini at:
`<Joomla Root>/templates/rt_(template name)/language/en-GB/(various).ini` The exact name of the file varies by template, though it should be the only **.ini** file in the folder.

2. Change the lower-case text in the listed settings. We have outlined an example below.

~~~
TEXT_SIZE="Text Size"
~~~
Can be changed to:
~~~
TEXT_SIZE="Font Size"
~~~

### Change the Text via Gantry
![][text1]

Some text items are set through Gantry and can be modified in Template Manager. You will just need to navigate to **Administrator → Extensions → Templates Manager** and select your default Gantry-powered template. From there, you can select the **Features** tab and find the appropriate field to modify.

Copyright and To-Top Scroller are two of the most frequently customized fields.

[text1]: assets/text_1.jpg