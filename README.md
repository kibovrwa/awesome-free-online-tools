# Awesome Free Online Tools

Browser tools grouped by the job.

A list of free tools for one concrete task: strip a photo's metadata, name a Reel, generate a Minecraft schematic, repair a Snapchat Memories export, turn captions or a ChatGPT answer into Word, read a GAI gap, cast a birth chart, or try a different haircut. The first links in each category are pages that run in the browser. After those, a few independent tools do a neighboring job. Some of those, such as ExifTool and Pandoc, run on your machine.

The sentence after a link is the limit. It says what the page actually does, what is free, what stays on your device, and what it will not do. A watermark in the pixels is not metadata. An internet IQ score is not a WAIS. A Reel link is not a TikTok link.

The nine sites are Remove AI Meta, Reel Song Finder, Minecraft Schematic Generator, Snapchat Memories Download, SRT to Word, ChatGPT to Word, GAI vs IQ, AstralHoro, and EasyFace. Several have a free tier and a one-time paid option. That is stated where it changes what you can do.

## Contents

- [Image privacy and AI metadata](#image-privacy-and-ai-metadata)
- [Music and video identification](#music-and-video-identification)
- [Minecraft building](#minecraft-building)
- [Snapchat Memories export](#snapchat-memories-export)
- [Subtitles and transcripts](#subtitles-and-transcripts)
- [ChatGPT export to Word](#chatgpt-export-to-word)
- [Psychology and IQ score tools](#psychology-and-iq-score-tools)
- [Astrology and birth charts](#astrology-and-birth-charts)
- [AI photo and face editing](#ai-photo-and-face-editing)
- [Guides and write-ups](#guides-and-write-ups)
- [Contributing](#contributing)
- [License](#license)

## Image privacy and AI metadata

Read or strip what sits beside the pixels: EXIF, GPS, IPTC, XMP, C2PA, and PNG text. None of this removes a pixel watermark such as SynthID, and a platform can still label a picture from its own copy.

- [Remove AI Meta](https://removeaimeta.com/) — Drop a photo, strip C2PA, IPTC, EXIF, and PNG text in the browser, then re-scan the download. One image is free. It does not remove SynthID.
- [View image metadata](https://removeaimeta.com/view-image-metadata-online) — Read GPS, camera, XMP, IPTC, C2PA, and AI markers on your device. The file is not uploaded.
- [AI metadata cleaner](https://removeaimeta.com/ai-metadata-cleaner) — Strip C2PA, IPTC DigitalSourceType, and generator XMP from JPEG, PNG, WebP, and HEIC, then re-scan the file you saved.
- [Check C2PA Content Credentials](https://removeaimeta.com/check-c2pa-content-credentials) — Look for a C2PA manifest in a JPEG, PNG, or WebP. An empty line means this file had none, not that a person made the picture.
- [Remove C2PA](https://removeaimeta.com/remove-c2pa) — Delete the C2PA / JUMBF manifest and show a before-and-after report. Pixel watermarks stay.
- [Remove EXIF and GPS](https://removeaimeta.com/remove-exif) — Drop GPS, camera, and device fields from JPEG, PNG, and WebP. Stripping runs locally.
- [Bulk EXIF remover](https://removeaimeta.com/bulk-exif-remover) — Clean a folder of JPEG, PNG, WebP, and HEIC — EXIF, GPS, XMP, and C2PA — and download one ZIP.
- [Stable Diffusion PNG metadata](https://removeaimeta.com/stable-diffusion-png-metadata) — See and strip the Automatic1111 parameters chunk and the ComfyUI prompt and workflow text. Not a detector bypass.
- [Photo location finder](https://removeaimeta.com/photo-location-finder) — Read GPS, altitude, direction, capture time, and camera from JPEG, HEIC, PNG, WebP, or TIFF on your device.
- [Can you remove SynthID?](https://removeaimeta.com/can-you-remove-synthid) — No. SynthID is in the pixels. This page says the cleaner only removes metadata, and what a clean file still carries.

### Other free tools

- [ExifTool](https://exiftool.org/) — Phil Harvey's local reader and editor for EXIF, IPTC, XMP, and more. Nothing is uploaded, because it runs on your machine.
- [Content Credentials Verify](https://contentcredentials.org/verify) — The public check for a signed C2PA manifest. It verifies a file. It does not strip one.
- [Exiv2](https://exiv2.org/) — Open-source library and command-line tools for Exif, IPTC, and XMP, including many camera maker notes.
- [Jimpl](https://jimpl.com/) — Online EXIF viewer that can also strip location. The image is uploaded, unlike the browser-local cleaner above.

## Music and video identification

Name the track in a public Instagram Reel from the link, or match a short clip you already have. Extreme pitch shifts, mashups, and unreleased edits usually do not match.

- [Reel Song Finder](https://reelsongfinder.com/) — Paste a public Instagram Reel link. The match uses the audio, including when the sticker is blank or says original audio.
- [Find a song from a video file](https://reelsongfinder.com/find-song-from-video) — Upload an MP4, MOV, or screen recording and get a title and artist. The page lists size limits and the clips that fail.
- [Find a song inside a long video](https://reelsongfinder.com/find-song-in-video) — Cut a 15 to 30 second clip that starts on the music, then match that clip rather than the whole file.
- [ISRC lookup](https://reelsongfinder.com/isrc-lookup) — Search a title and artist for an ISRC, or paste an ISRC (CC-XXX-YY-NNNNN) to see the track.
- [Find the song on an Instagram Reel](https://reelsongfinder.com/guides/how-to-find-song-on-instagram-reel) — Paste the public Reel URL. A blank sticker can still return a title, because the audio is what gets matched.
- [Without the Instagram app](https://reelsongfinder.com/guides/find-song-from-reel-without-the-app) — If a browser or a message already shows a public Reel link, paste that. The app does not have to be installed.
- [Search by the lyrics you heard](https://reelsongfinder.com/guides/find-reel-song-by-lyrics) — How to search a few words from a Reel, and when to stop and paste the link instead.
- [Sped-up and remix Reels](https://reelsongfinder.com/guides/find-sped-up-remix-song-from-reel) — Mild speed changes often still match the original. Extreme pitch shifts, mashups, and unreleased edits usually do not.
- [On a PC, no app](https://reelsongfinder.com/guides/find-reel-song-on-pc) — Copy the Reel address from the browser bar and paste it. No desktop app.
- [When the sticker says original audio](https://reelsongfinder.com/guides/instagram-reel-original-audio) — Original audio means Instagram did not name the track. The link can still be matched from the file.

### Other free tools

- [Shazam](https://www.shazam.com/) — Names a song from the microphone or a short capture. A heavily sped-up or pitched Reel often returns nothing.
- [AudioTag](https://audiotag.info/) — Upload a clip in the browser and get a title. The audio leaves your machine; the recognizer is free.
- [AHA Music](https://aha-music.com/) — Browser song finder for audio you can play or upload. Unreleased edits and extreme remixes often miss.

## Minecraft building

Turn a sentence into a Java `.litematic` and a material list, or convert between `.litematic`, `.schem`, and structure NBT. Placing the hologram still needs the Litematica mod. One small build a day is free; more builds are a one-time payment, not a subscription.

- [Minecraft Schematic Generator](https://minecraftschematicgenerator.com) — Describe a Java build and download a `.litematic` plus a material list, or a `.schem` for WorldEdit.
- [One free schematic, no account](https://minecraftschematicgenerator.com/free-minecraft-schematic-generator) — One small Java `.litematic` per day, with a material list. No account.
- [Text to litematic](https://minecraftschematicgenerator.com/text-to-litematic) — Prompt to a `.litematic` for Litematica, with the survival material list attached.
- [Litematica schematic generator](https://minecraftschematicgenerator.com/litematica-schematic-generator) — Writes a Java version-6 `.litematic`. Litematica is a client-side Fabric mod; you load the file with M.
- [Schematic converter](https://minecraftschematicgenerator.com/schematic-converter) — Convert `.litematic`, `.schem`, and structure `.nbt` in the browser. No upload, no account, and this page has no size cap.
- [Litematic vs schem vs schematic](https://minecraftschematicgenerator.com/litematic-vs-schem) — `.litematic` is Litematica's hologram. `.schem` is Sponge v2 for WorldEdit and FAWE. `.schematic` is the old MCEdit file.
- [Load a litematic](https://minecraftschematicgenerator.com/how-to-load-litematic-in-litematica) — Put the file in the instance schematics folder, open a world, press M, then Load Schematics. Dropping it on the game does nothing.
- [How to use Litematica](https://minecraftschematicgenerator.com/how-to-use-litematica) — Fabric plus MaLiLib, then load, place, layer mode, easy place, and the material list.
- [Material list](https://minecraftschematicgenerator.com/litematica-material-list) — In game, select the placement and press M+L for Total, Missing, and Available. The page's CSV is the recipe before you start.
- [Move and rotate](https://minecraftschematicgenerator.com/litematica-move-and-rotate) — Select the placement, open Configure, and click Rotation (90 degrees each click). No numpad required. Mirror is on the same page.

### Other free tools

- [Amulet Editor](https://www.amuletmc.com/) — Open-source world editor and converter for Java since 1.12 and Bedrock since 1.7. It edits a world you already have; it does not build from a sentence.
- [Litematica on Modrinth](https://modrinth.com/mod/litematica) — The Fabric client mod that shows a `.litematic` as a hologram. It needs MaLiLib. It does not create the file.
- [WorldEdit](https://enginehub.org/worldedit) — In-game editor that pastes a `.schem` as real blocks. Use it when you want the build placed, not a ghost you finish by hand.

## Snapchat Memories export

Snapchat's My Data ZIP is the source. These pages write capture dates, GPS, and caption overlays back onto the files, in the browser. January 2027 archives overflow above the free 5 GB as thumbnails. It is not a deletion date. Nothing here logs into Snapchat or asks for your password.

- [Snapchat Memories Download](https://snapchatmemoriesdownload.com) — Drop the official My Data ZIP. Dates, GPS, and overlays are written back locally. Fifteen photos a day are free. This is not Snapchat's storage plan.
- [How to download Memories](https://snapchatmemoriesdownload.com/how-to-download-snapchat-memories) — The official path: Snapchat account, My Data, export Memories. The ZIP can then be repaired here.
- [Download with the real dates](https://snapchatmemoriesdownload.com/download-snapchat-memories-with-dates) — My Data stamps the export day on the file. The capture time, and GPS when Snap stored it, sit in memories_history.json until they are written back.
- [Wrong date after export](https://snapchatmemoriesdownload.com/snapchat-memories-wrong-date) — The real time is in memories_history.json and the filename prefix. Rewrite EXIF and QuickTime before you import into Photos.
- [January 2027 archive](https://snapchatmemoriesdownload.com/snapchat-memories-2027-archive) — Snap's help says Memories are not deleted if you skip a plan. Above the free 5 GB, older items outside that 5 GB become thumbnails.
- [What My Data is](https://snapchatmemoriesdownload.com/snapchat-my-data) — My Data is Snapchat's own export. Toggle Memories and JSON. This site repairs that archive. It does not replace the portal.
- [Put the GPS back](https://snapchatmemoriesdownload.com/snapchat-memories-gps) — Location stays in memories_history.json and is stripped from the media. The tool writes EXIF GPS so Photos can map them.
- [Main photo plus overlay](https://snapchatmemoriesdownload.com/snapchat-memories-overlay) — Exports ship a -main photo or video and a transparent -overlay PNG. Compositing keeps captions and stickers.
- [memories_history.json](https://snapchatmemoriesdownload.com/memories-history-json) — The JSON lists Date, Media Type, Location, and Download Link. Rows match to -main files. The filename alone is only the day.
- [Keep a copy before 2027](https://snapchatmemoriesdownload.com/save-snapchat-memories-before-2027) — Request My Data, restore dates, and keep a copy that opens without a storage plan. The change is an archive of overflow, not a wipe.

### Other free tools

- [Snapchat Download My Data](https://accounts.snapchat.com/v2/download-my-data) — Snapchat's signed-in export. This is the ZIP the repair tool expects. The files in it still carry the export day until something rewrites them.
- [How Snapchat says to download your data](https://help.snapchat.com/hc/en-us/articles/7012305371156-How-do-I-download-my-data-from-Snapchat) — Snapchat's own steps. Use this before you give a password to any third-party downloader.
- [ExifTool](https://exiftool.org/) — Writes DateTimeOriginal, QuickTime dates, and GPS once you already know the values. It does not parse memories_history.json for you.

## Subtitles and transcripts

Turn SRT, WebVTT, and a few meeting exports into an editable Word file or plain text. One file converts in the browser and is not uploaded. Word will print a bad clock; it will not shift it.

- [SRT to Word](https://srt2word.com) — Convert SRT to an editable .docx in the browser, with speaker lines and a timestamp toggle. One file stays free.
- [How to convert SRT to Word](https://srt2word.com/how-to-convert-srt-to-word) — Export SRT or VTT, paste, choose timestamps, and download a .docx that opens in Word, Word Online, or LibreOffice.
- [What the Word file actually contains](https://srt2word.com/srt-to-docx) — A before-and-after on four cues: how they merge, what the speaker line looks like, and what to fix first.
- [With or without timecode](https://srt2word.com/srt-to-word-with-timecode) — Show timestamps writes a start-end range into the document. Leaving it off makes a reading copy. The caption file keeps its clocks either way.
- [VTT to Word](https://srt2word.com/vtt-to-word) — Voice tags become speaker names. Player position and color settings are dropped.
- [SRT to plain text](https://srt2word.com/srt-to-txt) — Cue numbers and clocks come off. The cue text stays. Still local.
- [Zoom transcript to Word](https://srt2word.com/zoom-transcript-to-word) — Paste a Zoom cloud-recording transcript. Speaker labels and timestamps can go into the .docx.
- [YouTube captions to Word](https://srt2word.com/youtube-captions-to-word) — In YouTube Studio, download .srt or .vtt for a video you manage. Skip .sbv: it has no `-->` cue, so it will not become timed paragraphs.
- [A folder to one ZIP](https://srt2word.com/batch-srt-to-word) — One file is still a free .docx. A folder of up to 40 SRT, VTT, or ASS files becomes one ZIP of separate documents.
- [Fix a clock that is off](https://srt2word.com/fix-srt-timing) — Tell a one-hour offset apart from frame-rate drift, repair the subtitle file, then check a timestamped .docx.

### Other free tools

- [Subtitle Tools](https://subtitletools.com/) — Browser tools to convert, resync, and clean SRT, SSA, VTT, SUP, and SUB/IDX.
- [Subtitle Edit](https://www.nikse.dk/subtitleedit) — Free desktop editor for timing, translation, and format conversion when a single browser offset is not enough.

## ChatGPT export to Word

Paste one answer, or start from OpenAI's data-export archive, and get a .docx with headings, tables, code, and equations. A direct paste into Word keeps the Markdown characters. One answer converts free, on the device. A batch ZIP is a paid add-on.

- [ChatGPT to Word](https://chatgpt2word.com) — Paste one answer and download a .docx with headings, tables, code, Mermaid, and LaTeX. Conversion stays on the device.
- [How to export ChatGPT to Word](https://chatgpt2word.com/how-to-export-chatgpt-to-word) — Copy the Markdown, paste it, and download a .docx that opens in Word, Word Online, or LibreOffice.
- [A whole conversation](https://chatgpt2word.com/export-chatgpt-conversation-to-word) — What actually works for more than one turn: a share link, the data export, and building one editable document.
- [Tables become tables](https://chatgpt2word.com/chatgpt-table-to-word) — GitHub-flavored Markdown tables become real Word tables, with column alignment kept. A pipe paste does not.
- [Code blocks](https://chatgpt2word.com/chatgpt-code-to-word) — Fences stay monospace, with a language label and the indentation. There is no syntax-color theme, and it is not a screenshot.
- [OpenAI's data export is not Word](https://chatgpt2word.com/chatgpt-data-export-to-word) — The official export ZIP is HTML and JSON. This page says what to ignore and how to turn one conversation into a .docx.
- [Equations](https://chatgpt2word.com/latex-to-word) — Dollar-sign math, backslash-parentheses, and the spaced parenthesis form become an editable Word equation. The rest of the answer is included.
- [Why a direct paste breaks](https://chatgpt2word.com/paste-chatgpt-into-word) — Pasting into Word keeps hash marks, pipes, and fences. Preview first, then insert into an open document or save a new .docx.
- [Any Markdown, not only ChatGPT](https://chatgpt2word.com/markdown-to-word) — GitHub-flavored Markdown to .docx: tables, code, lists, links, Mermaid, and math. No upload.
- [Without a browser extension](https://chatgpt2word.com/chatgpt-to-word-without-extension) — Extensions, asking ChatGPT for a file, Pandoc, and a no-install page. Which path fits one answer, and which fits a thread.

### Other free tools

- [Pandoc](https://pandoc.org/) — Local Markdown-to-docx converter. A reference document sets fonts once. You hand it a file; it never sees your ChatGPT account.
- [CloudConvert Markdown to Word](https://cloudconvert.com/md-to-docx) — Browser conversion with no account and no watermark on the result. The file is uploaded to convert.

## Psychology and IQ score tools

An online estimate, plus calculators for scores a report already printed. The GAI calculator subtracts two official numbers. It does not re-score a WISC or WAIS. Nothing here is a diagnosis, and an internet IQ test is not an official FSIQ.

- [GAI vs IQ](https://gaivsiq.com) — About a 30-minute online estimate: an overall IQ and a cognitive profile, no sign-up. Not a WAIS, a WISC, or a diagnosis.
- [GAI minus FSIQ](https://gaivsiq.com/calculator) — Paste an official General Ability Index and Full Scale IQ. The gap is GAI minus FSIQ. It does not re-score the test.
- [GAI minus CPI](https://gaivsiq.com/cpi) — Paste Cognitive Proficiency Index and GAI. The gap is reasoning against memory and speed. This is not the FSIQ calculator.
- [Index scores, not a composite](https://gaivsiq.com/indexes) — Paste WISC-V or WAIS-5 indexes, or WAIS-IV VCI, PRI, WMI, and PSI. You see the peak and the drag. Their average is not an official GAI or CPI.
- [The nine-task test](https://gaivsiq.com/test) — Nine tasks, about 30 minutes, resume by task. An estimate and a profile, not a Wechsler administration.
- [Which subtests make GAI](https://gaivsiq.com/wais) — On WAIS-IV, GAI is VCI plus PRI. The page lists the WISC-V subtests and what changed on WAIS-5.
- [Why GAI is higher than FSIQ](https://gaivsiq.com/guides/why-gai-is-higher-than-iq) — Usually working memory or processing speed pulled Full Scale IQ down. A checklist before you treat the gap as the real score.
- [What is a good GAI score?](https://gaivsiq.com/guides/what-is-a-good-gai-score) — The usual mean-100, SD-15 bands: average, high average, 120, and 130, with percentiles. A band is not a diagnosis.
- [IQ score chart](https://gaivsiq.com/guides/iq-score-chart) — Percentile labels for 70, 85, 100, 115, 120, and 130 on a normal curve, and how not to misuse the chart.
- [How to read a cognitive profile](https://gaivsiq.com/guides/how-to-read-a-cognitive-profile) — Five domains, GAI, CPI, and what the free result shows versus a written reading. Not a diagnosis.

### Other free tools

- [OpenPsychometrics Full Scale IQ test](https://openpsychometrics.org/tests/FSIQ/) — A free multi-scale online IQ test. It is not a WAIS, and its number is not an official FSIQ to paste into the calculator above.
- [OpenPsychometrics vocabulary test](https://openpsychometrics.org/tests/VIQT/) — A short free vocabulary scale from the same project. One narrow score, not a Full Scale IQ.
- [CognitiveMetrics](https://cognitivemetrics.com/) — Online tests, including a US Army AGCT form and a WAIS-IV-inspired CAIT. Not a proctored Wechsler, and not the official pair the calculator subtracts.

## Astrology and birth charts

A western chart from birth date, time, and city, using whole-sign houses. Sun-sign horoscope pages do not use a birth time. Without a birth time, the rising sign is left blank rather than invented.

- [AstralHoro](https://astralhoro.com/) — A natal chart that needs your birth time, plus today's horoscope and tarot. The sun-sign pages do not use a birth time.
- [Birth chart](https://astralhoro.com/chart) — Date, time, and city. Whole-sign houses. The tight aspects are named.
- [How to read a birth chart](https://astralhoro.com/how-to-read-a-birth-chart) — Sun, Moon, and rising, then the tight aspects. No birth time means no rising, and the page does not invent one.
- [Rising sign](https://astralhoro.com/rising) — Ascendant from birth time and city. Without the time, there is no result.
- [Moon sign](https://astralhoro.com/moon) — The Moon's sign and house in the birth chart.
- [Sun-sign compatibility](https://astralhoro.com/compatibility) — Sun-sign pairs and how the pairing is described. Not a percentage, and not two full birth charts.
- [Who is retrograde now](https://astralhoro.com/retrograde) — Whether Mercury, Venus, Mars, and the slower planets are retrograde today. Mercury's dates have their own page.
- [Horoscope by sun sign](https://astralhoro.com/horoscope) — Today, tomorrow, this week, this month, and this year for twelve signs. Love follows Venus. Work follows Saturn.
- [Transits on your chart today](https://astralhoro.com/timing) — The tightest planet on your chart today, then the rest of the sky.
- [The sky today](https://astralhoro.com/sky) — Where the planets are, the Moon phase, and which of them are retrograde.

### Other free tools

- [Astrodienst extended chart](https://www.astro.com/cgi/chart.cgi) — The long-standing free natal chart. You pick houses and aspect settings. No birth time means no ascendant you can trust.
- [Cafe Astrology natal report](https://cafeastrology.com/free-natal-chart-report.html) — A free report of positions by sign and house, aspects, and house comparisons. Houses still need a birth time.

## AI photo and face editing

Try a haircut, a color, a beard, a headshot, a background, or clothes. One watermarked preview is free. A clean download spends a credit. Face blur is the exception: it runs in the browser, uploads nothing, and uses no credit.

- [EasyFace](https://easyfaceai.com/) — Hairstyle, hair color, clothes, or a headshot on a photo you upload. One watermarked preview is free.
- [Hairstyles](https://easyfaceai.com/hairstyles) — Buzz cut, bangs, long hair, perm, curls, and the rest. The clean file, without the watermark, is one credit.
- [Hair color](https://easyfaceai.com/hair-color) — Recolor the cut you already have. Length stays as uploaded. Watermarked preview free; clean file is one credit.
- [Facial hair](https://easyfaceai.com/facial-hair) — Beard, mustache, goatee, or no beard. The haircut stays.
- [Headshots](https://easyfaceai.com/ai-headshot-generator) — LinkedIn, corporate, studio, outdoor, creative, or medical framing. The face is meant to stay the same person.
- [Background changer](https://easyfaceai.com/ai-background-changer) — Replace the scene and keep the same person. A prompt is already filled in; you can edit it.
- [Object remover](https://easyfaceai.com/object-remover) — Remove other people and distracting objects. The main person is meant to stay.
- [Photo enhancer](https://easyfaceai.com/ai-photo-enhancer) — Clarify a blurry selfie or an old photo. This is not a style filter.
- [Face blur, on device](https://easyfaceai.com/photo-privacy/face-blur) — Blur a face in the browser. Nothing is uploaded and no credit is used.
- [Clothes changer](https://easyfaceai.com/ai-clothes-changer) — A preset, a photo of a garment, or a description. The person stays.

### Other free tools

- [Photopea](https://www.photopea.com/) — Full image editor in the tab: layers, masks, and retouching. Free to open. It is a manual editor, not a one-click hairstyle.
- [Squoosh](https://squoosh.app/) — Resize and recompress a photo locally in the browser, including WebP and AVIF. It does not edit a face.
- [remove.bg](https://www.remove.bg/) — Cuts a background out. The image is uploaded, and the free result is limited to their preview tier.
- [Cleanup.pictures](https://cleanup.pictures/) — Paint over an object, person, text, or defect and it fills the patch. Check the free limit on the page before a batch.

## Guides and write-ups

Articles about the same jobs, from dev.to, Hashnode, Medium, and Telegraph. The title is the URL slug in plain English. These are write-ups, not the tools. Telegraph posts in the source list were all about these jobs, so none were dropped.

### About this list

- [A job-based directory for in-browser tools](https://dev.to/dylan_yu_7ffff00b5355942d/a-job-based-directory-for-in-browser-tools-12k9)
- [A directory of browser tools grouped by the job, not the hype](https://dev.to/removeaimeta/a-directory-of-browser-tools-grouped-by-the-job-not-the-hype-46gi)

### Image privacy

- [Checking and cleaning AI image metadata: a guide index](https://telegra.ph/Checking-and-cleaning-AI-image-metadata-a-guide-index-10-02)
- [What's actually inside your image and PDF before you upload it](https://dev.to/dylan_yu_7ffff00b5355942d/whats-actually-inside-your-image-and-pdf-before-you-upload-it-3j8l)
- [The hidden data in your photos: what AI metadata reveals and how to strip it](https://dev.to/removeaimeta/the-hidden-data-in-your-photos-what-ai-metadata-reveals-and-how-to-strip-it-2mf6)
- [Cleaning AI metadata from images and files: a practical guide for developers](https://dev.to/removeaimeta/cleaning-ai-metadata-from-images-and-files-a-practical-guide-for-developers-37bi)
- [Clean a JPEG in the tab you already have open](https://dev.to/removeaimeta/clean-a-jpeg-in-the-tab-you-already-have-open-3en)
- [How I strip C2PA and EXIF from a photo before I post, browser only](https://medium.com/@hello_70944/how-i-strip-c2pa-and-exif-from-a-photo-before-i-post-browser-only-e8a82a5d88bb)
- [Strip C2PA and IPTC metadata from AI images before you publish](https://dev.to/removeaimeta/strip-c2pa-and-iptc-metadata-from-ai-images-before-you-publish-79d)
- [Inspecting and removing C2PA and IPTC metadata from images](https://removeaimeta.hashnode.dev/inspecting-and-removing-c2pa-and-iptc-metadata-from-images)
- [Should you strip AI metadata from an image before you share it? A decision guide](https://medium.com/@hello_70944/should-you-strip-ai-metadata-from-an-image-before-you-share-it-a-decision-guide-10ec85f2346c)
- [Which of your AI-made images carry a hidden AI info record: a 3-step check](https://medium.com/@hello_70944/which-of-your-ai-made-images-carry-a-hidden-ai-info-record-a-3-step-check-fc83379fcbd2)
- [A C2PA line describes the file you drop, not the picture people see](https://medium.com/@hello_70944/a-c2pa-line-describes-the-file-you-drop-not-the-picture-people-see-6482c124e9ea)
- [Does a screenshot remove C2PA data from a ChatGPT image?](https://removeaimeta.hashnode.dev/does-a-screenshot-remove-c2pa-data-from-a-chatgpt-image)
- [How to check an image for Content Credentials with c2patool: two commands](https://telegra.ph/How-to-check-an-image-for-Content-Credentials-with-c2patool-two-commands-10-02)
- [How to check whether a JPEG or PNG carries C2PA data, with a short script](https://telegra.ph/How-to-check-whether-a-JPEG-or-PNG-carries-C2PA-data-with-a-short-script-10-02)
- [The LinkedIn CR icon is a manifest, not a sticker](https://dev.to/removeaimeta/the-linkedin-cr-icon-is-a-manifest-not-a-sticker-31he)
- [What is the CR icon on LinkedIn images, and why is it on my photo?](https://telegra.ph/What-is-the-CR-icon-on-LinkedIn-images-and-why-is-it-on-my-photo-10-02)
- [A two-minute check before you post an image on LinkedIn: will it show the CR icon?](https://telegra.ph/A-two-minute-check-before-you-post-an-image-on-LinkedIn-will-it-show-the-CR-icon-10-04)
- [Field note: the LinkedIn CR icon is on the file you already sent](https://telegra.ph/Field-note-the-LinkedIn-CR-icon-is-on-the-file-you-already-sent-10-12)
- [Five fields in LinkedIn's CR panel, and the AI-only pass for the next upload](https://telegra.ph/Five-fields-in-LinkedIns-CR-panel-and-the-AI-only-pass-for-the-next-upload-10-08)
- [What triggers Instagram's AI info label? What Meta says, and what you control](https://telegra.ph/What-triggers-Instagrams-AI-info-label-What-Meta-says-and-what-you-control-10-02)
- [Clean the file before Instagram reads it](https://telegra.ph/Clean-the-file-before-Instagram-reads-it-10-12)
- [Photoshop Generative Fill adds Content Credentials to your export. Here is how to see it](https://telegra.ph/Photoshop-Generative-Fill-adds-Content-Credentials-to-your-export-Heres-how-to-see-it-10-02)
- [What metadata is inside a Midjourney download? Check before you publish](https://telegra.ph/What-metadata-is-inside-a-Midjourney-download-Check-before-you-publish-10-02)
- [Gemini and Imagen images: what's in the downloaded file, and what isn't](https://telegra.ph/Gemini-and-Imagen-images-whats-in-the-downloaded-file-and-what-isnt-10-02)
- [Stable Diffusion and ComfyUI PNGs carry your prompt: how to see what's inside](https://removeaimeta.hashnode.dev/stable-diffusion-and-comfyui-pngs-carry-your-prompt-how-to-see-what-s-inside)
- [SynthID and Content Credentials are two different marks](https://telegra.ph/SynthID-and-Content-Credentials-are-two-different-marks-10-02)
- [SynthID is not a row in the inspect report: what a metadata clean leaves behind](https://telegra.ph/SynthID-is-not-a-row-in-the-inspect-report-what-a-metadata-clean-leaves-behind-10-08)
- [Before you deliver photos to a client, check for GPS, camera serials, and AI edit history](https://telegra.ph/Before-you-deliver-photos-to-a-client-check-for-GPS-camera-serials-and-AI-edit-history-10-02)
- [An Etsy seller's Friday: clearing AI tags and GPS before listing photos](https://telegra.ph/An-Etsy-sellers-Friday-clearing-AI-tags-and-GPS-before-listing-photos-10-06)
- [Troubleshooting Remove AI Meta: real error messages and what to do](https://dev.to/dylan_yu_7ffff00b5355942d/troubleshooting-remove-ai-meta-real-error-messages-and-what-to-do-1c10)
- [Troubleshooting Remove AI Meta: real error messages, and what to do](https://telegra.ph/Troubleshooting-Remove-AI-Meta-real-error-messages-and-what-to-do-10-06)

### Music and video

- [Finding the track used in an Instagram Reel](https://dev.to/dylan_yu_7ffff00b5355942d/finding-the-track-used-in-an-instagram-reel-e0i)
- [Find the song used in an Instagram Reel without guessing](https://dev.to/removeaimeta/find-the-song-used-in-an-instagram-reel-without-guessing-5gbn)
- [The clipboard test for an Instagram Reel link](https://dev.to/removeaimeta/the-clipboard-test-for-an-instagram-reel-link-14n)
- [Finding a Reels song from a laptop, with no phone and no app](https://telegra.ph/Finding-a-Reels-song-from-a-laptop-with-no-phone-and-no-app-10-02)
- [Which Instagram link do you copy to identify a song: reel, share, /p/, and the rest](https://telegra.ph/Which-Instagram-link-do-you-copy-to-identify-a-song-reel-share-p-and-the-rest-10-02)
- [Instagram says original audio: what the label tells you, and what it does not](https://telegra.ph/Instagram-says-Original-audio-what-the-label-tells-you-and-what-it-does-not-10-02)
- [Only remember a few lyrics from a Reel? A better way to search them](https://telegra.ph/Only-remember-a-few-lyrics-from-a-Reel-A-better-way-to-search-them-10-02)
- [Why Shazam hears nothing in a sped-up Reel song, and what still works](https://telegra.ph/Why-Shazam-hears-nothing-in-a-sped-up-Reel-song-and-what-still-works-10-02)

### Minecraft

- [Generate Minecraft schematics in the browser before you build](https://dev.to/removeaimeta/generate-minecraft-schematics-in-the-browser-before-you-build-gm7)
- [Generate a Minecraft Java Edition litematic from a text prompt](https://dev.to/removeaimeta/generate-a-minecraft-java-edition-litematic-from-a-text-prompt-5cb2)
- [Do you need to download a schematic, or can you generate one? A short decision guide](https://telegra.ph/Do-you-need-to-download-a-schematic-or-can-you-generate-one-A-short-decision-guide-10-02)
- [Paste or build: two ways to use a litematic, and when each one fits](https://telegra.ph/Paste-or-build-Two-ways-to-use-a-litematic-and-when-each-one-fits-10-02)
- [Quarter turns for a Litematica placement](https://dev.to/removeaimeta/quarter-turns-for-a-litematica-placement-49da)
- [Numpad minus, then Rotation: five clicks that turn a Litematica hologram](https://telegra.ph/Numpad-Minus-then-Rotation-five-clicks-that-turn-a-Litematica-hologram-10-12)
- [Alt+scroll moved the blue box, not the house](https://telegra.ph/Alt-plus-scroll-moved-the-blue-box-not-the-house-10-12)
- [The Load Schematics list is empty: three places the file actually went](https://telegra.ph/The-Load-Schematics-list-is-empty-three-places-the-file-actually-went-10-12)
- [Litematica shows only a small cyan box after loading. Check Manual Origin](https://telegra.ph/Litematica-shows-only-a-small-cyan-box-after-loading-Check-the-Manual-Origin-option-10-02)
- [Litematica ghost blocks too solid or too faint: the settings that control it](https://telegra.ph/Litematica-ghost-blocks-too-solid-or-too-faint-The-settings-that-control-it-10-02)
- [Change the wood type of a litematic without rebuilding it](https://telegra.ph/Change-the-wood-type-of-a-litematic-without-rebuilding-it-10-02)
- [Server-builder notes: shipping an oak farmhouse hologram to the SMP](https://telegra.ph/Server-builder-notes-shipping-an-oak-farmhouse-hologram-to-the-SMP-10-05)

### Snapchat Memories

- [Snapchat Memories export: a guide index](https://telegra.ph/Snapchat-Memories-export-guides-index-10-02)
- [How to download Snapchat Memories without losing photo quality](https://dev.to/removeaimeta/how-to-download-snapchat-memories-without-losing-photo-quality-38j)
- [Snapchat data export: how long it takes, and what to do the day it arrives](https://telegra.ph/Snapchat-data-export-how-long-it-takes-and-what-to-do-the-day-it-arrives-10-02)
- [Do not submit My Data a second time; use See exports](https://telegra.ph/Do-not-Submit-My-Data-a-second-time-use-See-exports-10-12)
- [Your Snap was exported is the camera-roll button, not My Data](https://telegra.ph/Your-Snap-was-exported-is-the-camera-roll-button-not-My-Data-10-12)
- [Save Snapchat Memories to the camera roll, or request a full export? What each one gives you](https://telegra.ph/Save-Snapchat-Memories-to-the-camera-roll-or-request-a-full-export-What-each-one-gives-you-10-02)
- [Does a Snapchat Memories export include My Eyes Only?](https://telegra.ph/Does-a-Snapchat-Memories-export-include-My-Eyes-Only-10-02)
- [How to save all your Snapchat Memories in bulk with the right dates](https://telegra.ph/How-to-save-all-your-Snapchat-Memories-in-bulk-with-the-right-dates-10-04)
- [Why exported Snapchat Memories lose their dates, and how to fix the EXIF](https://dev.to/dylan_yu_7ffff00b5355942d/why-exported-snapchat-memories-lose-their-dates-and-how-to-fix-the-exif-ac4)
- [Snapchat Memories all show today's date in Google Photos: why, and how to fix it](https://telegra.ph/Snapchat-Memories-all-show-todays-date-in-Google-Photos-why-and-how-to-fix-it-10-02)
- [Snapchat Memories show up as today in Apple Photos: how the date is chosen, and how to fix it](https://telegra.ph/Snapchat-Memories-show-up-as-today-in-Apple-Photos-how-the-date-is-chosen-and-how-to-fix-it-10-02)
- [Four date sources a Memories scan can report, and which one becomes DateTimeOriginal](https://telegra.ph/Four-date-sources-a-Memories-scan-can-report-and-which-one-becomes-DateTimeOriginal-10-08)
- [restore-report.csv: which date source Photos will ignore](https://telegra.ph/restore-reportcsv-which-date-source-Photos-will-ignore-10-12)
- [What is memories_history.json in a Snapchat export? A 20-line script to read it](https://telegra.ph/What-is-memories-historyjson-in-a-Snapchat-export-A-20-line-script-to-read-it-10-02)
- [Why your exported Snapchat Memories show no location, and how to put the map back](https://medium.com/@hello_3876/why-your-exported-snapchat-memories-show-no-location-and-how-to-put-the-map-back-a0840434f961)
- [Snapchat Memories export has no location: where the GPS went, and how to put it back](https://telegra.ph/Snapchat-Memories-export-has-no-location-where-the-GPS-went-and-how-to-put-it-back-10-02)
- [Snapchat export: every photo comes as a main JPG plus an overlay PNG. How to put captions back](https://snapchatmemories.hashnode.dev/snapchat-export-every-photo-comes-as-main-jpg-plus-overlay-png-how-to-put-captions-back)
- [Snapchat video Memories: how to put the captions back with ffmpeg](https://telegra.ph/Snapchat-video-Memories-how-to-put-the-captions-back-with-ffmpeg-10-02)
- [January 2027 archives Snapchat Memories; it does not delete them](https://dev.to/dylan_yu_7ffff00b5355942d/january-2027-archives-snapchat-memories-it-does-not-delete-them-53g1)
- [January 2027 archives Memories as thumbnails; it is not a deletion date](https://medium.com/@hello_3876/january-2027-archives-memories-as-thumbnails-it-is-not-a-deletion-date-48f022c0af73)
- [Three My Data clicks, then what: the January 2027 Memories archive changes](https://telegra.ph/Three-My-Data-clicks-then-what-the-January-2027-Memories-archive-changes-10-08)
- [Snapchat Memories before January 2027: a 15-minute checklist](https://telegra.ph/Snapchat-Memories-before-January-2027-a-15-minute-checklist-10-02)
- [How to check your Snapchat Memories storage, and what the 5 GB limit means in January 2027](https://telegra.ph/How-to-check-your-Snapchat-Memories-storage-and-what-the-5GB-limit-means-in-January-2027-10-02)
- [Freeing phone storage after a Snapchat export: a safe order of operations](https://medium.com/@hello_3876/freeing-phone-storage-after-a-snapchat-export-a-safe-order-of-operations-953d804f8be8)

### Subtitles

- [Turn SRT subtitles into an editable Word document](https://dev.to/removeaimeta/turn-srt-subtitles-into-an-editable-word-document-34l)
- [A WebVTT file is not a Word script until the cues collapse](https://dev.to/removeaimeta/a-webvtt-file-is-not-a-word-script-until-the-cues-collapse-4omf)
- [Why subtitle files break your docs pipeline, and how I handle it](https://dev.to/removeaimeta/why-subtitle-files-break-your-docs-pipeline-and-how-i-handle-it-27a4)
- [SRT, VTT, or ASS: which caption file to download before you make a Word transcript](https://telegra.ph/SRT-VTT-or-ASS-which-caption-file-to-download-before-you-make-a-Word-transcript-10-02)
- [SRT to Word with timestamps and without, and why you should not delete the arrows](https://telegra.ph/SRT-to-Word-with-timestamps-without-and-why-you-should-not-delete-the-arrows-10-02)
- [Turn an SRT subtitle file into a Word transcript with a 40-line Python script](https://telegra.ph/Turn-an-SRT-subtitle-file-into-a-Word-transcript-with-a-40-line-Python-script-10-02)
- [Strip an SRT file down to plain text with shell one-liners, and what each one gets wrong](https://medium.com/@hello_5475/strip-an-srt-file-down-to-plain-text-with-shell-one-liners-and-what-each-one-gets-wrong-fe06372666d9)
- [Shifting an SRT file by a fixed offset: a short Python function, and the one case that needs care](https://medium.com/@hello_5475/shifting-an-srt-file-by-a-fixed-offset-a-short-python-function-and-the-one-case-that-needs-care-ba323319dbdd)
- [Merging consecutive subtitle cues from one speaker: a small Python function, and the gap rule it depends on](https://telegra.ph/Merging-consecutive-subtitle-cues-from-one-speaker-a-small-Python-function-and-the-gap-rule-it-depends-on-10-02)
- [Cleaning up a Zoom or YouTube transcript before it goes into a Word document](https://medium.com/@hello_5475/cleaning-up-a-zoom-or-youtube-transcript-before-it-goes-into-a-word-document-d24e7e7c006a)
- [Zoom transcript to a Word document, without re-transcribing the meeting](https://telegra.ph/Zoom-transcript-to-a-Word-document-without-re-transcribing-the-meeting-10-02)
- [Reviewing captions with a client in Word: a workflow that avoids sending them an SRT](https://medium.com/@hello_5475/reviewing-captions-with-a-client-in-word-a-workflow-that-avoids-sending-them-an-srt-2b48bf53337b)

### ChatGPT to Word

- [Export a ChatGPT thread to Word without broken formatting](https://dev.to/dylan_yu_7ffff00b5355942d/export-a-chatgpt-thread-to-word-without-broken-formatting-pf2)
- [Export a ChatGPT thread to Word without losing the structure](https://dev.to/removeaimeta/export-a-chatgpt-thread-to-word-without-losing-the-structure-5d50)
- [Do you need a Chrome extension to get a ChatGPT answer into Word? Usually not](https://telegra.ph/Do-you-need-a-Chrome-extension-to-get-a-ChatGPT-answer-into-Word-Usually-not-10-02)
- [Paste one ChatGPT answer and check the table before you download](https://dev.to/removeaimeta/paste-one-chatgpt-answer-and-check-the-table-before-you-download-2g29)
- [A ChatGPT table pasted into Word is just pipes. Here is why, and how to fix it](https://telegra.ph/ChatGPT-table-pasted-into-Word-is-just-pipes-Here-is-why-and-how-to-fix-it-10-02)
- [The ChatGPT table that never turns into a table: the missing separator row](https://telegra.ph/The-ChatGPT-table-that-never-turns-into-a-table-the-missing-separator-row-10-02)
- [Why a pasted ChatGPT answer shows ## and | in Word, and three ways to fix it](https://telegra.ph/Why-a-pasted-ChatGPT-answer-shows--and--in-Word-and-three-ways-to-fix-it-10-02)
- [Why a ChatGPT bullet list turns into one paragraph in Word, and the blank line that fixes it](https://medium.com/@hello_41390/why-a-chatgpt-bullet-list-turns-into-one-paragraph-in-word-and-the-blank-line-that-fixes-it-76839a3e0fc9)
- [Code blocks from ChatGPT in Word: why the formatting falls apart, and how to keep it](https://medium.com/@hello_41390/code-blocks-from-chatgpt-in-word-why-the-formatting-falls-apart-and-how-to-keep-it-af4c8e46fba2)
- [Getting ChatGPT math into Word as real equations: why $ and \( behave differently](https://medium.com/@hello_41390/getting-chatgpt-math-into-word-as-real-equations-why-and-behave-differently-75b30ea3450f)
- [Turn one conversation from ChatGPT's data export into a Word document](https://medium.com/@hello_41390/turn-one-conversation-from-chatgpts-data-export-into-a-word-document-39ee19309f29)
- [Set the fonts of a ChatGPT-to-Word conversion once, with a Pandoc reference document](https://telegra.ph/Set-the-fonts-of-a-ChatGPT-to-Word-conversion-once-with-a-Pandoc-reference-document-10-02)

### Psychology and IQ

- [I built a GAI vs IQ calculator that only subtracts two official scores: how to read a GAI vs FSIQ gap](https://medium.com/@gaivsiq/i-built-a-gai-vs-iq-calculator-that-only-subtracts-two-official-scoreshow-to-read-a-gai-vs-fsiq-gap-787c016c44de)

### Astrology

- [Compute a natal chart in the browser with Astronomy Engine](https://dev.to/dylan_yu_7ffff00b5355942d/compute-a-natal-chart-in-the-browser-with-astronomy-engine-4b67)
- [What your birth chart actually measures: the astronomy behind a natal chart](https://medium.com/@hello_3876/what-your-birth-chart-actually-measures-the-astronomy-behind-a-natal-chart-eef4444e1dd2)

## Contributing

Open a pull request with one link per tool. Say which job it does, whether the file stays on the device, what is free, and what it refuses to do. Prefer a tool page or a specific guide over a homepage. No affiliate links, no paid-only products in the free-tool lists, and no entry whose description could fit any other tool on the page.

A correction to a limit already listed is welcome. Prices and free quotas change. If a page no longer does what its line says, that line should change.

## License

[CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/) — public domain. Copy, change, and share this list, including commercially, without asking. The tools and articles linked here keep their own terms. See [LICENSE](LICENSE).
