# Rapidleech

### What is Rapidleech?

Rapid Leech is a free server transfer script for use on various popular upload/download sites such as megaupload.com, Rapidshare.com and more than 45 others. The famous Rapidleech script transfers files from Rapidshare, Megaupload, Depositfiles.com, Easy-share.com, etc, via your fast servers connection speed and dumps the file on your server. You may then download these files from your server anytime later.
How do 

### I use Rapidleech?

To use Rapidleech, you will need a web hosting which supports PHP. There are also minimum requirement for the configuration of PHP, this includes safe_mode turned off, fsockopen is allowed and upload_max_filesize above 100M. You can also run Rapidleech on your local Windows computer, by install XAMPP.

### What are Rapidleech's requirements?

**PHP Requirement**

    safe_mode off
    Well, safe_mode can be turned on but you will need some knowledge of PHP to customize and make some workarounds.
    fsockopen enabled
    Check this through phpinfo(), if fsockopen is listed under disable_functions Rapidleech cannot work.
    allow_call_time_pass_reference On
    This isn't strictly required, but it will produce annoying messages across the pages.
    allow_url_fopen On
    memory_limit larger than 32MB
    Or you won't be able to download some large files
    cURL support enabled
    This is required to check links
    output_buffering Off
    This is required to show the progress bar during download, although there are workarounds even if this is turned on.

### What's with all the different Rapidleech versions?

Well, there is eqbal's plugmod, TheOnly's Mod and some other user contributed mods. But the main version is eqbal's plugmod. TheOnly's Mod extends the capability of Rapidleech suitable for public environment. If you're looking to host a public Rapidleech, you might be looking for this version. Besides, there is also a nightly build which contains latest fix and features in the trunk. It is quite unstable and meant for developers only. 
