# PHP Static Analysis Tools (phpcs, phpmd) and ESlint

This repository contains the templates of configuration files for each of the tool like phpcs, phpmd etc.. which are used to run php static analysis tools like phpcs, phpmd and eslint in a project and also setting up pre-commit git hook that will run these linters

To run phpcs (PHP Code Sniffer), type the following command in your project root directory (Considering you got phpcs.xml file located in the project root directory)

    $ ./vendor/bin/phpcs

To run phpmd (PHP Mess Detector), type the following command in your project root directory (Considering you got phpmd.xml file located in the project root directory)

    $ ./vendor/bin/phpmd ./ xml phpmd.xml --reportfile build/logs/phpmd.xml 
