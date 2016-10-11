# How to add new content:

1. Add a standard resolution image (`filename.jpg`) to `images/art` or `images/design`
2. Add a high res version of the image that is named `filename@2x.jpg` to same directory as above
   - The standard and high resolutions should have the same name expect for the `@2x` in the name of the high resolution version.
   - The high resolution version should be twice the size of the standard resolution for both dimensions.
3. Add the appropriate information to `_data/art.yml` or `_data/design.yml`
   - `title`: Title of the project, e.g. *Payette*
   - `media`: media of the project, e.g. Oil on Canvas
   - `file_name`: the name of the image file, e.g. payette.jpg
   - `height`: height in pixels of the standard resolution image, e.g. 407
   - `width`: widht in pixels of the standard resolution image, e.g. 530
   - `max_res`: the highest resolution version of the image you have, set this to 2 if you have an @2x version of your image, otherwise remove this entry
4. Commit and push new code to GitHub:
   1. `git add <filename>`
   2. ​