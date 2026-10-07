# Loans Central Dashboard: live demo

A simulation of our loans notification Chrome extension, built for client demos and screen recordings.
Four fictional lender portals receive replies to their marketing texts. Loans Central Dashboard
collects every reply in one place, opens priority customers by itself, checks today's notes for earlier
contact, and texts back asking for the customer's full name and the last 4 of their SSN.

All lenders, customers and numbers are fictional. The `.example` web addresses are reserved and never
belong to a real company.

## Run it

- Double-click `index.html`. It opens in Chrome or Edge with nothing to install. Internet is only
  used for the fonts; offline it falls back to Segoe UI.
- Add `#autostart` to the end of the address to skip the title card and start straight away.

## Presenting

- **Start demo** runs the guided tour (about 2 minutes at 1×), then carries on with live traffic.
- The controls sit in the bottom-right corner. ▴ opens the full panel.
  - **Guided tour / Live traffic / You send**: in *You send* nothing arrives until you send it.
    Use the four quick buttons, or type any text such as "I need funds".
  - Tick **Customer already contacted today** before sending to show the double-contact block.
  - Turn **Auto Send** off to show a drafted reply waiting for the agent. Press **Cancel** during the
    countdown to show the agent can stop it.
- Click any card on the central dashboard to open that customer by hand.

| Key | Action |
| --- | --- |
| Space | Play / pause |
| H | Hide or show the controls |
| C | Captions on / off |
| R | Restart |
| 1–4 | Priority text from that portal |
| N | Random text |
| F | Full screen |

## Recording a video

1. Make the browser window 1920×1080, or press F for full screen.
2. Start recording: Win + Alt + R (Xbox Game Bar), or OBS.
3. Click **Start demo**, then press H to hide the controls.
4. The step captions explain each stage, so the video works without narration.

## Branding

The Astra logo and favicon are built into `index.html`, so that one file is all you need to copy or
send. `astra-favicon.png` and `ASTRA LOGO.jpg` stay in this folder as the originals.

## Changing names, keywords or wording

Open `index.html` in a text editor. The `SETTINGS` block at the top of the script holds the lender
names, the reply template, the countdown length and the keyword lists. The product name and agent name
can also be changed from the controls panel. Those changes are remembered in that browser.
