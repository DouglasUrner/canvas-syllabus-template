# Canvas Page Template

Base template for Canvas pages. Currently (September of 2019) it does not appear to be possible to pull changes from the template into a repository that was based on the template.

Each page is its own repository. The content that is visible on Canvas is in the **docs** folder.

## Usage

This template is the boilerplate for a single Canvas page.

1. In **Settings** enable GitHub Pages using the **docs** folder on the **master** branch.
1. Create an page on Canvas.
1. Edit the page:
   - Switch to HTML mode.
   - Add an ```<iframe src="" width="100%" height="660px">``` tag.
   - Use the GitHub pages URL of this repository as the ```src``` artribute of the ```iframe``` tag.
1. Edit ```docs/_data/page.yml``` to reflect the parameters of this page. Custom values may be added, they can be referenced in [Liquid][] code as ```site.data.page.valueName```.

**Note that there is the potential for confusion between the Jekyll/Liquid use ef the term "page" and the Canvas usage.

[liquid]: <https://shopify.github.io/liquid/>
