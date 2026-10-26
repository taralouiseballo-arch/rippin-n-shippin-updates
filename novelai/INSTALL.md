# Install NovelAI on your iPad Home Screen

**Name:** NovelAI  
**Opens:** https://novelai.net/stories  
**Icon:** custom book + rose-gold quill

Apple does not let third-party tools create a signed `.shortcut` file.  
This package uses an installable **Home Screen web clip** (`.mobileconfig`) with the custom icon — that is the supported way to ship a one-tap Home Screen shortcut with your own artwork.

## Install now (iPad + Safari)

Open this link in **Safari**:

https://cdn.jsdelivr.net/gh/taralouiseballo-arch/rippin-n-shippin-updates@57a1d9a1df506d51ce436fc2780ba26e85523443/novelai/NovelAI.mobileconfig

Then:

1. Allow the configuration profile download.
2. Open **Settings**.
3. Tap **Profile Downloaded** (near the top).
4. Tap **Install** → enter your passcode → install.
5. Go to the Home Screen and open **NovelAI**.

The profile is unsigned (personal shortcut). That warning is expected.

## Files

| File | Purpose |
|------|---------|
| `NovelAI.mobileconfig` | Installable Home Screen shortcut (icon + URL) |
| `NovelAI-icon.png` | 1024×1024 custom icon |
| `icons/` | Apple touch icon sizes |
| `index.html` | Optional Safari installer / Add to Home Screen page |

## Optional: Add to Home Screen from the web page

If you prefer not to install a profile, open the installer page in Safari (after GitHub Pages is enabled for this repo), then **Share → Add to Home Screen**, keep the name **NovelAI**.
