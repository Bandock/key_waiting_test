# Key Waiting Test
This CHIP-8 related test is to see if the interpreter is executing the FX0A instruction correctly.

It will show a `thumbs up` if it passed or `thumbs down` if it failed.  It utilizes another key instruction where it should pass upon release of any key that was pressed.  If you see that `thumbs down`, your interpreter likely did not wait till the key that was pressed was released.
