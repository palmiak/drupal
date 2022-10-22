![drupal](https://user-images.githubusercontent.com/2342458/197362509-e7d73fda-7d87-446c-adcb-f651cd3baebb.png)

# Drupal - Hello World
An example of how to deploy a **Drupal** site on Kinsta's App Hosting services.

> Kinsta’s Application Hosting is a service to run your web apps and any databases side by side in a hassle-free environment, tailored for developer needs and ease of use. App Hosting is currently in an invite-only beta phase, sign up for a test account at [kinsta.com/application-hosting](https://kinsta.com/application-hosting/).
## Dependency Management
During the deployment process Kinsta will automatically install dependencies defined in your composer.json file.

## Web Server Setup

### Start Command
When deploying an application Kinsta will automatically create a web process with `heroku-php-apache2 web/`. It can be latered altered in the `Processes` tab in the UI.

### Database
**Drupal** requires a database to run. You can do this by following [this guide](https://kinsta.com/help/adding-a-database/). Don't forget to enable the connection to the application where Drupal is installed.

## Environment Variables
Note that **Drupal** requires few environment variables to be set:
- `DB_DATABASE`
- `DB_USERNAME`
- `DB_PASSWORD`
- `DB_HOST`

Optionally, you can also use:
- `DB_PREFIX`
- `DB_PORT`

## What is Drupal
Drupal is content management software. It's used to make many of the websites and applications you use every day. Drupal has great standard features, like easy content authoring, reliable performance, and excellent security. But what sets it apart is its flexibility; modularity is one of its core principles. Its tools help you build the versatile, structured content that dynamic web experiences need.
