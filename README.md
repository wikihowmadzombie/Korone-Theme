# Koromons-Theme


##  How to Use the Stylish Chrome Extension + Add a Custom Base64 Image

###  Step 1: Install Stylish

1. Open the [**Stylish Chrome Extension**](https://chrome.google.com/webstore/detail/fjnbnpbmkenffdnngjfgmeleoegfcffe) page.
2. Click **“Add to Chrome” → “Add Extension.”**
3. Once installed, open the **Stylish icon** in your browser toolbar.
4. Click **“Manage all styles” → “Write new style.”**

---

###  Step 2: Open the Code

1. Copy the code file you’ll be given (the `.css` or `.js` snippet).
2. Paste it inside the **Stylish editor**.
3. Look for this comment in the code:

   ```css
   /* INSERT YOUR BASE64 IMAGE BELOW */
   ```

   That’s where you’ll put your Base64 image code.

---

###  Step 3: Convert an Image to Base64

1. Go to  [https://www.base64-image.de/](https://www.base64-image.de/)
2. Click **“Upload Image”** and select your image file.
3. Once it loads, click **“Copy image as Base64.”**
4. You’ll get something that starts with:

   ```
   data:image/png;base64,iVBORw0KGgoAAAANSUhEUg...
   ```

---

###  Step 4: Insert the Base64 Code

1. In the Stylish editor, find the marked line again:

   ```css
   /* INSERT YOUR BASE64 IMAGE BELOW */
   ```
2. Paste your Base64 image code **right below it** like this:

   ```css
   background-image: url("data:image/png;base64,iVBORw0KGgoAAAANSUhEUg...");
   ```
3. Save your style and click **“Apply style”**.

---

###  Step 5: Test It

1. Go to the site the style is meant for.
2. Refresh the page — your new image or design should now appear!
3. If not, check you pasted the Base64 correctly (no missing quotes or spaces).

---

