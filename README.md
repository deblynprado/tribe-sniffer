# Tribe Sniffer
Author: Andras Guseo  
Release date: April 26, 2020

## Description
This is a tool created for the Support Team at Modern Tribe | The Events Calendar.

## What does it do?
The sniffer will check the following attributes on the page:

### Page attributes
* Is it Single Event view?
* Which editor was used? Classic or Block?
* Is this a default calendar page or was it generated by a shortcode?
  * Built-in shortcode
  * The Events Calendar Shortcode & Block
  * The Events Calendar Shortcode and Templates Addon
  
 ### Environment
 * Theme used 
 * WordPress version
 * TEC version
 * ECP version
 * Filter Bar version
 * ET version
 * ET+ version
 * WooCommerce version
 
 ### Is a caching plugin in use?
 The sniffer checks for the presence of the following caching plugins:
* Autoptimize
* WP-Super-Cache
* WP Fastest Cache
* W3 Total Cache
* Hummingbird
* WP Rocket

## How to use it
This tool is meant to be used as a bookmarklet.

### Quick deploy

1. Copy the one-line script from `tribe-sniffer.min.js` to your clipboard.
2. In your preferred browser create a new bookmark button on the bookmark bar.
3. Name it "Tribe Sniffer" or whatever you like.
4. Paste the code into the location / URL field and save it.
5. When visiting a webpage click on the bookmark button. A popup dialog will contain the information.

### Slow deploy

For that you will need to minimize the script. You can use an online tool like https://javascript-minifier.com/

Here are the steps to create a bookmarklet from the code:

1. Take the code without the header (starting with `(function`) and run it through the minifier.
2. Change the beginning from `!function()` to `javascript:(function()`. (Delete `!` and add `javacript:(`.)
3. Change the end from `}();` to `})();`. (Add a closing parentheses `)` after the curly bracket `}`.)
4. Select the minified code and copy it on your clipboard.
5. In your preferred browser create a new bookmark button on the bookmark bar.
6. Name it "Tribe Sniffer" or whatever you like.
7. Paste the code into the location / URL field and save it.
8. When visiting a webpage click on the bookmark button. A popup dialog will contain the information.

## Sample screenshot

This is what you will approximately get when clicking the button.
 
![image](https://user-images.githubusercontent.com/2614506/80293451-c7af0380-875f-11ea-9a86-270b167ea58e.png)