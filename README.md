# webp_ci_3
Codeigniter 3 Image Manipulation Class for webp Images - webp image uploading , webp image resizing and cropping , webp image water mark

# Step 1 
 ## Add webp MIME Type in config file: ./application/config/mimes.php.
   
   'webp'   =>  array('image/webp'), 
 
 ## and in your upload config "allowed_types" add "webp" :
 
   $config['allowed_types'] = 'gif|jpg|jpeg|png|webp';
   
   
