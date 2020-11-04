# LSMV (Less Shitty Media Viewer)
## What is it?
A media viewer that can handle both images and videos in the same UI.
Our main difference to other media viewers/players is a focus on simple design, exhuastive filtering, and the strive to support every visual media file possible.
LSMV is cross-platform (We could really use a Mac tester)

LSMV is strictly a viewer and should not *Ever* involve editing/writing files.
  - The only exception to this would be to export the media to dffierent types (JPG to PNG, MP4 to MKV, etc.)

 
 
## Requirements
 - We need to have a place to view the different video and photo files
 - find and pull in media files(videos and photos) from multiple folders and putting them into one list
 - button or menu to easily access remote files
 
 
 - toggle button to show only photos/only videos/all?
    - Wouldnt this just fit in the filter? Make an extra option on a filetype filter?
 - Support hardware acceleration
   - Support all the file types & codecs (HEIC/HEIF, VAAPI, etc.)
 - In depth sorting and *filtering* of media
    - File types
    - Videos
    - Photos
    - Length
    - Size
    - Created date
    - Modified date
    - Resolution
 
 - A preview box
 
 - Sane crash handling
    - Notify the user quitely ( Make it easy to suppress errors
 
 - Basic standard controls
    - When you select to view something it will fill the Window
    - There will be arrows on either side to cycle through
    - be able to toggle controls on and off at will and automatically
