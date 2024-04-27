# pURLfy-rules

Rules files for [pURLfy](https://github.com/PRO-2684/pURLfy).

## 📃 Files

- [list.json](list.json): A list of all rule files.
- [cn.json](cn.json): Chinese rules.
- [fandom.json](fandom.json): Redirects you from Fandom wiki to official wiki.
    - Rules are obtained from [Steve0Greatness/MovedFromFandomDB](https://github.com/Steve0Greatness/MovedFromFandomDB/blob/master/database.json)
    - Only includes host-based redirects, so all pages will redirect to the main page of the official wiki.

## 💖 Contributing

If you want to update a rule file, you can create a pull request with your changes to `*.json` files. Do not change `*.min.json` files, since they are generated by minifying corresponding `*.json` file automatically.

If you want to add a new rule file, in addition to creating a new `*.json` file, you'll need to update `list.json` file to include the new rule file, and `README.md` to briefly introduce your rules. After your pull request is merged, the minified version of the new rule file will be generated automatically.
