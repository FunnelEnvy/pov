FunnelEnvy POV

## Contributing

### Edit an existing note

Just make changes to the `.md` file in `/_notes`.

### Add a new note

Duplicate [/_notes/templates/_note.md](https://github.com/FunnelEnvy/pov/blob/main/_notes/templates/_note.md) and move it into `/_notes`.

By default, the filename will be slugified to create the permalink, but you can set this manually in the front matter.

The `title` field in the front matter determines what shows up at the top of the note and when the note appears in searches or lists.

(Filename and `title` _can_ be different but probably shouldn't be.)

### Edit styles and layouts

This is a Jekyll site based on the [Jekyll Garden](https://jekyll-garden.github.io/) theme. Feel free to tweak `/assets/css/main.css`, or `/_layouts/Post.html`, or whatever else you think needs improvement.

### Publish

Commit your changes, push to `main`, and your updates will be published.

### How to edit these files

Any text editor will work! But [Obsidian](https://obsidian.md/) is a good choice, as it offers autocomplete for wikilinks and will easily show a list of all files that link _to_ the file you're editing.

To use Obsidian, simply set `/_notes` as your vault folder.

## License

The theme is a modified version of [Jekyll Garden](https://jekyll-garden.github.io/), available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).

Contents under CC-BY-NC.
