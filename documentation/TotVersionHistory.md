# Tot Version History
- [Tot Version Archive](https://tot.rocks/versions/)

### [Tot 1.0.1](https://tot.rocks/versions/1.0.1.txt)

#### macOS:

- Text mode is now synced across devices: if you switch to plain text on
your phone, your desktop will also switch.

- Updated Settings to match Apple Style Guide. \[Yay John!\] - Fixed a
problem with the dynamic dock icon’s drop shadow. \[Yay Anthony!\] •
Increased contrast of help text for better readability. \[Yay John!\] •
Cleaned up help text -- its great now. \[Yay John, Dan, and TJ!\] •
Straight quote obliteration. \[Fricken’ Gruber!\] - Selecting Tot with
Cmd-Tab will now reopen its window if needed. - Popover window no longer
animates from menu bar. Snappy. \[Yay Fredrik!\] - A detached popover
window’s size is saved and used the next time you click on the menu bar
icon. \[Yay Jordan!\] - Added a “Display as Floating Window” option in
Window menu. \[Yay Kevin!\] - New Edit \> Add Link... (⌘K) can used to
create or edit links in rich text mode. - Arrow keys can now navigate in
Help.

#### iOS:

- Text mode is now synced across devices: if you switch to plain text on
your phone, your desktop will also switch.

- Cleaned up help text -- its great now. - Straight quote obliteration.
\[Fricken’ Gruber!\] - Delete button no longer causes a crash a first
character. \[Yay Matthew!\] - Fixed check for adding sample content: you
may see it once more, but then it will only occur after a new install. •
Text editing now adapts to new dynamic text size without having to
relaunch. - The keyboard is no longer tinted when Colored Backgrounds
are set to OFF - Additional keyboard shortcuts to match Safari muscle
memory: ⌘⇧\[ to show previous dot, ⌘⇧\] to show next dot. \[Thanks
Erik!\]

### Tot 1.0.2

#### macOS:

- AutoList™: lines with leading tabs or a symbol and a space are
automatically replicated to make maintaining lists easier. \[Yay Ben!\]
- Cmd-S no longer beeps when saving text, immediately syncs instead.
\[Yay Nick!\] - New “Extra Extra Large” font size setting. \[Yay
Justin!\] - Added check for plain text mode to prevent issues with style
attributes in fonts like Fira Code. \[Yay Jed!\] - Added a new Window \>
Column Layout option to set column width (wide, narrow or full) for
wider windows \[Yay Ben!\] - Spelling, grammar, and substitution
settings are now synced for each dot. Use Edit or the contextual menu
within a dot to turn on spell check or turn off substitutions. \[Yay
Andre!\]

#### iOS:

- AutoList™: lines with leading tabs or a symbol and a space are
automatically replicated to make maintaining lists easier. \[Yay Ben!\]
- Sharing now uses text from dot, not a file. To save a file, long-press
on the share icon. - Added Cmd-0 and Cmd-1-7 support to iPadOS - Clear
All no longer adds stuff to the clipboard unexpectedly

### [Tot 1.0.3](https://tot.rocks/versions/1.0.3.txt)

#### macOS:

- Tot can now customize the dot color theme: - Use Option key in Tot
menu or Cmd-Option-, to open Theme Preferences. - Select the dot you
want to change in the main window. - Changes to color well are displayed
immediately. - New colors are synced to all devices, including iOS. -
Share your theme as .tot file with save/load in Theme Preferences. -
Theme file is JSON with hex colors: easy to modify in text editor, too.

- Added Share to File menu. \[Yay DW!\] - Allows you to create custom
keyboard shortcuts. - See
https://support.iconfactory.com/kb/tot/keyboard-shortcuts-in-tot

- Updated Help to match changes with Cmd-S.

#### iOS:

- Custom app icons in 14 colors are now available in Settings. \[Yay
Ged!\] - Custom themes are supported - use macOS theme editor to update
all devices.

- Sharing sheet now includes actions to clear, copy, and replace all
text. - Use long press on sharing icon for quicker access and additional
options. - Added “Paste as Plain Text” \[Yay Brian!\] - Use keyboard
command Shift-Cmd-V on iPadOS. - Also at end of text selection menu. •
Worked around an iOS crash when selecting a huge amount of text. \[Yay
Federico!\]

### [Tot 1.0.4](https://tot.rocks/versions/1.0.4.txt)

#### macOS:

- AutoList improvements: - Items without any text are automatically
removed when you press return. \[Yay Ben, Gus, Ged, and Ian!\] - A new
item will be inserted before the current line if the cursor is at or
before the symbol. \[Yay Ian!\] - Text now scrolls into view after
inserting a new symbol. \[Yay Ian!\]

- Hiding the window with the hotkey will restore the application that
was open when the window was activated. - Updated help with settings for
menu bar items: configuring text view quotes and spelling, floating
window support, and modifying keyboard shortcuts. [Yay @tot_app
followers!] - Removed an unneeded submenu from text view context menu. 

#### iOS:

- AutoList improvements: - Items without any text are automatically
removed when you press return. \[Yay Ben, Gus, Ged, and Ian!\] - A new
item will be inserted before the current line if the cursor is at or
before the symbol. \[Yay Ian!\] - Text now scrolls into view after
inserting a new symbol. \[Yay Ian!\]

- Font improvements: - Tot now supports custom fonts. - For help
installing fonts on iOS, please see:
https://support.iconfactory.com/kb/tot/using-custom-fonts-in-tot-pocket -
Added setting for fixed width font. \[Yay Gruber!\] - Added sliders in
Settings to fine tune text size. \[Yay Ged!\] 

- Updated tab button icon (so it no longer looks like indent). - Fixed
name of dark green icon \[Yay Karan!\] - Fixed a problem with pasting
URLs as plain text.

### [Tot 1.0.5](https://tot.rocks/versions/1.0.5.txt)

#### All:

- Improved Accessibility: - Dots in header are now treated as an ordered
list of tab buttons in VoiceOver. - The text view’s label is now read as
“Dot \#” followed by its contents. - Fixed many items so they read
correctly in VoiceOver. - Dots now use numbers for “differentiate
without color” in Accessibility settings. \[Yay Jason!\] - Updated help
and default content for color blindness accessibility. - Added Grayscale
icons to app settings.

- Lines that begin with a brace or bracket are no longer used for
AutoList \[Yay huckncatch!\]

#### macOS:

• Moved Dock icon configuration to Settings: - Pick your favorite icon
style using the heart icon. - Use the contrast icon to pick between Dark
& Light themes.

• Dots can be numbered using “defaults write com.iconfactory.Tot
showIndex true” then quit and relaunch. \[Yay Kelvin!\] - Added tooltip
on menu bar icon that shows app name and keyboard shortcut. \[Yay
stiegjon!\]

#### iOS:

- Fixed a potential crash if a custom font was no longer available \[Yay
Ged!\] • Cleaned up presentation of bulk actions (when tapping and
holding on share button). \[Yay Gruber!\]

### [Tot 1.0.6](https://tot.rocks/versions/1.0.6.txt)

#### macOS:

- Fixed a crash when dragging or quitting from menu bar (yes, really).

#### iOS:

- Fixed VoiceOver when switching edit modes. \[Yay Alex!\] •
Improvements when navigating header using VoiceOver. \[Yay Alex!\] •
Disabled text size changes using keyboard commands (Cmd + and -). \[Yay
Gruber!\] - Text statistics are no longer abbreviated if there’s enough
space (e.g. iPad).

### [Tot 1.1](https://tot.rocks/versions/1.1.txt)

#### All:

- Added Share extension and widget - On macOS, enable in System
Preferences \> Extensions - On iOS, use ⋯ in Share sheet app icons to
add Tot - On iOS, use Edit at bottom of widget view to add Tot - New
Mobius icon. \[Yay Ged!\] - Added a limit of 100,000 characters per dot.
\[Yay Garrett!\]

macOS:

- Help text is displayed using the font size setting of the current dot.
\[Yay zax!\] - Fixed styling for links dragged in from Chrome. - URLs
pasted into rich text are now linked automatically. - Scrollbar is now
tinted using dot theme \[Yay Frank!\] - Fixed drawing issues with status
bar. - Improved VoiceOver labels for statistics and text mode toggle.
\[Yay Alex!\] - Improved VoiceOver for dot header, status bar, and
settings. \[Yay Robin!\]

#### iOS:

- Default font is now selected correctly in settings (both variable and
fixed). - Fixed a bug where tapping a link while editing didn’t select
the entire URL. - Fixed VoiceOver for switching edit modes. \[Yay
Alex!\] - Improvements when navigating header using VoiceOver. \[Yay
Alex!\]

### [Tot 1.1.1](https://tot.rocks/versions/1.1.1.txt)

#### All:

- Improved Markdown support: - Text should not lose characters when
switching edit modes, and literal escapes are only added as needed. -
Fixed issues with escaped Markdown characters not being removed from
rich text. \[Yay Marvin!\] - Underscores and asterisks in rich text are
now escaped when converted to Markdown. - Text for inline links is
handled correctly now. - Improved handling of horizontal rulers.

#### macOS:

- The icon picker in Settings is a lot simpler now. We’re not afraid to
make mistakes, we’re afraid of bad decisions that don’t get corrected.
:-) - Added icons that look better on future versions of macOS. •
Titlebar appearance was adapted for future versions of macOS. - Pasting
relative URLs now treats them as plain text. \[Yay Marvin!\] - Fixed
selecting fixed width fonts by not using a localized name. \[Yay
Carles!\] - Fixed issues with substitutions and text checking getting
stored and synced correctly. \[Yay Dom!\]

