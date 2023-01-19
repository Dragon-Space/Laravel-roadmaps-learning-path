# IMPORTANT: January 2023

This repository contains the **ordered** list of Laravel topics to learn, step-by-step, with related links.
If you want to add a topic, link, or any other suggestion, please open Issues or Pull Requests.

## Beginner Level 
Create your very first simple Laravel project
__Link icons: :book: Official Docs :clapper: Video :page_facing_up: Article :capital_abcd: Course__ 


| Bab | Topic |Learning Links|
| ----- | ----- | ----- |
|The Basics | Introducation |<a href="https://ninedragonlabs.medium.com/mengenal-laravel-9-1-7fc00ba610aa" target="_blank">:page_facing_up: Medium</a>|
|| Routing and Controllers: Basics|  | 
|| Callback Functions and Route::view() |  | 
|| Routing to a Single Controller Method |  | 
|| Route Parameters |  | 
|| Route Naming |  | 
|| Route Groups |  |
|| Blade Basics|  | 
|| <b>Middleware </b> |  |
|Database | Database Migrations |  |
|| Seeder |  |
|| Basic CRUD | <a href="https://santrikoding.com/tutorial-set/tutorial-laravel-9-untuk-pemula" target="_blank">:page_facing_up: Santrikoding</a> |
||Image CRUD|  |
|Relationships| Eloquent One To One |  |  
|| Eloquent One To Many |  |  
|| Eloquent One To Many (Inverse) / Belongs To |  |  
|| Has One Of Many |  |  
|| Has One Through |  |  
|| Has Many Through|  |  
|| Eloquent Many To Many ||
|Polymorphic | One To One | | 
||One To Many | | 
||ne Of Many | | 
||Many To Many | | 
||Custom Polymorphic Types | | 
|Querying|Relationship Methods||
|| Dynamic Properties||
|| Relationship Existence||
|| Relationship Absence||
|| Morph To Relationships||
|Aggregating| Counting Related Models||
|| Other Aggregate Functions||
|| Counting Related Models On Morph To Relationships||
|Eager Loading|Constraining Eager Loads||
||Lazy Eager Loading||
||Preventing Lazy Loading||
|Inserting & Updating|The save Method|||
||The create Method|||
||Belongs To Relationships|||
||Many To Many Relationships|||
|Security|Auth Basics||
||Starter Kits: Breeze (Tailwind) or Laravel UI (Bootstrap)||
||Default Auth Model and Access its Fields from Anywhere ||
||Check Auth in Controller / Blade||
||Auth Middleware||
|Other | All Type CRUD|  |  
||Automated Testing with PHPUnit||
||"Smoke" Tests to Check if Pages are Loading||
||Configure Testing Database and Test CRUD Operations||
||Git Version Control||
||Deployment on Live Servers||
||Try-Catch and Laravel Exceptions||
||Log Files in Laravel||
||API Error Handling and Status Codes||
||API Auth with Sanctum||
||API Eloquent Resources||
||Working with API Clients: Postman or Alternatives||
||API Routes and Controllers||
||Extra Packages: Spatie Medialibrary, Intervention Image, etc||
||Authorization: Roles/Permissions, Gates, Policies||
||Soft Deletes||



## Middle level
Master all Laravel features with 3-5 years of practical experience

__Link icons: :book: Official Docs :clapper: Video :page_facing_up: Article :capital_abcd: Course__ 

