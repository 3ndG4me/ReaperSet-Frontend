# ReaperSet-Frontend
HTML frontend for ReaperSet that allows for listing and jumping to songs in a setlist with a single button click

# About
Reaper set was built to extend the functionality ReaperSet [https://github.com/3ndG4me/ReaperSet](https://github.com/3ndG4me/ReaperSet) or [https://github.com/sethcenterbar/ReaperSet](https://github.com/sethcenterbar/ReaperSet).

The main idea is to create a frontend that mirrors the minimum core functionality of the commercial tool AbleSet for live playback using the Reaper DAW instead of Ableton. The whole goal is to provide an open source, and more affordable alternative to expensive live playback software with little to no compromise in functionality.

When used succesfully with ReaperSet, this frontend allows Reaper to have the following functionalities for live playback and setlist building:
1. Dynamically display song names for a setlist based on Region names generated from ReaperSet.
2. Jump to a specific song/region by clicking a button in the web UI.
3. Edit mix controls, record, play, pause, skip, and back functions (all from the original "fancier.html" provided with Reaper)

Reaper + ReaperSet + ReaperSet-Frontend creats a live playback experience that supports:
- Video for live visuals
- Normal tracks and audio playback
- Dynamic multi-project setlist generation (no more hoarding one giant playlist file)
- Seamless playback between tracks (no more waiting for a project to close and then open like with Ableset's multi-project mode)
- A responsive Web UI accessible from any browser, desktop or web, so you may adjust your performance live from a device other than your playback rig (imagine adjusting you IEM mix from your phone, or stopping or skipping a song in the set while not being in front of your laptop)


It looks sort of like this depending on how you configure your ReaperSet template but as long as a region exists and has a name, the Web UI will populate with the setlist. Simply place the `reaperset.html` file in the `reaper_www_root` folder and it will be accessible via the Reaper Control/OSC/Web Settings.

## Inactive
![Screenshot 2024-08-31 at 1 01 11 AM](https://github.com/user-attachments/assets/3eaa9341-1eaa-49c3-8993-3b73474f4499)

## Active
![Screenshot 2024-08-31 at 1 22 08 AM](https://github.com/user-attachments/assets/667623b2-6747-4435-b122-aa7bb3f29e5a)

## Inactive (Mobile)
![Screenshot 2024-08-31 at 1 23 22 AM](https://github.com/user-attachments/assets/d43013ac-c2d8-4e57-8283-8cb9bf5d2aa0)

## Active (Mobile)
![Screenshot 2024-08-31 at 1 22 20 AM](https://github.com/user-attachments/assets/f6856e9a-6527-4bb4-907b-4e1deddef730)



