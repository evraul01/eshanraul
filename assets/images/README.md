# Adding photographs and plots

1. Copy an optimized `.jpg`, `.png`, `.webp`, or `.svg` file into this folder. Use short lowercase names, for example `headshot.jpg` or `disk-spectrum.png`.
2. Find the matching placeholder in the relevant HTML page.
3. Replace its `<div class="media-placeholder">...</div>` with an image such as:

   ```html
   <img src="assets/images/headshot.jpg" alt="Eshan Raul at Washburn Observatory">
   ```

4. Keep the surrounding `<figure class="media-slot">` element. It provides the sizing and responsive layout automatically.
5. For a plot, keep `class="media-slot plot"` on the figure so the full plot is visible rather than cropped.

Write alt text that describes what is useful about the image. Avoid filenames with spaces. Before publishing, keep individual photographs under about 1 MB when possible.
