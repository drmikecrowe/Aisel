About [![Travis-CI](https://travis-ci.org/ivanproskuryakov/Aisel.svg?branch=master)](https://travis-ci.org/ivanproskuryakov/Aisel)
-----------------------------------

[![Latest Stable Version](https://poser.pugx.org/aisel/aisel/v/stable.svg)](https://packagist.org/packages/aisel/aisel)
[![Total Downloads](https://poser.pugx.org/aisel/aisel/downloads.svg)](https://packagist.org/packages/aisel/aisel)
[![Latest Unstable Version](https://poser.pugx.org/aisel/aisel/v/unstable.svg)](https://packagist.org/packages/aisel/aisel)
[![License](https://poser.pugx.org/aisel/aisel/license.svg)](https://packagist.org/packages/aisel/aisel)
<br/>
[![SensioLabsInsight](https://insight.sensiolabs.com/projects/e3761c26-4de8-4679-8645-ddedad0ae4a4/big.png)](https://insight.sensiolabs.com/projects/e3761c26-4de8-4679-8645-ddedad0ae4a4)<br/>
Aisel is open-source CMS for highload projects based on Symfony2 and AngularJS

Project website: `http://aisel.co/`<br/>
Demo frontend: `http://ecommerce.aisel.co/en/` [frontenduser/frontenduser]<br/>
Demo administration: `http://ecommerce.aisel.co/administration/en/` [backenduser/backenduser]<br/>

<img width="200" src="http://aisel.co/screenshots/frontend_product_view.png"/>
<img width="200" src="http://aisel.co/screenshots/frontend_checkout.png"/>
<img width="200" src="http://aisel.co/screenshots/backend_dashboard.png"/>

Installation: development branch
-----------------------------------

1. Download latest from master: <br/>
`git clone https://github.com/ivanproskuryakov/Aisel.git`
then `cd to aisel/` and download composer <br/>
`curl -sS https://getcomposer.org/installer | php` <br/>
2. Install Aisel environment
`php app/console aisel:install`
3. Install frontend dependencies with Bower<br/>
`bower install`
<br/>
Once this steps done you will be able to access the backend:<br/>
`http://ecommmerce.aisel.dev/administration/en/`<br/>


Notes:<br/>
1. Bower is a command line utility install with nodejs<br/>
`npm install -g bower`<br/>
2.For full javascript minification on frontend use grunt task<br/>
`grunt requirejs`
<br/><br/>

Installation: v0.1.0
-----------------------------------

1. Download composer<br/>
`curl -sS https://getcomposer.org/installer | php`
2. Create project, installer will ask you dbname, username, password, etc.. <br/>
`php composer.phar create-project -s dev aisel/aisel`
`cd aisel/` and finish installation with commands bellow:<br/>
3. Launch installation:<br/>
`php app/console aisel:install`
4. Install frontend dependencies with Bower<br/>
`bower install`

Tests
-----------------------------------
[Behat](http://behat.org) <br/>
`bin/behat`<br/>
[PHPSpec](http://phpspec.net/)<br/>
`bin/phpspec run`<br/>
[Protractor](http://angular.github.io/protractor/#/) <br/>
`protractor protractor/conf.js`<br/>


Documentation
-----------------------------------
Backend: http://aisel.co/documentation/backend/<br/>
Frontend: http://aisel.co/documentation/frontend/<br/>

Speed
-----------------------------------
Check with http://tools.pingdom.com/

Mobile ready check on [Responsinator](http://www.responsinator.com/)
-----------------------------------
http://www.responsinator.com/?url=ecommerce.aisel.co%2Fen%2Fproducts%2F

Bug tracking
-----------------------------------

Project uses [GitHub issues](https://github.com/ivanproskuryakov/Aisel/issues).
If you have found bug, please create an issue.

MIT License
-----------------------------------
License can be found [here](https://github.com/ivanproskuryakov/Aisel/blob/master/LICENSE).

Authors
-----------------------------------
Part of Aisel package, was originally created by [Ivan Proskuryakov](https://github.com/ivanproskuryakov) https://twitter.com/iproskuryakov<br/>
List of [contributors](https://github.com/ivanproskuryakov/AiselConfigBundle/graphs/contributors).

BTC Donations
-----------------------------------
To support ongoing development you may send BitCoin to 1DmBssUeNGXC8VC3BFm3VB3Qc9wmSB7DrK

Consulting
-----------------------------------
If you're need consulting, contact with me by e-mail service@magazento.com
