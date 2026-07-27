INFINITE GARDEN OF SORRY — FOLDER GUIDE
======================================

Ye poora folder GitHub pe upload karna hai (index.html + teeno subfolders),
taaki structure exactly waisa hi rahe.

FOLDERS:
  music/   -> yahan apna gaana daalo, naam "song.mp3"
  audio/   -> yahan apni voice recording daalo, naam "voice.mp3"
  photos/  -> yahan apni 5 photos daalo, naam "1.jpg" se "5.jpg" tak

Har folder ke andar ek chhoti .txt file hai jo bata rahi hai kya daalna hai —
unhe hata dena (ya rehne dena, koi farak nahi padta, site sirf .jpg/.mp3
files dhoondhti hai).

PASSWORD (index.html ke andar SITE_PASSWORD variable mein):
  forgiveme

  (Isko badal sakte ho — index.html file kholo, "const SITE_PASSWORD"
  line dhoondo, aur apni marzi ka password daal do.)

PERSONALIZE KARNE KE LIYE (index.html ke andar, "CONFIGURATION" section):
  - SITE_PASSWORD    -> apna password
  - LOVE_START_DATE  -> jis din baat hui thi/galti hui thi, wo date
  - HER_NAME         -> unka naam (ending message mein use hota hai)
  - INTRO_LINES       -> shuru ki 4 lines
  - GALLERY_PHOTOS    -> 5 photo captions
  - TIMELINE_EVENTS   -> "What Happened" wali story, apne hisaab se badlo
  - LETTER_LINES      -> letter scene ka poora text
  - ENDING_MESSAGE    -> final "Leave Forever" screen ka message

GitHub pe upload karne ka tareeka:
  1. Repo kholo -> "Add file" -> "Upload files"
  2. Ye poora folder (ya sab files ek saath, subfolder structure maintain
     karte hue) drag-drop karo
  3. "Commit changes" dabao

Bas ho gaya.
