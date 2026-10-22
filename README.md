SaiLang 0.9.9 for Linux
=======================

This is the original 0.9.9 release, with the SaiLang-IDLE.pyw launcher.

Option A: the program (no Python needed)
  chmod +x sai
  ./sai examples/hello.sai        run a program
  ./sai idle                      open SaiLang IDLE
  ./sai check file.sai            look for mistakes

Option B: the .pyw launcher (needs Python 3.9+ with tkinter)
  python3 SaiLang-IDLE.pyw
  python3 SaiLang-IDLE.pyw examples/hello.sai

The src/ folder holds the language source that the .pyw launcher uses.
Note: this release's built-in version text reads "1.0.0".
Licence: MIT (see LICENSE).
