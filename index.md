---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: index

ref: index
lang: ru

title: API Crafter

lead: Данные через API
sublead: Доступ через систему автоматизированного пользовательского интерфейса к разнообразным базам данных (о госзакупках, организациях и пр.), включая принадлежащие клиенту или создаваемые под его нужды базы данных

cta: Подробнее
cta2: Оформить заявку

hiw:
  heading: Как это работает
  subheading: API Crafter предоставляет рабочей системе клиента (его программному продукту) доступ к информации, содержащейся в имеющихся базах данных нашей компании, у наших партнеров или на стороне клиента, для автоматизированного подключения
  list:
    - heading: Источники данных
      subheading: Базы данных API Crafter, базы данных партнеров, базы данных клиента (дополнительная разработка)
      icon: database
    - heading: Формат передаваемых данных
      subheading: Все данные передаются в систему клиента в формате JSON
      icon: code
    - heading: Системы клиента
      subheading: Интернет-портал, мобильное приложение, аналитические информационные системы, информационные системы безопасности и т.д.
      icon: desktop

hiw2:
  heading: Возможности
  subheading: API Crafter предлагает несколько продуктов и услуг, среди которых вы можете подобрать наиболее эффективные для вашей деятельности
  list:
    - heading: Доступ через API к нашим базам данных
      subheading: Наша компания обладает набором дата-сетов, приобретая доступ к которым через API вы получите необходимые вам и вашим программным продуктам ресурсы в автоматическом режиме, оплачивая только те строки баз данных, которые вам нужны. Более подробное описание баз данных ниже
      icon: database
    - heading: Разовые выгрузки информации
      subheading: Для значительной части дата-сетов, имеющихся в распоряжении API Crafter, предоставляется услуга выгрузки целиком или какой-то части базы данных в необходимом клиенту формате
      icon: cloud-download
    - heading: Создание API на базе данных клиента
      subheading: Мы предоставляем услуги в области создания API для массивов данных на стороне клиента. Мы проводим работы по приведению баз данных в требуемое состояние, по созданию API для автоматизированной работы систем клиента с его дата сетами
      icon: cubes
    - heading: Специализированные решения
      subheading: Под задачи клиентов мы проводим кастомную обработку баз данных (сведение нового дата-сета из имеющихся) либо дорабатываем параметры запросов под технические требования заказчика.
      icon: cube
    - heading: Консультационные услуги
      subheading: Мы обладаем компетенциями и экспертизой в области использования API, создания и работы с базами данных и оказываем консультационные услуги по данным вопросам
      icon: graduation-cap

hiw3:
  heading: Источники данных
  subheading: API Crafter располагает разнообразными базами данных, а именно
  list:
    - heading: Госзакупки и госконтракты
      subheading: Контракты/договоры и извещения (суммы, даты, закупки и др.), поставщики/заказчики (реквизиты и контактная информация), планы-графики (дата, заказчик, общая сумма, совокупный объем и т.д.)
      icon: file-text-o
      src: gov
    - heading: Организации
      subheading: Базы данных по организациям на основании реестров Минфина, ФНС, Росстата и т.п.
      icon: building-o
      src: organization
    - heading: Государственные финансы
      subheading: Федеральный бюджет, данные отчетов федерального казначейства, отчетности по налоговым поступлениям и т.д.
      icon: money
      src: finance
    - heading: Регионы и муниципалитеты
      subheading: Показатели деятельности регионов и муниципальных образований по всей территории страны
      icon: globe
      src: region
    - heading: НКО
      subheading: Базы данных по некоммерческим организациям, а именно реестры, гранты, отчеты и т.д.
      text: Организациям и физическим лицам, обладающим наборами дата-сетов, доступ к которым они хотели бы реализовывать на открытом рынке, мы предлагаем взаимовыгодное сотрудничество на основе предоставления доступа к базам данных партнеров через наши техническое решение и каналы продаж
      icon: certificate
      src: ngo
      btn: form-ngo
    - heading: Банки
      subheading: Данные по показателям деятельности банков и банковской системе (базы данных ЦБ РФ, банковских ассоциаций, Минфина, Организаций фондового рынка и т.д.)
      icon: university
      src: bank

plan:
  heading: Тарифы
  subheading: Тарификация услуг производится в трех основных видах
  list:
    # - heading: Платежи за количество обращений
    #   price: <strong>от 50 <small>руб./запрос</small></strong>
    #   features:
    #     - Приобретение пакетов с лимитами запросов
    #     - Предоплата за пакет
    #     - Разные лимиты для разных баз данных
    - heading: Оплата разовой выгрузки базы данных
      price: <strong>Цена договорная</strong>
      features:
        - Одноразовая оплата
        - Договорная цена в зависимости от выгружаемой базы данных
        - Возможность кастомизации базы данных
    - heading: Подписка
      price: <strong>от 100 000 <small>руб./мес.</small></strong>
      features:
        - Доступ к отдельным базам данных
        - Ежемесячные платежи
        - Высокий лимит запросов

cta_section: Вам нужен удобный доступ к данным?

feedback:
  heading: Отзывы и примеры внедрения
  subheading: Как предлагаемые услуги помогли деятельности наших клиентов
  list:
    - text: Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quidem, veritatis nulla eum laudantium totam tempore optio doloremque laboriosam quas, quos eaque molestias odio aut eius animi. Impedit temporibus nisi accusamus.
      img: https://s3.amazonaws.com/uifaces/faces/twitter/rem/128.jpg
      active: true
    - text: Короткий отзыв
      img: https://s3.amazonaws.com/uifaces/faces/twitter/adellecharles/128.jpg
    - text: Длинный отзыв, lorem ipsum dolor sit amet, consectetur adipisicing elit. Quidem, veritatis nulla eum laudantium totam tempore optio doloremque laboriosam quas, quos eaque molestias odio aut eius animi. Impedit temporibus nisi accusamus. Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quidem, veritatis nulla eum laudantium totam tempore optio doloremque laboriosam quas, quos eaque molestias odio aut eius animi. Impedit temporibus nisi accusamus.
      img: https://s3.amazonaws.com/uifaces/faces/twitter/ritu/128.jpg

contact-form:
  heading: Свяжитесь с нами!

---