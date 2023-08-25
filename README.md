<div align="center">

# README

  ![README Gif](https://github.com/oliviagallucci/README/blob/main/images/readme.gif)

  Olivia Gallucci's README Template written in [Markdown](https://www.markdownguide.org/basic-syntax/)

  <a href="https://github.com/oliviagallucci/README">![GitHub](https://img.shields.io/badge/github-EA4AAA.svg?style=for-the-badge&logo=github&logoColor=white)</a>
  <a href="https://github.com/oliviagallucci/README/blob/main/LICENSE.md">![GPLv3 license](https://img.shields.io/badge/License-GPLv3-green.svg?style=for-the-badge)</a>
  <a href="">![Markdown](https://img.shields.io/badge/markdown-9558B2.svg?style=for-the-badge&logo=markdown&logoColor=white)</a>
  <a href="https://github.com/sponsors/oliviagallucci">![Github-sponsors](https://img.shields.io/badge/sponsor-pink?style=for-the-badge&logo=GitHub-Sponsors&logoColor=#EA4AAA)</a>

</div>

## Banner

<!--
Choosing a title w GitHub SEO 

TODO: learn about markdown formatting practices 

add my blog colors to this doc and keep formatting consistent 

-->

* All elements centered
* Project title
  * [GitHub's SEO](https://www.developermarkepear.com/blog/github-search-engine-optimization) examines the project's name, description, topics, stars, watchers, and forks via traffic, the README, and file types
* Logo or banner
  * Usually created with [Canva](canva.com/). However, I am looking for a more **libre-friendly alternative**; please let me know if you are aware of one.
* Description
  * Include your **core keywords** and not much else. Add an [emoji](https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md) to the end of the description.
* Badges
  * Create [new](https://shields.io/) or use [pre-existing](https://github.com/Ileriayo/markdown-badges) badges
    * Unsupported [gradient](https://github.com/bokub/gradient-badge) badges
  * 4 badges
    * Programming language
    * License
    * Tech (ex: Docker)
    * Sponsor button

```html

<!-- Centers elements-->
<div align="center">

  <!--Project title-->
  # Project-title

  <!-- Light mode logo -->
  <img src="light-mode-logo.png" alt="Light mode logo" class="logo">

  <!-- Dark mode logo -->
  <img src="dark-mode-logo.png" alt="Dark mode logo" class="logo">

  <!-- -->
  ![]( Link_to_GIF_Logo_Image )

  <!--Description + emoji -->
  Description 

  <!--Badges-->
  <a href=" your_link ">![badge1](https://img.shields.io/badge1/)</a>
  <a href=" your_link ">![badge2](https://img.shields.io/badge2/)</a>
  <a href=" your_link ">![badge3](https://img.shields.io/badge3/)</a>
  <a href="https://github.com/sponsors/oliviagallucci">![Github-sponsors](https://img.shields.io/badge/sponsor-pink?style=for-the-badge&logo=GitHub-Sponsors&logoColor=#EA4AAA)</a>

</div>

<!--
  Below, I am displaying two different images with the same class name .logo but with different src attributes. Then, I use CSS media queries to hide the logo that's not appropriate for the user's current color scheme.
-->

<style>
@media (prefers-color-scheme: dark) {
  /* Hide light mode logo in dark mode */
  .logo[src="light-mode-logo.png"] {
    display: none;
  }
}

@media (prefers-color-scheme: light) {
  /* Hide dark mode logo in light mode */
  .logo[src="dark-mode-logo.png"] {
    display: none;
  }
}
</style>
```

<style>
@media (prefers-color-scheme: dark) {
  /* Hide light mode logo in dark mode */
  .logo[src="light-mode-logo.png"] {
    display: none;
  }
}

@media (prefers-color-scheme: light) {
  /* Hide dark mode logo in light mode */
  .logo[src="dark-mode-logo.png"] {
    display: none;
  }
}
</style>

## Usage

![Peek GIF](https://raw.githubusercontent.com/phw/peek/master/data/screenshots/peek-recording-itself.gif)

Create a GIF demo via [Peek](https://github.com/phw/peek) showing how the project is used. Credits to Peek for the GIF above.

* Create custom [Terminal GIFs](https://www.terminalgif.com/)

```markdown
![](https://github.com/oliviagallucci/delete-twitter-likes/blob/main/delete-twitter-likes-usage.gif)
```

### Steps

Usage steps

### Modifications

Be concise. People have incredibly short attention spans. Cut all the excess wording out of your README.

## Releases

* Use [semantic](https://semver.org/) versioning
  * Versions are separated into major, minor, patch and pre-release. The identifiers below from left to right: major, minor, and patch versions are always compared numerically.
    * Example: 1.0.0 < 2.0.0 < 2.1.0 < 2.1.1.
* Pre-release examples
  * 1.0.0-alpha
    * testing is done by developers only
  * 1.0.0-beta
    * testing is done by users and developers

## Acknowledgements

* Olivia Gallucci ([@oliviagallucci](https://github.com/oliviagallucci)) - [https://oliviagallucci.com](https://oliviagallucci.com/)
* List of [contributors](https://github.com/your_username/your_project/contributors) who participated in this project.
* Supporters (do something with this)

## Contributions

```markdown
![ImageTheOtherMarkdown](Screent.png)
```

## Warranty

### GPLv3

The author of this tool offers no warranty or guarantee for its performance, reliability, or suitability for any particular purpose.

The tool is provided "as is" without warranty of any kind, either express or implied, including but not limited to the implied warranties of merchantability, fitness for a particular purpose, or non-infringement.

Use of this tool is entirely at the user's own risk. The author does not accept any liability for any loss, damage or expense incurred by the user or any third party resulting from the use of this tool, whether direct or indirect.

Furthermore, the author expressly disclaims any responsibility or liability for the accuracy, content, or availability of information found through the use of this tool, or for any harm caused by viruses, malware, or other harmful components that may be introduced into your system as a result of using this tool.

By using this tool, the user acknowledges that they have read this warranty statement and agree to assume all risks associated with its use.

### MIT 

The creator(s) of this tool provides no warranty or assurance regarding its performance, dependability, or suitability for any specific purpose.

The tool is furnished on an "as is" basis without any form of warranty, whether express or implied, encompassing, but not limited to, implied warranties of merchantability, fitness for a particular purpose, or non-infringement.

The user assumes full responsibility for employing this tool and does so at their own peril. The creator(s) holds no accountability for any loss, damage, or expenses sustained by the user or any third party due to the utilization of this tool, whether in a direct or indirect manner.

Moreover, the creator(s) explicitly renounces any liability or responsibility for the accuracy, substance, or availability of information acquired through the use of this tool, as well as for any harm inflicted by viruses, malware, or other malicious components that may infiltrate the user's system as a result of employing this tool.

By utilizing this tool, the user acknowledges that they have perused and understood this warranty declaration and agree to undertake all risks linked to its utilization.

## License

This project is licensed under the General Public License version 3.0 - see the [LICENSE.md](LICENSE.md) file for details


## Definitions 

### Markdown 

Markdown is a lightweight markup language that is used to format plain text documents. It was created to be easy to write and read in plain text, while also allowing for the conversion of the text into HTML or other document formats. 

Markdown is often used for creating documents, web pages, README files, and other types of content that require basic formatting.

In Markdown, formatting is achieved through the use of simple and intuitive syntax, such as:

```markdown
# Top-level heading
## Second-level heading 
### Third-level heading (and so on)

*italic text* or _italic text_
**bold text** or __bold text__

1. First item
2. Second item

- Bulleted item 1
- Bulleted item 2

[Olivia's website](https://oliviagallucci.com)

![Alt text](image-url.png)

`inline code`

> This is a blockquote.
```

## Back-to-top button

<p align="center">
  <a href="https://github.com/oliviagallucci/README#readme">
    <img src="https://github.com/oliviagallucci/README/blob/main/images/backToTopButtonTransparentBackground.png" alt="Back to top" height="29"/>
  </a>
</p>

```html
<p align="center">
  <a href="https://github.com/username/your_project#">
    <img src="https://github.com/oliviagallucci/README/blob/main/images/backToTopButtonTransparentBackground.png" alt="Back to top" height="29"/>
  </a>
</p>
```

<!-- Attempt to make my website's button -->
<!--
<div align="center">
  <button type="button" 
    style="padding: 16px 32px; 
    font: bold 18px libre baskerville; 
    text-align: center; 
    display: inline-block;
    cursor: pointer;
    color: black; 
    border-radius: 99px;
    background: linear-gradient(135deg,rgb(108,208,250) 0%,rgb(152,150,240) 50%,rgb(255,110,199) 100%)" 
    >
    <a href="oliviagallucci.com/in-the-press/" 
       style="text-decoration:none; color:black;">
        Back to top
    </a>
  </button>
</div>
-->
