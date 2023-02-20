<div align="center">
  
  # README

  Olivia Gallucci's README Template

  <a href="">![GitHub](https://img.shields.io/badge/github-EA4AAA.svg?style=for-the-badge&logo=github&logoColor=white)</a>
  <a href="">![GPLv3 license](https://img.shields.io/badge/License-GPLv3-green.svg?style=for-the-badge)</a>
  <a href="">![JavaScript](https://img.shields.io/badge/javascript-9558B2.svg?style=for-the-badge&logo=JavaScript&logoColor=%23F7DF1E)</a>
  <a href="">![Github-sponsors](https://img.shields.io/badge/sponsor-pink?style=for-the-badge&logo=GitHub-Sponsors&logoColor=#EA4AAA)</a>
    
</div>

## Initial Design
github.jpg

<!--
Choosing a title 
GitHub SEO 

-->

### Centered
* Logo or banner 
  * Example: 
  * Usually created with [Canva](canva.com/). However, I am looking for a more <b>libre-friendly alternative</b>; please let me know if you are aware of one.  
* Description 
  * .
  * .
  * TODO what makes a good description? 
  * .
  * .
* Badges 
  * Pre-existing [badges](https://github.com/Ileriayo/markdown-badges)
  * Make badges at [shields.io/](https://shields.io/) 

```html
<!-- Centers elements-->
<div align="center">

  <!--Project title-->
  # Project-title

  <!--Description-->
  Description

  <!--Badges-->
  <a href="">![badge1](https://img.shields.io/badge1/)</a>
  <a href="">![badge2](https://img.shields.io/badge2/)</a>
  <a href="">![badge3](https://img.shields.io/badge3/)</a>
  <a href="">![badge4](https://img.shields.io/badge4/)</a>

</div>
```

## Usage 
![](https://raw.githubusercontent.com/phw/peek/master/data/screenshots/peek-recording-itself.gif)

> Reminder to create a GIF demo showing how the project is used]. You can record the GIF using a libre-friendly application, [Peek](https://github.com/phw/peek). Credits to Peek for the GIF above. 

* Create custom [Terminal GIFs](https://www.terminalgif.com/)

```markdown
![](https://github.com/oliviagallucci/delete-twitter-likes/blob/main/delete-twitter-likes-usage.gif)
```

### Steps
> usage steps 

### Modifications 

2. Be concise
People have incredibly short attention spans. Cut all the excess wording out of your READ-ME and get down to brass tacks.

## Releases 

* Use [semantic](https://semver.org/) versioning
  * Versions are separated into major, minor, patch and pre-release. The identifiers below from left to right: major, minor, and patch versions are always compared numerically.
    * Example: 1.0.0 < 2.0.0 < 2.1.0 < 2.1.1.
* Pre-release examples
  * 1.0.0-alpha 
    * testing is done by developers only
  * 1.0.0-beta
    * testing is done by users and developers 

## Authors 

* [Olivia Gallucci](https://github.com/oliviagallucci)
* List of [contributors](https://github.com/your_username/your_project/contributors) who participated in this project.

## Contributions 

## Supporters

## Warranty  

The author of this tool offers no warranty or guarantee for its performance, reliability, or suitability for any particular purpose.

The tool is provided "as is" without warranty of any kind, either express or implied, including but not limited to the implied warranties of merchantability, fitness for a particular purpose, or non-infringement.

Use of this tool is entirely at the user's own risk. The author does not accept any liability for any loss, damage or expense incurred by the user or any third party resulting from the use of this tool, whether direct or indirect.

Furthermore, the author expressly disclaims any responsibility or liability for the accuracy, content, or availability of information found through the use of this tool, or for any harm caused by viruses, malware, or other harmful components that may be introduced into your system as a result of using this tool.

By using this tool, the user acknowledges that they have read this warranty statement and agree to assume all risks associated with its use.

## License

This project is licensed under the General Public License version 3.0 - see the [LICENSE.md](LICENSE.md) file for details

## Back-to-top button

[🔼 Back to top](https://github.com/oliviagallucci/README#readme)

```markdown
[🔼 Back to top](#[link to readme header])
```

or 

<p align="center">
  <a href="https://github.com/oliviagallucci/README#readme">
    <img src="https://github.com/oliviagallucci/README/blob/main/backToTopButtonTransparentBackground.png" alt="Back to top" height="29"/>
  </a>
</p>

```html
<p align="center">
  <a href="https://github.com/username/your_project#">
    <img src="https://github.com/oliviagallucci/README/blob/main/backToTopButtonTransparentBackground.png" alt="Back to top" height="29"/>
  </a>
</p>
```



<script src="https://cdn.jsdelivr.net/npm/gradient-badge"></script>
<script>
    var svgString = gradientBadge({
        /* same as above */
        subject: 'version', // <text>
      status: 'v1.2.3', // <text>
      style: 'flat', // 'flat' or undefined, optional
     // And any other parameter supported by badgen (icon, scale...)
    gradient: ['pink', 'F78642'], // array of colors (Hexadecimal or name)
    });
</script>

Result: ![Result][usage]

[usage]: https://runkit.io/bokub/badge/branches/master/version/v1.2.3/pink-F78642?style=for-the-badge

