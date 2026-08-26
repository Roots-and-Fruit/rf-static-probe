# RF Static Probe

Throwaway experiment. A local WordPress Studio site is exported with the free Simply Static plugin. This repo is that folder of HTML files. GitHub Pages serves them.

Live: https://roots-and-fruit.github.io/rf-static-probe/

This is not rootsandfruit.com.

## Loop

1. Start the Studio site `RF Static Probe` (`C:\Users\reach\Studio\rf-static-probe`, http://localhost:8893).
2. Edit pages in WordPress.
3. Simply Static → Generate (local directory: `static-export`).
4. Run `.\ship-to-pages.ps1` from the Studio site folder.
5. Commit and push this repo.

WordPress stays on the laptop. GitHub Pages only sees files.
