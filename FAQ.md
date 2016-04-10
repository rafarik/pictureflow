**PictureFlow does not run on my device! Please help!**

You provide too little information. Please check [How To Ask Questions The Smart Way](http://www.catb.org/~esr/faqs/smart-questions.html).

**I have problems building PictureFlow. Can you help me?**

Please post your question to the [mailing-list](http://groups.google.com/group/pictureflow).

**Can I use PictureFlow with Python?**

The current stable version (0.1) does not offer Python support yet, expect this in the next version (0.2). Alternatively, you can use [PyQt](http://wiki.python.org/moin/PyQt) and [SIP](http://www.riverbankcomputing.com/software/sip/intro) and generate the bindings by yourself. Please refer to PyQt and SIP documentations for details.

**Why does PictureFlow consume a lot of memory?**

Because you do not implement on-demand or lazy loading. See [PhotoFlow](http://code.google.com/p/photoflow/) on how to do that.

**Why can't PictureFlow find my pictures?**

Pass the path/directory to the executable. Otherwise, PictureFlow will try to search the files in the current directory.

**Why does not PictureFlow support transparent images?**

In its current version, certain rendering optimizations unfortunately means that alpha-blending is not supported. In the future version, it might be supported.

**Where to place the pictures so that PictureFlow can find it? Is it /Program Files/pictureflow or /My Documents/pictureflow?**

See the previous question. It does really depend on your platform/system and how you compile PictureFlow. You have to figure it out by yourself.

**How can I install PictureFlow on Windows? You don't provide any installer!**

You have to build it by yourself. Note that the intended audience of PictureFlow is _developers_, not _end-users_. It is just a normal Qt widget that needs to be used in a real application.

**Does PictureFlow run on Windows Mobile 5/6?**

Yes. See [the proof video](http://labs.trolltech.com/blogs/2007/11/02/pictureflow-on-windows-mobile/). Note that you need to compile and test the program by yourself to try it out.

**When is the next version released?**

It is released only when it is ready. In other words: there is no specific date, just watch its project page from time to time.