|Bab| Topic | Learning Links |
| ---- | ----- | ----- |
|Routing Extra Features | Route Caching |:book: [Route Caching](https://laravel.com/docs/routing#route-caching) <br>|
|| Rate Limiting |:book: [Rate Limiting](https://laravel.com/docs/routing#rate-limiting) <br>:clapper: [Laravel: Create Public API with Cache and Rate Limits](https://www.youtube.com/watch?v=vrLcCxWlxOk) <br>|
|| Invokable controllers |:book: [Single Action Controllers](https://laravel.com/docs/controllers#single-action-controllers) <br>|
|Database/Eloquent Extra Features| Model Observers |:book: [Eloquent Observers](https://laravel.com/docs/eloquent#observers) <br>:clapper: [Laravel Model: Check if Any Field Was Changed](https://www.youtube.com/watch?v=_xluet13xxE) <br>:clapper: [Eloquent Observers or Events Listeners? Which is Better?](https://www.youtube.com/watch?v=DvoaU6cQQHM) <br>|
|| Raw Database Queries |:book: [Query Builder: Raw Expressions](https://laravel.com/docs/queries#raw-expressions) <br>|
|| All Eloquent Features |:book: [All About Eloquent](https://laravel.com/docs/eloquent) <br>:capital_abcd: [Eloquent: Expert Level](https://laraveldaily.teachable.com/p/laravel-eloquent-expert-level?utm_source=github&utm_campaign=roadmap) <br>:page_facing_up: [20 Laravel Eloquent Tips and Tricks](https://laravel-news.com/eloquent-tips-tricks) <br> :clapper: [Laravel Collections: 5 Methods with Real Examples](https://www.youtube.com/watch?v=isAz2GduuA0) <br> [More videos](videos/all-eloquent-features.md) <br>|
|Various Extra Laravel Features| Custom Blade Directives |:book: [Extending Blade](https://laravel.com/docs/blade#extending-blade) <br>|
|| Events and Listeners |:book: [Events and Listeners](https://laravel.com/docs/events) <br>:clapper: [Laravel: 3 Ways to Send a Welcome Email (Controller vs Observer vs Events)](https://www.youtube.com/watch?v=ZWzH6SOzjhI) <br>:clapper: [Laravel: Why Observers and Event Listeners are "Risky"](https://www.youtube.com/watch?v=A3bmLo77e5M) <br>|
|| Laravel HTTP Client and Guzzle |:book: [HTTP Client](https://laravel.com/docs/http-client) <br>:clapper: [Laravel and External APIs: Get Data with HTTP Client](https://www.youtube.com/watch?v=oEDDZsmMLc0) <br>|
|| Login with X: Laravel Socialite |:book: [Laravel Socialite](https://laravel.com/docs/socialite) <br>|
|| Creating Artisan Commands |:book: [Writing Artisan Commands](https://laravel.com/docs/artisan#writing-commands) <br>:clapper: [How to Create Artisan Commands in Laravel](https://www.youtube.com/watch?v=-r3WnYy7g48) <br>|
|| Task Scheduling |:book: [Task Scheduling](https://laravel.com/docs/scheduling) <br>:clapper: [Laravel Task Scheduling: Run Artisan Command Hourly](https://www.youtube.com/watch?v=r-KrsQ0dN80) <br>|
|| Caching |:book: [Cache](https://laravel.com/docs/cache) <br>:clapper: [Cache Eloquent Query Results to Load Pages Instantly](https://www.youtube.com/watch?v=JhKngeE0XJA) <br>|
|| Real-time: Broadcasting, Echo and Pusher |:book: [Broadcasting](https://laravel.com/docs/broadcasting) <br>|
|| **Jobs and Queues** |:capital_abcd: [Queues in Laravel](https://laraveldaily.com/course/laravel-queues?utm_source=github&utm_campaign=roadmap) <br>|
| Queueable Classes and Jobs |:book: [Creating Jobs](https://laravel.com/docs/queues#creating-jobs) <br>:book: [Queueing Notifications](https://laravel.com/docs/notifications#queueing-notifications) <br>:book: [Queued Event Listeners](https://laravel.com/docs/events#queued-event-listeners) <br>:book: [Queueing Mail](https://laravel.com/docs/mail#queueing-mail) <br>:clapper: [Laravel Queues 101: Example with Sending Emails](https://www.youtube.com/watch?v=rVx8xKisbr8) <br>|
| Job Dispatching, Batching and Chaining |:book: [Dispatching Jobs](https://laravel.com/docs/queues#dispatching-jobs) <br>|
| Processing Failed Jobs |:book: [Dealing with Failed Jobs](https://laravel.com/docs/queues#dealing-with-failed-jobs) <br>|
| Configuring Queues: Drivers, Redis, Supervisor |:book: [Running the Queue Worker](https://laravel.com/docs/queues#running-the-queue-worker) <br>:book: [Configuring Supervisor](https://laravel.com/docs/queues#supervisor-configuration) <br>|
| Laravel Horizon (optional, if you use Redis) |:book: [Laravel Horizon](https://laravel.com/docs/horizon) <br>|
| **API Advanced** ||
| Upload Files via API |:page_facing_up: [Laravel API: How to Upload File from Vue.js](https://blog.quickadminpanel.com/laravel-api-how-to-upload-file-from-vue-js/) <br>|
| Generate API Documentation |:page_facing_up: [Laravel API Documentation with OpenAPI/Swagger](https://blog.quickadminpanel.com/laravel-api-documentation-with-openapiswagger/) <br>:clapper: [Scribe: New Package for Laravel API Documentation](https://www.youtube.com/watch?v=PjwGI8c2IfA) <br>|
| API Versioning |:page_facing_up: [Versioning your REST API with Laravel](https://codimth.com/blog/web/laravel/versioning-your-rest-api-laravel) <br>:clapper: [Versioning your API: from V1 to V2 and Beyond [video from my course]](https://laraveldaily.com/lesson/laravel-api/versioning-v1-v2?utm_source=github&utm_campaign=roadmap) <br>|
| API with OAuth and Laravel Passport |:book: [Laravel Passport](https://laravel.com/docs/passport) <br> :clapper: [Laravel API Auth Demo: Passport, oAuth and Sanctum](https://www.youtube.com/watch?v=8myQdPL8I1s)|
| Only-API Projects with Front-end like Vue.js / React.js |:capital_abcd: [Vue.js 3 + Laravel 9 SPA: CRUD with Auth](https://laraveldaily.com/course/vue-laravel-spa?utm_source=github&utm_campaign=roadmap) <br>:capital_abcd: [React.js + Laravel: SPA CRUD with Auth](https://laraveldaily.com/course/react-laravel-spa?utm_source=github&utm_campaign=roadmap) <br>|
| Only-API Projects with Mobile Apps |:capital_abcd: [Flutter Mobile App with Laravel API](https://laraveldaily.com/course/flutter-laravel?utm_source=github&utm_campaign=roadmap) <br>:page_facing_up: [Using Sanctum to authenticate a mobile app](https://laravel-news.com/using-sanctum-to-authenticate-a-mobile-app) <br>|
| **(optional) Starter Kits: Laravel Jetstream and Fortify** ||
| Laravel Jetstream (requires Livewire/Inertia knowledge) |:book: [Laravel Jetstream](https://jetstream.laravel.com) <br>:capital_abcd: [Laravel Jetstream+Livewire: Real Mini-Project](https://laraveldaily.teachable.com/p/laravel-jetstream-livewire-project?utm_source=github&utm_campaign=roadmap) <br>:clapper: [Laravel Jetstream: How it Works and Example How to Customize](https://www.youtube.com/watch?v=d8YgWApHMfA) <br>|
| Laravel Fortify |:book: [Laravel Fortify](https://laravel.com/docs/fortify) <br>:clapper: [Laravel Fortify: Four Auth Things to Customize](https://www.youtube.com/watch?v=Vr4LJU3kw1g) <br>|
| **Payments** ||
| Laravel Cashier with Stripe/Paddle |:book: [Laravel Cashier (Stripe)](https://laravel.com/docs/billing) <br>:book: [Laravel Cashier (Paddle)](https://laravel.com/docs/cashier-paddle) <br>|
| Custom Payment Providers: PayPal, Mollie, etc |:page_facing_up: [Subscription billing with Laravel Cashier for Mollie](https://github.com/laravel/cashier-mollie) <br>:page_facing_up: [How To Integrate Paypal Payment Gateway In Laravel](https://websolutionstuff.com/post/how-to-integrate-paypal-payment-gateway-in-laravel) <br>|
| **Automated Testing Advanced** ||
| TDD: Test-Driven Development |:capital_abcd: [Build A Laravel App With TDD](https://laracasts.com/series/build-a-laravel-app-with-tdd) <br>:capital_abcd: [TDD With Laravel](https://tddwithlaravel.com/) <br>|
| Mocking |:book: [Mocking](https://laravel.com/docs/mocking) <br>|
| (optional) Laravel Dusk |:book: [Laravel Dusk](https://laravel.com/docs/dusk) <br>|
| **Full-Text Search** ||
| Laravel Scout |:book: [Laravel Scout](https://laravel.com/docs/scout) <br>|
| Drivers: ElasticSearch, Algolia or MeiliSearch |:page_facing_up: [ElasticSearch Driver for Laravel Scout](https://laravel-news.com/explorer) <br>:book: [Algolia: Scout Extended](https://www.algolia.com/doc/framework-integration/laravel/getting-started/introduction-to-scout-extended/?client=php) <br>:page_facing_up: [Full-Text Search with MeiliSearch and Laravel Scout](https://tighten.co/blog/full-text-search-with-meilisearch-and-scout/) <br>|
| **Laravel Packages** ||
| Contributing to Packages, making Pull Requests |:clapper: [How to Contribute to Laravel Docs (or any open-source repository)](https://www.youtube.com/watch?v=vEcT6JIFji0) <br>|
| Create Laravel Packages |:book: [Package Development](https://laravel.com/docs/packages) <br>:capital_abcd: [Laravel Package Development](https://laravelpackage.com/) <br>|



## Senior Level
Responsibility for architecture decisions on large projects

| BAB |Topic | Learning Links |
| ---- | ----- | -----|
||PHP/Laravel Design Patterns||
||Creational Design Patterns||
||Structural Design Patterns||
||Behavioral Design Patterns||
||Well-written Code||
||SOLID Code||
||Scalable Code||
||Maintainable Code||
||Best Practices and Standards||
||Large Datasets||
||Large Database Structures||
||NoSQL Solutions||
||Eloquent/SQL Query Optimization||
||Scaling to Multiple Databases||
||Working with High-Traffic Projects||
||Stability and Zero-Downtime Deployments||
||Performance Optimization and Caching||
||Writing Testable Code||
||Continuous Integration and Continuous Delivery (CI/CD)||
