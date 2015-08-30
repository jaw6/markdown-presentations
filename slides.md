name: title
class: title-slide
layout: false

<footer>
  <span class="octicon octicon-logo-github"></span>
  <span class="tagline">How people build software</span>
</footer>

.mega-octicon.octicon-mark-github[]

# Title Text

Lorem ipsum dolor sit amet  
consectetur adipisicing elit  
sed do eiusmod tempor incididunt  
ut labore et dolore magna aliqua  
Ut enim ad minim veniam

---
layout: true
name: background

<footer>
  <span class="octicon octicon-mark-github"></span>
  <span class="tagline">How people build software</span>
</footer>

---

name: section-title
class: section-title-slide
layout: background

<span class="mega-octicon octicon-mark-github"></span>

# Title text

Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

---
name: body
class: body-slide
layout: background

# Title Text <span class="octicon octicon-mark-github"></span>

* Body Level One
    * Body Level Two
        * Body Level Three
            * Body Level Four
                * Body Level Five

---
class: bullet-slide
layout: background

# Title Text <span class="octicon octicon-mark-github"></span>

.column[
  .mega-octicon.octicon-calendar[]
  ## Text
  text
]

.column[
  .mega-octicon.octicon-bug[]
  ## Text
  text
]

.column[
  .mega-octicon.octicon-hubot[]
  ## Text
  text
]

---
class: code-slide
layout: background

# Title Text .octicon.octicon-mark-github[]

```java
////////////////////////////////////// 
//Put the cipher in encryption mode
desCipher.init(Cipher.ENCRYPT_MODE, desKey); 

//Encrypt and output the base64 data 
byte[] clearText = message1.getBytes(); 
byte[] encryptedBytes = desCipher.doFinal(clearText);
BASE64Encoder b64e = new sun.misc.BASE64Encoder();
String base64Encrypted = b64e.encode(encryptedBytes); 
System.out.println("Encrypted text: " + base64Encrypted);
```

---
class: title-slide
layout: background

.mega-octicon.octicon-mark-github[]

# Thank You!
