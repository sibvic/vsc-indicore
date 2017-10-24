# Change log

## 0.10.0

### New in 0.10.0

TODO

## 0.9.0

### New in 0.9.0

* host:execute("deleteFont", ...);
* host:execute("drawLabel", ...)
* host:execute("drawLabel1", ...)
* host:execute("drawLine", ...)
* host:execute("extendHistory", ...)
* host:execute("getAskPrice");
* host:execute("getBidPrice");
* host:execute("getHistory", ...)
* host:execute("getIndicatorOwner", ...)
* host:execute("getProperty", ...)
* host:execute("getSyncHistory", ...)
* host:execute("getTradingDayOffset")
* host:execute("getTradingProperty", ...);
* host:execute("prompt", ...);
* host:execute("removeLabel", ...)
* host:execute("removeLine", ...)
* host:execute("setStatus", ...);
* host:execute("setTimer", ...);
* host:execute("subscribeTradeEvents", ...);
* host:findTable
* host:version
* http_loader.cancel
* http_loader.load
* http_loader.loading
* http_loader.response
* http_loader.successful
* http_lua.createRequest

## 0.8.0

### New in 0.8.0

* core.date
* core.datetime
* core.dateToTable
* core.drawLine
* core.eraseStream
* core.findDate
* core.formatDate
* indicators:create
* indicators:findIndicator
* core.isnontrading
* core.makeHttpLoader
* core.now
* core.parseCsv
* core.range
* core.rangeFrom
* core.rangeTo
* core.requires
* core.rgb
* core.tableToDate
* core.touches
* core.valuemap
* core.version
* core:app_path
* creationStrategy:setMaxClickCount
* creationStrategy:setNeedParamsAfterPattern
* creationStrategy:setPattern
* db:get
* db:put
* core.ILanguageServiceIndicator
* core.ILanguageServiceJs
* core.ILanguageServiceLua
* core.ILanguageServiceNativeWin
* core.ILanguageServiceStrategy
* core.ILanguageServiceUnknownLanguage
* core.ILanguageServiceUnknownType
* Draw(stage, context)
* Update()
* reference_points
* reference_points:removeReferencePoint
* reference_points:setReferencePoint
* resources
* resources:get
* storagedb
* storagedb.get_db
* strategy
* strategy.parameters
* strategy:description
* strategy:name
* strategy:setTag
* strategy:type
* valuemap
* valuemap:append
* window
* window.CurrentPane
* expat_lua
* expat_lua.ATTRIBUTE
* expat_lua.COMMENT
* expat_lua.ELEMENT
* expat_lua.TEXT
* expat_lua.parseDOM
* expat_lua.parseSAX
* expat_lua.utf8_to_ansi
* ExtAsyncOperationFinished function
* ExtSubscribe function of helper.lua
* ExtSubscribe1 function of helper.lua
* ExtUpdate function
* host:execute("calculatePositionOfDate", ...)
* host:execute("convertTime", ...);
* host:execute("createFont", ...);

## 0.7.0

### New in 0.7.0

