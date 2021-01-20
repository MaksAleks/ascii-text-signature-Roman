# ASCII Text signature: ASCII New Roman

### Description

Let's increase the font size and use another font that looks very
similar to the real font called "Times New Roman".

The lowercase forms of the first four characters of the Roman alphabet
are shown below in this new font:

```
           .o8                       .o8
          "888                      "888
 .oooo.    888oooo.   .ooooo.   .oooo888
`P  )88b   d88' `88b d88' `"Y8 d88' `888
 .oP"888   888   888 888       888   888
d8(  888   888   888 888   .o8 888   888
`Y888""8o  `Y8bod8P' `Y8bod8P' `Y8bod88P"
```

You can download [this font]() , along with the smaller and less fancy font
from the previous example.

Notice that the width of the letters in this font varies.  
For example, the width of the letter T is 3 characters, and  
for the letter Y, it is 5. You can find the letter boundaries  
by determining spaces in the same positions in all three lines of the
font.

Also, each tag should contain the status of the person wearing it.  
This could be "VIP", "Worker", "Speaker", "Administrator",
"Participant", or something else.These statuses should appear on the
tag, below the person's name.  
This information is not as important as the name, so it should be
printed in a smaller font.

To be readable, every symbol in this font should be separated by a
column of spaces.

You may have noticed that there is no space among these symbols. As
shown in the example below, you should consider a space to be 4 symbols
wide not including spaces between symbols, or 6 symbols wide including
spaces between symbols.

Also, there should be exactly two spaces between the border and the
beginning and end of the name (or status, if it is longer than the
name).

In some cases, the width of the tag may have an even number of symbols
while the status has an odd number of symbols (or vice versa). In these
cases, you cannot generate a status that sits right in the middle, since
it will always be offset by one character on the left or the right. In
this case, your program should move the status to the left so there is
one fewer space to the left of the status than to the right it.

### Output examples

```
Enter name and surname: Bill Gates
Enter person's status: VIP
***************************************************
*  ___  _ _    _         ____ ____ ___ ____ ____  *
*  |__] | |    |         | __ |__|  |  |___ [__   *
*  |__] | |___ |___      |__] |  |  |  |___ ___]  *
*                       VIP                       *
***************************************************
```

```
Enter name and surname: Tom Smith
Enter person's status: Worker
*********************************************
*  ___ ____ _  _      ____ _  _ _ ___ _  _  *
*   |  |  | |\/|      [__  |\/| |  |  |__|  *
*   |  |__| |  |      ___] |  | |  |  |  |  *
*                  Worker                   *
*********************************************
```

```
Enter name and surname: Mr Anonimous
Enter person's status: Participant
**************************************************************
*  _  _ ____      ____ _  _ ____ _  _ _ _  _ ____ _  _ ____  *
*  |\/| |__/      |__| |\ | |  | |\ | | |\/| |  | |  | [__   *
*  |  | |  \      |  | | \| |__| | \| | |  | |__| |__| ___]  *
*                        Participant                         *
**************************************************************
```

```
Enter name and surname: John S
Enter person's status: Worker-coworker-superdupercoworker
****************************************
*      _ ____ _  _ _  _      ____      *
*      | |  | |__| |\ |      [__       *
*     _| |__| |  | | \|      ___]      *
*  Worker-coworker-superdupercoworker  *
****************************************
```

