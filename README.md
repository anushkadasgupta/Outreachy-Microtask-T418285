# Outreachy-Microtask-T418285

##  Overview

This repository contains the solution for **Outreachy Microtask T418285** as a part of the project "Addressing the lusophone technological wishlist proposals"

The task was to write a JavaScript script that processes a JSON object and displays the data in a human-readable format on a webpage.

---

##  What the Code Does

* Uses a predefined `data` array containing article details:

  * Title
  * Page ID
  * Creation date

* Loops through each article using a `for` loop

* Extracts and formats the date from `YYYY-MM-DD` to a readable format

* Converts numeric month values into month names

* Dynamically generates sentences like:

  ```
  Article "André Baniwa" (Page ID 6682420) was created at September 13, 2021.
  ```

* Displays the formatted output inside the HTML element with ID `results`

---

##  Technologies Used

* HTML
* JavaScript (Vanilla JS)

---

##  How to Run the Project

1. Download or clone the repository
2. Open the HTML file in any web browser
3. The output will be displayed under **"Results of my code:"**

---

##  Git Workflow Used

```bash
# Initialize repository
git init

# Add files
git add .

# Commit changes
git commit -m "Completed Microtask T418285"

# Connect to GitHub repository
git remote add origin https://github.com/YOUR_USERNAME/REPO_NAME.git

# Set main branch
git branch -M main

# Push to GitHub
git push -u origin main
```

---

## ✅ Status

✔️ Task completed successfully
✔️ Code tested in browser
✔️ Repository uploaded to GitHub

---
