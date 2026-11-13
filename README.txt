FUTURECARE ATTENDANCE UPDATE

Upload/replace these five files in the root of your Daily-attendance GitHub repository:
- index.html
- manifest.webmanifest
- sw.js
- icon-192.png
- icon-512.png

Keep your existing futurecare-logo.png.jpg file and do not delete it.
The updated app:
- Calculates paid hours only until 5:00 PM when Last-night viewing is checked.
- Calculates paid hours only until 7:00 PM when Last-night viewing is not checked.
- Uses the earlier actual Time Out when the employee leaves before the cutoff.
- Deducts unpaid breaks.
- Adds ₱300 per last-night viewing record separately.
- Provides buttons to fill Time In and Time Out using the phone's current local time.

Important: The Time In/Time Out buttons fill the fields with the phone time. The attendance record is saved to Supabase when the Secretary taps Save attendance, preserving the current database workflow.
