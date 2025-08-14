# MP3 Tag Reader in C

## 📌 Overview
This is a simple MP3 Tag Reader implemented in C that extracts metadata from MP3 files, such as:
- Title
- Artist
- Album
- Year
- Genre
- Comment

## 🚀 Features
- Reads ID3v1 tags from MP3 files.
- Displays metadata in a clean table format.
- Supports basic error handling for missing or invalid tags.

## 🛠️ How to Compile

View MP3 Tags
```bash
./mp3_tag_reader -v <file_name.mp3>
```

Edit MP3 Tags
```bash
./mp3_tag_reader -e <tag_code> <file_name.mp3> <new_tag_data>
```

## Tag Codes

| Tag Code | Tag Field | Description                  |
| -------- | --------- | ---------------------------- |
| `-a`     | Artist    | Name of the song’s artist    |
| `-t`     | Title     | Song title                   |
| `-A`     | Album     | Album name                   |
| `-y`     | Year      | Year of release              |
| `-m`     | Genre     | Genre of the song            |
| `-l`     | Lyricist  | Lyricist name                |
| `-c`     | Composer  | Composer name                |
| `-C`     | Comments  | Additional comments or notes |


Example (Change Artist name)
```bash
./mp3_tag_reader -e -a sample.mp3 Ed Sheeran
```

## 📸 Example Output (Viewing)
```text
===========================================================================
| Tag Name       :      Tag Data                                          |
===========================================================================
| Title          :      Sunny Sunny - Yo Yo Honey Singh - [SongsPk.CC]    |
| Artist         :      Yo Yo Honey Singh - [SongsPk.CC]                  |
| Album          :      Yaariyan                                          |
| Year           :      2013                                              |
| Genre          :      Bollywood Music - [SongsPk.CC]                    |
| Comments       :      eng                                               |
===========================================================================
```


---

That will keep the **box formatting** intact on GitHub and make your repo look more polished.  

If you want, I can now **finalize your README** so it contains:  
- A quick CLI usage table at the top  
- This sample output  
- Both view and edit instructions  

That way it’s GitHub-ready in one go. Do you want me to do that?