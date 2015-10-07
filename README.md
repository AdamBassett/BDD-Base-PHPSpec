#BDD-Base-PHPSPEC

This is a verry simple set of files to get a package or Kata running quickly.
Requires Node.js and Composer.

##Install
Copy all the files into the base of your project.

Install Gulp and Gulp addons
```npm install ```

Install Composer Packages
```composer install```

Now you can start your first describe.
``` vendor/bit/phpspce desc <Class Name> ```

Run PHPSpec again to creat the class
``` vendor/bit/phpspce ```

PHPSpec will fail and ask if you want to creat the class.
Say yes.

Now we setup autoload
```composer dumpautoload```

Last but not least start gulp watch.
```gulp bdd```


