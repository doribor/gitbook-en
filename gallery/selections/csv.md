---
description: How to quickly export favorites data in CSV format
---

# Selections data in CSV

For every gallery, you can generate a CSV file containing useful information: selected photos and files, links to favorites lists, and folder URLs.

### Links to favorites lists

The CSV file allows you to quickly copy links to pre-created favorites lists. This is useful for sending links to events managers like school shoots, sports, and more.

* Upload your gallery and create the necessary favorites lists.
* To download the document, go to the **Favorites** section of your gallery, click on the three dots **(⋮)**, and select **Favorites links in CSV**.\
  The file will be named _galleryname\_links.csv_.

**Fields in the document:**

* `list_client` — name of the client who created the list.
* `list_url` — link to the favorites list.

<figure><img src="../../.gitbook/assets/links to selections csv en.png" alt=""><figcaption></figcaption></figure>

### Links to gallery folders

Use this CSV to quickly access links to all folders in the gallery.\
You can also hide all folders, giving each client access only to their own folder.

In the gallery, click on the three dots **(⋮)** and select **Folders list in CSV**.\
The file will be named _galleryname.csv_.

**Fields in the document:**

* `Folder` — name of the folder.
* `Url` — link to the folder.

<figure><img src="../../.gitbook/assets/links to folders csv en.png" alt=""><figcaption></figcaption></figure>

### File list in CSV

This file contains information about the folder where each file was selected, a list of files, and comments on both the list and individual files.\
It’s especially helpful if your gallery folders are hidden and you’re sending clients a direct link to their personal favorites folder.

Go to the **Favorites** section, click on the three dots **(⋮)**, and choose **File list in CSV**.\
The file will be named _galleryname\_files.csv_.

**Fields in the document:**

* `file_folder` — name of the folder where the file was selected.
* `file_name` — name of the selected file.
* `file_added` — date the file was added to the list.
* `file_list` — name of the favorites list (usually client’s name).
* `list_comment` — comment on the list.
* `file_comment` — comment on the selected files.

<figure><img src="../../.gitbook/assets/csv en.png" alt=""><figcaption></figcaption></figure>

### Summary file list in CSV

This format is great for sharing selected files with retouchers or other team members for post-processing.

In the **Favorites** section, click on the three dots **(⋮)** and select **Summary file list in CSV**.\
The file will be named _galleryname\_summary.csv_.

**Fields in the document:**

* `list_client` — name of the client who created the list.
* `list_name` — list title (e.g. “To retouch,” “To print”).
* `list_status` — list status (`In process`, `Completed`).
* `list_updated` — date of last update (new files, comments, or status change).
* `list_files` — names of the selected files.
* `list_comments` — client’s comment on the list or individual files.
* `list_url` — link to the favorites list.

<figure><img src="../../.gitbook/assets/csv summary en.png" alt=""><figcaption></figcaption></figure>

### CSV lists for deleted galleries

If a gallery was deleted, the data about selected files is saved in CSV format.\
Go to the **Trash** section in the Drive and click on the three dots **(⋮)** to download either the file list or the summary list.

<figure><img src="../../.gitbook/assets/csv deleted galleries en.png" alt=""><figcaption></figcaption></figure>



These CSV lists help you structure and organize selections, share links with clients, and prepare files for further processing.
