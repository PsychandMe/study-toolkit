# Study toolkit

A calm, offline-friendly study planner. Plan your day, focus in short blocks, then reflect, with comfort and accessibility options built in from the start.

**Live app:** https://psychandme.github.io/study-toolkit/

## What it does

**Today**
- A "Next up" card shows your next task and its first small step.
- Break any task into small steps, and give tasks a time to see them on a day timeline with a "Now" marker.
- Brain dump: type everything on your mind, one item per line, and add it to today.
- A daily routine checklist for a predictable start.
- Print a clean one-page plan for the day.

**Focus**
- A visual timer with four block lengths: Tiny (2 min), Low (10), Steady (15) and Full (25), or set your own.
- The next block never starts by itself.
- Optional soft chime and vibration, a two-minute heads-up, and the option to hide the countdown numbers.
- Break ideas and a "Feeling stuck?" list of tiny first steps.

**Plan**
- A week view: tap a day to see and plan just that day.
- If–then plans ("If it is 4 pm, then I will open my notes"), with a daily check-in.
- A short weekly reflection.

**Settings**
- Light, dark or high-contrast themes, or match your device.
- Three typefaces (Lexend, Atkinson Hyperlegible, or your device default), five text sizes and roomy text spacing.
- Turn off animation.
- Low-pressure mode, which hides counts and tallies.
- Back up and restore your data as text.

## Privacy

There are no accounts, no tracking and no server. Your tasks, plans and settings are saved in your browser's storage on your own device, and nothing is sent anywhere. Because of this, data does not sync between devices. Use **Settings → Back up or move your data** to copy it across.

## Install and use offline

**Quickest, on a computer:** download the files and open `index.html`. It works offline in your browser.

**As an installed app:** open the live link once while online, then:
- **Chrome or Edge (computer or Android):** choose **Install app** in the address bar or menu.
- **iPhone or iPad:** in Safari, tap **Share**, then **Add to Home Screen**.

After the first visit it opens like a normal app with no connection. When offline, text uses your device's default font unless Lexend or Atkinson Hyperlegible was already loaded while online.

## Host your own copy

1. Fork this repository, or upload these files to a new public repository.
2. In **Settings → Pages**, choose **Deploy from a branch**, select **main** and **/(root)**, then save.
3. Your app appears at `https://YOUR-USERNAME.github.io/REPOSITORY-NAME/`.

To update, replace `index.html`. Installed copies refresh the next time they open online, sometimes on the second open.

## Files

| File | Purpose |
|---|---|
| `index.html` | The whole app: layout, styles and logic |
| `manifest.webmanifest` | Lets browsers install it as an app |
| `sw.js` | Service worker that stores the app for offline use |
| `icon.svg`, `icon-192.png`, `icon-512.png` | App icons |

## Evidence and limits

If–then planning is based on research on implementation intentions, and the reflection prompts follow the phases of self-regulated learning. The comfort options are design choices to reduce load and pressure. This is a planning aid to try and adjust, not a clinical tool or a treatment, and results vary between people.

- Gollwitzer, P. M. (1999). Implementation intentions: Strong effects of simple plans. *American Psychologist, 54*(7), 493–503. https://doi.org/10.1037/0003-066X.54.7.493
- Gollwitzer, P. M., & Sheeran, P. (2006). Implementation intentions and goal achievement: A meta-analysis of effects and processes. *Advances in Experimental Social Psychology, 38*, 69–119. https://doi.org/10.1016/S0065-2601(06)38002-1
- Zimmerman, B. J. (2002). Becoming a self-regulated learner: An overview. *Theory Into Practice, 41*(2), 64–70. https://doi.org/10.1207/s15430421tip4102_2

## Licence

MIT. See the `LICENSE` file.
