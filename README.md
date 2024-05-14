# A framework for automating testing of website "Welltory" - AI powered copilot for peak wellbeing
<a href="https://welltory.com" class="logo header-logo"> <img class="logo__img" src="https://welltory.com/wp-content/themes/Divi-child/img/hrt3.png" alt="logo"></a> <a target="_blank" href="https://www.welltory.com/">welltory.com</a>

![main page screenshot](/pictures/start.png)

----

### Особенности проекта

* Оповещения о тестовых прогонах в Telegram
* Отчеты с видео, скриншотом, логами, исходной моделью разметки страницы
* Сборка проекта в Jenkins
* Отчеты Allure Report
* Интеграция с Allure TestOps
* Автоматизация отчетности о тестовых прогонах и тест-кейсах в Jira
* Запуск web/UI автотестов в Selenoid
* Запуск mobile автотестов в BrowserStack
* Для запуска mobile автотестов используется Appium

### Список проверок, реализованных в web/UI автотестах

#### Главная страница:

- [x] <a target="_blank" href="https://welltory.com">Главная</a> страница сайта отображается
- [x] При нажатии на кнопку 
- [x] При нажатии на кнопку <a target="_blank" href="https://welltory.com/who-we-are">Who we are</a> происходит переход на соответствующую страницу сайта
- [x] При нажатии на кнопку <a target="_blank" href="https://welltory.com/science">Science</a> происходит переход на соответствующую страницу сайта
- [x] При нажатии на кнопку <a target="_blank" href="https://welltory.com/plans">Plans</a> происходит переход на соответствующую страницу сайта
      
#### Логотип на странице <a target="_blank" href="https://welltory.com/who-we-are">Who we are</a> :

- [x] При нажатии на логотип <img src="https://assets-global.website-files.com/660e8783c2152f6174eadc26/661304852a6aba8cccf8b761_menu%20logo.svg" alt="" width="Auto" class="image-62">  происходит переход на <a target="_blank" href="https://welltory.com">главную</a> страницу сайта

#### Логотип на странице <a target="_blank" href="https://welltory.com/science">Science</a> :

- [x] При нажатии на логотип <a href="https://welltory.com" class="logo header-logo"><img class="logo__img" src="https://welltory.com/wp-content/themes/Divi-child/img/hrt3.png" alt="logo"><span class="logo__text"><img src="https://welltory.com/wp-content/themes/Divi-child/img/welltory-logo.svg" alt="welltory-logo"></span></a> происходит переход на <a target="_blank" href="https://welltory.com">главную</a> страницу сайта

#### Логотип на странице <a target="_blank" href="https://welltory.com/science">Plans</a> :

