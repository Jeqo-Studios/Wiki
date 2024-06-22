---
description: >-
  Our Bloons plugin comes with premade locales to ensure that a multitude of
  people can access and use the plugin no matter the language they speak.
---

# 🗨️ Language and Locales

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

### Spanish US

{% code title="es_US.yml" %}
```yaml
messages:
  prefix: '<gradient:#ff00cc:#5555ff>[Bloons]</gradient> <white>'
  no-permission: '<#fc1c1c>Acceso denegado.'
  player-not-found: '<#fc1c1c>Jugador no encontrado.'
  config-reloaded: '<green>Configuración recargada.'
  command-disabled: '<#fc1c1c>¡Este comando está actualmente deshabilitado!'

  equipped: '%s <green>equipado!'
  unequipped: '<green>Su globo ha sido almacenado de forma segura.'
  balloon-not-found: '<#fc1c1c>Globo no encontrado.'
  not-equipped: '<#fc1c1c>Actualmente no tienes un globo equipado.'

  material-not-dyeable: 'El material %s no es un material que se pueda teñir.'
  invalid-rgb-values: 'Los valores RGB deben estar entre 0 y 255 para ser válidos.'
  balloon-not-set: '¡El globo %s no está configurado en la configuración!'
  material-not-set: '¡El material del globo %s no está configurado en la configuración!'
  material-not-valid: '¡El material del globo %s no es un material válido! Material: %s'
  material-is-not-valid: '¡El material %s no es un material válido!'
  invalid-item-meta: 'ItemMeta no es válido para material: %s'

  no-balloons-registered: '¡No se encuentran globos! No se puede crear un menú sin globos.'

  configuration-folder-not-found: 'Carpeta de configuración no encontrada: %s'
  no-configuration-files-found: 'No se encontraron archivos de configuración en la carpeta: %s'
  configuration-section-not-found: 'Sección de configuración no encontrada para el archivo: %s'
  balloon-type-not-found: 'Error al procesar el tipo de globo para la sección: %s en el archivo: %s. El tipo de globo no existe o es nulo.'
  balloon-process-error: 'Error al procesar el globo para la sección: %s en el archivo: %s. Error: %s'

  menu-slot-out-of-bounds: '¡%s espacios para botones de página de menú están fuera de límites!'

  invalid-hex-code: 'Código hexadecimal no válido: %s'


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
