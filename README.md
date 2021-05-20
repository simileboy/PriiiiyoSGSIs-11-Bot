# PriiiiyoSGSIs-11-Bot
### Warning: Do not run packages directly in this warehouse ! 
## Instructions:

1. Fork this warehouse
2. Edit sgsi.json:
     rom_url: Put your firmware URL for download.
     rom_name: The name of he rom you already downloaded.
     pack_sgsi: The name of the Rom you need to pack.
     build_type: The type of system need to build (AB|A)
     rom_type: The type of rom you want to run
     light_fix: Whether to fix the brightness
     bug_fix: Whether to fix bugs (only support MIUI, Flyme, H2OS, Color, please enter lowercase)
     use_7zip: Use 7z to compress SGSI
     use_zip: Use zip to compress SGSI
3. After modification, click Start commit -> Actions tab -> Star -> build_SGSI-11

 
## Output result
If you upload rom to Release for download, please modify upload_release of sgsi.json:'false' ->'true'
After each successful build, the mountain will remove the automatically uploaded version, otherwise the upload will fail next time.
Download the results in [Release](../../releases)

If you upload rom to WeTransfer for download, please modify upload_wetransfer in sgsi.json:'false' ->'true'
After uploading the download link, pay attention to the output result Download Link‌‌.

If you upload rom to SourceForge for download, please modify upload_sourceforge in sgsi.json:'false' ->'true'
After uploading the download link, pay attention to the output result Download Link‌‌.