- [x] При нажатии на логотип <svg width="165" height="34" fill="none" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" clip-rule="evenodd" d="M103.849 28.18c-.358 0-.475-.1-.507-.433l-.234-2.546V7.687c0-.336.124-.457.471-.457h1.629c.347 0 .471.12.471.457v17.974l.202 2.075v.007c.028.114.025.268-.042.334-.071.068-.241.102-.365.102h-1.625Zm17.629-1.616c1.542 1.522 3.639 2.36 5.906 2.36 2.289 0 4.4-.838 5.938-2.36 1.553-1.5 2.41-3.56 2.41-5.803 0-2.211-.857-4.275-2.41-5.807-1.538-1.521-3.649-2.359-5.938-2.359-2.267 0-4.364.838-5.906 2.36a7.876 7.876 0 0 0-1.816 2.636 8.116 8.116 0 0 0-.626 3.167c0 2.256.867 4.316 2.442 5.806Zm1.769-9.71c1.063-.997 2.531-1.543 4.137-1.543 1.617 0 3.124.563 4.133 1.542 1.038.938 1.631 2.36 1.631 3.905 0 .807-.145 1.528-.44 2.194a5.13 5.13 0 0 1-1.191 1.741 5.637 5.637 0 0 1-1.83 1.116c-.675.261-1.45.395-2.303.395a6.663 6.663 0 0 1-2.303-.395 6.5 6.5 0 0 1-1.83-1.113l-.004-.003a5.133 5.133 0 0 1-1.19-1.741 5.862 5.862 0 0 1-.405-2.194c0-1.535.579-2.957 1.595-3.905Zm-61.394-.425 2.638 11.75h4.12l3.357-14.744a.602.602 0 0 0-.018-.317.614.614 0 0 0-.355-.093h-1.671c-.473 0-.584.272-.608.437v.003L66.93 24.422h-.921l-2.453-10.957c-.057-.302-.21-.409-.576-.409h-3.005c-.352 0-.487.1-.576.416l-2.421 10.95h-.889l-2.453-10.957v-.003c-.018-.13-.114-.437-.573-.437h-1.67c-.235 0-.335.073-.367.104-.021.02-.043.123-.007.302l3.356 14.748h4.15l2.606-11.75h.722Zm95.262 16.802c-.256 0-.334-.056-.356-.09-.046-.066-.05-.227-.021-.31v-.004l1.233-4.617h-1.919l-4.323-14.754v-.003c-.028-.08-.053-.235.014-.331.036-.035.139-.097.363-.097h1.802c.32 0 .487.131.576.452l3.324 11.942h1.113l3.426-11.98v-.004c.057-.303.207-.41.576-.41h1.671c.185 0 .317.059.363.1.067.097.042.252.014.331v.004l-5.61 19.353v.004c-.057.303-.206.41-.576.41h-1.67v.004Zm-17.3-5.443c0 .31.128.427.472.427v.003h1.637c.344 0 .472-.117.472-.427V15.693h5.962c.344 0 .472-.118.472-.428v-1.781c0-.338-.125-.459-.472-.459h-8.071c-.348 0-.472.121-.472.459v14.304Zm-28.793-.007c.032.334.149.434.505.434v.003h1.621c.124 0 .293-.034.364-.103.067-.065.071-.22.042-.334v-.007l-.201-2.08v-9.999h3.111c.343 0 .47-.117.47-.427v-1.781c0-.338-.124-.458-.47-.458h-3.111v-2.905c0-.31-.127-.427-.47-.427h-1.624c-.343 0-.47.117-.47.427v15.104l.233 2.553Zm-28.037 1.143c-2.262 0-4.353-.838-5.892-2.36-1.55-1.47-2.404-3.53-2.404-5.806 0-1.12.206-2.184.61-3.166a7.72 7.72 0 0 1 1.794-2.638c1.538-1.521 3.63-2.359 5.892-2.359 1.22 0 2.382.216 3.46.639a7.917 7.917 0 0 1 2.662 1.786c1.546 1.624 2.35 3.88 2.273 6.36l-14.106.095.085.46c.273 1.288.922 2.336 1.932 3.119 1.014.752 2.287 1.15 3.687 1.15 1.517 0 2.8-.395 3.818-1.171a4.804 4.804 0 0 0 1.44-1.762h2.87c-.502 1.532-1.488 2.888-2.86 3.932a8.916 8.916 0 0 1-5.261 1.72Zm.103-13.613c-1.227 0-2.383.316-3.347.917a4.977 4.977 0 0 0-2.035 2.497l-.174.542h11.111l-.174-.542a4.977 4.977 0 0 0-2.035-2.497c-.964-.597-2.123-.917-3.346-.917Zm12.618 12.436c.032.347.133.433.514.433h1.653c.122 0 .288-.031.364-.097a.51.51 0 0 0 .05-.34v-.007l-.205-2.075V7.687c0-.336-.126-.457-.479-.457h-1.656c-.353 0-.479.12-.479.457v17.514l.238 2.546Z" fill="#fff"></path><path d="M30.333 16.337c-.234-5.735-4.396-6.89-6.34-6.835-3.019 0-5.575 1.212-7.684 3.635a.363.363 0 0 1-.568-.037c-2.307-3.31-7.341-3.88-9.9-2.595-2.659 1.335-3.833 3.665-3.833 6.167 0 10.003 10.159 16.665 14.159 16.665 3.333 0 14.513-8.5 14.166-17Z" fill="url(#logo_svg__a)"></path><path d="M3.833 14.007c-.166-2.167 2.834-3.834 4.834-4 1.94-.162 4.824.147 7.125 3.06a.33.33 0 0 0 .473.056c1.27-1.094 1.629-2.189 5.068-3.283-2 1-3.166 2-5.5 4.667-1.614 1.844-3.666 2.833-6.666 2.833-1.834 0-5.138-.794-5.334-3.333Z" fill="#C92E00"></path><path d="M18.333 21.005c.16.33-.006.614-.383.797-.377.182-.79.033-.95-.297-.16-.329-.005-.713.372-.896.377-.183.801.067.961.396ZM13.883 25.677c-.107-.35.1-.605.5-.728.401-.122.843.207.95.557.108.35-.16.588-.561.71-.401.123-.782-.189-.89-.539ZM6.5 22.005c-.107-.35.089-.715.408-.813.401-.122.893.15 1 .5.108.35-.216.525-.617.648-.4.122-.75-.199-.791-.335ZM21.4 15.54c0 .185-.127.334-.284.334-.156 0-.283-.15-.283-.334 0-.184.127-.333.283-.333.157 0 .284.15.284.333ZM13.107 22.703c0 .276-.238.5-.606.5s-.667-.224-.667-.5.299-.367.667-.367c.368 0 .606.09.606.367ZM21.666 26.336c0 .276-.238.5-.606.5s-.727-.224-.727-.5.359-.533.727-.533.606.257.606.533Z" fill="#FFAA54"></path><path opacity="0.2" d="M6.5.003c-2-.003-5 0-6.5.001 2.333 1.333 5.667 5.585 7.333 9.251.938 2.064.5 5.334 2.834 6.5 2.574 1.287 4.722-1.722 5.333-3 .111-.778.033-2.833-1.167-4.833-1.5-2.5-2.484-2.486-5.5-5.167C7.333 1.422 7.182.005 6.5.003Z" fill="#FF4D00"></path><path d="M8.833 15.17c0 .276-.39.5-.667.5a.5.5 0 1 1 0-1c.276 0 .667.224.667.5Z" fill="#CF0000"></path><path d="M13.5 10.592c.309-.013.578.443.591.772.014.33-.225.606-.534.619-.308.013-.568-.244-.582-.573-.013-.33.217-.805.526-.818Z" fill="#FFA600"></path><path d="M12.873 5.268c.309-.012.583.585.6 1.015.018.43-.217.789-.525.802-.309.012-.573-.326-.59-.756-.018-.43.207-1.048.515-1.06ZM17.8 8.813c.094.127-.042.385-.192.495-.15.11-.346.095-.44-.033-.092-.127-.047-.319.103-.428.15-.11.437-.162.53-.034Z" fill="#CF0000"></path><path d="M16.774 10.532c.108.147-.016.421-.166.53a.333.333 0 0 1-.466-.067.333.333 0 0 1 .076-.465c.15-.11.449-.145.556.002Z" fill="#FF6B30"></path><path d="M15.277 8.148c-.146-.108-.109-.407.002-.556a.333.333 0 0 1 .464-.074.333.333 0 0 1 .066.467c-.11.149-.385.272-.532.163Z" fill="#FEA900"></path><path d="M11.5 2.836c-.182-.014-.182-.149-.167-.334.014-.185.013-.393.195-.379a.333.333 0 0 1 .303.36c-.014.185-.15.367-.332.353Z" fill="#CC5616"></path><path d="M17.333 6.336c-.147-.108-.049-.268 0-.333.147-.199.414-.563.5-.5.12.09.032.427-.115.626-.08.109-.239.316-.385.207Z" fill="#E39932"></path><path d="M5 3.67c-.4-.267-.667-.5-1-.5-1 0-.667 1.5-.334 2 .334.5 1.334.833 1.667.667.333-.167.333-.5.333-.834 0-.333-.166-1-.666-1.333Z" fill="#FFB900"></path><path d="M10.5 8.504c-.834-.625-1.778-2.056-2.334-2.833-.287-.403-.496 0-.5.333 0 .333-.036 2.897.667 3.833 1 1.334 1.5 1.334 2.167.667.425-.425.666-1.5 0-2Z" fill="#FF5B0E"></path><path d="M6.833 11.504c0-.333-.667-1-1.167-1.667-.4-.533-.944-.555-1.167-.5-.11 0-.366.1-.5.5-.166.5.167 1 .5 1.167.15.074.834.167 1.334.667.425.424 1 .166 1-.167ZM14.622 14.714c-.53.496-2.043 1.401-2.874 1.606a.096.096 0 0 1-.112-.059c-.323-.807-.631-1.615-.47-2.423.29-1.444.945-1.388 1.334-1.166.758.433 1.642.498 2.146 1.94a.096.096 0 0 1-.024.102Z" fill="#FF6B30"></path><defs><radialGradient id="logo_svg__a" cx="0" cy="0" r="1" gradientUnits="userSpaceOnUse" gradientTransform="rotate(82.933 -.273 13.175) scale(24.3635 23.2241)"><stop stop-color="#FF6900"></stop><stop offset="0.503" stop-color="#FF4000"></stop><stop offset="0.768" stop-color="#B80747"></stop></radialGradient></defs></svg> происходит переход на <a target="_blank" href="https://welltory.com">главную</a> страницу сайта

