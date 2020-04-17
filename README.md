# qs_skt_tools
Quick and dirty tools
---

*Installation instructions:*

*Common dependencies*

- Execute the common/install_fedora to setup dependencies (on Fedora). Setup scripts for other OSes need to be worked on.

*OCR Tool*

- cd tess_ocr_gui; ./qs_ocrfile

- Use the video (tess_ocr_gui/OCRADocTutorial.mp4) for a quick-and-dirty tutorial

- Known issues: Code is badly written; but does the job. tesseract is currently spawned for every page (and on a single thread) so it's slow. TODO: Use multithreading and use the native API to speed things up.

All code released under GPL. Please contribute, re-share, and make your contributions available for everyone.

