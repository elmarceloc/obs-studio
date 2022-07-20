An implementation of the popular twitch extension 7TV into OBS Studio

Basically adds this javascript code to the **auth-twitch.cpp** file


```c++

    static const char *stv_script = "\
    var stv = document.createElement('script');\
    stv.setAttribute('src','https://cdn.jsdelivr.net/gh/elmarceloc/seventv-build/content.js');\
    document.head.appendChild(stv);";


```
