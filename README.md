# tabbed-sectionals
Creating quality sectional content is essential to showcasing your service or product. Occassionaly, however, design limitations can impact how much space you can afford to this necessary content. One solution is to include everything within separate tabs. This approach allows you to drastically increase the amount of content you include on a page while allowing you to work with, rather than against, your design. In this article, [Solodev](https://www.solodev.com/blog/) will teach you how to created tabbed sectional content for your website using HTML, CSS, and JavaScript. 

## Tutorial

For detailed instructions, vew Solodev's [Adding Sectional Tabs to your Homepage](https://www.solodev.com/blog/web-design/adding-sectional-tabs-to-your-homepage.stml) article.

## Demo

Try out a working example on [JSFiddle](https://jsfiddle.net/solodev/3q8ksc2d/).

## HTML

The tabbed sectionals contains the following basic HTML markup.

```
<section class="hTabsSection paddingTop60">
    <div class="container-fluid full-width text-center">
      <h2>Our Services Deliver Impact</h2>
      <p>Our teams are disrupting industry standards.</p>
      <div class="hTabsTop">
        <ul class="hTabs nav nav-pills" id="mainTabs" role="tablist">
          <li role="presentation" class="active build-tab"><a href="#build" aria-controls="build" role="tab" data-toggle="tab"><i class="fa fa-bar-chart" aria-hidden="true"></i>
 Strategy </a></li>
          <li role="presentation host-tab"><a href="#host" aria-controls="host" role="tab" data-toggle="tab"><i class="fa fa-server">&nbsp;</i> Engineering</a></li>
          <li role="presentation support-tab"><a href="#support" aria-controls="manage" role="tab" data-toggle="tab"><i class="fa fa-laptop" aria-hidden="true"></i>
 Products</a></li>
        </ul>
        <div class="hTabContent tab-content">
          <div role="tabpanel" class="tab-pane active" id="build">
            <div class="hTabProductImage video-container">
              <div class="video-monitor">
                <img src="https://www.solodev.com/assets/tab-img/1.png">
              </div>
            </div>
            <div class="hTabColumns">
              <div class="col-sm-4 text-left hpColumn">
                <h3>Consulting</h3>
                <p>The best consulting from the greatest minds from across the globe.</p>
              </div>
              <div class="col-sm-4 text-left hpColumn">
                <h3>Strategic Innovation</h3>
                <p>Innovating with every step we take.</p>
              </div>
              <div class="col-sm-4 text-left hpColumn">
                <h3>Market Analaysis</h3>
                <p>Making markets and making sense of existing markets.</p>
              </div>
            </div>
          </div>
          <div role="tabpanel" class="tab-pane" id="host">
            <div class="hTabProductImage video-container">
              <div class="video-monitor">
                <img src="https://www.solodev.com/assets/tab-img/3.png">
              </div>
            </div>
            <div class="hTabColumns">
              <div class="col-md-4 text-left hpColumn">
                <h3>Cloud Computing</h3>
                <p>Implementing rock-solid cloud computing solutions to serve any needs.</p>
              </div>
              <div class="col-md-4 text-left hpColumn">
                <h3>Systems Delivery</h3>
                <p>A complete turney systems delivery offering.</p>
              </div>
              <div class="col-md-4 text-left hpColumn">
                <h3>Cyber Security</h3>
                <p>Making sure you're IT infrastructure is never hacked. Ever.</p>
              </div>
            </div>
          </div>
          <div role="tabpanel" class="tab-pane" id="support">
            <div class="hTabProductImage video-container">
              <div class="video-monitor">
                <img src="https://www.solodev.com/assets/tab-img/4.png">
              </div>
            </div>
            <div class="hTabColumns">
              <div class="col-md-4 text-left hpColumn">
                <h3>IT Strategy</h3>
                <p>Strategy is the name of the game in implementing IT solutions. We're #1 in that game.</p>
              </div>
              <div class="col-md-4 text-left hpColumn">
                <h3>Operational Effiency</h3>
                <p>Let us take a look under the hood and help improve operational efficiency.</p>
              </div>
              <div class="col-md-4 text-left hpColumn">
                <h3>Change Management</h3>
                <p>Easing the transition of power within organizations.</p>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="row">
        <div class="col-md-12 text-center hTabsButtons">
          <a class="btn btn-home" href="/new-features/" id="blankLink0">View All Features</a>
        </div>
      </div>
    </div>
</section>
```

## CSS

All required CSS is in tabbed-sectional.css

## JavaScript

No JavaScript is needed for this tutorial.

## External Includes

This tutorial includes the following third party resources.
```
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
<link href="https://maxcdn.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css" rel="stylesheet" >
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.1.1/jquery.min.js"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
```
