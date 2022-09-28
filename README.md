# display_imported_file
how to show preview of a video and an image selected using the same html input type=file


In order to display any **image** and **video** from using the same **input** button then you must dynamically create such elements as needed.

This means:

- Detect what File type the user selected.
- Create a Path to the selected File.
- Create the relevant Element and set Path as **.src** input.
- Remove any pre-existing Element from your container (usually a **div**).
- **.append** the newly created Element for display on the page.