### Список проверок, реализованных в mobile автотестах

- [x] Элементы управления отображаются
- [x] Раздел "Сериалы" отображается
- [ ] Раздел "Профиль" отображается

----

### Используемый стэк

<div>
  <img src="https://github.com/devicons/devicon/blob/master/icons/python/python-original.svg" title="Python" alt="Python" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/pytest/pytest-original.svg" title="PyTest" alt="PyTest" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/pycharm/pycharm-original.svg" title="PyCharm" alt="PyCharm" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/selenium/selenium-original.svg" title="Selenium" alt="Selenium" width="40" height="40"/>&nbsp;
  <img title="Selenoid" src="pictures/icons/selenoid.png" height="40" width="40"/>
  <img title="Selene" src="pictures/icons/selene.png" height="40" width="40"/>
  <img src="https://github.com/devicons/devicon/blob/master/icons/git/git-original.svg" title="Git" alt="Git" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/gitlab/gitlab-original.svg" title="GitLab" alt="GitLab" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/jira/jira-original.svg" title="Jira" alt="Jira" width="40" height="40"/>&nbsp;
  <img title="Allure Report" src="pictures/icons/Allure_Report.png" height="40" width="40"/>
  <img title="Allure TestOps" src="pictures/icons/AllureTestOps.png" height="40" width="40"/>
  <img title="Telegram" src="pictures/icons/tg.png" height="40" width="40"/>
