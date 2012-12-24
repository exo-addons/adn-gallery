ADN:Gallery
==
Description
--
_adn:gallery_ is a specific nodetype which display a set of photos on an animated photogallery view.

How to install
--
* Import the nodetype `nodetypes-adn-gallery-configuration.xml`.
* Add the namespace configuration 'ADN' for Addon `system-configuration.xml`
* Add the dialog and the view templates for this nodetype: `dialog.gtmpl` & `view.gtmpl`
* Put these files `jquery.min.js` & `jquery.adn-gallery.js` in any WAR file under your application server and update their location sources in the view template:


        <script 
          type="text/javascript"
          src="{/your-location}/jquery.min.js">
        </script>
		
        <script 
          type="text/javascript"
          src="{/your-location}/jquery.adn-gallery.js">
        </script>

* Go to the File Explorer and add a new content, select `Gallery` then upload your photos, thus you get your photogallery. 
