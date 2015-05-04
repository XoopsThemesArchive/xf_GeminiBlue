A friend of mine, who is using Wordpress with the GeminiBlue theme a long time, asked me if I could port 
the GeminiBlue theme (from http://geeksmakemehot.com) to xoops so that he could use a forum and the other 
nice things I'm able to use with XOOPS within a layout, his visitors are used to.

For I thought, it would be useful for some other XOOPSers, i asked the original Author, Jennifer Ledbetter,
if there is anything against to port this theme. There isn't. So, here we are. XOOPS isn't Wordpress so i had
to add some stuff to fit our modules, but not that much.

I made an extra templateset to get the full results and you should use it otherwise most settings of eg. main menu
won't work :-) 

You can set a forum eg. (or any other module) full width without a sidebar by using the settings in
blockadministration. Set no left or right block active on this module.
To set the sidebar active, both a left and right block should be active on this module.


xf_Gemini isn't of width 800px but 770px to fit this type of screens too. 
The right sidebar ID (#menu) is made 30px smaller.

Install as any other XOOPS theme and do not forget to install the templateset containing system templates 
you'll find in root of themefolder and set it active in admin preferences.


Michael