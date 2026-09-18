# Privacy & Terms

Video Alignment Tool is a free desktop app that works on recordings stored on your own computer. There are no accounts and no servers that receive your media, so this page is short.

_Last updated 16 September 2026._ The same text is on the website at <https://alignment_tool.alexstein.ca/legal/>.

- [Privacy Policy](#privacy-policy)
    - [What we collect](#what-we-collect)
    - [Your recordings](#your-recordings)
    - [When the app goes online](#when-the-app-goes-online)
    - [This website](#this-website)
- [Terms & Conditions](#terms--conditions)
    - [License to use](#license-to-use)
    - [Your responsibilities](#your-responsibilities)
    - [No warranty](#no-warranty)
    - [Limitation of liability](#limitation-of-liability)
- [Contact](#contact)

## Privacy Policy

Video Alignment Tool runs entirely on your computer. It reads, analyses and exports your recordings locally and never uploads them.

> **The short version.** We don't collect your recordings, your file names, your projects, or anything about how you use the app. There are no analytics, no tracking and no accounts. The app only goes online to check for updates and, if you ask it to, to download ffmpeg.

### What we collect

Nothing about you. The app stores everything it remembers on your own computer.

| Data                                                                                           | Where it lives                                                                                            |
| ---------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------- |
| Project files, which hold the list of recordings, their alignment, markers and export settings | Wherever you save them.                                                                                   |
| Preferences, export presets and the recent-projects list                                       | In the app's settings folder on your computer.                                                            |
| Autosave recovery copies                                                                       | In the app's settings folder, until you save or discard them.                                             |
| Preview copies, called proxies, of video the app can't play directly                           | Beside the original file, or in a folder you choose in Preferences. You can delete them from Preferences. |

### Your recordings

ffmpeg processes your recordings on your computer. The app writes exports to the folder you choose, only ever reads your original files, and never changes them. It sends nothing about their contents to us or to anyone else.

### When the app goes online

| When                                                            | What happens                                                                                                                                                                                                          |
| --------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| On launch, if **Check for updates** is on, which is the default | The app asks GitHub for the latest release number. Turn this off in **Preferences → Updates**. The app never downloads or installs anything without asking. **Download** opens the download page in your web browser. |
| When you choose to download ffmpeg                              | The app fetches a list of download locations from GitHub, then downloads ffmpeg from a public build provider such as ffmpeg.martin-riedl.de, evermeet.cx or the BtbN builds on GitHub.                                |

These requests carry what any web request does, like your IP address and the app's version. The privacy policies of GitHub and the build providers apply to them. Video Alignment Tool does not sell data, show ads, or share information with advertisers.

### This website

This site has no analytics or cookies. It loads fonts from Google Fonts, and the download page asks GitHub which installer files are available so its buttons can link straight to them. Your light or dark theme choice is saved in your own browser and nowhere else.

## Terms & Conditions

By downloading and using Video Alignment Tool, you agree to these terms. We've tried to keep them fair and readable, so please do read them.

### License to use

Video Alignment Tool is free under the [MIT License](LICENSE), for personal, academic, commercial and institutional use. ffmpeg, which the app downloads or uses, is a separate open-source project under its own LGPL and GPL licenses. The other open-source parts of the app keep their own licenses too.

### Your responsibilities

- **Check your results.** The app reports how confident each alignment is, but you are responsible for confirming that exported files meet your needs before relying on them.
- **Keep your originals.** The app never modifies source recordings. Keep them until you are satisfied with your exports.
- **Use recordings you're entitled to.** You're responsible for having the right to process the recordings you use, and for following any consent, ethics or data-handling rules that apply to them.
- **Use the software lawfully.** Don't use Video Alignment Tool for anything unlawful.

### No warranty

The software is provided "as is", without warranty of any kind, express or implied, including but not limited to the warranties of merchantability, fitness for a particular purpose, and non-infringement. We do not guarantee that the software will be uninterrupted or error-free, or that any alignment or export will be correct in every circumstance.

### Limitation of liability

To the fullest extent permitted by law, the authors and contributors of Video Alignment Tool shall not be liable for any data loss or for any direct, indirect, incidental, special, or consequential damages arising out of the use of, or inability to use, the software, even if advised of the possibility of such damages.

We may update these terms and this policy as the app evolves. When we do, we'll change the "last updated" date above. Continued use after a change means you accept the revised version.

## Contact

Questions about privacy or these terms? [Open an issue](https://github.com/LiminalSpaces/video-align-dist/issues/new/choose) on this repository.
