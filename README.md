# Awesome Rails Gem zh-CN [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
Awesome Rails Gem 中文版

熟悉大牛们写的 gem，不用重复造轮子，将更多的精力放到更有意义的事情上。

* [目录](#目录)
  * [用户](#用户)
  * [模型](#模型)
  * [插件](#插件)
  * [API](#api)
  * [邮件](#邮件)
  * [文件上传](#文件上传)
  * [搜索](#搜索)
  * [定时任务](#定时任务)
  * [视图](#视图)
  * [环境变量](#环境变量)
  * [后台管理](#后台管理)
  * [日志](#日志)
  * [调试](#调试)
  * [代码风格](#代码风格)
  * [测试](#测试)
  * [安全](#安全)
  * [生产](#生产)
  * [错误日志](#错误日志)
  * [资源管道](#资源管道)

## 用户

### 认证
* [Devise](https://github.com/plataformatec/devise/) - 用于快速构建用户功能，如：注册，登陆，个人设置，找回密码...
* [Knock](https://github.com/nsarno/knock) - 符合 JWT (JSON Web Token) 规范的认证 API
* [Clearance](https://github.com/thoughtbot/clearance) - 基于邮箱密码认证
* [Devise token auth](https://github.com/lynndylanhurley/devise_token_auth) - 基于 Token 认证的 JSON API

### 授权
* [Pundit](https://github.com/elabs/pundit) - Pundit 提供一系列方法来扩展 Ruby 的基本类和面相对象的设计模式，用以构建简单、强壮、可伸缩的认证系统
* [cancancan](https://github.com/CanCanCommunity/cancancan) - 扩展 CanCan，可以规定某个用户拥有哪些资源，所有权限都定义在一个单独的地方( Ability 类)
* [rolify](https://github.com/RolifyCommunity/rolify) - 角色管理
* [acl9](https://github.com/be9/acl9/) - 基于角色的认证系统，并且提供简洁的 DSL


### Omniauth
* [omniauth-facebook](https://github.com/mkdynamic/omniauth-facebook)
* [omniauth-google-oauth2](https://github.com/zquestz/omniauth-google-oauth2)
* [omniauth-weibo-oauth2](https://github.com/beenhero/omniauth-weibo-oauth2)
* [omniauth-twitter](https://github.com/arunagw/omniauth-twitter)
* [omniauth-github](https://github.com/intridea/omniauth-github)
* [omniauth-linkedin-oauth2](https://github.com/decioferreira/omniauth-linkedin-oauth2)

## 模型
* [Enumerize](https://github.com/brainspec/enumerize) - 适用枚举类型的属性，支持 i18n 、activerecord、mongoid，并可以集成到 Simple Form
* [counter_culture](https://github.com/magnusvk/counter_culture) - 计数缓存
* [custom_counter_cache](https://github.com/cedric/custom_counter_cache) - 简单的自定义技术缓存，可以在 model间共用
* [Sequenced](https://github.com/djreimer/sequenced) - 管理 排序性 id 的 gem
* [FriendlyId](https://github.com/norman/friendly_id) - URL 友好的 ID
* [AASM](https://github.com/aasm/aasm) - 状态机
* [PaperTrail](https://github.com/airblade/paper_trail) - 记录版本、审计用的，记录数据的变化
* [paranoia](https://github.com/rubysherpas/paranoia) - 假删除
* [Validates](https://github.com/kaize/validates) - 提供一系列有用的自定义验证，包括Email, Url, Slug, Money, Ip, AssociationLength, AbsolutePath, UriComponent, Color, Ean
* [globalize](https://github.com/globalize/globalize) - 数据翻译中的 i18n 库
* [deep_cloneable](https://github.com/moiristo/deep_cloneable) - 深度拷贝、支持关系拷贝、可选拷贝
* [social_shares](https://github.com/Timrael/social_shares) - 检查 url 在社交网络中的共享次数
* [public_activity](https://github.com/chaps-io/public_activity) - 活动追踪，类似 github的 Public Activity
* [goldiloader](https://github.com/salsify/goldiloader) - activerecode 预加载，用来减少数据库查询次数
* Tagging
  * [ActsAsTaggableOn](https://github.com/mbleigh/acts-as-taggable-on) - 打标记
  * [closure_tree](https://github.com/mceachen/closure_tree) - 多层级标记

## 插件
* [Spreadsheet](https://github.com/zdavatz/spreadsheet) - 读写 Spreadsheet 文档
* [Chartkick](https://github.com/ankane/chartkick) - 用一行 ruby 代码创建漂亮的 js 图表
* [kaminari](https://github.com/amatsuda/kaminari) - 很火的分页插件
* [CKEditor](https://github.com/galetahub/ckeditor) - 所见即所得编辑器
* [HTML::Pipeline](https://github.com/jch/html-pipeline) - html 处理器
* [Slack Notifier](https://github.com/stevenosloan/slack-notifier) 给 slack 发通知
* [Rails ERD](https://github.com/voormedia/rails-erd) - 生成实体关系图
* [Parity](https://github.com/thoughtbot/parity) - 为 heroku 提供 shell 命令
* [Airbrussh](https://github.com/mattbrictson/airbrussh) - 美化 SSHKit 和 Capistrano 的输出内容

## API
* [Grape](https://github.com/ruby-grape/grape) - 提供 REST-ful APIs
* [ActiveModel::Serializers](https://github.com/rails-api/active_model_serializers) - 通过配置方便生成 JSON
* [Jbuilder](https://github.com/rails/jbuilder) - 提供 DSL 来定义 JSON 结构
* [rest-client](https://github.com/rest-client/rest-client) - HTTP 和 REST 客户端
* [has_scope](https://github.com/plataformatec/has_scope) - 在 controller 中使用named scopes
* Documentation
  * [Grape Swagger](https://github.com/ruby-grape/grape-swagger) - 为 Grape API 自动生成文档
  * [Grape Swagger UI](https://github.com/swagger-api/swagger-ui) - Grape Swagger 的界面
  * [apiary](https://apiary.io/) - [收费]团队协作工具，一起设计、原型、文档和测试 API
  * [apiblueprint](https://apiblueprint.org) - API 文档

## 邮件
* [letter_opener](https://github.com/ryanb/letter_opener) - 在浏览器中预览邮件，而不用真实的发送

## 文件上传
* [Carrierwave](https://github.com/carrierwaveuploader/carrierwave) - 为 Rails, Sinatra 等框架负责文件上传，很流行
  * [carrierwave_backgrounder](https://github.com/lardawge/carrierwave_backgrounder) - 分流图片处理、并且在后台存储，用 Delayed Job, Resque, Sidekiq 等
  * [CarrierWave Crop](https://github.com/kirtithorat/carrierwave-crop/) - 裁剪上传的图片
  * [CarrierWave ImageOptimizer](https://github.com/jtescher/carrierwave-imageoptimizer) - 优化上传的图片
* [remotipart](https://github.com/JangoSteve/remotipart) - Rails jQuery 上传控件
* [MiniMagick](https://github.com/minimagick/minimagick) - ImageMagick/GraphicsMagick 的 ruby 包装
* [fog](https://github.com/fog/fog) - 云服务管理
* [refile](https://github.com/refile/refile) - 流行的上传库
* [Paperclip](https://github.com/thoughtbot/paperclip) - ActiveRecord 附件管理
* [Dragonfly](http://markevans.github.io/dragonfly) -  on-the-fly 上传工具

## 搜索
* [ransack](https://github.com/activerecord-hackery/ransack) - 可以创建简单或复杂的搜索表单
* [elasticsearch-rails](https://github.com/elastic/elasticsearch-rails) - 集成 Elasticsearch
* [Chewy](https://github.com/toptal/chewy) - 高度集成 Elasticsearch
* [Chewy_Kiqqer](https://github.com/averell23/chewy_kiqqer) - [不再维护]
* [pg_search](https://github.com/Casecommons/pg_search) - 充分利用 postgres 的优势
* [sunspot](https://github.com/sunspot/sunspot) - 与 Solr 集成
* [searchkick](https://github.com/ankane/searchkick) - 集成 Elasticsearch

## 定时任务
* [Whenever](https://github.com/javan/whenever) - 定时任务
* [Resque](https://github.com/resque/resque) - 基于 Redis 的后台延时处理任务
* [Rufus-Scheduler](https://github.com/jmettraux/rufus-scheduler) - 又一个定时任务
* [Delayed Job](https://github.com/collectiveidea/delayed_job) -  基于数据库的后台延时处理任务
* [Sidekiq](https://github.com/mperham/sidekiq) - 后台延时处理任务
  * [sidetiq](https://github.com/tobiassvn/sidetiq) - Sidekiq 的循环任务
  * [sidekiq-cron](https://github.com/ondrejbartas/sidekiq-cron) - Sidekiq 的又一个循环任务
  * [sidekiq-scheduler](https://github.com/Moove-it/sidekiq-scheduler) -  Sidekiq 的又一个循环任务
* [Sucker Punch](https://github.com/brandonhilkert/sucker_punch) - 后台延时处理任务，不需要额外进程

## 视图
* [formtastic](https://github.com/justinfrench/formtastic) - 创建表单的 DSL
* [Simple Form](https://github.com/plataformatec/simple_form) - 更加灵活的表单 DSL
* [Nested Form](https://github.com/ryanb/nested_form) - 级联的表单 DSL，兼容 Simple Form
* [meta-tags](https://github.com/kpumuk/meta-tags) - SEO 相关的库
* [active_link_to](https://github.com/comfy/active_link_to) - 根据当前 url 自动加 active 样式
* [cells](https://github.com/apotonick/cells) - 把公用的 UI 写到 view models
* [i18n Country Code Select](https://github.com/onomojo/i18n_country_select) - 国家代码列表
* [Subdivision Select](https://github.com/cllns/subdivision_select) - 二级下拉列表，包括国家、省
* [cocoon](https://github.com/nathanvda/cocoon) - 级联的表单 DSL

## 环境变量
* [Config](https://github.com/railsconfig/config) - 多环境的 YAML 配置文件
* [Figaro](https://github.com/laserlemon/figaro) - 针对 heroku 的配置办法
* [dotenv](https://github.com/bkeepers/dotenv) - 将环境变量写到 .env 文件中
* [opsworks-dotenv](https://github.com/mikamai/opsworks-dotenv) - 用 OpsWorks, Chef 和 Dotenv 配置环境变量

## 后台管理
* [ActiveAdmin](http://activeadmin.info) - 后台管理框架
  - [active_skin](https://github.com/rstgroup/active_skin): 为 ActiveAdmin 制作的皮肤
* [RailsAdmin](https://github.com/sferik/rails_admin) - 后台管理
* [Typus](https://github.com/typus/typus) - 管理界面，让受信任用户管理数据
* [administrate](https://github.com/thoughtbot/administrate) - 灵活的后台管理

## 日志
* [Impressionist](https://github.com/charlotte-ruby/impressionist) - 记录页面访问情况，还可以为一个访问记录几次
* [Ahoy](https://github.com/ankane/ahoy) - 记录访问情况，和事件
* [Lograge](https://github.com/roidrage/lograge) - 改变 rails 默认的日志，使变得更好

## 调试
* [byebug](https://github.com/deivid-rodriguez/byebug) - 简单易用，不依赖其他代码
  * [pry-byebug](https://github.com/deivid-rodriguez/pry-byebug) - 集成 Pry 与 byebug
* [pry-rails](https://github.com/rweng/pry-rails) - 使用 pry 打开 rails console
* [awesome_print](https://github.com/michaeldv/awesome_print) - 将 ruby 对象打印的更加漂亮
* [web-console](https://github.com/rails/web-console) - 把 console 加到 rails 中
* [spring](https://github.com/rails/spring) -  rails 预加载
* [rails-footnotes](https://github.com/josevalim/rails-footnotes) - 将调试信息显示到脚注
* [g](https://github.com/jugyo/g) - [不更新]
* [terminal-notifier](https://github.com/julienXX/terminal-notifier) - 发送 Mac OS X 通知
* [Better Errors](https://github.com/charliesome/better_errors) - 替代原生的错误页面，更加漂亮有用
* [RailsPanel](https://github.com/dejan/rails_panel) - Chrome 扩展，在浏览器上更好的显示 rails 日志

## 代码风格
* [RuboCop](https://github.com/bbatsov/rubocop) - 代码分析，遵循很多代码规范
* [Rails Best Practice](https://github.com/railsbp/rails_best_practices) - 检查代码质量
* [Metric Fu]( https://github.com/metricfu/metric_fu) - 检查代码质量
* [Pronto](https://github.com/mmozuras/pronto) - 自动检查变化的代码，与 github 集成

## 测试
* [rspec-rails](https://github.com/rspec/rspec-rails) - 测试框架
* [Capybara](https://github.com/jnicklas/capybara) -模拟真实用户交互 测试 Web 应用，有这些驱动：
  - [capybara-webkit](https://github.com/thoughtbot/capybara-webkit) - 使用 QtWebkit 的 webkit
  - [selenium-webdriver](https://github.com/vertis/selenium-webdriver) - webdriver 支持
  - [poltergeist](https://github.com/teampoltergeist/poltergeist) - headless WebKit browser，使用 PhantomJS
  - [page-object](https://github.com/cheezy/page-object) - 创建灵活的页面对象来做 web 测试
* [factory_girl](https://github.com/thoughtbot/factory_girl) - 专门用来构造模拟测试数据的,完美替代Fixture的工具
* [factory_girl_rails](https://github.com/thoughtbot/factory_girl_rails) - factory_girl 集成到 Rails
* [factory_factory_girl](https://github.com/st0012/factory_factory_girl) - 根据命名规则，生成 factory 文件
* [Database Cleaner](https://github.com/DatabaseCleaner/database_cleaner) - 一系列清理数据库的策略
* [shoulda-matchers](https://github.com/thoughtbot/shoulda-matchers) - 提供很多 matchers 来测试 Rails 的函数
* [ResponseCodeMatchers](https://github.com/r7kamura/response_code_matchers) -  rspec matchers 匹配 http 返回值
* [SimpleCov](https://github.com/colszowka/simplecov) - 代码测试覆盖分析工具
* [Timecop](https://github.com/travisjeffery/timecop) - 用来测试时间相关，可以冻结时间、时间旅行
* [VCR](https://github.com/vcr/vcr) - 记录 http 的返回内容，并在以后的测试中快速准确的重现

### 安全
* [brakeman](https://github.com/presidentbeef/brakeman) - 静态分析工具，检查程序的安全缺陷
* [bundle-audit](https://github.com/rubysec/bundler-audit) - 检查 Bundle 的补丁等级，包括易受攻击版本和不安全的 gem 源等
* [Secure Headers](https://github.com/twitter/secureheaders) -  自动设置安全相关的 headers

## 生产
* [Capistrano](https://github.com/capistrano/capistrano) - 远程服务器部署工具
* [Slowpoke](https://github.com/ankane/slowpoke) - Rack::Timeout 的升级版
* [Rack Attack](https://github.com/kickstarter/rack-attack) - 防止恶意攻击、限制访问频率
* [Responders](https://github.com/plataformatec/responders) - 一系列 responders
* [production_rails](https://github.com/ankane/production_rails) - Rails Best practices，一系列 Gem
* [Mina](https://github.com/mina-deploy/mina) -  快速部署、服务器自动化工具

## 错误日志
* [Rollbar](https://github.com/rollbar/rollbar-gem) - 记录错误日志并汇总到 Rollbar
* [Airbrake](https://github.com/airbrake/airbrake) - 与 Airbrake 集成
* [Errbit](https://github.com/errbit/errbit) - 兼容 Airbrake，开源

## 资源管道
* [Alaska](https://github.com/mavenlink/alaska) - ExecJS 运行时保持与 nodejs 连接，加速 coffeescript 的编译和部署

## 贡献

欢迎大家贡献代码，请先阅读 [贡献指南](contributing.md) 。

