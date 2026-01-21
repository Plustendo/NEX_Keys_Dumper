# NEX_Keys_dumper.3dsx

NEX Keys Dumper is a **3DS homebrew application** that displays your NEX PID information and exports it to a text file for later use.

📚 **Source used:**
[https://github.com/Stary2001/nex-dissector](https://github.com/Stary2001/nex-dissector)

---

## What does this homebrew do?

This homebrew:

* Displays your NEX PID and related authentication data on screen
* Creates a file named `nex-keys.txt` at the root of your SD card
* Allows you to easily retrieve the information needed for NEX-based services

---

## Requirements

* A modded Nintendo 3DS / 2DS
* Homebrew Launcher installed
* SD card access

---

## Installation

1. Download the file **`NEX_Keys_dumper.3dsx`** by going in the [releases](https://github.com/Plustendo/NEX_Keys_Dumper/releases/latest)
2. Copy it to the following folder on your SD card:

```
SD:/3ds/
```

Your final path should look like:

```
SD:/3ds/NEX_Keys_dumper.3dsx
```

---

## How to use

1. Launch the **Homebrew Launcher** on your 3DS.
2. Look at the top screen and verify the path.

If it does **not** show:

```
sdmc:/3ds/
```

Then:

* Press the **B** button until you reach:

```
sdmc:/
```

* Use the **touch screen** to open the folder named **3ds**.

3. Scroll down and launch **NEX Keys Dumper**.

---

## Output

* Your NEX information will be displayed on the **top screen**.
* A file named:

```
nex-keys.txt
```

will be created at the **root of your SD card**.

---

## Notes

* This tool only reads and exports data.
* It does not modify your system.
* Keep your `nex-keys.txt` file private.
