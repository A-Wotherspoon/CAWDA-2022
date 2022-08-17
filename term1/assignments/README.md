# TIA1 - Adrian Wotherspoon

## Q1.

Markup languages can be defined as a notation method of how particular pieces of information are to be displayed and formatted. In the context of web development, markup languages refer to a language with a specific set of rules that govern the appearance of a document. This differs to programming languages as no logic or processing of data are performed.

HyperText Markup Language (HTML) is the most commonly used markup language on the Web, where its main feature is the use of tags and elements to define the structure and formatting of the web document's contents. These tags and elements are defined within opening "<" and closing ">" tags, where any text written within these characters are considered as part of the markup language instructing how the document should look, and not part of the displayed text.

A number of key elements are defined below, with HTML examples included:
<ul>
    <li>
        <b>Document type declaration</b>: Contained in the very first line of the document, this is an instruction to the document reader about what type of document to expect. In HTML documents, this is defined via the &lt!DOCTYPE html&gt declaration.
    </li>
    <li>
        <b>Root element</b>: A container element which acts as a parent for all other elements on the page of the document. In HTML documents, all other elements are contained within the &ltHTML&gt&lt/HTML&gt tags.
    </li>
    <li>
        <b>Head</b>: A section where metadata about the document is included, containing information such as title, other referenced sheets or assets, and information to aid reading compatibility. In HTML, this is enclosed within the &lthead&gt&lt/head&gt tags.
    </li>
    <li>
        <b>Body</b>: Where the main content of the document that is to be displayed is included, such as all text and images. In a HTML document, the content is contained within the &ltbody&gt&lt/body&gt tags.
    </li>
</ul>

## Q2.

<ul> 
    <li>
        <b>Packets</b>: A packet is the basic unit of information when data is transferred over a network. Large quantities of data are broken down into smaller pieces referred to as the payload, with additional information attached to form a full packet: the sender's IP address, the destination's IP address and a sequence value indicating how many packets the item includes, all of which form the packet header, and a checksum value (usually referred to as a cyclic redundancy check) forming the packet footer. Packets are an efficient way of transferring data over the internet due to the following features:
        <ul>
            <li>Packets can be transferred via the best available route/routes.</li> <li>Cyclic reduncancy checks allow for packets to be retransmitted if there is an error</li>
            <li>Improved security via encryption.</li>
            <li>Allows for multiple computers to share the same connection and transfer data simultaneously.</li>
        </ul>
        A typical packet size on the internet ranges from 1476-1500 bytes.         
    </li>
    <li>
        <b>IP addresses (IPv4 and IPv6)</b>: An Internet Protocol (IP) address is a unique identifier for any device that is connected to the internet or a local network. The "IP" part refers to the specific rules and formatting of the data for it to be transferred between two devices via the internet or a local network. IP addresses currently follow the two main versions:
        <ul>
            <li>IPv4: Uses a 32-bit address, providing 2<sup>32</sup> unique addresses. IPv4 is mostly commonly displayed as 4 sets of numbers, each ranging from 0-255, giving a full addressing range of 0.0.0.0 to 255.255.255.255.</li> 
            <li>IPv6: Uses a 128-bit address, theoretically allowing for 2<sup>128</sup> unique addresses. IPv6 was developed with the understanding that more devices want to connect to the internet than the available number of unique addresses available via IPv4. IPv6 address are represented as eight groups of four hexadecimals, e.g. 2022:ae7f:1123::7bc9, noting that the double colons represent "0" value segments that would fill the address to 8 segments. </li>
        </ul>
        By having a unique address and standardised protocol, IP addressing forms an essential part of how the internet works, allowing for devices to identify and connect directly to each other and share information.
    </li>
    <li>
        <b>Routers and routing</b>: Routing in a networking context refers to the process of selecting a path to allow a device to send a packet to a specified destination across one or more networks. The processing of routing decisions are made by specialised pieces of hardward called routers.<br/>
        A router is a device that connects two or more networks or subnetworks, and primarily serve two functions: managing the traffic between the two connected networks via forwarding their packets to the intended address, and by allowing multiple devices to utilise the same internet connection. The internet utilises routers to help direct packets that follow Internet Protocol to their destination IP address. It performs this by reading the packet's header, and utlises an internal routing table which lists paths to numerous network destination in order to map out the most efficient path to the destination IP address. 
    </li>
    <li>
        <b>Domains and DNS</b>: A unique IP address is given to each device connected to the internet, which can be a seemingly random 12 digit number (for IPv4) or 32 alphanumeric characters (for IPv6). In order to make it easier to look up network addresses, we can instead use domain names such as <u>www.google.com</u>. The Domain Name System (DNS) acts as a phonebook for the internet, which translates a web browser's input domain name into an IP address which network devices can then utilise. This is usually facilitated by a browser making a query to a system called a DNS resolver, where if the domain name has been cached, it can automatically answer the query. If not, the resolver will make additional sequential request to DNS root name server, Top Level Domain Name server, then Authoratative DNS server which finally holds the IP address information to satisfy the initial query.
    </li>

</ul>


## Q3.

<ul> 
    <li>
        <b>TCP</b>:
    </li>
    <li>
        <b>HTTP and HTTPS</b>:
    </li>
    <li>
        <b>Web browsers</b>:
    </li>

</ul>