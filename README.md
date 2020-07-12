
<header>

# Shodan AIO Reference

</header>

This is a work in progress please feel free to add new search filters and interesting search querries using pull requests.

Search keywords should be enclosed within "" to avoid false positives. 
A + or - sign could be appended infront of the keywork to include or exclude results, very useful! 

example: +"webcam" -"login" 

This will give results which are related to webcam that do not have "login" in them.



#### Physical Location

<table class="collection-content">

<thead>

<tr>

<th><span class="icon property-icon"></span>Filter</th>

<th><span class="icon property-icon"></span>Description</th>

<th><span class="icon property-icon"></span>Usage</th>

</tr>

</thead>

<tbody>

<tr id="cf443e1f-9068-470d-811d-3d203b115abf">

<td class="cell-title">[country]</td>

<td class="cell-&amp;g~[">Search by country code</td>

<td class="cell-YvA?">country:”IN”</td>

</tr>

<tr id="86897907-8fdd-4e9f-a565-60ee69ecc863">

<td class="cell-title">[city]</td>

<td class="cell-&amp;g~[">Search by city name</td>

<td class="cell-YvA?">city:"Bengaluru"</td>

</tr>

<tr id="3a595eef-6799-42ea-857b-176966a7b69c">

<td class="cell-title">[state]</td>

<td class="cell-&amp;g~[">Search by state code (US only)</td>

<td class="cell-YvA?">state:"NY"</td>

</tr>

<tr id="e867be6f-001c-48ce-b9b3-c5cc84d789c5">

<td class="cell-title">[region]</td>

<td class="cell-&amp;g~[">Same as state filter</td>

<td class="cell-YvA?">region:"NY"</td>

</tr>

<tr id="6d22ecbc-7e3d-41f4-b9ea-f00023fb2bcb">

<td class="cell-title">[postal]</td>

<td class="cell-&amp;g~[">Search by zip code</td>

<td class="cell-YvA?">postal:"92127"</td>

</tr>

<tr id="452292a2-6ea7-43bf-9f8a-c3ea140d03d5">

<td class="cell-title">[geo]</td>

<td class="cell-&amp;g~[">Search by GPS cordinates</td>

<td class="cell-YvA?">geo:”40.759487,-73.978356"</td>

</tr>

<tr id="398cfd3d-27ac-4fd1-a1c7-800d3cfd6588">

<td class="cell-title">[geo]</td>

<td class="cell-&amp;g~[">Search by GPS cordinates within a specific radius</td>

<td class="cell-YvA?">geo:”40.759487,-73.978356,2"</td>

</tr>

<tr id="5ce78154-1a8f-4e3f-b851-4a4c49482b5e">

<td class="cell-title">[org]</td>

<td class="cell-&amp;g~[">Search by Organization/Company</td>

<td class="cell-YvA?">org:"Microsoft"</td>

</tr>

</tbody>

</table>

</div>

<div id="177d96b0-0199-4c16-895f-bc8f6a9f664d" class="collection-content">



#### IP Addresses & Subnets

<table class="collection-content">

<thead>

<tr>

<th><span class="icon property-icon"></span>Filter</th>

<th><span class="icon property-icon"></span>Description</th>

<th><span class="icon property-icon"></span>Usage</th>

</tr>

</thead>

<tbody>

<tr id="6d71cc9c-4211-4778-86cd-a3c0c90161aa">

<td class="cell-title">[Untitled]</td>

<td class="cell-&amp;g~[">Search findings on a single ip</td>

<td class="cell-YvA?">52.179.197.205</td>

</tr>

<tr id="4ac4a8e2-6307-4900-83e3-dcc5aa22c2fc">

<td class="cell-title">[hostname]</td>

<td class="cell-&amp;g~[">Search for string in any hostname</td>

<td class="cell-YvA?">hostname:"microsoft.com"</td>

</tr>

<tr id="29a43374-a83e-429f-9f64-4487aba1eb3d">

<td class="cell-title">[net]</td>

<td class="cell-&amp;g~[">Search across a specfic subnet range</td>

<td class="cell-YvA?">net:"52.179.197.0/24"</td>

</tr>

<tr id="b324cca3-6200-484e-baa3-b2b649521e54">

<td class="cell-title">[port]</td>

<td class="cell-&amp;g~[">Find instances where a specific port is open</td>

<td class="cell-YvA?">port:"445"</td>

</tr>

<tr id="e1eec811-f1d8-4c72-9979-b778aa5611cc">

<td class="cell-title">[isp]</td>

<td class="cell-&amp;g~[">Search by ISP Name</td>

<td class="cell-YvA?">isp:"BSNL"</td>

</tr>

<tr id="ad80aced-539f-4cef-b043-54cff0ab4cfc">

<td class="cell-title">[ASN]</td>

<td class="cell-&amp;g~[">Search by Autonomous System Number (ASN)</td>

<td class="cell-YvA?">ASN:"AS8075"</td>

</tr>

<tr id="f7ff97fc-36ba-4b47-8b6a-9378f4987474">

<td class="cell-title">[org]</td>

<td class="cell-&amp;g~[">Search by Organization/Company</td>

<td class="cell-YvA?">org:"Microsoft"</td>

</tr>

</tbody>

</table>

</div>

<div id="8628e19e-4ef9-4eb7-9a51-290b5266a91e" class="collection-content">



#### Products & Operating Systems

<table class="collection-content">

<thead>

<tr>

<th><span class="icon property-icon"></span>Filter</th>

<th><span class="icon property-icon"></span>Description</th>

<th><span class="icon property-icon"></span>Usage</th>

</tr>

</thead>