#### iOS:

- Added entitlement for “user installed fonts” so Adobe CC fonts can be
used. - Change sharing extension button from “Done” to “Save”. - Fixed
issues with keys when reduced transparency was turned on. \[Yay Oli!\] •
Typing whitespace at the end of a link will remove link formatting and
allow normal text to be entered. \[Yay Gruber!\]

### [Tot 1.2](https://tot.rocks/versions/1.2.txt)

#### All:

- Compatibility with latest operating systems and hardware, including
Big Sur and Apple Silicon.

macOS:

- Fixed an issue where the center dot wasn’t clickable. \[Yay Chris!\] •
Fixed titlebar appearance.


### [Tot 1.2.1](https://tot.rocks/versions/1.2.1.txt)

#### All:

- Dot defragger: compacts dots to keep things clean and organized: -
Cleans up dots by moving full ones to the left and empty ones to the
right - iOS: Use “Compact Dots” in share sheet (or tap & hold on share
icon) - macOS: Use Window \> Compact Dots... (or ⇧⌘D) • AutoList will
only remove bullets if they are in the middle of a list \[Thanks Ian!\]
- Fixed check for 100,000 characters: deleting text no longer triggers
the alert - If the first paragraph of a dot is mostly Arabic or Hebrew,
the text will automatically switch to using a Right-to-Left writing
direction \[Thanks Ezra!\] - In plain text, ⌘B and ⌘I inserts a single
Markdown character without a selection (this previously only worked with
selected text)

