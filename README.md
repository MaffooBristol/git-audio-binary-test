git-audio-binary-test
=====================

* Initial commit, 2MB file = 1.7mb .git folder
* Changing amplitude from 0db to -6db was supposedly a 76% rewrite. File is same size. .git folder now 2.5MB
* Doubled length of output, still the full sine tone. Doesn't mention rewrite. File now 4MB, .git folder now 4.9MB
* Halved length again. File is back to 2MB. Git folder now 6.1MB
* At this point, I run git gc, which lowers the folder size down to 3.6MB
* Added 8 seconds of silence to the end of the file. File has doubled in size. Git folder is now 4.8MB
* Did a simple `cp audio.wav audio-copy.wav` and committed it- strangely enough, the .git folder is now only 4.9MB, so it recognises duplication.
