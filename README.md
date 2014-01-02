#Update January 2nd, 2014
There has been a recent uptick in interest about Soapy, so I feel the need to clarify a few things.  The project is not under active development.  Feel free to fork and make something awesome! :D  All deployed extensions were disabled/deactivated at the end of 2012.  My current main projects are [Commotion](https://commotionwireless.net) and [Cupcake](http://cupcakebridge.com).

###While SOPA did not pass, similar legislation could pass!<br/>
####See <a href="http://eff.org">the EFF</a> or <a href="http://www.doyouhaveasecret.org/">Do You Have a Secret?</a> for more info

<p><b>Soapy is a small, free Fire Fox plugin that allows users to go to web sites banned under SOPA -- making SOPA, if it is passed, moot.</b> It focuses on the DNS-blocking technique favored by oppressive regimes and middle management. Because this is designed to go around a complete block, <i>HTTPS is disabled for sites covered by this plugin.</i></p>

<p>There's a bit of a lag time between coding and releasing source on git, just so you know.  Every site that this circumvents for has a set of XML rules that are tailored to the quirks of that specific site.  These are found in <code>rules</code> and <code>src/chrome/content/rules</code>.  Much of the code has been borrowed from HTTPS-Everywhere and NoScript.</p>

<p>To compile this into a plugin, compress everything in <code>/src</code> into a zip file <code>soapy.zip</code>, then change the extension to <code>.xpi</code>.  So once packed, the plugin should be called <code>soapy.xpi</code>. </p>

<p>Let me know what you think, either by email at griffinboyce@gmail.com, or on Twitter at @abditum. ~Griffin Boyce</p>

<center><h2>What is Soapy, exactly?</h2></center>

<h3>In a technical nutshell:</h3>
<p>Soapy works by automatically redirecting users to the website's server
directly. It replaces the DNS system entirely for these blocked
websites.</p>

<p>Domain Name Servers match domains like Google.com to their server's IP
address (in this case http://74.125.224.72/ ). This process is usually
invisible to the user, but you can access Google's site by using their
IP address as well.</p>

<h3>More basic, less technical:</h3>
<p>Computers use Domain Name Servers to make the connection to websites.
These large servers act as online address books for websites, telling
computers where the site they want to visit is located. Soapy acts as an
alternative address book for sites that are at risk of being blocked.</p>

<h3>More technical info:</h3>
<p>Soapy is a plugin for FireFox written in JavaScript and XML that is
designed to bypass DNS blocks by automatically redirecting the user to
the site's IP address (if available). This is based on pre-defined rules
for websites which may be at risk of being blocked. So while this means
that sites must be included in the plugin package, it also means that
they've been tested and aren't simply assumed to work.</p>

<p>Version: 0.05; MD5: <code>b2ec7aaae1cc7b4810355fd0374868e1</code></p>

<h2>How to install:</h2>
<p>Step one: Download it here, and save it to your hard drive.</p>
<p>Step two: Drag and drop the file onto your FireFox window.</p>
<p>Step three: Restart Firefox.</p>

<h2>How to remove:</h2>
<p><i>Since SOPA isn't in effect, you should disable the plugin or uninstall completely.  Soapy updates its definitions automatically.</i></p>
<p>To remove, go to <i>Tools > Addons</i>, click Soapy, then click Uninstall. Firefox will ask you to restart your browser.</p>

All code is open source under GPL v2. Though if you're charging for this, I could use a job (just saying).</p>



<p><i><small>Like crispy bacon, I crave censorship circumvention.</small></i></p>
