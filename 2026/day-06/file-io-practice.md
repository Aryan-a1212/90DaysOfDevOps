tee writes and displays output
cat reads full file
head shows first lines
tail shows last lines



Commands Practiced

touch notes.txt
Created an Empty file

echo "Line 1" > notes.txt
Wrote the first line into the file.

echo "Line 2" >> notes.txt
Appended a second line using >>.

echo "Line 3" | tee -a notes.txt
Displayed the line on terminal and appended it to the file

cat notes.txt
Displayed the full content of the file.

head -n 2 notes.txt
Displayed the first 2 lines of the file.

tail -n 2 notes.txt
Displayed the last 2 lines of the file.
