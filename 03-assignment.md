# Assignment 3: Terminal Navigation Practice Sheet

**Instructions:** Starting from your home directory, execute the practice exercise commands and record every command used.

---

### Practice Exercise Questions:
1. Create `website/` containing `index.html`, `css/style.css`, `images/`.
2. Go into `css`, then return to `website` with a single command (`cd ..`).
3. List everything recursively: `ls -R`.
4. Rename `index.html` to `home.html`, then rename it back.
5. Open the folder in VS Code.

---

### My Answers:

```bash
cd ~
mkdir -p website/css website/images
touch website/index.html website/css/style.css
cd website/css
cd ..
ls -R
mv index.html home.html
mv home.html index.html
code .
```