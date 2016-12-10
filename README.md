# HTML 5

An extensive HTML 5 template for web designers and developers. It's written based on the latest available technologies presented by modern web browsers!

`PS : Internet Explorer is not a modern browser!, Stop rolling your eyes!` 

It has always been a struggle to find an extensive HTML5 template to use. this one is what I've gathered and learned in the past couple of years working as a web developer and designer.

This repository is going to be updated as soon a new things appear in the web development community.

I've added some of the common `meta` tags that is used by developers. and here is some explanations:

- [Recommended Minimum](#recommended-minimum)
- [Elements](#elements)
- [Meta](#meta)
- [Link](#link)

## Recommended Minimum
Essential tags for basic, minimalist websites:

```html
<meta charset="utf-8">
<meta http-equiv="x-ua-compatible" content="ie=edge">
<meta name="viewport" content="width=device-width, initial-scale=1">
<!-- The above 3 meta tags *must* come first in the head; any other head content must come *after* these tags -->
<title>Page Title</title>
```

## Elements

``` html
<!DOCTYPE html>
<html>

<head>
    <meta charset="utf-8">
    <meta http-equiv="x-ua-compatible" content="ie=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <!-- The above 3 meta tags *must* come first in the head; any other head content must come *after* these tags -->
    <title>Page Title</title>

    <!-- Load your css stylesheets-->
    <link href="css/style.css" rel="stylesheet">

    <!--[if IE 7 ]>
        <p>Please go shoot yourself</p>
    <![endif]-->
</head>

<body>
    <div class="content">
        <!--Some content would eventually come here-->
    </div>
    <!--Load Javascript Libraries -->
    <script src="myscripts.js"></script>
</body>

</html>

```

## Meta

``` html
<meta charset="utf-8"> <!-- set character encoding for the document -->
<meta http-equiv="x-ua-compatible" content="ie=edge">
<meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
<!-- The above 3 meta tags *must* come first in the head; any other head content must come *after* these tags -->

<!-- Allows control over where resources are loaded from -->
<meta http-equiv="Content-Security-Policy" content="default-src 'self'">
<!-- Place as early in the document as possible -->
<!-- Only applies to content below this tag -->

<!-- Name of web application (only should be used if the website is used as an app) -->
<meta name="application-name" content="Application Name">

<!-- Short description of the page (limit to 150 characters) -->
<!-- In *some* situations this description is used as a part of the snippet shown in the search results. -->
<meta name="description" content="A description of the page">

<!-- Control the behavior of search engine crawling and indexing -->
<meta name="robots" content="index,follow,noodp"><!-- All Search Engines -->
<meta name="googlebot" content="index,follow"><!-- Google Specific -->

<!-- Tells Google not to show the sitelinks search box -->
<meta name="google" content="nositelinkssearchbox">

<!-- Tells Google not to provide a translation for this page -->
<meta name="google" content="notranslate">

<!-- Verify ownership for Google Search Console -->
<meta name="google-site-verification" content="verification_token">

<!-- Used to name software used to build the website (i.e. - WordPress, Dreamweaver) -->
<meta name="generator" content="program">

<!-- Short description of your site's subject -->
<meta name="subject" content="your website's subject">

<!-- Very short (10 words or less) description. Primarily for academic papers -->
<meta name="abstract" content="">

<!-- Full domain name or web address -->
<meta name="url" content="https://example.com/">

<meta name="directory" content="submission">

<!-- Gives a general age rating based on sites content -->
<meta name="rating" content="General">

<!-- Allows control over how referrer information is passed -->
<meta name="referrer" content="no-referrer">

<!-- Disable automatic detection and formatting of possible phone numbers -->
<meta name="format-detection" content="telephone=no">

<!-- Completely opt out of DNS prefetching by setting to 'off' -->
<meta http-equiv="x-dns-prefetch-control" content="off">

<!-- Stores cookie on the client web browser for client identification -->
<meta http-equiv="set-cookie" content="name=value; expires=date; path=url">

<!-- Specifies the page to appear in a specific frame -->
<meta http-equiv="Window-Target" content="_value">

<!-- Geo tags -->
<meta name="ICBM" content="latitude, longitude">
<meta name="geo.position" content="latitude;longitude">
<meta name="geo.region" content="country[-state]"><!-- Country code (ISO 3166-1): mandatory, state code (ISO 3166-2): optional; eg. content="US" / content="US-NY" -->
<meta name="geo.placename" content="city/town"><!-- eg. content="New York City" -->

<!-- Dealing with caching issues among browsers specially the stupid one IE-->
<meta http-equiv="cache-control" content="max-age=0">
<meta http-equiv="cache-control" content="no-cache">
<meta http-equiv="expires" content="0">
<meta http-equiv="expires" content="Tue, 01 Jan 1980 1:00:00 GMT">
<meta http-equiv="pragma" content="no-cache">

```

## Link

``` html
<!-- Helps prevent duplicate content issues -->
<link rel="canonical" href="https://example.com/2010/06/9-things-to-do-before-entering-social-media.html">

<!-- Used to be included before the icon link, but is deprecated and no longer is used -->
<link rel="shortlink" href="https://example.com/?p=42">

<!-- Links to an AMP HTML version of the current document -->
<link rel="amphtml" href="https://example.com/path/to/amp-version.html">

<!-- Points to a CSS stylesheet -->
<link rel="stylesheet" href="https://example.com/styles.css">

<!-- Links to a JSON file that specifies "installation" credentials for web applications -->
<link rel="manifest" href="manifest.json">

<!-- Links to the author of the document -->
<link rel="author" href="humans.txt">

<!-- Refers to a copyright statement that applies to the links context -->
<link rel="copyright" href="copyright.html">

<!-- Gives a reference to a location in your document that may be in another language -->
<link rel="alternate" href="https://es.example.com/" hreflang="es">

<!-- Gives information about an author or another person -->
<link rel="me" href="https://google.com/profiles/thenextweb" type="text/html">
<link rel="me" href="mailto:name@example.com">
<link rel="me" href="sms:+77777777">

<!-- Links to a document that contains an archive link to the current document -->
<link rel="archives" href="https://example.com/2003/05/" title="May 2003">

<!-- Links to top level resource in an hierarchical structure -->
<link rel="index" href="https://example.com/" title="DeWitt Clinton">

<!-- Gives the starting point of the document -->
<link rel="start" href="https://example.com/photos/pattern_recognition_1_about/" title="Pattern Recognition 1">

<!-- Leads to the preceding resource of the sequence the current document is in -->
<link rel="prev" href="https://example.com/opensearch/opensearch-and-openid-a-sure-way-to-get-my-attention/" title="OpenSearch and OpenID? A sure way to get my attention.">

<!-- Gives a self reference - useful when the document has multiple possible references -->
<link rel="self" type="application/atom+xml" href="https://example.com/atomFeed.php?page=3">

<!-- The first, next, previous, and last documents in a series of documents, respectively -->
<link rel="first" href="https://example.com/atomFeed.php">
<link rel="next" href="https://example.com/atomFeed.php?page=4">
<link rel="previous" href="https://example.com/atomFeed.php?page=2">
<link rel="last" href="https://example.com/atomFeed.php?page=147">

<!-- Used when using a 3rd party service to maintain a blog -->
<link rel="EditURI" href="https://example.com/xmlrpc.php?rsd" type="application/rsd+xml" title="RSD">

<!-- Forms an automated comment when another WordPress blog links to your WordPress blog or post -->
<link rel="pingback" href="https://example.com/xmlrpc.php">

<!-- Notifies a url when you link to it on your site -->
<link rel="webmention" href="https://example.com/webmention">

<!-- Loads in an external HTML file into the current HTML file -->
<link rel="import" href="component.html">

<!-- Open Search -->
<link rel="search" href="/open-search.xml" type="application/opensearchdescription+xml" title="Search Title">

<!-- Feeds -->
<link rel="alternate" href="https://feeds.feedburner.com/example" type="application/rss+xml" title="RSS">
<link rel="alternate" href="https://example.com/feed.atom" type="application/atom+xml" title="Atom 0.3">

<!-- Prefetching, preloading, prebrowsing -->
<link rel="dns-prefetch" href="//example.com/">
<link rel="preconnect" href="https://www.example.com/">
<link rel="prefetch" href="https://www.example.com/">
<link rel="prerender" href="https://example.com/">
<link rel="preload" href="image.png" as="image">
<!-- More info: https://css-tricks.com/prefetching-preloading-prebrowsing/ -->
```