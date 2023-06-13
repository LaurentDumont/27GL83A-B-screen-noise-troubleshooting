# Hardware
- Amazon purchased LG 27GL83A-B --> https://www.amazon.ca/dp/B07YGZL8XF?psc=1&ref=ppx_yo2ov_dt_b_product_details
- New, not refurbished. No indication that product was used before.

# Symptoms
- Visual noise when changing resolution / refresh rate / changing input (HDMI --> DP / DP --> HDMI)
- Flashing visual artefacts when switching into a full screen application
- Power cycling the monitor fixes the issue 1/10. 
- "Fixing" the problem often requires turning off the monitor for X hours.
- When in a "glitched" state, the OSC screen fails to render. This is done outside of the HDMI/DP output. It is unlikely that it would be related to the GPU outputting the signal.

# Troubleshooting performed
- Factory reset multiple times
- Turning off 
  - Adaptative Sync
  - HDR
  - Response Time
  - Digital Fine Contract (DFC --> Auto brightness adjuster)
  - Smart Energy Saver
- Same issue with three different computers (Linux, Windows, Mac)
- Same issue with DisplayPort1.4 and HDMI
- Tried different DP and HDMI cables
- Monitor running most recent firmware
- LG on-screen-control software reports no issues and offers no updates
- Changing between 60hz or 144hz seems to trigger the issue. Locking to a specific refresh rate does not help. Issue still triggers randomly. 
