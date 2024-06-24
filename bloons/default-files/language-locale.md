---
description: >-
  Learn how to configure language and locale settings for our Minecraft plugins
  to match your preferred language and regional preferences.
---

# 🗨️ Language/Locale

The default language used by Bloons is English. The language file can be selected via the `config.yml` file. Language files are generated and stored in `Bloons/languages/`.

{% hint style="info" %}
Troubleshooting and Support

Having issues with Bloons? Join our [community Discord](https://jeqo.net/discord) server and leave a message!
{% endhint %}

### English US (only option for Bloons Legacy)

{% code title="en_US.yml" fullWidth="false" %}
```yaml
messages:
  prefix: '<gradient:#ff00cc:#5555ff>[Bloons]</gradient> <white>'
  no-permission: '<#fc1c1c>Access denied.'
  player-not-found: '<#fc1c1c>Player not found.'
  config-reloaded: '<green>Config reloaded.'
  command-disabled: '<#fc1c1c>This command is currently disabled!'

  equipped: '%s <green>equipped!'
  unequipped: '<green>Your balloon has been stored safely.'
  balloon-not-found: '<#fc1c1c>Balloon not found.'
  not-equipped: '<#fc1c1c>You do not currently have a balloon equipped.'

  material-not-dyeable: 'Material %s is not a dyeable material.'
  invalid-rgb-values: 'RGB values must be between 0 and 255 to be valid.'
  balloon-not-set: 'The balloon %s is not set in the configuration!'
  material-not-set: 'The material of the balloon %s is not set in the configuration!'
  material-not-valid: 'The material of the balloon %s is not a valid material! Material: %s'
  material-is-not-valid: 'Material %s is not a valid material!'
  invalid-item-meta: 'ItemMeta is not valid for material: %s'

  no-balloons-registered: 'No balloons are found! Cannot create a menu with no balloons.'

  configuration-folder-not-found: 'Configuration folder not found: %s'
  no-configuration-files-found: 'No configuration files found in the folder: %s'
  configuration-section-not-found: 'Configuration section not found for file: %s'
  balloon-type-not-found: 'Error processing balloon type for section: %s in file: %s. Balloon type does not exist or is null.'
  balloon-process-error: 'Error processing balloon for section: %s in file: %s. Error: %s'

  menu-slot-out-of-bounds: '%s menu page button slot(s) out of bounds!'

  invalid-hex-code: 'Invalid hex code: %s'
```
{% endcode %}

### Spanish (Spain)

{% code title="es_ES.yml" %}
```yaml
messages:
  prefix: '<gradient:#ff00cc:#5555ff>[Bloons]</gradient> <white>'
  no-permission: '<#fc1c1c>Acceso denegado.'
  player-not-found: '<#fc1c1c>Jugador no encontrado.'
  config-reloaded: '<green>Configuración recargada.'
  command-disabled: '<#fc1c1c>¡Este comando está actualmente desactivado!'

  equipped: '%s <green>equipado!'
  unequipped: '<green>Tu globo ha sido almacenado de forma segura.'
  balloon-not-found: '<#fc1c1c>Globo no encontrado.'
  not-equipped: '<#fc1c1c>No tienes actualmente un globo equipado.'

  material-not-dyeable: 'El material %s no se puede teñir.'
  invalid-rgb-values: 'Los valores RGB deben estar entre 0 y 255 para ser válidos.'
  balloon-not-set: '¡El globo %s no está configurado!'
  material-not-set: '¡El material del globo %s no está configurado!'
  material-not-valid: '¡El material del globo %s no es válido! Material: %s'
  material-is-not-valid: '¡El material %s no es válido!'
  invalid-item-meta: 'ItemMeta no es válido para el material: %s'

  no-balloons-registered: '¡No hay globos registrados! No se puede crear un menú sin globos.'

  configuration-folder-not-found: 'Carpeta de configuración no encontrada: %s'
  no-configuration-files-found: 'No se encontraron archivos de configuración en la carpeta: %s'
  configuration-section-not-found: 'Sección de configuración no encontrada para el archivo: %s'
  balloon-type-not-found: 'Error al procesar el tipo de globo para la sección: %s en el archivo: %s. El tipo de globo no existe o es nulo.'
  balloon-process-error: 'Error al procesar el globo para la sección: %s en el archivo: %s. Error: %s'

  menu-slot-out-of-bounds: '%s botón(es) de página de menú fuera de límites!'

  invalid-hex-code: 'Código hexadecimal inválido: %s'
```
{% endcode %}

### German

{% code title="de_DE.yml" %}
```yaml
messages:
  prefix: '<gradient:#ff00cc:#5555ff>[Bloons]</gradient> <white>'
  no-permission: '<#fc1c1c>Zugriff verweigert.'
  player-not-found: '<#fc1c1c>Spieler nicht gefunden.'
  config-reloaded: '<green>Konfiguration neu geladen.'
  command-disabled: '<#fc1c1c>Dieser Befehl ist derzeit deaktiviert!'

  equipped: '%s <green>ausgerüstet!'
  unequipped: '<green>Dein Ballon wurde sicher verstaut.'
  balloon-not-found: '<#fc1c1c>Ballon nicht gefunden.'
  not-equipped: '<#fc1c1c>Du hast derzeit keinen Ballon ausgerüstet.'

  material-not-dyeable: 'Material %s ist kein färbbares Material.'
  invalid-rgb-values: 'RGB-Werte müssen zwischen 0 und 255 liegen, um gültig zu sein.'
  balloon-not-set: 'Der Ballon %s ist nicht in der Konfiguration gesetzt!'
  material-not-set: 'Das Material des Ballons %s ist nicht in der Konfiguration gesetzt!'
  material-not-valid: 'Das Material des Ballons %s ist kein gültiges Material! Material: %s'
  invalid-item-meta: 'ItemMeta ist für das Material %s nicht gültig.'

  no-balloons-registered: 'Keine Ballons gefunden! Kann kein Menü ohne Ballons erstellen.'

  configuration-folder-not-found: 'Konfigurationsordner nicht gefunden: %s'
  no-configuration-files-found: 'Keine Konfigurationsdateien im Ordner gefunden: %s'
  configuration-section-not-found: 'Konfigurationsabschnitt für Datei %s nicht gefunden.'
  balloon-type-not-found: 'Fehler bei der Verarbeitung des Ballontyps für Abschnitt %s in Datei %s. Ballontyp existiert nicht oder ist null.'
  balloon-process-error: 'Fehler bei der Verarbeitung des Ballons für Abschnitt %s in Datei %s. Fehler: %s'

  menu-slot-out-of-bounds: 'Menüseitenschaltflächenslot(s) %s außerhalb der Grenzen!'

  invalid-hex-code: 'Ungültiger Hex-Code: %s'
```
{% endcode %}

### French

{% code title="fr_FR.yml" %}
```yaml
messages:
  prefix: '<gradient:#ff00cc:#5555ff>[Bloons]</gradient> <white>'
  no-permission: '<#fc1c1c>Accès refusé.'
  player-not-found: '<#fc1c1c>Joueur non trouvé.'
  config-reloaded: '<green>Configuration rechargée.'
  command-disabled: '<#fc1c1c>Cette commande est actuellement désactivée!'

  equipped: '%s <green>équipé!'
  unequipped: '<green>Votre ballon a été rangé en toute sécurité.'
  balloon-not-found: '<#fc1c1c>Ballon non trouvé.'
  not-equipped: '<#fc1c1c>Vous n\''avez actuellement aucun ballon équipé.'

  material-not-dyeable: 'Le matériau %s n\''est pas un matériau teignable.'
  invalid-rgb-values: 'Les valeurs RGB doivent être comprises entre 0 et 255 pour être valides.'
  balloon-not-set: 'Le ballon %s n\''est pas défini dans la configuration!'
  material-not-set: 'Le matériau du ballon %s n\''est pas défini dans la configuration!'
  material-not-valid: 'Le matériau du ballon %s n\''est pas un matériau valide! Matériau: %s'
  invalid-item-meta: 'ItemMeta n\''est pas valide pour le matériau: %s'

  no-balloons-registered: 'Aucun ballon trouvé! Impossible de créer un menu sans ballons.'

  configuration-folder-not-found: 'Dossier de configuration non trouvé: %s'
  no-configuration-files-found: 'Aucun fichier de configuration trouvé dans le dossier: %s'
  configuration-section-not-found: 'Section de configuration non trouvée pour le fichier: %s'
  balloon-type-not-found: 'Erreur de traitement du type de ballon pour la section: %s dans le fichier: %s. Le type de ballon n\''existe pas ou est nul.'
  balloon-process-error: 'Erreur de traitement du ballon pour la section: %s dans le fichier: %s. Erreur: %s'

  menu-slot-out-of-bounds: 'Le(s) bouton(s) de la page de menu %s sont hors limites!'

  invalid-hex-code: 'Code hexadécimal invalide: %s'
```
{% endcode %}

### Japanese

{% code title="ja_JP.yml" %}
```yaml
messages:
  prefix: '<gradient:#ff00cc:#5555ff>[Bloons]</gradient> <white>'
  no-permission: '<#fc1c1c>アクセスが拒否されました。'
  player-not-found: '<#fc1c1c>プレイヤーが見つかりません。'
  config-reloaded: '<green>設定がリロードされました。'
  command-disabled: '<#fc1c1c>このコマンドは現在無効です！'

  equipped: '%s <green>装備されました！'
  unequipped: '<green>バルーンが安全に保管されました。'
  balloon-not-found: '<#fc1c1c>バルーンが見つかりません。'
  not-equipped: '<#fc1c1c>現在、装備しているバルーンはありません。'

  material-not-dyeable: '材料 %s は染色可能な材料ではありません。'
  invalid-rgb-values: 'RGB値は0から255の間でなければなりません。'
  balloon-not-set: '設定にバルーン %s が設定されていません！'
  material-not-set: 'バルーン %s の材料が設定にありません！'
  material-not-valid: 'バルーン %s の材料は有効な材料ではありません！ 材料: %s'
  invalid-item-meta: '材料 %s に対してItemMetaが無効です。'

  no-balloons-registered: 'バルーンが見つかりません！ バルーンなしでメニューを作成することはできません。'

  configuration-folder-not-found: '設定フォルダが見つかりません: %s'
  no-configuration-files-found: 'フォルダに設定ファイルが見つかりません: %s'
  configuration-section-not-found: 'ファイル %s の設定セクションが見つかりません。'
  balloon-type-not-found: 'ファイル %s のセクション %s のバルーンタイプを処理中にエラーが発生しました。バルーンタイプが存在しないか、nullです。'
  balloon-process-error: 'ファイル %s のセクション %s のバルーンを処理中にエラーが発生しました。エラー: %s'

  menu-slot-out-of-bounds: '%s メニューページのボタンスロットが範囲外です！'

  invalid-hex-code: '無効な 16 進コード: %s'
```
{% endcode %}

### Korean

{% code title="ko_KR.yml" %}
```yaml
messages:
  prefix: '<gradient:#ff00cc:#5555ff>[Bloons]</gradient> <white>'
  no-permission: '<#fc1c1c>접근이 거부되었습니다.'
  player-not-found: '<#fc1c1c>플레이어를 찾을 수 없습니다.'
  config-reloaded: '<green>구성이 다시 로드되었습니다.'
  command-disabled: '<#fc1c1c>이 명령은 현재 비활성화되어 있습니다!'

  equipped: '%s <green>장착되었습니다!'
  unequipped: '<green>풍선이 안전하게 보관되었습니다.'
  balloon-not-found: '<#fc1c1c>풍선을 찾을 수 없습니다.'
  not-equipped: '<#fc1c1c>현재 장착된 풍선이 없습니다.'

  material-not-dyeable: '재료 %s 은(는) 염색할 수 있는 재료가 아닙니다.'
  invalid-rgb-values: 'RGB 값은 0에서 255 사이여야 합니다.'
  balloon-not-set: '구성에 풍선 %s 이(가) 설정되어 있지 않습니다!'
  material-not-set: '구성에 풍선 %s 의 재료가 설정되어 있지 않습니다!'
  material-not-valid: '풍선 %s 의 재료가 유효한 재료가 아닙니다! 재료: %s'
  invalid-item-meta: '재료 %s 의 ItemMeta가 유효하지 않습니다.'

  no-balloons-registered: '풍선을 찾을 수 없습니다! 풍선이 없는 메뉴를 만들 수 없습니다.'

  configuration-folder-not-found: '구성 폴더를 찾을 수 없습니다: %s'
  no-configuration-files-found: '폴더에서 구성 파일을 찾을 수 없습니다: %s'
  configuration-section-not-found: '파일 %s 에 대한 구성 섹션을 찾을 수 없습니다.'
  balloon-type-not-found: '파일 %s 의 섹션 %s 에 대한 풍선 유형을 처리하는 동안 오류가 발생했습니다. 풍선 유형이 존재하지 않거나 null입니다.'
  balloon-process-error: '파일 %s 의 섹션 %s 에 대한 풍선을 처리하는 동안 오류가 발생했습니다. 오류: %s'

  menu-slot-out-of-bounds: '%s 메뉴 페이지 버튼 슬롯이 범위를 벗어났습니다!'

  invalid-hex-code: '잘못된 16진수 코드: %s'
```
{% endcode %}

### Portuguese (Brazil)

{% code title="pt_BR.yml" %}
```yaml
messages:
  prefix: '<gradient:#ff00cc:#5555ff>[Bloons]</gradient> <white>'
  no-permission: '<#fc1c1c>Acesso negado.'
  player-not-found: '<#fc1c1c>Jogador não encontrado.'
  config-reloaded: '<green>Configuração recarregada.'
  command-disabled: '<#fc1c1c>Este comando está desativado no momento!'

  equipped: '%s <green>equipado!'
  unequipped: '<green>Seu balão foi armazenado com segurança.'
  balloon-not-found: '<#fc1c1c>Balão não encontrado.'
  not-equipped: '<#fc1c1c>Você não possui um balão equipado no momento.'

  material-not-dyeable: 'O material %s não pode ser tingido.'
  invalid-rgb-values: 'Os valores RGB devem estar entre 0 e 255 para serem válidos.'
  balloon-not-set: 'O balão %s não está configurado!'
  material-not-set: 'O material do balão %s não está configurado!'
  material-not-valid: 'O material do balão %s não é válido! Material: %s'
  material-is-not-valid: 'O material %s não é válido!'
  invalid-item-meta: 'ItemMeta não é válido para o material: %s'

  no-balloons-registered: 'Nenhum balão registrado! Não é possível criar um menu sem balões.'

  configuration-folder-not-found: 'Pasta de configuração não encontrada: %s'
  no-configuration-files-found: 'Nenhum arquivo de configuração encontrado na pasta: %s'
  configuration-section-not-found: 'Seção de configuração não encontrada para o arquivo: %s'
  balloon-type-not-found: 'Erro ao processar o tipo de balão para a seção: %s no arquivo: %s. O tipo de balão não existe ou é nulo.'
  balloon-process-error: 'Erro ao processar o balão para a seção: %s no arquivo: %s. Erro: %s'

  menu-slot-out-of-bounds: '%s botão(s) da página do menu fora dos limites!'

  invalid-hex-code: 'Código hexadecimal inválido: %s'
```
{% endcode %}

### Russian

{% code title="ru_RU.yml" %}
```yaml
messages:
  prefix: '<gradient:#ff00cc:#5555ff>[Bloons]</gradient> <white>'
  no-permission: '<#fc1c1c>Доступ запрещен.'
  player-not-found: '<#fc1c1c>Игрок не найден.'
  config-reloaded: '<green>Конфигурация перезагружена.'
  command-disabled: '<#fc1c1c>Эта команда в данный момент отключена!'

  equipped: '%s <green>экипирован!'
  unequipped: '<green>Ваш шар успешно убран.'
  balloon-not-found: '<#fc1c1c>Шар не найден.'
  not-equipped: '<#fc1c1c>У вас нет экипированного шара.'

  material-not-dyeable: 'Материал %s не является окрашиваемым.'
  invalid-rgb-values: 'Значения RGB должны быть в диапазоне от 0 до 255.'
  balloon-not-set: 'Шар %s не задан в конфигурации!'
  material-not-set: 'Материал шара %s не задан в конфигурации!'
  material-not-valid: 'Материал шара %s не является допустимым материалом! Материал: %s'
  invalid-item-meta: 'ItemMeta недействителен для материала: %s'

  no-balloons-registered: 'Не найдено ни одного шара! Невозможно создать меню без шаров.'

  configuration-folder-not-found: 'Папка конфигурации не найдена: %s'
  no-configuration-files-found: 'В папке не найдено конфигурационных файлов: %s'
  configuration-section-not-found: 'Не найдена конфигурационная секция для файла: %s'
  balloon-type-not-found: 'Ошибка обработки типа шара для секции: %s в файле: %s. Тип шара не существует или равен null.'
  balloon-process-error: 'Ошибка обработки шара для секции: %s в файле: %s. Ошибка: %s'

  menu-slot-out-of-bounds: 'Слот(ы) кнопки страницы меню %s вне допустимых границ!'

  invalid-hex-code: 'Неверный шестнадцатеричный код: %s.'
```
{% endcode %}

### Chinese (Traditional)

{% code title="zh_CN.yml" %}
```yaml
messages:
  prefix: '<gradient:#ff00cc:#5555ff>[Bloons]</gradient> <white>'
  no-permission: '<#fc1c1c>访问被拒。'
  player-not-found: '<#fc1c1c>玩家未找到。'
  config-reloaded: '<green>配置已重新加载。'
  command-disabled: '<#fc1c1c>此命令目前已禁用！'

  equipped: '%s <green>已装备！'
  unequipped: '<green>你的气球已安全存放。'
  balloon-not-found: '<#fc1c1c>气球未找到。'
  not-equipped: '<#fc1c1c>你当前没有装备气球。'

  material-not-dyeable: '材料 %s 不是可染色材料。'
  invalid-rgb-values: 'RGB 值必须在 0 到 255 之间才有效。'
  balloon-not-set: '配置中未设置气球 %s！'
  material-not-set: '配置中未设置气球 %s 的材料！'
  material-not-valid: '气球 %s 的材料不是有效的材料！材料: %s'
  invalid-item-meta: '材料 %s 的 ItemMeta 无效。'

  no-balloons-registered: '未找到任何气球！无法创建没有气球的菜单。'

  configuration-folder-not-found: '配置文件夹未找到: %s'
  no-configuration-files-found: '文件夹中未找到配置文件: %s'
  configuration-section-not-found: '文件 %s 中未找到配置部分。'
  balloon-type-not-found: '处理文件 %s 中部分 %s 的气球类型时出错。气球类型不存在或为空。'
  balloon-process-error: '处理文件 %s 中部分 %s 的气球时出错。错误: %s'

  menu-slot-out-of-bounds: '%s 菜单页面按钮槽超出范围！'

  invalid-hex-code: '無效的十六進位代碼：%s'
```
{% endcode %}

### Afrikaans (South Africa)

{% code title="af_ZA.yml" %}
```yaml
messages:
  prefix: '<gradient:#ff00cc:#5555ff>[Bloons]</gradient> <white>'
  no-permission: '<#fc1c1c>Toegang geweier.'
  player-not-found: '<#fc1c1c>Speler nie gevind nie.'
  config-reloaded: '<green>Konfigurasie herlaai.'
  command-disabled: '<#fc1c1c>Hierdie opdrag is tans gedeaktiveer!'

  equipped: '%s <green>toegerus!'
  unequipped: '<green>Jou ballon is veilig gestoor.'
  balloon-not-found: '<#fc1c1c>Ballon nie gevind nie.'
  not-equipped: '<#fc1c1c>Jy het tans nie 'n ballon toegerus nie.'

  material-not-dyeable: 'Materiaal %s is nie 'n kleurbare materiaal nie.'
  invalid-rgb-values: 'RGB-waardes moet tussen 0 en 255 wees om geldig te wees.'
  balloon-not-set: 'Die ballon %s is nie in die konfigurasie gestel nie!'
  material-not-set: 'Die materiaal van die ballon %s is nie in die konfigurasie gestel nie!'
  material-not-valid: "Die materiaal van die ballon %s is nie 'n geldige materiaal nie! Materiaal: %s"
  material-is-not-valid: 'Materiaal %s is nie 'n geldige materiaal nie!'
  invalid-item-meta: 'ItemMeta is nie geldig vir materiaal: %s nie'

  no-balloons-registered: 'Geen ballonne gevind nie! Kan nie 'n spyskaart met geen ballonne skep nie.'

  configuration-folder-not-found: 'Konfigurasie-lêergids nie gevind nie: %s'
  no-configuration-files-found: 'Geen konfigurasie-lêers gevind in die gids nie: %s'
  configuration-section-not-found: 'Konfigurasie-afdeling nie gevind vir lêer nie: %s'
  balloon-type-not-found: 'Fout met verwerking van ballontipe vir afdeling: %s in lêer: %s. Ballontipe bestaan nie of is nul.'
  balloon-process-error: 'Fout met verwerking van ballon vir afdeling: %s in lêer: %s. Fout: %s'

  menu-slot-out-of-bounds: '%s spyskaartbladsy knoppie gleuf(e) buite perke!'

  invalid-hex-code: 'Ongeldige heksadesimale kode: %s'
```
{% endcode %}

### Arabic (Saudi Arabia)

{% code title="ar_SA.yml" %}
```yaml
messages:
  prefix: '<gradient:#ff00cc:#5555ff>[Bloons]</gradient> <white>'
  no-permission: '<#fc1c1c>الوصول ممنوع.'
  player-not-found: '<#fc1c1c>اللاعب غير موجود.'
  config-reloaded: '<green>تم إعادة تحميل الإعدادات.'
  command-disabled: '<#fc1c1c>هذا الأمر معطل حالياً!'

  equipped: '%s <green>تم التجهيز!'
  unequipped: '<green>تم تخزين بالونك بأمان.'
  balloon-not-found: '<#fc1c1c>البالون غير موجود.'
  not-equipped: '<#fc1c1c>ليس لديك بالون مجهز حالياً.'

  material-not-dyeable: 'المادة %s غير قابلة للصبغ.'
  invalid-rgb-values: 'قيم RGB يجب أن تكون بين 0 و 255 لتكون صالحة.'
  balloon-not-set: 'البالون %s غير محدد في الإعدادات!'
  material-not-set: 'مادة البالون %s غير محددة في الإعدادات!'
  material-not-valid: 'مادة البالون %s غير صالحة! المادة: %s'
  material-is-not-valid: 'المادة %s غير صالحة!'
  invalid-item-meta: 'ItemMeta غير صالح للمادة: %s'

  no-balloons-registered: 'لا توجد بالونات مسجلة! لا يمكن إنشاء قائمة بدون بالونات.'

  configuration-folder-not-found: 'مجلد الإعدادات غير موجود: %s'
  no-configuration-files-found: 'لا توجد ملفات إعدادات في المجلد: %s'
  configuration-section-not-found: 'قسم الإعدادات غير موجود للملف: %s'
  balloon-type-not-found: 'خطأ في معالجة نوع البالون للقسم: %s في الملف: %s. نوع البالون غير موجود أو فارغ.'
  balloon-process-error: 'خطأ في معالجة البالون للقسم: %s في الملف: %s. الخطأ: %s'

  menu-slot-out-of-bounds: 'فتحات زر صفحة القائمة %s خارج الحدود!'

  invalid-hex-code: 'كود سداسي غير صالح: %s'
```
{% endcode %}

### Azerbaijani (Azerbaijan)

{% code title="az_AZ.yml" %}
```yaml
messages:
  prefix: '<gradient:#ff00cc:#5555ff>[Bloons]</gradient> <white>'
  no-permission: '<#fc1c1c>Giriş icazəsi yoxdur.'
  player-not-found: '<#fc1c1c>Oyuncu tapılmadı.'
  config-reloaded: '<green>Konfiq yenidən yükləndi.'
  command-disabled: '<#fc1c1c>Bu komanda hazırda deaktiv edilmişdir!'

  equipped: '%s <green>təchiz edildi!'
  unequipped: '<green>Balonunuz təhlükəsiz şəkildə saxlanıldı.'
  balloon-not-found: '<#fc1c1c>Balon tapılmadı.'
  not-equipped: '<#fc1c1c>Hazırda təchiz edilmiş bir balonunuz yoxdur.'

  material-not-dyeable: 'Material %s boyanabilir material deyil.'
  invalid-rgb-values: 'RGB dəyərləri etibarlı olmaq üçün 0 ilə 255 arasında olmalıdır.'
  balloon-not-set: 'Konfiqurasiyada %s balon təyin edilməyib!'
  material-not-set: '%s balonun materialı konfiqurasiyada təyin edilməyib!'
  material-not-valid: '%s balonun materialı etibarlı material deyil! Material: %s'
  material-is-not-valid: 'Material %s etibarlı bir material deyil!'
  invalid-item-meta: 'Material üçün əşya meta etiketi etibarlı deyil: %s'

  no-balloons-registered: 'Heç bir balon qeydə alınmayıb! Balonsuz bir menyü yaradıla bilməz.'

  configuration-folder-not-found: 'Konfiqurasiya qovluğu tapılmadı: %s'
  no-configuration-files-found: 'Qovluqda konfiqurasiya faylları tapılmadı: %s'
  configuration-section-not-found: 'Faylı üçün konfiqurasiya bölməsi tapılmadı: %s'
  balloon-type-not-found: 'Faylda %s bölməsi üçün balon növü işlənməsində xəta baş verdi: %s. Balon növü mövcud deyil və ya boşdur.'
  balloon-process-error: 'Faylda %s bölməsi üçün balon prosesi xətası baş verdi: %s. Xəta: %s'

  menu-slot-out-of-bounds: '%s menyü səhifə düymə yeri çapdan kənar çıxır!'

  invalid-hex-code: 'Etibarsız hex kodu: %s'
```
{% endcode %}

### Belarusian (Belarus)

{% code title="be_BY.yml" %}
```yaml
messages:
  prefix: '<gradient:#ff00cc:#5555ff>[Bloons]</gradient> <white>'
  no-permission: '<#fc1c1c>Доступ забаронены.'
  player-not-found: '<#fc1c1c>Гульца не знойдзены.'
  config-reloaded: '<green>Канфігурацыя перазагружана.'
  command-disabled: '<#fc1c1c>Гэтая каманда зараз адключана!'

  equipped: '%s <green>запасены!'
  unequipped: '<green>Ваш шарік захаваны бяспечна.'
  balloon-not-found: '<#fc1c1c>Шар не знойдзены.'
  not-equipped: '<#fc1c1c>У вас зараз няма запасенага шара.'

  material-not-dyeable: 'Матэрыял %s не можа быць пазначаны колерамі.'
  invalid-rgb-values: 'Значэння RGB павінны быць у дыяпазоне ад 0 да 255, каб быць сапраўднымі.'
  balloon-not-set: 'Шар %s не ўстаноўлены ў канфігурацыі!'
  material-not-set: 'Матэрыял шара %s не ўстаноўлены ў канфігурацыі!'
  material-not-valid: "Матэрыял шара %s не з'яўляецца сапраўдным матэрыялам! Матэрыял: %s"
  material-is-not-valid: 'Матэрыял %s не з'яўляецца сапраўдным матэрыялам!'
  invalid-item-meta: 'Няправільныя метаданыя элемента для матэрыялу: %s'

  no-balloons-registered: 'Няма зарэгістраваных шароў! Немагчыма стварыць меню без шараў.'

  configuration-folder-not-found: 'Катэгорыя канфігурацыі не знойдзена: %s'
  no-configuration-files-found: 'Няма файлаў канфігурацыі ў тэчцы: %s'
  configuration-section-not-found: 'Секцыя канфігурацыі не знойдзена для файла: %s'
  balloon-type-not-found: 'Памылка пры апрацоўцы тыпу шара для раздзелу: %s у файле: %s. Тып шара не існуе або ёсць пустота.'
  balloon-process-error: 'Памылка пры апрацоўцы шара для раздзелу: %s у файле: %s. Памылка: %s'

  menu-slot-out-of-bounds: '%s кнопка(-і) старонкі меню выходзяць за межы!'

  invalid-hex-code: 'Няправільны шэсцнаццатковы код: %s'
```
{% endcode %}

### Bulgarian (Bulgaria)

{% code title="bg_BG.yml" %}
```yaml
messages:
  prefix: '<gradient:#ff00cc:#5555ff>[Bloons]</gradient> <white>'
  no-permission: '<#fc1c1c>Нямате разрешение.'
  player-not-found: '<#fc1c1c>Играчът не е намерен.'
  config-reloaded: '<green>Конфигурацията е презаредена.'
  command-disabled: '<#fc1c1c>Тази команда е в момента деактивирана!'

  equipped: '%s <green>екипиран!'
  unequipped: '<green>Вашият балон е сигурно съхранен.'
  balloon-not-found: '<#fc1c1c>Балонът не е намерен.'
  not-equipped: '<#fc1c1c>В момента нямате екипиран балон.'

  material-not-dyeable: 'Материалът %s не може да бъде оцветен.'
  invalid-rgb-values: 'RGB стойностите трябва да са между 0 и 255, за да бъдат валидни.'
  balloon-not-set: 'Балонът %s не е настроен в конфигурацията!'
  material-not-set: 'Материалът на балона %s не е настроен в конфигурацията!'
  material-not-valid: 'Материалът на балона %s не е валиден! Материал: %s'
  material-is-not-valid: 'Материалът %s не е валиден!'
  invalid-item-meta: 'ItemMeta не е валиден за материала: %s'

  no-balloons-registered: 'Няма регистрирани балони! Не може да се създаде меню без балони.'

  configuration-folder-not-found: 'Папката с конфигурация не е намерена: %s'
  no-configuration-files-found: 'Няма намерени конфигурационни файлове в папката: %s'
  configuration-section-not-found: 'Разделът на конфигурацията не е намерен за файла: %s'
  balloon-type-not-found: 'Грешка при обработката на типа балон за секцията: %s във файла: %s. Типът на балона не съществува или е празен.'
  balloon-process-error: 'Грешка при обработката на балона за секцията: %s във файла: %s. Грешка: %s'

  menu-slot-out-of-bounds: '%s бутон на страницата на менюто извън границите!'

  invalid-hex-code: 'Невалиден хекс код: %s'
```
{% endcode %}

### Bengali (India)

{% code title="bn_IN.yml" %}
```yaml
messages:
  prefix: '<gradient:#ff00cc:#5555ff>[Bloons]</gradient> <white>'
  no-permission: '<#fc1c1c>অনুমতি অস্বীকৃত।'
  player-not-found: '<#fc1c1c>খেলোয়াড় পাওয়া যায়নি।'
  config-reloaded: '<green>কনফিগারেশন পুনরায় লোড হয়েছে।'
  command-disabled: '<#fc1c1c>এই কমান্ড বর্তমানে নিষ্ক্রিয় করা হয়েছে!'

  equipped: '%s <green>পরিপ্রেক্ষিত!'
  unequipped: '<green>আপনার বেলুন নিরাপদে সংরক্ষিত হয়েছে।'
  balloon-not-found: '<#fc1c1c>বেলুন পাওয়া যায়নি।'
  not-equipped: '<#fc1c1c>আপনি বর্তমানে কোনও বেলুন পরিপ্রেক্ষিত করা নেই।'

  material-not-dyeable: '%s উপাদানটি রঙ করা যাবে না।'
  invalid-rgb-values: 'আরজিবি মান 0 থেকে 255 এর মধ্যে হতে হবে একটি বৈধ মানের জন্য।'
  balloon-not-set: '%s কনফিগারেশনে বেলুন সেট করা হয়নি!'
  material-not-set: '%s বেলুনের উপাদানটি কনফিগারেশনে সেট করা হয়নি!'
  material-not-valid: '%s বেলুনের উপাদানটি বৈধ নয়! উপাদান: %s'
  material-is-not-valid: '%s উপাদান বৈধ নয়!'
  invalid-item-meta: 'উপাদান মেটা মূল্য বৈধ নয় মেটেরিয়ালের জন্য: %s'

  no-balloons-registered: 'কোনও বেলুন নিবন্ধিত নেই! কোনও বেলুন নেই মেনু তৈরি করা যায় না।'

  configuration-folder-not-found: 'কনফিগারেশন ফোল্ডার খুঁজে পাওয়া যায়নি: %s'
  no-configuration-files-found: 'ফোল্ডারে কোনও কনফিগারেশন ফাইল পাওয়া যায়নি: %s'
  configuration-section-not-found: 'ফাইলের জন্য কনফিগারেশন বিভাগ পাওয়া যায়নি: %s'
  balloon-type-not-found: 'বিভাগের জন্য বেলুনের প্রকার প্রসেসিং ত্রুটি: %s ফাইলে: %s। বেলুনের ধরন অস্তিত্ব নেই বা খালি।'
  balloon-process-error: 'বিভাগের জন্য বেলুন প্রসেসিং ত্রুটি: %s ফাইলে: %s। ত্রুটি: %s'

  menu-slot-out-of-bounds: '%s মেনু পৃষ্ঠা বোতাম স্লটগুলি সীমার বাইরে!'

  invalid-hex-code: 'অবৈধ হেক্স কোড: %s'
```
{% endcode %}

### Bosnian (Bosnia and Herzegovina)

{% code title="bs_BA.yml" %}
```yaml
messages:
  prefix: '<gradient:#ff00cc:#5555ff>[Bloons]</gradient> <white>'
  no-permission: '<#fc1c1c>Nema dozvole.'
  player-not-found: '<#fc1c1c>Igrač nije pronađen.'
  config-reloaded: '<green>Konfiguracija je ponovo učitana.'
  command-disabled: '<#fc1c1c>Ova komanda je trenutno onemogućena!'

  equipped: '%s <green>opremljen!'
  unequipped: '<green>Vaš balon je sigurno spremljen.'
  balloon-not-found: '<#fc1c1c>Balon nije pronađen.'
  not-equipped: '<#fc1c1c>Trenutno nemate opremljen balon.'

  material-not-dyeable: 'Materijal %s nije moguće obojiti.'
  invalid-rgb-values: 'RGB vrijednosti moraju biti između 0 i 255 da bi bile validne.'
  balloon-not-set: 'Balon %s nije postavljen u konfiguraciji!'
  material-not-set: 'Materijal balona %s nije postavljen u konfiguraciji!'
  material-not-valid: 'Materijal balona %s nije validan materijal! Materijal: %s'
  material-is-not-valid: 'Materijal %s nije validan materijal!'
  invalid-item-meta: 'ItemMeta nije validan za materijal: %s'

  no-balloons-registered: 'Nema registrovanih balona! Ne može se kreirati meni bez balona.'

  configuration-folder-not-found: 'Mapa konfiguracije nije pronađena: %s'
  no-configuration-files-found: 'Nema pronađenih konfiguracionih fajlova u mapi: %s'
  configuration-section-not-found: 'Sekcija konfiguracije nije pronađena za fajl: %s'
  balloon-type-not-found: 'Greška prilikom procesiranja tipa balona za sekciju: %s u fajlu: %s. Tip balona ne postoji ili je prazan.'
  balloon-process-error: 'Greška prilikom procesiranja balona za sekciju: %s u fajlu: %s. Greška: %s'

  menu-slot-out-of-bounds: '%s dugme stranice menija izvan granica!'

  invalid-hex-code: 'Nevažeći heks kod: %s'
```
{% endcode %}

### Czech (Czech Republic)

{% code title="cs_CZ.yml" %}
```yaml
messages:
  prefix: '<gradient:#ff00cc:#5555ff>[Bloons]</gradient> <white>'
  no-permission: '<#fc1c1c>Nemáte oprávnění.'
  player-not-found: '<#fc1c1c>Hráč nebyl nalezen.'
  config-reloaded: '<green>Konfigurace byla znovu načtena.'
  command-disabled: '<#fc1c1c>Tento příkaz je momentálně zakázán!'

  equipped: '%s <green>vybaven!'
  unequipped: '<green>Váš balón byl uložen bezpečně.'
  balloon-not-found: '<#fc1c1c>Balon nebyl nalezen.'
  not-equipped: '<#fc1c1c>Nemáte momentálně vybaven žádný balón.'

  material-not-dyeable: 'Materiál %s nelze obarvit.'
  invalid-rgb-values: 'RGB hodnoty musí být mezi 0 a 255, aby byly platné.'
  balloon-not-set: 'Balon %s není nastaven v konfiguraci!'
  material-not-set: 'Materiál balonu %s není nastaven v konfiguraci!'
  material-not-valid: 'Materiál balonu %s není platný materiál! Materiál: %s'
  material-is-not-valid: 'Materiál %s není platný materiál!'
  invalid-item-meta: 'ItemMeta není platný pro materiál: %s'

  no-balloons-registered: 'Nejsou registrovány žádné balóny! Nelze vytvořit menu bez balónů.'

  configuration-folder-not-found: 'Složka s konfigurací nebyla nalezena: %s'
  no-configuration-files-found: 'V této složce nebyly nalezeny žádné konfigurační soubory: %s'
  configuration-section-not-found: 'Sekce konfigurace nebyla nalezena pro soubor: %s'
  balloon-type-not-found: 'Chyba při zpracování typu balónu pro sekci: %s v souboru: %s. Typ balónu neexistuje nebo je prázdný.'
  balloon-process-error: 'Chyba při zpracování balónu pro sekci: %s v souboru: %s. Chyba: %s'

  menu-slot-out-of-bounds: '%s tlačítek na stránce menu přesahuje rozsah!'

  invalid-hex-code: 'Neplatný hexadecimální kód: %s'
```
{% endcode %}

### Welsh (United Kingdom)

{% code title="cy_GB.yml" %}
```yaml
messages:
  prefix: '<gradient:#ff00cc:#5555ff>[Bloons]</gradient> <white>'
  no-permission: '<#fc1c1c>Mynediad wedi'i wrthod.'
  player-not-found: '<#fc1c1c>Nid yw'r chwaraewr wedi'i ddod o hyd.'
  config-reloaded: '<green>Wedi ail-lwytho'r cyfluniad.'
  command-disabled: '<#fc1c1c>Mae'r gorchymyn hwn wedi'i analluogi ar hyn o bryd!'

  equipped: '%s <green>wedi'i osod!'
  unequipped: '<green>Wedi cadw eich balŵn yn ddiogel.'
  balloon-not-found: '<#fc1c1c>Nid oes balŵn wedi'i ddod o hyd.'
  not-equipped: '<#fc1c1c>Nid oes balŵn wedi'i osod gennych ar hyn o bryd.'

  material-not-dyeable: 'Ni ellir lliwio'r deunydd %s.'
  invalid-rgb-values: 'Gwerthoedd RGB annilys: Rhaid i'r gwerthoedd fod rhwng 0 a 255.'
  balloon-not-set: 'Nid yw'r balŵn %s wedi'i osod yn y cyfluniad!'
  material-not-set: 'Nid yw deunydd y balŵn %s wedi'i osod yn y cyfluniad!'
  material-not-valid: 'Nid yw deunydd y balŵn %s yn ddilys! Deunydd: %s'
  material-is-not-valid: 'Nid yw deunydd %s yn ddilys!'
  invalid-item-meta: 'ItemMeta annilys ar gyfer deunydd: %s'

  no-balloons-registered: 'Heb gofrestru unrhyw balŵn! Ni ellir creu menyw heb unrhyw balŵn.'

  configuration-folder-not-found: 'Heb ddod o hyd i ffolder cyfluniad: %s'
  no-configuration-files-found: 'Heb ddod o hyd i ffeiliau cyfluniad yn y ffolder: %s'
  configuration-section-not-found: 'Heb ddod o hyd i adran cyfluniad ar gyfer y ffeil: %s'
  balloon-type-not-found: 'Gwall wrth brosesu math balŵn ar gyfer adran: %s yn y ffeil: %s. Nid yw'r math balŵn yn bodoli neu'n wag.'
  balloon-process-error: 'Gwall wrth brosesu balŵn ar gyfer adran: %s yn y ffeil: %s. Gwall: %s'

  menu-slot-out-of-bounds: '%s nodyn tudalen y fwylen yn mynd dros y ffiniau!'

  invalid-hex-code: 'Cod hex annilys: %s'
```
{% endcode %}

### Danish (Denmark)

{% code title="da_DK.yml" %}
```yaml
messages:
  prefix: '<gradient:#ff00cc:#5555ff>[Bloons]</gradient> <white>'
  no-permission: '<#fc1c1c>Ingen tilladelse.'
  player-not-found: '<#fc1c1c>Spilleren blev ikke fundet.'
  config-reloaded: '<green>Konfiguration genindlæst.'
  command-disabled: '<#fc1c1c>Denne kommando er i øjeblikket deaktiveret!'

  equipped: '%s <green>udrustet!'
  unequipped: '<green>Din ballon er blevet gemt sikkert.'
  balloon-not-found: '<#fc1c1c>Ballonen blev ikke fundet.'
  not-equipped: '<#fc1c1c>Du har i øjeblikket ikke en udstyret ballon.'

  material-not-dyeable: 'Materialet %s kan ikke farves.'
  invalid-rgb-values: 'RGB-værdier skal være mellem 0 og 255 for at være gyldige.'
  balloon-not-set: 'Ballonen %s er ikke indstillet i konfigurationen!'
  material-not-set: 'Materialet til ballonen %s er ikke indstillet i konfigurationen!'
  material-not-valid: 'Materialet til ballonen %s er ikke gyldigt! Materiale: %s'
  material-is-not-valid: 'Materialet %s er ikke gyldigt!'
  invalid-item-meta: 'ItemMeta er ikke gyldig for materialet: %s'

  no-balloons-registered: 'Ingen balloner er registreret! Kan ikke oprette en menu uden balloner.'

  configuration-folder-not-found: 'Konfigurationsmappen blev ikke fundet: %s'
  no-configuration-files-found: 'Ingen konfigurationsfiler blev fundet i mappen: %s'
  configuration-section-not-found: 'Konfigurationssektionen blev ikke fundet for filen: %s'
  balloon-type-not-found: 'Fejl ved behandling af ballontypen for afsnittet: %s i filen: %s. Ballontypen findes ikke eller er tom.'
  balloon-process-error: 'Fejl ved behandling af ballonen for afsnittet: %s i filen: %s. Fejl: %s'

  menu-slot-out-of-bounds: '%s menuknap(er) er uden for grænserne!'

  invalid-hex-code: 'Ugyldig hexadecimal kode: %s'
```
{% endcode %}

### Greek (Greece)

{% code title="el_GR.yml" %}
```yaml
messages:
  prefix: '<gradient:#ff00cc:#5555ff>[Bloons]</gradient> <white>'
  no-permission: '<#fc1c1c>Δεν έχετε άδεια.'
  player-not-found: '<#fc1c1c>Ο παίκτης δεν βρέθηκε.'
  config-reloaded: '<green>Η διαμόρφωση επαναφορτώθηκε.'
  command-disabled: '<#fc1c1c>Αυτή η εντολή είναι απενεργοποιημένη αυτή τη στιγμή!'

  equipped: '%s <green>εξοπλίστηκε!'
  unequipped: '<green>Η αερόσφαιρά σας αποθηκεύτηκε με ασφάλεια.'
  balloon-not-found: '<#fc1c1c>Η αερόσφαιρα δεν βρέθηκε.'
  not-equipped: '<#fc1c1c>Δεν έχετε αυτή τη στιγμή εξοπλισμένη αερόσφαιρα.'

  material-not-dyeable: 'Το υλικό %s δεν μπορεί να βαφτεί.'
  invalid-rgb-values: 'Οι τιμές RGB πρέπει να είναι από 0 έως 255 για να είναι έγκυρες.'
  balloon-not-set: 'Η αερόσφαιρα %s δεν έχει οριστεί στη διαμόρφωση!'
  material-not-set: 'Το υλικό της αερόσφαιρας %s δεν έχει οριστεί στη διαμόρφωση!'
  material-not-valid: 'Το υλικό της αερόσφαιρας %s δεν είναι έγκυρο υλικό! Υλικό: %s'
  material-is-not-valid: 'Το υλικό %s δεν είναι έγκυρο!'
  invalid-item-meta: 'Η ItemMeta δεν είναι έγκυρη για το υλικό: %s'

  no-balloons-registered: 'Δεν βρέθηκαν αερόσφαιρες! Δεν μπορεί να δημιουργηθεί ένα μενού χωρίς αερόσφαιρες.'

  configuration-folder-not-found: 'Ο φάκελος διαμόρφωσης δεν βρέθηκε: %s'
  no-configuration-files-found: 'Δεν βρέθηκαν αρχεία διαμόρφωσης στον φάκελο: %s'
  configuration-section-not-found: 'Η ενότητα διαμόρφωσης δεν βρέθηκε για το αρχείο: %s'
  balloon-type-not-found: 'Σφάλμα επεξεργασίας τύπου αερόσφαιρας για την ενότητα: %s στο αρχείο: %s. Ο τύπος αερόσφαιρας δεν υπάρχει ή είναι κενός.'
  balloon-process-error: 'Σφάλμα επεξεργασίας αερόσφαιρας για την ενότητα: %s στο αρχείο: %s. Σφάλμα: %s'

  menu-slot-out-of-bounds: '%s κουμπιά σελίδας μενού εκτός ορίων!'

  invalid-hex-code: 'Μη έγκυρος κωδικός hex: %s'
```
{% endcode %}

### Estonian (Estonia)

{% code title="et_EE.yml" %}
```yaml
messages:
  prefix: '<gradient:#ff00cc:#5555ff>[Bloons]</gradient> <white>'
  no-permission: '<#fc1c1c>Puudub luba.'
  player-not-found: '<#fc1c1c>Mängijat ei leitud.'
  config-reloaded: '<green>Konfiguratsioon on uuesti laaditud.'
  command-disabled: '<#fc1c1c>See käsk on hetkel keelatud!'

  equipped: '%s <green>on varustatud!'
  unequipped: '<green>Teie õhupall on ohutult salvestatud.'
  balloon-not-found: '<#fc1c1c>Õhupalli ei leitud.'
  not-equipped: '<#fc1c1c>Teil ei ole hetkel ühtegi õhupalli varustatud.'

  material-not-dyeable: 'Materjali %s ei saa värvida.'
  invalid-rgb-values: 'RGB väärtused peavad olema vahemikus 0 kuni 255, et olla kehtivad.'
  balloon-not-set: 'Õhupalli %s pole konfiguratsioonis määratud!'
  material-not-set: 'Õhupalli materjal %s pole konfiguratsioonis määratud!'
  material-not-valid: 'Õhupalli materjal %s pole kehtiv materjal! Materjal: %s'
  material-is-not-valid: 'Materjal %s pole kehtiv materjal!'
  invalid-item-meta: 'ItemMeta pole materjali %s jaoks kehtiv.'

  no-balloons-registered: 'Õhupalle ei leitud! Menüüd ei saa luua ilma õhupallideta.'

  configuration-folder-not-found: 'Konfiguratsioonikausta ei leitud: %s'
  no-configuration-files-found: 'Konfiguratsioonifaile ei leitud kaustast: %s'
  configuration-section-not-found: 'Konfiguratsiooni sektsiooni ei leitud failist: %s'
  balloon-type-not-found: 'Viga õhupalli tüübi töötlemisel sektsioonile: %s failis: %s. Õhupalli tüüp ei eksisteeri või on tühi.'
  balloon-process-error: 'Viga õhupalli töötlemisel sektsioonile: %s failis: %s. Viga: %s'

  menu-slot-out-of-bounds: '%s menüülehe nupu kohta on väljaspool piire!'

  invalid-hex-code: 'Vigane heksakood: %s'
```
{% endcode %}

### Basque (Spain)

{% code title="eu_ES.yml" %}
```yaml
messages:
  prefix: '<gradient:#ff00cc:#5555ff>[Bloons]</gradient> <white>'
  no-permission: '<#fc1c1c>Ezinezkoa sarrera.'
  player-not-found: '<#fc1c1c>Jokalaria ez da aurkitu.'
  config-reloaded: '<green>Konfigurazioa berrargitaratu da.'
  command-disabled: '<#fc1c1c>Komandu hau ez dago aktibatuta!'

  equipped: '%s <green>ekipatu da!'
  unequipped: '<green>Zure baloia seguru batera gorde da.'
  balloon-not-found: '<#fc1c1c>Baloia ez da aurkitu.'
  not-equipped: '<#fc1c1c>Ez daukazu momentuz ekipatutako baloirik.'

  material-not-dyeable: '%s materiala ez da koloreztagarria.'
  invalid-rgb-values: 'RGB balioak 0 eta 255 artean egon behar dute baliozkoak izateko.'
  balloon-not-set: 'Ez da %s baloia konfigurazioan ezarri!'
  material-not-set: '%s baloiko materiala ez da konfigurazioan ezarri!'
  material-not-valid: '%s baloiko materiala ez da baliozko materiala! Materiala: %s'
  material-is-not-valid: '%s materiala ez da baliozko materiala!'
  invalid-item-meta: 'ItemMeta ez da baliozko materialarentzako: %s'

  no-balloons-registered: 'Ez daude baloiak erregistratuta! Baloirik gabeko menua sortu ezin da.'

  configuration-folder-not-found: 'Ezarpenak gordetzeko karpeta ez da aurkitu: %s'
  no-configuration-files-found: 'Ez da konfigurazio fitxategirik aurkitu karpeta honetan: %s'
  configuration-section-not-found: 'Ezarpen atala ez da aurkitu fitxategian: %s'
  balloon-type-not-found: 'Errorea baloia mota prozesatzerakoan atalean: %s fitxategian: %s. Baloia mota ez da existitzen edo hutsik dago.'
  balloon-process-error: 'Errorea baloia prozesatzerakoan atalean: %s fitxategian: %s. Errorea: %s'

  menu-slot-out-of-bounds: '%s menu orri botoi tokia mugatik kanpo dago!'

  invalid-hex-code: 'Hex kode baliogabea: %s'
```
{% endcode %}

### Persian (Iran)

{% code title="fa_IR.yml" %}
```yaml
messages:
  prefix: '<gradient:#ff00cc:#5555ff>[Bloons]</gradient> <white>'
  no-permission: '<#fc1c1c>دسترسی رد شد.'
  player-not-found: '<#fc1c1c>بازیکن یافت نشد.'
  config-reloaded: '<green>پیکربندی مجدداً بارگذاری شد.'
  command-disabled: '<#fc1c1c>این دستور در حال حاضر غیرفعال است!'

  equipped: '%s <green>نصب شده است!'
  unequipped: '<green>بادبادک شما اکنون به طور ایمن ذخیره شده است.'
  balloon-not-found: '<#fc1c1c>بادبادک یافت نشد.'
  not-equipped: '<#fc1c1c>شما در حال حاضر هیچ بادبادکی نصب نکرده‌اید.'

  material-not-dyeable: 'مواد %s قابل رنگ‌آمیزی نیست.'
  invalid-rgb-values: 'مقادیر RGB باید بین 0 و 255 باشند تا معتبر باشند.'
  balloon-not-set: 'بادبادک %s در پیکربندی تنظیم نشده است!'
  material-not-set: 'مواد بادبادک %s در پیکربندی تنظیم نشده است!'
  material-not-valid: 'مواد بادبادک %s معتبر نیست! مواد: %s'
  material-is-not-valid: 'ماده %s معتبر نیست!'
  invalid-item-meta: 'ItemMeta برای ماده %s معتبر نیست.'

  no-balloons-registered: 'بادبادکی ثبت نشده است! نمی‌توانید یک فهرست بدون بادبادک ایجاد کنید.'

  configuration-folder-not-found: 'پوشه پیکربندی یافت نشد: %s'
  no-configuration-files-found: 'فایل‌های پیکربندی در پوشه یافت نشد: %s'
  configuration-section-not-found: 'بخش پیکربندی برای فایل یافت نشد: %s'
  balloon-type-not-found: 'خطا در پردازش نوع بادبادک برای بخش: %s در فایل: %s. نوع بادبادک موجود نیست یا صفر است.'
  balloon-process-error: 'خطا در پردازش بادبادک برای بخش: %s در فایل: %s. خطا: %s'

  menu-slot-out-of-bounds: '%s دکمه صفحه منو خارج از حدود است!'

  invalid-hex-code: 'کد هگزاگرادی اشتباه است: %s'
```
{% endcode %}

### Finnish (Finland)

{% code title="fi_FI.yml" %}
```yaml
messages:
  prefix: '<gradient:#ff00cc:#5555ff>[Bloons]</gradient> <white>'
  no-permission: '<#fc1c1c>Ei lupaa.'
  player-not-found: '<#fc1c1c>Pelaajaa ei löydetty.'
  config-reloaded: '<green>Asetukset on ladattu uudelleen.'
  command-disabled: '<#fc1c1c>Tämä komento on tällä hetkellä poistettu käytöstä!'

  equipped: '%s <green>varustettu!'
  unequipped: '<green>Ilmapallonne on turvallisesti tallennettu.'
  balloon-not-found: '<#fc1c1c>Ilmapalloa ei löytynyt.'
  not-equipped: '<#fc1c1c>Sinulla ei ole tällä hetkellä varustettua ilmapalloa.'

  material-not-dyeable: 'Materiaalia %s ei voi värjätä.'
  invalid-rgb-values: 'RGB-arvojen on oltava välillä 0 ja 255, jotta ne olisivat kelvollisia.'
  balloon-not-set: 'Ilmapalloa %s ei ole asetettu asetuksissa!'
  material-not-set: 'Ilmapallon materiaalia %s ei ole asetettu asetuksissa!'
  material-not-valid: 'Ilmapallon materiaali %s ei ole kelvollinen materiaali! Materiaali: %s'
  material-is-not-valid: 'Materiaali %s ei ole kelvollinen materiaali!'
  invalid-item-meta: 'ItemMeta ei ole kelvollinen materiaalille: %s'

  no-balloons-registered: 'Ei löydy rekisteröityjä ilmapalloja! Ei voida luoda valikkoa ilman ilmapalloja.'

  configuration-folder-not-found: 'Asetuskansiota ei löydy: %s'
  no-configuration-files-found: 'Asetustiedostoja ei löytynyt kansiosta: %s'
  configuration-section-not-found: 'Asetusosaa ei löytynyt tiedostosta: %s'
  balloon-type-not-found: 'Virhe käsiteltäessä ilmapallotyyppiä osiolle: %s tiedostossa: %s. Ilmapallotyyppiä ei ole tai se on tyhjä.'
  balloon-process-error: 'Virhe käsiteltäessä ilmapalloa osiolle: %s tiedostossa: %s. Virhe: %s'

  menu-slot-out-of-bounds: '%s valikkosivun painike(tta) on ulkona rajoista!'

  invalid-hex-code: 'Virheellinen heksakoodi: %s'
```
{% endcode %}

### Faroese (Faroe Islands)

{% code title="fo_FO.yml" %}
```yaml
messages:
  prefix: '<gradient:#ff00cc:#5555ff>[Bloons]</gradient> <white>'
  no-permission: '<#fc1c1c>Eingin loyvi.'
  player-not-found: '<#fc1c1c>Spælari fannst ikki.'
  config-reloaded: '<green>Stillingar endurrættir.'
  command-disabled: '<#fc1c1c>Hetta skipan er tøkt nú!'

  equipped: '%s <green>útbúgvað!'
  unequipped: '<green>Tínur ballónur er trygt geymdur.'
  balloon-not-found: '<#fc1c1c>Ballónur fannst ikki.'
  not-equipped: '<#fc1c1c>Tit hava ikki nakrar ballónur útbúgvaðar í nú. '

  material-not-dyeable: 'Materiál %s kann ikki litast.'
  invalid-rgb-values: 'RGB virðið má vera millum 0 og 255 fyri at vera gildandi.'
  balloon-not-set: 'Ballónur %s er ikki sett í stillingar!'
  material-not-set: 'Materiálið hjá ballónunum %s er ikki sett í stillingar!'
  material-not-valid: 'Materiálið hjá ballónunum %s er ikki gildigt! Materiál: %s'
  material-is-not-valid: 'Materiál %s er ikki gildigt!'
  invalid-item-meta: 'ItemMeta er ikki gild fyri materiál: %s'

  no-balloons-registered: 'Eingin ballónur funnist! Ikki gjørt henda menu uttan ballónum.'

  configuration-folder-not-found: 'Stillingamappan fannst ikki: %s'
  no-configuration-files-found: 'Eingin stillingaskráir funnist í mappuni: %s'
  configuration-section-not-found: 'Stillingarsnið fannst ikki fyri skrá: %s'
  balloon-type-not-found: 'Feilur við at handtera ballóntegund fyri seksjón: %s í skrá: %s. Ballóntegundin er ikki til ella er tóm.'
  balloon-process-error: 'Feilur við at handtera ballón fyri seksjón: %s í skrá: %s. Feilur: %s'

  menu-slot-out-of-bounds: '%s mený síðu knøtt(ur) er úteftir teirra mørk!'

  invalid-hex-code: 'Ógild heksadekimal koda: %s'
```
{% endcode %}

### Galician (Spain)

{% code title="gl_ES.yml" %}
```yaml
messages:
  prefix: '<gradient:#ff00cc:#5555ff>[Bloons]</gradient> <white>'
  no-permission: '<#fc1c1c>Sen permiso.'
  player-not-found: '<#fc1c1c>Xogador non atopado.'
  config-reloaded: '<green>Configuración recargada.'
  command-disabled: '<#fc1c1c>Este comando está actualmente desactivado!'

  equipped: '%s <green>equipado!'
  unequipped: '<green>O seu globo foi almacenado con seguridade.'
  balloon-not-found: '<#fc1c1c>Globo non atopado.'
  not-equipped: '<#fc1c1c>Actualmente non ten ningún globo equipado.'

  material-not-dyeable: 'O material %s non pode ser tingido.'
  invalid-rgb-values: 'Os valores RGB deben estar entre 0 e 255 para seren válidos.'
  balloon-not-set: 'O globo %s non está definido na configuración!'
  material-not-set: 'O material do globo %s non está definido na configuración!'
  material-not-valid: 'O material do globo %s non é válido! Material: %s'
  material-is-not-valid: 'O material %s non é válido!'
  invalid-item-meta: 'ItemMeta non é válido para o material: %s'

  no-balloons-registered: 'Non se atopan globos! Non se pode crear un menú sen globos.'

  configuration-folder-not-found: 'Cartafol de configuración non atopado: %s'
  no-configuration-files-found: 'Non se atoparon arquivos de configuración no cartafol: %s'
  configuration-section-not-found: 'Sección de configuración non atopada para o arquivo: %s'
  balloon-type-not-found: 'Erro ao procesar o tipo de globo para a sección: %s no arquivo: %s. O tipo de globo non existe ou é nulo.'
  balloon-process-error: 'Erro ao procesar o globo para a sección: %s no arquivo: %s. Erro: %s'

  menu-slot-out-of-bounds: '%s botóns da páxina do menú fóra dos límites!'

  invalid-hex-code: 'Código hexadecimal non válido: %s'
```
{% endcode %}

### Gujarati (India)

{% code title="gu_IN.yml" %}
```yaml
messages:
  prefix: '<gradient:#ff00cc:#5555ff>[Bloons]</gradient> <white>'
  no-permission: '<#fc1c1c>કોઈ પરવાનગી નથી.'
  player-not-found: '<#fc1c1c>ખેલાડી મળી નથી.'
  config-reloaded: '<green>રૂપરેખાંકન પુનઃલોડ થયો.'
  command-disabled: '<#fc1c1c>આ આદેશ હાલમાં અક્રિય છે!'

  equipped: '%s <green>સજ્જ કરેલું છે!'
  unequipped: '<green>તમારી બલૂન સુરક્ષિત રીતે સંગ્રહિત થઇ ગઈ છે.'
  balloon-not-found: '<#fc1c1c>બલૂન મળ્યું નથી.'
  not-equipped: '<#fc1c1c>તમારી સાથે હાલમાં કોઈ બલૂન સજ્જ નથી.'

  material-not-dyeable: 'સામગ્રી %s રંગીન નથી.'
  invalid-rgb-values: 'RGB મૂલ્યો માન્ય હોવા માટે 0 થી 255 વચ્ચે હોવો જ જોઈએ.'
  balloon-not-set: 'બલૂન %s રૂપરેખાંકનમાં સેટ કરવામાં નથી!'
  material-not-set: 'બલૂનની સામગ્રી %s રૂપરેખાંકનમાં સેટ કરવામાં નથી!'
  material-not-valid: 'બલૂનની સામગ્રી %s માન્ય સામગ્રી નથી! સામગ્રી: %s'
  material-is-not-valid: 'સામગ્રી %s માન્ય સામગ્રી નથી!'
  invalid-item-meta: 'વસ્તુની મેટા માન્ય નથી: %s'

  no-balloons-registered: 'કોઈ બલૂન્સ મળ્યા નથી! કોઈ બલૂન્સ સાથે મેનૂ બનાવી શકાતું નથી.'

  configuration-folder-not-found: 'રૂપરેખાંકન ફોલ્ડર મળ્યો નથી: %s'
  no-configuration-files-found: 'ફોલ્ડરમાં કોઈ રૂપરેખાંકન ફાઇલો મળ્યા નથી: %s'
  configuration-section-not-found: 'ફાઇલ માટે રૂપરેખાંકન વિભાગ મળ્યો નથી: %s'
  balloon-type-not-found: 'વિભાગ %s માટે બલૂન પ્રકારનું પ્રક્રિયાકરણ ક્રમ નથી: %s ફાઇલમાં. બલૂન પ્રકાર અસ્તિત્વમાં નથી અથવા ખાલી છે.'
  balloon-process-error: 'વિભાગ %s માટે બલૂન પ્રક્રિયાકરણ ક્રમ નથી: %s ફાઇલમાં. ભૂલ: %s'

  menu-slot-out-of-bounds: '%s મેનુ પેજ બટન સ્લોટ(સ) બાહ્ય મર્યાદાઓ બહાર!'

  invalid-hex-code: 'અમાન્ય હેક્સ કોડ: %s'
```
{% endcode %}

### Hebrew (Israel)

{% code title="he_IL.yml" %}
```yaml
messages:
  prefix: '<gradient:#ff00cc:#5555ff>[Bloons]</gradient> <white>'
  no-permission: '<#fc1c1c>אין הרשאה.'
  player-not-found: '<#fc1c1c>שחקן לא נמצא.'
  config-reloaded: '<green>התצורה נטענה מחדש.'
  command-disabled: '<#fc1c1c>פקודה זו מנוטרלת כרגע!'

  equipped: '%s <green>נצמד בהצלחה!'
  unequipped: '<green>הבלון שלך נשמר בבטיחות.'
  balloon-not-found: '<#fc1c1c>הבלון לא נמצא.'
  not-equipped: '<#fc1c1c>אין לך בלון מצופה כרגע.'

  material-not-dyeable: 'החומר %s אינו ניתן לצביעה.'
  invalid-rgb-values: 'ערכי RGB חייבים להיות בין 0 ל-255 כדי להיות חוקיים.'
  balloon-not-set: 'הבלון %s לא מוגדר בתצורה!'
  material-not-set: 'החומר של הבלון %s אינו מוגדר בתצורה!'
  material-not-valid: 'החומר של הבלון %s אינו חומר חוקי! חומר: %s'
  material-is-not-valid: 'החומר %s אינו חומר חוקי!'
  invalid-item-meta: 'ItemMeta אינו חוקי עבור החומר: %s'

  no-balloons-registered: 'לא נמצאו בלונים! לא ניתן ליצור תפריט ללא בלונים.'

  configuration-folder-not-found: 'תיקיית התצורה לא נמצאה: %s'
  no-configuration-files-found: 'לא נמצאו קבצי תצורה בתיקייה: %s'
  configuration-section-not-found: 'לא נמצאה סעיף תצורה עבור הקובץ: %s'
  balloon-type-not-found: 'שגיאה בעיבוד סוג בלון עבור הסעיף: %s בקובץ: %s. סוג הבלון אינו קיים או הוא ריק.'
  balloon-process-error: 'שגיאה בעיבוד הבלון עבור הסעיף: %s בקובץ: %s. שגיאה: %s'

  menu-slot-out-of-bounds: '%s כפתורי עמוד תפריט מחוץ לגבולות!'

  invalid-hex-code: 'קוד hex לא חוקי: %s'
```
{% endcode %}

### Hindi (India)

{% code title="hi_IN.yml" %}
```yaml
messages:
  prefix: '<gradient:#ff00cc:#5555ff>[Bloons]</gradient> <white>'
  no-permission: '<#fc1c1c>पहुंच निषेध।'
  player-not-found: '<#fc1c1c>खिलाड़ी नहीं मिला।'
  config-reloaded: '<green>कॉन्फ़िगरेशन पुनः लोड किया गया।'
  command-disabled: '<#fc1c1c>यह कमांड वर्तमान में निष्क्रिय है!'

  equipped: '%s <green>सफलतापूर्वक सुसज्जित किया गया!'
  unequipped: '<green>आपका गुब्बारा सुरक्षित रूप से संग्रहीत हो गया है।'
  balloon-not-found: '<#fc1c1c>गुब्बारा नहीं मिला।'
  not-equipped: '<#fc1c1c>आपके पास वर्तमान में कोई गुब्बारा सुसज्जित नहीं है।'

  material-not-dyeable: 'सामग्री %s को रंगने में सक्षम नहीं है।'
  invalid-rgb-values: 'RGB मूल्यों को मान्य होने के लिए 0 से 255 के बीच होना चाहिए।'
  balloon-not-set: 'गुब्बारा %s कॉन्फ़िगरेशन में सेट नहीं है!'
  material-not-set: 'गुब्बारे की सामग्री %s कॉन्फ़िगरेशन में सेट नहीं है!'
  material-not-valid: 'गुब्बारे की सामग्री %s मान्य सामग्री नहीं है! सामग्री: %s'
  material-is-not-valid: 'सामग्री %s मान्य सामग्री नहीं है!'
  invalid-item-meta: 'आइटम मेटा सामग्री के लिए मान्य नहीं है: %s'

  no-balloons-registered: 'कोई गुब्बारे नहीं मिले! कोई गुब्बारे के साथ मेनू नहीं बनाया जा सकता।'

  configuration-folder-not-found: 'कॉन्फ़िगरेशन फ़ोल्डर नहीं मिला: %s'
  no-configuration-files-found: 'फ़ोल्डर में कोई कॉन्फ़िगरेशन फ़ाइलें नहीं मिलीं: %s'
  configuration-section-not-found: 'फ़ाइल के लिए कॉन्फ़िगरेशन सेक्शन नहीं मिला: %s'
  balloon-type-not-found: 'धागे के सेक्शन के लिए गुब्बारे का प्रकार प्रसंस्करण त्रुटि: %s फ़ाइल में: %s। गुब्बारे का प्रकार मौजूद नहीं है या खाली है।'
  balloon-process-error: 'धागे के सेक्शन के लिए गुब्बारे की प्रसंस्करण त्रुटि: %s फ़ाइल में: %s। त्रुटि: %s'

  menu-slot-out-of-bounds: '%s मेनू पृष्ठ बटन स्लॉट(स) सीमाओं के बाहर हैं!'

  invalid-hex-code: 'अमान्य hex कोड: %s'
```
{% endcode %}

### Croatian (Croatia)

{% code title="hr_HR.yml" %}
```yaml
messages:
  prefix: '<gradient:#ff00cc:#5555ff>[Bloons]</gradient> <white>'
  no-permission: '<#fc1c1c>Nema dopuštenja.'
  player-not-found: '<#fc1c1c>Igrač nije pronađen.'
  config-reloaded: '<green>Konfiguracija je ponovno učitana.'
  command-disabled: '<#fc1c1c>Ova naredba je trenutno onemogućena!'

  equipped: '%s <green>opremljen!'
  unequipped: '<green>Vaš balon je sigurno pohranjen.'
  balloon-not-found: '<#fc1c1c>Balon nije pronađen.'
  not-equipped: '<#fc1c1c>Trenutno nemate opremljen balon.'

  material-not-dyeable: 'Materijal %s nije moguće obojiti.'
  invalid-rgb-values: 'RGB vrijednosti moraju biti između 0 i 255 da bi bile valjane.'
  balloon-not-set: 'Balon %s nije postavljen u konfiguraciji!'
  material-not-set: 'Materijal balona %s nije postavljen u konfiguraciji!'
  material-not-valid: 'Materijal balona %s nije valjan materijal! Materijal: %s'
  material-is-not-valid: 'Materijal %s nije valjan materijal!'
  invalid-item-meta: 'ItemMeta nije valjan za materijal: %s'

  no-balloons-registered: 'Nema registriranih balona! Ne može se stvoriti izbornik bez balona.'

  configuration-folder-not-found: 'Mapa konfiguracije nije pronađena: %s'
  no-configuration-files-found: 'Nema pronađenih konfiguracijskih datoteka u mapi: %s'
  configuration-section-not-found: 'Sekcija konfiguracije nije pronađena za datoteku: %s'
  balloon-type-not-found: 'Pogreška pri obradi vrste balona za odjeljak: %s u datoteci: %s. Vrsta balona ne postoji ili je prazna.'
  balloon-process-error: 'Pogreška pri obradi balona za odjeljak: %s u datoteci: %s. Greška: %s'

  menu-slot-out-of-bounds: '%s gumbi stranice izbornika izvan granica!'

  invalid-hex-code: 'Nevažeći heksadecimalni kod: %s'
```
{% endcode %}

### Hungarian (Hungary)

{% code title="hu_HU.yml" %}
```yaml
messages:
  prefix: '<gradient:#ff00cc:#5555ff>[Bloons]</gradient> <white>'
  no-permission: '<#fc1c1c>Hozzáférés megtagadva.'
  player-not-found: '<#fc1c1c>A játékos nem található.'
  config-reloaded: '<green>A konfiguráció újratöltve.'
  command-disabled: '<#fc1c1c>Ez a parancs jelenleg letiltva van!'

  equipped: '%s <green>felszerelve!'
  unequipped: '<green>A lufid biztonságosan eltárolva.'
  balloon-not-found: '<#fc1c1c>A lufi nem található.'
  not-equipped: '<#fc1c1c>Jelenleg nincs felszerelve lufi.'

  material-not-dyeable: 'Az anyag %s nem festhető.'
  invalid-rgb-values: 'Az RGB értékeknek 0 és 255 között kell lenniük.'
  balloon-not-set: 'A %s lufi nincs beállítva a konfigurációban!'
  material-not-set: 'A %s lufi anyaga nincs beállítva a konfigurációban!'
  material-not-valid: 'A %s lufi anyaga nem érvényes anyag! Anyag: %s'
  material-is-not-valid: 'Az anyag %s nem érvényes anyag!'
  invalid-item-meta: 'Az ItemMeta nem érvényes az anyaghoz: %s'

  no-balloons-registered: 'Nincsenek regisztrált lufik! Nem lehet menüt létrehozni regisztrált lufik nélkül.'

  configuration-folder-not-found: 'A konfigurációs mappa nem található: %s'
  no-configuration-files-found: 'Nincsenek konfigurációs fájlok a mappában: %s'
  configuration-section-not-found: 'A konfigurációs szakasz nem található a fájlhoz: %s'
  balloon-type-not-found: 'Hiba a lufi típusának feldolgozásakor a szakaszhoz: %s a fájlban: %s. A lufi típusa nem létezik vagy null.'
  balloon-process-error: 'Hiba a lufi feldolgozásakor a szakaszhoz: %s a fájlban: %s. Hiba: %s'

  menu-slot-out-of-bounds: '%s menü oldal gomb hely nincs határokon belül!'

  invalid-hex-code: 'Érvénytelen hex kód: %s'
```
{% endcode %}

### Armenian (Armenia)

{% code title="hy_AM.yml" %}
```yaml
messages:
  prefix: '<gradient:#ff00cc:#5555ff>[Bloons]</gradient> <white>'
  no-permission: '<#fc1c1c>Թույլատրելիություն չկա.'
  player-not-found: '<#fc1c1c>Հաստատիչը չի գտնվել.'
  config-reloaded: '<green>Կոնֆիգուրացիան վերաբեռնվել է:'
  command-disabled: '<#fc1c1c>Այս հրամանը ներկայացնված չէ։'

  equipped: '%s <green>հավաքվեց։'
  unequipped: '<green>Ձեր բլունը անվանակում է ապակում։'
  balloon-not-found: '<#fc1c1c>Բլունը չի գտնվել։'
  not-equipped: '<#fc1c1c>Դուք ներկայացրել չունեք բլուն։'

  material-not-dyeable: 'Մատիան %s չի կարող նվագել։'
  invalid-rgb-values: 'RGB արժեքները պետք է լինեն 0-ից 255 միջակայքում։'
  balloon-not-set: 'Բլունը %s չի սահմանված կոնֆիգուրացիայում։'
  material-not-set: 'Բլունի %s մարմինը չի սահմանված կոնֆիգուրացիայում։'
  material-not-valid: 'Բլունի %s մարմինը վավեր չէ։ Մարմինը: %s'
  material-is-not-valid: 'Մատիան %s վավեր չէ։'
  invalid-item-meta: 'Ապրանքի մետատվյալները չեն վավերացիայի %s համար։'

  no-balloons-registered: 'Ոչ մի բլուն չի գրանցվել։ Չհաջողվեց ստեղծել ընտրացանկ առանց բլուն։'

  configuration-folder-not-found: 'Կոնֆիգուրացիայի թղթապանակը չի գտնվել՝ %s'
  no-configuration-files-found: 'Չի գտնվել կոնֆիգուրացիայի ֆայլեր %s թղթապանակում։'
  configuration-section-not-found: 'Կոնֆիգուրացիայի բաժնի գտնվելը չհաջողվեց ֆայլում՝ %s'
  balloon-type-not-found: 'Բլունի տեսակի սխալ մշակման համար բաժինը՝ %s, ֆայլում՝ %s։ Բլունի տեսակը չկա կամ դա դատարկ է։'
  balloon-process-error: 'Բլունի մշակման սխալ համար բաժինը՝ %s, ֆայլում՝ %s։ Սխալ՝ %s'

  menu-slot-out-of-bounds: '%s ընտրացանկի էջի կոճակի տեղերը շարունակվում են առանց պահի։'

  invalid-hex-code: 'Անվավեր հեքս կոդ՝ %s'
```
{% endcode %}

### Indonesian (Indonesia)

{% code title="id_ID.yml" %}
```yaml
messages:
  prefix: '<gradient:#ff00cc:#5555ff>[Bloons]</gradient> <white>'
  no-permission: '<#fc1c1c>Akses ditolak.'
  player-not-found: '<#fc1c1c>Pemain tidak ditemukan.'
  config-reloaded: '<green>Konfigurasi dimuat ulang.'
  command-disabled: '<#fc1c1c>Perintah ini saat ini dinonaktifkan!'

  equipped: '%s <green>terpasang!'
  unequipped: '<green>Balon Anda telah disimpan dengan aman.'
  balloon-not-found: '<#fc1c1c>Balon tidak ditemukan.'
  not-equipped: '<#fc1c1c>Anda saat ini tidak memiliki balon terpasang.'

  material-not-dyeable: 'Material %s tidak dapat diwarnai.'
  invalid-rgb-values: 'Nilai RGB harus antara 0 dan 255 untuk valid.'
  balloon-not-set: 'Balon %s tidak diatur dalam konfigurasi!'
  material-not-set: 'Material balon %s tidak diatur dalam konfigurasi!'
  material-not-valid: 'Material balon %s bukan material yang valid! Material: %s'
  material-is-not-valid: 'Material %s bukan material yang valid!'
  invalid-item-meta: 'ItemMeta tidak valid untuk material: %s'

  no-balloons-registered: 'Tidak ada balon yang terdaftar! Tidak dapat membuat menu tanpa balon.'

  configuration-folder-not-found: 'Folder konfigurasi tidak ditemukan: %s'
  no-configuration-files-found: 'Tidak ada file konfigurasi yang ditemukan di folder: %s'
  configuration-section-not-found: 'Bagian konfigurasi tidak ditemukan untuk file: %s'
  balloon-type-not-found: 'Kesalahan saat memproses jenis balon untuk bagian: %s di file: %s. Jenis balon tidak ada atau null.'
  balloon-process-error: 'Kesalahan saat memproses balon untuk bagian: %s di file: %s. Kesalahan: %s'

  menu-slot-out-of-bounds: '%s slot tombol halaman menu di luar batas!'

  invalid-hex-code: 'Kode hex tidak valid: %s'
```
{% endcode %}

### Icelandic (Iceland)

{% code title="is_IS.yml" %}
```yaml
messages:
  prefix: '<gradient:#ff00cc:#5555ff>[Bloons]</gradient> <white>'
  no-permission: '<#fc1c1c>Áður hefur verið óheimilt.'
  player-not-found: '<#fc1c1c>Leikmaður fannst ekki.'
  config-reloaded: '<green>Stillingar hlaðnar aftur inn.'
  command-disabled: '<#fc1c1c>Þessi skipun er í augnablikinu óvirk!'

  equipped: '%s <green>búið til!'
  unequipped: '<green>Loftbelgurinn þinn hefur verið geymdur örugglega.'
  balloon-not-found: '<#fc1c1c>Loftbelgur fannst ekki.'
  not-equipped: '<#fc1c1c>Þú ert ekki með loftbelg búinn að gera ráð fyrir þig.'

  material-not-dyeable: 'Efnið %s er ekki litarefni.'
  invalid-rgb-values: 'RGB gildin verða að vera á milli 0 og 255 til að vera gild gildi.'
  balloon-not-set: '%s loftbelgurinn er ekki settur í stillingunni!'
  material-not-set: '%s loftbelgurinn er ekki settur í efni í stillingunni!'
  material-not-valid: '%s loftbelgurinn er ekki gilt efni! Efni: %s'
  material-is-not-valid: 'Efnið %s er ekki gilt efni!'
  invalid-item-meta: 'ItemMeta er ekki gilt fyrir efnið: %s'

  no-balloons-registered: 'Engir loftbelgar eru skráðir! Ekki hægt að búa til valmynd án loftbelga.'

  configuration-folder-not-found: 'Stillingarmappa fannst ekki: %s'
  no-configuration-files-found: 'Engar stillingarskrár fundust í möppunni: %s'
  configuration-section-not-found: 'Stillingarsekt fannst ekki fyrir skrá: %s'
  balloon-type-not-found: 'Villa við að vinna með loftbelg tegund fyrir hluta: %s í skrá: %s. Loftbelgur tegund er ekki til eða er tómur.'
  balloon-process-error: 'Villa við að vinna loftbelg fyrir hluta: %s í skrá: %s. Villa: %s'

  menu-slot-out-of-bounds: '%s valmynd síðuhnappur staðsetning er utan marka!'

  invalid-hex-code: 'Ógild hex kóði: %s'
```
{% endcode %}

### Italian (Italy)

{% code title="it_IT.yml" %}
```yaml
messages:
  prefix: '<gradient:#ff00cc:#5555ff>[Bloons]</gradient> <white>'
  no-permission: '<#fc1c1c>Accesso negato.'
  player-not-found: '<#fc1c1c>Giocatore non trovato.'
  config-reloaded: '<green>Configurazione ricaricata.'
  command-disabled: '<#fc1c1c>Questo comando è attualmente disabilitato!'

  equipped: '%s <green>equipaggiato!'
  unequipped: '<green>Il tuo palloncino è stato riposto in sicurezza.'
  balloon-not-found: '<#fc1c1c>Palloncino non trovato.'
  not-equipped: '<#fc1c1c>Al momento non hai un palloncino equipaggiato.'

  material-not-dyeable: 'Il materiale %s non è tinto.'
  invalid-rgb-values: 'I valori RGB devono essere compresi tra 0 e 255 per essere validi.'
  balloon-not-set: 'Il palloncino %s non è impostato nella configurazione!'
  material-not-set: 'Il materiale del palloncino %s non è impostato nella configurazione!'
  material-not-valid: 'Il materiale del palloncino %s non è un materiale valido! Materiale: %s'
  material-is-not-valid: 'Il materiale %s non è un materiale valido!'
  invalid-item-meta: 'ItemMeta non è valido per il materiale: %s'

  no-balloons-registered: 'Nessun palloncino registrato! Impossibile creare un menu senza palloncini.'

  configuration-folder-not-found: 'Cartella di configurazione non trovata: %s'
  no-configuration-files-found: 'Nessun file di configurazione trovato nella cartella: %s'
  configuration-section-not-found: 'Sezione di configurazione non trovata per il file: %s'
  balloon-type-not-found: "Errore durante l'elaborazione del tipo di palloncino per la sezione: %s nel file: %s. Il tipo di palloncino non esiste o è nullo."
  balloon-process-error: "Errore durante l'elaborazione del palloncino per la sezione: %s nel file: %s. Errore: %s"

  menu-slot-out-of-bounds: '%s slot pulsante della pagina del menu fuori limite!'

  invalid-hex-code: 'Codice esadecimale non valido: %s'
```
{% endcode %}

### Georgian (Georgia)

{% code title="ka_GE.yml" %}
```yaml
messages:
  prefix: '<gradient:#ff00cc:#5555ff>[Bloons]</gradient> <white>'
  no-permission: '<#fc1c1c>არაა ნებართვა.'
  player-not-found: '<#fc1c1c>მოთამაშე არ მოიძებნა.'
  config-reloaded: '<green>კონფიგურაცია გადატვირთულია.'
  command-disabled: '<#fc1c1c>ეს ბრძანება ამჟამად გამორთულია!'

  equipped: '%s <green>შედეგიდან ჩამორთულია!'
  unequipped: '<green>თქვენი ბურთი დაშენახულია უსაფრთხოდ.'
  balloon-not-found: '<#fc1c1c>ბურთი ვერ მოიძებნა.'
  not-equipped: '<#fc1c1c>თქვენ ამჟამად არ გაქვთ დამორჩილებული ბურთი.'

  material-not-dyeable: 'მასალა %s არ შეიძლება გათვლდეს.'
  invalid-rgb-values: 'RGB მნიშვნელობები უნდა იყოს 0-დან 255-მდე, რათა იყოს სწორი.'
  balloon-not-set: 'ბურთი %s არ არის დაყენებული კონფიგურაციაში!'
  material-not-set: 'ბურთის მასალა %s არ არის დაყენებული კონფიგურაციაში!'
  material-not-valid: 'ბურთის მასალა %s არ არის მართებული! მასალა: %s'
  material-is-not-valid: 'მასალა %s არ არის მართებული!'
  invalid-item-meta: 'ItemMeta არ არის მასალათვის: %s'

  no-balloons-registered: 'ბურთები არ მოიძებნა! მენიუ ვერ შეიქმნა ბურთების გარეშე.'

  configuration-folder-not-found: 'კონფიგურაციის საქაღალდე არ მოიძებნა: %s'
  no-configuration-files-found: 'კონფიგურაციის ფაილები არ მოიძებნა საქაღალდეში: %s'
  configuration-section-not-found: 'კონფიგურაციის სექცია არ მოიძებნა ფაილისთვის: %s'
  balloon-type-not-found: 'ბურთის ტიპის დამუშავების შეცდომა სექციისთვის: %s ფაილში: %s. ბურთის ტიპი არ არსებობს ან იქნა ცარიელი.'
  balloon-process-error: 'ბურთის დამუშავების შეცდომა სექციისთვის: %s ფაილში: %s. შეცდომა: %s'

  menu-slot-out-of-bounds: '%s მენიუს გვერდის ღილაკი(ები) გარეთ ზღვაში!'

  invalid-hex-code: 'არასწორი hex კოდი: %s'
```
{% endcode %}

### Kazakh (Kazakhstan)

{% code title="kk_KZ.yml" %}
```yaml
messages:
  prefix: '<gradient:#ff00cc:#5555ff>[Bloons]</gradient> <white>'
  no-permission: '<#fc1c1c>Кіру расталған жоқ.'
  player-not-found: '<#fc1c1c>Ойыншы табылмады.'
  config-reloaded: '<green>Конфигурация қайта жүктелді.'
  command-disabled: '<#fc1c1c>Бұл команда қазір өшірілген!'

  equipped: '%s <green>орнатылды!'
  unequipped: '<green>Сіздің шарыңыз қауіпсіз сақталды.'
  balloon-not-found: '<#fc1c1c>Шар табылмады.'
  not-equipped: '<#fc1c1c>Қазір сізде орнатылған шар жоқ.'

  material-not-dyeable: '%s материалды боялау мүмкін емес.'
  invalid-rgb-values: 'RGB мәндері 0 және 255 арасында болуы керек.'
  balloon-not-set: '%s шар конфигурацияда орнатылмаған!'
  material-not-set: '%s шар материалы конфигурацияда орнатылмаған!'
  material-not-valid: '%s шар материалы жарамсыз материал емес! Материал: %s'
  material-is-not-valid: '%s материалы жарамсыз материал емес!'
  invalid-item-meta: 'ItemMeta материалға жарамсыз: %s'

  no-balloons-registered: 'Шығарушылар тіркеулі емес! Шарларсыз мәзір жасау мүмкін емес.'

  configuration-folder-not-found: 'Конфигурация қалтасы табылмады: %s'
  no-configuration-files-found: 'Конфигурация файлдары табылмады: %s папкада жоқ'
  configuration-section-not-found: 'Файл үшін конфигурация бөлімі табылмады: %s'
  balloon-type-not-found: 'Бөлім: %s файл: %s үшін шар түрін өңдеу кезінде қате пайда болды. Шар түрі жоқ немесе бос.'
  balloon-process-error: 'Бөлім: %s файл: %s үшін шарды өңдеу кезінде қате пайда болды. Қате: %s'

  menu-slot-out-of-bounds: '%s меню бет батырма орындары шектеуден тыс!'

  invalid-hex-code: 'Жарамсыз қиылмашы код: %s'
```
{% endcode %}

### Kannada (India)

{% code title="kn_IN.yml" %}
```yaml
messages:
  prefix: '<gradient:#ff00cc:#5555ff>[Bloons]</gradient> <white>'
  no-permission: '<#fc1c1c>ಪ್ರವೇಶ ನಿರಾಕರಿಸಲಾಗಿದೆ.'
  player-not-found: '<#fc1c1c>ಆಟಗಾರ ಕಂಡುಬರಲಿಲ್ಲ.'
  config-reloaded: '<green>ಕಾನ್ಫಿಗರೇಷನ್ ಮರುಹೊಂದಿಸಲಾಗಿದೆ.'
  command-disabled: '<#fc1c1c>ಈ ಕಮಾಂಡ್ ಪ್ರಸ್ತುತವಾಗಿ ನಿಷೇಧಿಸಲಾಗಿದೆ!'

  equipped: '%s <green>ಅಣಿಮಾಡಲಾಗಿದೆ!'
  unequipped: '<green>ನಿಮ್ಮ ಬಲೂನ್ ಸುರಕ್ಷಿತವಾಗಿ ಸಂಗ್ರಹಿತವಾಗಿದೆ.'
  balloon-not-found: '<#fc1c1c>ಬಲೂನ್ ಸಿಗಲಿಲ್ಲ.'
  not-equipped: '<#fc1c1c>ನೀವು ಪ್ರಸ್ತುತವಾಗಿ ಯಾವುದೇ ಬಲೂನ್ ಅಣಿಯಲಾಗಿಲ್ಲ.'

  material-not-dyeable: 'ತರಹದ %s ಬಣ್ಣಿಸಲು ಸಾಧ್ಯವಿಲ್ಲ.'
  invalid-rgb-values: 'RGB ಮೌಲ್ಯಗಳು 0 ಮತ್ತು 255 ನಡುವೆ ಇರಬೇಕು ಅಥವಾ ಮಾನ್ಯವಿರಬೇಕು.'
  balloon-not-set: 'ಬಲೂನ್ %s ಆಕೃತಿಯಲ್ಲಿ ಹೊಂದಲ್ಪಡಿಲ್ಲ!'
  material-not-set: 'ಬಲೂನ್ %s ಆಕೃತಿಯ ಬಲೂನ್ ಅನಾಯಕ್ತವಾಗಿದೆ!'
  material-not-valid: 'ಬಲೂನ್ %s ಆಕೃತಿಯ ಬಲೂನ್ ಅಮಾನ್ಯ ವಸ್ತು! ವಸ್ತು: %s'
  material-is-not-valid: '%s ವಸ್ತು ಅಮಾನ್ಯ ವಸ್ತು ಅಥವಾ ಖಾಲಿ ಇದೆ!'
  invalid-item-meta: 'ಐಟಂಮೇಟಾ ಬಲೂನ್ ಅನಾಯಕ್ತವಾಗಿದೆ: %s'

  no-balloons-registered: 'ಯಾವುದೇ ಬಲೂನ್‌ಗಳು ನೋಂದಿಗೆಯಾಗಿಲ್ಲ! ಬಲೂನ್‌ಗಳಿಲ್ಲದೆ ಮೆನು ರಚಿಸಲಾಗಿಲ್ಲ.'

  configuration-folder-not-found: 'ಆಕೃತಿ ಫೋಲ್ಡರ್ ಸಿಗಲಿಲ್ಲ: %s'
  no-configuration-files-found: 'ಫೋಲ್ಡರ್‌ನಲ್ಲಿ ಯಾವುದೇ ಆಕೃತಿ ಫೈಲ್‌ಗಳು ಸಿಗಲಿಲ್ಲ: %s'
  configuration-section-not-found: 'ಫೈಲ್‌ಗಾಗಿ ಆಕೃತಿ ವಿಭಾಗ ಸಿಗಲಿಲ್ಲ: %s'
  balloon-type-not-found: 'ಪ್ರಕಾರ ಸಿಗಲಿಲ್ಲ ಅಥವಾ ಖಾಲಿ ಆಗಿದೆ: %s ಫೈಲ್‌ನಲ್ಲಿ %s ವಿಭಾಗಕ್ಕಾಗಿ ಬಲೂನ್ ಪ್ರಕ್ರಿಯೆ ತಪ್ಪಾಗಿದೆ.'
  balloon-process-error: 'ಬಲೂನ್ ವಿಭಾಗಕ್ಕಾಗಿ %s ಫೈಲ್‌ನಲ್ಲಿ %s ಬಲೂನ್ ಪ್ರಕ್ರಿಯೆ ತಪ್ಪಾಗಿದೆ. ತಪ್ಪು: %s'

  menu-slot-out-of-bounds: '%s ಮೆನು ಪುಟ ಬಟನ್ ಸ್ಲಾಟ್‌ಗಳು ಗರಿಷ್ಠ ಮಿತಿಯ ಹೊರಗಿವೆ!'

  invalid-hex-code: 'ಅಮಾನ್ಯ ಹೆಕ್ಸ್ ಕೋಡ್: %s'
```
{% endcode %}

### Konkani (India)

{% code title="kok_IN.yml" %}
```yaml
messages:
  prefix: '<gradient:#ff00cc:#5555ff>[Bloons]</gradient> <white>'
  no-permission: '<#fc1c1c>परवानगी नको.'
  player-not-found: '<#fc1c1c>खेळाडू सापडला नाही.'
  config-reloaded: '<green>कॉनफिगरेशन पुन्हा लोड केली.'
  command-disabled: '<#fc1c1c>हे कमांड आत्ता अक्षम आहे!'

  equipped: '%s <green>थांबलेला आहे!'
  unequipped: '<green>तुमचा गुबांस सुरक्षितरित्या जतन केला गेला आहे.'
  balloon-not-found: '<#fc1c1c>गुबांस सापडला नाही.'
  not-equipped: '<#fc1c1c>आत्ता तुमच्याकडे कोणतेही थांबलेले गुबांस नाही.'

  material-not-dyeable: 'मटेरियल %s रंगण योग्य नाही.'
  invalid-rgb-values: 'RGB मूल्ये 0 आणि 255 यांच्यात असाव्याचे आवश्यक आहेत.'
  balloon-not-set: '%s गुबांस सेट केलेला नाही!'
  material-not-set: '%s गुबांसचा सामग्री कॉनफिगरेशनमध्ये सेट केलेला नाही!'
  material-not-valid: '%s गुबांसचा सामग्री अवैध सामग्री आहे! सामग्री: %s'
  material-is-not-valid: '%s सामग्री अवैध सामग्री नाही!'
  invalid-item-meta: 'आयटममेटा सामग्र्यासाठी अवैध आहे: %s'

  no-balloons-registered: 'कोणत्याही गुबांस नोंदविल्या नाहीत! गुबांस बिना मेनू तयार करणे असंभव आहे.'

  configuration-folder-not-found: 'कॉनफिगरेशन फोल्डर सापडला नाही: %s'
  no-configuration-files-found: 'कॉनफिगरेशन फाइल सापडली नाही: %s'
  configuration-section-not-found: 'फाइलसाठी कॉनफिगरेशन खंड सापडला नाही: %s'
  balloon-type-not-found: 'विभाग: %s फाईल: %s साठी गुबांस प्रकार प्रोसेसिंग करण्यात त्रुटी आली. गुबांस प्रकार अस्तित्वात नाही किंवा रिक्त आहे.'
  balloon-process-error: 'विभाग: %s फाईल: %s साठी गुबांस प्रोसेसिंग करण्यात त्रुटी आली. त्रुटी: %s'

  menu-slot-out-of-bounds: '%s मेनू पृष्ठ बटण स्लॉट सीमेत आहेत!'

  invalid-hex-code: 'अवैध हेक्स कोड: %s'
```
{% endcode %}

### Lithuanian (Lithuania)

{% code title="lt_LT.yml" %}
```yaml
messages:
  prefix: '<gradient:#ff00cc:#5555ff>[Bloons]</gradient> <white>'
  no-permission: '<#fc1c1c>Prieiga uždrausta.'
  player-not-found: '<#fc1c1c>Žaidėjas nerastas.'
  config-reloaded: '<green>Konfigūracija įkelta iš naujo.'
  command-disabled: '<#fc1c1c>Ši komanda šiuo metu išjungta!'

  equipped: '%s <green>įrengtas!'
  unequipped: '<green>Jūsų balionas buvo saugiai padėtas.'
  balloon-not-found: '<#fc1c1c>Balionas nerastas.'
  not-equipped: '<#fc1c1c>Jūs šiuo metu neturite įrengto baliono.'

  material-not-dyeable: 'Medžiaga %s negali būti nudažyta.'
  invalid-rgb-values: 'RGB reikšmės turi būti tarp 0 ir 255, kad būtų galiojančios.'
  balloon-not-set: 'Balionas %s neįrengtas konfigūracijoje!'
  material-not-set: 'Baliono %s medžiaga nėra nustatyta konfigūracijoje!'
  material-not-valid: 'Baliono %s medžiaga nėra galiojanti! Medžiaga: %s'
  material-is-not-valid: 'Medžiaga %s nėra galiojanti medžiaga!'
  invalid-item-meta: 'Elemento meta nėra galiojanti medžiagai: %s'

  no-balloons-registered: 'Nėra užregistruota jokių balionų! Negalima sukurti meniu be balionų.'

  configuration-folder-not-found: 'Konfigūracijos aplankas nerastas: %s'
  no-configuration-files-found: 'Konfigūracijos failų nerasta aplanke: %s'
  configuration-section-not-found: 'Konfigūracijos skyriaus nerasta failui: %s'
  balloon-type-not-found: 'Klaida apdorojant baliono tipą skyriui: %s faile: %s. Baliono tipas neegzistuoja arba yra nulinis.'
  balloon-process-error: 'Klaida apdorojant balioną skyriui: %s faile: %s. Klaida: %s'

  menu-slot-out-of-bounds: '%s meniu puslapio mygtukų slotų yra už ribų!'

  invalid-hex-code: 'Netinkamas heksadinis kodas: %s'
```
{% endcode %}

### Latvian (Latvia)

{% code title="lv_LV.yml" %}
```yaml
messages:
  prefix: '<gradient:#ff00cc:#5555ff>[Bloons]</gradient> <white>'
  no-permission: '<#fc1c1c>Piekļuve liegta.'
  player-not-found: '<#fc1c1c>Spēlētājs nav atrasts.'
  config-reloaded: '<green>Konfigurācija pārlādēta.'
  command-disabled: '<#fc1c1c>Šī komanda pašlaik ir atspējota!'

  equipped: '%s <green>izvēlēts!'
  unequipped: '<green>Jūsu gaisa balons ir droši saglabāts.'
  balloon-not-found: '<#fc1c1c>Gaisa balons nav atrasts.'
  not-equipped: '<#fc1c1c>Jums pašlaik nav neviena gaisa balona izvēlēta.'

  material-not-dyeable: 'Materiālu %s nevar nokrāsot.'
  invalid-rgb-values: 'RGB vērtībām jābūt starp 0 un 255, lai tās būtu derīgas.'
  balloon-not-set: '%s gaisa balons nav iestatīts konfigurācijā!'
  material-not-set: '%s gaisa balona materiāls nav iestatīts konfigurācijā!'
  material-not-valid: '%s gaisa balona materiāls nav derīgs! Materiāls: %s'
  material-is-not-valid: 'Materiāls %s nav derīgs materiāls!'
  invalid-item-meta: 'Priekšmets Meta nav derīgs materiālam: %s'

  no-balloons-registered: 'Nav reģistrēts neviens gaisa balons! Nevar izveidot izvēlni bez gaisa baloniem.'

  configuration-folder-not-found: 'Konfigurācijas mape nav atrasta: %s'
  no-configuration-files-found: 'Konfigurācijas faili nav atrasti mapē: %s'
  configuration-section-not-found: 'Konfigurācijas sadaļa nav atrasta failam: %s'
  balloon-type-not-found: 'Kļūda apstrādājot gaisa balona veidu sadaļai: %s failā: %s. Gaisa balona tips neeksistē vai ir nulle.'
  balloon-process-error: 'Kļūda apstrādājot gaisa balonu sadaļai: %s failā: %s. Kļūda: %s'

  menu-slot-out-of-bounds: '%s izvēlnes lapas pogu slots ir ārpus robežām!'

  invalid-hex-code: 'Nederīgs hex kods: %s'
```
{% endcode %}

### Macedonian (Macedonia)

{% code title="mk_MK.yml" %}
```yaml
messages:
  prefix: '<gradient:#ff00cc:#5555ff>[Bloons]</gradient> <white>'
  no-permission: '<#fc1c1c>Пристапот е забранет.'
  player-not-found: '<#fc1c1c>Играчот не е пронајден.'
  config-reloaded: '<green>Конфигурацијата е превчитана.'
  command-disabled: '<#fc1c1c>Оваа команда е исклучена во моментов!'

  equipped: '%s <green>опремен!'
  unequipped: '<green>Вашиот балон е безбедно зачуван.'
  balloon-not-found: '<#fc1c1c>Балонот не е пронајден.'
  not-equipped: '<#fc1c1c>Моментално немате опремен балон.'

  material-not-dyeable: 'Материјалот %s не може да се обои.'
  invalid-rgb-values: 'RGB вредностите мора да бидат помеѓу 0 и 255 за да бидат валидни.'
  balloon-not-set: 'Балонот %s не е поставен во конфигурацијата!'
  material-not-set: 'Материјалот на балонот %s не е поставен во конфигурацијата!'
  material-not-valid: 'Материјалот на балонот %s не е валиден! Материјал: %s'
  material-is-not-valid: 'Материјалот %s не е валиден материјал!'
  invalid-item-meta: 'ItemMeta не е валиден за материјалот: %s'

  no-balloons-registered: 'Не се регистрирани балони! Не може да се создаде мени без балони.'

  configuration-folder-not-found: 'Папката за конфигурација не е пронајдена: %s'
  no-configuration-files-found: 'Не се пронајдени конфигурациски датотеки во папката: %s'
  configuration-section-not-found: 'Секцијата за конфигурација не е пронајдена за датотеката: %s'
  balloon-type-not-found: 'Грешка при процесирањето на типот на балон за секцијата: %s во датотеката: %s. Типот на балон не постои или е нула.'
  balloon-process-error: 'Грешка при процесирањето на балон за секцијата: %s во датотеката: %s. Грешка: %s'

  menu-slot-out-of-bounds: '%s копчиња на страната на мениот се надвор од опсегот!'

  invalid-hex-code: 'Невалиден хекс код: %s'
```
{% endcode %}

### Malayalam (India)

{% code title="ml_IN.yml" %}
```yaml
messages:
  prefix: '<gradient:#ff00cc:#5555ff>[Bloons]</gradient> <white>'
  no-permission: '<#fc1c1c>അനുമതി നിരസ്കരിച്ചു.'
  player-not-found: '<#fc1c1c>കളിക്കാർ കണ്ടെത്തിയില്ല.'
  config-reloaded: '<green>കോൺഫിഗറേഷൻ പുനഃലോഡ് ചെയ്യപ്പെട്ടു.'
  command-disabled: '<#fc1c1c>ഈ കമാൻഡ് ഇപ്പോൾ നിരോധിച്ചിരിക്കുന്നു!'

  equipped: '%s <green>സജ്ജമാക്കി!'
  unequipped: '<green>നിങ്ങളുടെ ബൽലൂൺ സുരക്ഷിതമായി സംരക്ഷിക്കപ്പെട്ടു.'
  balloon-not-found: '<#fc1c1c>ബൽലൂൺ കണ്ടെത്തിയില്ല.'
  not-equipped: '<#fc1c1c>നിങ്ങൾക്ക് നിലവിലുള്ള ബൽലൂൺ ഇപ്പോൾ ലഭ്യമല്ല.'

  material-not-dyeable: 'ഉള്ളടക്കം %s എന്ന ഉള്ളടക്കം മണിച്ചുകൊടുക്കാം അല്ല.'
  invalid-rgb-values: 'RGB മൂല്യങ്ങൾ സാധുവായിരിക്കണം എന്നതിനാൽ 0 കുറവും 255 കൂടിയിരിക്കണം.'
  balloon-not-set: '%s ബൽലൂൺ കോൺഫിഗറേഷനിൽ സജ്ജമാക്കിയില്ല!'
  material-not-set: '%s ബൽലൂൺ ഉള്ളടക്കം കോൺഫിഗറേഷനിൽ സജ്ജമാക്കിയില്ല!'
  material-not-valid: '%s ബൽലൂൺ ഉള്ളടക്കം സാധുവായ ഉള്ളടക്കം അല്ല! ഉള്ളടക്കം: %s'
  material-is-not-valid: 'ഉള്ളടക്കം %s സാധുവായ ഉള്ളടക്കം അല്ല!'
  invalid-item-meta: 'ഉള്ളടക്കം മെറ്റ സാധുവായ ഉള്ളടക്കംകൊണ്ടില്ല: %s'

  no-balloons-registered: 'രജിസ്ട്രുചെയ്ത ബൽലൂൺ ഇല്ല! ബൽലൂൺസ് ഇല്ലാതെ ഒരു മെനു സൃഷ്ടിക്കാനായില്ല.'

  configuration-folder-not-found: 'കോൺഫിഗറേഷൻ ഫോൾഡർ കണ്ടെത്തിയില്ല: %s'
  no-configuration-files-found: 'ഫോൾഡർനിൽ കോൺഫിഗറേഷൻ ഫയലുകൾ കണ്ടെത്തിയില്ല: %s'
  configuration-section-not-found: 'ഫയൽക്ക് കോൺഫിഗറേഷൻ വിഭാഗം കണ്ടെത്തിയില്ല: %s'
  balloon-type-not-found: 'വിഭാഗത്തിനുള്ള ബൽലൂൺ തരത്തിന്റെ പ്രോസസ്സിംഗ് പിഴവ്: %s ഫയലിൽ: %s. ബൽലൂൺ തരം നിലവിലില്ല അല്ലെങ്കിൽ നൽകുന്നത് ശൂന്യമാണ്.'
  balloon-process-error: 'വിഭാഗത്തിനുള്ള ബൽലൂൺ പ്രോസസ്സിംഗിന് പിഴവ്: %s ഫയലിൽ: %s. പിഴവ്: %s'

  menu-slot-out-of-bounds: '%s മെനു പേജ് ബട്ടൺ സ്ലോട്ടുകൾ പരിധിയിൽ വിരുദ്ധമാണ്!'

  invalid-hex-code: 'അസാധുവായ ഹെക്സ് കോഡ്: %s'
```
{% endcode %}

### Mongolian (Mongolia)

{% code title="mn_MN.yml" %}
```yaml
messages:
  prefix: '<gradient:#ff00cc:#5555ff>[Bloons]</gradient> <white>'
  no-permission: '<#fc1c1c>Хандах эрх алгагүй.'
  player-not-found: '<#fc1c1c>Тоглогч олдсонгүй.'
  config-reloaded: '<green>Тохиргоо дахин татаж авлагдлаа.'
  command-disabled: '<#fc1c1c>Энэ комманд одоогоор идэвхгүй байна!'

  equipped: '%s <green>тохируулсан!'
  unequipped: '<green>Таны бөмбөг амжилттай хадгалагдсан байна.'
  balloon-not-found: '<#fc1c1c>Бөмбөг олдсонгүй.'
  not-equipped: '<#fc1c1c>Танд одоогоор суурилсан бөмбөг байхгүй байна.'

  material-not-dyeable: 'Материал %s харах боломжгүй.'
  invalid-rgb-values: 'RGB утгууд 0 ба 255 хооронд байх ёстой.'
  balloon-not-set: '%s бөмбөг тохиргоо дотор тохирохгүй байна!'
  material-not-set: '%s бөмбөгийн материал тохиргоо дотор тохирохгүй байна!'
  material-not-valid: '%s бөмбөгийн материал буруу бөгөөд! Материал: %s'
  material-is-not-valid: 'Материал %s буруу материал байна!'
  invalid-item-meta: 'ItemMeta %s материалд хүчин төгөлдөр биш байна.'

  no-balloons-registered: 'Тодорхойлолтоо хийгээгүй бөмбөг олдсонгүй! Бөмбөгтэй цэс үүсгэх боломжгүй.'

  configuration-folder-not-found: 'Тохиргоо хавтас олдсонгүй: %s'
  no-configuration-files-found: 'Тохиргоо файл олдсонгүй хавтас дотор: %s'
  configuration-section-not-found: 'Тохиргоо хэсэг олдсонгүй файлд: %s'
  balloon-type-not-found: 'Секц шинж чанарыг бөмбөг төрөлд байршуулахад алдаа гарлаа: %s файлаас: %s. Бөмбөгийн төрөл байхгүй буюу хоосон байна.'
  balloon-process-error: 'Секц бөмбөгийг боловсруулах үед алдаа гарлаа: %s файлаас: %s. Алдаа: %s'

  menu-slot-out-of-bounds: '%s цэсийн товчны слот баасан хязгаартай байна!'

  invalid-hex-code: 'Хүчин төгөлдөрт олдсонгүй хэкс код: %s'
```
{% endcode %}

### Marathi (India)

{% code title="mr_IN.yml" %}
```yaml
messages:
  prefix: '<gradient:#ff00cc:#5555ff>[Bloons]</gradient> <white>'
  no-permission: '<#fc1c1c>परवानगी नाकारली.'
  player-not-found: '<#fc1c1c>खेळाडू सापडला नाही.'
  config-reloaded: '<green>कॉन्फिगरेशन पुन्हा लोड केली गेली आहे.'
  command-disabled: '<#fc1c1c>ही कमाण्ड सध्या अक्षम केली आहे!'

  equipped: '%s <green>सज्ज झाला आहे!'
  unequipped: '<green>तुमचं गुब्बा सुरक्षितपणे संग्रहित केलं गेलं आहे.'
  balloon-not-found: '<#fc1c1c>गुब्बा सापडला नाही.'
  not-equipped: '<#fc1c1c>तुम्हाला सध्या कोणत्याही गुब्बा सज्ज नाही.'

  material-not-dyeable: 'सामग्री %s फेरफटकारण्यायोग्य नाही.'
  invalid-rgb-values: 'RGB मूल्ये 0 आणि 255 दरम्यान असणे आवश्यक आहेत.'
  balloon-not-set: '%s गुब्बा कॉन्फिगरेशनमध्ये सेट केलं नाही!'
  material-not-set: 'गुब्बा %s सामग्री कॉन्फिगरेशनमध्ये सेट केली नाही!'
  material-not-valid: 'गुब्बा %s सामग्री वैध नाही! सामग्री: %s'
  material-is-not-valid: 'सामग्री %s वैध सामग्री नाही!'
  invalid-item-meta: 'मदत मेटा %s सामग्रीसाठी वैध नाही.'

  no-balloons-registered: 'कोणतेही गुब्बे नोंदणीकृत नाहीत! गुब्बे विहित केल्याशिवाय मेनू तयार केले जाऊ शकत नाहीत.'

  configuration-folder-not-found: 'कॉन्फिगरेशन फोल्डर सापडला नाही: %s'
  no-configuration-files-found: 'कोणतेही कॉन्फिगरेशन फाइल सापडली नाही: %s'
  configuration-section-not-found: 'फाइलसाठी कॉन्फिगरेशन खंड सापडला नाही: %s'
  balloon-type-not-found: 'सेक्शनसाठी गुब्बा प्रकार प्रोसेसिंग त्रुटी: %s फाइलमध्ये: %s. गुब्बा प्रकार अस्तित्वात नाही किंवा शून्य आहे.'
  balloon-process-error: 'सेक्शनसाठी गुब्बा प्रोसेसिंग त्रुटी: %s फाइलमध्ये: %s. त्रुटी: %s'

  menu-slot-out-of-bounds: '%s मेनू पृष्ठ बटण स्लॉट सीमा उत्तीर्ण!'

  invalid-hex-code: "अवैध हेक्स कोड: %s"
```
{% endcode %}

### Malay (Malaysia)

{% code title="ms_MY.yml" %}
```yaml
messages:
  prefix: '<gradient:#ff00cc:#5555ff>[Bloons]</gradient> <white>'
  no-permission: '<#fc1c1c>Akses ditolak.'
  player-not-found: '<#fc1c1c>Pemain tidak dijumpai.'
  config-reloaded: '<green>Konfigurasi dimuat semula.'
  command-disabled: '<#fc1c1c>Perintah ini kini dinyahaktifkan!'

  equipped: '%s <green>dilengkapi!'
  unequipped: '<green>Belon anda telah disimpan dengan selamat.'
  balloon-not-found: '<#fc1c1c>Belon tidak dijumpai.'
  not-equipped: '<#fc1c1c>Anda kini tidak mempunyai belon yang dilengkapi.'

  material-not-dyeable: 'Bahan %s tidak boleh diwarnakan.'
  invalid-rgb-values: 'Nilai-nilai RGB mestilah antara 0 dan 255 untuk sah.'
  balloon-not-set: 'Belon %s tidak ditetapkan dalam konfigurasi!'
  material-not-set: 'Bahan belon %s tidak ditetapkan dalam konfigurasi!'
  material-not-valid: 'Bahan belon %s tidak sah! Bahan: %s'
  material-is-not-valid: 'Bahan %s bukan bahan yang sah!'
  invalid-item-meta: 'ItemMeta tidak sah untuk bahan: %s'

  no-balloons-registered: 'Tiada belon yang didaftarkan! Tidak dapat membuat menu tanpa belon.'

  configuration-folder-not-found: 'Folder konfigurasi tidak dijumpai: %s'
  no-configuration-files-found: 'Tiada fail konfigurasi dijumpai dalam folder: %s'
  configuration-section-not-found: 'Seksyen konfigurasi tidak dijumpai untuk fail: %s'
  balloon-type-not-found: 'Ralat semasa pemprosesan jenis belon untuk seksyen: %s dalam fail: %s. Jenis belon tidak wujud atau adalah null.'
  balloon-process-error: 'Ralat semasa pemprosesan belon untuk seksyen: %s dalam fail: %s. Ralat: %s'

  menu-slot-out-of-bounds: '%s slot butang halaman menu di luar batasannya!'

  invalid-hex-code: 'Kod heks tidak sah: %s'
```
{% endcode %}

### Maltese (Malta)

{% code title="mt_MT.yml" %}
```yaml
messages:
  prefix: '<gradient:#ff00cc:#5555ff>[Bloons]</gradient> <white>'
  no-permission: '<#fc1c1c>Aċċess imneħħi.'
  player-not-found: '<#fc1c1c>Lilek ma nstabx.'
  config-reloaded: '<green>Konfigurazzjoni riffriskata.'
  command-disabled: '<#fc1c1c>Din il-kommanda hija disattivata bħalissa!'

  equipped: '%s <green>imħallat!'
  unequipped: '<green>Il-ballun tiegħek ġie ssalvat b'sigurtà.'
  balloon-not-found: '<#fc1c1c>Ballun ma nstabx.'
  not-equipped: '<#fc1c1c>Inti bħalissa ma għandekx ballun imħallat.'

  material-not-dyeable: 'Il-materjal %s ma jistax jiġi maħżul.'
  invalid-rgb-values: 'Il-valuri RGB għandhom ikunu bejn 0 u 255 biex ikunu validi.'
  balloon-not-set: 'Il-ballun %s ma ġiex stabbilit fil-konfigurazzjoni!'
  material-not-set: 'Il-materjal tal-ballun %s ma ġie stabbilit fil-konfigurazzjoni!'
  material-not-valid: 'Il-materjal tal-ballun %s ma huwiex materjal validu! Materjal: %s'
  material-is-not-valid: 'Il-materjal %s ma huwiex materjal validu!'
  invalid-item-meta: 'ItemMeta mhix valida għal materjal: %s'

  no-balloons-registered: 'L-ebda balluni mregistra! Ma tistax toħloq menu bla balluni.'

  configuration-folder-not-found: 'Fowldier tal-konfigurazzjoni ma nstabx: %s'
  no-configuration-files-found: 'Ebda fajl tal-konfigurazzjoni ma nstabx fil-fowldier: %s'
  configuration-section-not-found: 'Seksjoni tal-konfigurazzjoni ma nstabx għall-fajl: %s'
  balloon-type-not-found: 'Żballun tal-tip mhux matmati għas-sezzjoni: %s fil-fajl: %s. It-tip tal-ballun ma jeżistix jew huwa null.'
  balloon-process-error: "Żballun ta' l-proċessar għas-sezzjoni: %s fil-fajl: %s. Żballun processa l-ħażin: %s"

  menu-slot-out-of-bounds: '%s slot tal-paġna tal-meni huwa barra mill-limiti!'

  invalid-hex-code: 'Kodiċi heksa invalidu: %s'
```
{% endcode %}

### Norwegian Bokmål (Norway)

{% code title="nb_NO.yml" %}
```yaml
messages:
  prefix: '<gradient:#ff00cc:#5555ff>[Bloons]</gradient> <white>'
  no-permission: '<#fc1c1c>Tilgang nektet.'
  player-not-found: '<#fc1c1c>Spilleren ble ikke funnet.'
  config-reloaded: '<green>Konfigurasjon lastet på nytt.'
  command-disabled: '<#fc1c1c>Dette kommandoen er for øyeblikket deaktivert!'

  equipped: '%s <green>utstyrt!'
  unequipped: '<green>Din ballong er nå trygt lagret.'
  balloon-not-found: '<#fc1c1c>Ballongen ble ikke funnet.'
  not-equipped: '<#fc1c1c>Du har for øyeblikket ingen ballong utstyrt.'

  material-not-dyeable: 'Materialet %s kan ikke farges.'
  invalid-rgb-values: 'RGB-verdiene må være mellom 0 og 255 for å være gyldige.'
  balloon-not-set: 'Ballongen %s er ikke satt i konfigurasjonen!'
  material-not-set: 'Materialet til ballongen %s er ikke satt i konfigurasjonen!'
  material-not-valid: 'Materialet til ballongen %s er ikke gyldig! Materiale: %s'
  material-is-not-valid: 'Materialet %s er ikke gyldig!'
  invalid-item-meta: 'ItemMeta er ikke gyldig for materialet: %s'

  no-balloons-registered: 'Ingen ballonger er registrert! Kan ikke opprette en meny uten ballonger.'

  configuration-folder-not-found: 'Konfigurasjonsmappen ble ikke funnet: %s'
  no-configuration-files-found: 'Ingen konfigurasjonsfiler ble funnet i mappen: %s'
  configuration-section-not-found: 'Konfigurasjonsdelen ble ikke funnet for filen: %s'
  balloon-type-not-found: 'Feil ved behandling av ballongtype for seksjon: %s i filen: %s. Ballongtypen eksisterer ikke eller er null.'
  balloon-process-error: 'Feil ved behandling av ballong for seksjon: %s i filen: %s. Feil: %s'

  menu-slot-out-of-bounds: '%s meny sideknapp(er) utenfor grensene!'

  invalid-hex-code: 'Ugyldig heksadesimal kode: %s'
```
{% endcode %}

### Dutch (Netherlands)

{% code title="nl_NL.yml" %}
```yaml
messages:
  prefix: '<gradient:#ff00cc:#5555ff>[Bloons]</gradient> <white>'
  no-permission: '<#fc1c1c>Geen toestemming.'
  player-not-found: '<#fc1c1c>Speler niet gevonden.'
  config-reloaded: '<green>Configuratie herladen.'
  command-disabled: '<#fc1c1c>Deze opdracht is momenteel uitgeschakeld!'

  equipped: '%s <green>uitgerust!'
  unequipped: '<green>Uw ballon is veilig opgeborgen.'
  balloon-not-found: '<#fc1c1c>Ballon niet gevonden.'
  not-equipped: '<#fc1c1c>U hebt momenteel geen ballon uitgerust.'

  material-not-dyeable: 'Materiaal %s kan niet geverfd worden.'
  invalid-rgb-values: 'RGB-waarden moeten tussen 0 en 255 liggen om geldig te zijn.'
  balloon-not-set: 'De ballon %s is niet ingesteld in de configuratie!'
  material-not-set: 'Het materiaal van de ballon %s is niet ingesteld in de configuratie!'
  material-not-valid: 'Het materiaal van de ballon %s is geen geldig materiaal! Materiaal: %s'
  material-is-not-valid: 'Materiaal %s is geen geldig materiaal!'
  invalid-item-meta: 'ItemMeta is niet geldig voor materiaal: %s'

  no-balloons-registered: 'Geen ballonnen geregistreerd! Kan geen menu maken zonder ballonnen.'

  configuration-folder-not-found: 'Configuratiemap niet gevonden: %s'
  no-configuration-files-found: 'Geen configuratiebestanden gevonden in de map: %s'
  configuration-section-not-found: 'Configuratiesectie niet gevonden voor bestand: %s'
  balloon-type-not-found: 'Fout bij verwerken van ballontype voor sectie: %s in bestand: %s. Ballontype bestaat niet of is leeg.'
  balloon-process-error: 'Fout bij verwerken van ballon voor sectie: %s in bestand: %s. Fout: %s'

  menu-slot-out-of-bounds: '%s menuknop(pen) buiten bereik!'

  invalid-hex-code: 'Ongeldige hexadecimale code: %s'
```
{% endcode %}

### Norwegian Nynorsk (Norway)

{% code title="nn_NO.yml" %}
```yaml
messages:
  prefix: '<gradient:#ff00cc:#5555ff>[Bloons]</gradient> <white>'
  no-permission: '<#fc1c1c>Tilgang nekta.'
  player-not-found: '<#fc1c1c>Spelaren vart ikkje funnen.'
  config-reloaded: '<green>Konfigurasjon lasta inn på nytt.'
  command-disabled: '<#fc1c1c>Denne kommandoen er for øyeblikket deaktivert!'

  equipped: '%s <green>utstyrte!'
  unequipped: '<green>Ballongen din er no trygt lagra.'
  balloon-not-found: '<#fc1c1c>Ballongen vart ikkje funnen.'
  not-equipped: '<#fc1c1c>Du har for øyeblikket ingen ballong utstyrt.'

  material-not-dyeable: 'Materialet %s kan ikkje fargestast.'
  invalid-rgb-values: 'RGB-verdiane må vere mellom 0 og 255 for å vere gyldige.'
  balloon-not-set: 'Ballongen %s er ikkje sett i konfigurasjonen!'
  material-not-set: 'Materialet til ballongen %s er ikkje sett i konfigurasjonen!'
  material-not-valid: 'Materialet til ballongen %s er ikkje gyldig! Materiale: %s'
  material-is-not-valid: 'Materialet %s er ikkje gyldig!'
  invalid-item-meta: 'ItemMeta er ikkje gyldig for materialet: %s'

  no-balloons-registered: 'Ingen ballongar er registrert! Kan ikkje opprette ei meny utan ballongar.'

  configuration-folder-not-found: 'Konfigurasjonsmappa vart ikkje funnen: %s'
  no-configuration-files-found: 'Ingen konfigurasjonsfiler vart funne i mappa: %s'
  configuration-section-not-found: 'Konfigurasjonsdelen vart ikkje funnen for fila: %s'
  balloon-type-not-found: 'Feil ved behandling av ballongtype for seksjon: %s i fila: %s. Ballongtypen eksisterer ikkje eller er null.'
  balloon-process-error: 'Feil ved behandling av ballong for seksjon: %s i fila: %s. Feil: %s'

  menu-slot-out-of-bounds: '%s meny sideknapp(ar) utanfor grensene!'

  invalid-hex-code: 'Ugyldig heksadesimal kode: %s'
```
{% endcode %}

### Punjabi (India)

{% code title="pa_IN.yml" %}
```yaml
messages:
  prefix: '<gradient:#ff00cc:#5555ff>[Bloons]</gradient> <white>'
  no-permission: '<#fc1c1c>ਪਹੁੰਚ ਨਹੀਂ ਦਿੱਤੀ.'
  player-not-found: '<#fc1c1c>ਖਿਡਾਰ ਨਹੀਂ ਲੱਭਿਆ.'
  config-reloaded: '<green>ਸੰਰਚਨਾ ਮੁੜ ਲੋਡ ਕੀਤੀ.'
  command-disabled: '<#fc1c1c>ਇਹ ਕਮਾਂਡ ਵਰਤਮਾਨ ਵਿੱਚ ਬੰਦ ਹੈ!'

  equipped: '%s <green>ਸਜਾਇਆ ਗਿਆ ਹੈ!'
  unequipped: '<green>ਤੁਹਾਡਾ ਗੁਬਾਰ ਸੁਰੱਖਿਆ ਨਾਲ ਭਰਾ ਗਿਆ ਹੈ.'
  balloon-not-found: '<#fc1c1c>ਗੁਬਾਰ ਨਹੀਂ ਲੱਭਿਆ.'
  not-equipped: '<#fc1c1c>ਤੁਹਾਡੇ ਕੋਲ ਵਰਤਮਾਨ ਵਿੱਚ ਕੋਈ ਗੁਬਾਰ ਨਹੀਂ ਹੈ.'

  material-not-dyeable: 'ਮਾਟੀ %s ਨੂੰ ਰੰਗਣਯੋਗ ਨਹੀਂ ਹੈ.'
  invalid-rgb-values: 'RGB ਮੁੱਲ 0 ਅਤੇ 255 ਵਿੱਚ ਹੀ ਮਾਨਯੋਗ ਹਨ.'
  balloon-not-set: '%s ਗੁਬਾਰ ਸੰਰਚਨਾ ਵਿੱਚ ਸੈੱਟ ਨਹੀਂ ਹੈ!'
  material-not-set: 'ਗੁਬਾਰ %s ਦੀ ਸਮਗਰੀ ਸੰਰਚਨਾ ਵਿੱਚ ਸੈੱਟ ਨਹੀਂ ਹੈ!'
  material-not-valid: 'ਗੁਬਾਰ %s ਦਾ ਸਮਗਰੀ ਮਾਨਯੋਗ ਨਹੀਂ ਹੈ! ਸਮਗਰੀ: %s'
  material-is-not-valid: 'ਮਾਟੀ %s ਮਾਨਯੋਗ ਨਹੀਂ ਹੈ!'
  invalid-item-meta: 'ਆਇਟਮਮੀਟਾ ਮਾਟੀ ਲਈ ਮਾਨਯੋਗ ਨਹੀਂ ਹੈ: %s'

  no-balloons-registered: 'ਕੋਈ ਗੁਬਾਰ ਰਜਿਸਟਰ ਨਹੀਂ ਹੋਈ! ਗੁਬਾਰ ਬਿਨਾਂ ਮੇਨੂ ਬਣਾਉਣਾ ਮੁਮਕਿਨ ਨਹੀਂ ਹੈ।'

  configuration-folder-not-found: 'ਸੰਰਚਨਾ ਫੋਲਡਰ ਨਹੀਂ ਮਿਲਿਆ: %s'
  no-configuration-files-found: 'ਕੋਈ ਸੰਰਚਨਾ ਫਾਈਲਾਂ ਫੋਲਡਰ ਵਿੱਚ ਨਹੀਂ ਮਿਲੀਆ: %s'
  configuration-section-not-found: 'ਫਾਈਲ ਲਈ ਸੰਰਚਨਾ ਖੰਡ ਨਹੀਂ ਮਿਲਿਆ: %s'
  balloon-type-not-found: 'ਸੈਕਸ਼ਨ ਲਈ ਗੁਬਾਰ ਕਿਸਮ ਪ੍ਰੋਸੈਸਿੰਗ ਵਿੱਚ ਗਲਤੀ ਹੋਈ ਹੈ: %s ਫਾਈਲ: %s। ਗੁਬਾਰ ਕਿਸਮ ਮੌਜੂਦ ਨਹੀਂ ਹੈ ਜਾਂ ਨਲ ਹੈ।'
  balloon-process-error: 'ਸੈਕਸ਼ਨ ਲਈ ਗੁਬਾਰ ਪ੍ਰੋਸੈਸਿੰਗ ਵਿੱਚ ਗਲਤੀ ਹੋਈ ਹੈ: %s ਫਾਈਲ: %s। ਗਲਤੀ: %s'

  menu-slot-out-of-bounds: '%s ਮੀਨੂ ਸਾਇਡ ਬਟਨ ਸਲੋਟ(ਸ) ਸੀਮਾਵਾਰ ਤੋਂ ਬਾਹਰ ਹਨ!'

  invalid-hex-code: 'ਗਲਤ ਹੈਕਸਾਡੇਸੀਮਲ ਕੋਡ: %s'
```
{% endcode %}

### Polish (Poland)

{% code title="pl_PL.yml" %}
```yaml
messages:
  prefix: '<gradient:#ff00cc:#5555ff>[Bloons]</gradient> <white>'
  no-permission: '<#fc1c1c>Brak uprawnień.'
  player-not-found: '<#fc1c1c>Nie znaleziono gracza.'
  config-reloaded: '<green>Konfiguracja została ponownie załadowana.'
  command-disabled: '<#fc1c1c>Ta komenda jest obecnie wyłączona!'

  equipped: '%s <green>wyposażony!'
  unequipped: '<green>Twój balon został teraz bezpiecznie przechowany.'
  balloon-not-found: '<#fc1c1c>Balon nie został znaleziony.'
  not-equipped: '<#fc1c1c>Nie masz obecnie wyposażonego balonu.'

  material-not-dyeable: 'Materiał %s nie może być farbowany.'
  invalid-rgb-values: 'Wartości RGB muszą być między 0 a 255, aby być prawidłowe.'
  balloon-not-set: 'Balon %s nie jest ustawiony w konfiguracji!'
  material-not-set: 'Materiał balonu %s nie jest ustawiony w konfiguracji!'
  material-not-valid: 'Materiał balonu %s nie jest prawidłowy! Materiał: %s'
  material-is-not-valid: 'Materiał %s nie jest prawidłowy!'
  invalid-item-meta: 'ItemMeta nie jest prawidłowy dla materiału: %s'

  no-balloons-registered: 'Nie zarejestrowano żadnych balonów! Nie można utworzyć menu bez balonów.'

  configuration-folder-not-found: 'Nie znaleziono folderu konfiguracji: %s'
  no-configuration-files-found: 'Nie znaleziono plików konfiguracyjnych w folderze: %s'
  configuration-section-not-found: 'Nie znaleziono sekcji konfiguracji dla pliku: %s'
  balloon-type-not-found: 'Błąd przetwarzania typu balonu dla sekcji: %s w pliku: %s. Typ balonu nie istnieje lub jest null.'
  balloon-process-error: 'Błąd przetwarzania balonu dla sekcji: %s w pliku: %s. Błąd: %s'

  menu-slot-out-of-bounds: '%s przycisk(i) strony menu poza zakresem!'

  invalid-hex-code: 'Nieprawidłowy kod szesnastkowy: %s'
```
{% endcode %}

### Romanian (Romania)

{% code title="ro_RO.yml" %}
```yaml
messages:
  prefix: '<gradient:#ff00cc:#5555ff>[Bloons]</gradient> <white>'
  no-permission: '<#fc1c1c>Acces interzis.'
  player-not-found: '<#fc1c1c>Jucătorul nu a fost găsit.'
  config-reloaded: '<green>Configurația a fost reîncărcată.'
  command-disabled: '<#fc1c1c>Această comandă este momentan dezactivată!'

  equipped: '%s <green>echipat!'
  unequipped: '<green>Balonul tău a fost stocat în siguranță.'
  balloon-not-found: '<#fc1c1c>Balonul nu a fost găsit.'
  not-equipped: '<#fc1c1c>Nu deții momentan un balon echipat.'

  material-not-dyeable: 'Materialul %s nu poate fi vopsit.'
  invalid-rgb-values: 'Valorile RGB trebuie să fie între 0 și 255 pentru a fi valide.'
  balloon-not-set: 'Balonul %s nu este setat în configurație!'
  material-not-set: 'Materialul balonului %s nu este setat în configurație!'
  material-not-valid: 'Materialul balonului %s nu este valid! Material: %s'
  material-is-not-valid: 'Materialul %s nu este valid!'
  invalid-item-meta: 'ItemMeta nu este valid pentru materialul: %s'

  no-balloons-registered: 'Nu sunt baloane înregistrate! Nu se poate crea un meniu fără baloane.'

  configuration-folder-not-found: 'Folderul de configurare nu a fost găsit: %s'
  no-configuration-files-found: 'Nu s-au găsit fișiere de configurare în folder: %s'
  configuration-section-not-found: 'Secțiunea de configurare nu a fost găsită pentru fișier: %s'
  balloon-type-not-found: 'Eroare la procesarea tipului de balon pentru secțiunea: %s în fișier: %s. Tipul de balon nu există sau este nul.'
  balloon-process-error: 'Eroare la procesarea balonului pentru secțiunea: %s în fișier: %s. Eroare: %s'

  menu-slot-out-of-bounds: '%s sloturi de butoane de pagină meniu depășesc limitele!'

  invalid-hex-code: 'Cod hexazecimal invalid: %s'
```
{% endcode %}

### Northern Sami (Norway)

{% code title="se_NO.yml" %}
```yaml
messages:
  prefix: '<gradient:#ff00cc:#5555ff>[Bloons]</gradient> <white>'
  no-permission: '<#fc1c1c>Tillatelse nektet.'
  player-not-found: '<#fc1c1c>Spiller ikke funnet.'
  config-reloaded: '<green>Konfigurasjon lastet på nytt.'
  command-disabled: '<#fc1c1c>Dette kommandoen er for øyeblikket deaktivert!'

  equipped: '%s <green>utstyrt!'
  unequipped: '<green>Din ballong er nå trygt lagret.'
  balloon-not-found: '<#fc1c1c>Ballong ikke funnet.'
  not-equipped: '<#fc1c1c>Du har for øyeblikket ingen ballong utstyrt.'

  material-not-dyeable: 'Materialet %s kan ikke farges.'
  invalid-rgb-values: 'RGB-verdiene må være mellom 0 og 255 for å være gyldige.'
  balloon-not-set: 'Ballongen %s er ikke satt i konfigurasjonen!'
  material-not-set: 'Materialet til ballongen %s er ikke satt i konfigurasjonen!'
  material-not-valid: 'Materialet til ballongen %s er ikke gyldig! Materiale: %s'
  material-is-not-valid: 'Materialet %s er ikke gyldig!'
  invalid-item-meta: 'ItemMeta er ikke gyldig for materialet: %s'

  no-balloons-registered: 'Ingen ballonger er registrert! Kan ikke opprette en meny uten ballonger.'

  configuration-folder-not-found: 'Konfigurasjonsmappen ble ikke funnet: %s'
  no-configuration-files-found: 'Ingen konfigurasjonsfiler ble funnet i mappen: %s'
  configuration-section-not-found: 'Konfigurasjonsdelen ble ikke funnet for filen: %s'
  balloon-type-not-found: 'Feil ved behandling av ballongtype for seksjon: %s i filen: %s. Ballongtypen eksisterer ikke eller er null.'
  balloon-process-error: 'Feil ved behandling av ballong for seksjon: %s i filen: %s. Feil: %s'

  menu-slot-out-of-bounds: '%s meny sideknapp(er) utenfor grensene!'

  invalid-hex-code: 'Ugyldig heksadesimal kode: %s'
```
{% endcode %}

### Slovak (Slovakia)

{% code title="sk_SK.yml" %}
```yaml
messages:
  prefix: '<gradient:#ff00cc:#5555ff>[Bloons]</gradient> <white>'
  no-permission: '<#fc1c1c>Prístup zamietnutý.'
  player-not-found: '<#fc1c1c>Hráč nenájdený.'
  config-reloaded: '<green>Konfigurácia bola znovu načítaná.'
  command-disabled: '<#fc1c1c>Tento príkaz je momentálne zakázaný!'

  equipped: '%s <green>nastavený!'
  unequipped: '<green>Váš balón bol bezpečne uložený.'
  balloon-not-found: '<#fc1c1c>Neexistuje žiadny balón.'
  not-equipped: '<#fc1c1c>Nemáte momentálne žiadny balón nastavený.'

  material-not-dyeable: 'Materiál %s nie je možné farbiť.'
  invalid-rgb-values: 'Hodnoty RGB musia byť medzi 0 a 255, aby boli platné.'
  balloon-not-set: 'Balón %s nie je nastavený v konfigurácii!'
  material-not-set: 'Materiál balónu %s nie je nastavený v konfigurácii!'
  material-not-valid: 'Materiál balónu %s nie je platný! Materiál: %s'
  material-is-not-valid: 'Materiál %s nie je platný!'
  invalid-item-meta: 'ItemMeta nie je platný pre materiál: %s'

  no-balloons-registered: 'Nie sú zaregistrované žiadne balóny! Nie je možné vytvoriť menu bez balónov.'

  configuration-folder-not-found: 'Priečinok s konfiguráciou sa nenašiel: %s'
  no-configuration-files-found: 'V priečinku sa nenašli žiadne konfiguračné súbory: %s'
  configuration-section-not-found: 'Sekcia konfigurácie sa nenašla pre súbor: %s'
  balloon-type-not-found: 'Chyba pri spracovaní typu balónu pre sekciu: %s v súbore: %s. Typ balónu neexistuje alebo je null.'
  balloon-process-error: 'Chyba pri spracovaní balónu pre sekciu: %s v súbore: %s. Chyba: %s'

  menu-slot-out-of-bounds: '%s tlačidlá stránok menu prekračujú hranice!'

  invalid-hex-code: 'Neplatný hexadecimálny kód: %s'
```
{% endcode %}

### Albanian (Albania)

{% code title="sq_AL.yml" %}
```yaml
messages:
  prefix: '<gradient:#ff00cc:#5555ff>[Bloons]</gradient> <white>'
  no-permission: '<#fc1c1c>Qasja e refuzuar.'
  player-not-found: '<#fc1c1c>Lojtari nuk u gjet.'
  config-reloaded: '<green>Konfigurimi u rifreskua.'
  command-disabled: '<#fc1c1c>Kjo komandë është aktualisht e çaktivizuar!'

  equipped: '%s <green>pajisur!'
  unequipped: '<green>Balona juaj është ruajtur me siguri.'
  balloon-not-found: '<#fc1c1c>Balona nuk u gjet.'
  not-equipped: '<#fc1c1c>Ju nuk keni një balonë të pajisur aktualisht.'

  material-not-dyeable: 'Materiali %s nuk është një material që mund të ngjyroset.'
  invalid-rgb-values: 'Vlerat RGB duhet të jenë midis 0 dhe 255 për të qenë të vlefshme.'
  balloon-not-set: 'Balona %s nuk është vendosur në konfigurim!'
  material-not-set: 'Materiali i balonës %s nuk është vendosur në konfigurim!'
  material-not-valid: 'Materiali i balonës %s nuk është një material i vlefshëm! Materiali: %s'
  material-is-not-valid: 'Materiali %s nuk është një material i vlefshëm!'
  invalid-item-meta: 'ItemMeta nuk është i vlefshëm për materialin: %s'

  no-balloons-registered: 'Nuk u gjetën balona! Nuk mund të krijohet një menu pa balona.'

  configuration-folder-not-found: 'Dosja e konfigurimit nuk u gjet: %s'
  no-configuration-files-found: 'Nuk u gjetën skedarë konfigurimi në dosje: %s'
  configuration-section-not-found: 'Seksioni i konfigurimit nuk u gjet për skedarin: %s'
  balloon-type-not-found: 'Gabim në përpunimin e llojit të balonës për seksionin: %s në skedarin: %s. Lloji i balonës nuk ekziston ose është null.'
  balloon-process-error: 'Gabim në përpunimin e balonës për seksionin: %s në skedarin: %s. Gabimi: %s'

  menu-slot-out-of-bounds: '%s vendet e butonit të faqes së menysë jashtë kufijve!'

  invalid-hex-code: 'Kodi heksadecimal i pavlefshëm: %s'
```
{% endcode %}

### Serbian (Bosnia and Herzegovina)

{% code title="sr_BA.yml" %}
```yaml
messages:
  prefix: '<gradient:#ff00cc:#5555ff>[Bloons]</gradient> <white>'
  no-permission: '<#fc1c1c>Nema dozvole.'
  player-not-found: '<#fc1c1c>Igrač nije pronađen.'
  config-reloaded: '<green>Konfiguracija je ponovo učitana.'
  command-disabled: '<#fc1c1c>Ova komanda je trenutno onemogućena!'

  equipped: '%s <green>opremljen!'
  unequipped: '<green>Vaš balon je sada sigurno uskladišten.'
  balloon-not-found: '<#fc1c1c>Balon nije pronađen.'
  not-equipped: '<#fc1c1c>Trenutno nemate opremljen balon.'

  material-not-dyeable: 'Materijal %s nije moguće obojiti.'
  invalid-rgb-values: 'RGB vrednosti moraju biti između 0 i 255 da bi bile validne.'
  balloon-not-set: 'Balon %s nije postavljen u konfiguraciji!'
  material-not-set: 'Materijal balona %s nije postavljen u konfiguraciji!'
  material-not-valid: 'Materijal balona %s nije validan! Materijal: %s'
  material-is-not-valid: 'Materijal %s nije validan!'
  invalid-item-meta: 'ItemMeta nije validan za materijal: %s'

  no-balloons-registered: 'Nema registrovanih balona! Ne može se kreirati meni bez balona.'

  configuration-folder-not-found: 'Folder konfiguracije nije pronađen: %s'
  no-configuration-files-found: 'Nije pronađena nijedna konfiguraciona datoteka u folderu: %s'
  configuration-section-not-found: 'Sekcija konfiguracije nije pronađena za datoteku: %s'
  balloon-type-not-found: 'Greška prilikom obrade tipa balona za sekciju: %s u datoteci: %s. Tip balona ne postoji ili je null.'
  balloon-process-error: 'Greška prilikom obrade balona za sekciju: %s u datoteci: %s. Greška: %s'

  menu-slot-out-of-bounds: '%s slot(ova) meni stranice prelazi granice!'

  invalid-hex-code: 'Nevažeći heksadecimalni kod: %s'
```
{% endcode %}

### Swedish (Sweden)

{% code title="sv_SE.yml" %}
```yaml
messages:
  prefix: '<gradient:#ff00cc:#5555ff>[Bloons]</gradient> <white>'
  no-permission: '<#fc1c1c>Åtkomst nekad.'
  player-not-found: '<#fc1c1c>Spelaren hittades inte.'
  config-reloaded: '<green>Konfigurationen har laddats om.'
  command-disabled: '<#fc1c1c>Denna kommando är för närvarande inaktiverad!'

  equipped: '%s <green>utrustad!'
  unequipped: '<green>Din ballong har säkrats.'
  balloon-not-found: '<#fc1c1c>Ballongen hittades inte.'
  not-equipped: '<#fc1c1c>Du har för närvarande ingen ballong utrustad.'

  material-not-dyeable: 'Materialet %s kan inte färgas.'
  invalid-rgb-values: 'RGB-värdena måste vara mellan 0 och 255 för att vara giltiga.'
  balloon-not-set: 'Ballongen %s är inte inställd i konfigurationen!'
  material-not-set: 'Materialet för ballongen %s är inte inställt i konfigurationen!'
  material-not-valid: 'Materialet för ballongen %s är inte giltigt! Material: %s'
  material-is-not-valid: 'Materialet %s är inte giltigt!'
  invalid-item-meta: 'ItemMeta är inte giltigt för materialet: %s'

  no-balloons-registered: 'Inga ballonger är registrerade! Det går inte att skapa en meny utan ballonger.'

  configuration-folder-not-found: 'Konfigurationsmappen hittades inte: %s'
  no-configuration-files-found: 'Inga konfigurationsfiler hittades i mappen: %s'
  configuration-section-not-found: 'Konfigurationssektionen hittades inte för filen: %s'
  balloon-type-not-found: 'Fel vid bearbetning av ballongtypen för avsnittet: %s i filen: %s. Ballongtypen finns inte eller är null.'
  balloon-process-error: 'Fel vid bearbetning av ballongen för avsnittet: %s i filen: %s. Fel: %s'

  menu-slot-out-of-bounds: '%s meny sida knapp(ar) utanför gränserna!'

  invalid-hex-code: 'Ogiltig hex-kod: %s'
```
{% endcode %}

### Swahili (Kenya)

{% code title="sw_KE.yml" %}
```yaml
messages:
  prefix: '<gradient:#ff00cc:#5555ff>[Bloons]</gradient> <white>'
  no-permission: '<#fc1c1c>Hakuna ruhusa.'
  player-not-found: '<#fc1c1c>Mchezaji hakupatikana.'
  config-reloaded: '<green>Mipangilio imesasishwa upya.'
  command-disabled: '<#fc1c1c>Amri hii kwa sasa imelemazwa!'

  equipped: '%s <green>limevalishwa!'
  unequipped: '<green>Baluni lako limehifadhiwa kwa usalama.'
  balloon-not-found: '<#fc1c1c>Baluni halipatikani.'
  not-equipped: '<#fc1c1c>Huna baluni limevalishwa kwa sasa.'

  material-not-dyeable: 'Materiali %s haiwezi kuchovyeka.'
  invalid-rgb-values: 'Thamani za RGB lazima ziwe kati ya 0 na 255 ili ziwe halali.'
  balloon-not-set: 'Baluni %s haijasanidiwa!'
  material-not-set: 'Vifaa vya baluni %s havijasanidiwa!'
  material-not-valid: 'Vifaa vya baluni %s sio halali! Materiali: %s'
  material-is-not-valid: 'Materiali %s sio halali!'
  invalid-item-meta: 'ItemMeta sio halali kwa vifaa: %s'

  no-balloons-registered: 'Hakuna baluni zilizosajiliwa! Haiwezekani kuunda menyu bila baluni.'

  configuration-folder-not-found: 'Folda ya mipangilio haipatikani: %s'
  no-configuration-files-found: 'Hakuna faili za mipangilio zilizopatikana kwenye folda: %s'
  configuration-section-not-found: 'Sehemu ya mipangilio haikupatikana kwa faili: %s'
  balloon-type-not-found: 'Kosa katika kusindika aina ya baluni kwa sehemu: %s katika faili: %s. Aina ya baluni haipo au ni tupu.'
  balloon-process-error: 'Kosa katika kusindika baluni kwa sehemu: %s katika faili: %s. Kosa: %s'

  menu-slot-out-of-bounds: '%s kifungo cha ukurasa wa menyu kimezidi mipaka!'

  invalid-hex-code: 'Nambari ya hexa batili: %s'
```
{% endcode %}

### Syriac (Syria)

{% code title="syr_SY.yml" %}
```yaml
messages:
  prefix: '<gradient:#ff00cc:#5555ff>[Bloons]</gradient> <white>'
  no-permission: '<#fc1c1c>رخصة مرفوضة.'
  player-not-found: '<#fc1c1c>اللاعب غير موجود.'
  config-reloaded: '<green>تم إعادة تحميل الإعدادات.'
  command-disabled: '<#fc1c1c>هذا الأمر معطل حالياً!'

  equipped: '%s <green>مجهز!'
  unequipped: '<green>تم تخزين بالونك بأمان.'
  balloon-not-found: '<#fc1c1c>البالون غير موجود.'
  not-equipped: '<#fc1c1c>ليس لديك حالياً بالون مجهز.'

  material-not-dyeable: 'المادة %s غير قابلة للصبغ.'
  invalid-rgb-values: 'قيم RGB يجب أن تكون بين 0 و 255 لتكون صالحة.'
  balloon-not-set: 'البالون %s غير معين في التكوين!'
  material-not-set: 'مادة البالون %s غير معينة في التكوين!'
  material-not-valid: 'مادة البالون %s غير صالحة! المادة: %s'
  material-is-not-valid: 'المادة %s غير صالحة!'
  invalid-item-meta: 'الميتاداتا غير صالحة للمادة: %s'

  no-balloons-registered: 'لا توجد بالونات مسجلة! لا يمكن إنشاء قائمة بدون بالونات.'

  configuration-folder-not-found: 'مجلد التكوين غير موجود: %s'
  no-configuration-files-found: 'لم يتم العثور على ملفات تكوين في المجلد: %s'
  configuration-section-not-found: 'القسم في التكوين غير موجود للملف: %s'
  balloon-type-not-found: 'خطأ في معالجة نوع البالون للقسم: %s في الملف: %s. نوع البالون غير موجود أو فارغ.'
  balloon-process-error: 'خطأ في معالجة البالون للقسم: %s في الملف: %s. الخطأ: %s'

  menu-slot-out-of-bounds: '%s زر صفحة القائمة خارج الحدود!'

  invalid-hex-code: 'رمز هكس غير صالح: %s'
```
{% endcode %}

### Tamil (India)

{% code title="ta_IN.yml" %}
```yaml
messages:
  prefix: '<gradient:#ff00cc:#5555ff>[Bloons]</gradient> <white>'
  no-permission: '<#fc1c1c>அனுமதி இல்லை.'
  player-not-found: '<#fc1c1c>வீரர் கண்டுபிடிக்கப்படவில்லை.'
  config-reloaded: '<green>உள்ளமைவு மீள்படுத்தப்பட்டது.'
  command-disabled: '<#fc1c1c>இந்த கட்டளை தற்போது முடக்கப்பட்டுள்ளது!'

  equipped: '%s <green>உடைக்கப்பட்டது!'
  unequipped: '<green>உங்கள் பலூன் பாதுகாக்கப்பட்டுள்ளது.'
  balloon-not-found: '<#fc1c1c>பலூன் காணப்படவில்லை.'
  not-equipped: '<#fc1c1c>உங்களுக்கு தற்போது பலூன் உடையப்பட்டிருக்கவில்லை.'

  material-not-dyeable: 'பொருள் %s வண்ணமாக்க முடியாது.'
  invalid-rgb-values: 'RGB மதிப்புகள் 0 மற்றும் 255 இடம் இருக்க வேண்டும்.'
  balloon-not-set: 'பலூன் %s உள்ளது உள்ளது கட்டமைப்பில் அமைக்கப்படவில்லை!'
  material-not-set: 'பலூன் %s மெட்டீரியல் கட்டமைப்பில் அமைக்கப்படவில்லை!'
  material-not-valid: 'பலூன் %s மெட்டீரியல் தவறானது! பொருள்: %s'
  material-is-not-valid: 'பொருள் %s தவறானது!'
  invalid-item-meta: 'உருப்படி மெட்டாவின் %s மாதிரி தவறானது.'

  no-balloons-registered: 'பலூன்கள் பதிவு செய்யப்படவில்லை! பலூன்கள் இல்லாத ஒரு பட்டியலை உருவாக்க முடியாது.'

  configuration-folder-not-found: 'கட்டமைப்பு கோப்புறை காணப்படவில்லை: %s'
  no-configuration-files-found: 'கோப்புறையில் கட்டமைப்பு கோப்புகள் காணப்படவில்லை: %s'
  configuration-section-not-found: 'கோப்பின் கட்டமைப்பு பிரிப்பு காணப்படவில்லை: %s'
  balloon-type-not-found: 'பட்டியலில் பலூன் வகையை செயல்படுத்தும் பிழை: %s கோப்பில் பிரிப்பு: %s. பலூன் வகை இல்லை அல்லது பூட்.'
  balloon-process-error: 'பட்டியலில் பலூன் செயல்படுத்தும் பிழை: %s கோப்பில் பிரிப்பு: %s. பிழை: %s'

  menu-slot-out-of-bounds: '%s பட்டி பக்க பொத்தான்(கள்) எல்லைகளை மீறுகின்றன!'

  invalid-hex-code: 'தவறான ஹெக்ஸ் குறியீடு: %s'
```
{% endcode %}

### Telugu (India)

{% code title="te_IN.yml" %}
```yaml
messages:
  prefix: '<gradient:#ff00cc:#5555ff>[Bloons]</gradient> <white>'
  no-permission: '<#fc1c1c>అనుమతి లేదు.'
  player-not-found: '<#fc1c1c>క్రీడకు వ్యక్తి కనబడలేదు.'
  config-reloaded: '<green>ఆకృతీకరణ మళ్ళీ లోడు చేయబడింది.'
  command-disabled: '<#fc1c1c>ఈ కమాండు ప్రస్తుతం నిలిపివేయబడింది!'

  equipped: '%s <green>ఆకృతీకరించబడింది!'
  unequipped: '<green>మీ బలూన్ భద్రంగా భద్రపరచబడింది.'
  balloon-not-found: '<#fc1c1c>బలూన్ కనబడలేదు.'
  not-equipped: '<#fc1c1c>మీకు ప్రస్తుతం బలూన్ ఆకృతీకరించబడలేదు.'

  material-not-dyeable: 'సామగ్రి %s రంగుబద్ధం చేయబడదు.'
  invalid-rgb-values: 'RGB విలువలు 0 మరియు 255 ల మధ్య ఉండాలి మాత్రమే చెల్లవు.'
  balloon-not-set: 'బలూన్ %s ఆకృతీకరించబడలేదు!'
  material-not-set: 'బలూన్ %s సామగ్రి ఆకృతీకరించబడలేదు!'
  material-not-valid: 'బలూన్ %s సామగ్రి చెల్లనిది! సామగ్రి: %s'
  material-is-not-valid: 'సామగ్రి %s చెల్లనిది!'
  invalid-item-meta: 'ఐటం మెటా %s మాటీరియల్కు చెల్లనిది.'

  no-balloons-registered: 'రిజిస్టర్ చేయబడిన బలూన్లు లేవు! బలూన్లు లేని మెనును సృష్టించలేరు.'

  configuration-folder-not-found: 'ఆకృతీకరణ ఫోల్డర్ కనబడలేదు: %s'
  no-configuration-files-found: 'ఫోల్డర్ లో ఆకృతీకరణ ఫైళ్ళు కనబడలేదు: %s'
  configuration-section-not-found: 'ఫైల్ కోసం ఆకృతీకరణ విభాగం కనబడలేదు: %s'
  balloon-type-not-found: 'విభాగంలో బలూన్ రకం ప్రాసెసింగ్ లో లోపం: %s ఫైల్లోను: %s. బలూన్ రకం లేదు లేదా ఖాళీగా ఉంది.'
  balloon-process-error: 'విభాగంలో బలూన్ ప్రాసెస్ లో లోపం: %s ఫైల్లోను: %s. లోపం: %s'

  menu-slot-out-of-bounds: '%s మెను పేజీ బటన్ స్లాట్(లు) బారిస్తాయి!'

  invalid-hex-code: 'చెల్లని హెక్స్ కోడ్: %s'
```
{% endcode %}

### Thai (Thailand)

{% code title="th_TH.yml" %}
```yaml
messages:
  prefix: '<gradient:#ff00cc:#5555ff>[Bloons]</gradient> <white>'
  no-permission: '<#fc1c1c>ไม่อนุญาต.'
  player-not-found: '<#fc1c1c>ไม่พบผู้เล่น.'
  config-reloaded: '<green>โหลดการตั้งค่าใหม่.'
  command-disabled: '<#fc1c1c>คำสั่งนี้ถูกปิดใช้งานในปัจจุบัน!'

  equipped: '%s <green>ได้รับการติดตั้งแล้ว!'
  unequipped: '<green>บอลลูนของคุณได้รับการจัดเก็บไว้อย่างปลอดภัย'
  balloon-not-found: '<#fc1c1c>ไม่พบบอลลูน.'
  not-equipped: '<#fc1c1c>คุณยังไม่ได้ติดตั้งบอลลูนใด ๆ.'

  material-not-dyeable: 'วัสดุ %s ไม่สามารถเปลี่ยนสีได้.'
  invalid-rgb-values: 'ค่า RGB ต้องอยู่ระหว่าง 0 และ 255 เพื่อเป็นไปได้.'
  balloon-not-set: 'ไม่ได้ตั้งค่าบอลลูน %s ในการกำหนดค่า!'
  material-not-set: 'วัสดุของบอลลูน %s ไม่ได้ตั้งค่าในการกำหนดค่า!'
  material-not-valid: 'วัสดุของบอลลูน %s ไม่ถูกต้อง! วัสดุ: %s'
  material-is-not-valid: 'วัสดุ %s ไม่ถูกต้อง!'
  invalid-item-meta: 'ItemMeta ไม่ถูกต้องสำหรับวัสดุ: %s'

  no-balloons-registered: 'ไม่มีบอลลูนที่ลงทะเบียน! ไม่สามารถสร้างเมนูโดยไม่มีบอลลูน.'

  configuration-folder-not-found: 'ไม่พบโฟลเดอร์การกำหนดค่า: %s'
  no-configuration-files-found: 'ไม่พบไฟล์การกำหนดค่าในโฟลเดอร์: %s'
  configuration-section-not-found: 'ไม่พบส่วนการกำหนดค่าสำหรับไฟล์: %s'
  balloon-type-not-found: 'ข้อผิดพลาดในการประมวลผลประเภทบอลลูนสำหรับส่วน: %s ในไฟล์: %s. ประเภทบอลลูนไม่มีหรือเป็น null.'
  balloon-process-error: 'ข้อผิดพลาดในการประมวลผลบอลลูนสำหรับส่วน: %s ในไฟล์: %s. ข้อผิดพลาด: %s'

  menu-slot-out-of-bounds: 'ปุ่มเมนูหน้า %s เกินขอบเขต!'

  invalid-hex-code: 'รหัสฮีกไม่ถูกต้อง: %s'
```
{% endcode %}

### Tswana (South Africa)

{% code title="tn_ZA.yml" %}
```yaml
messages:
  prefix: '<gradient:#ff00cc:#5555ff>[Bloons]</gradient> <white>'
  no-permission: '<#fc1c1c>Ha u fa tirisano.'
  player-not-found: '<#fc1c1c>Ha ke kene ke hore o tsebe monna oa chelete.'
  config-reloaded: '<green>Sebaka se hlasiloe ka tlase.'
  command-disabled: '<#fc1c1c>Khomando ena ke e tlaaseha ha ho na le tšireletso e sa tšoanang!'

  equipped: '%s <green>e pharalletsa!'
  unequipped: '<green>Seboka sa hao sa behe ka khalemoleng.'
  balloon-not-found: '<#fc1c1c>Ha ho fumanehe seboka.'
  not-equipped: '<#fc1c1c>Haeba o sa fumane seboka e kenyelletsoa.'

  material-not-dyeable: 'Letsoho %s ha le se e tsebahalisang.'
  invalid-rgb-values: 'Maqheku a RGB a tlameha ho beng 0 le 255 ho ba le mohlala.'
  balloon-not-set: 'Seboka %s se ha se sesebetseng ka sebaka!'
  material-not-set: 'Mosebetsi oa seboka %s ha o se setelehang ka sebaka!'
  material-not-valid: 'Mosebetsi oa seboka %s ha o se boemo bona! Boemo: %s'
  material-is-not-valid: 'Mosebetsi %s ha o se boemo bona!'
  invalid-item-meta: 'ItemMeta ha e sebetse ho mosebetsi: %s'

  no-balloons-registered: 'Ha ho na besebetsi ba bolone ba rekisitara! Ha hloka ho atleha menu e sa fumane bolone.'

  configuration-folder-not-found: 'Sebaka sa tšireletso e sa fumaneha: %s'
  no-configuration-files-found: 'Ha ho fumanehe maqheku a tšireletso a sebaka: %s'
  configuration-section-not-found: 'Maqheku a tšireletso a sebaka ha a fumaneha bakeng sa file: %s'
  balloon-type-not-found: 'Khetla e sa sebedisana ka tsebo ea bolone bakeng sa sebaka: %s ka file: %s. E ka sebelisoa ka e ka sebelisoa hoba ka nolle.'
  balloon-process-error: 'Khetla e sa sebedisana ka bolone bakeng sa sebaka: %s ka file: %s. Hlobo ea sebetsa: %s'

  menu-slot-out-of-bounds: '%s khatiso ea bontša lebitla le kasehleng!'

  invalid-hex-code: 'Mohlala oa hex e sa sebetse: %s'
```
{% endcode %}

### Turkish (Turkey)

{% code title="tr_TR.yml" %}
```yaml
messages:
  prefix: '<gradient:#ff00cc:#5555ff>[Bloons]</gradient> <white>'
  no-permission: '<#fc1c1c>İzin verilmedi.'
  player-not-found: '<#fc1c1c>Oyuncu bulunamadı.'
  config-reloaded: '<green>Ayarlar yeniden yüklendi.'
  command-disabled: '<#fc1c1c>Bu komut şu anda devre dışı!'

  equipped: '%s <green>donatıldı!'
  unequipped: '<green>Balonunuz güvenli bir şekilde depolandı.'
  balloon-not-found: '<#fc1c1c>Balon bulunamadı.'
  not-equipped: '<#fc1c1c>Şu anda donatılmış bir balonunuz yok.'

  material-not-dyeable: '%s malzemesi boyanabilir değil.'
  invalid-rgb-values: 'Geçersiz RGB değerleri: Değerler 0 ve 255 arasında olmalıdır.'
  balloon-not-set: '%s balonu yapılandırmada belirtilmemiş!'
  material-not-set: '%s balonunun malzemesi yapılandırmada belirtilmemiş!'
  material-not-valid: '%s balonun malzemesi geçerli değil! Malzeme: %s'
  material-is-not-valid: '%s malzemesi geçerli değil!'
  invalid-item-meta: 'Malzeme için geçersiz ItemMeta: %s'

  no-balloons-registered: 'Kayıtlı balon bulunmuyor! Boş bir balon menüsü oluşturulamaz.'

  configuration-folder-not-found: 'Yapılandırma klasörü bulunamadı: %s'
  no-configuration-files-found: 'Klasörde yapılandırma dosyası bulunamadı: %s'
  configuration-section-not-found: 'Dosya için yapılandırma bölümü bulunamadı: %s'
  balloon-type-not-found: 'Bölüm için balon türü işlenirken hata oluştu: %s, dosya: %s. Balon türü mevcut değil veya null.'
  balloon-process-error: 'Bölüm için balon işlenirken hata oluştu: %s, dosya: %s. Hata: %s'

  menu-slot-out-of-bounds: '%s menü sayfa düğme yuvası sınırların dışında!'

  invalid-hex-code: 'Geçersiz hex kodu: %s'
```
{% endcode %}

### Ukrainian (Ukraine)

{% code title="uk_UA.yml" %}
```yaml
messages:
  prefix: '<gradient:#ff00cc:#5555ff>[Bloons]</gradient> <white>'
  no-permission: '<#fc1c1c>Доступ заборонено.'
  player-not-found: '<#fc1c1c>Гравець не знайдений.'
  config-reloaded: '<green>Конфігурація перезавантажена.'
  command-disabled: '<#fc1c1c>Ця команда наразі вимкнена!'

  equipped: '%s <green>встановлено!'
  unequipped: '<green>Ваша кулька безпечно збережена.'
  balloon-not-found: '<#fc1c1c>Кулька не знайдена.'
  not-equipped: '<#fc1c1c>Наразі у вас не встановлено кульку.'

  material-not-dyeable: 'Матеріал %s не можна забарвити.'
  invalid-rgb-values: 'Недійсні значення RGB: значення повинні бути від 0 до 255.'
  balloon-not-set: 'Кулька %s не встановлена в конфігурації!'
  material-not-set: 'Матеріал кульки %s не встановлено в конфігурації!'
  material-not-valid: 'Матеріал кульки %s недійсний! Матеріал: %s'
  material-is-not-valid: 'Матеріал %s недійсний!'
  invalid-item-meta: 'Недійсна мета-предмету для матеріалу: %s'

  no-balloons-registered: 'Кульки не знайдено! Неможливо створити меню без кульок.'

  configuration-folder-not-found: 'Каталог конфігурації не знайдено: %s'
  no-configuration-files-found: 'Не знайдено конфігураційних файлів у каталозі: %s'
  configuration-section-not-found: 'Розділ конфігурації не знайдено для файлу: %s'
  balloon-type-not-found: 'Помилка обробки типу кульки для розділу: %s в файлі: %s. Тип кульки не існує або є null.'
  balloon-process-error: 'Помилка обробки кульки для розділу: %s в файлі: %s. Помилка: %s'

  menu-slot-out-of-bounds: '%s кнопка сторінки меню виходить за межі!'

  invalid-hex-code: 'Недійсний шістнадцятковий код: %s'
```
{% endcode %}

### Uzbek (Uzbekistan)

{% code title="uz_UZ.yml" %}
```yaml
messages:
  prefix: '<gradient:#ff00cc:#5555ff>[Bloons]</gradient> <white>'
  no-permission: '<#fc1c1c>Ruxsat berilmagan.'
  player-not-found: '<#fc1c1c>Oyinchi topilmadi.'
  config-reloaded: '<green>Sozlamalar qayta yuklandi.'
  command-disabled: '<#fc1c1c>Ushbu buyruq hozir faol emas!'

  equipped: '%s <green>ojiqtirildi!'
  unequipped: '<green>Baloningiz xavfsiz saqlandi.'
  balloon-not-found: '<#fc1c1c>Balon topilmadi.'
  not-equipped: '<#fc1c1c>Hozircha o'rnatilgan baloningiz yo\'q.'

  material-not-dyeable: '%s materialini ranglab bo\'lmaydi.'
  invalid-rgb-values: "Noto'g'ri RGB qiymatlari: qiymatlar 0 va 255 oralig'ida bo\'lishi kerak."
  balloon-not-set: '%s baloni sozlamada o\'rnatilmagan!'
  material-not-set: 'Balon materiali %s sozlamada o\'rnatilmagan!'
  material-not-valid: '%s balon materiali haqiqiy emas! Material: %s'
  material-is-not-valid: '%s materiali haqiqiy emas!'
  invalid-item-meta: "Material uchun noto'g'ri ItemMeta: %s"

  no-balloons-registered: 'Ro\'yxatga olingan balonlar yo\'q! Balonsiz menyuni yaratib bo\'lmaydi.'

  configuration-folder-not-found: 'Sozlamalar papkasi topilmadi: %s'
  no-configuration-files-found: 'Fayllar katalogida sozlamalar fayllari topilmadi: %s'
  configuration-section-not-found: "Fayl uchun sozlamalar bo\'limi topilmadi: %s"
  balloon-type-not-found: "Bo\'limda balon turi qayta ishlab chiqish jarayonida xatolik yuz berdi: %s faylda: %s. Balon turi mavjud emas yoki null."
  balloon-process-error: "Bo\'limda balon jarayonida xatolik yuz berdi: %s faylda: %s. Xatolik: %s"

  menu-slot-out-of-bounds: '%s menyuni sahifa tugmasi chetlardan tashqari!'

  invalid-hex-code: "Noto'g'ri hex kodi: %s"
```
{% endcode %}

### Vietnamese (Vietnam)

{% code title="vi_VN.yml" %}
```yaml
messages:
  prefix: '<gradient:#ff00cc:#5555ff>[Bloons]</gradient> <white>'
  no-permission: '<#fc1c1c>Không có quyền truy cập.'
  player-not-found: '<#fc1c1c>Không tìm thấy người chơi.'
  config-reloaded: '<green>Cấu hình đã được tải lại.'
  command-disabled: '<#fc1c1c>Lệnh này hiện đang bị vô hiệu hóa!'

  equipped: '%s <green>đã được trang bị!'
  unequipped: '<green>Bóng của bạn đã được lưu an toàn.'
  balloon-not-found: '<#fc1c1c>Không tìm thấy bóng.'
  not-equipped: '<#fc1c1c>Bạn hiện không có bóng nào được trang bị.'

  material-not-dyeable: 'Vật liệu %s không thể nhuộm màu.'
  invalid-rgb-values: 'Giá trị RGB không hợp lệ: Giá trị phải nằm trong khoảng từ 0 đến 255.'
  balloon-not-set: 'Bóng %s không được thiết lập trong cấu hình!'
  material-not-set: 'Vật liệu của bóng %s không được thiết lập trong cấu hình!'
  material-not-valid: 'Vật liệu của bóng %s không hợp lệ! Vật liệu: %s'
  material-is-not-valid: 'Vật liệu %s không hợp lệ!'
  invalid-item-meta: 'ItemMeta không hợp lệ cho vật liệu: %s'

  no-balloons-registered: 'Không có bóng nào được đăng ký! Không thể tạo menu không có bóng.'

  configuration-folder-not-found: 'Thư mục cấu hình không tìm thấy: %s'
  no-configuration-files-found: 'Không tìm thấy tệp cấu hình trong thư mục: %s'
  configuration-section-not-found: 'Không tìm thấy phần cấu hình cho tệp: %s'
  balloon-type-not-found: 'Lỗi khi xử lý loại bóng cho phần: %s trong tệp: %s. Loại bóng không tồn tại hoặc là null.'
  balloon-process-error: 'Lỗi khi xử lý bóng cho phần: %s trong tệp: %s. Lỗi: %s'

  menu-slot-out-of-bounds: '%s nút trang menu vượt ra ngoài giới hạn!'

  invalid-hex-code: 'Mã hex không hợp lệ: %s'
```
{% endcode %}

### Xhosa (South Africa)

{% code title="xh_ZA.yml" %}
```yaml
messages:
  prefix: '<gradient:#ff00cc:#5555ff>[Bloons]</gradient> <white>'
  no-permission: '<#fc1c1c>Ukunceda akwenzeki.'
  player-not-found: '<#fc1c1c>I-Player ayikho.'
  config-reloaded: '<green>I-config yachazwe kabusha.'
  command-disabled: '<#fc1c1c>Loo mkhombandlela ulwaziwe!'

  equipped: '%s <green>kwenziwe!'
  unequipped: '<green>Umtya wakho uwugcinwe ngefanayo.'
  balloon-not-found: '<#fc1c1c>Uballooni awukho.'
  not-equipped: '<#fc1c1c>Awunayo ngoku i-ballooni engabhiyiselwe.'

  material-not-dyeable: 'I-material %s alifakanyi ngezinto.'
  invalid-rgb-values: 'Izimvo RGB ezisembiwe: Izimvo kufanele zibe phakathi kwesikhombisa se-0 kunye ne-255.'
  balloon-not-set: 'Uballooni %s akawuthandwa kwi-config!'
  material-not-set: 'I-material yoballoon %s aliyithandwa kwi-config!'
  material-not-valid: 'I-material yoballoon %s aliyenzekanga! Material: %s'
  material-is-not-valid: 'I-material %s aliyenzekanga!'
  invalid-item-meta: 'ItemMeta ayifanelekanga kwi-material: %s'

  no-balloons-registered: 'Akukho i-ballooni ethandwa! Ayikwazi ukwakha imenyu ngenkathazo i-ballooni.'

  configuration-folder-not-found: 'Akakuthandwa ifowudha yomhleli wocaphepha: %s'
  no-configuration-files-found: 'Akakuthandwa amafayela omthwalo wocaphepha: %s'
  configuration-section-not-found: 'Akakuthandwa i-section ye-config yokhuphela: %s'
  balloon-type-not-found: 'Igosa elikhona lokuqhuba i-ballooni elithandwa kwi-section: %s kwi-fayela: %s. Lolu qhubo lwaballooni alukho noma lulungile.'
  balloon-process-error: 'Lolu qhubo lwaballooni lokuqhuba kwenzakala kwi-section: %s kwi-fayela: %s. Iphutha: %s'

  menu-slot-out-of-bounds: '%s imenyu yephepha i-buttoni yaselwimiyo kwi-imfundiso!'

  invalid-hex-code: 'Ikhodi ye-hex engalungile: %s'
```
{% endcode %}

### Chinese (Taiwan)

{% code title="zh_TW.yml" %}
```yaml
messages:
  prefix: '<gradient:#ff00cc:#5555ff>[Bloons]</gradient> <white>'
  no-permission: '<#fc1c1c>無權訪問。'
  player-not-found: '<#fc1c1c>找不到玩家。'
  config-reloaded: '<green>配置已重新加載。'
  command-disabled: '<#fc1c1c>此命令目前已禁用！'

  equipped: '%s <green>已裝備！'
  unequipped: '<green>您的氣球已安全存儲。'
  balloon-not-found: '<#fc1c1c>找不到氣球。'
  not-equipped: '<#fc1c1c>您目前沒有裝備氣球。'

  material-not-dyeable: '材料%s無法染色。'
  invalid-rgb-values: 'RGB 值必須在 0 和 255 之間才有效。'
  balloon-not-set: '未在配置中設置氣球%s！'
  material-not-set: '未在配置中設置氣球%s的材料！'
  material-not-valid: '氣球%s的材料無效！ 材料：%s'
  material-is-not-valid: '材料%s無效！'
  invalid-item-meta: '對於材料%s，ItemMeta 無效。'

  no-balloons-registered: '沒有註冊氣球！不能創建沒有氣球的菜單。'

  configuration-folder-not-found: '找不到配置文件夾：%s'
  no-configuration-files-found: '在文件夾%s中找不到配置文件。'
  configuration-section-not-found: '找不到文件%s的配置部分。'
  balloon-type-not-found: '處理文件%s中部分%s的氣球類型時出錯。氣球類型不存在或為空。'
  balloon-process-error: '處理文件%s中部分%s的氣球時出錯。錯誤：%s'

  menu-slot-out-of-bounds: '菜單頁%s按鈕位置超出範圍！'

  invalid-hex-code: '無效的十六進制代碼：%s'
```
{% endcode %}
