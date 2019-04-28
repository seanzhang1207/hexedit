# hexedit with remapped keys
The goal here is to shift the key combinations around to fit a more modern-time user habit. Specifically, combinations are changed to be similar to shortcuts in other applications, and the need for F1-12 keys are minimized. 

## Changes made to key combinations:
* **Ctrl-Q** to quit.
* **Ctrl-C**, **Ctrl-V** to copy/paste. **Ctrl-N** to paste to a new file.
* **Ctrl-O** to open another file.
* **Ctrl-S** to save.
* **Ctrl-Z** to undo all changes.
* **Shift-<**, **Shift->** to go up/down a page.
* **Shift-{**, **Shift-}** to go to the beginning/end of buffer.
* **Shift-S**, **Shift-R** to search forward/backward.
* **Ctrl-U** to suspend.
* **Shift-I** to do quoted insert.


To build from git:

```
./autogen.sh && ./configure && make
```
