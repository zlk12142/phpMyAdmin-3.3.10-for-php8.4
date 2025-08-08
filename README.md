# phpMyAdmin-3.3.10-for-php8.4
phpMyAdmin-3.3.10 supports Internet Explorer 6, but cannot run on php8.4 by default.

config2.inc.php is not managed by git.<br>
You can configure some of the $cfg values inside it.<br>
For example:<br>
&lt;?php<br>
$cfg['blowfish_secret'] = 'f6PnhY6MRSNA3x4mGxjwjvbrVXVxKUYn';<br>
$cfg['Servers'][1]['controluser'] = 'pma';<br>
$cfg['Servers'][1]['controlpass'] = 'pmapass';<br>
$cfg['Servers'][1]['pmadb'] = 'phpmyadmin';<br>
$cfg['Servers'][1]['bookmarktable'] = 'pma_bookmark';<br>
$cfg['Servers'][1]['relation'] = 'pma_relation';<br>
$cfg['Servers'][1]['table_info'] = 'pma_table_info';<br>
$cfg['Servers'][1]['table_coords'] = 'pma_table_coords';<br>
$cfg['Servers'][1]['pdf_pages'] = 'pma_pdf_pages';<br>
$cfg['Servers'][1]['column_info'] = 'pma_column_info';<br>
$cfg['Servers'][1]['history'] = 'pma_history';<br>
$cfg['Servers'][1]['tracking'] = 'pma_tracking';<br>
$cfg['Servers'][1]['designer_coords'] = 'pma_designer_coords';<br>
?&gt;<br>
<img src="https://zh.purasbar.com/Files/TopicImages/2025-8/1_2025-8-8_124610_-28199-2475.png"><br>
<img src="https://zh.purasbar.com/Files/TopicImages/2025-8/1_2025-8-8_124756_2677-1063127.png"><br>
<img src="https://zh.purasbar.com/Files/TopicImages/2025-8/1_2025-8-8_124928_-2528-936962.png">
