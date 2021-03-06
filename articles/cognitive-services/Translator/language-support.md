---
title: Language support - Translator
titleSuffix: Azure Cognitive Services
description: Cognitive Services Translator supports the following languages for text to text translation using Neural Machine Translation (NMT).
services: cognitive-services
author: laujan
manager: nitinme
ms.service: cognitive-services
ms.subservice: translator-text
ms.topic: reference
ms.date: 06/10/2020
ms.author: lajanuar
---
# Language and region support for text and speech translation

Use Translator to translate to and from any of the 90 text translation languages and dialects. Neural Machine Translation (NMT) is the new standard for high-quality AI-powered machine translations and is available as the default using V3 of Translator when a neural system is available.

You can also use Translator in conjunction with Custom Translator to build neural translation systems that understand the terminology used in your own business and industry, and with Microsoft Speech Service to add speech translation to your app.

[Learn more about how machine translation works](https://www.microsoft.com/translator/mt.aspx)

## Text translation
Text Translation is available using the Translate operation to or from any of the languages available in Translator. The API also offers language detection using the Detect operation, transliteration using the Transliterate operation, and bilingual dictionaries using the Dictionary Lookup and Dictionary Examples operations. The available languages for each of these operations are listed below. 

### Translate

Translator supports the following languages for text to text translation. 

[View Translate operation reference documentation](reference/v3-0-translate.md)

| Language | Language code |
|:-|:-:|
| Afrikaans | `af` |
| Albanian | `sq` |
| Amharic | `am` |
| Arabic | `ar` |
| Armenian | `hy` |
| Assamese | `as` |
| Azerbaijani | `az` |
| Bangla | `bn` |
| Bosnian (Latin) | `bs` |
| Bulgarian | `bg` |
| Cantonese (Traditional) | `yue` |
| Catalan | `ca` |
| Chinese Simplified | `zh-Hans` |
| Chinese Traditional | `zh-Hant` |
| Croatian | `hr` |
| Czech | `cs` |
| Dari | `prs` |
| Danish | `da` |
| Dutch | `nl` |
| English | `en` |
| Estonian | `et` |
| Fijian | `fj` |
| Filipino | `fil` |
| Finnish | `fi` |
| French | `fr` |
| French (Canada) | `fr-ca` |
| German | `de` |
| Greek | `el` |
| Gujarati | `gu` |
| Haitian Creole | `ht` |
| Hebrew | `he` |
| Hindi | `hi` |
| Hmong Daw | `mww` |
| Hungarian | `hu` |
| Icelandic | `is` |
| Indonesian | `id` |
| Inuktitut | `iu` |
| Irish | `ga` |
| Italian | `it` |
| Japanese | `ja` |
| Kannada | `kn` |
| Kazakh | `kk` |
| Khmer | `km` |
| Klingon | `tlh-Latn` |
| Klingon (plqaD) | `tlh-Piqd` |
| Korean | `ko` |
| Kurdish (Central) | `ku` |
| Kurdish (Northern) | `kmr` |
| Lao | `lo` |
| Latvian | `lv` |
| Lithuanian | `lt` |
| Malagasy | `mg` |
| Malay | `ms` |
| Malayalam | `ml` |
| Maltese | `mt` |
| Maori | `mi` |
| Marathi | `mr` |
| Myanmar | `my` |
| Nepali | `ne` |
| Norwegian | `nb` |
| Odia | `or` |
| Pashto | `ps` |
| Persian | `fa` |
| Polish | `pl` |
| Portuguese (Brazil) | `pt` |
| Portuguese (Portugal) | `pt-pt` |
| Punjabi | `pa` |
| Queretaro Otomi | `otq` |
| Romanian | `ro` |
| Russian | `ru` |
| Samoan | `sm` |
| Serbian (Cyrillic) | `sr-Cyrl` |
| Serbian (Latin) | `sr-Latn` |
| Slovak | `sk` |
| Slovenian | `sl` |
| Spanish | `es` |
| Swahili | `sw` |
| Swedish | `sv` |
| Tahitian | `ty` |
| Tamil | `ta` |
| Telugu | `te` |
| Thai | `th` |
| Tigrinya | `ti` |
| Tongan | `to` |
| Turkish | `tr` |
| Ukrainian | `uk` |
| Urdu | `ur` |
| Vietnamese | `vi` |
| Welsh | `cy` |
| Yucatec Maya | `yua` |

> [!NOTE]
> Language code `pt` will default to `pt-br`, Portuguese (Brazil).

### Detect

Translator detects the following languages for translation and transliteration.

[View Detect operation reference documentation](reference/v3-0-detect.md)

| Language | Language code |
|:-|:-:|
| Afrikaans | `af` |
| Albanian | `sq` |
| Arabic | `ar` |
| Bulgarian | `bg` |
| Catalan | `ca` |
| Chinese Simplified | `zh-Hans` |
| Chinese Traditional | `zh-Hant` |
| Croatian | `hr` |
| Czech | `cs` |
| Danish | `da` |
| Dutch | `nl` |
| English | `en` |
| Estonian | `et` |
| Finnish | `fi` |
| French | `fr` |
| German | `de` |
| Greek | `el` |
| Gujarati | `gu` |
| Haitian Creole | `ht` |
| Hebrew | `he` |
| Hindi | `hi` |
| Hungarian | `hu` |
| Icelandic | `is` |
| Indonesian | `id` |
| Inuktitut | `iu` |
| Irish | `ga` |
| Italian | `it` |
| Japanese | `ja` |
| Klingon | `tlh-Latn` |
| Korean | `ko` |
| Kurdish (Central) | `ku-Arab` |
| Latvian | `lv` |
| Lithuanian | `lt` |
| Malay | `ms` |
| Maltese | `mt` |
| Norwegian | `nb` |
| Pashto | `ps` |
| Persian | `fa` |
| Polish | `pl` |
| Portuguese | `pt` |
| Romanian | `ro` |
| Russian | `ru` |
| Serbian (Cyrillic) | `sr-Cyrl` |
| Serbian (Latin) | `sr-Latn` |
| Slovak | `sk` |
| Slovenian | `sl` |
| Spanish | `es` |
| Swahili | `sw` |
| Swedish | `sv` |
| Tahitian | `ty` |
| Thai | `th` |
| Turkish | `tr` |
| Ukrainian | `uk` |
| Urdu | `ur` |
| Vietnamese | `vi` |
| Welsh | `cy` |
| Yucatec Maya | `yua` |

### Transliterate

The Transliterate method supports the following languages. In the "To/From", "<-->" indicates that the language can be transliterated from or to either of the scripts listed. The "-->" indicates that the language can only be transliterated from one script to the other.

[View Transliterate operation reference documentation](reference/v3-0-translate.md)


| Language    | Language code | Script | To/From | Script|
|:----------- |:-------------:|:-------------:|:-------------:|:-------------:|
| Arabic | `ar` | Arabic `Arab` | <--> | Latin `Latn` |
| Assamese | `as` | Bengali `Beng` | <--> | Latin `Latn` |
| Bangla  | `bn` | Bengali `Beng` | <--> | Latin `Latn` |
|Belarusian| `be` | Cyrillic `Cyrl`  | <--> | Latin `Latn` |
|Bulgarian| `bg` | Cyrillic `Cyrl`  | <--> | Latin `Latn` |
| Chinese (Simplified) | `zh-Hans` | Chinese Simplified `Hans`| <--> | Latin `Latn` |
| Chinese (Simplified) | `zh-Hans` | Chinese Simplified `Hans`| <--> | Chinese Traditional `Hant`|
| Chinese (Traditional) | `zh-Hant` | Chinese Traditional `Hant`| <--> | Latin `Latn` |
| Chinese (Traditional) | `zh-Hant` | Chinese Traditional `Hant`| <--> | Chinese Simplified `Hans` |
|Greek| `el` | Greek `Grek`  | <--> | Latin `Latn` |
| Gujarati | `gu`  | Gujarati `Gujr` | <--> | Latin `Latn` |
| Hebrew | `he` | Hebrew `Hebr` | <--> | Latin `Latn` |
| Hindi | `hi` | Devanagari `Deva` | <--> | Latin `Latn` |
| Japanese | `ja` | Japanese `Jpan` | <--> | Latin `Latn` |
| Kannada | `kn` | Kannada `Knda` | <--> | Latin `Latn` |
|Kazakh| `kk` | Cyrillic `Cyrl`  | <--> | Latin `Latn` |
|Korean| `ko` | Korean `Kore`  | <--> | Latin `Latn` |
|Kyrgyz| `ky` | Cyrillic `Cyrl`  | <--> | Latin `Latn` |
|Macedonian| `mk` | Cyrillic `Cyrl`  | <--> | Latin `Latn` |
| Malayalam | `ml` | Malayalam `Mlym` | <--> | Latin `Latn` |
| Marathi | `mr` | Devanagari `Deva` | <--> | Latin `Latn` |
|Mongolian| `mn` | Cyrillic `Cyrl`  | <--> | Latin `Latn` |
| Odia | `or` | Oriya `Orya` | <--> | Latin `Latn` |
|Persian| `fa` | Arabic `Arab`  | <--> | Latin `Latn` |
| Punjabi | `pa` | Gurmukhi `Guru`  | <--> | Latin `Latn`  |
|Russian| `ru` | Cyrillic `Cyrl`  | <--> | Latin `Latn` |
| Serbian (Cyrillic) | `sr-Cyrl` | Cyrillic `Cyrl`  | --> | Latin `Latn` |
| Serbian (Latin) | `sr-Latn` | Latin `Latn` | --> | Cyrillic `Cyrl`|
|Sindhi| `sd` | Arabic `Arab`  | <--> | Latin `Latn` |
|Sinhala| `si` | Sinhala `Sinh`  | <--> | Latin `Latn` |
|Tajik| `tg` | Cyrillic `Cyrl`  | <--> | Latin `Latn` |
| Tamil | `ta` | Tamil `Taml` | <--> | Latin `Latn` |
|Tatar| `tt` | Cyrillic `Cyrl`  | <--> | Latin `Latn` |
| Telugu | `te` | Telugu `Telu` | <--> | Latin `Latn` |
| Thai | `th` | Thai `Thai` | --> | Latin `Latn` |
|Ukrainian| `uk` | Cyrillic `Cyrl`  | <--> | Latin `Latn` |
|Urdu| `ur` | Arabic `Arab`  | <--> | Latin `Latn` |

### Dictionary

The dictionary supports the following languages to or from English using the Lookup and Examples methods.

View reference documentation for the [Dictionary Lookup](reference/v3-0-dictionary-lookup.md) and [Dictionary Examples](reference/v3-0-dictionary-examples.md) operations.

| Language    | Language code |
|:----------- |:-------------:|
| Afrikaans      | `af`          |
| Arabic       | `ar`          |
| Bangla      | `bn`          |
| Bosnian (Latin)      | `bs`          |
| Bulgarian      | `bg`          |
| Catalan      | `ca`          |
| Chinese Simplified      | `zh-Hans`          |
| Croatian      | `hr`          |
| Czech      | `cs`          |
| Danish      | `da`          |
| Dutch      | `nl`          |
| Estonian      | `et`          |
| Finnish      | `fi`          |
| French      | `fr`          |
| German      | `de`          |
| Greek      | `el`          |
| Haitian Creole      | `ht`          |
| Hebrew      | `he`          |
| Hindi      | `hi`          |
| Hmong Daw      | `mww`          |
| Hungarian      | `hu`          |
| Icelandic    | `is`  |
| Indonesian      | `id`          |
| Italian      | `it`          |
| Japanese      | `ja`          |
| Klingon      | `tlh`          |
| Korean      | `ko`          |
| Latvian      | `lv`          |
| Lithuanian      | `lt`          |
| Malay      | `ms`          |
| Maltese      | `mt`          |
| Norwegian      | `nb`          |
| Persian      | `fa`          |
| Polish      | `pl`          |
| Portuguese (Brazil)     | `pt`          |
| Romanian      | `ro`          |
| Russian      | `ru`          |
| Serbian (Latin)      | `sr-Latn`          |
| Slovak     | `sk`          |
| Slovenian      | `sl`          |
| Spanish      | `es`          |
| Swahili      | `sw`          |
| Swedish      | `sv`          |
| Tamil      | `ta`          |
| Thai      | `th`          |
| Turkish      | `tr`          |
| Ukrainian      | `uk`          |
| Urdu      | `ur`          |
| Vietnamese      | `vi`          |
| Welsh      | `cy`          |

### Access the Translator language list programmatically

You can retrieve a list of supported languages for Translator using the Languages method. You can view the list by feature, language code, as well as the language name in English or any other supported language. This list is automatically updated by the Microsoft Translator service as new languages are made available.

[View Languages operation reference documentation](reference/v3-0-languages.md)

## Customization

The following languages are available for customization to or from English using [Custom Translator](https://aka.ms/CustomTranslator).

| Language    | Language code |
|:----------- |:-------------:|
|Afrikaans|	`af`|
| Arabic       | `ar`          |
| Bangla      | `bn`          |
| Bosnian (Latin)      | `bs`          |
| Bulgarian      | `bg`          |
|Catalan|	`ca`	|
| Chinese Simplified      | `zh-Hans`          |
|Chinese Traditional|	`zh-Hant`	|
| Croatian      | `hr`          |
| Czech      | `cs`          |
| Danish      | `da`          |
| Dutch      | `nl`          |
| English    | `en`     |
| Estonian      | `et`          |
|Fijian|	`fj`	|
|Filipino|	`fil`	|
| Finnish      | `fi`          |
| French      | `fr`          |
| German      | `de`          |
| Greek      | `el`          |
| Gujarati|	`gu`	|
| Hebrew      | `he`          |
| Hindi      | `hi`          |
| Hungarian      | `hu`          |
| Icelandic | `is` |
| Indonesian|	`id`	|
| Irish | `ga`	|
| Italian      | `it`          |
| Japanese      | `ja`          |
|Kannada|`kn`|
| Korean      | `ko`          |
| Latvian      | `lv`          |
| Lithuanian      | `lt`          |
| Malagasy|	`mg`	|
| Malay|	`ms` |
|Maltese|	`mt`	|
| Maori| `mi`  |
| Marathi| `mr`  |
| Norwegian      | `nb`          |
| Persian      | `fa`          |
| Polish      | `pl`          |
| Portuguese (Brazil) | `pt` |
| Punjabi|`pa`|
| Romanian      | `ro`          |
| Russian      | `ru`          |
| Samoan|	`sm`	|
| Serbian (Latin)      | `sr-Latn`          |
| Slovak     | `sk`          |
| Slovenian      | `sl`          |
| Spanish      | `es`          |
| Swahili|	`sw`	|
| Swedish      | `sv`          |
|Tahitian|	`ty`	|
| Thai      | `th`          |
|Tongan|	`to`	|
| Turkish      | `tr`          |
| Ukrainian      | `uk`          |
| Urdu|	`ur`	|
| Vietnamese      | `vi`          |
| Welsh | `cy` |

## Speech Translation
Speech Translation is available by using Translator with Cognitive Services Speech service. View [Speech Service documentation](../speech-service/index.yml) to learn more about using speech translation and to view all of the [available language options](../speech-service/language-support.md).

### Speech-to-text
Convert speech into text in order to translate to the text language of your choice. Speech-to-text is used for speech to text translation, or for speech-to-speech translation when used in conjunction with speech synthesis.

| Language    |
|:----------- |
|Arabic|
|Cantonese (Traditional)|
|Catalan|
|Chinese Simplified|
|Chinese Traditional|
|Danish|
|Dutch|
|English|
|Finnish|
|French|
|French (Canada)|
|German|
|Gujarati|
|Hindi|
|Italian|
|Japanese|
|Korean|
|Marathi|
|Norwegian|
|Polish|
|Portuguese (Brazil)|
|Portuguese (Portugal)|
|Russian|
|Spanish|
|Swedish|
|Tamil|
|Telugu|
|Thai|
|Turkish|

### Text-to-speech
Convert text to speech. Text-to-speech is used to add audible output of translation results, or for speech-to-speech translation when used with Speech-to-text. 

| Language |
|:-|
| Arabic |
| Bulgarian |
| Cantonese (Traditional) |
| Catalan |
| Chinese Simplified |
| Chinese Traditional |
| Croatian |
| Czech |
| Danish |
| Dutch |
| English |
| Finnish |
| French |
| French (Canada) |
| German |
| Greek |
| Hebrew |
| Hindi |
| Hungarian |
| Indonesian |
| Italian |
| Japanese |
| Korean |
| Malay |
| Norwegian |
| Polish |
| Portuguese (Brazil) |
| Portuguese (Portugal) |
| Romanian |
| Russian |
| Slovak |
| Slovenian |
| Spanish |
| Swedish |
| Tamil |
| Telugu |
| Thai |
| Turkish |
| Vietnamese |

## View the language list on the Microsoft Translator website

For a quick look at the languages, the Microsoft Translator website shows all the languages supported by Translator for text translation and Speech service for speech translation. This list doesn't include developer-specific information such as language codes.

[See the list of languages](https://www.microsoft.com/translator/languages.aspx)
