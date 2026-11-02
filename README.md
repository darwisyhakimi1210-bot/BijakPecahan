# BijakMath — How to Run This App

> This guide is written for anyone — no computer knowledge needed.
> Just follow the steps one by one and the app will work.

---

## What is BijakMath?

BijakMath (Bijak Pecahan) is a **school learning app** about fractions (pecahan).
It runs inside a web browser, just like a website — but on your own computer.

It includes:

- Video lessons on fractions
- Quizzes and exercises
- Interactive games (memory cards, drag & drop)
- A 3D animated character called **Mr P** as your guide

---

## Before You Start — What You Need

You need **2 things**:

| What                       | Why                                               |
| -------------------------- | ------------------------------------------------- |
| A Windows computer         | The app runs on Windows                           |
| **Laragon** (free program) | Runs the app like a mini website on your computer |

> **Internet connection** is also needed the first time you open each page
> (to load the font style and 3D graphics library).

---

## STEP 1 — Install Laragon

> Skip this step if Laragon is already installed on the computer.

1. Open your browser and go to this website:

   ```
   https://laragon.org/download
   ```

2. Click **"Download Laragon Full"**

3. Once downloaded, open the file and install it
   (just keep clicking **Next** and then **Install** — no special settings needed)

4. When installation finishes, **Laragon will open automatically**

---

## STEP 2 — Put the App Files in the Right Place

1. Find the **BijakMath** folder (the one you received)

2. Copy or move it into this location on your computer:

   ```
   C:\laragon\www\
   ```

   After this, the folder should be at:

   ```
   C:\laragon\www\BijakMath\
   ```

> **How to get there:** Open File Explorer → click on **This PC** → open **Local Disk (C:)** → open **laragon** → open **www** → paste the BijakMath folder here.

---

## STEP 3 — Start Laragon

1. Find **Laragon** in your Start Menu (search "Laragon") and open it

2. A small control panel will appear on screen

3. Click the big button that says **"Start All"**

4. Wait a few seconds — you will see **Apache** turn green

   ```
   Apache   ●  Running   ← it should look like this
   ```

5. Laragon is now ready

---

## STEP 4 — Open the App in Your Browser

1. Open **Google Chrome**, **Microsoft Edge**, or **Firefox**

2. Click on the **address bar** at the very top of the browser
   (the long white box where you type website addresses)

3. Delete whatever is there and type this **exactly**:

   ```
   http://localhost/BijakMath/index.html
   ```

4. Press **Enter**

5. The BijakMath home page will open with Mr P greeting you!

---

## How to Use the App

Once the app is open, here is how it works:

```
Home Page
    ↓
Click "MULA" (means Start)
    ↓
Pelajaran — choose a lesson topic
    ↓
Watch the video lesson
    ↓
Go to "Latihan" (from the top menu) to practice
    ↓
Do quizzes and play games!
```

**Top Menu buttons:**

- **HALAMAN UTAMA** = Home
- **PELAJARAN** = Lessons
- **LATIHAN** = Practice / Games

---

## When You Are Done

1. Close the browser tab
2. Go back to the Laragon control panel
3. Click **"Stop All"**
4. Close Laragon

---

## Something Not Working? Check These First

### The page says "This site can't be reached"

- Laragon is not running
- Go back to **Step 3** and click "Start All"

---

### The 3D character (Mr P) does not appear

- You opened the file the **wrong way**
- Do NOT double-click the HTML file to open it
- You MUST type the address in the browser:
  ```
  http://localhost/BijakMath/index.html
  ```

---

### No sound is playing

- Click anywhere on the page once
- Browsers need a click before they allow sounds to play

---

### The page looks empty or broken

- Check that the BijakMath folder is inside `C:\laragon\www\`
- Make sure Laragon is running (Apache is green)
- Press **F5** on your keyboard to refresh the page

---

### Fonts look wrong (not pixel/game style)

- Check your internet connection
- The app needs internet to load its special font style

---

## Quick Checklist (Before Opening the App)

- [ ] Laragon is installed
- [ ] BijakMath folder is inside `C:\laragon\www\`
- [ ] Laragon is open and Apache shows green "Running"
- [ ] Browser address bar shows: `http://localhost/BijakMath/index.html`

If all 4 are checked, the app will work perfectly.

---

_BijakMath — Making Fractions Fun!_