* context.DASH
* tick_stream:pipSize
* mathex.max
* mathex.min
* AsyncOperationFinished
* bar_stream.close
* bar_stream.high
* bar_stream.low
* bar_stream.median
* bar_stream.open
* bar_stream.typical
* bar_stream.volume
* bar_stream.weighted
* bar_stream:getAll
* bar_stream:supportsVolume
* ChangeParameters()
* CheckParameters(parameters)
* Click(x, y, price, date)
* CreationStarted()
* CreationFinished()
* Drag(x, y, price, date)
* DoubleClick(x, y, price, date)
* DragEnd(x, y, price, date)
* MoveStart()
* Move(x, y, price, date)
* MoveFinished()
* MoveReferencePointStart(pointID)
* MoveReferencePoint(x, y, price, date)
* MoveReferencePointFinished()
* Prepare(nameOnly)
* ReleaseInstance()
* context.DASHDOT
* context.DOT
* context.SOLID
* context:bottom
* context:convertPenStyle
* context:convertTransparency
* context:createFont
* context:createHatchBrush
* context:createPen
* context:createPoints
* context:deleteObject
* context:drawArc
* context:drawBezierLine
* context:drawBezierShape
* context:drawEllipse
* context:drawGradientRectangle
* context:drawGradientTriangle
* context:drawIcon
* context:drawLine
* context:drawPicture
* context:drawPictureTransparentBackground
* context:drawPolygon
* context:drawPolyline
* context:drawText
* context:firstBar
* context:indexOfBar
* context:lastBar
* context:left
* context:loadIcon
* context:loadPicture
* context:maxPrice
* context:measureText
* context:minPrice
* context:nextBar
* context:pixelsToPoints
* context:pointOfPrice
* context:pointsToPixels
* context:positionOfBar
* context:positionOfDate
* context:priceOfPoint
* context:priceWidth
* context:resetClipRectangle
* context:right
* context:setClipRectangle
* context:setPixel
* context:startEnumeration
* context:top
* core
* core.ASYNC_REDRAW
* core.Bar
* core.Both
* core.COLOR_BACKGROUND
* core.COLOR_CUSTOMLEVEL
* core.COLOR_DOWNCANDLE
* core.COLOR_LABEL
* core.COLOR_LINE
* core.COLOR_UPCANDLE
* core.colors
* core.CR_BOTTOM
* core.CR_CENTER
* core.CR_CHART
* core.CR_LEFT
* core.CR_RIGHT
* core.CR_TOP
* core.Dot
* core.FLAG_ACCOUNT
* core.FLAG_ALLOW_TRADE
* core.FLAG_BARPERIODS
* core.FLAG_BARPERIODS_EDIT
* core.FLAG_BIDASK
* core.FLAG_DATE
* core.FLAG_DATE_OR_NULL
* core.FLAG_DATETIME
* core.FLAG_DATETIME_OR_NULL
* core.FLAG_EMAIL
* core.FLAG_INDICATOR
* core.FLAG_INSTRUMENTS
* core.FLAG_LEVEL_STYLE
* core.FLAG_LINE_STYLE
* core.FLAG_ONLYINDICATORS
* core.FLAG_ONLYOSCILLATORS
* core.FLAG_ORDER
* core.FLAG_PERIODS
* core.FLAG_PERIODS_EDIT
* core.FLAG_PRICE
* core.FLAG_SOUND
* core.FLAG_STRATEGY
* core.FLAG_TRADE
* core.H_Center
* core.H_Left
* core.H_Right
* core.host
* core.Indicator
* core.indicators
* core.Line
* core.LINE_DASH
* core.LINE_DASHDOT
* core.LINE_DOT
* core.LINE_NONE
* core.LINE_SOLID
* core.Oscillator
* core.OWNER_ADDITIONAL_AREA
* core.OWNER_INTERNAL
* core.OWNER_MAIN_AREA
* core.OWNER_UNKNOWN
* core.Signal
* core.Strategy
* core.Tick
* core.TZ_EST
* core.TZ_FINANCIAL
* core.TZ_GMT
* core.TZ_LOCAL
* core.TZ_SERVER
* core.TZ_TS
* core.UpdateAll
* core.UpdateLast
* core.UpdateNew
* core.V_Bottom
* core.V_Center
* core.V_Top
* core.View
* creationStrategy
* db
* core.DragClick
* core.DoubleClick
* host.ReferencePoints
* host.Window
* http_loader
* http_lua
* http_request
* indicator
* indicator.parameters
* indicore3_ffi
* instance
* instance.ask
* instance.bid
* instance

## 0.5.0

### New in this version

* host:execute("attachOutputToChart", ...);
* host:execute("attachTextToChart", ...);
* host:execute("calculateDate", ...)
* context:drawRectangle (pen, brush, x1, y1, x2, y2, transparency?)
* context:createSolidBrush(objid, color)

## 0.4.0

* core.host:trace
* host:execute("getTradingWeekOffset")
* host:execute("stop")
* host:execute("isTableFilled", ...)
* host:execute("killTimer", ...)
* host:execute("getServerTime")
* host:execute("removeAll")
* host:execute("addCommand", ...);