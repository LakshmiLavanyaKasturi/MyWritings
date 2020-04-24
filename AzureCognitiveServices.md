# AZURE COGNITIVE SERVICES DIRECTORY

Enable apps and services to harness the power of a Web-scale, ad-free search engine with Search. Use search services to find exactly what you’re looking for across billions of web pages, images, videos, and news search results.

[Bing Spell Check](https://github.com/LakshmiLavanyaKasturi/searchAPI/blob/master/BingSpellCheck.md).

[Bing Visual Search](https://azure.microsoft.com/en-us/services/cognitive-services/bing-visual-search/).

[Bing Entity Search](https://azure.microsoft.com/en-us/services/cognitive-services/bing-entity-search-api/).

[Bing News Search](https://azure.microsoft.com/en-us/services/cognitive-services/bing-news-search-api/).

[Bing Auto Suggest](https://azure.microsoft.com/en-us/services/cognitive-services/autosuggest/).

[Bing web Search](https://azure.microsoft.com/en-us/services/cognitive-services/bing-web-search-api/)

[Bing Custom Search](https://azure.microsoft.com/en-us/services/cognitive-services/bing-custom-search/)

[Bing Video Search](https://azure.microsoft.com/en-us/services/cognitive-services/bing-video-search-api/)

[Bing Image Search](https://azure.microsoft.com/en-us/services/cognitive-services/bing-image-search-api/)

[Bing Local Business](https://azure.microsoft.com/en-us/services/cognitive-services/bing-local-business-search/)

# Bing Entity Search

Bring rich context about people, places, things, and local businesses to your apps through entity information for a more engaging user experience.

[Try it now](https://azure.microsoft.com/en-us/services/cognitive-services/bing-entity-search-api/)

Examples: 
    Satya nadella  
    Market ( en-us (English - United States) )
    
 ##### Optional Parameters:
 
 1. Latitude
 2. Longitude
 3. Radius (meters)
 
 # [Bing Spell Check](https://docs.microsoft.com/en-us/azure/cognitive-services/bing-spell-check/).

*The Bing Spell Check API lets you perform contextual grammar and spell checking. Bing has developed a web-based spell-checker that leverages machine learning and statistical machine translation to dynamically train a constantly evolving and highly contextual algorithm. The spell-checker is based on a massive body of web searches and documents. Learn how to analyze content in different ways with our quickstarts, tutorials, and samples.*

***

### Spell Check Modes 
Multiple spell check modes enable you to get corrections focused on grammar and/or spelling.

1. __Word Breaks__
    1. Correct word-breaking issues with a single flag.
    
    ![](https://github.com/LakshmiLavanyaKasturi/searchAPI/blob/master/word-breaks.png)

2. __Slang__
    1. Easily recognize slang and informal language.
    
    ![](https://github.com/LakshmiLavanyaKasturi/searchAPI/blob/master/slang.png)

3. __Names__
    1. Spot common name errors in context.
    
    ![](https://github.com/LakshmiLavanyaKasturi/searchAPI/blob/master/names.png)    
    
3. __Homonyms__
    1. Fix homonyms and other hard-to-spot errors in context.
    
    ![](https://github.com/LakshmiLavanyaKasturi/searchAPI/blob/master/brands.png)

4. __Brands__
    1. Provide support for new brands and other coined expressions as they emerge.
    
    ![](https://github.com/LakshmiLavanyaKasturi/searchAPI/blob/master/brands.png)

The Bing Spell Check API is easy to call from any [programming language ](https://en.wikipedia.org/wiki/List_of_programming_languages)that can make HTTP requests and parse JSON responses. The service is accessible using the REST API or the Bing Spell Check SDKs.

# BING VISUAL SEARCH
### Interpret images to build tailored visual experiences

Create compelling visual experiences through interpretation of images on a device of your choice. Enrich the search experience with visually similar images and products from your business, and use Bing Visual Search to recognize celebrities, monuments, artwork, and other related objects. Identify barcodes or extract textual information from images to provide rich insights—all through the single API.

![](https://github.com/LakshmiLavanyaKasturi/searchAPI/blob/master/VisualSearch1.png)


**Search results**

![](https://github.com/LakshmiLavanyaKasturi/searchAPI/blob/master/pic%201.jpg)
![](https://github.com/LakshmiLavanyaKasturi/searchAPI/blob/master/pic%202.jpg)
![](https://github.com/LakshmiLavanyaKasturi/searchAPI/blob/master/pic%203.jpg)
![](https://github.com/LakshmiLavanyaKasturi/searchAPI/blob/master/pic%204.jpg)
![](https://github.com/LakshmiLavanyaKasturi/searchAPI/blob/master/pic%205.jpg)
![](https://github.com/LakshmiLavanyaKasturi/searchAPI/blob/master/pic%206.jpg)


### Discover intelligent context identification
Use smart identification of image content to recognize celebrities, find products, or search for related content. Bing Visual Search automatically identifies the type of picture, recognizing image context whether it is a barcode, a business card, or a product.

### Enhance product recommendations for your business
Create compelling product recommendations for your domain through visually similar images and products. For example, build a crop-free product selection experience for your users to detect and delineate fashion products automatically.

### Make your applications and devices intelligent
Add search intelligence to your apps and devices. Integrate with any image source to get annotations and information, whether using a bot, mobile device, or output from another Cognitive Service.

### Augment image understanding through OCR
Extract structured textual information to build better search results by reading the text in images using optical character recognition (OCR).

### Powerful statistics for your queries
Inform your strategic decisions with the Bing Statistics add-in. Quickly retrieve statistics such as your top queries, call volume, market distribution, response code summary, and many more—and derive rich insights to advance your business. Visit the [portal](https://www.bingapistatistics.com/) to consume these statistics. You can subscribe to Bing Statistics Add-in from [Azure Portal](https://login.microsoftonline.com/common/oauth2/authorize?resource=https%3a%2f%2fmanagement.core.windows.net%2f&response_mode=form_post&response_type=code+id_token&scope=user_impersonation+openid&state=OpenIdConnect.AuthenticationProperties%3dbdsxWrEDv9E1cDwdAoAIe6-bAj0nSprMxNhNmLbQuqOWfrGrS6mSv4T9LSQ6qBjfMlZeHSS1FLhns6aaURKw6QekZYkuRxp9xL7hd6HLXfmbQnpyNfgmzAEU6BIT6Ub2Dhf1cUK6lzrOQlcpNheqJ7afCPPVSuaQsDcN93lvumPXBEUpEIvX_cM0ts9-2hAnJ-YrYWId9RSWxrZK3M2FfNFAFjEePqAMH46BgkN479jXxTGsWBgWfydu6lg2FQ8_JLA0QuzAgpCcH31BrpxvM7omq1DIYcbV_oSZeXk4M1UL97lnSXKmd0JZSATPGV9w&nonce=637039189532481553.NTBmODViY2YtNGI2YS00ZGViLWI4ODQtNmI1ZjI1YjYyZjZiNTU1NGVjZjktNGQwMi00MzBlLWIwYzgtNmJlMDIxZjYwNWMz&client_id=c44b4083-3bb0-49c1-b47d-974e53cbdf3c&redirect_uri=https%3a%2f%2fportal.azure.com%2fsignin%2findex%2f%3ffeature.refreshtokenbinding%3dtrue&site_id=501430&client-request-id=e8879e47-6308-450d-bda1-d2a015f81220&x-client-SKU=ID_NET&x-client-ver=1.0.40306.1554).
