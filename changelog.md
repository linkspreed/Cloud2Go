# 2021 July 16 - Version 2.2.6
## New Features
 - Added filtering functionality. It's now possible to filter and search files by date, type, owner, shared status and more.
 - Enhancements
 - Drive "not found" images were updated and will now use colors from appearance editor.
 - Search will now scan the whole title and description content.
 - Updated landing design. It's now also possible to select language and dark mode from landing page footer.
 - It's now possible to export users as CSV from admin area.
 - Updated filtering and search in all data tables in admin area.
 - Added a number of new filters to all data tables.
 - Compatibility with latest Stripe API version.
 - Users can now delete their own account from their account settings page.
 - Updated laravel and angular to latest versions.
 - Custom pages will now support code highlighting for more languages.
 - A more descriptive error message will now be shown if incompatible PHP version is detected.
## Bug Fixes
 - Fixed an issue where files in workspace would sometimes not count toward total user space.
 - Fixed an issue where deleting workspace would not delete files inside it sometimes.
 - It's no longer possible to open multiple audio/video previews at the same time.
 - Corrected a few issues with uploading user avatar from "admin > users" page.
 - Copying a file will now longer require a page reload for it to appear.
 - Corrected a few issues with API documentation.
 - Folders ending with an extension will now upload properly.
 - Deleting a user from admin area will now correctly remove all resources attached to them.
 - Disable free plan selection on upgrade plan page.
 - Fixed a few issues with favicon generation.
 - Registering from pricing page will now correctly redirect user to payment page after registration.
 - Fixed an issue where installation might not start properly on some hosting environments.
 - A number of other smaller fixes.
