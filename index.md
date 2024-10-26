---
layout: default
title: "wmWebStack: Local Server Stack for Windows | Apache, PHP, MySQL"
description: "wmWebStack offers a complete local server stack for Windows, including Apache, PHP, and MySQL. Easy installation and setup for development."
keywords:
  - wmWebStack
  - local server stack
  - Windows server
  - Apache
  - PHP
  - MySQL
  - development environment
noindex: false
---

# Welcome to wmWebStack

**wmWebStack** is a free and installable software package that provides an all-in-one solution for web development on Windows. It includes an intuitive graphical interface that allows you to manage all essential web development tools and utilities with ease. Ideal for developers, testers, and anyone in need of an installable and easy-to-use server solution, wmWebStack offers a robust set of features without the complexity.

<div style="gap: 10px; margin-top: 20px;">
  <a href="https://github.com/wikimint/wmWebStack/releases/latest" target="_blank" class="btn btn-success text-light mb-3 me-lg-2">Download</a>
  <a href="#documentation" class="btn btn-primary text-light mb-3">Documentation</a>
</div>

<a href="/version-log">View Version History</a>

<br/>
![wmWebStack - a lightweight server stack for localhost with Apache, PHP and MySQL](assets/images/localhost-server-stack-apache-php-mysql.webp)

## Features

- **Integrated Control Panel**: A user-friendly GUI with buttons to start and stop all modules like Apache, PHP, MySQL, and more.
- **Antivirus Integration**: Perform ClamAV antivirus scans directly from the control panel.
- **Serveo.net Publishing**: Easily publish your local server live with Serveo.net and manage public links.
- **Configuration Management**: Quick access to open and edit all configuration and INI files for Apache, PHP, MySQL, etc.
- **PHP Info**: Access detailed PHP configuration and status with a single click.
- **System Utilities**: Additional shortcuts for useful Windows system commands like `ipconfig`, `netstat`, `services.msc`, and more.

## Installation

1. Download the latest installer from [GitHub Releases](https://github.com/wikimint/wmWebStack/releases).
2. Run the installer and follow the on-screen instructions.
3. After installation, a shortcut to **wmWebStack** will appear on your desktop.

## How to Use

1. Launch **wmWebStack** using the desktop shortcut.
2. Use the GUI to start and stop services like Apache, PHP, MySQL, and perform other tasks.
3. Access configuration files, server status, and more through the available shortcuts.
4. Use the built-in options to publish your local site via Serveo.net, or run an antivirus scan with a click.

<a name="#documentation"></a>
## Documentation

- **[Getting Started Guide](https://webstack.wikimint.com/docs/getting-started)**
- **[Module Configuration](https://webstack.wikimint.com/docs/configuration)**
- **[FAQ](https://webstack.wikimint.com/docs/faq)**

## About the Developer

**Selvakumaran Krishnan** is a Software Developer and Computer Programmer. With extensive experience in web technologies, Selvakumaran created **wmWebStack** to streamline web development on Windows by combining all necessary tools in one easy-to-use package. Connect with him on [LinkedIn](https://www.linkedin.com/in/selvakumaran-krishnan).

## License

**wmWebStack** is freeware. You are free to use and distribute the software, but the source code is not available for modification or redistribution. For more details, refer to the [EULA](https://webstack.wikimint.com/eula).

## Contact

For any inquiries or support, please reach out via [email](mailto:support@wikimint.com) or visit our [Support Page](https://developer.wikimint.com/p/contact.html).

## Latest Blog Posts

<div class="list-group mt-4">
  {% for post in site.posts limit: 5 %}
  <div class="list-group-item list-group-item-action flex-column align-items-start p-4">
      <a href="{{ post.url | absolute_url }}">{{ post.title }}</a>
      <p>{{ post.description | strip_html | truncate: 150 }}</p>
      <p><small>Published on {{ post.date | date: "%B %d, %Y" }}</small></p>
    </div>
  {% endfor %}
</div>
