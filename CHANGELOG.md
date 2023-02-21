# Change log

## 1.5

### New in 1.5

* Fixed addStreamOscillator

## 1.4

### New in 1.4

* addTextOutput
* addPriceTypeParam
* ReportURL_TP, canCreateEntry_TP, canCreateMarketOpen_TP, canCreateMarketClose_TP, canCreateStopLimit_TP, canCreateNetStopLimit_TP, canUseDynamicTrailingForEntryLimit_TP, canUseDynamicTrailingForEntryStop_TP, canUseDynamicTrailingForLimit_TP, canUseDynamicTrailingForStop_TP, canUseFluctuateTrailingForEntryLimit_TP, canUseFluctuateTrailingForEntryStop_TP, canUseFluctuateTrailingForLimit_TP, canUseFluctuateTrailingForStop_TP, baseUnitSize_TP, MMR_TP, EMR_TP, LMR_TP, conditionalDistanceEntryLimit_TP, conditionalDistanceEntryStop_TP, conditionalDistanceLimitForEntry_TP, conditionalDistanceStopForEntry_TP, conditionalDistanceLimitForTrade_TP, conditionalDistanceStopForTrade_TP, marketStatus_TP, maxQuantity_TP, minQuantity_TP, UserName_TP, SessionID_TP
* TradeField
* drawLabel1
* textOutput_get

## 1.3

### New in 1.3

* priceParam/priceParamClipboard
* addStringAlternativeParam/addStringAlternativeParamClipboard
* createAverage
* getIndicatorCandle
* enumPanes, enumPaneStreams
* getIndiStreamColor
* macdParameters
* getParam
* drawLineStream
* createStyledPen
* tradeParam
* atrParameters
* enumStreams
* bbParameters
* sarPatameters
* getTextOutput
* getTextOutputCount
* strategyUpdate
* ssdParameters
* addIntegerAlternativeParam

## 1.2.0

### New in 1.2.0

* createChannel
* indicatorColorParam/indicatorColorParamClipboard
* doubleParam/doubleParamClipboard
* stringParam/stringParamClipboard
* timeframeParam
* strategyInit, strategyPrepare, strategyInclude,
* enumVisibleBars
* averageFunctions, averageParams
* toolInit, pointParams, toolCreateFunctions, toolMovePointFunctions
* instrumentParam for instruments parameter

## 1.1.7

### New in 1.1.7

* Bug fixes
* indicatorIntegerParam, indicatorIntegerParamClipboard
* strategyIntegerParam

## 1.1.6

### New in 1.1.6

* Bug fixes
* addLineParamsClipboard and addLineParams for adding color, width and style parameters
* addLineParamsTool, addLineParamsClipboardTool, addLineWidthParamTool, addLineWidthParamClipboardTool, addLineStyleParamTool, addLineStyleParamClipboardTool
* debugTraceClipboard
* indicatorInit for function Init() of the indicator
* indicatorTransparencyParam
* strategyBidAskParam

## 1.1.5

### New in 1.1.5

* bugfixes
* functionDraw snippet

## 1.1.4

### New in 1.1.4

* addLineStyleParam and addLineStyleParamClipboard for indicator's line style parameter
* addStreamClipboard, addStreamOscillator, addStreamOscillatorClipboard
* indicatorPrepare
* strategyTimeframeParam, indicatorTimeframeParam for timeframe parameter
* addLineWidthParamClipboard, addLineWidthParam for indicator's line width parameter
* indicatorAddBooleanParam, strategyAddBooleanParam, indicatorAddBooleanParamClipboard, strategyAddBooleanParamClipboard for a boolean parameter
* tradingOffsets (getTradingWeekOffset + getTradingDayOffset)

## 1.1.3

### New in 1.1.3

* enumTable snippet
* createCustomIndicator snippet
* assignParam will use a clipboard value
* assignParamManual will ask a user to type a parameter name

## 1.1.2

### New in 1.1.2

* Options for addStream
* Use of clipboard value for assignParam

## 1.1.1

### New in 1.1.1

* Fixed typos

## 1.1.0

### New in 1.1.0

* assignParam pattern (param = instance.parameters.param;)
* addStreamStyled (addStream + setWidth + setStyle)

## 1.0.2

### New in 1.0.2

* Fixed function AsyncOperationFinished

## 1.0.1

### New in 1.0.1

* Fixed ExtAsyncOperation

## 1.0.0

### New in 1.0.0

* xmlelement:elementsCount
* xmlelement:findAttribute
* xmlelement:getAttribute
* xmlelement:getElement
* xmlelement:getNode
* xmlelement:nodesCount
* xmlelement:text
* xmlhandler.endCDATA
* xmlhandler.endNamespace
* xmlhandler.processingInstruction
* xmlhandler.startNamespace
* xmlhandler:characters
* xmlhandler:comment
* xmlhandler:endElement
* xmlhandler:startCDATA
* xmlhandler:startElement
* xmlnode.namespaceURI
* xmlnode:fullName
* xmlnode:hasNamespace
* xmlnode:name
* xmlnode:prefix
* xmlnode:value
* xmlnode:type
* context.tooltip

## 0.20.0

### New in 0.20.0

* text_output:halign
* text_output:hasData
* text_output:id
* text_output:label
* text_output:size
* text_output:valign
* text_output_impl:set
* text_output_impl:setNoData
* tick_stream:barSize
* tick_stream:date
* tick_stream:first
* tick_stream:getDisplayPrecision
* tick_stream:getPrecision
* tick_stream:hasData
* tick_stream:instrument
* tick_stream:isAlive
* tick_stream:isBar
* tick_stream:isBid
* tick_stream:name
* tick_stream:serial
* tick_stream:size
* tick_stream:tick
* tool
* tool.creationStrategy
* tool.parameters
* tool:description
* tool:icon
* tool:setTag
* tool:name
* tradingtable:enumerator
* tradingtable:find
* tradingtable:findAll
* tradingtable:version
* tradingtable_enum:next
* tradingtable_enum:reset
* tradingtable_row:cell
* tradingtable_row:refresh
* xmldocument
* xmldocument.root
* xmlelement
* xmlelement:attributesCount

## 0.19.0

### New in 0.19.0

* parameters:addColor
* parameters:addDate
* parameters:addDouble
* parameters:addFile
* parameters:addInteger
* parameters:addString
* parameters:getBoolean
* parameters:addGroup
* parameters:addIntegerAlternative
* parameters:addStringAlternative
* parameters:getColor
* parameters:getCustomParameters
* parameters:getDouble
* parameters:getFile
* parameters:getInteger
* parameters:getString
* parameters:setBoolean
* parameters:setColor
* parameters:setDouble
* parameters:setFlag
* parameters:setInteger
* parameters:setString
* profile
* profile:createInstance
* profile:description
* profile:id
* profile:name
* profile:parameters
* profile:profileLanguage
* profile:profileType
* profile:requiredSource
* profile:type
* terminal
* terminal:alertEmail
* terminal:alertMessage
* terminal:alertSound
* terminal:execute
* text_output:color
* text_output:font
* text_output:get
