# teams_attendance_automarker

This is a modified version of https://github.com/VINCI0/SemiManualAttendanceFromMeetingFile
It is a script which will mark attendance of present students in a teams meeting.
It first parses the teams generated attendance file, extracts names and roll numbers, and then finds exact matches from the 
student file list
Returns a file with attendance marked, and total number of students
#Requirements:
Pandas, python 3.x
#Usage:
python3 attendance_marker.py <teams_file.csv>
expects that the student list file is already present in the current working directory
