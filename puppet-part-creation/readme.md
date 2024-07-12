# Creating Puppet Parts

Adding a new hairstyle or piece of clothing to the game is easy, and you can do it yourself! All you need is a graphics program like Krita or Gimp and some creativity.

## Steps to Add a New Part

1. **Design Your Part**: Create your new hairstyle or clothing item using your graphics program. Make sure each part is 800x800 pixels and saved as a transparent PNG file.

2. **Layering**: Each part has two layers:
   - **Front Layer**: This goes in front of the puppet's body.
   - **Back Layer**: This goes behind the puppet's body.

3. **Saving Files**:
   - Save the front layer with a sequential number followed by `_f.png` (e.g., `1_f.png`, `2_f.png`, `3_f.png`).
   - Save the back layer with the same sequential number followed by `_b.png` (e.g., `1_b.png`, `2_b.png`, `3_b.png`).
   - If a part is not needed, save it as an empty transparent 800x800 pixel PNG file with the same naming convention (e.g., `1_f.png`, `1_b.png`).

4. **File Placement**: Place your files in the correct folder. For example, if you're adding hair, save the files in the folder `puppet/a/hair/`.

## Example

If you're adding the first hairstyle, your files should look like this:
- `puppet/a/hair/1_f.png` (front layer)
- `puppet/a/hair/1_b.png` (back layer)

For the second hairstyle, your files should look like this:
- `puppet/a/hair/2_f.png` (front layer)
- `puppet/a/hair/2_b.png` (back layer)

By following these steps, you can easily add new parts to your puppet and customize your game!

---

Feel free to ask if you need more details or have any questions!