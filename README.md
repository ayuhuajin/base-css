
包含一些常用的样式，以及特效，仅供自己总结记录，如有错误，请指出

1.sass 中文网 https://www.sass.hk/install/ 安装教程

2.安装 Sass 首先需要下载 ruby https://rubyinstaller.org/downloads/

3.gem install sass

4.软件方式编译; 这里推荐 koala (把项目拖进 koala,实时编译, 后缀名为.scss 方能识别)

5.包含mobile与pc 重置样式

## 项目布局
```
├─public
│  └─img
│      ├─first
│      └─second
└─src             
    ├─assets
    │  ─css
    │  ─images
    │    └ ─qualityTracing
    │  └─js
    ├─common
    │  └─filter
    ├─components
    │  ├─alert
    │  ├─backEnd
    │  │  ├─circulationBusinessManage
    │  │  ├─driverManage
    │  │  ├─qualityCheckManage
    │  │  └─qualityTracing
    │  ├─bigDataPlatform
    │  ├─buyingAndSelling
    │  │  ├─fishSales
    │  │  ├─fryPurchase
    │  │  └─materialPurchase
    │  ├─common
    │  ├─dataAnalyze
    │  ├─enterpriseBigData
    │  ├─expense
    │  │  ├─expenseRecord
    │  │  └─expenseSetting
    │  ├─login
    │  ├─productionControl
    │  │  ├─cultureCycleManagement
    │  │  ├─feedingManagement
    │  │  ├─lossManagement
    │  │  ├─preventionManagement
    │  │  ├─productionPlan
    │  │  ├─proofingManagement
    │  │  ├─turnPondManagement
    │  │  └─waterQualityParameters
    │  │      ├─parameterInput
    │  │      └─parameterLine
    │  ├─qualityTracking
    │  ├─register
    │  ├─setting
    │  │  ├─companyManagement
    │  │  │  ├─baseSetting
    │  │  │  ├─companySetting
    │  │  │  ├─cultureBreed
    │  │  │  ├─pondSetting
    │  │  │  └─unitInformation
    │  │  ├─goodsSetting
    │  │  ├─materialSetting
    │  │  │  └─tabComponent
    │  │  ├─personalAuthorityManagement
    │  │  │  └─PersonManageComponent
    │  │  ├─purchaseUnit
    │  │  └─supplierManagement
    │  ├─smartDevice
    │  └─tablePackage
    ├─service
    ├─store
    │  └─modules
    └─views
```
