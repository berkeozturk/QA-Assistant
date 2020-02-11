---
layout: default
---

This is the presentation page for **QA Assistant**,  a tool that literally provides assistance to checking a batch of .msg (Outlook) emails in the quality assurance (QA) phase.

It was developed for the purpose of making some steps of QA process automatically.



© This program was coded in Python language by _Berke Öztürk_
<br><br><br>
**The process:**

While making QA for the e-mail campaigns, the team shares local proofs as a zip file that includes outlook (.msg) mails.

> Local proofs: emails that have dynamic text language and the URLs.
>
> E.g. "fr_fr" proof has French copy and goes to the "fr_fr" version of the landing page when a CTA has been performed. 

<br><br>
_These are some of the manual steps after a colleague takes one QA job of a campaign built by another person:_

## QA Steps

1.  Jira ticket should be opened to see applied changes and check launching instructions for the QA of automation.
2.  All local proofs are opened one by one and checked in Outlook then “View e-mail online” button insde the e-mail is clicked.
3.  All e-mails open in browser.
4.  They should be checked in private mode.
5.  All CTAs and necessary links should be clicked.
6.  Landing pages’ urls should be checked to see if they are live and works properly as they should be

<h1 style="color: #eb4f34">What does the tool do?</h1>

*   The tool can open many things automatically and can open directly in incognito mode of the browser.


_**The user interface shows the options you can choose with the tool in the images below:**_

##  Home Screen (Requesting the path)

<img src="/QA-Assistant/assets/images/empty_first.png" alt="empty_first.png" style="max-width: 300px">

This is a normal paragraph following a header. GitHub is a code hosting platform for version control and collaboration. It lets you and others work together on projects from anywhere.

## Header 2

> This is a blockquote following a header.
>
> When something is important enough, you do it even if the odds are not in your favor.

### Header 3

```js
// Javascript code with syntax highlighting.
var fun = function lang(l) {
  dateformat.i18n = require('./lang/' + l)
  return true;
}
```

```ruby
# Ruby code with syntax highlighting
GitHubPages::Dependencies.gems.each do |gem, version|
  s.add_dependency(gem, "= #{version}")
end
```



*   This is an unordered list following a header.
*   This is an unordered list following a header.
*   This is an unordered list following a header.

##### Header 5

1.  This is an ordered list following a header.
2.  This is an ordered list following a header.
3.  This is an ordered list following a header.

###### Header 6

| head1        | head two          | three |
|:-------------|:------------------|:------|
| ok           | good swedish fish | nice  |
| out of stock | good and plenty   | nice  |
| ok           | good `oreos`      | hmm   |
| ok           | good `zoute` drop | yumm  |

### There's a horizontal rule below this.

* * *

### Here is an unordered list:

*   Item foo
*   Item bar
*   Item baz
*   Item zip

### And an ordered list:

1.  Item one
1.  Item two
1.  Item three
1.  Item four

### And a nested list:

- level 1 item
  - level 2 item
  - level 2 item
    - level 3 item
    - level 3 item
- level 1 item
  - level 2 item
  - level 2 item
  - level 2 item
- level 1 item
  - level 2 item
  - level 2 item
- level 1 item

### Small image

![homescreen](/assets/images/empty_first.png)

### Large image

![Branching](https://guides.github.com/activities/hello-world/branching.png)


### Definition lists can be used with HTML syntax.

<dl>
<dt>Name</dt>
<dd>Godzilla</dd>
<dt>Born</dt>
<dd>1952</dd>
<dt>Birthplace</dt>
<dd>Japan</dd>
<dt>Color</dt>
<dd>Green</dd>
</dl>

```
Long, single-line code blocks should not wrap. They should horizontally scroll if they are too long. This line should be long enough to demonstrate this.
```

```
The final element.
```
