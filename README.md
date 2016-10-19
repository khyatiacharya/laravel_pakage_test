for making package refer link
http://laraveldaily.com/how-to-create-a-laravel-5-package-in-10-easy-steps/


In main composer.json put 

"require": 
  {
    "laraveltest/testpkg": "*@dev"
  }
  
  "psr-4": 
  {
    "App\\": "app/",
    "Laraveltest\\Testpkg\\": "vendor/laraveltest/testpkg/src"
  }
  
  add this "Laraveltest\Testpkg\TimezonesServiceProvider::class" in app/config.php
  
 make a blank folder with name "database" in laraveltest/testpkg/database
 
 run command "composer update" on terminal
