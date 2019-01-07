Origin from: https://gitea.werefoxsoftware.com/shadow8t4/Gitea-Dark-Theme

# Installing

Just put `styles.css` in the `custom/public/` subdirectory of the directory where your gitea executable is located.
If the subdirectory doesn't exist, make it yourself.

## Example

If I have my gitea binary in `/home/gitea/`, then I will put this .css in `/home/gitea/custom/public/`.

# Troubleshooting

I've added a header.tmpl file to the repo, as this may help fixing issues where the theme does not show up out of the box.
To add this, you simply need to put it in a `custom/templates/custom/` subdirectory.

# File tree
```
gitea/custom/templates/custom/header.tmpl
gitea/custom/public/styles.css
```