</div>

----

### Локальный запуск автотестов

#### Для запуска web/UI автотестов выполнить в cli:
> [!NOTE]
> Ключ выбора версии `--browser-version` не обязателен
```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
pytest --browser-version=100 ./tests/web/
```

#### Для запуска mobile автотестов выполнить в cli:
> [!NOTE]
> Ключ `--context` не обязателен, по умолчанию тесты будут запущены на BrowserStack
* Для запуска на реальном устройстве указать ключ `--context=local_real_device`
* Для запуска на виртуальном устройстве указать ключ `--context=local_real_device`
* Для запуска на BrowserStack указать ключ `--context=bstack`

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
pytest --context=bstack ./tests/mobile/
```

#### Для запуска всех автотестов выполнить в cli:

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
pytest -s -v
```

#### Получение отчёта:
```bash
allure serve build/allure-results
```

----

### Проект в Jenkins
> <a target="_blank" href="https://jenkins.autotests.cloud/job/Ivi-mobile-and-UI-Auto-Tests/">Ссылка</a>

#### Параметры сборки
> [!NOTE]
> Параметры сборки не обязательны
```python
ENVIRONMENT = ['STAGE', 'PREPROD', 'PROD'] # Окружение
COMMENT = 'some comment' # Комментарий
```
#### Запуск автотестов в Jenkins
1. Открыть <a target="_blank" href="https://jenkins.autotests.cloud/job/Ivi-mobile-and-UI-Auto-Tests/">проект</a>

