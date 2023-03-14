# rsschool-cv

# Pavel Mihailov

# Contacts

Location: Mogilev, Belarus  
Phone:  +375 44 496-39-71  
Email: pamixy@gmail.com  
GitHub: [svygzhryr](https://github.com/Svygzhryr) 


# About me

For me, learning and discovering something new was always exciting, as well as challenging and overcoming myself. Trying my best in learning Front End and Javascript and looking forward for opportunities of employment. 


# Skills

* HTML
* CSS
* SCSS
* JavaScript
* React (basic)
* Figma
* Adobe Photoshop
* Git


# Code Example

Roman to integer converter:  
```js
    var romanToInt = function(s) {
    const numerals = {
        'I': 1,
        'V': 5,
        'X': 10,
        'L': 50,
        'C': 100,
        'D': 500,
        'M': 1000,
    }
    let arr = s.split('')
    let narr = [];
    arr.forEach((e) => {
        narr.push(numerals[e]);
    })
    let sum = 0;
    for (let i = 0; i < narr.length; i++) {
        if (narr[i] < narr[i + 1]) {
            sum -= narr[i];
        } else sum += narr[i]
    }
    return sum
};
```


# Experience

From most noticeable projects here is an online piano app made using react:  

* [Piano](https://svygzhryr.github.io/SvygzhryrPiano/)   

Pretty old mp3 player:  

* [Player](https://svygzhryr.github.io/SimplisticMusicPlayer/)  

Also i was working on some landing pages:

* [TheHumbleGuys](https://svygzhryr.github.io/THG/)  
* [MyBlog](https://svygzhryr.github.io/SomeDudesBlog/)  
* [NewWorld](https://svygzhryr.github.io/NewWorld/)  


# Education
* University: Belarusian-Russian University, biomedical engineering

# Languages

* Russian: native
* English: intermediate
* Belarusian: basic
