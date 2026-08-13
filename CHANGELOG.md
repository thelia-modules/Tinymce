# Unreleased

- Remove the bundled ResponsiveFilemanager component and its editor button. The component is
  unmaintained upstream and published its own PHP entry points under `web/tinymce/filemanager/`.
- Use the TinyMCE image and media dialogs, or the images and documents attached to your products,
  categories, contents and folders, to insert media in the editor.
- Files already uploaded under `web/media/` are left untouched, so URLs already stored in your
  content keep working.

# 2.3.0

- Add the possibility to choose the text areas where the module editor will be shown
- The available text areas are description, summary and conclusion in the updating pages of brands, products, categories, folder and contents
- The default configuration activates the module for all the descriptions