![jenkins project main page](ivi_ui_and_mobile_test_framework/pictures/jenkins_project_main_page.png)

2. Нажать "Build with Parameters"
3. Из списка "ENVIRONMENT" выбрать любое окружение
4. В поле "COMMENT" ввести комментарий
5. Нажать "Build"

![jenkins_build](ivi_ui_and_mobile_test_framework/pictures/jenkins_build.png)

----

### Allure отчет
#### <a target="_blank" href="https://jenkins.autotests.cloud/job/Ivi-mobile-and-UI-Auto-Tests/15/allure/">Общие результаты</a>
![allure_report_overview](ivi_ui_and_mobile_test_framework/pictures/allure_report_overview.png)

#### <a target="_blank" href="https://jenkins.autotests.cloud/job/Ivi-mobile-and-UI-Auto-Tests/15/allure/#suites">Результаты прохождения теста</a>

![allure_reports_behaviors](ivi_ui_and_mobile_test_framework/pictures/allure_reports_suites.png)

#### <a target="_blank" href="https://jenkins.autotests.cloud/job/Ivi-mobile-and-UI-Auto-Tests/15/allure/#graph">Графики</a>


![allure_reports_graphs](ivi_ui_and_mobile_test_framework/pictures/alluere_reports_graphs_1.png)
![allure_reports_graphs](ivi_ui_and_mobile_test_framework/pictures/alluere_reports_graphs_2.png)

----

### Интеграция с Allure TestOps
> <a target="_blank" href="https://allure.autotests.cloud/project/3910/dashboards">Ссылка на проект</a>

#### <a target="_blank" href="https://allure.autotests.cloud/project/3910/dashboards">Дашборд с общими показателями тестовых прогонов</a>

![allure_test_ops_dashboards](ivi_ui_and_mobile_test_framework/pictures/allure_testops_dashboards.png)

#### <a target="_blank" href="https://allure.autotests.cloud/project/3910/launches">История запуска тестовых наборов</a>

![allure_testops_launches](ivi_ui_and_mobile_test_framework/pictures/allure_testops_launches.png)

#### <a target="_blank" href="https://allure.autotests.cloud/project/3910/test-cases/28510?treeId=0">Тест кейсы</a>

![allure_testops_suites](ivi_ui_and_mobile_test_framework/pictures/allure_testops_suites.png)

#### <a target="_blank" href="https://allure.autotests.cloud/launch/33573/tree/551292/attachments?treeId=0">Тестовые артефакты</a>

![allure_testops_suites](ivi_ui_and_mobile_test_framework/pictures/allure_testops_test_attachments.png)

#### <a target="_blank" href="https://allure.autotests.cloud/project/3910/test-cases/28510?treeId=0">Ручной запуск авто теста из Allure TestOps</a>

![allure_testops_suites](ivi_ui_and_mobile_test_framework/pictures/allure_testops_manual_test_run.png)

1. Нажать на чек-бокс необходимого тест кейса
2. Нажать на "Bulk actions"
3. Нажать на "Run"

----

### Интеграция с Jira
> <a target="_blank" href="https://ed-qa-engineer.atlassian.net/jira/software/projects/KAN/boards/1">Ссылка на проект</a>

![jira_project](ivi_ui_and_mobile_test_framework/pictures/jira_project.png)

----

### Оповещения в Telegram
![telegram_allert](ivi_ui_and_mobile_test_framework/pictures/telegram_allert.png)

----

### Видео прохождения web/UI автотеста
![autotest_gif](ivi_ui_and_mobile_test_framework/pictures/autotest.gif)

----

### Видео прохождения mobile автотеста
![autotest_gif](ivi_ui_and_mobile_test_framework/pictures/test_mobile_video.gif)
