<h1 align="center">
  <br>
  <img width="40%" src="https://github.com/vision-consensus/vision-material-repo/raw/master/images/vision-banner.png">
  <br>
  Visionscan First Validator Template
  <br>
</h1>

<h4 align="center">
  Template for First Validator to publish on <a href="https://visionscan.org">Visionscan.org</a>
</h4>

<p align="center">
  <a href="#how-to-use">How to use</a> •
  <a href="#example">Example</a> •
  <a href="#faq">FAQ</a> •
  <a href="https://visionscan.org">Visionscan.org</a>
</p>

## Intro

Tronscan provides a way for First Validator to publish their information right where the voters are, on Tronscan!

First Validator can use this template to build a static page which will be shown on Tronscan. The link will be placed in the voting overview page right next to the name.

By editing files in the repository on Github the First Validator can manage their own content.


## Example

The example shows which files are presented where. Whenever the files on Github are modified the page will instantly be updated

![](https://github.com/vision-consensus/vision-material-repo/raw/master/images/example-page.png)

__Example First Validator Pages__

* [CryptoGuyInZA](https://www.visionscan.org/#/representative/VMKWT86BYGSgtyeeYWcmuajzjtJhKGVBuF)
* [Skypeople](https://www.visionscan.org/#/representative/VMKWT86BYGSgtyeeYWcmuajzjtJhKGVBuF)
* [CryptoChain](https://www.visionscan.org/#/representative/VMKWT86BYGSgtyeeYWcmuajzjtJhKGVBuF)

## How to use

__This guide assumes that you already have an account which has First Validator (candidate) status__

### Step 1: Copy/Fork the template on Github

* Go to https://github.com/vision-consensus/vision-fv-template
* Fork the repository  
![](https://github.com/vision-consensus/vision-material-repo/raw/master/images/fork-repo.png)

After forking the repository you will be navigated to your own `visionfv-template` version of the repository where you can make changes

## Step 2: Fill in the template

The template can now be modified by editing files on Github.

* Click the file you want to edit  
![](https://github.com/vision-consensus/vision-material-repo/raw/master/images/github-open-file.png)
* Open edit modus
![](https://github.com/vision-consensus/vision-material-repo/raw/master/images/github-edit-file.png)
* Add some information to the file
![](https://github.com/vision-consensus/vision-material-repo/raw/master/images/edit-team-intro.png)

Files are written in markdown format. An excellent intro can be found at https://guides.github.com/features/mastering-markdown/

* Update the logo.png and banner.png  
![](https://github.com/vision-consensus/vision-material-repo/raw/master/images/github-upload-files.png) 
Then click on "choose your files" and make sure the logo or banner you want to upload is named `logo.png` or `banner.png` to overwrite the placeholder images.

After you filled in the template it can now be published on https://visionscan.org

## Step 3: Publish to Tronscan

* Navigate to https://visionscan.org
* Login to your account. In this example it shows using the plugin, but you may use any login method.
![](https://github.com/vision-consensus/vision-material-repo/raw/master/images/login-with-plugin.png)
* Open account and make sure the "Representative" label is visible  
![](https://github.com/vision-consensus/vision-material-repo/raw/master/images/open-account.png)
* Scroll to the bottom and click "Set Github Link"
![](https://github.com/vision-consensus/vision-material-repo/raw/master/images/set-github-link.png)
* Input your Github username and then press "Link Github"  
![](https://github.com/vision-consensus/vision-material-repo/raw/master/images/input-username.png)

## Translations

Checkout the [Pages](/pages) directory for the translation readme

## FAQ

* __I've modified a file but the changes aren't visible on visionscan.org?__  
  Contents from the repository are served using the Github CDN which uses aggressive caching. It may take a few minutes before the changes are reflected on visionscan.org.
* __Why are HTML elements visible on Github but not on visionscan.org?__  
  Tronscan.org will sanitize all HTML tags for security reasons, only standard markdown tags are allowed
