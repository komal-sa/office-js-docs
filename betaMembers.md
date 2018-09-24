# Excel JavaScript API Beta Members

The following is an exahustive list of APIs in Beta. Make sure to be on the latest insiders fast and to use the BETA CDN from https://appsforoffice.microsoft.com/lib/beta/hosted/office.js

## New Members


|Object| What is new| Description|Feedback|
|:----|:----|:----|:----|
|[application](/javascript/api/excel/excel.application)|_Property_ > calculationEngineVersion|Returns a number about the version of Excel Calculation Engine that the workbook was last fully recalculated by. Read-only.|beta|
|[application](/javascript/api/excel/excel.application)|_Relationship_ > calculationState|Returns a CalculationState that indicates the calculation state of the application. Read-only.|beta|
|[application](/javascript/api/excel/excel.application)|_Relationship_ > iterativeCalculation|Returns the Iterative Calculation settings. Read-only.|beta|
|[application](/javascript/api/excel/excel.application)|_Method_ > [suspendScreenUpdatingUntilNextSync()](/javascript/api/excel/excel.application)" is called.|beta|
|[autoFilter](/javascript/api/excel/excel.autofilter)|_Property_ > enabled|Indicates if the AutoFilter is enabled or not. Read-Only. Read-only.|beta|
|[autoFilter](/javascript/api/excel/excel.autofilter)|_Property_ > isDataFiltered|Indicates if the AutoFilter has filter criteria. Read-Only. Read-only.|beta|
|[autoFilter](/javascript/api/excel/excel.autofilter)|_Relationship_ > criteria|Array that holds all filter criterias in an autofiltered range. Read-Only. Read-only.|beta|
|[autoFilter](/javascript/api/excel/excel.autofilter)|_Method_ > [apply(range: Range or string, columnIndex: number, criteria: FilterCriteria)](/javascript/api/excel/excel.autofilter)|Applies AutoFilter on a range and filters the column if column index and filter criteria are specified.|beta|
|[autoFilter](/javascript/api/excel/excel.autofilter)|_Method_ > [clearCriteria()](/javascript/api/excel/excel.autofilter)|Clears the criteria if AutoFilter has filters|beta|
|[autoFilter](/javascript/api/excel/excel.autofilter)|_Method_ > [getRange()](/javascript/api/excel/excel.autofilter)|Returns the Range object that represents the range to which the AutoFilter applies.|beta|
|[autoFilter](/javascript/api/excel/excel.autofilter)|_Method_ > [getRangeOrNullObject()](/javascript/api/excel/excel.autofilter)|If there is Range object associated with the AutoFilter, this method returns it.|beta|
|[autoFilter](/javascript/api/excel/excel.autofilter)|_Method_ > [reapply()](/javascript/api/excel/excel.autofilter)|Applies the specified Autofilter object currently on the range.|beta|
|[autoFilter](/javascript/api/excel/excel.autofilter)|_Method_ > [remove()](/javascript/api/excel/excel.autofilter)|Removes the AutoFilter for the range.|beta|
|[chart](/javascript/api/excel/excel.chart)|_Relationship_ > pivotOptions|Encapsulates the options for the pivot chart. Read-only.|beta|
|[chart](/javascript/api/excel/excel.chart)|_Method_ > [activate()](/javascript/api/excel/excel.chart)|Activate the chart in the Excel UI.|beta|
|[chartAreaFormat](/javascript/api/excel/excel.chartareaformat)|_Property_ > roundedCorners|TrueΓö¼├íif the chart area of the chart has rounded corners. ReadWrite.|beta|
|[chartAreaFormat](/javascript/api/excel/excel.chartareaformat)|_Relationship_ > colorScheme|Returns or sets anΓö¼├íintegerΓö¼├íthat represents the color scheme for the chart. ReadWrite.|beta|
|[chartAxis](/javascript/api/excel/excel.chartaxis)|_Property_ > linkNumberFormat|Represents whether the number format is linked to the cells (so that the number format changes in the labels when it changes in the cells).|beta|
|[chartBinOptions](/javascript/api/excel/excel.chartbinoptions)|_Property_ > allowOverflow|Returns or sets if bin overflow enabled in a histogram chart or pareto chart. ReadWrite.|beta|
|[chartBinOptions](/javascript/api/excel/excel.chartbinoptions)|_Property_ > allowUnderflow|Returns or sets if bin underflow enabled in a histogram chart or pareto chart. ReadWrite.|beta|
|[chartBinOptions](/javascript/api/excel/excel.chartbinoptions)|_Property_ > count|Returns or sets count of bin of a histogram chart or pareto chart. ReadWrite.|beta|
|[chartBinOptions](/javascript/api/excel/excel.chartbinoptions)|_Property_ > overflowValue|Returns or sets bin overflow value of a histogram chart or pareto chart. ReadWrite.|beta|
|[chartBinOptions](/javascript/api/excel/excel.chartbinoptions)|_Property_ > underflowValue|Returns or sets bin underflow value of a histogram chart or pareto chart. ReadWrite.|beta|
|[chartBinOptions](/javascript/api/excel/excel.chartbinoptions)|_Property_ > width|Returns or sets bin width value of a histogram chart or pareto chart. ReadWrite.|beta|
|[chartBinOptions](/javascript/api/excel/excel.chartbinoptions)|_Relationship_ > type|Returns or sets bin type of a histogram chart or pareto chart. ReadWrite.|beta|
|[chartBoxwhiskerOptions](/javascript/api/excel/excel.chartboxwhiskeroptions)|_Property_ > showInnerPoints|Returns or sets if inner points showed in a Box &amp; whisker chart. ReadWrite.|beta|
|[chartBoxwhiskerOptions](/javascript/api/excel/excel.chartboxwhiskeroptions)|_Property_ > showMeanLine|Returns or sets if mean line showed in a Box &amp; whisker chart. ReadWrite.|beta|
|[chartBoxwhiskerOptions](/javascript/api/excel/excel.chartboxwhiskeroptions)|_Property_ > showMeanMarker|Returns or sets if mean marker showed in a Box &amp; whisker chart. ReadWrite.|beta|
|[chartBoxwhiskerOptions](/javascript/api/excel/excel.chartboxwhiskeroptions)|_Property_ > showOutlierPoints|Returns or sets if outlier points showed in a Box &amp; whisker chart. ReadWrite.|beta|
|[chartBoxwhiskerOptions](/javascript/api/excel/excel.chartboxwhiskeroptions)|_Relationship_ > quartileCalculation|Returns or sets quartile calculation type of a Box &amp; whisker chart. ReadWrite.|beta|
|[chartDataLabel](/javascript/api/excel/excel.chartdatalabel)|_Property_ > linkNumberFormat|Boolean value representing if the number format is linked to the cells (so that the number format changes in the labels when it changes in the cells).|beta|
|[chartDataLabels](/javascript/api/excel/excel.chartdatalabels)|_Property_ > linkNumberFormat|Represents whether the number format is linked to the cells (so that the number format changes in the labels when it changes in the cells).|beta|
|[chartErrorBars](/javascript/api/excel/excel.charterrorbars)|_Property_ > endStyleCap|Represents whether have the end style cap for the error bars.|beta|
|[chartErrorBars](/javascript/api/excel/excel.charterrorbars)|_Property_ > visible|Represents whether shown error bars.|beta|
|[chartErrorBars](/javascript/api/excel/excel.charterrorbars)|_Relationship_ > format|Represents the formatting of chart ErrorBars. Read-only.|beta|
|[chartErrorBars](/javascript/api/excel/excel.charterrorbars)|_Relationship_ > include|Represents which error-bar parts to include.|beta|
|[chartErrorBars](/javascript/api/excel/excel.charterrorbars)|_Relationship_ > type|Represents the range marked by error bars.|beta|
|[chartErrorBarsFormat](/javascript/api/excel/excel.charterrorbarsformat)|_Relationship_ > line|Represents chart line formatting. Read-only.|beta|
|[chartMapOptions](/javascript/api/excel/excel.chartmapoptions)|_Relationship_ > labelStrategy|Returns or sets series map labels strategy of a region map chart. ReadWrite.|beta|
|[chartMapOptions](/javascript/api/excel/excel.chartmapoptions)|_Relationship_ > level|Returns or sets series map area of a region map chart. ReadWrite.|beta|
|[chartMapOptions](/javascript/api/excel/excel.chartmapoptions)|_Relationship_ > projectionType|Returns or sets series projection type of a region map chart. ReadWrite.|beta|
|[chartPivotOptions](/javascript/api/excel/excel.chartpivotoptions)|_Property_ > showAxisFieldButtons|Represents whether to display axis field buttons on a PivotChart.|beta|
|[chartPivotOptions](/javascript/api/excel/excel.chartpivotoptions)|_Property_ > showLegendFieldButtons|Represents whether to display legend field buttons on a PivotChart.|beta|
|[chartPivotOptions](/javascript/api/excel/excel.chartpivotoptions)|_Property_ > showReportFilterFieldButtons|Represents whether to display report filter field buttons on a PivotChart.|beta|
|[chartPivotOptions](/javascript/api/excel/excel.chartpivotoptions)|_Property_ > showValueFieldButtons|Represents whether to display show value field buttons on a PivotChart.|beta|
|[chartSeries](/javascript/api/excel/excel.chartseries)|_Property_ > bubbleScale|Returns or sets the scale factor for bubbles in the specified chart group. Can be an integer value from 0 (zero) to 300, corresponding to a percentage of the default size. Applies only to bubble charts. ReadWrite.|beta|
|[chartSeries](/javascript/api/excel/excel.chartseries)|_Property_ > gradientMaximumColor|Returns or sets the Color for maximum value of a region map chart series. ReadWrite.|beta|
|[chartSeries](/javascript/api/excel/excel.chartseries)|_Property_ > gradientMaximumValue|Returns or sets the maximum value of a region map chart series. ReadWrite.|beta|
|[chartSeries](/javascript/api/excel/excel.chartseries)|_Property_ > gradientMidpointColor|Returns or sets the Color for midpoint value of a region map chart series. ReadWrite.|beta|
|[chartSeries](/javascript/api/excel/excel.chartseries)|_Property_ > gradientMidpointValue|Returns or sets the midpoint value of a region map chart series. ReadWrite.|beta|
|[chartSeries](/javascript/api/excel/excel.chartseries)|_Property_ > gradientMinimumColor|Returns or sets the Color for minimum value of a region map chart series. ReadWrite.|beta|
|[chartSeries](/javascript/api/excel/excel.chartseries)|_Property_ > gradientMinimumValue|Returns or sets the minimum value of a region map chart series. ReadWrite.|beta|
|[chartSeries](/javascript/api/excel/excel.chartseries)|_Property_ > invertColor|Returns or sets the fill color for negative data points in a series. ReadWrite.|beta|
|[chartSeries](/javascript/api/excel/excel.chartseries)|_Property_ > showConnectorLines|Returns or sets if connector lines show in a waterfall chart. ReadWrite.|beta|
|[chartSeries](/javascript/api/excel/excel.chartseries)|_Property_ > showLeaderLines|True if Microsoft Excel show leaderlines for each datalabel in series. ReadWrite.|beta|
|[chartSeries](/javascript/api/excel/excel.chartseries)|_Property_ > splitValue|Returns or sets the threshold value separating the two sections of either a pie of pie chart or a bar of pie chart. ReadWrite.|beta|
|[chartSeries](/javascript/api/excel/excel.chartseries)|_Relationship_ > binOptions|Encapsulates the bin options only for histogram chart and pareto chart. Read-only.|beta|
|[chartSeries](/javascript/api/excel/excel.chartseries)|_Relationship_ > boxwhiskerOptions|Encapsulates the options for the Box &amp; Whisker chart. Read-only.|beta|
|[chartSeries](/javascript/api/excel/excel.chartseries)|_Relationship_ > gradientMaximumType|Returns or sets the type for maximum value of a region map chart series. ReadWrite.|beta|
|[chartSeries](/javascript/api/excel/excel.chartseries)|_Relationship_ > gradientMidpointType|Returns or sets the type for midpoint value of a region map chart series. ReadWrite.|beta|
|[chartSeries](/javascript/api/excel/excel.chartseries)|_Relationship_ > gradientMinimumType|Returns or sets the type for minimum value of a region map chart series. ReadWrite.|beta|
|[chartSeries](/javascript/api/excel/excel.chartseries)|_Relationship_ > gradientStyle|Returns or sets series gradient style of a region map chart. ReadWrite.|beta|
|[chartSeries](/javascript/api/excel/excel.chartseries)|_Relationship_ > mapOptions|Encapsulates the options for the Map chart. Read-only.|beta|
|[chartSeries](/javascript/api/excel/excel.chartseries)|_Relationship_ > parentLabelStrategy|Returns or sets series parent label strategy area of a treemap chart. ReadWrite.|beta|
|[chartSeries](/javascript/api/excel/excel.chartseries)|_Relationship_ > xErrorBars|Represents the error bar object for a chart series. Read-only.|beta|
|[chartSeries](/javascript/api/excel/excel.chartseries)|_Relationship_ > yErrorBars|Represents the error bar object for a chart series. Read-only.|beta|
|[chartTrendlineLabel](/javascript/api/excel/excel.charttrendlinelabel)|_Property_ > linkNumberFormat|Boolean value representing if the number format is linked to the cells (so that the number format changes in the labels when it changes in the cells).|beta|
|[closeWorkbookPostProcessAction](/javascript/api/excel/excel.closeworkbookpostprocessaction)|_Relationship_ > actionType|Transmits additional data to client side, e.g., worksheetId for TableSelectionChangedEvent.|beta|
|[conditionalFormat](/javascript/api/excel/excel.conditionalformat)|_Method_ > [getRanges()](/javascript/api/excel/excel.conditionalformat)|Returns the RangeAreas, comprising one or more rectangular ranges, the conditonal format is applied to. Read-only.|beta|
|[dataValidation](/javascript/api/excel/excel.datavalidation)|_Method_ > [getInvalidCells()](/javascript/api/excel/excel.datavalidation)|Returns a RangeAreas, comprising one or more rectangular ranges, with invalid cell values. If all cell values are valid, this function will throw an ItemNotFound error.|beta|
|[dataValidation](/javascript/api/excel/excel.datavalidation)|_Method_ > [getInvalidCellsOrNullObject()](/javascript/api/excel/excel.datavalidation)|Returns a RangeAreas, comprising one or more rectangular ranges, with invalid cell values. If all cell values are valid, this function will return null.|beta|
|[filterCriteria](/javascript/api/excel/excel.filtercriteria)|_Property_ > subField|The property used by the filter to do rich filter on richvalues.|beta|
|[geometricShape](/javascript/api/excel/excel.geometricshape)|_Property_ > id|Represents the shape identifier. Read-only.|beta|
|[geometricShape](/javascript/api/excel/excel.geometricshape)|_Relationship_ > shape|Returns the shape object for the geometric shape. Read-only.|beta|
|[headerFooter](/javascript/api/excel/excel.headerfooter)|_Property_ > centerFooter|Gets or sets the center footer of the worksheet.|beta|
|[headerFooter](/javascript/api/excel/excel.headerfooter)|_Property_ > centerHeader|Gets or sets the center header of the worksheet.|beta|
|[headerFooter](/javascript/api/excel/excel.headerfooter)|_Property_ > leftFooter|Gets or sets the left footer of the worksheet.|beta|
|[headerFooter](/javascript/api/excel/excel.headerfooter)|_Property_ > leftHeader|Gets or sets the left header of the worksheet.|beta|
|[headerFooter](/javascript/api/excel/excel.headerfooter)|_Property_ > rightFooter|Gets or sets the right footer of the worksheet.|beta|
|[headerFooter](/javascript/api/excel/excel.headerfooter)|_Property_ > rightHeader|Gets or sets the right header of the worksheet.|beta|
|[headerFooterGroup](/javascript/api/excel/excel.headerfootergroup)|_Property_ > useSheetMargins|Gets or sets a flag indicating if headersfooters are aligned with the page margins set in the page layout options for the worksheet.|beta|
|[headerFooterGroup](/javascript/api/excel/excel.headerfootergroup)|_Property_ > useSheetScale|Gets or sets a flag indicating if headersfooters should be scaled by the page percentage scale set in the page layout options for the worksheet.|beta|
|[headerFooterGroup](/javascript/api/excel/excel.headerfootergroup)|_Relationship_ > defaultForAllPages|The general headerfooter, used for all pages unless evenodd or first page is specified. Read-only.|beta|
|[headerFooterGroup](/javascript/api/excel/excel.headerfootergroup)|_Relationship_ > evenPages|The headerfooter to use for even pages, odd headerfooter needs to be specified for odd pages. Read-only.|beta|
|[headerFooterGroup](/javascript/api/excel/excel.headerfootergroup)|_Relationship_ > firstPage|The first page headerfooter, for all other pages general or evenodd is used. Read-only.|beta|
|[headerFooterGroup](/javascript/api/excel/excel.headerfootergroup)|_Relationship_ > oddPages|The headerfooter to use for odd pages, even headerfooter needs to be specified for even pages. Read-only.|beta|
|[headerFooterGroup](/javascript/api/excel/excel.headerfootergroup)|_Relationship_ > state|Gets or sets the state of which headersfooters are set.|beta|
|[image](/javascript/api/excel/excel.image)|_Property_ > id|Represents the shape identifier for the image object. Read-only.|beta|
|[image](/javascript/api/excel/excel.image)|_Relationship_ > shape|Returns the shape object for the image. Read-only.|beta|
|[iterativeCalculation](/javascript/api/excel/excel.iterativecalculation)|_Property_ > enabled|True if Excel will use iteration to resolve circular references.|beta|
|[iterativeCalculation](/javascript/api/excel/excel.iterativecalculation)|_Property_ > maxChange|Returns or sets the maximum amount of change between each iteration as Excel resolves circular references.|beta|
|[iterativeCalculation](/javascript/api/excel/excel.iterativecalculation)|_Property_ > maxIteration|Returns or sets the maximum number of iterations that Excel can use to resolve a circular reference.|beta|
|[pageBreak](/javascript/api/excel/excel.pagebreak)|_Property_ > columnIndex|Represents the column index for the page break Read-only.|beta|
|[pageBreak](/javascript/api/excel/excel.pagebreak)|_Property_ > rowIndex|Represents the row index for the page break Read-only.|beta|
|[pageBreak](/javascript/api/excel/excel.pagebreak)|_Method_ > [delete()](/javascript/api/excel/excel.pagebreak)|Deletes a page break object.|beta|
|[pageBreak](/javascript/api/excel/excel.pagebreak)|_Method_ > [getStartCell()](/javascript/api/excel/excel.pagebreak)|Gets the first cell after the page break.|beta|
|[pageBreakCollection](/javascript/api/excel/excel.pagebreakcollection)|_Property_ > items|A collection of pageBreak objects. Read-only.|beta|
|[pageBreakCollection](/javascript/api/excel/excel.pagebreakcollection)|_Method_ > [add(pageBreakRange: Range or string)](/javascript/api/excel/excel.pagebreakcollection)|Adds a page break before the top-left cell of the range specified.|beta|
|[pageBreakCollection](/javascript/api/excel/excel.pagebreakcollection)|_Method_ > [getCount()](/javascript/api/excel/excel.pagebreakcollection)|Gets the number of page breaks in the collection.|beta|
|[pageBreakCollection](/javascript/api/excel/excel.pagebreakcollection)|_Method_ > [getItem(index: number)](/javascript/api/excel/excel.pagebreakcollection)|Gets a page break object via the index.|beta|
|[pageBreakCollection](/javascript/api/excel/excel.pagebreakcollection)|_Method_ > [removePageBreaks()](/javascript/api/excel/excel.pagebreakcollection)|Resets all manual page breaks in the collection.|beta|
|[pageLayout](/javascript/api/excel/excel.pagelayout)|_Property_ > blackAndWhite|Gets or sets the worksheet's black and white print option.|beta|
|[pageLayout](/javascript/api/excel/excel.pagelayout)|_Property_ > bottomMargin|Gets or sets the worksheet's bottom page margin to use for printing in points.|beta|
|[pageLayout](/javascript/api/excel/excel.pagelayout)|_Property_ > centerHorizontally|Gets or sets the worksheet's center horizontally flag. This flag determines whether the worksheet will be centered horizontally when it's printed.|beta|
|[pageLayout](/javascript/api/excel/excel.pagelayout)|_Property_ > centerVertically|Gets or sets the worksheet's center vertically flag. This flag determines whether the worksheet will be centered vertically when it's printed.|beta|
|[pageLayout](/javascript/api/excel/excel.pagelayout)|_Property_ > draftMode|Gets or sets the worksheet's draft mode option. If true the sheet will be printed without graphics.|beta|
|[pageLayout](/javascript/api/excel/excel.pagelayout)|_Property_ > firstPageNumber|Gets or sets the worksheet's first page number to print. Null value represents "auto" page numbering.|beta|
|[pageLayout](/javascript/api/excel/excel.pagelayout)|_Property_ > footerMargin|Gets or sets the worksheet's footer margin, in points, for use when printing.|beta|
|[pageLayout](/javascript/api/excel/excel.pagelayout)|_Property_ > headerMargin|Gets or sets the worksheet's header margin, in points, for use when printing.|beta|
|[pageLayout](/javascript/api/excel/excel.pagelayout)|_Property_ > leftMargin|Gets or sets the worksheet's left margin, in points, for use when printing.|beta|
|[pageLayout](/javascript/api/excel/excel.pagelayout)|_Property_ > orientation|Gets or sets the worksheet's orientation of the page. Possible values are: Portrait, Landscape.|beta|
|[pageLayout](/javascript/api/excel/excel.pagelayout)|_Property_ > paperSize|Gets or sets the worksheet's paper size of the page. Possible values are: Letter, LetterSmall, Tabloid, Ledger, Legal, Statement, Executive, A3, A4, A4Small, A5, B4, B5, Folio, Quatro, Paper10x14, Paper11x17, Note, Envelope9, Envelope10, Envelope11, Envelope12, Envelope14, Csheet, Dsheet, Esheet, EnvelopeDL, EnvelopeC5, EnvelopeC3, EnvelopeC4, EnvelopeC6, EnvelopeC65, EnvelopeB4, EnvelopeB5, EnvelopeB6, EnvelopeItaly, EnvelopeMonarch, EnvelopePersonal, FanfoldUS, FanfoldStdGerman, FanfoldLegalGerman.|beta|
|[pageLayout](/javascript/api/excel/excel.pagelayout)|_Property_ > printGridlines|Gets or sets the worksheet's print gridlines flag. This flag determines whether gridlines will be printed or not.|beta|
|[pageLayout](/javascript/api/excel/excel.pagelayout)|_Property_ > printHeadings|Gets or sets the worksheet's print headings flag. This flag determines whether headings will be printed or not.|beta|
|[pageLayout](/javascript/api/excel/excel.pagelayout)|_Property_ > rightMargin|Gets or sets the worksheet's right margin, in points, for use when printing.|beta|
|[pageLayout](/javascript/api/excel/excel.pagelayout)|_Property_ > topMargin|Gets or sets the worksheet's top margin, in points, for use when printing.|beta|
|[pageLayout](/javascript/api/excel/excel.pagelayout)|_Relationship_ > headersFooters|Header and footer configuration for the worksheet. Read-only.|beta|
|[pageLayout](/javascript/api/excel/excel.pagelayout)|_Relationship_ > printComments|Gets or sets whether the worksheet's comments should be displayed when printing.|beta|
|[pageLayout](/javascript/api/excel/excel.pagelayout)|_Relationship_ > printErrors|Gets or sets the worksheet's print errors option.|beta|
|[pageLayout](/javascript/api/excel/excel.pagelayout)|_Relationship_ > printOrder|Gets or sets the worksheet's page print order option. This specifies the order to use for processing the page number printed.|beta|
|[pageLayout](/javascript/api/excel/excel.pagelayout)|_Relationship_ > zoom|Gets or sets the worksheet's print zoom options.|beta|
|[pageLayout](/javascript/api/excel/excel.pagelayout)|_Method_ > [getPrintArea()](/javascript/api/excel/excel.pagelayout)|Gets the RangeAreas object, comprising one or more rectangular ranges, that represents the print area for the worksheet. If there is no print area, an ItemNotFound error will be thrown.|beta|
|[pageLayout](/javascript/api/excel/excel.pagelayout)|_Method_ > [getPrintAreaOrNullObject()](/javascript/api/excel/excel.pagelayout)|Gets the RangeAreas object, comprising one or more rectangular ranges, that represents the print area for the worksheet. If there is no print area, a null object will be returned.|beta|
|[pageLayout](/javascript/api/excel/excel.pagelayout)|_Method_ > [getPrintTitleColumns()](/javascript/api/excel/excel.pagelayout)|Gets the range object representing the title columns.|beta|
|[pageLayout](/javascript/api/excel/excel.pagelayout)|_Method_ > [getPrintTitleColumnsOrNullObject()](/javascript/api/excel/excel.pagelayout)|Gets the range object representing the title columns. If not set, this will return a null object.|beta|
|[pageLayout](/javascript/api/excel/excel.pagelayout)|_Method_ > [getPrintTitleRows()](/javascript/api/excel/excel.pagelayout)|Gets the range object representing the title rows.|beta|
|[pageLayout](/javascript/api/excel/excel.pagelayout)|_Method_ > [getPrintTitleRowsOrNullObject()](/javascript/api/excel/excel.pagelayout)|Gets the range object representing the title rows. If not set, this will return a null object.|beta|
|[pageLayout](/javascript/api/excel/excel.pagelayout)|_Method_ > [setPrintArea(printArea: Range or RangeAreas or string)](/javascript/api/excel/excel.pagelayout)|Sets the worksheet's print area.|beta|
|[pageLayout](/javascript/api/excel/excel.pagelayout)|_Method_ > [setPrintMargins(unit: PrintMarginUnit, marginOptions: PageLayoutMarginOptions)](/javascript/api/excel/excel.pagelayout)|Sets the worksheet's page margins with units.|beta|
|[pageLayout](/javascript/api/excel/excel.pagelayout)|_Method_ > [setPrintTitleColumns(printTitleColumns: Range or string)](/javascript/api/excel/excel.pagelayout)|Sets the columns that contain the cells to be repeated at the left of each page of the worksheet for printing.|beta|
|[pageLayout](/javascript/api/excel/excel.pagelayout)|_Method_ > [setPrintTitleRows(printTitleRows: Range or string)](/javascript/api/excel/excel.pagelayout)|Sets the rows that contain the cells to be repeated at the top of each page of the worksheet for printing.|beta|
|[pageLayoutMarginOptions](/javascript/api/excel/excel.pagelayoutmarginoptions)|_Property_ > bottom|Represents the page layout bottom margin in the unit specified to use for printing.|beta|
|[pageLayoutMarginOptions](/javascript/api/excel/excel.pagelayoutmarginoptions)|_Property_ > footer|Represents the page layout footer margin in the unit specified to use for printing.|beta|
|[pageLayoutMarginOptions](/javascript/api/excel/excel.pagelayoutmarginoptions)|_Property_ > header|Represents the page layout header margin in the unit specified to use for printing.|beta|
|[pageLayoutMarginOptions](/javascript/api/excel/excel.pagelayoutmarginoptions)|_Property_ > left|Represents the page layout left margin in the unit specified to use for printing.|beta|
|[pageLayoutMarginOptions](/javascript/api/excel/excel.pagelayoutmarginoptions)|_Property_ > right|Represents the page layout right margin in the unit specified to use for printing.|beta|
|[pageLayoutMarginOptions](/javascript/api/excel/excel.pagelayoutmarginoptions)|_Property_ > top|Represents the page layout top margin in the unit specified to use for printing.|beta|
|[pageLayoutZoomOptions](/javascript/api/excel/excel.pagelayoutzoomoptions)|_Property_ > horizontalFitToPages|Number of pages to fit horizontally. This value can be null if percentage scale is used.|beta|
|[pageLayoutZoomOptions](/javascript/api/excel/excel.pagelayoutzoomoptions)|_Property_ > scale|Print page scale value can be between 10 and 400. This value can be null if fit to page tall or wide is specified.|beta|
|[pageLayoutZoomOptions](/javascript/api/excel/excel.pagelayoutzoomoptions)|_Property_ > verticalFitToPages|Number of pages to fit vertically. This value can be null if percentage scale is used.|beta|
|[pivotField](/javascript/api/excel/excel.pivotfield)|_Method_ > [sortByValues(sortby: SortBy, valuesHierarchy: DataPivotHierarchy, pivotItemScope: ()[])](/javascript/api/excel/excel.pivotfield)|Sorts the PivotField by specified values in a given scope. The scope defines which specific values will be used to sort when|beta|
|[pivotLayout](/javascript/api/excel/excel.pivotlayout)|_Property_ > enableFieldList|True if the field list should be shown or hidden from the UI.|beta|
|[pivotTable](/javascript/api/excel/excel.pivottable)|_Property_ > useCustomSortLists|True if the PivotTable should use custom lists when sorting.|beta|
|[range](/javascript/api/excel/excel.range)|_Relationship_ > linkedDataTypeState|Represents the data type state of each cell. Read-only.|beta|
|[range](/javascript/api/excel/excel.range)|_Method_ > [convertDataTypeToText()](/javascript/api/excel/excel.range)|Converts the range cells with datatypes into text.|beta|
|[range](/javascript/api/excel/excel.range)|_Method_ > [convertToLinkedDataType(serviceID: number, languageCulture: string)](/javascript/api/excel/excel.range)|Converts the range cells into linked datatype in the worksheet.|beta|
|[range](/javascript/api/excel/excel.range)|_Method_ > [copyFrom(sourceRange: Range or RangeAreas or string, copyType: RangeCopyType, skipBlanks: bool, transpose: bool)](/javascript/api/excel/excel.range)|Copies cell data or formatting from the source range or RangeAreas to the current range.|beta|
|[range](/javascript/api/excel/excel.range)|_Method_ > [find(text: string, criteria: SearchCriteria)](/javascript/api/excel/excel.range)|Finds the given string based on the criteria specified.|beta|
|[range](/javascript/api/excel/excel.range)|_Method_ > [findOrNullObject(text: string, criteria: SearchCriteria)](/javascript/api/excel/excel.range)|Finds the given string based on the criteria specified.|beta|
|[range](/javascript/api/excel/excel.range)|_Method_ > [getSpecialCells(cellType: SpecialCellType, cellValueType: SpecialCellValueType)](/javascript/api/excel/excel.range)|Gets the RangeAreas object, comprising one or more rectangular ranges, that represents all the cells that match the specified type and value.|beta|
|[range](/javascript/api/excel/excel.range)|_Method_ > [getSpecialCellsOrNullObject(cellType: SpecialCellType, cellValueType: SpecialCellValueType)](/javascript/api/excel/excel.range)|Gets the RangeAreas object, comprising one or more ranges, that represents all the cells that match the specified type and value.|beta|
|[range](/javascript/api/excel/excel.range)|_Method_ > [getTables(fullyContained: bool)](/javascript/api/excel/excel.range)|Gets a scoped collection of tables that overlap with the range.|beta|
|[range](/javascript/api/excel/excel.range)|_Method_ > [removeDuplicates(columns: int[], includesHeader: bool)](/javascript/api/excel/excel.range)|Removes duplicate values from the range specified by the columns.|beta|
|[range](/javascript/api/excel/excel.range)|_Method_ > [replaceAll(text: string, replacement: string, criteria: ReplaceCriteria)](/javascript/api/excel/excel.range)|Finds and replaces the given string based on the criteria specified within the current range.|beta|
|[range](/javascript/api/excel/excel.range)|_Method_ > [setDirty()](/javascript/api/excel/excel.range)|Set a range to be recalculated when the next recalculation occurs.|beta|
|[rangeAreas](/javascript/api/excel/excel.rangeareas)|_Property_ > address|Returns the RageAreas reference in A1-style. Address value will contain the worksheet name for each rectangular block of cells (e.g. "Sheet1!A1:B4, Sheet1!D1:D4"). Read-only.|beta|
|[rangeAreas](/javascript/api/excel/excel.rangeareas)|_Property_ > addressLocal|Returns the RageAreas reference in the user locale. Read-only.|beta|
|[rangeAreas](/javascript/api/excel/excel.rangeareas)|_Property_ > areaCount|Returns the number of rectangular ranges that comprise this RangeAreas object. Read-only.|beta|
|[rangeAreas](/javascript/api/excel/excel.rangeareas)|_Property_ > cellCount|Returns the number of cells in the RangeAreas object, summing up the cell counts of all of the individual rectangular ranges. Returns -1 if the cell count exceeds 2^31-1 (2,147,483,647). Read-only.|beta|
|[rangeAreas](/javascript/api/excel/excel.rangeareas)|_Property_ > isEntireColumn|Indicates whether all the ranges on this RangeAreas object represent entire columns (e.g., "A:C, Q:Z"). Read-only.|beta|
|[rangeAreas](/javascript/api/excel/excel.rangeareas)|_Property_ > isEntireRow|Indicates whether all the ranges on this RangeAreas object represent entire rows (e.g., "1:3, 5:7"). Read-only.|beta|
|[rangeAreas](/javascript/api/excel/excel.rangeareas)|_Property_ > style|Represents the style for all ranges in this RangeAreas object.|beta|
|[rangeAreas](/javascript/api/excel/excel.rangeareas)|_Relationship_ > areas|Returns a collection of rectangular ranges that comprise this RangeAreas object. Read-only.|beta|
|[rangeAreas](/javascript/api/excel/excel.rangeareas)|_Relationship_ > conditionalFormats|Returns a collection of ConditionalFormats that intersect with any cells in this RangeAreas object. Read-only.|beta|
|[rangeAreas](/javascript/api/excel/excel.rangeareas)|_Relationship_ > dataValidation|Returns a dataValidation object for all ranges in the RangeAreas. Read-only.|beta|
|[rangeAreas](/javascript/api/excel/excel.rangeareas)|_Relationship_ > format|Returns a rangeFormat object, encapsulating the the font, fill, borders, alignment, and other properties for all ranges in the RangeAreas object. Read-only.|beta|
|[rangeAreas](/javascript/api/excel/excel.rangeareas)|_Relationship_ > worksheet|Returns the worksheet for the current RangeAreas. Read-only.|beta|
|[rangeAreas](/javascript/api/excel/excel.rangeareas)|_Method_ > [calculate()](/javascript/api/excel/excel.rangeareas)|Calculates all cells in the RangeAreas.|beta|
|[rangeAreas](/javascript/api/excel/excel.rangeareas)|_Method_ > [clear(applyTo: string)](/javascript/api/excel/excel.rangeareas)|Clears values, format, fill, border, etc on each of the areas that comprise this RangeAreas object.|beta|
|[rangeAreas](/javascript/api/excel/excel.rangeareas)|_Method_ > [convertDataTypeToText()](/javascript/api/excel/excel.rangeareas)|Converts all cells in the RangeAreas with datatypes into text.|beta|
|[rangeAreas](/javascript/api/excel/excel.rangeareas)|_Method_ > [convertToLinkedDataType(serviceID: number, languageCulture: string)](/javascript/api/excel/excel.rangeareas)|Converts all cells in the RangeAreas into linked datatype.|beta|
|[rangeAreas](/javascript/api/excel/excel.rangeareas)|_Method_ > [copyFrom(sourceRange: Range or RangeAreas or string, copyType: RangeCopyType, skipBlanks: bool, transpose: bool)](/javascript/api/excel/excel.rangeareas)|Copies cell data or formatting from the source range or RangeAreas to the current RangeAreas.|beta|
|[rangeAreas](/javascript/api/excel/excel.rangeareas)|_Method_ > [getEntireColumn()](/javascript/api/excel/excel.rangeareas).|beta|
|[rangeAreas](/javascript/api/excel/excel.rangeareas)|_Method_ > [getEntireRow()](/javascript/api/excel/excel.rangeareas).|beta|
|[rangeAreas](/javascript/api/excel/excel.rangeareas)|_Method_ > [getIntersection(anotherRange: Range or RangeAreas or string)](/javascript/api/excel/excel.rangeareas)|Returns the RangeAreas object that represents the intersection of the given ranges or RangeAreas. If no intersection is found, an ItemNotFound error will be thrown.|beta|
|[rangeAreas](/javascript/api/excel/excel.rangeareas)|_Method_ > [getIntersectionOrNullObject(anotherRange: Range or RangeAreas or string)](/javascript/api/excel/excel.rangeareas)|Returns the RangeAreas object that represents the intersection of the given ranges or RangeAreas. If no intersection is found, a null object is returned.|beta|
|[rangeAreas](/javascript/api/excel/excel.rangeareas)|_Method_ > [getOffsetRangeAreas(rowOffset: number, columnOffset: number)](/javascript/api/excel/excel.rangeareas)|Returns an RangeAreas object that is shifted by the specific row and column offset. The dimension of the returned RangeAreas will match the original object. If the resulting RangeAreas is forced outside the bounds of the worksheet grid, an error will be thrown.|beta|
|[rangeAreas](/javascript/api/excel/excel.rangeareas)|_Method_ > [getSpecialCells(cellType: SpecialCellType, cellValueType: SpecialCellValueType)](/javascript/api/excel/excel.rangeareas)|Returns a RangeAreas object that represents all the cells that match the specified type and value. Throws an error if no special cells are found that match the criteria.|beta|
|[rangeAreas](/javascript/api/excel/excel.rangeareas)|_Method_ > [getSpecialCellsOrNullObject(cellType: SpecialCellType, cellValueType: SpecialCellValueType)](/javascript/api/excel/excel.rangeareas)|Returns a RangeAreas object that represents all the cells that match the specified type and value. Returns a null object if no special cells are found that match the criteria.|beta|
|[rangeAreas](/javascript/api/excel/excel.rangeareas)|_Method_ > [getTables(fullyContained: bool)](/javascript/api/excel/excel.rangeareas)|Returns a scoped collection of tables that overlap with any range in this RangeAreas object.|beta|
|[rangeAreas](/javascript/api/excel/excel.rangeareas)|_Method_ > [getUsedRangeAreas(valuesOnly: bool)](/javascript/api/excel/excel.rangeareas)|Returns the used RangeAreas that comprises all the used areas of individual rectangular ranges in the RangeAreas object.|beta|
|[rangeAreas](/javascript/api/excel/excel.rangeareas)|_Method_ > [getUsedRangeAreasOrNullObject(valuesOnly: bool)](/javascript/api/excel/excel.rangeareas)|Returns the used RangeAreas that comprises all the used areas of individual rectangular ranges in the RangeAreas object.|beta|
|[rangeAreas](/javascript/api/excel/excel.rangeareas)|_Method_ > [setDirty()](/javascript/api/excel/excel.rangeareas)|Sets the RangeAreas to be recalculated when the next recalculation occurs.|beta|
|[rangeBorder](/javascript/api/excel/excel.rangeborder)|_Property_ > tintAndShade|Returns or sets a double that lightens or darkens a color for Range Border, the value is between -1 (darkest) and 1 (brightest), with 0 for the original color.|beta|
|[rangeBorderCollection](/javascript/api/excel/excel.rangebordercollection)|_Property_ > tintAndShade|Returns or sets a double that lightens or darkens a color for Range Borders, the value is between -1 (darkest) and 1 (brightest), with 0 for the original color.|beta|
|[rangeCollection](/javascript/api/excel/excel.rangecollection)|_Property_ > items|A collection of range objects. Read-only.|beta|
|[rangeCollection](/javascript/api/excel/excel.rangecollection)|_Method_ > [getCount()](/javascript/api/excel/excel.rangecollection)|Returns the number of ranges in the RangeCollection.|beta|
|[rangeCollection](/javascript/api/excel/excel.rangecollection)|_Method_ > [getItemAt(index: number)](/javascript/api/excel/excel.rangecollection)|Returns the range object based on its position in the RangeCollection.|beta|
|[rangeFill](/javascript/api/excel/excel.rangefill)|_Property_ > patternColor|Sets HTML color code representing the color of the Range pattern, of the form ).|beta|
|[rangeFill](/javascript/api/excel/excel.rangefill)|_Property_ > patternTintAndShade|Returns or sets a double that lightens or darkens a pattern color for Range Fill, the value is between -1 (darkest) and 1 (brightest), with 0 for the original color.|beta|
|[rangeFill](/javascript/api/excel/excel.rangefill)|_Property_ > tintAndShade|Returns or sets a double that lightens or darkens a color for Range Fill, the value is between -1 (darkest) and 1 (brightest), with 0 for the original color.|beta|
|[rangeFill](/javascript/api/excel/excel.rangefill)|_Relationship_ > pattern|Gets or sets the pattern of a Range.|beta|
|[rangeFont](/javascript/api/excel/excel.rangefont)|_Property_ > strikethrough|Represents the strikethrough status of font. A null value indicates that the entire range doesn't have uniform Strikethrough setting.|beta|
|[rangeFont](/javascript/api/excel/excel.rangefont)|_Property_ > subscript|Represents the Subscript status of font.|beta|
|[rangeFont](/javascript/api/excel/excel.rangefont)|_Property_ > superscript|Represents the Superscript status of font.|beta|
|[rangeFont](/javascript/api/excel/excel.rangefont)|_Property_ > tintAndShade|Returns or sets a double that lightens or darkens a color for Range Font, the value is between -1 (darkest) and 1 (brightest), with 0 for the original color.|beta|
|[rangeFormat](/javascript/api/excel/excel.rangeformat)|_Property_ > autoIndent|Indicates if text is automatically indented when text alignment is set to equal distribution.|beta|
|[rangeFormat](/javascript/api/excel/excel.rangeformat)|_Property_ > indentLevel|An integer from 0 to 250 that indicates the indent level.|beta|
|[rangeFormat](/javascript/api/excel/excel.rangeformat)|_Property_ > readingOrder|The reading order for the range. Possible values are: Context, LeftToRight, RightToLeft.|beta|
|[rangeFormat](/javascript/api/excel/excel.rangeformat)|_Property_ > shrinkToFit|Indicates if text automatically shrinks to fit in the available column width.|beta|
|[removeDuplicatesResult](/javascript/api/excel/excel.removeduplicatesresult)|_Property_ > removed|Number of duplicated rows removed by the operation. Read-only.|beta|
|[removeDuplicatesResult](/javascript/api/excel/excel.removeduplicatesresult)|_Property_ > uniqueRemaining|Number of remaining unique rows present in the resulting range. Read-only.|beta|
|[replaceCriteria](/javascript/api/excel/excel.replacecriteria)|_Property_ > completeMatch|Specifies whether the match needs to be complete or partial. Default is false (partial).|beta|
|[replaceCriteria](/javascript/api/excel/excel.replacecriteria)|_Property_ > matchCase|Specifies whether the match is case sensitive. Default is false (insensitive).|beta|
|[searchCriteria](/javascript/api/excel/excel.searchcriteria)|_Property_ > completeMatch|Specifies whether the match needs to be complete or partial. Default is false (partial).|beta|
|[searchCriteria](/javascript/api/excel/excel.searchcriteria)|_Property_ > matchCase|Specifies whether the match is case sensitive. Default is false (insensitive).|beta|
|[searchCriteria](/javascript/api/excel/excel.searchcriteria)|_Relationship_ > searchDirection|Specifies the search direction. Default is forward.|beta|
|[shape](/javascript/api/excel/excel.shape)|_Property_ > altTextDescription|Returns or sets the alternative descriptive text string for a Shape object when the object is saved to a Web page.|beta|
|[shape](/javascript/api/excel/excel.shape)|_Property_ > altTextTitle|Returns or sets the alternative title text string for a Shape object when the object is saved to a Web page.|beta|
|[shape](/javascript/api/excel/excel.shape)|_Property_ > height|Represents the height, in points, of the shape.|beta|
|[shape](/javascript/api/excel/excel.shape)|_Property_ > id|Represents the shape identifier. Read-only.|beta|
|[shape](/javascript/api/excel/excel.shape)|_Property_ > left|The distance, in points, from the left side of the shape to the left of the worksheet.|beta|
|[shape](/javascript/api/excel/excel.shape)|_Property_ > lockAspectRatio|Represents if the aspect ratio locked, in boolean, of the shape.|beta|
|[shape](/javascript/api/excel/excel.shape)|_Property_ > name|Represents the name of the shape. Read-only.|beta|
|[shape](/javascript/api/excel/excel.shape)|_Property_ > rotation|Represents the rotation, in degrees, of the shape.|beta|
|[shape](/javascript/api/excel/excel.shape)|_Property_ > top|The distance, in points, from the top edge of the shape to the top of the worksheet.|beta|
|[shape](/javascript/api/excel/excel.shape)|_Property_ > width|Represents the width, in points, of the shape.|beta|
|[shape](/javascript/api/excel/excel.shape)|_Property_ > zOrderPosition|Returns the position of the specified shape in the z-order, the very bottom shape's z-order value is 0. Read-only.|beta|
|[shape](/javascript/api/excel/excel.shape)|_Relationship_ > fill|Returns the fill formatting of the shape object. Read-only.|beta|
|[shape](/javascript/api/excel/excel.shape)|_Relationship_ > geometricShape|Returns the geometric shape for the shape object. Error will be thrown, if the shape object is other shape type (Like, Image, SmartArt, etc.) rather than GeometricShape. Read-only.|beta|
|[shape](/javascript/api/excel/excel.shape)|_Relationship_ > geometricShapeType|Represents the geometric shape type of the specified shape.|beta|
|[shape](/javascript/api/excel/excel.shape)|_Relationship_ > image|Returns the image for the shape object. Error will be thrown, if the shape object is other shape type (Like, GeometricShape, SmartArt, etc.) rather than Image. Read-only.|beta|
|[shape](/javascript/api/excel/excel.shape)|_Relationship_ > placement|Represents the placment, value that represents the way the object is attached to the cells below it.|beta|
|[shape](/javascript/api/excel/excel.shape)|_Relationship_ > textFrame|Returns the textFrame object of a shape. Read only. Read-only.|beta|
|[shape](/javascript/api/excel/excel.shape)|_Relationship_ > type|Returns the type of the specified shape. Read-only.|beta|
|[shape](/javascript/api/excel/excel.shape)|_Method_ > [delete()](/javascript/api/excel/excel.shape)|Deletes the Shape|beta|
|[shape](/javascript/api/excel/excel.shape)|_Method_ > [setZOrder(value: string)](/javascript/api/excel/excel.shape).|beta|
|[shapeActivatedEventArgs](/javascript/api/excel/excel.shapeactivatedeventargs)|_Property_ > shapeId|Gets the id of the shape that is activated.|beta|
|[shapeActivatedEventArgs](/javascript/api/excel/excel.shapeactivatedeventargs)|_Property_ > type|Gets the type of the event.|beta|
|[shapeActivatedEventArgs](/javascript/api/excel/excel.shapeactivatedeventargs)|_Property_ > worksheetId|Gets the id of the worksheet in which the shape is activated.|beta|
|[shapeCollection](/javascript/api/excel/excel.shapecollection)|_Property_ > items|A collection of shape objects. Read-only.|beta|
|[shapeCollection](/javascript/api/excel/excel.shapecollection)|_Method_ > [addGeometricShape(geometricShapeType: string, left: double, top: double, width: double, height: double)](/javascript/api/excel/excel.shapecollection)|Adds a geometric shape to worksheet. Returns a Shape object that represents the new shape.|beta|
|[shapeCollection](/javascript/api/excel/excel.shapecollection)|_Method_ > [addImage(base64ImageString: string)](/javascript/api/excel/excel.shapecollection)|Creates an image from a base64 string and adds it to worksheet. Returns the image object that represents the new Image.|beta|
|[shapeCollection](/javascript/api/excel/excel.shapecollection)|_Method_ > [addTextBox(text: string)](/javascript/api/excel/excel.shapecollection)|Adds a textbox to worksheet by telling it's text content. Returns a Shape object that represents the new text box.|beta|
|[shapeCollection](/javascript/api/excel/excel.shapecollection)|_Method_ > [getCount()](/javascript/api/excel/excel.shapecollection)|Returns the number of shapes in the worksheet. Read-only.|beta|
|[shapeCollection](/javascript/api/excel/excel.shapecollection)|_Method_ > [getItem(shapeId: string)](/javascript/api/excel/excel.shapecollection)|Returns a shape identified by the shape id. Read-only.|beta|
|[shapeDeactivatedEventArgs](/javascript/api/excel/excel.shapedeactivatedeventargs)|_Property_ > shapeId|Gets the id of the shape that is deactivated.|beta|
|[shapeDeactivatedEventArgs](/javascript/api/excel/excel.shapedeactivatedeventargs)|_Property_ > type|Gets the type of the event.|beta|
|[shapeDeactivatedEventArgs](/javascript/api/excel/excel.shapedeactivatedeventargs)|_Property_ > worksheetId|Gets the id of the worksheet in which the shape is deactivated.|beta|
|[shapeFill](/javascript/api/excel/excel.shapefill)|_Property_ > foreColor|Represents the shape fill fore color in HTML color format, of the form )|beta|
|[shapeFill](/javascript/api/excel/excel.shapefill)|_Property_ > transparency|Returns or sets the degree of transparency of the specified fill as a value from 0.0 (opaque) through 1.0 (clear). For API not supported shape types  or special fill type with inconsistent transparencies, return null. For example, gradient fill type could have inconsistent transparencies.|beta|
|[shapeFill](/javascript/api/excel/excel.shapefill)|_Relationship_ > type|Returns the fill type of the shape. Read-only.|beta|
|[shapeFill](/javascript/api/excel/excel.shapefill)|_Method_ > [clear()](/javascript/api/excel/excel.shapefill)|Clears the fill formatting of a shape object.|beta|
|[shapeFill](/javascript/api/excel/excel.shapefill)|_Method_ > [setSolidColor(color: string)](/javascript/api/excel/excel.shapefill)|Sets the fill formatting of a shape object to a uniform color, fill type changeing to Solid Fill.|beta|
|[shapeFont](/javascript/api/excel/excel.shapefont)|_Property_ > bold|Represents the bold status of font. Returns null the TextRange includes both bold and non-bold text fragments.|beta|
|[shapeFont](/javascript/api/excel/excel.shapefont)|_Property_ > color|HTML color code representation of the text color. E.g. #FF0000 represents Red. Returns null if the TextRange includes text fragments with different colors.|beta|
|[shapeFont](/javascript/api/excel/excel.shapefont)|_Property_ > italic|Represents the italic status of font. Return null if the TextRange includes both italic and non-italic text fragments.|beta|
|[shapeFont](/javascript/api/excel/excel.shapefont)|_Property_ > name|Represents font name (e.g. "Calibri"). If the text is Complex Script or East Asian language, represents corresponding font name; otherwise represents Latin font name.|beta|
|[shapeFont](/javascript/api/excel/excel.shapefont)|_Property_ > size|Represents font size in points (e.g. 11). Return null if the TextRange includes text fragments with different font sizes.|beta|
|[shapeFont](/javascript/api/excel/excel.shapefont)|_Relationship_ > underline|Type of underline applied to the font. Return null if the TextRange includes text fragments with different underline styles.|beta|
|[sortField](/javascript/api/excel/excel.sortfield)|_Property_ > subField|Represents the subfield that is the target property name of a rich value to sort on.|beta|
|[table](/javascript/api/excel/excel.table)|_Relationship_ > autoFilter|Represents the AutoFilter object of the table. Read-Only. Read-only.|beta|
|[table](/javascript/api/excel/excel.table)|_Method_ > [clearStyle()](/javascript/api/excel/excel.table)|Changes the table to use the default table style.|beta|
|[tableAddedEventArgs](/javascript/api/excel/excel.tableaddedeventargs)|_Property_ > tableId|Gets the id of the table that is added.|beta|
|[tableAddedEventArgs](/javascript/api/excel/excel.tableaddedeventargs)|_Property_ > type|Gets the type of the event.|beta|
|[tableAddedEventArgs](/javascript/api/excel/excel.tableaddedeventargs)|_Property_ > worksheetId|Gets the id of the worksheet in which the table is added.|beta|
|[tableAddedEventArgs](/javascript/api/excel/excel.tableaddedeventargs)|_Relationship_ > source|Gets the source of the event.|beta|
|[tableDeletedEventArgs](/javascript/api/excel/excel.tabledeletedeventargs)|_Property_ > tableId|Specifies the id of the table that is deleted.|beta|
|[tableDeletedEventArgs](/javascript/api/excel/excel.tabledeletedeventargs)|_Property_ > tableName|Specifies the name of the table that is deleted.|beta|
|[tableDeletedEventArgs](/javascript/api/excel/excel.tabledeletedeventargs)|_Property_ > type|Specifies the type of the event.|beta|
|[tableDeletedEventArgs](/javascript/api/excel/excel.tabledeletedeventargs)|_Property_ > worksheetId|Specifies the id of the worksheet in which the table is deleted.|beta|
|[tableDeletedEventArgs](/javascript/api/excel/excel.tabledeletedeventargs)|_Relationship_ > source|Specifies the source of the event.|beta|
|[tableFilteredEventArgs](/javascript/api/excel/excel.tablefilteredeventargs)|_Property_ > tableId|Represents the id of the table in which the filter is applied..|beta|
|[tableFilteredEventArgs](/javascript/api/excel/excel.tablefilteredeventargs)|_Property_ > type|Represents the type of the event.|beta|
|[tableFilteredEventArgs](/javascript/api/excel/excel.tablefilteredeventargs)|_Property_ > worksheetId|Represents the id of the worksheet which contains the table.|beta|
|[tableScopedCollection](/javascript/api/excel/excel.tablescopedcollection)|_Property_ > items|A collection of tableScoped objects. Read-only.|beta|
|[tableScopedCollection](/javascript/api/excel/excel.tablescopedcollection)|_Method_ > [getCount()](/javascript/api/excel/excel.tablescopedcollection)|Gets the number of tables in the collection.|beta|
|[tableScopedCollection](/javascript/api/excel/excel.tablescopedcollection)|_Method_ > [getFirst()](/javascript/api/excel/excel.tablescopedcollection)|Gets the first table in the collection. The tables in the collection are sorted top to bottom and left to right, such that top left table is the first table in the collection.|beta|
|[tableScopedCollection](/javascript/api/excel/excel.tablescopedcollection)|_Method_ > [getItem(key: string)](/javascript/api/excel/excel.tablescopedcollection)|Gets a table by Name or ID.|beta|
|[textFrame](/javascript/api/excel/excel.textframe)|_Property_ > bottomMargin|Represents the bottom margin, in points, of the text frame.|beta|
|[textFrame](/javascript/api/excel/excel.textframe)|_Property_ > hasText|Specifies whether the TextFrame contains text. Read-only.|beta|
|[textFrame](/javascript/api/excel/excel.textframe)|_Property_ > leftMargin|Represents the left margin, in points, of the text frame.|beta|
|[textFrame](/javascript/api/excel/excel.textframe)|_Property_ > rightMargin|Represents the right margin, in points, of the text frame.|beta|
|[textFrame](/javascript/api/excel/excel.textframe)|_Property_ > topMargin|Represents the top margin, in points, of the text frame.|beta|
|[textFrame](/javascript/api/excel/excel.textframe)|_Relationship_ > autoSize|Gets or sets the auto sizing settings for the text frame. A text frame can be set to auto size the text to fit the text frame, or auto size the text frame to fit the text, or without auto sizing.|beta|
|[textFrame](/javascript/api/excel/excel.textframe)|_Relationship_ > horizontalAlignment|Represents the horizontal alignment of the text frame.|beta|
|[textFrame](/javascript/api/excel/excel.textframe)|_Relationship_ > horizontalOverflow|Represents the horizontal overflow type of the text frame.|beta|
|[textFrame](/javascript/api/excel/excel.textframe)|_Relationship_ > orientation|Represents the text orientation of the text frame.|beta|
|[textFrame](/javascript/api/excel/excel.textframe)|_Relationship_ > readingOrder|Represents the reading order of the text frame, RTL or LTR.|beta|
|[textFrame](/javascript/api/excel/excel.textframe)|_Relationship_ > textRange|Returns or sets the degree of transparency of the specified fill as a value from 0.0 (opaque) through 1.0 (clear). For API not supported shape types  or special fill type with inconsistent transparencies, return null. For example, gradient fill type could have inconsistent transparencies. Read-only.|beta|
|[textFrame](/javascript/api/excel/excel.textframe)|_Relationship_ > verticalAlignment|Represents the vertical alignment of the text frame.|beta|
|[textFrame](/javascript/api/excel/excel.textframe)|_Relationship_ > verticalOverflow|Represents the vertical overflow type of the text frame.|beta|
|[textFrame](/javascript/api/excel/excel.textframe)|_Method_ > [deleteText()](/javascript/api/excel/excel.textframe)|Deletes all the text in the textframe.|beta|
|[textRange](/javascript/api/excel/excel.textrange)|_Property_ > text|Represents the plain text content of the text range.|beta|
|[textRange](/javascript/api/excel/excel.textrange)|_Relationship_ > font|Returns a ShapeFont object that represents the font attributes for the text range. Read-only.|beta|
|[textRange](/javascript/api/excel/excel.textrange)|_Method_ > [getCharacters(start: number, length: number)](/javascript/api/excel/excel.textrange)|Returns a TextRange object for characters in the given range.|beta|
|[workbook](/javascript/api/excel/excel.workbook)|_Property_ > autoSave|True if the workbook is in auto save mode. Read-only.|beta|
|[workbook](/javascript/api/excel/excel.workbook)|_Property_ > calculationEngineVersion|Returns a number about the version of Excel Calculation Engine. Read-Only. Read-only.|beta|
|[workbook](/javascript/api/excel/excel.workbook)|_Property_ > chartDataPointTrack|True if all charts in the workbook are tracking the actual data points to which they are attached.|beta|
|[workbook](/javascript/api/excel/excel.workbook)|_Property_ > isDirty|True if no changes have been made to the specified workbook since it was last saved.|beta|
|[workbook](/javascript/api/excel/excel.workbook)|_Property_ > previouslySaved|True if the workbook has ever been saved locally or online. Read-only.|beta|
|[workbook](/javascript/api/excel/excel.workbook)|_Property_ > use1904DateSystem|True if the workbook uses the 1904 date system.|beta|
|[workbook](/javascript/api/excel/excel.workbook)|_Property_ > usePrecisionAsDisplayed|True if calculations in this workbook will be done using only the precision of the numbers as they're displayed.|beta|
|[workbook](/javascript/api/excel/excel.workbook)|_Method_ > [close(closeBehavior: CloseBehavior)](/javascript/api/excel/excel.workbook)|Close current workbook.|beta|
|[workbook](/javascript/api/excel/excel.workbook)|_Method_ > [getActiveChart()](/javascript/api/excel/excel.workbook)|Gets the currently active chart in the workbook. If there is no active chart, will throw exception when invoke this statement|beta|
|[workbook](/javascript/api/excel/excel.workbook)|_Method_ > [getActiveChartOrNullObject()](/javascript/api/excel/excel.workbook)|Gets the currently active chart in the workbook. If there is no active chart, will return null object|beta|
|[workbook](/javascript/api/excel/excel.workbook)|_Method_ > [getIsActiveCollabSession()](/javascript/api/excel/excel.workbook).|beta|
|[workbook](/javascript/api/excel/excel.workbook)|_Method_ > [getSelectedRanges()](/javascript/api/excel/excel.workbook), this method returns a RangeAreas object that represents all the selected ranges.|beta|
|[worksheet](/javascript/api/excel/excel.worksheet)|_Property_ > enableCalculation|Gets or sets the enableCalculation property of the worksheet.|beta|
|[worksheet](/javascript/api/excel/excel.worksheet)|_Relationship_ > autoFilter|Represents the AutoFilter object of the worksheet. Read-Only. Read-only.|beta|
|[worksheet](/javascript/api/excel/excel.worksheet)|_Relationship_ > horizontalPageBreaks|Gets the horizontal page break collection for the worksheet. This collection only contains manual page breaks. Read-only.|beta|
|[worksheet](/javascript/api/excel/excel.worksheet)|_Relationship_ > pageLayout|Gets the PageLayout object of the worksheet. Read-only.|beta|
|[worksheet](/javascript/api/excel/excel.worksheet)|_Relationship_ > shapes|Returns the collection of all the Shape objects on the worksheet. Read-only.|beta|
|[worksheet](/javascript/api/excel/excel.worksheet)|_Relationship_ > verticalPageBreaks|Gets the vertical page break collection for the worksheet. This collection only contains manual page breaks. Read-only.|beta|
|[worksheet](/javascript/api/excel/excel.worksheet)|_Method_ > [findAll(text: string, criteria: WorksheetSearchCriteria)](/javascript/api/excel/excel.worksheet)|Finds all occurrences of the given string based on the criteria specified and returns them as a RangeAreas object, comprising one or more rectangular ranges.|beta|
|[worksheet](/javascript/api/excel/excel.worksheet)|_Method_ > [findAllOrNullObject(text: string, criteria: WorksheetSearchCriteria)](/javascript/api/excel/excel.worksheet)|Finds all occurrences of the given string based on the criteria specified and returns them as a RangeAreas object, comprising one or more rectangular ranges.|beta|
|[worksheet](/javascript/api/excel/excel.worksheet)|_Method_ > [getRanges(address: string)](/javascript/api/excel/excel.worksheet)|Gets the RangeAreas object, representing one or more blocks of rectangular ranges, specified by the address or name.|beta|
|[worksheet](/javascript/api/excel/excel.worksheet)|_Method_ > [replaceAll(text: string, replacement: string, criteria: ReplaceCriteria)](/javascript/api/excel/excel.worksheet)|Finds and replaces the given string based on the criteria specified within the current worksheet.|beta|
|[worksheetFilteredEventArgs](/javascript/api/excel/excel.worksheetfilteredeventargs)|_Property_ > type|Represents the type of the event.|beta|
|[worksheetFilteredEventArgs](/javascript/api/excel/excel.worksheetfilteredeventargs)|_Property_ > worksheetId|Represents the id of the worksheet in which the filter is applied.|beta|
|[worksheetSearchCriteria](/javascript/api/excel/excel.worksheetsearchcriteria)|_Property_ > completeMatch|Specifies whether the match needs to be complete or partial. Default is false (partial).|beta|
|[worksheetSearchCriteria](/javascript/api/excel/excel.worksheetsearchcriteria)|_Property_ > matchCase|Specifies whether the match is case sensitive. Default is false (insensitive).|beta|