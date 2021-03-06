isolate
=======

Isolate is a sandbox built to safely run untrusted executables,
offering them a limited-access environment and preventing them from
affecting the host system. It takes advantage of features specific to
the Linux kernel, like namespaces and control groups.

Isolate was developed by Martin Mareš (<mj@ucw.cz>) and Bernard Blackham
(<bernard@blackham.com.au>), who still maintain it. Several other people
contributed patches for features and bug fixes (see Git history for a list).
Thanks!

Originally, Isolate was a part of the [Moe Contest Environment](http://www.ucw.cz/moe/),
but it evolved to a separate project used by different
contest systems, most prominently [CMS](https://github.com/cms-dev/cms).
It now lives at [GitHub](https://github.com/ioi/isolate),
where you can submit bug reports and feature requests.

If you are interested in more details, please read Martin's
and Bernard's [paper](http://mj.ucw.cz/papers/isolate.pdf) presented
at the IOI Conference. Also, Isolate's [manual page](http://www.ucw.cz/moe/isolate.1.html)
is available online.

To compile Isolate, you need docker to run the docker file.

Most of the code was **not** written by me (Ryan-Kan). I've added some files to complile it using Docker, but most was written by the people mentioned above. You can find the original source code at [https://github.com/ioi/isolate](https://github.com/ioi/isolate). I've merely updated the code so that it can be used with Docker.

