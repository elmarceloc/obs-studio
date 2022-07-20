[7TV](https://github.com/SevenTV/SevenTV) emotes for [OBS Studio](https://github.com/obsproject/obs-studio)'s Chat

Basically adds this javascript code (7TV FFZ Addon) to the **auth-twitch.cpp** file


```c++

    static const char *stv_script = "\
    var stv = document.createElement('script');\
    stv.setAttribute('src','https://cdn.jsdelivr.net/gh/elmarceloc/seventv-build/content.js');\
    document.head.appendChild(stv);";


```
