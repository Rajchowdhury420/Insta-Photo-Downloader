### InstaGram Photo Downloader Tool using Go !
Install
--------------

    go get -u -x github.com/Rajchowdhury420/Insta-Photo-Downloader

Note, you need go to [Instagram developer page](https://instagram.com/developer/clients/manage/) to get latest token and update in environment variables

     export InstagramID="YOUR_ClientID_HERE"

Usage
---------------------

    Insta-Photo-Downloader [options] 

All the photos will download to `USERS/Pictures/goInstagram`.

Options
---------------

- `-n` Instagram page name such as: [Yanzee Sherpa](https://www.instagram.com/y.a.n.z.e.e/) 
- `-c` number of workers. (concurrency), default workers is "2"


Examples
---------------

Download all photos from LeBron James Instagram Photos with 10 workers.

  Insta-Photo-Downloader -n=y.a.n.z.e.e -c=10



