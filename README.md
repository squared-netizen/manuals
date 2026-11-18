# Manuals

Documentation for the [squared SDK](https://squared-netizen.github.io/squared-netizen/),
found first and read second: a fuzzy search across every manual installed,
then a reader that moves through a page by its headings and links, in a
terminal or as a squared screen.

**Status: designed, not yet built.**

## What it will be

- **Pages are Obsidian-style markdown**: frontmatter (title, aliases, tags),
  `[[wikilinks]]`, callouts. Command pages share one shape (TLDR first,
  then synopsis, description, parameters), so every command reads alike.
- **Manuals come in cartridges** (sqcart 3.0, kind `manual`), and installing
  a package with sqterm's `pkg` installs its manual through a hook.
- **Search is fuzzy**: letters in order with gaps (`cartdg` finds
  "cartridge"), typos forgiven, over titles, aliases, headings, tags and
  text. Commands that have no page still show which package installed them.
- **Better navigation than man**: headings that fold, a header window,
  `]]` and `[[` between headings, links with back and forward history,
  marks, and a `:` command line as in neovim.
- **Two faces, one core**: `manuals` in a terminal (character cells, works
  over ssh), and a reader screen any squared app can show.
- **Web pages come in too**: a saved site converts to a manual with its
  internal links still working, through squared/data's converter.

Inspired by the [Linux Command Library](https://github.com/SimonSchubert/LinuxCommandLibrary).

## Licence

MIT: see [LICENSE](LICENSE). Security issues: see [SECURITY.md](SECURITY.md).