#### macOS:

- New symbol picker added to status bar: - Click on the asterisk to get
a popover with symbols - Pick a bullet to start a new list, Emoji to add
status, or any other symbol - A quick alternative to ⌃⌘Spacebar

#### iOS:

- Fixed sample text at first launch

### [Tot 1.2.2](https://tot.rocks/versions/1.2.2.txt)

#### macOS:

- Updated all icons, including dynamic ones, to Big Sur style - Added
purple tint color on controls to match iOS

### [Tot 1.2.3](https://tot.rocks/versions/1.2.3.txt)

#### All:

- Fixed a crash during iCloud updates - often seen at launch • Fixed a
typo in help: there are no longer limitions in this app • Hash marks for
Markdown headers are no longer used for AutoList \[Yay TJ!\] - Fixed
issues with some bullet characters not automatically starting a list

#### macOS:

- Fixed a problem with spell check settings not saving correctly •
Improved rendering of dots on the flat title bar - Fixed placement of
popover window in menu bar

#### iOS:

- Fixed a problem with text undo not working - Changed shortcut action
names to be more explicit by adding “Text” - Fixed a problem with RTL
text being displayed incorrectly when returning to foreground \[Yay
Moshik!\]

### [Tot 1.2.4](https://tot.rocks/versions/1.2.4.txt)

#### macOS:

- Local backups of iCloud data are now done automatically: - View latest
backups with File \> Show Automatic Backups - Backups are JSON files
encoded in UTF-8 - Restore a backup with File \> Restore Backup... -
Backups are updated as needed every hour • Increased contrast of unused
dots in dark mode \[Yay Mark!\] - Keyboard shortcuts like ⌘G now work
correctly while Find panel is displayed \[Yay Ben!\] - Improved
compatibility with Bartender \[Yay Michal!\]