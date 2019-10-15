$Weburl = "https://www.dj-store.ru/"

$streamhtml = Invoke-WebRequest -URI $Weburl

$streamhtml.Links | Foreach {$_.href }

Список ссылок на все изображения:

$Weburl = "https://www.dj-store.ru/"

$streamhtml = Invoke-WebRequest -URI $Weburl

$streamhtml.Images | Foreach {$_.src }

$streamhtml = Invoke-WebRequest -URI $Weburl

$streamhtml.AllElements | where Id -eq 'content' | Foreach {$_.innerText}
