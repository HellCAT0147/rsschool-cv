# Ilya Bukhairov
![My photo](photo.jpg)

23.10.1995
## Contacts
* **Email:** letscheckmail23@gmail.com
* **Phone:** +998901873153
* **Location:** Tashkent, Uzbekistan
* **Discord:** HellCAT (@HellCAT0147)
* **Telegram:** [@HellCAT23](https://t.me/HellCAT23)

## Summary
Junior web-developer with basic knowledge of PHP, Java, Python, JavaScript.

## Education
> 01.09.2018 - 06.07.2022

St. Petersburg University of Industrial Technologies and Design: Higher School of Technology and Energy

Bachelor degree

01.03.02 - Applied Maths and Computer Science

## Work Experience
> 01.09.2011 - till now

OOO ALFAKOM STUDY

## Job Responsibilities
1. Alfakom website support;
1. Frontend development;
1. Backend development.

## Skills
* PHP + MySQL;
* HTML + CSS;
* Java;
* Python;
* JavaScript;
* Git;
* Adobe Photoshop;
* Microsoft Office.

## Code Example
``` PHP
/* get a list of all files in the "uploads" folder and come up with a new name for the new image */
function newName($dir){
  $files = glob($dir.'*.*');
  $i = 0;
  foreach($files as $file) {
    $file = pathinfo($file);
    $files[$i++] = $file['filename'];
  }
  if(count($files) == 0)
    $name = 1;
  else
    $name = max($files) + 1;
    return $name;
}
```

## Interests
I am fond of reading books on programming, such as: Michael Dawson - Programming in python; David Griffiths, Don Griffiths - Head First Android Programming, as well as taking online courses such as RS School JS/FE.

## Languages
Russian - Native
English - B1 (Pre-Intermediate)