---
-api-type: winrt property
---
 The binding source provides a separate value that is accessed by a different path, which acts as the singleton value that can substitute for any **null** value coming from a specific data item in the source. For example:```xaml
 Use resources to provide a value that's specific to your app in cases where the data source provided **null** and has no suitable property in another path to use as the substitution value. For example, ```xaml