Pixel-perfect   Retina-ready   Fast   Consistent   Hackable   No tracking

search / project URL

Love Shields? Please consider donating to sustain our activities
Build
Code Coverage
Test Results
Analysis
Chat
Dependencies
Size
Downloads
Funding
Issue Tracking
License
Rating
Social
Version
Platform & Version Support
Monitoring
Activity
Other
Your Badge
Static
label
message
color
Make Badge
Using dash "-" separator

https://img.shields.io/badge/<LABEL>-<MESSAGE>-<COLOR>

Dashes --	→	- Dash
Underscores __	→	_ Underscore
_ or Space  	→	  Space
Using query string parameters

https://img.shields.io/static/v1?label=<LABEL>&message=<MESSAGE>&color=<COLOR>

Colors
brightgreengreenyellowgreenyelloworangeredbluelightgrey
successimportantcriticalinformationalinactive
bluevioletff69b49cf

Endpoint
https://img.shields.io/endpoint?url=<URL>&style<STYLE>

Create badges from your own JSON endpoint.

Dynamic

data type
 
label
data url
query
color
prefix
suffix
Make Badge
https://img.shields.io/badge/dynamic/json?url=<URL>&label=<LABEL>&query=<$.DATA.SUBDATA>&color=<COLOR>&prefix=<PREFIX>&suffix=<SUFFIX>

https://img.shields.io/badge/dynamic/xml?url=<URL>&label=<LABEL>&query=<//data/subdata>&color=<COLOR>&prefix=<PREFIX>&suffix=<SUFFIX>

https://img.shields.io/badge/dynamic/yaml?url=<URL>&label=<LABEL>&query=<$.DATA.SUBDATA>&color=<COLOR>&prefix=<PREFIX>&suffix=<SUFFIX>

Styles
The following styles are available. Flat is the default. Examples are shown with an optional logo:

?style=plastic&logo=appveyor	plastic
?style=flat&logo=appveyor	flat
?style=flat-square&logo=appveyor	flat-square
?style=for-the-badge&logo=appveyor	for-the-badge
?style=social&logo=appveyor	social
Here are a few other parameters you can use: (connecting several with "&" is possible)

?label=healthinesses	Override the default left-hand-side text (URL-Encoding needed for spaces or special characters!)
?logo=appveyor	Insert one of the named logos from (bitcoin, dependabot, gitlab, npm, paypal, serverfault, stackexchange, superuser, telegram, travis) or simple-icons. Simple-icons are referenced using icon slugs which can be found on the simple-icons site or in the slugs.md file in the simple-icons repository.
?logo=data:image/png;base64,…	Insert custom logo image (≥ 14px high). There is a limit on the total size of request headers we can accept (8192 bytes). From a practical perspective, this means the base64-encoded image text is limited to somewhere slightly under 8192 bytes depending on the rest of the request header.
?logoColor=violet	Set the color of the logo (hex, rgb, rgba, hsl, hsla and css named colors supported). Supported for named logos but not for custom logos.
?logoWidth=40	Set the horizontal space to give to the logo
?link=http://left&link=http://right	Specify what clicking on the left/right of a badge should do. Note that this only works when integrating your badge in an<object> HTML tag, but not an<img> tag or a markup language.
?labelColor=abcdef	Set background of the left part (hex, rgb, rgba, hsl, hsla and css named colors supported). The legacy name "colorA" is also supported.
?color=fedcba	Set background of the right part (hex, rgb, rgba, hsl, hsla and css named colors supported). The legacy name "colorB" is also supported.
?cacheSeconds=3600	Set the HTTP cache lifetime (rules are applied to infer a default value on a per-badge basis, any values specified below the default will be ignored). The legacy name "maxAge" is also supported.
