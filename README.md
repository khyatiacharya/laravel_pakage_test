for making package refer link
https://laracasts.com/discuss/channels/tips/developing-your-packages-in-laravel-5



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
  
 make a blank folder with name "database" in laraveltest/testpkg/database
