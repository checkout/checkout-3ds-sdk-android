# Android 3D Secure SDK from Checkout.com

The Checkout.com 3D Secure (3DS) mobile SDK allows you to provide a native 3DS2 experience in your mobile app, with visual styling that you can control.
<br/>
The SDK handles the device data collection, communication with the card issuer, and presentation of 3D Secure challenges to the customer when required.
<br/><br/>
👉  [See the Integration Guide with Code Examples](https://www.checkout.com/docs/risk-management/3d-secure/sessions/non-hosted-sessions/3d-secure-mobile-sdks)
<br/>
📚  [Read the reference documentation](https://checkout.github.io/checkout-mobile-docs/checkout-3ds-sdk-android/index.html)
<br/><br/>
## Features
- Supports <strong>3D Secure protocols 2.1.0 and 2.2.0</strong>.
- Presents <strong>native 3DS2 challenge screens</strong> to the user, with <strong>styling that you can customise</strong> to best fit your apps and branding.
- Optionally <strong>falls back to 3DS1</strong> when 3DS2 is not available, returning the same authentication result to your app as for 3DS2. (This option can be configured by Checkout.com for your account.)
- Supports a <strong>range of local languages and accessibility needs</strong>, and allows you to set your own string translations.
- Meets requirements from <strong>EMVCo and the PCI Security Standards Council</strong>, specifically set for 3DS SDKs, so you can be sure it is interoperable with card issuers and that your customers’ sensitive data stays secure.
  <br/><br/>
## Minimum Requirements

The 3DS SDK for Android supports apps targeting Android 5.0 (API level 21) and above.
<br/><br/>
## Getting Started

First, integrate the 3DS SDK into your app.
<br/><br/>
Then, configure your app to: 
<br/><br/>
1. Initialize the SDK with your preferred user interface options.
1. Configure the parameters for an authentication.
1. Request authentication and handle the result to continue your payment flow.
<br/><br/>
   
👉  [See the Integration Guide with Code Examples](https://www.checkout.com/docs/risk-management/3d-secure/sessions/non-hosted-sessions/3d-secure-mobile-sdks) for full details.
<br/>
📚  [Read the reference documentation](https://checkout.github.io/checkout-mobile-docs/checkout-3ds-sdk-android/index.html)
<br/><br/>

## Dependencies

The Android SDK depends on some external libraries:
<br/><br/>
-   To help maintain security, we use [SpongyCastle](https://rtyley.github.io/spongycastle/), [Jose JWT](https://connect2id.com/products/nimbus-jose-jwt), [Jetpack Security](https://developer.android.com/jetpack) and [Certificate Transparency Android](https://github.com/babylonhealth/certificate-transparency-android).
-   To help provide support and monitor the performance of the SDK, we use our own Checkout Event Logger.
<br/><br/>
## Help and Feedback

<strong>For help using the 3D Secure SDK</strong>, or to pass on your feedback, you can email our team at [support@checkout.com](mailto:support@checkout.com).
<br/><br/>
<strong>If you’ve found a bug</strong>, we encourage you to open an issue through [GitHub](https://github.com/checkout/checkout-3ds-sdk-android/issues). If your problem isn’t already listed, please detail the versions of the SDK and your development environment that you’re using, what you were hoping to accomplish, and what the actual result you observed was.
<br/><br/>
<strong>If you have an idea for a new feature</strong>, we’d also love to hear about it through GitHub. Please [open an issue](https://github.com/checkout/checkout-3ds-sdk-android/issues), detailing your idea and why it’s important for your project.
<br/><br/>
## License

This software is released under license. See [LICENSE](LICENSE.md) for details.
