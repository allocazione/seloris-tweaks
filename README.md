<div align="center">
  <h1>🌘 Seloris' Discord Tweaks</h1>
</div>

<div align="center">
  <img src="https://img.shields.io/badge/Discord-7289DA?style=for-the-badge&logo=discord&logoColor=white" alt="Discord">
  <img src="https://img.shields.io/badge/CSS-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS">
  <img src="https://img.shields.io/github/license/allocazione/seloris-tweaks?style=for-the-badge" alt="License">
  <img src="https://img.shields.io/github/stars/allocazione/seloris-tweaks?style=for-the-badge" alt="Stars">
</div>

<p align="center">
  ✨ <strong>A comprehensive collection of Discord CSS tweaks</strong> ✨<br>
  Designed to enhance your Discord experience with modern UI improvements, cleaner interfaces, and better usability.
</p>

## 🚀 Features

### 🎨 **Visual Enhancements**
- **🔄 Revamped Profile Popouts** - Modern, sleek profile cards
- **📱 Simplified Panel Area** - Clean and minimalist interface
- **🗑️ Clutter Removal** - Eliminates unnecessary UI elements
- **📏 Compact Context Menus** - Streamlined right-click menus
- **👥 Compact Member List** - Space-efficient member sidebar

### 🛠️ **Customization Options**
- **🏷️ Reordered Username Tags** - Swap clan tags and role icons
- **✂️ Trimmed Long Tags** - Automatic tag truncation
- **💬 Custom Chat Bar** - Uniform messaging interface
- **🎭 Role Pills Display** - Enhanced role visualization
- **👤 Full Bio Viewing** - Expanded profile descriptions

### 🎯 **Quality of Life Improvements**
- **🎁 Hidden Gift Button** - Removes distracting gift prompts
- **📱 Hidden Apps Button** - Cleaner toolbar
- **💎 No Nitro Upsells** - Removes promotional content
- **🔧 Fixed Icon Alignments** - Pixel-perfect interface
- **📜 Darker Scrollbars** - Better visual contrast
- **⚡ Hidden Hover Reactions** - Reduces UI clutter

## 📦 Installation

### 🎯 **Choose Your Installation Type**

**🔄 Auto-Updating Theme (Recommended)**
- **File**: `seloris-autoupd.theme.css`
- **Pros**: Automatically receives updates and new features
- **Cons**: Requires internet connection, may occasionally introduce breaking changes
- **Best for**: Users who want the latest features and don't mind occasional updates

**📁 Static Theme**
- **File**: `seloris-tweaks.theme.css` 
- **Pros**: Consistent experience, works offline, no unexpected changes
- **Cons**: Manual updates required for new features and fixes
- **Best for**: Users who prefer stability and control over updates

### 🔧 **For Vencord Users**

#### 📁 **Local Installation**
1. **Download** the `seloris-*.theme.css` file
2. **Navigate** to your Vencord themes folder:
   - **Windows**: `%APPDATA%\Vencord\themes\`
   - **macOS**: `~/Library/Application Support/Vencord/themes/`
   - **Linux**: `~/.config/Vencord/themes/`
3. **Place** the CSS file in the themes directory
4. **Enable** the theme in Vencord settings

#### 🌐 **Direct Import (Recommended)**
1. **Copy** this URL:
   ```
   https://raw.githubusercontent.com/allocazione/seloris-tweaks/refs/heads/main/css/seloris-tweaks.theme.css
   ```
2. **Paste** it in Vencord's theme import field
3. **Apply** and enjoy!

### 🌐 **For BetterDiscord Users**

#### 📁 **Local Installation**
1. **Download** the `seloris-*.theme.css` file
2. **Navigate** to your BetterDiscord themes folder:
   - **Windows**: `%APPDATA%\BetterDiscord\themes\`
   - **macOS**: `~/Library/Application Support/BetterDiscord/themes/`
   - **Linux**: `~/.config/BetterDiscord/themes/`
3. **Place** the CSS file in the themes directory
4. **Enable** the theme in BetterDiscord settings

#### 🌐 **Direct Import**
1. **Open** BetterDiscord settings
2. **Go to** the Themes tab
3. **Click** "Open Theme Folder" or use the import URL feature
4. **Import** using: `https://raw.githubusercontent.com/allocazione/seloris-tweaks/refs/heads/main/css/seloris-tweaks.theme.css`

