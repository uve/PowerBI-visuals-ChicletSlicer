# NPM-packages

PowerBI NEW API doesn't provide. So all internal modules used by custom visuals has been exported as independent.
If your visual uses such modules you should import them into project manually.

1. Save npm-package
```bash
npm install --save https://github.com/vtkalek/powerbi-visuals-utils-arrayextensions
```
2. Add Typings to your project.

3. Add package js-file into your pbiviz.json file.


Here is list of the packages moved from [PowerBI Core](https://github.com/Microsoft/PowerBI-visuals-core) project:

* [ArrayExtensions](https://github.com/vtkalek/powerbi-visuals-utils-arrayextensions)
* [AxisHelper](https://github.com/vtkalek/powerbi-visuals-utils-axishelper)
* [Color](https://github.com/vtkalek/powerbi-visuals-utils-color)
* [ColorUtility](https://github.com/uve/powerbi-visuals-utils-colorutility)
* [converterHelper](https://github.com/uve/powerbi-visuals-utils-converterhelper)
* [createEnumType](https://github.com/uve/powerbi-visuals-utils-enumtype)
* [controls.TouchUtils](https://github.com/ignatvilesov/powerbi-visuals-utils-controls-touchutils)
* [ColorHelper](https://github.com/ignatvilesov/powerbi-visuals-utils-colorhelper)
* [CssConstants](https://github.com/uve/powerbi-visuals-utils-cssconstants)
* [DataColorPalette](https://github.com/vtkalek/powerbi-visuals-utils-datacolorpalette)
* [DataLabelManager](https://github.com/vtkalek/powerbi-visuals-utils-datalabelmanager)
* [dataLabelUtils](https://github.com/vtkalek/powerbi-visuals-utils-datalabelutils)
* [DataRoleHelper](https://github.com/ignatvilesov/powerbi-visuals-utils-datarolehelper)
* [DataViewObjects](https://github.com/ignatvilesov/powerbi-visuals-utils-dataviewobjects)
* [DateTimeSequence ](https://github.com/ignatvilesov/powerbi-visuals-utils-datetimesequence)
* [DisplayUnitSystem ](https://github.com/ignatvilesov/powerbi-visuals-utils-displayunitsystem)
* [DisplayunitSystemType ](https://github.com/ignatvilesov/powerbi-visuals-utils-displayunitsystemtype)
* [Double ](https://github.com/ignatvilesov/powerbi-visuals-utils-double)
* [EnumExtensions ](https://github.com/ignatvilesov/powerbi-visuals-utils-enumextensions)
* [FontUtils](https://github.com/vtkalek/powerbi-visuals-utils-fontutils)
* [Formatting ](https://github.com/ignatvilesov/powerbi-visuals-utils-formatting)
* [FormattingService ](https://github.com/ignatvilesov/powerbi-visuals-utils-formattingservice)
* [Imargin ](https://github.com/ignatvilesov/powerbi-visuals-utils-imargin)
* [DisplayUnitSystem](https://github.com/ignatvilesov/powerbi-visuals-utils-displayunitsystem)
* [DisplayunitSystemType](https://github.com/ignatvilesov/powerbi-visuals-utils-displayunitsystemtype)
* [Double](https://github.com/ignatvilesov/powerbi-visuals-utils-double)
* [EnumExtensions](https://github.com/ignatvilesov/powerbi-visuals-utils-enumextensions)
* [FontUtils](https://github.com/vtkalek/powerbi-visuals-utils-fontutils)
* [Formatting](https://github.com/ignatvilesov/powerbi-visuals-utils-formatting)
* [FormattingService](https://github.com/ignatvilesov/powerbi-visuals-utils-formattingservice)
* [Imargin](https://github.com/ignatvilesov/powerbi-visuals-utils-imargin)
* [InteractivityService](https://github.com/vtkalek/powerbi-visuals-utils-interactivityservice)
* [InteractivityUtils](https://github.com/ignatvilesov/powerbi-visuals-utils-interactivityutils)
* [Legend](https://github.com/vtkalek/powerbi-visuals-utils-legend)
* [localStorageService](https://github.com/uve/powerbi-visuals-utils-localstorageservice)
* [NumericSequence ](https://github.com/ignatvilesov/powerbi-visuals-utils-numericsequence)
* [NumericSequenceRange ](https://github.com/ignatvilesov/powerbi-visuals-utils-numericsequencerange)
* [Pixelconverter ](https://github.com/ignatvilesov/powerbi-visuals-utils-pixelconverter)
* [NumericSequence](https://github.com/ignatvilesov/powerbi-visuals-utils-numericsequence)
* [NumericSequenceRange](https://github.com/ignatvilesov/powerbi-visuals-utils-numericsequencerange)
* [Pixelconverter](https://github.com/ignatvilesov/powerbi-visuals-utils-pixelconverter)
* [Point](https://github.com/vtkalek/powerbi-visuals-utils-point)
* [pointerUtils](https://github.com/ignatvilesov/powerbi-visuals-utils-pointerutils)
* [Prototype](https://github.com/uve/powerbi-visuals-utils-prototype)
* [Rect](https://github.com/ignatvilesov/powerbi-visuals-utils-rect)
* [RegexpExtensions ](https://github.com/ignatvilesov/powerbi-visuals-utils-regexpextensions)
* [semanticQuery](https://github.com/vtkalek/powerbi-visuals-utils-semanticquery)
* [Shapes](https://github.com/vtkalek/powerbi-visuals-utils-shapes)
* [StandalonUtility](https://github.com/vtkalek/powerbi-visuals-utils-standaloneutility)
* [StringExtensions ](https://github.com/ignatvilesov/powerbi-visuals-utils-stringextensions)
* [RegexpExtensions](https://github.com/ignatvilesov/powerbi-visuals-utils-regexpextensions)
* [semanticQuery](https://github.com/vtkalek/powerbi-visuals-utils-semanticquery)
* [Shapes](https://github.com/vtkalek/powerbi-visuals-utils-shapes)
* [StandalonUtility](https://github.com/vtkalek/powerbi-visuals-utils-standaloneutility)
* [StringExtensions](https://github.com/ignatvilesov/powerbi-visuals-utils-stringextensions)
* [SVGUtil](https://github.com/vtkalek/powerbi-visuals-utils-svgutil)
* [TextMeasurementService](https://github.com/uve/powerbi-visuals-utils-textmeasurementservice)
* [TextUtil](https://github.com/vtkalek/powerbi-visuals-utils-textutil)
* [TooltipBuilder](https://github.com/ignatvilesov/powerbi-visuals-utils-tooltipbuilder)
* [TooltipManager](https://github.com/ignatvilesov/powerbi-visuals-utils-tooltipmanager)
* [TooltipService](https://github.com/ignatvilesov/powerbi-visuals-utils-tooltipservice)
* [TouchUtils](https://github.com/ignatvilesov/powerbi-visuals-utils-touchutils)
* [valueFormatter ](https://github.com/ignatvilesov/powerbi-visuals-utils-valueformatter)
* [ValueType ](https://github.com/ignatvilesov/powerbi-visuals-utils-valuetype)
* [WordBreaker](https://github.com/uve/powerbi-visuals-utils-wordbreaker)
* [valueFormatter](https://github.com/ignatvilesov/powerbi-visuals-utils-valueformatter)
* [ValueType](https://github.com/ignatvilesov/powerbi-visuals-utils-valuetype)
* [WordBreaker](https://github.com/uve/powerbi-visuals-utils-wordbreaker)

