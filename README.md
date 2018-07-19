# wal-telegram

# Screenshots

![demo 1 (green)](https://user-images.githubusercontent.com/40271651/42736395-79242280-8866-11e8-8419-a9dc0b22be4c.png)
![demo 2 (orange)](https://user-images.githubusercontent.com/40271651/42736398-7e628d04-8866-11e8-9b40-ee09c09910d7.png)
![demo 3 (purple)](https://user-images.githubusercontent.com/40271651/42736400-81f08110-8866-11e8-860d-d71c3e1b4c10.png)

# Installation

```bash
git clone --depth 1 https://github.com/matteoguarda/wal-telegram
cd wal-telegram
./wal-telegram
# Open telegram, go to "settings/chat background" and click on choose from file:
![instruction 1]()
# Select ~/.cache/wal-telegram/colors.tdesktop-theme
![instruction 2]()
# Select ~/.cache/wal-telegram/background.png or jpg depending on your wallpaper:
![instruction 3]()
```

# Updating

You can update wal-telegram by running git pull inside wal-telegram:
```bash
cd wal-telegram
git pull
```

# Important notes

Some color constants in colors.tdesktop-theme are marked as // [UNTESTED], this because I couldn't find the elements responsable in the app.
So if you find something strange open an issue (with a screenshot of the element and it's name if possible) and I'll fix.

You can also use light colorschemes, no need for extra option, just run tde normally.

The theme works with [wal] too, not just [pywal].

[pywal]: https://github.com/dylanaraps/pywal
[wal]: https://github.com/dylanaraps/wal
