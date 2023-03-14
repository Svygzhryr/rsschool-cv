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

