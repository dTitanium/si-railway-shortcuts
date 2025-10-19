# Staten Island Train Siri Shortcut 🚆

This Siri Shortcut lets you know:
> “When is the next train from [Origin] to Tottenville Direction?”

and instantly get how many minutes away the next Staten Island Railway local train is — based on real timetable data.

---

## 🔧 Features
- Supports **weekday, Saturday, and Sunday** schedules.
- Works for **St. George → Tottenville** direction.  
- Automatically switches to **next day schedule** after the last train.
- JSON file is **external**, so it can easily be updated or replaced.
- Runs directly via Siri or the Shortcuts app.

---

## 🧠 How It Works
1. Shortcut reads timetable data from the `timetable_v1.0.json` file stored in iCloud Shortcuts folder.
2. You choose your **origin** station.
3. It calculates the **next available train** and how many minutes away it is.
4. If it’s after the last train, it automatically uses the **next day’s schedule**.

---

## 📂 Installation
1. Download the latest `NextTottenvilleTrain.shortcut` and `timetable_v1.0.json` files from this repository.
2. Save `timetable_v1.0.json` to your **iCloud Drive → Shortcuts** folder.
3. Add the shortcut to your Shortcuts app.
4. Open it once manually to grant file access permissions.
5. Then, just Tap shortcut and pick the origin station.
---

## 🧩 Future Plans
- Add **Tottenville → St. George** direction.
- Add **Ferry connections** and real-time updates.
- Accept community pull requests for improved logic or UI.

---

## 🤝 Contributing
Pull requests are welcome!  
If you’d like to contribute:
1. Fork this repo.
2. Modify the `.shortcut` or `timetable.json`.
3. Submit a PR describing your change.

---

## 📸 Screenshots / Demo
![Added to the Home Screen](<Screenshot Shortcut.png>) ![Where time table name goes](<Screenshot JSON timetable name.png>) ![alt text](<Screenshot Station List 2.PNG>) ![alt text](<Screenshot Station List 1.PNG>) ![Timetable  JSON in icloud Shortcuts Folder](<Timetable  JSON.png>)



---

**Created by [Dinuk K. Senadheerage](https://github.com/dTitanium) (https://www.linkedin.com/in/dinuknadishan/)**  
📍 New York, USA
