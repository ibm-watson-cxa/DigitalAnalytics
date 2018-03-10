# IBM DigitalAnalytics

IBM DigitalAnalytics is a digital analytics SDK as documented [here](https://developer.ibm.com/customer-engagement/tutorials/getting-started-digital-analytics-sdk-ios/)


## Getting Started

### Prerequisites

You need to have recent cocoapods version install on your Mac OS. Current version is 1.4.0. Please refer to cocoapods website for the details.

For SDK prerequisites and documentation, please refer to the SDK documentation [here](https://developer.ibm.com/customer-engagement/tutorials/getting-started-digital-analytics-sdk-ios/)

### Installing

Add following lines at the begining of your Podfile

`source 'https://github.com/ibm-watson-cxa/EOCore.git'`

`source 'https://github.com/ibm-watson-cxa/DigitalAnalytics.git'`

`source 'https://github.com/CocoaPods/Specs.git'`

Set platform as iOS 9

`platform :ios, '9.0'`

Uncomment use_frameworks

`use_frameworks!`

In the respective targets for your project in the Podfile add the following line if you want to use IBM DigitalAnalytics SDK's release version

`pod 'DigitalAnalytics'`

In the respective targets for your project in the Podfile add the following line if you want to use IBM DigitalAnalytics SDK's release version

`pod 'DigitalAnalyticsDebug'`


Remember you can use only one of  `pod 'DigitalAnalytics'` and `pod 'DigitalAnalyticsDebug'`. Do not use both at the same time.

## Troubleshooting

If you are using Debug version of IBM DigitalAnalytics SDK. i.e. `pod 'DigitalAnalyticsDebug'` , then you may edit your project's scheme in XCode and add environmental variable `DIGITAL_ANALYTICS_DEBUG` and set its value to 1; also add environmental variable `EODebug` and set its value to 1. This will make the SDK to start writing debug logs to your xcode console window. If and when you want to report issues, the DigitalAnalytics support engineers will ask you for these logs.


## Versioning

Current stable version of DigitalAnalytics SDK is 1.0.3.18


## License

License files can be read [here](https://github.com/ibm-watson-cxa/DigitalAnalytics/tree/master/Licenses)
