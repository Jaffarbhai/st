SAJAWAT BY HASHIR — WEBSITE
===========================

FILES
  index.html   The complete website (one file). Open it in any browser.
  images/      All site pictures, named by where they appear.

PUT IT ONLINE
  Upload the whole folder to any host: Netlify (drag and drop the folder at
  app.netlify.com/drop), Hostinger, cPanel "public_html", GitHub Pages, etc.
  An internet connection is needed for the fonts and animations.

CHANGE YOUR DETAILS
  Open index.html in a text editor (Notepad, VS Code) and search for
  "EDIT YOUR BUSINESS DETAILS HERE". Edit the SITE section:
    whatsapp   923123380876   (country code, digits only)
    phone      0312 3380876
    email      ""             (add one to show it in the footer)
    address    Jinnah Square, Malir, Karachi
    instagram / facebook / tiktok   your profile links

CHANGE THE PICTURES  (images folder)
  The number at the start of each file shows where it appears:

    01-hero-desktop/mobile.jpg      Top banner (drawn floral stage)
    02-about.jpg                    About section photo (fairy-light corridor)
    03-stage-4-mehndi-jhoola.jpg    Signature Stages: Mehndi
    03-stage-8-birthday.jpg         Signature Stages: Birthday
    03-stage-9-gala.jpg             Signature Stages: Gala
    03-stage-10-dholki-night.jpg    Signature Stages: Dholki Night
    03-stage-*-bg.jpg               Blurred backdrop behind a portrait photo
    04-flowers-2..6-*.jpg           Gallery ("The Art of Flowers") photos
    06-final-desktop/mobile.jpg     Last big photo (drawn)

  TO REPLACE: put your photo in images/ with EXACTLY the same file name.

VIDEOS  (videos folder)
  Each video has a .jpg with the same name: the still shown while it loads.

    02-drone-floral-tunnel.mp4         Drone View: Drone Film 1
    02-drone-aerial-marquee.mp4        Drone View: Drone Film 2 (arches + lit marquee)
    03-stage-1-nikah.mp4               Stages: Weddings
    03-stage-2-baat-pakki.mp4          Stages: Baat Pakki
    03-stage-3-mayoon.mp4              Stages: Mayoon
    03-stage-5-baraat.mp4              Stages: Baraat
    03-stage-6-walima.mp4              Stages: Walima
    03-stage-7-milad.mp4               Stages + Events + Naat: Milad
    03-stage-11-bridal-room.mp4        Stages: Bridal Room
    04-flowers-1-roses-closeup.mp4     Gallery: first tile
    04-flowers-7-pink-drapes.mp4       Gallery: pink & white drapes
    05-event-1-weddings.mp4            Event card: Weddings
    05-event-2-dholki-night-mehndi.mp4 Event card: Mayoon & Mehndi
    05-event-3-floral-entrance-walima.mp4 Event card: Baraat & Walima
    05-event-5-birthdays.mp4           Event card: Birthdays
    05-event-6-corporate.mp4           Event card: Corporate
    07-lights-1/2/3-*.mp4              DJ / Lights section videos
    08-naat-mehfil-e-milad.mp4         Naat: Zohaib Ashrafi highlight (+ "Play Naat")
    08-qawwali-night.mp4               Naat: qawwali
    08-naat-eco-sound.mp4              Naat: Eco Sound naat khwani
    08-naat-12-rabi-stage.mp4          Naat: 12 Rabi-ul-Awal stage
    08-naat-12-rabi-illumination.mp4   Naat: chiraghan / building lights

  All videos and photos carry a light "Sajawat by Hashir" watermark. Clips
  with naat, qawwali or music keep their sound; noise-only clips are muted.
  Where we ran out of photos, a "More on WhatsApp" tile asks visitors to
  message you for the full portfolio.

ADD CLIENT REVIEWS
  Find REVIEWS and add real reviews like:
    { quote: "They turned our walima hall into a garden.", name: "Ayesha & Bilal", event: "Walima · 2026" },

BOOKING FORM
  The "Book Your Event" section asks 7 questions, then opens WhatsApp with
  the answers addressed to the number in SITE.whatsapp (923123380876).
  To change the questions or options, search for BOOK_STEPS in index.html.

WELCOME QUESTION & EVENT THEMES
  On opening, visitors pick their event (English + Urdu). The site then
  switches flower colours, accent colour, petals, DJ lights mood, puts that
  event's stage and card first, and pre-fills the booking form.
  Milad & Naat: the DJ section becomes "Eco Sound · Professional Naat
  Khwani" (no DJ booth, no beat) with a "Play Naat" button.
  Edit the themes by searching for "const THEMES" in index.html.

PAGE ORDER
  Decoration banner -> Drone View (3D arch walk) -> Book Your Event -> Sajawat by Hashir DJ (3D) -> About -> Stages -> Gallery -> Events -> Naat -> ...

DJ, LIGHTS & SOUND (3D model, right under the top banner)
  A real 3D model (three.js): box truss on 4 towers, moving-head lights with
  beams, hanging line-array and floor speakers, DJ booth. Drag to look around. The vibe buttons
  (Nikah / Mehndi Dhol / Baraat / Dance Floor) change the lights, and
  "Play the beat" plays a sample rhythm made in the browser (no song files).
  Edit the three cards by searching for "Moving-head sharp beams" in index.html.