<tbody>

<tr id="2d21704c-4e69-4204-8c0a-dbd31c3f3aab">

<td class="cell-title">[os]</td>

<td class="cell-&amp;g~[">Search by operating system type</td>

<td class="cell-YvA?">os:"Windows Server 2008"</td>

</tr>

<tr id="06e87881-3dc6-4089-8f09-cac74fbab6b9">

<td class="cell-title">[org]</td>

<td class="cell-&amp;g~[">Search by Organization/Company</td>

<td class="cell-YvA?">org:"Xiaomi"</td>

</tr>

<tr id="0be51b31-b0d0-44af-9dd6-567f8e9f1137">

<td class="cell-title">[product]</td>

<td class="cell-&amp;g~[">Search by known product name</td>

<td class="cell-YvA?">product:"Cisco C3550 Router"</td>

</tr>

<tr id="37abd8bd-8119-4b2a-b2bf-fc4b5b1ba38d">

<td class="cell-title">[version]</td>

<td class="cell-&amp;g~[">Can be used in conjunction with product to get specific versions</td>

<td class="cell-YvA?">product:"nginx" version:"1.8.1"</td>

</tr>

<tr id="5af7de99-980f-4aca-a77f-f325b2799f3c">

<td class="cell-title">[category]</td>

<td class="cell-&amp;g~[">Search by Shodan category</td>

<td class="cell-YvA?">category:"ics"</td>

</tr>

<tr id="11286b25-8ef9-4f15-937a-d07a6a2b8eb4">

<td class="cell-title">[smb]</td>

<td class="cell-&amp;g~[">Search for specific SMB server</td>

<td class="cell-YvA?">smb:"2"</td>

</tr>

</tbody>

</table>

</div>

<div id="e28868f9-1851-4564-94da-0f15163aaf02" class="collection-content">



#### Web Applications

<table class="collection-content">

<thead>

<tr>

<th><span class="icon property-icon"></span>Filter</th>

<th><span class="icon property-icon"></span>Description</th>

<th><span class="icon property-icon"></span>Usage</th>

</tr>

</thead>

<tbody>

<tr id="d57a8cb0-24c9-4025-a1da-a8d8b05d4fac">

<td class="cell-title">[title]</td>

<td class="cell-&amp;g~[">Search for text in page title</td>

<td class="cell-YvA?">title:"Index of /ftp"</td>

</tr>

<tr id="5893b56b-9ba9-4450-995a-27c276590534">

<td class="cell-title">[html]</td>

<td class="cell-&amp;g~[">Search for a strings in webpage's body</td>

<td class="cell-YvA?">html:"XML-RPC server accepts"</td>

</tr>

<tr id="f2637fd1-6b63-40d3-8948-388028b40e9e">

<td class="cell-title">[http.component]</td>

<td class="cell-&amp;g~[">Search for a specfic web technology</td>

<td class="cell-YvA?">http.component:”php”</td>

</tr>

<tr id="f8d5c46b-6445-4687-9bca-97608a05ffcc">

<td class="cell-title">[ssl.version]</td>

<td class="cell-&amp;g~[">Search for SSL/TLS versions supported</td>

<td class="cell-YvA?">ssl.version:"tlsv1.1"</td>

</tr>

<tr id="bca91ede-16a0-4451-89f3-12c6dce73450">

<td class="cell-title">[ssl.cert.expired]</td>

<td class="cell-&amp;g~[">Search for expired HTTPS certs</td>

<td class="cell-YvA?">ssl.cert.expired:”true”</td>

</tr>

</tbody>

</table>

</div>

<div id="1f82bb7f-5df5-4cb7-9f64-0e3dbd77076d" class="collection-content">



#### Other

<table class="collection-content">

<thead>

<tr>

<th><span class="icon property-icon"></span>Filter</th>

<th><span class="icon property-icon"></span>Description</th>

<th><span class="icon property-icon"></span>Usage</th>

</tr>

</thead>

<tbody>

<tr id="b6a7ec36-55de-4d62-a412-8a2488a95b10">

<td class="cell-title">[after]</td>

<td class="cell-&amp;g~[">Search for findings that appeared after a specific date</td>

<td class="cell-YvA?">after:"01/01/19"</td>

</tr>

<tr id="30a42261-53d9-42c4-ad5c-14b0c5592f3d">

<td class="cell-title">[before]</td>

<td class="cell-&amp;g~[">Search for findings that appeared after a specific date</td>

<td class="cell-YvA?">before:"01/01/19"</td>

</tr>

<tr id="7b87203b-1c88-44a7-928d-202525ee5dd4">

<td class="cell-title">[has_screenshot]</td>

<td class="cell-&amp;g~[">Search for results which have a screenshot</td>

<td class="cell-YvA?">has_screenshot:"true"</td>

</tr>

<tr id="9f0c3238-fde9-4c46-90c2-ecf8c69bed80">

<td class="cell-title">[vuln]</td>

<td class="cell-&amp;g~[">Search posible vulnerable devices by CVE ID</td>

<td class="cell-YvA?">vuln:"CVE-2017-0143"</td>

</tr>

<tr id="a0933cf0-6289-4cd5-a75c-1c9ef37dee62">

<td class="cell-title">[tag]</td>

<td class="cell-&amp;g~[">search based on shodan tagged data</td>

<td class="cell-YvA?">tag:"honeypot"</td>

</tr>

</tbody>

</table>

</div>



### Interesting Search Queries

*   To be updated.

</div>




<sup>Reference: [Shodan QuickStart v1](https://www.uk-osint.net/documents/Shodan_QuickStart_v1.pdf). </sup>

</article>
