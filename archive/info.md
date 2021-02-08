---
title: "info"
search: false
permalink: /archive/info/
excerpt: "for admin only"
last_modified_at: 2020-10-28
redirect_from:
  - /theme-setup/
gallery:
  - url: /assets/images/unsplash-gallery-image-1.jpg
    image_path: /assets/images/unsplash-gallery-image-1-th.jpg
    alt: "placeholder image 1"
    title: "Image 1 title caption"
  - url: /assets/images/unsplash-gallery-image-2.jpg
    image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Image 2 title caption"
  - url: /assets/images/unsplash-gallery-image-3.jpg
    image_path: /assets/images/unsplash-gallery-image-3-th.jpg
    alt: "placeholder image 3"
    title: "Image 3 title caption"
feature_row:
  - image_path: /assets/images/unsplash-gallery-image-1-th.jpg
    alt: "placeholder image 1"
    title: "Placeholder 1"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Placeholder 2"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--inverse"
  - image_path: /assets/images/unsplash-gallery-image-3-th.jpg
    title: "Placeholder 3"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
toc: true
toc_label: "testing"
toc_icon: "cogs"
---

This is a `sentence` [This is a link](https://www.google.com) :wink: and **this can be bold [bold link](https://www.google.com).**

Markdowns
1. `word`
2. **bold**
3. ***bold italic***
3. *italic*
4. ~~strikethrough~~

> This is a quote. *Quote can be stylish*

- [x] this is a complete 
- [ ] this is an incomplete 

[![Invite Zarena](https://cdn.jsdelivr.net/gh/twolfson/paypal-github-button@1.0.0/dist/button.svg)](https://discordapp.com/api/oauth2/authorize?client_id=471701482874601472&scope=bot&permissions=8)

[<i class="fas fa-download"></i> Download something lol](https://google.com){: .btn .btn--success}

## Line1

[^structure]: See [**Structure** page]({{ "/docs/structure/" | relative_url }}) This is a sentence which comes at last.

**ProTip:** This is a info sentence `/This is a sentence` [link1](https://google.com) [link2][netlify-jekyll], [link3](#ruby-gem-method). [`/word` link4](https://google.com) 
{: .notice--info}

[netlify-jekyll]: https://www.google.com/

**Note:** This is a warning sentence [link](https://google.com).`word` and `word 'word'`.<http://google.com>.
{: .notice--warning}

**Danger:** This is a info sentence
{: .notice--danger}

## Line2

1. This is a ruby:
   ```ruby
   gem "ruby highlight"
   # Hello! This is really long sentence so long that it needs horizontal slider.
   group :jekyll_plugins do
   end
   ```

2. This is bash:
   ```bash
   $ shit install
   ```

3. This is yaml:
```yaml
defaults:
  - scope:
      path: ""
      type: tag
    values:
      author_profile: true
```
   
4. This is javascipt:
```javascript
function fancyAlert(arg) {
   if(arg) {
     $.facebox({div:'#foo'})
  }
}
```
   
5. This is liquid:
   ```liquid
   {% raw %}{% include feature_row %}{% endraw %}
   ```
   
3. This is python:
   ```python
   print("Hello world")
   ```

This is a sentence `word`.
---
<div class="notice--success" markdown="1">

<h4 class="no_toc"><i class="fas fa-lightbulb"></i> Tip</h4>

This is a sentence. [A link](https:google.com) can also be `included`.

```yaml
defaults:
  - scope:
      path: ""
      type: tag
    values:
      author_profile: true
```

</div>

---

<figure>
  <img src="{{ '/assets/images/mm-gh-pages.gif' | relative_url }}" alt="creating a new branch on GitHub">
</figure>

---

<figure>
  <img src="{{ '/assets/images/mm-theme-fork-repo.png' | relative_url }}" alt="fork Minimal Mistakes">
</figure>

{:.no_toc}

<figure class="half">
    <a href="{{ site.baseurl }}/assets/images/air-skin-archive-large.png"><img src="{{ site.baseurl }}/assets/images/air-skin-archive.png"></a>
    <a href="{{ site.baseurl }}/assets/images/air-skin-post-large.png"><img src="{{ site.baseurl }}/assets/images/air-skin-post.png"></a>
    <figcaption>Calm and blue.</figcaption>
</figure>

{% include figure image_path="/assets/images/unsplash-image-10.jpg" alt="this is a placeholder image" caption="This is a figure caption." %}

{% include gallery caption="This is a sample gallery with **Markdown support**." %}

{% include feature_row %}

{% include video id="XsxDH4HcOWA" provider="youtube" %}

![image-center]({{ "/assets/images/image-alignment-580x300.jpg" | relative_url }}){: .align-center}

![image-left]({{ "/assets/images/image-alignment-150x150.jpg" | relative_url }}){: .align-left} The rest of this paragraph is filler for the sake of seeing the text wrap around the 150×150 image, which is **left aligned**. There should be plenty of room above, below, and to the right of the image. Just look at him there --- Hey guy! Way to rock that left side. I don't care what the right aligned image says, you look great. Don't let anyone else tell you differently.

Buttons!
[simple](#link){: .btn} [primary](#link){: .btn .btn--primary} [success](#link){: .btn .btn--success} [warning](#link){: .btn .btn--warning} [danger](#link){: .btn .btn--danger} [info](#link){: .btn .btn--info} [Inverse](#link){: .btn .btn--inverse} [Invisible](#link){: .btn .btn--light-outline}

Alerts!
**Watch out!** This is[notice](#).
{: .notice}

**Watch out!** This is [primary](#).
{: .notice--primary}

**Watch out!** This is [info](#).
{: .notice--info}

**Watch out!** This is [warning](#).
{: .notice--warning}

**Watch out!** This is [success](#).
{: .notice--success}

**Watch out!** This is [danger](#).
{: .notice--danger}

{% capture notice-text %}
This is a sentence

* Bullet point 1
* Bullet point 2
{% endcapture %}

<div class="notice--info">
  <h4 class="no_toc">Notice Headline:</h4>
  {{ notice-text | markdownify }}
</div>

## Line3
### Sub line1
### Sub line2
### Sub line3

This is a list

- `.list1`
- `/list2`
- list 3

### Line3
This is a sentence [**Configuration**]({{ "/docs/configuration/" | relative_url }}) .

- [`_data/ui-text.yml`][ui-text.yml] - This is a sentence1 [documentation]({{ "/docs/ui-text/" | relative_url }})
- [`_data/navigation.yml`][navigation.yml] - This is a sentence2 [documentation]({{ "/docs/navigation/" | relative_url }})

  [ui-text.yml]: https://github.com/mmistakes/minimal-mistakes/blob/master/_data/ui-text.yml
  [navigation.yml]: https://github.com/mmistakes/minimal-mistakes/blob/master/_data/navigation.yml

```terminal
├── c
├── c++
├── java
├── python
|  ├── html
|  ├── css
|  └── js
```

```bash
minimal-mistakes
├── data                      # test
|  ├── navigation.yml          # test
|  └── ui-text.yml             # test
├── includes
|  ├── analytics-providers     # test
|  ├── comments-providers      # test
|  ├── toc                     # test
|  └── ...
├── assets
|  ├── images                  # test
|  ├── js
|  |  ├── plugins              # test
|  |  ├── vendor               # test
|  |  ├── _main.js             # test
|  |  └── main.min.js          # test
├── index.html                 # test
└── package.json               # test
```

Here's a table:

| Name              |                 |
| ----              | ---             |
| `field1`          | something       |
| `field2`          | something.      |
| field3            | `something`.    |
| **field4**        | **something**.  |

This is just a line

| Name             | Comment Provider                                             |
| ---------------- | -------------------------------------------------------------|
| **disqus**       | Disqus                                                       |
| **discourse**    | Discourse                                                    |
| **facebook**     | Facebook Comments                                            |
| **utterances**   | utterances                                                   |
| **custom**       |  [cool](https://google.com) <i class="fas fa-file-alt"></i>. |

---
---

sentence1[^structure] .

sentence2[^update-jekyll] 

[^update-jekyll]: This will go to sentence2 `word`.

---

That's it!.
