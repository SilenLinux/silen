# silen-website

Static website for **Silen Linux** - served at https://cgtlpa.github.io/silen/.

- `index.html` - home
- `get.html` - ISO downloads (standard, NVIDIA, Arch and Void; Debian base coming soon)
- `packages.html` - CRES package manager + repository
- `styles.css` - Space Grotesk + Inter, charcoal + muted steel theme

No build step. Open `index.html` or serve the folder:

```sh
python3 -m http.server -d . 8080
```

ISO files: [Silen-Linux on Hugging Face](https://huggingface.co/datasets/vgzz/silen-isos).
