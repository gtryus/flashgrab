To 'build' this addon, make a zip file containing this folder and file:
syncxml/
syncx.py

Then, upload the zip file to this addon's page: 
https://ankiweb.net/shared/info/915685712

Optionally, first make sure that the files here are up to date:
  syncxml/samples

That is, if you've edited the FLEx project, do this:
- Re-export that (with media) to LIFT
- If necessary, delete the Anki project, and record types DICT_LIFT/DICT_LIFT_EX, and reload this fresh:
syncxml/samples/lift-dictionary.apkg
- Sync the LIFT/media into that fresh Anki deck, then re-create an updated .apkg file.
  At this point you should probably also re-share the .apkg file on its own, here:
  https://ankiweb.net/shared/decks/

