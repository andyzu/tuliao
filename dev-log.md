1、20210726 安装了 laravel-getwayworker 扩展
composer require smileymrking/laravel-gateway-worker
php artisan vendor:publish --provider="SmileyMrKing\GatewayWorker\GatewayWorkerServiceProvider"
地址：https://github.com/smileymrking/laravel-gateway-worker


2、20210726 安装了 Dcat admin 扩展
composer require dcat/laravel-admin:"2.*" -vvv 
php artisan admin:publish
php artisan admin:install
详细参阅：https://learnku.com/docs/dcat-admin/2.x/install/8081