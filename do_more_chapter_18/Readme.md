
# Chapter 18: Looking inside files (grep)

## Do More

### Use quotes to find "new file" and "old file" and "This is".

```
Tommys-MacBook-Pro:tmp tommy.haggerty$ grep "new file" *.txt
newfile.txt:This is a new file.
newfile.txt:This is a new file.
newfile.txt:This is a new file.
Tommys-MacBook-Pro:tmp tommy.haggerty$ grep "old file" *.txt
oldfile.txt:This is an old file.
oldfile.txt:This is an old file.
oldfile.txt:This is an old file.
Tommys-MacBook-Pro:tmp tommy.haggerty$ grep "This is" *.txt
newfile.txt:This is a new file.
newfile.txt:This is a new file.
newfile.txt:This is a new file.
oldfile.txt:This is an old file.
oldfile.txt:This is an old file.
oldfile.txt:This is an old file.
```

### Take the list of videos you created (or any other list) and use it to find some videos you want to find.

```
Tommys-MacBook-Pro:tmp tommy.haggerty$ grep "intro" videofile.txt
./workspace/davinci_videos/in_class/agile_intro.mp4
./workspace/davinci_videos/in_class/mentorship_intro.mp4
./workspace/davinci_videos/in_class/pivotal_intro.mp4
./workspace/davinci_videos/in_class/slack_intro.mp4
./workspace/davinci_videos/in_class/syllabus_and_toolbelt_intro.mp4
```

### Unix: You can use -i to ignore case with grep. Try grep -i new *.txt

```
Tommys-MacBook-Pro:tmp tommy.haggerty$ grep "NEW" *.txt
Tommys-MacBook-Pro:tmp tommy.haggerty$ grep -i "NEW" *.txt
newfile.txt:This is a new file.
newfile.txt:This is a new file.
newfile.txt:This is a new file.
```
