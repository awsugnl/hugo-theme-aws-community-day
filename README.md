# hugo-theme-aws-community-day

## Installation & Updates

Recommended is to add the theme as a submodule.

```text
cd themes
git submodule add https://....git
```

To update the latest version.

```text
git submodule update --init --recursive
```

To update to a specific version (tag).

```text
cd themes/hugo-theme-aws-community-day
git checkout v1.2.3
```

## Layout

Hugo first looks in a local folder 'layouts' before it looks in your theme. That means if you want to change something quickly, you can simply copy a theme file to the layouts folder and make the change there. For example if you want to change something in the header of the page:

```text
/themes/hugo-theme-aws-community-day/layouts/_default/baseof.html
```

To:

```text
/layouts/_default/baseof.html
```
