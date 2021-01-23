# How to replace default logo?

Currently the only way to change default WikiPeep logo is to go to <code>/config/app.php</code>
and paste the path of your <code>.svg</code> / <code>.png</code> logo to <code>logo</code> key.

```php
    /**
     * The application name and logo.
     * When logo is set to false the default WikiPeep logo will be shown.
     */
    'name' => env('APP_NAME', 'WikiPeep'),

    /**
     * Set the application URL mainly used for getting assets
     */
    'url' => env('APP_URL'),

    /**
     * The path to your .svg, .png logo.
     * If set false|null, will show default WikiPeep logo.
     */
    'logo' => false,

```