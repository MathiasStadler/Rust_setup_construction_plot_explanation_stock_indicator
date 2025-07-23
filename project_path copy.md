# Project path of these repo

>[!NOTE]
>Useful extension inside VSCode
><!-- Keep the format -->
> - TODO Highlight
> - Todo Tree
<!-- Keep the format -->
>[!NOTE]
>Markdown Preview - Extension for save unnecessary submit to GitHub
<!-- Keep the format -->
>[!NOTE]
>Check/test binary local already installed e.g. git
FIXME Missing Link
This command is compatible with script testing, by ignoring the output
<!-- Keep the format -->
>```bash
>#dpkg-query -s <pkg> >/dev/null 2>&1
>dpkg-query -s git >/dev/null 2>&1
>echo $?
>```
><!-- Keep the format -->
>[!TIP]
> Add the link sync to repo
>
>```bash <!-- markdownlint-disable-line code-block-style -->
> mkdir -p img && wget  -P img/ "https://raw.githubusercontent.com/MathiasStadler/link_symbol_svg/360d1327d05280d53de5fa816c522f89a35891ca/img/link_symbol.svg"
>```
><!-- Keep the format -->
<!-- Keep the format -->
## Create a new repository on the command line - found by GitHub.com hint for a new  empty repo
<!-- -->
```bash <!-- markdownlint-disable-line code-block-style -->
echo "# Rust_setup_construction_plot_explanation_stock_indicator" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/MathiasStadler/Rust_setup_construction_plot_explanation_stock_indicator.git
git push -u origin main
```
<!-- Keep the format -->
## Crete plain rust project for using inside MS Visual Studio Code
