# Adding New Languages

To add a new language to the game, follow these steps:

1. **Create a New Language File**:
   - Copy the existing `en.php` file.
   - Rename the copied file to the new language code (e.g., `de.php` for German).

2. **Translate the Variables**:
   - Open the new language file (e.g., `de.php`).
   - Translate each variable's value to the new language. For example:
     ```php
     <?php
     $LANG_Avatar = 'Avatar';
     $LANG_Hitpoints = 'Lebenspunkte';
     // Continue translating all variables...
     ?>
     ```

3. **Save the File**:
   - Save the translated file in the same directory as the other language files.