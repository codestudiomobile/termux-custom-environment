# CodeStudio Termux Custom Environment

An aesthetic initialization and layout thematic extension engine for CodeStudio workspaces. This repository holds specialized modules to compute customized structural blocks, print stylish greeting frames, and maintain synchronized localized metadata targets.

## 📦 What's Inside?
* **`bash.bashrc`**: Core profile handler that reads saved title elements and routes layout metadata dynamically before displaying prompt spaces.
* **`apply-banner.sh`**: Custom structural translation engine which parses alpha characters (A–Z) across 6 vertical row indexes to generate high-impact block-matrix greeting banners.
* **`apply-title.sh`**: Targeted string compiler that updates interactive top-frame shell headings dynamically by routing persistent textual changes into structural state targets.

---

## 🚀 Quick Setup & Installation

Deploy these terminal appearance controls using your active terminal environment:

### 1. Build Terminal Framework Foundations
```bash
curl -fsSL [https://raw.githubusercontent.com/codestudiomobile/termux-custom-environment/main/bash.bashrc](https://raw.githubusercontent.com/codestudiomobile/termux-custom-environment/main/bash.bashrc) -o $PREFIX/etc/bash.bashrc

```

### 2. Deploy Script Management Tools

Download and activate permissions for layout customizers:

```bash
# Download Banners tool
curl -fsSL [https://raw.githubusercontent.com/codestudiomobile/termux-custom-environment/main/apply-banner.sh](https://raw.githubusercontent.com/codestudiomobile/termux-custom-environment/main/apply-banner.sh) -o $PREFIX/bin/apply-banner
chmod +x $PREFIX/bin/apply-banner

# Download Titles tool
curl -fsSL [https://raw.githubusercontent.com/codestudiomobile/termux-custom-environment/main/apply-title.sh](https://raw.githubusercontent.com/codestudiomobile/termux-custom-environment/main/apply-title.sh) -o $PREFIX/bin/apply-title
chmod +x $PREFIX/bin/apply-title

```

---

## 💡 How to Use

### 🎨 Create block-matrix ASCII Banners

Pass string parameters into the custom system utility. Alpha parameters automatically translate to large block-art visualizations displayed every time a shell terminal launches:

```bash
apply-banner "CODE STUDIO"

```

### 🏷️ Update Terminal Headings

Modify active shell title flags instantaneously using the application customizer tool:

```bash
apply-title "C++ Dev Mode"

```
