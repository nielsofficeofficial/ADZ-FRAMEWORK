<h2> ADZ-FRAMEWORK (Accelerate Development Zone) - A WordPress Framework Cooked by nielsoffice V2.0 Alpha </h2>
<span>Welcome to ADZ Framework (Accelerate Development Zone) - A WordPress Framework with this tools you can develop your project in WordPress very handy just download and install and enjoy!</span>

<pre>
ADZ-FRAMWORK FILE STRUCTURE v2.0
 |- css
   |- front-page.css 
   |- settings.css   // relocate piece of code to style.css when have update 
 |- img
 |- inc
   |- class-tgm-plugin-activation.php
   |- custom-header.php
   |- woocommerce.php
 |- js
   |- adz-extend.js   // Goes your custom script
   |- jquery.preloadinator.min.js
 |- languages
 |- layouts
 |- templates
 |- woocommerce
 |- wp-data
   |- processor      // Class and Query
   |- view           // HTML client side 
   |- template-parts // Pages and Other WordPress Contents
   |- e-wpcore       // Archive file (ShortCode)
   |- Saver          // Development/TestingMode
     |- processor      // This
     |- e-wpcore       // is development
     |- view           // version 
     |- config.php     // Config file activate saver 
   |- adz-framework  // Pages Files
     |- adz-framework.php
     |- framework-footer
       |- adz-framework-footer.php
     |- framework-header
       |- adz-framework-header.php
     |- framework-page
       |- adz-framework-page.php
     |- framework-search
       |- adz-framework-search.php
     |- framework-sidebar
       |- adz-framework-sidebar.php
     |- framework-single
       |- adz-framework-single.php           
   |- e-wpcore-register.php // Custom function/Class/PHPMethod
 |- 404
 |- comments.php
 |- footer.php
 |- front-page.php 
 |- functions.php
 |- header.php
 |- index.php
 |- page.php
 |- search.php
 |- single.php
 |- style.css
 |- woocommerce.css
</pre>
 
<h3> ADZ FRAMEWORK | Plugins Development tools included: </h3>
  - Debug Bar                  Created To: https://wordpress.org/<br />  
  - What Template File Am I Viewing? Created To: http://www.themightymo.com/<br />
  - What The File  Created To: http://www.never5.com/<br />
  - Query Monitor              Created To: https://querymonitor.com/ <br />
  - Redirection                Created To: By John Godley<br />
  - CPTA Pagination            Created To: By Naveenkumar C<br />  
  - Server IP & Memory Usage Display Created To:http://apasionados.es/<br />  
  - Classic Editor             Created To: https://github.com/WordPress/classic-editor/<br />    
  - Advanced Custom Fields     Created To: https://www.advancedcustomfields.com/<br />
  - Simple Custom CSS and JS   Created To: https://www.silkypress.com/<br />
  - GDPR Cookie Consent        Created To: http://cookielawinfo.com/<br /> 
  - All in one Favicon         Created To: https://appsumo.com/tools/wordpress/?utm_source=sumo&utm_medium=wp-widget&utm_campaign=all-in-one-favicon<br />
 
<h3> HOW TO USE ADZ FRAMEWORK v2.0 </h3>
  - Download and install to your WordPress project<br />
  - Remove or Rename front-page.php ex. frontpage.php<br />
  - Remove style css front-page.css<br />
  - Install requried Plugins for development purposes<br />
  - Rename sample-page as home and also slug as home hit save<br />
    DONE! Congratulation you can develop your project now!<br />

<h3> USING CLASS/NAMESPACE |- processor </h3>

<pre>
# Default instantiate Class/NameSpace/

# Index File
- $adzFramework = new \adz-project\ADZFRAMEWORK\YourClassName();

# Class File	
namespace adz-project\ADZFRAMEWORK;
class YouClass {
function __construct() 
 {
    // you code goes here..
    ex. parent::html // Extend class for crownPHPEXTEND noHTML/Design/OptimizedCode
    ex. parent::form // Extend class for crownPHPEXTEND formBuilder
 }
}

</pre>

<pre>

# W/ Sub Folder
- $adzFramework = new \adz-project\ADZFRAMEWORK\SubDirectoryName\YourClassName();

# Class File	
namespace adz-project\ADZFRAMEWORK\SubDirectoryName;
class YouClass {
function __construct() 
 {
 
 }
}

</pre>

<pre>

# W/ Sub w/ sub Folder 2
- $adzFramework = new \adz-project\ADZFRAMEWORK\SubDirectoryName\SubDirectoryName2\YourClassName();

# Class File	
namespace adz-project\ADZFRAMEWORK\SubDirectoryName\SubDirectoryName2;
class YouClass {
function __construct() 
 {
 
 }
}

</pre>

<h3>Working with crownPHPEXTEND<br />
   // Do this every page you need to use the library</h3>
<pre>
 // Instantiate Class
 $_Template       = NEW  \adzProject\ADZFRAMEWORK\Template\Template();
 // Or
 USE adzProject\ADZFRAMEWORK\Template\Template AS YourProjectName;
 
 $adzProject = NEW YourProjectName();<br />
</pre>

<pre>
 # Usage of Class 
 // Instantiate Class
 $_Html           = NEW  \adzProject\ADZFRAMEWORK\Html\Html()
 // Or
 USE adzProject\ADZFRAMEWORK\Html\Html AS  YourProjectName;
 
 $adzProject = NEW YourProjectName();
</pre>

<pre>
 # Usage of Class 
 // Instantiate Class
 $_Form           = NEW  \adzProject\ADZFRAMEWORK\Form\Form();
 // or
 USE adzProject\ADZFRAMEWORK\Form\Form AS  YourProjectName
 
 $adzProject = NEW YourProjectName();
</pre>



<h4> NOTE! </h4>
  - Uninstall and remove development extension tools before official publish of your project.<br />
  - You can use this ADZ framework and feel FREE.<br />
 
