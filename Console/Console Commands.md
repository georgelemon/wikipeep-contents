# Console Commands
If you're coming from Laravel & Symfony world then you already know about it - so you can skip.

Console gives WikiPeep the power to be controlled via a terminal, which makes everyting a pleasure.
Things like building contents based on their status, caching routes and managing the status of the application.
Without the Symfony Console API all these couldn't be possible without dealing with an dashboard admin interface, which we don't need it yet, and we don't have in plan to make one too soon.

## Availalbe Commands

You can find all available commands using
```bash
php artisan
```
You will get the following list
```bash
Available commands:
  help         Displays help for a command
  list         Lists commands

 has
  has:deletes    Determine if there are any markdown files deleted from content directory.
  has:edits      Determine if there are any unpublished edits, in case you forgot what you did last night.
  has:new        Checking if there are any new contents that must be published

 publish
  publish:all    Builds the content of the application based on provided markdown.
  publish:edits  Builds contents only for modified articles that are already published.
  publish:new    Builds new contents only without touching edits or anything published before.
   
```

## Todos
To be added
```bash
 cache
  cache:clear    Clear all cache
  cache:off      Disable caching routes and search API endpoint.
  cache:on       Enable caching routes and search API endpoint.

 app
  app:down       Make WikiPeep application instance offline.
  app:up         Make WikiPeep application instance online.
  app:public     Set WikiPeep application available for public.
  app:private    Set WikiPeep instance as private by setting a password.

  app:clear      Delete all compiled contents and current settings
```