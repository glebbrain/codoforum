# codoforum
Translate codoforum v3.4(http://codoforum.com/) to Russian:<br>
&nbsp;&nbsp;copy file "ru_RU.php" to "//your.domain.com/sites/default/locale/ru_RU/<b>ru_RU.php</b>"<br>
&nbsp;&nbsp;and edit file "//your.domain.com/sites/default/<b>constants.php</b>", <br>
&nbsp;&nbsp;<b>change</b> define('LOCALE', '<b>en_US</b>') to define('LOCALE', '<b>ru_RU</b>');<br>

Translate admin menu:<br>
&nbsp;&nbsp;edit file "//your.domain.com/admin/layout/templates/layout.tpl"<br>
&nbsp;&nbsp;change \<span\>Dashboard\</span\> to <span>{_t('Dashboard')}</span> and so on<br>
&nbsp;&nbsp;or copy my "admin/layout/templates/layout.tpl"<br>

