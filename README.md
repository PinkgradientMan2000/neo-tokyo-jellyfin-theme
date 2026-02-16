This is a current work-in-progress build for a Neo-Tokyo inspired look for Jellyfin users. Currently, this is build 10.11.6 and looks almost perfect (aside from some color issues) on mobile. However, there are a couple of glitches being worked on for the desktop site. Anyone who would like to use this can do so and even build upon it. This theme was made possible with AI assistance (since I don't know much about coding CSS), so there are bound to be things that can be improved within the code. For now, I'm unsure if importing the GitHub URL will work to add the theme to your Jellyfin server, so I have been using the raw code itself.

## How to Set the Theme in Jellyfin

To use this theme in Jellyfin, follow these steps:

1. Go to **Dashboard** > **Branding** in your Jellyfin server settings.
2. Scroll down to the **Custom CSS** section.
3. Paste the following code:

```css
@import url('https://cdn.jsdelivr.net/gh/PinkgradientMan2000/neo-tokyo-jellyfin-theme@main/Neo-Tokyo.css');
```

4. Save your changes. The Neo-Tokyo theme should now be applied.


Down below will have images of how this theme currently looks.



Login (Credentials)
<img width="787" height="1025" alt="Login (Credentials)" src="https://github.com/user-attachments/assets/cdc0e1a3-4043-4c25-a5e4-3a068adff3be" />


Login (Profile Selection)
<img width="1041" height="1143" alt="Login (Profile Selection)" src="https://github.com/user-attachments/assets/beffcdc7-8e2c-45a9-8455-d020737550a0" />


Home Screen
<img width="2493" height="1241" alt="Home Screen" src="https://github.com/user-attachments/assets/0736b0b9-4b7a-46b0-b7bf-8bb93f41cc31" />


Title Selection
<img width="2487" height="1227" alt="Title Selection" src="https://github.com/user-attachments/assets/ce818430-3431-4689-85c3-0ea3e501c36e" />


Sidebar Area
<img width="1067" height="1237" alt="Sidebar" src="https://github.com/user-attachments/assets/ea86a607-6e28-4af7-8c8d-95cda8e9ed6a" />


Settings Area
<img width="2495" height="1230" alt="Setting Area" src="https://github.com/user-attachments/assets/01064b33-e3da-4ce7-8ecd-50feed6b4df9" />


Search Area
<img width="2495" height="1202" alt="Search Area" src="https://github.com/user-attachments/assets/59af26cc-d9aa-40e4-85b3-32537c233ad5" />




There are currently a couple issues with the desktop site which I'm aware of but cannot get it looking correct which I will show below. If there is anyone that would like to contribute in making this work a bit better for the desktop side, please let me know.

Known issue #1 (Screen after selecting a title) [Only on PC web side]

  -Title in cyan runs off the screen instead of wrapping correctly
  
  -Color of certain areas seem to be a purple color
  
  -Poster of the media seems to overlap over other areas
<img width="2492" height="1232" alt="Issues 1" src="https://github.com/user-attachments/assets/05c3e588-ed6b-45d0-87aa-d658495e0725" />


Known issue #2 (same as one small issue in #1)

  -Selection areas seem to be a purple color
<img width="2492" height="1222" alt="Issues 2" src="https://github.com/user-attachments/assets/32f63d74-f983-46db-81ca-674f4cc32867" />
