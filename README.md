# Webp Image Upload, Crop, Resize And Water Marking CodeIgniter 3
Codeigniter 3 Image Manipulation Class for webp Images - webp image uploading , webp image resizing and cropping , webp image water marking

# Image Uploading

 ## Add webp MIME Type in config file: ./application/config/mimes.php. 
    'webp'   =>  array('image/webp'), 
 
 ## And in your upload config "allowed_types" add "webp" :
    $config['allowed_types'] = 'gif|jpg|jpeg|png|webp';
   
   Or upload the class mimes.php file to:  ./application/config/
   
 # Image Manipulation Class
   upload the class Image_lib.php file to:  ./application/libraries/
   
   Tested And Verified 
   -------------------
   
    * Image Resizing
    * Thumbnail Creation
    * Image Watermarking 
    
    Comment for more ...
