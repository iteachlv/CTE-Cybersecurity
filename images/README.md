# Adding photos to the showcase

The homepage's "Showcase" section (`index.html`, id="showcase") currently uses
placeholder tiles instead of real images, so nothing is blocked on having
photos ready yet.

To swap in real photos:

1. Add your image files to this `images/` folder (e.g. `lab-day.jpg`,
   `ctf-team.jpg`, `capstone-project.jpg`). Keep filenames lowercase with
   hyphens, no spaces.
2. In `index.html`, find each `.gallery-tile` block inside the `#showcase`
   section and replace it with an `<img>`, for example:

   ```html
   <div class="gallery-tile" style="padding:0; border-style:solid;">
     <img src="images/lab-day.jpg" alt="Students working through a PC
     investigation lab" style="width:100%; height:100%; object-fit:cover;
     border-radius:10px;">
   </div>
   ```
3. Keep photos under ~500KB each so pages load quickly — most phone photos
   will need resizing/compressing first (any free image compressor works).
4. Get photo-release clearance per CCSD policy before posting identifiable
   student photos publicly.
