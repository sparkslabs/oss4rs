---
title: Nextcloud
---

:::questions
- Using Nextcloud as an example of an open-source alternative, how would you go about installing it?
- What are the different options for running instances of open source software?
- What alternatives are there to Nexcloud?
:::

:::objectives
- Explain how you would go about deciding on a solution
- List the requirements of the different solutions to running an instance of Nextcloud 
:::

:::instructor

Instructor note

:::

## Why did we select NextCloud?
When looking for an alternative to an office suite such as Google or Microsoft Office we would probably want to know which features are supported. NextCloud can give us the following:

- Using LibreOffice and Collabora, Nextcloud provide a full office suite which includes
  - a Wordprocessor,
  - Spreadsheet,
  - Presentation Software,
  - Plain text and Markdown files
- Using IMAP NextCloud offers integration with any email provider that allows IMAP
- Contacts
- a calendar as well as integration, via iCal, with calendars from other providers such as MicroSoft and Google
- Tools for collaboration (similar to MS Teams)
- and more

## Hosting NextCloud
NextCloud can be hosted in several ways:
1. Host it yourself on your home network
2. Host it yourself with an ISP using either a physical server or with a virtual machine
3. Organisational hosting
4. Commercial hosting [Hostinger](https://www.hostinger.com/), [Ionos](https://www.ionos.co.uk/), etc.
5. National hosting by organisation that have the resources to host for multiple organisations (eg. UKRI)

## Requirements for running NextCloud yourself
1. A 64-bit CPU, OS and PHP

<table class="docutils align-default">
<thead>
<tr class="row-odd"><th class="head"><p>Platform</p></th>
<th class="head"><p>Options</p></th>
</tr>
</thead>
<tbody>
<tr class="row-even"><td><p>Operating System
(64-bit)</p></td>
<td><ul class="simple">
<li><p><strong>Ubuntu 26.04 LTS</strong> (recommended)</p></li>
<li><p>Ubuntu 24.04 LTS</p></li>
<li><p><strong>Red Hat Enterprise Linux 10</strong> (recommended)</p></li>
<li><p>Red Hat Enterprise Linux 9</p></li>
<li><p>Debian 13 (Trixie)</p></li>
<li><p>SUSE Linux Enterprise Server 16</p></li>
<li><p>SUSE Linux Enterprise Server 15 SP7 (or later)</p></li>
<li><p>openSUSE Leap 16</p></li>
<li><p>CentOS Stream</p></li>
<li><p>Alpine Linux</p></li>
</ul>
</td>
</tr>
<tr class="row-odd"><td><p>Database</p></td>
<td><ul class="simple">
<li><p>MySQL 8.4 / 9.7</p></li>
<li><p>MariaDB 10.11 / 11.4 / <strong>11.8</strong> / 12.3 (recommended)</p></li>
<li><p>Oracle Database 19c, 21c, 23ai
(<em>only as part of an enterprise subscription</em>)</p></li>
<li><p>PostgreSQL 14 / 15 / 16 / 17 / <strong>18</strong> (recommended)</p></li>
<li><p>SQLite 3.24+ (<em>only recommended for testing and minimal-instances</em>)</p></li>
</ul>
</td>
</tr>
<tr class="row-even"><td><p>Webserver</p></td>
<td><ul class="simple">
<li><p><strong>Apache 2.4 with</strong> <code class="docutils literal notranslate"><span class="pre">mod_php</span></code> <strong>or</strong> <code class="docutils literal notranslate"><span class="pre">php-fpm</span></code> (recommended)</p></li>
<li><p>nginx with <code class="docutils literal notranslate"><span class="pre">php-fpm</span></code></p></li>
</ul>
</td>
</tr>
<tr class="row-odd"><td><p>PHP Runtime</p></td>
<td><ul class="simple">
<li><p>8.3</p></li>
<li><p>8.4</p></li>
<li><p><strong>8.5</strong> (<em>recommended</em>)</p></li>
</ul>
</td>
</tr>
</tbody>
</table>

:::keypoints
- How to select an open source alternative
- Different ways of hosting open source software
- Example of installing software on a server
:::
