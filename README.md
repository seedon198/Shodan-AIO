Shodan AIO Reference  /\* webkit printing magic: print all background colors \*/ html { -webkit-print-color-adjust: exact; } \* { box-sizing: border-box; -webkit-print-color-adjust: exact; } html, body { margin: 0; padding: 0; } @media only screen { body { margin: 2em auto; max-width: 900px; color: rgb(55, 53, 47); } } body { line-height: 1.5; white-space: pre-wrap; } a, a.visited { color: inherit; text-decoration: underline; } .pdf-relative-link-path { font-size: 80%; color: #444; } h1, h2, h3 { letter-spacing: -0.01em; line-height: 1.2; font-weight: 600; margin-bottom: 0; } .page-title { font-size: 2.5rem; font-weight: 700; margin-top: 0; margin-bottom: 0.75em; } h1 { font-size: 1.875rem; margin-top: 1.875rem; } h2 { font-size: 1.5rem; margin-top: 1.5rem; } h3 { font-size: 1.25rem; margin-top: 1.25rem; } .source { border: 1px solid #ddd; border-radius: 3px; padding: 1.5em; word-break: break-all; } .callout { border-radius: 3px; padding: 1rem; } figure { margin: 1.25em 0; page-break-inside: avoid; } figcaption { opacity: 0.5; font-size: 85%; margin-top: 0.5em; } mark { background-color: transparent; } .indented { padding-left: 1.5em; } hr { background: transparent; display: block; width: 100%; height: 1px; visibility: visible; border: none; border-bottom: 1px solid rgba(55, 53, 47, 0.09); } img { max-width: 100%; } @media only print { img { max-height: 100vh; object-fit: contain; } } @page { margin: 1in; } .collection-content { font-size: 0.875rem; } .column-list { display: flex; justify-content: space-between; } .column { padding: 0 1em; } .column:first-child { padding-left: 0; } .column:last-child { padding-right: 0; } .table\_of\_contents-item { display: block; font-size: 0.875rem; line-height: 1.3; padding: 0.125rem; } .table\_of\_contents-indent-1 { margin-left: 1.5rem; } .table\_of\_contents-indent-2 { margin-left: 3rem; } .table\_of\_contents-indent-3 { margin-left: 4.5rem; } .table\_of\_contents-link { text-decoration: none; opacity: 0.7; border-bottom: 1px solid rgba(55, 53, 47, 0.18); } table, th, td { border: 1px solid rgba(55, 53, 47, 0.09); border-collapse: collapse; } table { border-left: none; border-right: none; } th, td { font-weight: normal; padding: 0.25em 0.5em; line-height: 1.5; min-height: 1.5em; text-align: left; } th { color: rgba(55, 53, 47, 0.6); } ol, ul { margin: 0; margin-block-start: 0.6em; margin-block-end: 0.6em; } li > ol:first-child, li > ul:first-child { margin-block-start: 0.6em; } ul > li { list-style: disc; } ul.to-do-list { text-indent: -1.7em; } ul.to-do-list > li { list-style: none; } .to-do-children-checked { text-decoration: line-through; opacity: 0.375; } ul.toggle > li { list-style: none; } ul { padding-inline-start: 1.7em; } ul > li { padding-left: 0.1em; } ol { padding-inline-start: 1.6em; } ol > li { padding-left: 0.2em; } .mono ol { padding-inline-start: 2em; } .mono ol > li { text-indent: -0.4em; } .toggle { padding-inline-start: 0em; list-style-type: none; } /\* Indent toggle children \*/ .toggle > li > details { padding-left: 1.7em; } .toggle > li > details > summary { margin-left: -1.1em; } .selected-value { display: inline-block; padding: 0 0.5em; background: rgba(206, 205, 202, 0.5); border-radius: 3px; margin-right: 0.5em; margin-top: 0.3em; margin-bottom: 0.3em; white-space: nowrap; } .collection-title { display: inline-block; margin-right: 1em; } time { opacity: 0.5; } .icon { display: inline-block; max-width: 1.2em; max-height: 1.2em; text-decoration: none; vertical-align: text-bottom; margin-right: 0.5em; } img.icon { border-radius: 3px; } .user-icon { width: 1.5em; height: 1.5em; border-radius: 100%; margin-right: 0.5rem; } .user-icon-inner { font-size: 0.8em; } .text-icon { border: 1px solid #000; text-align: center; } .page-cover-image { display: block; object-fit: cover; width: 100%; height: 30vh; } .page-header-icon { font-size: 3rem; margin-bottom: 1rem; } .page-header-icon-with-cover { margin-top: -0.72em; margin-left: 0.07em; } .page-header-icon img { border-radius: 3px; } .link-to-page { margin: 1em 0; padding: 0; border: none; font-weight: 500; } p > .user { opacity: 0.5; } td > .user, td > time { white-space: nowrap; } input\[type="checkbox"\] { transform: scale(1.5); margin-right: 0.6em; vertical-align: middle; } p { margin-top: 0.5em; margin-bottom: 0.5em; } .image { border: none; margin: 1.5em 0; padding: 0; border-radius: 0; text-align: center; } .code, code { background: rgba(135, 131, 120, 0.15); border-radius: 3px; padding: 0.2em 0.4em; border-radius: 3px; font-size: 85%; tab-size: 2; } code { color: #eb5757; } .code { padding: 1.5em 1em; } .code > code { background: none; padding: 0; font-size: 100%; color: inherit; } blockquote { font-size: 1.25em; margin: 1em 0; padding-left: 1em; border-left: 3px solid rgb(55, 53, 47); } .bookmark { text-decoration: none; max-height: 8em; padding: 0; display: flex; width: 100%; align-items: stretch; } .bookmark-title { font-size: 0.85em; overflow: hidden; text-overflow: ellipsis; height: 1.75em; white-space: nowrap; } .bookmark-text { display: flex; flex-direction: column; } .bookmark-info { flex: 4 1 180px; padding: 12px 14px 14px; display: flex; flex-direction: column; justify-content: space-between; } .bookmark-image { width: 33%; flex: 1 1 180px; display: block; position: relative; object-fit: cover; border-radius: 1px; } .bookmark-description { color: rgba(55, 53, 47, 0.6); font-size: 0.75em; overflow: hidden; max-height: 4.5em; word-break: break-word; } .bookmark-href { font-size: 0.75em; margin-top: 0.25em; } .sans { font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol"; } .code { font-family: "SFMono-Regular", Consolas, "Liberation Mono", Menlo, Courier, monospace; } .serif { font-family: Lyon-Text, Georgia, YuMincho, "Yu Mincho", "Hiragino Mincho ProN", "Hiragino Mincho Pro", "Songti TC", "Songti SC", "SimSun", "Nanum Myeongjo", NanumMyeongjo, Batang, serif; } .mono { font-family: iawriter-mono, Nitti, Menlo, Courier, monospace; } .pdf .sans { font-family: Inter, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK SC', 'Noto Sans CJK KR'; } .pdf .code { font-family: Source Code Pro, "SFMono-Regular", Consolas, "Liberation Mono", Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK SC', 'Noto Sans Mono CJK KR'; } .pdf .serif { font-family: PT Serif, Lyon-Text, Georgia, YuMincho, "Yu Mincho", "Hiragino Mincho ProN", "Hiragino Mincho Pro", "Songti TC", "Songti SC", "SimSun", "Nanum Myeongjo", NanumMyeongjo, Batang, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK SC', 'Noto Sans CJK KR'; } .pdf .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK SC', 'Noto Sans Mono CJK KR'; } .highlight-default { } .highlight-gray { color: rgb(155,154,151); } .highlight-brown { color: rgb(100,71,58); } .highlight-orange { color: rgb(217,115,13); } .highlight-yellow { color: rgb(223,171,1); } .highlight-teal { color: rgb(15,123,108); } .highlight-blue { color: rgb(11,110,153); } .highlight-purple { color: rgb(105,64,165); } .highlight-pink { color: rgb(173,26,114); } .highlight-red { color: rgb(224,62,62); } .highlight-gray\_background { background: rgb(235,236,237); } .highlight-brown\_background { background: rgb(233,229,227); } .highlight-orange\_background { background: rgb(250,235,221); } .highlight-yellow\_background { background: rgb(251,243,219); } .highlight-teal\_background { background: rgb(221,237,234); } .highlight-blue\_background { background: rgb(221,235,241); } .highlight-purple\_background { background: rgb(234,228,242); } .highlight-pink\_background { background: rgb(244,223,235); } .highlight-red\_background { background: rgb(251,228,228); } .block-color-default { color: inherit; fill: inherit; } .block-color-gray { color: rgba(55, 53, 47, 0.6); fill: rgba(55, 53, 47, 0.6); } .block-color-brown { color: rgb(100,71,58); fill: rgb(100,71,58); } .block-color-orange { color: rgb(217,115,13); fill: rgb(217,115,13); } .block-color-yellow { color: rgb(223,171,1); fill: rgb(223,171,1); } .block-color-teal { color: rgb(15,123,108); fill: rgb(15,123,108); } .block-color-blue { color: rgb(11,110,153); fill: rgb(11,110,153); } .block-color-purple { color: rgb(105,64,165); fill: rgb(105,64,165); } .block-color-pink { color: rgb(173,26,114); fill: rgb(173,26,114); } .block-color-red { color: rgb(224,62,62); fill: rgb(224,62,62); } .block-color-gray\_background { background: rgb(235,236,237); } .block-color-brown\_background { background: rgb(233,229,227); } .block-color-orange\_background { background: rgb(250,235,221); } .block-color-yellow\_background { background: rgb(251,243,219); } .block-color-teal\_background { background: rgb(221,237,234); } .block-color-blue\_background { background: rgb(221,235,241); } .block-color-purple\_background { background: rgb(234,228,242); } .block-color-pink\_background { background: rgb(244,223,235); } .block-color-red\_background { background: rgb(251,228,228); } .select-value-color-default { background-color: rgba(206,205,202,0.5); } .select-value-color-gray { background-color: rgba(155,154,151, 0.4); } .select-value-color-brown { background-color: rgba(140,46,0,0.2); } .select-value-color-orange { background-color: rgba(245,93,0,0.2); } .select-value-color-yellow { background-color: rgba(233,168,0,0.2); } .select-value-color-green { background-color: rgba(0,135,107,0.2); } .select-value-color-blue { background-color: rgba(0,120,223,0.2); } .select-value-color-purple { background-color: rgba(103,36,222,0.2); } .select-value-color-pink { background-color: rgba(221,0,129,0.2); } .select-value-color-red { background-color: rgba(255,0,26,0.2); } .checkbox { display: inline-flex; vertical-align: text-bottom; width: 16; height: 16; background-size: 16px; margin-left: 2px; margin-right: 5px; } .checkbox-on { background-image: url("data:image/svg+xml;charset=UTF-8,%3Csvg%20width%3D%2216%22%20height%3D%2216%22%20viewBox%3D%220%200%2016%2016%22%20fill%3D%22none%22%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%3E%0A%3Crect%20width%3D%2216%22%20height%3D%2216%22%20fill%3D%22%2358A9D7%22%2F%3E%0A%3Cpath%20d%3D%22M6.71429%2012.2852L14%204.9995L12.7143%203.71436L6.71429%209.71378L3.28571%206.2831L2%207.57092L6.71429%2012.2852Z%22%20fill%3D%22white%22%2F%3E%0A%3C%2Fsvg%3E"); } .checkbox-off { background-image: url("data:image/svg+xml;charset=UTF-8,%3Csvg%20width%3D%2216%22%20height%3D%2216%22%20viewBox%3D%220%200%2016%2016%22%20fill%3D%22none%22%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%3E%0A%3Crect%20x%3D%220.75%22%20y%3D%220.75%22%20width%3D%2214.5%22%20height%3D%2214.5%22%20fill%3D%22white%22%20stroke%3D%22%2336352F%22%20stroke-width%3D%221.5%22%2F%3E%0A%3C%2Fsvg%3E"); }

Shodan AIO Reference
====================

This is a work in progress please feel free to add new search filters and interesting search querries using pull requests.

Search keywords should be enclosed within "" to avoid false positives. A + or - sign could be appended infront of the keywork to include or exclude results, very useful! example: +"webcam" -"login" This will give results which are related to webcam that do not have "login" in them.

#### Physical Location

Filter

Description

Usage

[country](https://www.notion.so/country-cf443e1f9068470d811d3d203b115abf)

Search by country code

country:”IN”

[city](https://www.notion.so/city-868979078fdd4e9fa56560ee69ecc863)

Search by city name

city:"Bengaluru"

[state](https://www.notion.so/state-3a595eef679942ea857b176966a7b69c)

Search by state code (US only)

state:"NY"

[region](https://www.notion.so/region-e867be6f001c48ceb9b3c5cc84d789c5)

Same as state filter

region:"NY"

[postal](https://www.notion.so/postal-6d22ecbc7e3d41f4b9eaf00023fb2bcb)

Search by zip code

postal:"92127"

[geo](https://www.notion.so/geo-452292a26ea743bf9f8ac3ea140d03d5)

Search by GPS cordinates

geo:”40.759487,-73.978356"

[geo](https://www.notion.so/geo-398cfd3d27ac4fd1a1c7800d3cfd6588)

Search by GPS cordinates within a specific radius

geo:”40.759487,-73.978356,2"

[org](https://www.notion.so/org-5ce781541a8f4e3fb8514a4c49482b5e)

Search by Organization/Company

org:"Microsoft"

#### IP Addresses & Subnets

Filter

Description

Usage

[Untitled](https://www.notion.so/6d71cc9c4211477886cda3c0c90161aa)

Search findings on a single ip

52.179.197.205

[hostname](https://www.notion.so/hostname-4ac4a8e26307490083e3dcc5aa22c2fc)

Search for string in any hostname

hostname:"microsoft.com"

[net](https://www.notion.so/net-29a43374a83e429f9f644487aba1eb3d)

Search across a specfic subnet range

net:"52.179.197.0/24"

[port](https://www.notion.so/port-b324cca36200484ebaa3b2b649521e54)

Find instances where a specific port is open

port:"445"

[isp](https://www.notion.so/isp-e1eec811f1d84c729979b778aa5611cc)

Search by ISP Name

isp:"BSNL"

[ASN](https://www.notion.so/ASN-ad80aced539f4cefb04354cff0ab4cfc)

Search by Autonomous System Number (ASN)

ASN:"AS8075"

[org](https://www.notion.so/org-f7ff97fc36ba4b478b6a9378f4987474)

Search by Organization/Company

org:"Microsoft"

#### Products & Operating Systems

Filter

Description

Usage

[os](https://www.notion.so/os-2d21704c4e6942048c0adbd31c3f3aab)

Search by operating system type

os:"Windows Server 2008"

[org](https://www.notion.so/org-06e878813dc640898f09cac74fbab6b9)

Search by Organization/Company

org:"Xiaomi"

[product](https://www.notion.so/product-0be51b31b0d044af9dd6567f8e9f1137)

Search by known product name

product:"Cisco C3550 Router"

[version](https://www.notion.so/version-37abd8bd81194b2ab2bffc4b5b1ba38d)

Can be used in conjunction with product to get specific versions

product:"nginx" version:"1.8.1"

[category](https://www.notion.so/category-5af7de99980f4acaa77ff325b2799f3c)

Search by Shodan category

category:"ics"

[smb](https://www.notion.so/smb-11286b258ef94f15937ad07a6a2b8eb4)

Search for specific SMB server

smb:"2"

#### Web Applications

Filter

Description

Usage

[title](https://www.notion.so/title-d57a8cb024c94025a1daa8d8b05d4fac)

Search for text in page title

title:"Index of /ftp"

[html](https://www.notion.so/html-5893b56b9ba94450995a27c276590534)

Search for a strings in webpage's body

html:"XML-RPC server accepts"

[http.component](https://www.notion.so/http-component-f2637fd16b6340d38948388028b40e9e)

Search for a specfic web technology

http.component:”php”

[ssl.version](https://www.notion.so/ssl-version-f8d5c46b644546879bca97608a05ffcc)

Search for SSL/TLS versions supported

ssl.version:"tlsv1.1"

[ssl.cert.expired](https://www.notion.so/ssl-cert-expired-bca91ede16a0445189f312c6dce73450)

Search for expired HTTPS certs

ssl.cert.expired:”true”

#### Other

Filter

Description

Usage

[after](https://www.notion.so/after-b6a7ec3655de4d62a4128a2488a95b10)

Search for findings that appeared after a specific date

after:"01/01/19"

[before](https://www.notion.so/before-30a4226153d942c4ad5c14b0c5592f3d)

Search for findings that appeared after a specific date

before:"01/01/19"

[has\_screenshot](https://www.notion.so/has_screenshot-7b87203b1c8844a7928d202525ee5dd4)

Search for results which have a screenshot

has\_screenshot:"true"

[vuln](https://www.notion.so/vuln-9f0c3238fde94c4690c2ecf8c69bed80)

Search posible vulnerable devices by CVE ID

vuln:"CVE-2017-0143"

[tag](https://www.notion.so/tag-a0933cf062894cd5a75c1c9ef37dee62)

search based on shodan tagged data

tag:"honeypot"

### Interesting Search Queries

*   To be updated.
