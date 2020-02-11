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

<br><br id="qa_steps">
_These are some of the manual steps after a colleague takes one QA job of a campaign built by another person:_

## QA Steps

1.  Jira ticket should be opened to see applied changes and check launching instructions for the QA of automation.
2.  All local proofs are opened one by one and checked in Outlook then “View e-mail online” button inside the e-mail is clicked.
3.  All e-mails open in browser.
4.  They should be checked in private mode.
5.  All CTAs and necessary links should be clicked.
6.  Landing pages’ urls should be checked to see if they are live and works properly as they should be

<h1 style="color: #eb4f34">What does the tool do?</h1>

*   The tool can open many things automatically and can open directly in incognito mode of the browser.


_**The user interface shows the options you can choose with the tool in the images below:**_

##  Home Screen (Requesting the path)

<div style="overflow: auto">
  <img src="/QA-Assistant/assets/images/empty_first.png" alt="empty_first.png" style="max-width: 370px; float: left; margin: 0 15px 15px 0;">
  <p style="color: #567482; background-color: #f3f6fa; border: solid 1px #dce6f0; padding: 0.8rem; overflow: auto; font-size: 16px; line-height: 1.45; border-radius: 0.3rem; margin:0">Tool first asks user to enter the path of a folder only consisting of .msg files.<br><br><br>An example of this folder can be seen in the next <a href="#folder">picture</a></p>
</div>
<br id="folder">
## Sample Folder

<div style="overflow: auto">
  <img src="/QA-Assistant/assets/images/folder.png" alt="folder.png" style="max-width: 530px; float: left; margin: 0 15px 15px 0;">
  <p style="color: #567482; background-color: #f3f6fa; border: solid 1px #dce6f0; padding: 0.8rem; overflow: auto; font-size: 16px; line-height: 1.45; border-radius: 0.3rem; margin:0">This folder should only include .msg files; otherwise the program gives error.<br><br><br>As it is seen, this is a sample of emails that are to be sent to 6 countries in 6 different languages.</p>
</div>
> _Location Bar:_
> <img src="/QA-Assistant/assets/images/copied_path.png" alt="path of a folder" style="max-width: 420px; display: block">
> 
> At this point, you can refresh your knowledge by reading required <a href="#qa_steps">QA Steps</a> again.

## Start the program

<div style="overflow: auto">
  <img src="/QA-Assistant/assets/images/filled_first.png" alt="filled_first.png" style="max-width: 370px; float: left; margin: 0 15px 15px 0;">
  <p style="color: #567482; background-color: #f3f6fa; border: solid 1px #dce6f0; padding: 0.8rem; overflow: auto; font-size: 16px; line-height: 1.45; border-radius: 0.3rem; margin:0">Copy the path of the folder by clicking inside the location bar<br><br><br> Paste the path to the input row.<br>Then press OK.</p>
</div>
> At this point, you can refresh your knowledge by reading required <a href="#qa_steps">QA Steps</a> again.
> 

## QA Options

<div style="overflow: auto">
  <img src="/QA-Assistant/assets/images/qa_options.png" alt="qa_options" style="max-width: 530px; float: left; margin: 0 15px 15px 0;">
  <p style="color: #567482; background-color: #f3f6fa; border: solid 1px #dce6f0; padding: 0.8rem; overflow: auto; font-size: 16px; line-height: 1.45; border-radius: 0.3rem; margin:0">Copy the path of the folder by clicking inside the location bar<br><br><br> Paste the path to the input row.<br>Then press OK.</p>
</div>
> At this point, you can refresh your knowledge by reading required <a href="#qa_steps">QA Steps</a> again.
> 

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
