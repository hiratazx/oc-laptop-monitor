A curated list of monitors or laptop displays with their overclockable specifications. This repository aims to provide details on monitors that users have successfully overclocked or tested.

---

## List of Overclockable Monitors/Laptop Displays

This is a list of overclockable monitors and laptop displays that have been tested by the community.  

• **Lenovo CMN14D6** (as known as Lenovo IdeaPad S145-14API 81UV display)  
  - **Max Resolution:** 2560x1440  
  - **Max Refresh Rate:** 72 Hz  
  - **Max Bit Depth:** 6 bit
  - **Tested by:** [ItzKaguya](https://github.com/hiratazx)

---

## How to Overclock Your Monitor

To overclock your monitor, you’ll need a tool called **Custom Resolution Utility (CRU)**. Follow these simple steps:

### Step 1: Download CRU
Download the tool from [Custom Resolution Utility (CRU)](https://www.monitortests.com/forum/Thread-Custom-Resolution-Utility-CRU). Extract the downloaded file and run **CRU.exe**.

### Step 2: Open CRU
When you open CRU, you’ll see a list of detailed resolutions for your current display configuration. Select the topmost entry under the **Detailed resolutions** pane and click **Edit**.

### Step 3: Copy the Configuration
In the edit window:
1. Click **Copy** to save the current resolution settings.
2. Close the window and click **Add** in the **Detailed resolutions** pane.

### Step 4: Add a New Refresh Rate
1. Click **Paste** in the new window.
2. Change the **Refresh Rate** value (at the bottom) by increasing it by 1–2 Hz. Avoid making large changes initially.
3. Click **OK** to save and exit the window.

### Step 5: Reboot Your System
Restart your computer to apply the changes.

### Step 6: Test the New Refresh Rate
1. Go to **Settings > System > Display > Advanced Display Settings**.  
2. Check if the new refresh rate is listed.  
3. Select the new refresh rate and apply it.  

### Step 7: Gradually Increase the Refresh Rate
If the new refresh rate works, repeat the steps to increase the frequency by 1–2 Hz at a time. Be cautious, as pushing the monitor too far may cause instability or no signal.

---

## Contributing

We welcome contributions to this list! If you have successfully overclocked a monitor or laptop display and want to share the specs:
1. Fork the repository.
2. Add your monitor's details in the format below:
    ```markdown
    • **Model Name** (additional details if applicable)  
      - **Max Resolution:** [Insert resolution]  
      - **Max Refresh Rate:** [Insert refresh rate]  
      - **Max Bit Depth:** [Insert bit depth]
      - **Add additional info if applicable**
      - **Tested by:** [GitHub Username](GitHub Profile Link)
    ```
3. Submit a pull request.

---

## Disclaimer

- Overclocking monitors can void warranties or damage hardware. Proceed at your own risk.
- All data is user-submitted and may vary depending on specific hardware or configurations.
