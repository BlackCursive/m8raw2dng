![LEICA - M8](https://img.shields.io/badge/LEICA-M8-ed1c24?style=for-the-badge&logo=photobucket&logoColor=FFFFFF)
## [m8raw2dng](https://web.archive.org/web/20191202004916/http://m8raw2dng.de/)
Arvid from the website m8raw2dng created a program to convert Leica M8 RAW files (16-bit container with 14-bit of data) to DNG format (8-bit).
This conversion helps particular in low light.  Typically one would not shoot the M8 past 640 but with the conversion files with 2500 are very 
much useable.  Please see included RAW file as an example ( Run the script to get the DNG output ).

## Leica M8 Service Mode - Button Dance

Complete the following steps:
- Push the Right Arrow button 4 times
- Push the Left Arrow button 3 times
- Push the Right Arrow button 1 time
- Push the Set button
- Scroll down to Compression
- Push the Set button
- Scroll down to Jpeg+Raw
- Push the Set button

Please note that once your camera turns off or hibernates the previous setting will change back to, "Fine Jpeg" and you will have to enter the Leica service mode again to alter the settings.

##
* I edited the Apple Script Droplet to do the conversion in the current working directory so the folder is portable.  
* Previously you would have to edit the script and have one designated location and reading through numerous forums,
many people had issues with this task.
