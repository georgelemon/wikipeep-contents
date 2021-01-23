# Syncing your live contents with the local
Keeping your markdown contents in a git repository is probably the best idea. In this case you can easily sync the contents between environments. 

**Checking for available edits**
```
php artisan has:edits

You have 1 edit available for publishing
Publishing edits will not affect any other contents.
```

**Publishing only the edits**
```
php artisan publish:edits

All your edits have been published!
Everything is up to date 👌
```

[Go to Console page for finding all Artisan commands](/console) or just run <code>php artisan</code> in your console.

## On shared hosting
Some hosting providers may still offer <code>ssh</code> access on demand. Anyway, in case you don't have ssh access you can build the contents locally and update the live version via <code>FTP</code> by deleting the old <code>/storage/database</code> directory and uploading it back the updated <code>database</code> from your local. That's it!

[Do you have more questions? Check the FAQ page](/faqs)