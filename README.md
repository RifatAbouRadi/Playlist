# Playlist
This project is a small playlist manager built to practice singly linked lists in C.
The program loads tracks from a text file, stores them in a linked list, modifies the playlist (insert/delete), and then saves the updated playlist back to a new file.


# 🎧 What the Program Does

Loads tracks from playlist.txt

Each line in the file contains an index + a track title (e.g., 1 Billie Jean)

The code strips the index and stores only the title inside a linked list.

Prints all loaded tracks.

Deletes a song at a chosen index.

In the template: deletes the track at index 4.

Inserts a new song into the playlist.

In the template: inserts
"Tarkan – Şımarık"
at position 3.

Saves the updated playlist to playlist-out.txt with new numbering.

📚 Concepts Practiced

Linked list creation and traversal

Dynamic memory allocation (malloc, free)

File reading (using fopen, fgets)

File writing (using fprintf)

Pointer manipulation (especially Node **list)

This assignment is mainly about understanding how linked lists work in real programs.

▶️ How to Run

Open your terminal in the project folder and run:

make
./main


After execution, a new file playlist-out.txt will be created containing the updated playlist.
