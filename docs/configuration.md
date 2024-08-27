# Configuration Guide for wmWebStack

This guide provides information on how to configure the various components of **wmWebStack** to suit your development needs.

## Apache Configuration

1. **Access Configuration File**
   - Open the Apache configuration file through the “Open Config Files” option in the GUI.

2. **Modify Settings**
   - Edit the `httpd.conf` file to adjust server settings like port number, document root, and virtual hosts.

3. **Restart Apache**
   - After making changes, restart Apache using the control panel to apply the new settings.

## PHP Configuration

1. **Access php.ini**
   - Access the `php.ini` file from the GUI to modify PHP settings.

2. **Common Changes**
   - Increase `upload_max_filesize` or `post_max_size` if needed for larger file uploads.
   - Adjust `max_execution_time` for scripts that take longer to run.

3. **Apply Changes**
   - Restart PHP via the GUI to apply your changes.

## MySQL Configuration

1. **Access MySQL Configuration**
   - Use the GUI to open the MySQL configuration file.

2. **Modify Settings**
   - Edit settings such as `max_connections` or `innodb_buffer_pool_size` as needed.

3. **Restart MySQL**
   - Restart MySQL to apply the changes.

## Serveo.net Configuration

1. **Setup Serveo**
   - Click on the Serveo.net button in the GUI to configure and start publishing your local site.

2. **Manage Public Links**
   - The GUI provides quick access to your public Serveo.net links.

For detailed instructions on each component, refer to the specific documentation or visit our [Support Page](https://developer.wikimint.com/p/contact.html).
