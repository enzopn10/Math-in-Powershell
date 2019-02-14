### Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/enzopn10/PowerMath/edit/master/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

## Hypotenuse, Opposite, Adjacent
```markdown
& {
& {
while ($option -ne "done") {

& {
$option=""
$var=""
$opt=""
$opp=""
$sin=""
$hip=""
$adj=""
$cos=""
} # Clear Variables
& {
echo "                                         "
echo "       !  !  !  SOHCAHTOA  !  !  !       "
echo "                                         "
echo "    SOH            CAH            TOA    "
echo "                                         "
echo " S   O   H      C   A   H      T   O   A "
echo " |   |   |      |   |   |      |   |   | "
echo " v   v   v      v   v   v      v   v   v "
echo "sin opp/hip    cos adj/hip    tan opp/adj"
echo "                                         "
echo "                                         "
echo "                    |                    "
echo "  Sin = Sine        |  Hip = Hypotenuse  "
echo "                    |                    "
echo "  Con = Cosine      |  Opp = Opposite    "
echo "                    |                    "
echo "  Tan = Tangent     |  Adj = Adjacent    "
echo "                    |                    "
echo "                                         "
} # Text Art
& {
$option = Read-Host " SIN , CON or TAN ?_ "

if ($option -eq "SIN") {
$opt = Read-Host " OPP or HIP ?_ "

if ($opt -eq "OPP") {
$var = Read-Host " What is the _ SIN ?_ "
$opp = Read-Host " What is the _ OPP ?_ "
$sin=[System.Math]::Sin($var/180*[System.Math]::PI)
$hip=$opp/$sin
echo ""
echo "   Hypotenuse = '$hip' "
echo ""
pause
}

if ($opt -eq "HIP") {
$var = Read-Host " What is the _ SIN ?_ "
$hip = Read-Host " What is the _ HIP ?_ "
$sin=[System.Math]::Sin($var/180*[System.Math]::PI)
$opp=$hip*$sin
echo ""
echo "   Opposite = '$opp'"
echo ""
pause
}

}

if ($option -eq "COS") {
$opt = Read-Host " ADJ or HIP ?_ "

if ($opt -eq "ADJ") {
$var=Read-Host " What is the _ COS ?_ "
$adj=Read-Host " What is the _ ADJ ?_ "
$cos=[System.Math]::cos($var/180*[System.Math]::PI)
$opp=$adj/$cos
echo ""
echo "   Hypotenuse = '$hip'"
echo ""
pause
}

if ($opt -eq "HIP") {
$var = Read-Host " What is the _ COS ?_ "
$hip = Read-Host " What is the _ HIP ?_ "
$cos=[System.Math]::cos($var/180*[System.Math]::PI)
$adj=$hip*$cos
echo ""
echo "   Adjacent = '$adj'"
echo ""
pause
}

}

if ($option -eq "TAN") {
$opt = Read-Host " OPP or ADJ ?_ "

if ($opt -eq "OPP") {
$var = Read-Host " What is the _ TAN ?_ "
$opp = Read-Host " What is the _ OPP ?_ "
$tan=[System.Math]::tan($var/180*[System.Math]::PI)
$adj=$opp/$tan
echo ""
echo "   Adjacent = '$adj'"
echo ""
pause
}

if ($opt -eq "ADJ") {
$var = Read-Host " What is the _ TAN ?_ "
$adj = Read-Host " What is the _ ADJ ?_ "
$tan=[System.Math]::tan($var/180*[System.Math]::PI)
$opp=$adj*$tan
echo ""
echo "   Opposite = '$opp'"
echo ""
pause
}

}
} # Read Host and Math
}
} # Loop
& {
$option=""
$var=""
$opt=""
$opp=""
$sin=""
$hip=""
$adj=""
$cos=""
} # Clear Variables (x2)
} # Everything
```

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/enzopn10/PowerMath/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
