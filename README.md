## yey clara, here ur manual
#### read the fucking manual (rtfm) 
please .. at least the below four tiny chapters, with focus, at first. its very important info for understanding and not to fuck up the site.  
then go to the seperate edit parts to edit what u want.

##### global explanation
your website is editable in the [content](https://github.com/clarasaito/clarasaito.github.io/tree/main/content) folder.  
In there u see three folders and one _index and a privacy file.  
The main folder, content, is the home page. The folders inside are workshops & projects page.  
Inside those two folders there is the different subjects, each there own folders.  
There's also a photo starting with feature. this is the background of the page ánd the thumbnail photo of the page above it.  

##### about the _index files
You can edit text and summary there, and more, i'lll explain later. NOT title!
fyi: the description should be (best) min and max 160 characters. It is not sufficient now. No enters, just txt.  
You will have to decide what u want people to read there.  

##### about the index files
what is in that index files, below the texts {{gallmir}}  
DO NOT TOUCH!!   
it is hidden code for the way the galleries are shown.  
u can put some text above or below if u want. Always under the minusses.

##### fucking up
if u fuckup anything and i have an impossibility to do a thing..  
u can go back in commit (saving) history to go back to before what u did:  
this is why it is handy to put a certain personal message in ur commit before saving anything.  
but... avoid it if possible. and make sure i really cannot do anything at all.  
because when i am doing things and u do things at the same time, everything can be even more fucked up :P  
anyway.. in extreme circumstances u can 'quite easily' unfuck the fucks ;) [infos if necessary: revert a commit](https://docs.gitlab.com/ee/user/project/merge_requests/revert_changes.html#revert-a-commit)  
YAYY (i love this system)

and really .. if u fuckup.. please dont hesistate at all.. call me no worries it happens ;)

## practic manual
#### to change the *texts* in the pages
the text is written in [markdown](https://www.markdownguide.org/basic-syntax/) language. if u just wanna change a sentence, change it.  
but if u want things in bold, italic, as a heading, etc etc, check the markdown link. it is EASY.

press here for changing text about u: [author](https://github.com/clarasaito/clarasaito.github.io/blob/main/content/authors/admin/_index.md?plain=1)
this for the text within the projects page: [project](https://github.com/clarasaito/clarasaito.github.io/blob/main/content/project/_index.md?plain=1)
this one for the workshop page: [workshop](https://github.com/clarasaito/clarasaito.github.io/blob/main/content/workshops/_index.md?plain=1)


fyi: two spaces after a line ánd one enter is a new line, two enters a new paragraph.
1. click on the index or _index file. then,  
2. click the blue edit button.  
3. change that text.   
4. save: u can put a commit message below. it is handy for reference but not necessary. leave the tick ticked and press the blue button, commit changes.  

Yay u have then edited the page. check the change in ur website! (it *can* take some minutes before the change is visible)

#### add videos or pics to ur gallery
to add videos or pics, just add them in the [video](https://gitlab.com/mirmuis/kyatest/-/tree/main/content/gallery/video) or [pictures](https://gitlab.com/mirmuis/kyatest/-/tree/main/content/gallery/pictures) folder  
best is to have mp4 for video and jpg/jpeg for pictures, this works in all browsers.  
the sequence is numerically then alfabetically  
1. press the plus folder within the video/pictures folder
2. add photo
3. save: if u want put a commit message, leave the tick ticked and press the blue button, commit changes.

Yayy now u have added a photo/video.. check the change in the website! (it *can* take some minutes before the change is visible)

#### change background in the seperate pages  
(not the main page tho)
if u want a different photo in the background of the page, it should be uploaded in the folder of that page.
1. press the big plus button
2. upload photo - the name should start with feature
3. save: if u want put a commit message, leave the tick ticked and press the blue button, commit changes.

edit name of current photo: 
1. press blue edit button
2. open in Web IDE
3. in the left u see the folders, go to content, the folder u want to edit, rightclick on the old feature photo and press rename

this way it is handy to just check and test if the thumbnails of the pages look good in the main page and if the background looks good anyway in the page. so u can easily change the filename back if it looks shitty (which is very very possible)  
so.. check the change in the website! (it *can* take some minutes before the change is visible)

*alternatively:*
1. click on the current photo
2. press replace (next to the blue edit button)
3. upload the photo, the name should start with feature(!) if u want put a different commit message, leave the tick as is and press the blue button, commit changes

and check the change :)

---

tadaaaa.. easy as is (no?)  
if not, don't hesistate to call me please
