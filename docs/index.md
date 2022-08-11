This is my TestWiki/docs/index.md file.

These do not work
* Link to [topic1](https://github.com/bfasching/TestWiki/blob/main/docs/subdir/topic1.html)
* Link 2 to [topic1](https://bfasching.github.io/TestWiki/docs/topic1.html)
* Link 3 to [topic1](/docs/subdir/topic1.html)
* Link 4 to [topic1](/subdir/topic1.html)

This one does and uses a relative path, renaming an "md" file as "html".
* Link 5 to [topic1](subdir/topic1.html) 

---

This one uses a permalink.

* Link to [topic2](sub/topic2.html)

----

Link to tracking document in Documents folder

* Link to [tracking](../Documentation/tracking/Tracking.html)
* Link 2 to [tracking](/Documentation/tracking/Tracking.html)
* Link 3 to [tracking](Documentation/tracking/Tracking.html)
