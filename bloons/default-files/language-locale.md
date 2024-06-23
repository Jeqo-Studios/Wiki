---
description: >-
  Learn how to configure language and locale settings for our Minecraft plugins
  to match your preferred language and regional preferences.
---

# 🗨️ Language/Locale

The default language used by Bloons is English. The language file can be selected via the `config.yml` file. Language files are generated and stored in `Bloons/languages/`.

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

### Portuguese (Portugal)

{% code title="pt_PT.yml" %}
```yaml
messages:
  prefix: '<gradient:#ff00cc:#5555ff>[Bloons]</gradient> <white>'
  no-permission: '<#fc1c1c>Acesso negado.'
  player-not-found: '<#fc1c1c>Jogador não encontrado.'
  config-reloaded: '<green>Configuração recarregada.'
  command-disabled: '<#fc1c1c>Este comando está atualmente desativado!'

  equipped: '%s <green>equipado!'
  unequipped: '<green>Seu balão foi guardado com segurança.'
  balloon-not-found: '<#fc1c1c>Balão não encontrado.'
  not-equipped: '<#fc1c1c>Você não tem nenhum balão equipado no momento.'

  material-not-dyeable: 'Material %s não é um material tingível.'
  invalid-rgb-values: 'Os valores RGB devem estar entre 0 e 255 para serem válidos.'
  balloon-not-set: 'O balão %s não está definido na configuração!'
  material-not-set: 'O material do balão %s não está definido na configuração!'
  material-not-valid: 'O material do balão %s não é um material válido! Material: %s'
  invalid-item-meta: 'ItemMeta não é válido para o material: %s'

  no-balloons-registered: 'Nenhum balão encontrado! Não é possível criar um menu sem balões.'

  configuration-folder-not-found: 'Pasta de configuração não encontrada: %s'
  no-configuration-files-found: 'Nenhum arquivo de configuração encontrado na pasta: %s'
  configuration-section-not-found: 'Seção de configuração não encontrada para o arquivo: %s'
  balloon-type-not-found: 'Erro ao processar o tipo de balão para a seção: %s no arquivo: %s. O tipo de balão não existe ou é nulo.'
  balloon-process-error: 'Erro ao processar o balão para a seção: %s no arquivo: %s. Erro: %s'

  menu-slot-out-of-bounds: 'Slot(s) do botão da página de menu %s fora dos limites!'

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
