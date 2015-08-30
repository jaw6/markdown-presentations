# GitHub-Flavored Presentations

This template uses the Markdown-driven slideshow tool [remark](http://gnab.github.io/remark/) to create an HTML-based presentation.

## Getting Started

0. Run `script/bootstrap`
0. Run `script/server`
0. visit [localhost:4000](http://localhost:4000)
0. Edit `slides.md`

## Formatting

### Title Slide

![Screenshot of title slide](https://cloud.githubusercontent.com/assets/173/9566023/a4a637ba-4ebf-11e5-92b2-0f7b8ab87abd.png)

```markdown
template: title

.mega-octicon.octicon-mark-github[]

# Title Text

Lorem ipsum dolor sit amet  
consectetur adipisicing elit
```

### Section Slide

![Screenshot of section](https://cloud.githubusercontent.com/assets/173/9566034/3acc0792-4ec0-11e5-8994-1750e3c1cc56.png)

```markdown
template: section

.mega-octicon.octicon-mark-github[]

# Title Text

Lorem ipsum dolor sit amet
```

### Content Slide

![Screenshot of content slide](https://cloud.githubusercontent.com/assets/173/9566042/79a8f4ac-4ec0-11e5-9285-7a1138c7434f.png)

```markdown
template: content

# Title Text .octicon.octicon-mark-github[]

* Body Level One
    * Body Level Two
        * Body Level Three
            * Body Level Four
                * Body Level Five
```

### Syntax highlighting

![Screenshot of syntax highlighting](https://cloud.githubusercontent.com/assets/173/9566046/b79db4be-4ec0-11e5-9084-f1e3a21dd3aa.png)

```
template: content

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

## TODO

- [ ] styleguide
- [ ] livereload
- [ ] dots on top of code block
- [ ] Implement dark theme
- [ ] Electron app to remove need for command-line (see [bkeepers/sopabox](https://github.com/bkeepers/soapbox))
- [ ] GitHub syntax theme
- [ ] Tips for presenter notes and presenting