### 🎨 **For Custom CSS Injection**
1. **Import** directly via URL:
   ```css
   @import url('https://raw.githubusercontent.com/allocazione/seloris-tweaks/refs/heads/main/css/seloris-tweaks.theme.css');
   ```
2. **Or copy** the contents of `seloris-*.theme.css`
3. **Paste** into your preferred CSS injection method
4. **Apply** the styles to Discord

## ⚙️ Configuration

The theme includes several customizable variables in the `:root` section:

```css
:root {
  --tag-order: 1;                          /* 🏷️ Username tag ordering */
  --status-enabled: true;                   /* 🟢 Status indicator visibility */
  --background-width: full;                 /* 📐 Background width setting */
  --right-gradient: false;                  /* 🎨 Gradient effect toggle */
  --show-notes: false;                      /* 📝 Note visibility */
  --rolepills: true;                        /* 💊 Role pill display */
  --compact-input-box: true;                /* 📝 Compact message input */
  --hide-gift-button: true;                 /* 🎁 Gift button visibility */
  --hide-apps-button: true;                 /* 📱 Apps button visibility */
  --hide-nitro-upsells: true;              /* 💎 Nitro promotion hiding */
  --fix-minor-icon-misalignments: true;     /* 🔧 Icon alignment fixes */
  --darker-scrollbar: true;                 /* 📜 Scrollbar styling */
  --hide-hover-quick-reactions: true;       /* ⚡ Hover reaction hiding */
}
```

## 🎯 Optimization Tips

### 🚀 **Performance Optimization**
- **🔄 Regular Updates**: Keep your theme updated for compatibility
- **🧹 Clean Installation**: Remove old themes before installing new ones
- **⚡ Selective Features**: Disable unused features by setting variables to `false`
- **🔍 Monitor Performance**: Use Discord's Developer Tools to check for issues

### 🎨 **Visual Optimization**
- **🌗 Dark Mode**: Optimized for Discord's dark theme
- **🎪 Custom Colors**: Modify CSS variables to match your preferences

### 🛠️ **Troubleshooting**
- **🔄 Clear Cache**: Restart Discord after applying themes
- **🐛 Disable Conflicting Themes**: Only use one theme at a time
- **📝 Check Console**: Look for CSS errors in Developer Tools

## 🤝 Contributing

We welcome contributions! Here's how you can help:

### 📝 **Guidelines**
- **🎯 Focus on Usability**: Prioritize user experience improvements
- **📱 Maintain Compatibility**: Test across different Discord clients
- **🧹 Clean Code**: Use proper CSS formatting and comments
- **📚 Document Changes**: Update README for new features

### 🔧 **Development Setup**
1. **Fork** this repository
2. **Clone** your fork locally
3. **Make** your changes
4. **Test** thoroughly
5. **Submit** a pull request

### 🎨 **Design Principles**
- **Minimalism**: Less is more
- **Consistency**: Maintain visual harmony
- **Accessibility**: Consider all users
- **Performance**: Optimize for speed

## 📚 Resources

### 🔗 **Useful Links**
- [**Discord Developer Documentation**](https://discord.com/developers/docs) - Official Discord API docs
- [**Vencord Documentation**](https://vencord.dev/) - Vencord client mod
- [**BetterDiscord Documentation**](https://betterdiscord.app/) - BetterDiscord client mod
- [**CSS Selectors Reference**](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Selectors) - MDN CSS guide
- [**Discord Theme Development**](https://github.com/topics/discord-theme) - Community themes

### 🎨 **Inspiration & Tools**
- [**CSS Beautifier**](https://www.freeformatter.com/css-beautifier.html) - Format your CSS
- [**Color Palette Generator**](https://coolors.co/) - Create color schemes
- [**CSS Validator**](https://jigsaw.w3.org/css-validator/) - Validate CSS syntax

## 📄 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

## 🎉 Acknowledgments

- **🎨 External CSS Authors** - Credits to original snippet creators:
  - [Krammeth](https://github.com/Krammeth/css-snippets) - Profile Popouts
  - [Davart154](https://github.com/davart154/Themes) - Simplified Panel Area
  - [Abbie](https://github.com/abbie/discord-css) - Clutter Removal
- **💻 Vencord Community** - For their shared snippets

<div align="center">
  <p>
    <strong>⭐ If you used this tweaks, please star the repository! ⭐</strong><br>
    <sub>Made with ❤️ by <a href="https://github.com/allocazione">@allocazione / Seloris</a></sub>
  </p>
</div>
</div>
