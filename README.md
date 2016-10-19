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
  
 make a folder with name "database" in laraveltest/testpkg/database
