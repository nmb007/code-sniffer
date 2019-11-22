# PHP Static Analysis Tools (phpcs, phpmd) and ESlint

Set of important files which are used to setup php code sniffer and eslint in a project and also setting up pre-commit git hook that will run these linters

To run phpcs (PHP Code Sniffer), type the following command in your project root directory (Considering you got phpcs.xml file located in the project root directory)

    $ ./vendor/bin/phpcs

To run phpmd (PHP Mess Detector), type the following command in your project root directory (Considering you got phpmd.xml file located in the project root directory)

    $ ./vendor/bin/phpmd ./ xml phpmd.xml --reportfile build/logs/phpmd.xml 
