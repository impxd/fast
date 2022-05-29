---
id: fast-element.attributeconfiguration
title: AttributeConfiguration type
hide_title: true
---
<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[@microsoft/fast-element](./fast-element.md) &gt; [AttributeConfiguration](./fast-element.attributeconfiguration.md)

## AttributeConfiguration type

Metadata used to configure a custom attribute's behavior.

<b>Signature:</b>

```typescript
export declare type AttributeConfiguration = {
    property: string;
    attribute?: string;
    mode?: AttributeMode;
    converter?: ValueConverter;
};
```