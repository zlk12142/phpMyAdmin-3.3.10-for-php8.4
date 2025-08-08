# phpMyAdmin-3.3.10-for-php8.4
phpMyAdmin-3.3.10 supports Internet Explorer 6, but cannot run on php8.4 by default.

config2.inc.php is not managed by git.
You can configure some of the $cfg values inside it.
For example:
<?php
$cfg['blowfish_secret'] = 'f6PnhY6MRSNA3x4mGxjwjvbrVXVxKUYn';
$cfg['Servers'][1]['controluser'] = 'pma';
$cfg['Servers'][1]['controlpass'] = 'pmapass';
$cfg['Servers'][1]['pmadb'] = 'phpmyadmin';
$cfg['Servers'][1]['bookmarktable'] = 'pma_bookmark';
$cfg['Servers'][1]['relation'] = 'pma_relation';
$cfg['Servers'][1]['table_info'] = 'pma_table_info';
$cfg['Servers'][1]['table_coords'] = 'pma_table_coords';
$cfg['Servers'][1]['pdf_pages'] = 'pma_pdf_pages';
$cfg['Servers'][1]['column_info'] = 'pma_column_info';
$cfg['Servers'][1]['history'] = 'pma_history';
$cfg['Servers'][1]['tracking'] = 'pma_tracking';
$cfg['Servers'][1]['designer_coords'] = 'pma_designer_coords';
?>
