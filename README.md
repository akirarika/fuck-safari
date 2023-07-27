# fuck-safari

一个绝佳的浏览器升级提醒库，支持移动端，尤其是当你不希望用户使用较低版本的 Safari 时。

## 为什么要使用 Fuck Safari？

许多用户在使用陈旧的设备，但这没什么大不了的，如果你买了一台设备，使用三五年就要更换，这反而是不可接受的。

但真正的问题在于，由于设备开发商的傲慢（以前是 Microsoft，现在是 Apple），许多用户的系统自从购买之日起就没有再升级过。

这导致我们必须要花费大量精力去处理兼容性问题、放弃使用更好的新特性。尤其在旧的 Safari 上，更多是布局上的错误，这并非简单引入一些 Polyfill 就能解决的。

即便你遇到的问题能够引入 Polyfill 来解决，这也往往会导致我们的网页变慢。即便用户在使用支持更新特性的浏览器，也不得不运行这些旧的补丁代码。

想想看吧！诸多能显著提升开发者或用户体验的新功能，仅仅因为有该死的不到 1% 的用户在使用，却不得不花费 30% 或更多的精力去兼容他们的不愿升级的设备！

通过简单的配置，可以让你所不支持的用户访问你的网页时，看到的是一份事无巨细、就像照顾可爱宝宝一样的升级浏览器指南。**尤其对于 Safari 用户来说**，做了特别的照顾，因为他们坚信只要不升级自己的手机系统，那么他们的手机就永远不会卡顿。

你还可以指定模式，例如，你的网页是运行在 App 中，将会提示升级系统 WebView 而非用户的浏览器。对于 Android 5 之前的无法升级 WebView 的设备（老实说，谁还会在用？）会提醒升级手机系统。

我们的目标是支持到 IE8+，即便你的代码在 IE8 上会直接白屏不显示任何东西，也一样支持。

## 使用

开发中
