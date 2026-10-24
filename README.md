# total-site-block-backup
Total Site &amp; Block Theme Backup Suite for WordPres

Version: 1.0 Stable (1.0.0)
Developer: androidSuperUser
Donate: Support development via PayPal
License: GPL-2.0-or-later

Total Site & Block Theme Backup Suite is a WordPress backup tool for creating comprehensive ZIP backup files and restoring site content(Post, Page, Archive) , installed plugins and themes, and Full Site Editing (FSE) block-theme customizations.

Features

* Selective content backups: Option to choose individual posts, pages, and categories to backup.
* Block-theme customization backups: Back up the supported templates, template parts ( header, footer, single post, archive), global styles, navigation, and synced or reusable blocks.
* Plugin and theme selection: Choose installed plugins and themes to include in a zip backup file.
* ZIP export: Download backup archives or save them to the server-side backup vault for huge files.
* Server Vault: Manage the backup archives stored under the wp-content/uploads/tsbb-backups/, including downloading and deleting archives.
* Flexible restoration: Restore selected supported components from a vault archive or an uploaded ZIP file in importer.
* Chunked archive uploads: Upload ZIP files in 1 MB chunks to help work around common PHP upload-size limits (Working to make chunk files flexibl).
* Restore conflict options: Choose whether to overwrite matching items or skip existing items like plugin, theme, page, etc.
* ZIP compatibility: Uses ZipArchive when available, with a PclZip fallback.

    ->> Working on Automatic Backup.


Installation

1. Download the plugin ZIP release.
2. In WordPress, navigate to Plugins → Add New Plugin → Upload Plugin.
3. Select the plugin ZIP and click Install Now.
4. Activate Total Site & Block Theme Backup Suite.
5. Open Total Backup from the WordPress administration menu.

Creating a Backup

1. Open Total Backup.
2. Select the content, block-theme customizations, plugins, and themes you want to include.
3. Choose whether to download the archive, save it to the Server Vault, or do both.
4. Start the export.
5. Keep an additional copy of important backups outside your hosting server.

Restoring a Backup

1. Open Total Backup.
2. Select an existing Server Vault archive or upload a backup ZIP.
3. Choose the supported components you want to restore.
4. Select the conflict-handling option: overwrite existing items or skip them.
5. Review your selections before starting the restoration.

Important Notes

* Test restorations first: Use a staging website whenever possible before restoring on a production site.
* Maintain independent backups: Archives stored on the same server may be lost if that server or hosting account becomes unavailable.
* Understand backup scope: Selective backups should not be assumed to contain every database table, uploaded file, configuration file, or server setting.
* Protect your archives: Backups may contain private website content. Store and share them securely.
* Check compatibility: Available components and restoration results depend on your WordPress version, active theme, installed plugins, and server environment.

Developer & Authorship

Made with ♥ by androidSuperUser.

* GitHub Profile: https://github.com/androidSuperUser
* Developer: androidSuperUser
* Version: 1.0.0 Stable
* Donations: https://paypal.me/paymenttomanu

If this plugin is useful to you, consider supporting its continued development through the PayPal donation link above.

The developer attribution identifies the project author. The plugin is distributed under the license stated below, which permits modification and redistribution subject to the applicable license terms.

License

This plugin is licensed under the GNU General Public License v2.0 or later (GPL-2.0-or-later).

For details, see the GNU General Public License.
