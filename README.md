Danbooru Downloader: save images locally
===

Now [sanakakucomplex.com API][1] don't return original image url. This script help store images from [sankakucomplex](http://chan.sankakucomplex.com) to your hard drive.
Usage examples:

    danbooru_downloader -q vocaloid+order:popular -p ~/Desktop -c 60

store to your *Desktop* folder *60* most popular images with *"vocaloid"* tag

    danbooru_downloader -d http://konachan.com/ -c -1

download to *imgs* folder all images from *konachan.com*


[1]:http://chan.sankakucomplex.com/help/api