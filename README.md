<h2>About the Facebook Album Fetcher Module</h2>
This is a Drupal7 module which allows you to fetch your facebook albums and photo galleries from your Facebook Account.To get started, you must first connect with your Facebook account. Once connected, you can create a gallery by making a new Drupal Post or Page and pasting in one line of special HTML, like this:
<pre>
[facebookAlbumFetcher album_id=ALBUM_ID]
</pre>
Whenever you save a post or page containing these tokens, this plugin will automatically download the album information and insert its contents between them. You are free to include any normal content you like before or after, as usual.The example number above (2032831634182) is an ID that tells the module which Facebook album you had like to import. To find a list of available albums, you can use the "Facebook Album List" tab.

This is the drupal full project. You can also download it from drupal site. 
<a href="https://www.drupal.org/project/facebook_album_fetcher" target="_blank">Facebook Album Fetcher</a>

<h2>Installation Steps:</h2>
<ul>
<li> <strong>Step 1 :</strong> Download and unpack the facebook_album_fetcher module in "sites/all/modules".</li>
<li> <strong>Step 2 :</strong> Go to "Administer" -> "Modules" and enable the module.</li>
<li> <strong>Step 3 :</strong> Connect your facebook account to with Facebook Album Fetcher.</li>
<li> <strong>Step 4 :</strong> After getting the proper Access Token Save it.</li>
<li> <strong>Step 5 :</strong> Now check other tabs that it is working proper.</li>
<li> <strong>Step 6 :</strong> Enable the "Facebook Album Fetcher" Filter:</li>
<ul>
<li> <strong>Step 6.1 :</strong> Open the "Text Formats" from "admin/config"</li>
<li> <strong>Step 6.2 :</strong> Click on the "Configure" Operation of Full HTML</li>
<li> <strong>Step 6.3 :</strong> Select the "Facebook Album Fetcher" option of Enabled filters Section.</li>
<li> <strong>Step 6.4 :</strong> Position "Facebook Album Fetcher" on the Top by setting the order inside the "Filter processing order".</li>
<li> <strong>Step 6.5 :</strong> Now Save the Configurtaion.</li>
</ul>
<li> <strong>Step 7 :</strong> To fetch the album from your account. Click on the "Facebook Album List" Tab</li>
<li> <strong>Step 8 :</strong> Now Copy the "FACEBOOK ALBUM FETCHER CODE" in your post or page.</li>
<li> <strong>Step 9 :</strong> Before saving, Select the Text Format Full HTML.</li>
<li> <strong>Step 10 :</strong> Save your page.</li>
</ul>

<h2>Facebook Album Fetcher Administration</h2>
<ul>
<li><strong>Facebook Login :</strong> Provide you an interface to connect your facebook account and register with Facebook Album Fetcher App.</li>
<li><strong>Facebook Album List :</strong> It will import all of your facebook album.</li>
<li><strong>Personal Details :</strong> Your facebook personal details will be shown here.</li>
<li><strong>Facebook Friends :</strong> It imports all of your facebook friends list and you can access there public albums and can integrate with your drupal content.</li>
<li><strong>Setting :</strong> This form provides you the various setting of the facebook album fetcher.</li>
</ul>

<h2>Lightbox Image Popup Integration:</h2>

Install the Lightbox Module to open the image into lightbox. To enable the lightbox module for Facebook Photo Fetcher. Go on the Settings tab and enable the lightbox "Embed Lightbox For Opening Image" option.

