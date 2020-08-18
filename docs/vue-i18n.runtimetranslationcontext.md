<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [vue-i18n](./vue-i18n.md) &gt; [RuntimeTranslationContext](./vue-i18n.runtimetranslationcontext.md)

## RuntimeTranslationContext interface

<b>Signature:</b>

```typescript
export interface RuntimeTranslationContext<Messages = {}, Message = string> extends RuntimeCommonContext<Message> 
```

## Properties

|  Property | Type | Description |
|  --- | --- | --- |
|  [messageCompiler](./vue-i18n.runtimetranslationcontext.messagecompiler.md) | <code>MessageCompiler&lt;Message&gt;</code> |  |
|  [messages](./vue-i18n.runtimetranslationcontext.messages.md) | <code>Messages</code> |  |
|  [modifiers](./vue-i18n.runtimetranslationcontext.modifiers.md) | <code>LinkedModifiers&lt;Message&gt;</code> |  |
|  [pluralRules](./vue-i18n.runtimetranslationcontext.pluralrules.md) | <code>PluralizationRules</code> |  |
|  [postTranslation](./vue-i18n.runtimetranslationcontext.posttranslation.md) | <code>PostTranslationHandler&lt;Message&gt; &#124; null</code> |  |
|  [processor](./vue-i18n.runtimetranslationcontext.processor.md) | <code>MessageProcessor&lt;Message&gt; &#124; null</code> |  |
|  [warnHtmlMessage](./vue-i18n.runtimetranslationcontext.warnhtmlmessage.md) | <code>boolean</code> |  |
