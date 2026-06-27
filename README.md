> [!CAUTION]
> As of April 7th, 2026, Discord has expressed their intent to crack down on automating quest completion.
>
> Use at your own risk.

## Complete Recent Discord Quest
> [!NOTE]
> This does not work in the browser for quests which require you to play a game!
> Use the **desktop app** to complete those.
>
## Do Window Key + R > %appdata% > discord > settings.json 

<details>
<summary>📄 Click to Expand</summary>

```json
{
  "IS_MAXIMIZED": true,
  "IS_MINIMIZED": false,
  "WINDOW_BOUNDS": {
    "x": 112,
    "y": 60,
    "width": 1284,
    "height": 724
  },
  "DANGEROUS_ENABLE_DEVTOOLS_ONLY_ENABLE_IF_YOU_KNOW_WHAT_YOURE_DOING": true,
  "MIN_WIDTH": 940,
  "MIN_HEIGHT": 500,
  "chromiumSwitches": {},
  "BACKGROUND_COLOR": "#000000",
  "audioSubsystem": "experimental",
  "offloadAdmControls": true,
  "DESKTOP_TTI_DNSTCP_WARMUP": true,
  "DESKTOP_TTI_SPLASH_USE_WEBP": true,
  "DESKTOP_TTI_EARLY_UPDATE_CHECK": true,
  "DESKTOP_TTI_REMOVE_V8_CACHE_CLEAR": false,
  "asyncVideoInputDeviceInit": true
}
```

</details>

Save the settings.json and close the discord application 

## How to use this script:

1. Accept a quest under the **Quests** tab.
2. Press `Ctrl + Shift + I` to open **DevTools**.
3. Go to the **Console** tab.
4. Paste the following code and press **Enter**.

<details>
<summary>📦 Click To Expand</summary>

Download the **ZIP** file to access the code. I'm currently having issues pasting the code here.

</details>

 Follow the printed instructions depending on what type of quest you have.
   - If your quest says to **"play"** the game or watch a video, you can just wait and do nothing.
   - If your quest says to **"stream"** the game, join a VC with a friend or alt and stream any window.

Wait a bit for it to complete the quest.

You can now claim the reward!

You can track the progress by looking at the `Quest progress:` prints in the **Console** tab, or by looking at the progress bar in the **Quests** tab.



## FAQ
Q: Running the script does nothing besides printing "undefined", and makes chat messages not go through

A: This is a random bug with opening devtools, where all http requests break for a few minutes. It's not the script's fault. Either wait and try again, or restart discord and try again.

Q: Can I get banned for using this?

A: There is always a risk, though so far nobody has been banned for this or other similar things like client mods.

Q: Ctrl + Shift + I doesn't work

A: Either download the ptb client, or use this to enable DevTools on stable.

Q: Ctrl + Shift + I takes a screenshot

A: Disable the keybind in your AMD Radeon app.

Q: I get a syntax error/unexpected token error

A: Make sure your browser isn't auto-translating this website before copying the script. Turn off any translator extensions and try again.

Q: I'm on Vesktop but it tells me that I'm using a browser

A: Vesktop is not a true desktop client, it's a fancy browser wrapper. Download the actual desktop app instead.

Q: I get a different error

A: Make sure you're copy/pasting the script correctly and that you've have done all the steps.

Q: Can I complete expired quests with this?

A: No, there is no way to do that.

Q: Can you make the script auto accept the quest/reward?

A: No. Both of those actions may show a captcha, so automating them is not a good idea. Just do the two clicks yourself.

Q: Can you make this a Vencord plugin?

A: No. The script sometimes requires immediate updates for Discord's changes, and Vencord's update cycle and code review would be too slow for that. There are some Vencord forks which have implemented this script or their own quest completers if you really want one.

Q: Can you upload the standalone script to a repo and make this gist's code a one line fetch()?

A: No. Doing that would put you at risk because I (or someone in my account) could change the underlying code to be malicious at any time, then forcepush it away later, and you'd never know.
