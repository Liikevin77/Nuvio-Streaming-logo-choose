# 📁 Community Logos

Welcome to the **Community Logos** section!

This folder is for community members who want to contribute **streaming-service logos** that can be used in your collection.

## 📌 How to contribute

Each streaming service should have its **own folder**.

### 1️⃣ Create a folder

Create a new folder for the streaming service you want to add.

Example:

```text
community-logos/
└── 🔴 Hbo max/
```

### 2️⃣ Upload the logo or GIF

Upload the streaming-service **PNG or GIF** into your new folder.

You can add one or multiple images if needed.

Example:

```text
🔴 Hbo max/
├── logo.png
└── logo.gif
```

### 3️⃣ Get the jsDelivr CDN link

After uploading your PNG or GIF:

1. Go to **[https://www.jsdelivr.com/github](https://www.jsdelivr.com/github)**
2. Enter or select this GitHub repository.
3. Find the **PNG or GIF** you uploaded.
4. Click **Get CDN Link**.
5. Copy the **jsDelivr CDN link**.

The CDN link is the link you should use in your collection.

Example:

```text
https://cdn.jsdelivr.net/gh/Liikevin77/Nuvio-Streaming-logo-choose@main/community-logos/Hbo%20max/logo.png
```

### 4️⃣ Add the CDN link

Create a file called:

```text
cdn-link.txt
```

Then paste the jsDelivr CDN link inside it.

Your folder should look like:

```text
🔴 Hbo max/
├── logo.png
├── logo.gif
└── cdn-link.txt
```

If you uploaded multiple images, you can include their CDN links in `cdn-link.txt`.

## ⚠️ Important

* 🚫 **Do not modify, replace, or remove anything inside `📁 streaming-logo-selector/`.**
* 📁 Put all community submissions inside `📁 community-logos/`.
* 📂 Create **one folder per streaming service**.
* 🖼️ PNG and GIF files are supported.
* 🔗 Get the CDN link from **jsDelivr GitHub** and use that link in your collection.
* 📝 Include a `cdn-link.txt` file with the CDN link(s).
* ✨ Use a clear streaming-service name.
* ✅ Make sure each CDN link points to the correct uploaded image.
* 🧹 Keep the repository structure clean.

## 📂 Example

```text
📁 Repository/
│
├── 📁 streaming-logo-selector/
│   └── 🔒 Official logos
│
└── 📁 community-logos/
    │
    ├── 🔴 Hbo max/
    │   ├── logo.png
    │   ├── logo.gif
    │   └── cdn-link.txt
    │
    ├── 🔵 My Streaming Service/
    │   ├── logo.png
    │   └── cdn-link.txt
    │
    └── 🟢 Another Service/
        ├── logo.gif
        └── cdn-link.txt
```

## ❤️ Thank You

Thank you for contributing and helping expand the available streaming-service logos!

**Create → Upload → Get the jsDelivr CDN link → Add it to your collection.** 🚀
