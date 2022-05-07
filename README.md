# awesome-quant-cn
awesome quant中文版，最近会更新比较频繁，欢迎关注github及微信公众号～

## 金融数据
* [tushare](https://waditu.com/document/1?doc_id=131) -- 分为tushare和tushare pro。tushare pro数据覆盖范围广，接口调用简单,响应快速，但获取次数较多时有积分限制。老版api有下线风险
* [akshare](https://github.com/akfamily/akshare) -- 基于 Python 的财经数据接口库, 目的是实现对股票、期货、期权、基金、外汇、债券、指数、加密货币等金融产品的基本面数据、实时和历史行情数据、衍生数据从数据采集、数据清洗到数据落地的一套工具
* [BaoStock](http://baostock.com) -- 一个免费、开源的证券数据平台（无需注册），通过python API获取证券数据信息，返回的数据格式为pandas DataFrame类型，同时支持通过BaoStock的数据存储功能，将数据全部保存到本地后进行分析
* [yfinace](https://github.com/ranaroussi/yfinance) -- yahoo财经
* [jqdatasdk](https://www.joinquant.com/help/api/help#name:JQData) -- 聚宽提供的本地量化金融数据服务。申请可以获得三个月的试用期，一个手机号仅限注册一次。[申请链接](https://www.joinquant.com/default/index/sdk?utm_campaign=JQData%E7%94%B3%E8%AF%B7&utm_medium=%E7%BD%91%E9%A1%B5&utm_source=%E8%81%9A%E5%AE%BD&gio_link_id=xRxqAjP5)
* [rqdata](https://www.ricequant.com/welcome/pricing) -- 米筐数据服务。免费试用15天，试用账户进行了每天 50MB 的配额限制，[申请链接](https://www.ricequant.com/welcome/purchase#1)
* [tqsdk](https://doc.shinnytech.com/tqsdk/latest/intro.html) -- TqSdk免费版本提供全部的期货、商品/金融期权和上证50、沪深300和中证500的实时行情，TqSdk专业版可提供A股股票的实时和历史行情
* [efinance](https://github.com/Micro-sheep/efinance) -- 个人打造的用于获取股票、基金、期货数据的免费开源 Python 库
* [easyquotation](https://github.com/shidenggui/easyquotation) -- 快速获取新浪/腾讯的全市场行情

## 回测引擎
* [zipline](https://github.com/quantopian/zipline) -- Quantopian开源的本地量化回测平台，可以和pyfolio和alphalen无缝衔接
* [rqalpha](https://github.com/ricequant/rqalpha) -- Ricequant开源的本地量化回测平台，在 API 设计上和 Quantopian 保持一致，但License完全排除商业用途
* [backtrader](https://github.com/mementum/backtrader) -- 纯python实现的在线交易和回测平台
* [zvt](https://github.com/zvtvz/zvt/blob/master/README-cn.md) -- 包含可扩展的数据recorder，api，因子计算，选股，回测，交易,以及统一的可视化，抽象度较高
* [bt](https://github.com/pmorissette/bt) -- 基于ffn打造的python回测框架， 目标是充分利用python生态，不重复造轮子
* [QUANTAXIS](https://github.com/QUANTAXIS/QUANTAXIS) -- 支持任务调度 分布式部署的 股票/期货/期权 数据/回测/模拟/交易/可视化/多账户 纯本地量化解决方案

## 数据分析
* [numpy](https://numpy.org/) -- python科学计算基础包，开源，高性能，支持矩阵运算
* [pandas](https://pandas.pydata.org/) -- python数据分析工具，开源，功能强大，运行速度快

## 指标&风险分析
* [TA-Lib](https://ta-lib.org/) -- 交易软件开发广泛使用的技术分析lib，包括了200多个技术指标，如MACD, RSI等
* [ta-lib for python](https://mrjbq7.github.io/ta-lib/) -- python封装的ta-lib，使用Cython和Numpy高效实现，比使用SWIG接口的原始版本快2-4倍
* [empyrical](https://github.com/quantopian/empyrical) -- Quantopian开源的常见金融风险指标
* [pyfolio](https://github.com/quantopian/pyfolio) -- Quantopian开源的用图形表示的金融投资组合性能和风险分析的Python库，可以参考[full_tear_sheet_example.ipynb](https://github.com/quantopian/pyfolio/blob/master/pyfolio/examples/full_tear_sheet_example.ipynb)
* [quantstats](https://github.com/ranaroussi/quantstats) -- 更深层次的python量化分析和风险指标

## 可视化
* [Matplotlib](https://matplotlib.org/) -- python及numpy数值计算库的绘图lib库
* [seaborn](https://github.com/mwaskom/seaborn) -- 基于matplotlib的python可视化lib库
* [mplfinance](https://github.com/matplotlib/mplfinance) -- 使用matplotlib对金融市场数据可视化
* [Bokeh](https://bokeh.org/) -- python构建的基于浏览器的交互式图形库
* [plotly.py](https://github.com/plotly/plotly.py)--基于plotly.js构建，plotly.py是一个交互式的基于浏览器的图形库
* [pyecharts](https://pyecharts.org/#/) -- 对Echarts的python封装，特性包括简洁的 API 设计，囊括了 30+ 种常见图表，支持主流 Notebook 环境，高度灵活的配置项，可轻松搭配出精美的图表等

## 数据存储
* [peewee](http://docs.peewee-orm.com/en/latest/index.html)--简单、轻量级的orm
* [bcolz](https://github.com/Blosc/bcolz) -- bcolz 压缩率高，性能好，列式存储容器，可以用来作为底层回测数据存储格式

## 实盘交易
* [vnpy](https://github.com/vnpy/vnpy) -- 基于Python的开源量化交易系统开发框架
* [Futu OpenAPI](https://openapi.futunn.com/futu-api-doc/intro/intro.html) -- 功能主要有两部分：行情和交易。支持香港、美国、A 股市场的行情数据，涉及的品类包括股票、指数、期权、期货等；支持香港、美国、A 股、新加坡、日本 5 个市场的交易能力，涉及的品类包括股票、期权、期货等
* [tigeropen](https://quant.itiger.com/openapi/py-docs/zh-cn/docs/intro/quickstart.html) -- 老虎开放平台提供的直接管理交易、查看帐户信息、查询行情变动及交易支持功能
* [WonderTrader](https://github.com/wondertrader/wondertrader) -- 一个基于C++核心模块的，适应全市场全品种交易的，高效率、高可用的量化交易开发框架

## 策略研究平台
* [聚宽](https://www.joinquant.com/) -- 量化平台，提供多种数据方便投资研究；提供多种的策略评价指标与评价维度；支持多种策略的编写、回测、模拟、实盘
* [米筐](https://www.ricequant.com/) -- 米筐科技专注于为用户提供快速便捷、功能强大的量化交易和分析工具。用户可以使用基于浏览器（网上回测平台）或本地化（RQAlpha 等项目）的米筐科技产品，随时、随地开发自己的交易策略，验证自己的投资思路
* [优矿](https://uqer.datayes.com/) -- 量化平台，使用通联数据，支持回测功能

## 量化书籍
* [海龟交易法则](https://book.douban.com/subject/2339892/) -- 豆瓣评分8.5分。原版海龟首次揭密适用于任何市场的交易策略
* [以交易为生（原书第2版）](https://book.douban.com/subject/27093851/) -- 豆瓣评分8.3分。被众多交易员誉为现代交易经典之作。对于投机入门者来说，这本书的语言更浅显易懂，作者以心理的视角剖析了我们身为普通投资者的交易心理弱点，同时又为我们设计了一套有效的工具来理性面对分析市场。用无数深入浅出的例子，揭示了交易纪律、交易系统、交易风险、资金管理、交易日志这些交易者的必备武器

## 其他资源
* [awesome-quant](https://github.com/wilsonfreitas/awesome-quant) -- 可以参考

## 交流
* 微信公众号：诸葛说talk
* 博客：<https://zhugetalk.cn/>