> https://qgis.org/pyqgis/3.4/core/QgsSettings.html



```python
>>>print(QSettings().allKeys())
[
	'Cad/Floater',
	'DB_Manager/mainWindow/geometry', 'DB_Manager/mainWindow/windowState',
	'Error/dialog/detail',
	'MSSQL/connections/selected',
	
	'Map/highlight/buffer','Map/highlight/color','Map/highlight/colorAlpha','Map/highlight/minWidth','Map/identifyMode',
	'Map/logCanvasRefreshEvent','Map/scales', 'Map/searchRadiusMM',
	
	'Oracle/connections/selected',
	
	'Plugin-DelimitedText/booleanFalse','Plugin-DelimitedText/booleanTrue','Plugin-DelimitedText/crs','Plugin-DelimitedText/csv/booleanFalse',
	'Plugin-DelimitedText/csv/booleanTrue','Plugin-DelimitedText/csv/crs','Plugin-DelimitedText/csv/decimalPoint',
	'Plugin-DelimitedText/csv/delimiterRegexp','Plugin-DelimitedText/csv/delimiterType','Plugin-DelimitedText/csv/delimiters',
	'Plugin-DelimitedText/csv/detectTypes','Plugin-DelimitedText/csv/encoding','Plugin-DelimitedText/csv/escapeChars',
	'Plugin-DelimitedText/csv/geomColumnType','Plugin-DelimitedText/csv/geometry','Plugin-DelimitedText/csv/quoteChars',
	'Plugin-DelimitedText/csv/skipEmptyFields','Plugin-DelimitedText/csv/spatialIndex','Plugin-DelimitedText/csv/startFrom',
	'Plugin-DelimitedText/csv/subsetIndex','Plugin-DelimitedText/csv/trimFields','Plugin-DelimitedText/csv/useHeader',
	'Plugin-DelimitedText/csv/watchFile','Plugin-DelimitedText/csv/xyDms','Plugin-DelimitedText/decimalPoint',
	'Plugin-DelimitedText/delimiterRegexp','Plugin-DelimitedText/delimiterType','Plugin-DelimitedText/delimiters',
	'Plugin-DelimitedText/detectTypes','Plugin-DelimitedText/encoding','Plugin-DelimitedText/escapeChars',
	'Plugin-DelimitedText/file_filter','Plugin-DelimitedText/geomColumnType','Plugin-DelimitedText/geometry',
	'Plugin-DelimitedText/quoteChars','Plugin-DelimitedText/skipEmptyFields','Plugin-DelimitedText/spatialIndex',
	'Plugin-DelimitedText/startFrom','Plugin-DelimitedText/subsetIndex','Plugin-DelimitedText/text_path',
	'Plugin-DelimitedText/trimFields','Plugin-DelimitedText/useHeader','Plugin-DelimitedText/watchFile',
	'Plugin-DelimitedText/xyDms','PluginReloader/extraCommands','PluginReloader/extraCommandsEnabled',
	'PluginReloader/notify','PluginReloader/plugin',

	'PostgreSQL/connections/selected','PostgreSQL/connections/unifiber_scope_list/allowGeometrylessTables',
	'PostgreSQL/connections/unifiber_scope_list/authcfg','PostgreSQL/connections/unifiber_scope_list/database',
	'PostgreSQL/connections/unifiber_scope_list/dontResolveType','PostgreSQL/connections/unifiber_scope_list/estimatedMetadata',
	'PostgreSQL/connections/unifiber_scope_list/geometryColumnsOnly','PostgreSQL/connections/unifiber_scope_list/host',
	'PostgreSQL/connections/unifiber_scope_list/metadataInDatabase','PostgreSQL/connections/unifiber_scope_list/password',
	'PostgreSQL/connections/unifiber_scope_list/port','PostgreSQL/connections/unifiber_scope_list/projectsInDatabase',
	'PostgreSQL/connections/unifiber_scope_list/publicOnly','PostgreSQL/connections/unifiber_scope_list/savePassword',
	'PostgreSQL/connections/unifiber_scope_list/saveUsername','PostgreSQL/connections/unifiber_scope_list/service',
	'PostgreSQL/connections/unifiber_scope_list/sslmode','PostgreSQL/connections/unifiber_scope_list/username',
	
	'Processing/Configuration/ACTIVATE_GDAL','Processing/Configuration/DefaultOutputRasterLayerExt',
	'Processing/Configuration/DefaultOutputVectorLayerExt','Processing/Configuration/FILTER_INVALID_GEOMETRIES',
	'Processing/Configuration/GRASS7_LOG_COMMANDS','Processing/Configuration/GRASS7_LOG_CONSOLE',
	'Processing/Configuration/GRASS_HELP_PATH','Processing/Configuration/GRASS_USE_REXTERNAL',
	'Processing/Configuration/GRASS_USE_VEXTERNAL','Processing/Configuration/KEEP_DIALOG_OPEN',
	'Processing/Configuration/MAX_THREADS','Processing/Configuration/MODELS_FOLDER',
	'Processing/Configuration/OUTPUTS_FOLDER','Processing/Configuration/POST_EXECUTION_SCRIPT',
	'Processing/Configuration/PREFER_FILENAME_AS_LAYER_NAME','Processing/Configuration/PRE_EXECUTION_SCRIPT',
	'Processing/Configuration/RASTER_STYLE','Processing/Configuration/RESULTS_GROUP_NAME',
	'Processing/Configuration/SAGA_IMPORT_EXPORT_OPTIMIZATION','Processing/Configuration/SAGA_LOG_COMMANDS',
	'Processing/Configuration/SAGA_LOG_CONSOLE','Processing/Configuration/SCRIPTS_FOLDERS',
	'Processing/Configuration/SHOW_ALGORITHMS_KNOWN_ISSUES','Processing/Configuration/SHOW_CRS_DEF',
	'Processing/Configuration/SHOW_PROVIDERS_TOOLTIP','Processing/Configuration/TEMP_PATH2',
	'Processing/Configuration/VECTOR_FEATURE_COUNT','Processing/Configuration/VECTOR_LINE_STYLE',
	'Processing/Configuration/VECTOR_POINT_STYLE','Processing/Configuration/VECTOR_POLYGON_STYLE',
	'Processing/Configuration/WARN_UNMATCHING_CRS','Processing/LastOutputPath',
	'Processing/LastVectorOutputExt','Processing/geometryScriptEditor','Processing/hasPortedOldLog',
	'Processing/lastModelsDir','Processing/lastScriptsDir','Processing/lastUsedLogDirectory',
	'Processing/modelParametersDefinitionDialogGeometry','Processing/multipleInputDialogGeometry',
	'Processing/stateScriptEditor','Projections/layerDefaultCrs',
	
	'PythonPlugins/GdalTools','PythonPlugins/LoadQSS','PythonPlugins/MetaSearch','PythonPlugins/QuickOSM',
	'PythonPlugins/StreetView','PythonPlugins/db_manager','PythonPlugins/fiberklarprocesssuit','PythonPlugins/grassprovider',
	'PythonPlugins/joinmultiplelines','PythonPlugins/kmltools','PythonPlugins/latlontools','PythonPlugins/lftools',
	'PythonPlugins/plugin_reloader','PythonPlugins/processing','PythonPlugins/quick_map_services','PythonPlugins/refFunctions',
	'PythonPlugins/sagaprovider','PythonPlugins/unifiberprocesssuit','PythonPlugins/watchDog/lftools',
	
	'QgsCollapsibleGroupBox/QgisApp/groupLayerRendering/collapsed',
	'QgsCollapsibleGroupBox/QgsBookmarkEditorDialog/mExtentGroupBox/collapsed',
	'QgsCollapsibleGroupBox/QgsDataSourceManagerDialog/fileFormatGroupBox/collapsed',
	'QgsCollapsibleGroupBox/QgsDataSourceManagerDialog/geometryDefinitionGroupBox/collapsed',
	'QgsCollapsibleGroupBox/QgsDataSourceManagerDialog/layerSettingsGroupBox/collapsed',
	'QgsCollapsibleGroupBox/QgsDataSourceManagerDialog/recordOptionsGroupBox/collapsed',
	'QgsCollapsibleGroupBox/QgsFieldCalculatorBase/groupBox/collapsed',
	'QgsCollapsibleGroupBox/QgsJoinDialogBase/mEditableJoinLayer/collapsed',
	'QgsCollapsibleGroupBox/QgsJoinDialogBase/mUseCustomPrefix/collapsed',
	'QgsCollapsibleGroupBox/QgsJoinDialogBase/mUseJoinFieldsSubset/collapsed',
	'QgsCollapsibleGroupBox/QgsMeasureBase/groupBox/collapsed',
	'QgsCollapsibleGroupBox/QgsNewGeoPackageLayerDialog/groupBox/collapsed',
	'QgsCollapsibleGroupBox/QgsOptionsBase/groupBox/collapsed',
	'QgsCollapsibleGroupBox/QgsOptionsBase/groupBoxAutoCompletion/checked',
	'QgsCollapsibleGroupBox/QgsOptionsBase/groupBoxAutoCompletion/collapsed',
	'QgsCollapsibleGroupBox/QgsOptionsBase/groupBoxRunDebugEditor/collapsed',
	'QgsCollapsibleGroupBox/QgsOptionsBase/groupBox_11/collapsed',
	'QgsCollapsibleGroupBox/QgsOptionsBase/groupBox_2/collapsed',
	'QgsCollapsibleGroupBox/QgsOptionsBase/groupBox_29/collapsed',
	'QgsCollapsibleGroupBox/QgsOptionsBase/groupBox_4/collapsed',
	'QgsCollapsibleGroupBox/QgsOptionsBase/grpLocale/collapsed',
	'QgsCollapsibleGroupBox/QgsOptionsBase/mCurrentVariablesGrpBx/collapsed',
	'QgsCollapsibleGroupBox/QgsOptionsBase/mEnvironmentGrpBx/collapsed',
	'QgsCollapsibleGroupBox/QgsOptionsBase/mQSettingsGrpBx/collapsed',
	'QgsCollapsibleGroupBox/QgsPluginManagerBase/ckbDeprecated/checked',
	'QgsCollapsibleGroupBox/QgsPluginManagerBase/ckbDeprecated/collapsed',
	'QgsCollapsibleGroupBox/QgsPluginManagerBase/ckbExperimental/checked',
	'QgsCollapsibleGroupBox/QgsPluginManagerBase/ckbExperimental/collapsed',
	'QgsCollapsibleGroupBox/QgsProcessingDialogBase/grpAdvanced/collapsed',
	'QgsCollapsibleGroupBox/QgsProjectPropertiesBase/btnGrpMeasureEllipsoid/collapsed',
	'QgsCollapsibleGroupBox/QgsProjectPropertiesBase/groupBox/collapsed',
	'QgsCollapsibleGroupBox/QgsProjectPropertiesBase/groupBox_2/collapsed',
	'QgsCollapsibleGroupBox/QgsProjectPropertiesBase/groupBox_7/collapsed',
	'QgsCollapsibleGroupBox/QgsProjectPropertiesBase/grpProjectScales/collapsed',
	'QgsCollapsibleGroupBox/QgsProjectPropertiesBase/grpWMSExt/collapsed',
	'QgsCollapsibleGroupBox/QgsProjectPropertiesBase/grpWMSList/collapsed',
	'QgsCollapsibleGroupBox/QgsProjectPropertiesBase/mCoordinateDisplayGroup/collapsed',
	'QgsCollapsibleGroupBox/QgsProjectPropertiesBase/mExtentGroupBox/collapsed',
	'QgsCollapsibleGroupBox/QgsProjectPropertiesBase/mGroupBoxStyleDatabases/collapsed',
	'QgsCollapsibleGroupBox/QgsProjectPropertiesBase/mLayerCapabilitiesGrpBox/collapsed',
	'QgsCollapsibleGroupBox/QgsProjectPropertiesBase/mLayerRestrictionsGroupBox/collapsed',
	'QgsCollapsibleGroupBox/QgsProjectPropertiesBase/mWMSInspire/collapsed',
	'QgsCollapsibleGroupBox/QgsProjectPropertiesBase/mWMSPrintLayoutGroupBox/collapsed',
	'QgsCollapsibleGroupBox/QgsProjectPropertiesBase/titleBox/collapsed',
	'QgsCollapsibleGroupBox/QgsProviderSublayersDialogBase/groupBox/collapsed',
	'QgsCollapsibleGroupBox/QgsQueryBuilderBase/groupBox4/collapsed',
	'QgsCollapsibleGroupBox/QgsTextAnnotationDialogBase/mMarginsGroupBox/collapsed',
	'QgsCollapsibleGroupBox/QgsVectorLayerPropertiesBase/groupBox/collapsed',
	'QgsCollapsibleGroupBox/QgsVectorLayerPropertiesBase/groupBoxActionList/collapsed',
	'QgsCollapsibleGroupBox/QgsVectorLayerPropertiesBase/groupBox_2/collapsed',
	'QgsCollapsibleGroupBox/QgsVectorLayerPropertiesBase/groupBox_3/collapsed',
	'QgsCollapsibleGroupBox/QgsVectorLayerPropertiesBase/groupBox_4/collapsed',
	'QgsCollapsibleGroupBox/QgsVectorLayerPropertiesBase/groupBox_60/collapsed',
	'QgsCollapsibleGroupBox/QgsVectorLayerPropertiesBase/groupLayerRendering/collapsed',
	'QgsCollapsibleGroupBox/QgsVectorLayerPropertiesBase/mCrsGroupBox/collapsed',
	'QgsCollapsibleGroupBox/QgsVectorLayerPropertiesBase/mFilterGroupBox/collapsed',
	'QgsCollapsibleGroupBox/QgsVectorLayerPropertiesBase/mGeomGroupBox/collapsed',
	'QgsCollapsibleGroupBox/QgsVectorLayerPropertiesBase/mMetaAttributionGrpBx/collapsed',
	'QgsCollapsibleGroupBox/QgsVectorLayerPropertiesBase/mMetaDescriptionGrpBx/collapsed',
	'QgsCollapsibleGroupBox/QgsVectorLayerPropertiesBase/mMetaLegendGrpBx/collapsed',
	'QgsCollapsibleGroupBox/QgsVectorLayerPropertiesBase/mScaleVisibilityGroupBox/collapsed',
	'QgsCollapsibleGroupBox/QgsVectorLayerPropertiesBase/mShowInAttributeTable/collapsed',
	'QgsCollapsibleGroupBox/QgsVectorLayerPropertiesBase/mSubsetGroupBox/collapsed',
	'QgsCollapsibleGroupBox/QgsVectorLayerPropertiesBase/mUseReferenceScaleGroupBox/collapsed',
	'QgsCollapsibleGroupBox/QgsVectorLayerPropertiesBase/mWmsDimensionsGrpBx/collapsed',
	'QgsCollapsibleGroupBox/QgsVectorLayerSaveAsDialogBase/mAttributesSelection/collapsed',
	'QgsCollapsibleGroupBox/QgsVectorLayerSaveAsDialogBase/mDatasourceOptionsGroupBox/collapsed',
	'QgsCollapsibleGroupBox/QgsVectorLayerSaveAsDialogBase/mExtentGroupBox/collapsed',
	'QgsCollapsibleGroupBox/QgsVectorLayerSaveAsDialogBase/mGeometryGroupBox/collapsed',
	'QgsCollapsibleGroupBox/QgsVectorLayerSaveAsDialogBase/mLayerOptionsGroupBox/collapsed',
	'QgsCollapsibleGroupBox/QgsVectorLayerSaveAsDialogBase/mOgrOptionsGroupBox/collapsed',
	'QgsCollapsibleGroupBox/mAdvLabelingDlg/groupBox_mPreview/collapsed',
	'QgsCollapsibleGroupBox/mAdvLabelingDlg/mPlacementOverrunGroupBox_2/collapsed',
	'QgsCollapsibleGroupBox/mAdvLabelingDlg/mRenderingLabelGrpBx/collapsed',

	'QgsVariableEditor/Global/expanded','QgsVariableEditorTree/globalOptions/column0width',
	'QgsVariableEditorTree/mVariablesEditor/column0width','QgsVariableEditorTree/projectProperties/column0width',
	
	'QuickOSM/copyright_dialog','QuickOSM/defaultNominatimAPI','QuickOSM/defaultOAPI',

	'Raster/cumulativeCutLower','Raster/cumulativeCutUpper','Raster/defaultBlueBand',
	'Raster/defaultContrastEnhancementAlgorithm/multiBandMultiByte',
	'Raster/defaultContrastEnhancementAlgorithm/multiBandSingleByte','Raster/defaultContrastEnhancementAlgorithm/singleBand',
	'Raster/defaultContrastEnhancementLimits/multiBandMultiByte','Raster/defaultContrastEnhancementLimits/multiBandSingleByte',
	'Raster/defaultContrastEnhancementLimits/singleBand','Raster/defaultEarlyResampling','Raster/defaultGreenBand',
	'Raster/defaultOversampling','Raster/defaultRedBand','Raster/defaultStandardDeviation','Raster/defaultZoomedInResampling',
	'Raster/defaultZoomedOutResampling',

	'UI/UITheme','UI/annotationTool','UI/defaultAddDbLayerAction','UI/defaultNewLayer','UI/defaultVertexTool',
	'UI/deselectionTool','UI/encoding','UI/geometry','UI/lastFileNameWidgetDir','UI/lastProjectDir','UI/lastVectorFileFilter',
	'UI/lastVectorFileFilterDir','UI/lastVectorFormat','UI/measureTool','UI/openTableTool','UI/recentProjectionsAuthId',
	'UI/recentProjectionsProj4','UI/recentProjectionsWkt','UI/recentProjects/1/crs','UI/recentProjects/1/path',
	'UI/recentProjects/1/pin','UI/recentProjects/1/previewImage','UI/recentProjects/1/title','UI/recentProjects/10/crs',
	'UI/recentProjects/10/path','UI/recentProjects/10/pin','UI/recentProjects/10/previewImage','UI/recentProjects/10/title',
	'UI/recentProjects/11/crs','UI/recentProjects/11/path','UI/recentProjects/11/pin','UI/recentProjects/11/previewImage',
	'UI/recentProjects/11/title','UI/recentProjects/12/crs','UI/recentProjects/12/path','UI/recentProjects/12/pin',
	'UI/recentProjects/12/previewImage','UI/recentProjects/12/title','UI/recentProjects/13/crs','UI/recentProjects/13/path',
	'UI/recentProjects/13/pin','UI/recentProjects/13/previewImage','UI/recentProjects/13/title','UI/recentProjects/14/crs',
	'UI/recentProjects/14/path','UI/recentProjects/14/pin','UI/recentProjects/14/previewImage','UI/recentProjects/14/title',
	'UI/recentProjects/15/crs','UI/recentProjects/15/path','UI/recentProjects/15/pin','UI/recentProjects/15/previewImage',
	'UI/recentProjects/15/title','UI/recentProjects/16/crs','UI/recentProjects/16/path','UI/recentProjects/16/pin',
	'UI/recentProjects/16/previewImage','UI/recentProjects/16/title','UI/recentProjects/17/crs','UI/recentProjects/17/path',
	'UI/recentProjects/17/pin','UI/recentProjects/17/previewImage','UI/recentProjects/17/title','UI/recentProjects/18/crs',
	'UI/recentProjects/18/path','UI/recentProjects/18/pin','UI/recentProjects/18/previewImage','UI/recentProjects/18/title',
	'UI/recentProjects/19/crs','UI/recentProjects/19/path','UI/recentProjects/19/pin','UI/recentProjects/19/previewImage',
	'UI/recentProjects/19/title','UI/recentProjects/2/crs','UI/recentProjects/2/path','UI/recentProjects/2/pin',
	'UI/recentProjects/2/previewImage','UI/recentProjects/2/title','UI/recentProjects/20/crs','UI/recentProjects/20/path',
	'UI/recentProjects/20/pin','UI/recentProjects/20/previewImage','UI/recentProjects/20/title','UI/recentProjects/3/crs',
	'UI/recentProjects/3/path','UI/recentProjects/3/pin','UI/recentProjects/3/previewImage','UI/recentProjects/3/title',
	'UI/recentProjects/4/crs','UI/recentProjects/4/path','UI/recentProjects/4/pin','UI/recentProjects/4/previewImage',
	'UI/recentProjects/4/title','UI/recentProjects/5/crs','UI/recentProjects/5/path','UI/recentProjects/5/pin',
	'UI/recentProjects/5/previewImage','UI/recentProjects/5/title','UI/recentProjects/6/crs','UI/recentProjects/6/path',
	'UI/recentProjects/6/pin','UI/recentProjects/6/previewImage','UI/recentProjects/6/title','UI/recentProjects/7/crs',
	'UI/recentProjects/7/path','UI/recentProjects/7/pin','UI/recentProjects/7/previewImage','UI/recentProjects/7/title',
	'UI/recentProjects/8/crs','UI/recentProjects/8/path','UI/recentProjects/8/pin','UI/recentProjects/8/previewImage',
	'UI/recentProjects/8/title','UI/recentProjects/9/crs','UI/recentProjects/9/path','UI/recentProjects/9/pin',
	'UI/recentProjects/9/previewImage','UI/recentProjects/9/title','UI/selectTool','UI/selectionTool',
	'UI/showInstallFromZipWarning','UI/state',

	'Windows/AttributeDialog/geometry','Windows/BetterAttributeTable/geometry','Windows/Bookmarks/headerstateV2',
	'Windows/CodeEditorOptions/splitterState',
	'Windows/ColorDialog/activeComponent','Windows/ColorDialog/activeScheme','Windows/ColorDialog/activeTab',
	'Windows/ColorDialog/customColor1','Windows/ColorDialog/customColor10','Windows/ColorDialog/customColor11',
	'Windows/ColorDialog/customColor12','Windows/ColorDialog/customColor13','Windows/ColorDialog/customColor14',
	'Windows/ColorDialog/customColor15','Windows/ColorDialog/customColor16','Windows/ColorDialog/customColor2',
	'Windows/ColorDialog/customColor3','Windows/ColorDialog/customColor4','Windows/ColorDialog/customColor5',
	'Windows/ColorDialog/customColor6','Windows/ColorDialog/customColor7','Windows/ColorDialog/customColor8',
	'Windows/ColorDialog/customColor9','Windows/ColorDialog/sampleRadius',
	'Windows/Data Source Manager/geometry','Windows/Data Source Manager/splitState','Windows/Data Source Manager/tab',
	'Windows/DatumTransformDialog/columnWidths/0','Windows/DatumTransformDialog/columnWidths/1',
	'Windows/DatumTransformDialog/hideDeprecated',
	'Windows/DatumTransformTable/headerState',
	'Windows/Diagrams/OptionsSplitState','Windows/Diagrams/Tab',
	'Windows/DlgHistory/geometry',
	'Windows/HanaSourceSelect/HoldDialogOpen','Windows/HanaSourceSelect/columnWidths/0','Windows/HanaSourceSelect/columnWidths/1',
	'Windows/HanaSourceSelect/columnWidths/2','Windows/HanaSourceSelect/columnWidths/3','Windows/HanaSourceSelect/columnWidths/4',
	'Windows/HanaSourceSelect/columnWidths/5','Windows/HanaSourceSelect/columnWidths/6','Windows/HanaSourceSelect/columnWidths/7',
	'Windows/HanaSourceSelect/columnWidths/8','Windows/HanaSourceSelect/geometry',
	'Windows/Identify/columnWidth',
	'Windows/Labeling/FontPreviewSplitState','Windows/Labeling/OptionsSplitState','Windows/Labeling/Tab',
	'Windows/MSSQLSourceSelect/HoldDialogOpen','Windows/MSSQLSourceSelect/columnWidths/0','Windows/MSSQLSourceSelect/columnWidths/1',
	'Windows/MSSQLSourceSelect/columnWidths/2','Windows/MSSQLSourceSelect/columnWidths/3','Windows/MSSQLSourceSelect/columnWidths/4',
	'Windows/MSSQLSourceSelect/columnWidths/5','Windows/MSSQLSourceSelect/columnWidths/6','Windows/MSSQLSourceSelect/columnWidths/7',
	'Windows/MSSQLSourceSelect/columnWidths/8',
	'Windows/MainWindow/geometry',
	'Windows/Measure/h',
	'Windows/ModelerParametersDialog/geometry',
	'Windows/Options/geometry','Windows/Options/splitState','Windows/Options/tab',
	'Windows/OracleSourceSelect/HoldDialogOpen','Windows/OracleSourceSelect/columnWidths/0','Windows/OracleSourceSelect/columnWidths/1',
	'Windows/OracleSourceSelect/columnWidths/2','Windows/OracleSourceSelect/columnWidths/3','Windows/OracleSourceSelect/columnWidths/4',
	'Windows/OracleSourceSelect/columnWidths/5','Windows/OracleSourceSelect/columnWidths/6','Windows/OracleSourceSelect/columnWidths/7',
	'Windows/PgSourceSelect/HoldDialogOpen','Windows/PgSourceSelect/columnWidths/0','Windows/PgSourceSelect/columnWidths/1',
	'Windows/PgSourceSelect/columnWidths/10','Windows/PgSourceSelect/columnWidths/2','Windows/PgSourceSelect/columnWidths/3',
	'Windows/PgSourceSelect/columnWidths/4','Windows/PgSourceSelect/columnWidths/5','Windows/PgSourceSelect/columnWidths/6',
	'Windows/PgSourceSelect/columnWidths/7','Windows/PgSourceSelect/columnWidths/8','Windows/PgSourceSelect/columnWidths/9',
	'Windows/PluginManager/geometry','Windows/PluginManager/option','Windows/PluginManager/secondSplitterState',
	'Windows/PluginManager/splitState','Windows/PluginManager/tab',
	'Windows/ProjectProperties/geometry','Windows/ProjectProperties/splitState','Windows/ProjectProperties/tab',
	'Windows/ProjectionSelector/splitterState',
	'Windows/ProjectionSelectorDialog/splitterState',
	'Windows/QWidget/geometry',
	'Windows/QgsBookmarkEditorDialog/geometry',
	'Windows/QgsColorDialogBase/geometry',
	'Windows/QgsConfigureShortcutsDialog/geometry',
	'Windows/QgsDataSourceSelectDialog/geometry',
	'Windows/QgsDatumTransformDialogBase/geometry',
	'Windows/QgsDelAttrDialogBase/geometry',
	'Windows/QgsDxfExportDialogBase/geometry',
	'Windows/QgsExpressionBuilderDialogBase/geometry',
	'Windows/QgsExpressionBuilderWidget/editorsplitter',
	'Windows/QgsExpressionBuilderWidget/functionsplitter',
	'Windows/QgsExpressionBuilderWidget/splitter',
	'Windows/QgsExpressionSelectionDialogBase/geometry',
	'Windows/QgsFieldCalculatorBase/geometry',
	'Windows/QgsMeasureBase/geometry',
	'Windows/QgsMessageViewer/geometry',
	'Windows/QgsModelDesignerDialogBase/geometry',
	'Windows/QgsNewGeoPackageLayerDialog/geometry',
	'Windows/QgsNewMemoryLayerDialogBase/geometry',
	'Windows/QgsNewVectorLayerDialogBase/geometry',
	'Windows/QgsOrganizeTableColumnsDialog/geometry',
	'Windows/QgsPgNewConnectionBase/geometry',
	'Windows/QgsPluginInstallerFetchingDialogBase/geometry',
	'Windows/QgsProcessingDialogBase/geometry',
	'Windows/QgsProcessingParameterDefinitionDialog/geometry',
	'Windows/QgsProviderSublayersDialogBase/geometry',
	'Windows/QgsQueryBuilderBase/geometry',
	'Windows/QgsRendererRulePropsDialog/geometry',
	'Windows/QgsSelectByFormDialog/geometry',
	'Windows/QgsStyleManagerDialogBase/geometry',
	'Windows/QgsStyleSaveDialog/geometry',
	'Windows/QgsTextAnnotationDialogBase/geometry',
	'Windows/QgsVectorLayerLoadStyleDialog/geometry',
	'Windows/QgsVectorLayerSaveAsDialogBase/geometry',
	'Windows/QgsVectorLayerSaveStyleDialog/geometry',
	'Windows/RuleBasedTree/sectionWidth/0',
	'Windows/RuleBasedTree/sectionWidth/1',
	'Windows/RuleBasedTree/sectionWidth/2',
	'Windows/RuleBasedTree/sectionWidth/3',
	'Windows/RuleBasedTree/sectionWidth/4',
	'Windows/SQLCommandsDialog/geometry',
	'Windows/SnappingWidget/geometry',
	'Windows/SpatiaLiteSourceSelect/HoldDialogOpen',
	'Windows/StyleV2Manager/splitter',
	'Windows/SubLayers/headerState',
	'Windows/SymbolSelectorDialog/geometry',
	'Windows/VectorLayerProperties/geometry',
	'Windows/VectorLayerProperties/splitState',
	'Windows/VectorLayerProperties/tab',
	'Windows/VirtualLayer/layerTableHeaderState',
	'Windows/WFSSourceSelect/FeatureCurrentViewExtent',
	'Windows/WFSSourceSelect/HoldDialogOpen',
	'Windows/WFSSourceSelect/UseTitleLayerName',
	'Windows/about/geometry',
	'Windows/about/splitState',
	'Windows/about/tab',

	'app/ModelDesigner/state',
	'app/Windows/WelcomePage/SplitState',
	'app/Windows/WelcomePage/SplitState2',
	'app/askToDeleteFeatures',
	'app/map3d/axisInversion',
	'app/map3d/defaultFieldOfView',
	'app/map3d/defaultMovementSpeed',
	'app/map3d/defaultNavigation',
	'app/map3d/defaultProjection',
	'app/plugin_installer/allowDeprecated',
	'app/plugin_installer/allowExperimental',
	'app/plugin_installer/checkOnStart',
	'app/plugin_installer/checkOnStartInterval',
	'app/plugin_installer/checkOnStartLastDate',
	'app/plugin_installer/lastZipDirectory',
	'app/plugin_installer/seen_plugins',
	'app/plugin_repositories/Repositório oficial de módulos do QGIS/url',
	'app/projections/crsAccuracyWarningThreshold',

	'browser/expandedPaths',
	'browser/hiddenPaths',

	'cache/size',

	'colors/recent',

	'core/Layout/searchPathsForTemplates',
	'core/NewsFeed/httpsfeedqgisorg/49/content',
	'core/NewsFeed/httpsfeedqgisorg/49/imageUrl',
	'core/NewsFeed/httpsfeedqgisorg/49/link',
	'core/NewsFeed/httpsfeedqgisorg/49/sticky',
	'core/NewsFeed/httpsfeedqgisorg/49/title',
	'core/NewsFeed/httpsfeedqgisorg/62/content',
	'core/NewsFeed/httpsfeedqgisorg/62/expiry',
	'core/NewsFeed/httpsfeedqgisorg/62/imageUrl',
	'core/NewsFeed/httpsfeedqgisorg/62/link',
	'core/NewsFeed/httpsfeedqgisorg/62/sticky',
	'core/NewsFeed/httpsfeedqgisorg/62/title',
	'core/NewsFeed/httpsfeedqgisorg/65/content',
	'core/NewsFeed/httpsfeedqgisorg/65/expiry',
	'core/NewsFeed/httpsfeedqgisorg/65/imageUrl',
	'core/NewsFeed/httpsfeedqgisorg/65/link',
	'core/NewsFeed/httpsfeedqgisorg/65/sticky',
	'core/NewsFeed/httpsfeedqgisorg/65/title',
	'core/NewsFeed/httpsfeedqgisorg/72/content',
	'core/NewsFeed/httpsfeedqgisorg/72/expiry',
	'core/NewsFeed/httpsfeedqgisorg/72/imageUrl',
	'core/NewsFeed/httpsfeedqgisorg/72/link',
	'core/NewsFeed/httpsfeedqgisorg/72/sticky',
	'core/NewsFeed/httpsfeedqgisorg/72/title',
	'core/NewsFeed/httpsfeedqgisorg/74/content',
	'core/NewsFeed/httpsfeedqgisorg/74/expiry',
	'core/NewsFeed/httpsfeedqgisorg/74/imageUrl',
	'core/NewsFeed/httpsfeedqgisorg/74/link',
	'core/NewsFeed/httpsfeedqgisorg/74/sticky',
	'core/NewsFeed/httpsfeedqgisorg/74/title',
	'core/NewsFeed/httpsfeedqgisorg/disabled',
	'core/NewsFeed/httpsfeedqgisorg/lastFetchTime',
	'core/OpenClDefaultDevice',
	'core/OpenClEnabled',
	'core/layer-tree/show_feature_count_for_new_layers',

	'defaults/bearing_format/decimal_separator',
	'defaults/bearing_format/decimals',
	'defaults/bearing_format/direction_format',
	'defaults/bearing_format/rounding_type',
	'defaults/bearing_format/show_plus',
	'defaults/bearing_format/show_thousand_separator',
	'defaults/bearing_format/show_trailing_zeros',
	'defaults/bearing_format/thousand_separator',
	'defaults/coordinate_format/angle_format',
	'defaults/coordinate_format/decimal_separator',
	'defaults/coordinate_format/decimals',
	'defaults/coordinate_format/rounding_type',
	'defaults/coordinate_format/show_leading_degree_zeros',
	'defaults/coordinate_format/show_leading_zeros',
	'defaults/coordinate_format/show_plus',
	'defaults/coordinate_format/show_suffix',
	'defaults/coordinate_format/show_thousand_separator',
	'defaults/coordinate_format/show_trailing_zeros',
	'defaults/coordinate_format/thousand_separator',

	'expressions/recent/fieldcalc',
	'expressions/recent/generic',
	'expressions/recent/selection',

	'fonts/downloadMissingFonts',
	'fonts/fontFamilyReplacements',

	'gps/acquisitionInterval',
	'gps/applyLeapSeconds',
	'gps/autoAddVertices',
	'gps/autoCommit',
	'gps/babelDeviceList',
	'gps/babelDevices/Garmin serial/rtedownload',
	'gps/babelDevices/Garmin serial/rteupload',
	'gps/babelDevices/Garmin serial/trkdownload',
	'gps/babelDevices/Garmin serial/trkupload',
	'gps/babelDevices/Garmin serial/wptdownload',
	'gps/babelDevices/Garmin serial/wptupload',
	'gps/bearingLineSymbol',
	'gps/calculateBearingFromTravel',
	'gps/distanceThreshold',
	'gps/gpsdDevice',
	'gps/gpsdHost',
	'gps/gpsdPort',
	'gps/lastPort',
	'gps/location-marker-symbol',
	'gps/mapExtentMultiplier',
	'gps/markerSize',
	'gps/panMode',
	'gps/portMode',
	'gps/rotate-location-marker',
	'gps/rotateMap',
	'gps/rotateMapInterval',
	'gps/showBearingLine',
	'gps/showMarker',
	'gps/timestampFormat',
	'gps/timestampTimeZone',
	'gps/trackColor',
	'gps/trackWidth',

	'gui/LayoutDesigner/defaultSnapGridOffsetX',
	'gui/LayoutDesigner/defaultSnapGridOffsetY',
	'gui/LayoutDesigner/defaultSnapGridResolution',
	'gui/LayoutDesigner/defaultSnapTolerancePixels',
	'gui/LayoutDesigner/gridAlpha',
	'gui/LayoutDesigner/gridBlue',
	'gui/LayoutDesigner/gridGreen',
	'gui/LayoutDesigner/gridRed',
	'gui/LayoutDesigner/gridStyle',
	'gui/UI/symbolsList/lastIconView',
	'gui/UI/symbolsList/treeState',
	'gui/Windows/StyleV2Manager/lastIconView',
	'gui/Windows/StyleV2Manager/thumbnailSize',
	'gui/Windows/StyleV2Manager/treeState',
	'gui/codeEditor/caretLineColor',
	'gui/codeEditor/classFontColor',
	'gui/codeEditor/colorScheme',
	'gui/codeEditor/commentBlockFontColor',
	'gui/codeEditor/commentFontColor',
	'gui/codeEditor/commentLineFontColor',
	'gui/codeEditor/cursorColor',
	'gui/codeEditor/decoratorFontColor',
	'gui/codeEditor/defaultFontColor',
	'gui/codeEditor/doubleQuoteFontColor',
	'gui/codeEditor/edgeColor',
	'gui/codeEditor/foldColor',
	'gui/codeEditor/foldIconForeground',
	'gui/codeEditor/foldIconHalo',
	'gui/codeEditor/identifierFontColor',
	'gui/codeEditor/indentationGuide',
	'gui/codeEditor/keywordFontColor',
	'gui/codeEditor/marginBackgroundColor',
	'gui/codeEditor/marginForegroundColor',
	'gui/codeEditor/matchedBraceBackground',
	'gui/codeEditor/matchedBraceColor',
	'gui/codeEditor/methodFontColor',
	'gui/codeEditor/numberFontColor',
	'gui/codeEditor/operatorFontColor',
	'gui/codeEditor/overrideColors',
	'gui/codeEditor/paperBackgroundColor',
	'gui/codeEditor/quotedIdentifierFontColor',
	'gui/codeEditor/quotedOperatorFontColor',
	'gui/codeEditor/selectionBackgroundColor',
	'gui/codeEditor/selectionForegroundColor',
	'gui/codeEditor/singleQuoteFontColor',
	'gui/codeEditor/stderrBackgroundColor',
	'gui/codeEditor/stderrFontColor',
	'gui/codeEditor/tagFontColor',
	'gui/codeEditor/tripleDoubleQuoteFontColor',
	'gui/codeEditor/tripleSingleQuoteFontColor',
	'gui/codeEditor/unknownTagFontColor',
	'gui/processing/recentAlgorithms',
	'gui/qgis/respect_screen_dpi',

	'locale/globalLocale',
	'locale/overrideFlag',
	'locale/showGroupSeparator',
	'locale/userLocale',
	
	'myStyles/Activated',
	'myStyles/BlueGlass/name',
	'myStyles/BlueGlass/path',
	'myStyles/Coffee/name',
	'myStyles/Coffee/path',
	'myStyles/Dark Blue (FreeCAD)/name',
	'myStyles/Dark Blue (FreeCAD)/path',
	'myStyles/Dark Green (FreeCAD)/name',
	'myStyles/Dark Green (FreeCAD)/path',
	'myStyles/Dark Orange (FreeCAD)/name',
	'myStyles/Dark Orange (FreeCAD)/path',
	'myStyles/Dark/name',
	'myStyles/Dark/path',
	'myStyles/DarkOrange/name',
	'myStyles/DarkOrange/path',
	'myStyles/Light Blue (FreeCAD)/name',
	'myStyles/Light Blue (FreeCAD)/path',
	'myStyles/Light Green (FreeCAD)/name',
	'myStyles/Light Green (FreeCAD)/path',
	'myStyles/Light Orange (FreeCAD)/name',
	'myStyles/Light Orange (FreeCAD)/path',
	'myStyles/Minimalist/name',
	'myStyles/Minimalist/path',
	'myStyles/Preview',
	'myStyles/Wombat/name',
	'myStyles/Wombat/path',
	'myStyles/light/name',
	'myStyles/light/path',
	'myStyles/machinery/name',
	'myStyles/machinery/path',

	'plugins/automatically-check-for-updates',
	'plugins/plugin_topology',
	'plugins/searchPathsForPlugins',
	'plugins/topolplugin',

	'providers/ogr/GPKGSourceSelect/HoldDialogOpen',

	'proxy/authcfg',
	'proxy/noProxyUrls',
	'proxy/proxyEnabled',
	'proxy/proxyHost',
	'proxy/proxyPassword',
	'proxy/proxyPort',
	'proxy/proxyType',
	'proxy/proxyUser',

	'pythonConsole/accessTokenGithub',
	'pythonConsole/autoCloseBracket',
	'pythonConsole/autoCompThreshold',
	'pythonConsole/autoCompleteEnabled',
	'pythonConsole/autoCompleteSource',
	'pythonConsole/autoInsertionImport',
	'pythonConsole/autoSaveScript',
	'pythonConsole/enableObjectInsp',
	'pythonConsole/lastDirPath',
	'pythonConsole/preloadAPI',
	'pythonConsole/preparedAPIFile',
	'pythonConsole/splitterConsole',
	'pythonConsole/splitterEditor',
	'pythonConsole/splitterObj',
	'pythonConsole/tabScripts',
	'pythonConsole/usePreparedAPIFile',
	'pythonConsole/userAPI',

	'qgis/askToDeleteLayers',
	'qgis/askToSaveProjectChanges',
	'qgis/attributeTable/splitterState',
	'qgis/attributeTableBehavior',
	'qgis/attributeTableLastAddFeatureMethod',
	'qgis/attributeTableRowCache',
	'qgis/attributeTableView',
	'qgis/connections-wcs/selected',
	'qgis/connections-xyz/selected',
	'qgis/copyFeatureFormat',
	'qgis/customEnvVars',
	'qgis/customEnvVarsUse',
	'qgis/dataSourceManagerNonModal',
	'qgis/defaultCapabilitiesExpiry',
	'qgis/defaultLegendGraphicResolution',
	'qgis/defaultProjectFileFormat',
	'qgis/defaultTileExpiry',
	'qgis/defaultTileMaxRetry',
	'qgis/default_canvas_color_blue',
	'qgis/default_canvas_color_green',
	'qgis/default_canvas_color_red',
	'qgis/default_measure_color_blue',
	'qgis/default_measure_color_green',
	'qgis/default_measure_color_red',
	'qgis/default_selection_color_alpha',
	'qgis/default_selection_color_blue',
	'qgis/default_selection_color_green',
	'qgis/default_selection_color_red',
	'qgis/digitizing/convert_to_curve',
	'qgis/digitizing/convert_to_curve_angle_tolerance',
	'qgis/digitizing/convert_to_curve_distance_tolerance',
	'qgis/digitizing/default_m_value',
	'qgis/digitizing/default_snap_type',
	'qgis/digitizing/default_snapping_tolerance',
	'qgis/digitizing/default_z_value',
	'qgis/digitizing/disable_enter_attribute_values_dialog',
	'qgis/digitizing/fill_color_alpha',
	'qgis/digitizing/fill_color_blue',
	'qgis/digitizing/fill_color_green',
	'qgis/digitizing/fill_color_red',
	'qgis/digitizing/line_color_alpha',
	'qgis/digitizing/line_color_blue',
	'qgis/digitizing/line_color_green',
	'qgis/digitizing/line_color_red',
	'qgis/digitizing/line_ghost',
	'qgis/digitizing/line_width',
	'qgis/digitizing/marker_only_for_selected',
	'qgis/digitizing/marker_size_mm',
	'qgis/digitizing/marker_style',
	'qgis/digitizing/offset_join_style',
	'qgis/digitizing/offset_miter_limit',
	'qgis/digitizing/offset_quad_seg',
	'qgis/digitizing/reuseLastValues',
	'qgis/digitizing/search_radius_vertex_edit',
	'qgis/digitizing/search_radius_vertex_edit_unit',
	'qgis/digitizing/shape-map-tools/Circle/default',
	'qgis/digitizing/shape-map-tools/Curve/default',
	'qgis/digitizing/shape-map-tools/Ellipse/default',
	'qgis/digitizing/shape-map-tools/Rectangle/default',
	'qgis/digitizing/shape-map-tools/RegularPolygon/default',
	'qgis/digitizing/snap_color',
	'qgis/digitizing/snap_tooltip',
	'qgis/digitizing/validate_geometries',
	'qgis/dockAttributeTable',
	'qgis/enableMacros',
	'qgis/enable_anti_aliasing',
	'qgis/enable_render_caching',
	'qgis/hideSplash',
	'qgis/iconSize',
	'qgis/lastDxfCrs',
	'qgis/lastDxfDir',
	'qgis/lastDxfEncoding',
	'qgis/lastDxfLayerTitleAsName',
	'qgis/lastDxfMapRectangle',
	'qgis/lastDxfSymbologyMode',
	'qgis/lastDxfUseMText',
	'qgis/lastSymbologyExportScale',
	'qgis/legendDoubleClickAction',
	'qgis/legendsymbolMaximumSize',
	'qgis/legendsymbolMinimumSize',
	'qgis/localized_data_paths',
	'qgis/magnifier_factor_default',
	'qgis/mainSnappingWidgetMode',
	'qgis/main_canvas_preview_jobs',
	'qgis/mapTipsDelay',
	'qgis/map_update_interval',
	'qgis/max_threads',
	'qgis/measure/angleunits',
	'qgis/measure/areaunits',
	'qgis/measure/decimalplaces',
	'qgis/measure/displayunits',
	'qgis/measure/keepbaseunit',
	'qgis/messageTimeout',
	'qgis/native_color_dialogs',
	'qgis/networkAndProxy/networkTimeout',
	'qgis/networkAndProxy/userAgent',
	'qgis/newProjectDefault',
	'qgis/new_layers_visible',
	'qgis/openSublayersInGroup',
	'qgis/overwriteStyle',
	'qgis/parallel_rendering',
	'qgis/projOpenAtLaunch',
	'qgis/projOpenAtLaunchPath',
	'qgis/projOpenedOKAtLaunch',
	'qgis/projectTemplateDir',
	'qgis/promptForSublayers',
	'qgis/scanItemsInBrowser2',
	'qgis/scanZipInBrowser2',
	'qgis/segmentationTolerance',
	'qgis/segmentationToleranceType',
	'qgis/showLegendClassifiers',
	'qgis/simplifyAlgorithm',
	'qgis/simplifyDrawingHints',
	'qgis/simplifyDrawingTol',
	'qgis/simplifyLocal',
	'qgis/simplifyMaxScale',
	'qgis/style',
	'qgis/symbolsListGroupsIndex',
	'qgis/warnOldProjectVersion',
	'qgis/zoom_factor',

	'qgsbrowserwidgetbase/expandedPaths',
	'qgsbrowserwidgetbase/propertiesWidgetEnabled',
	'qgsbrowserwidgetbase/propertiesWidgetHeight',

	'shortcuts/Add Delimited Text Layer…',
	'shortcuts/Add Oracle Spatial Layer…',
	'shortcuts/Add Point Feature',
	'shortcuts/Add PostGIS Layers…',
	'shortcuts/Add Raster Layer…',
	'shortcuts/Add SpatiaLite Layer…',
	'shortcuts/Add Vector Layer…',
	'shortcuts/Add WMS/WMTS Layer…',
	'shortcuts/Deselect Features from All Layers',
	'shortcuts/Deselect Features from the Current Active Layer',
	'shortcuts/Digitize with Curve',
	'shortcuts/Enable Tracing',
	'shortcuts/Exit QGIS',
	'shortcuts/Filter…',
	'shortcuts/Help Contents',
	'shortcuts/Hide All Layers',
	'shortcuts/Identify Features',
	'shortcuts/Layer Styling',
	'shortcuts/Measure Area',
	'shortcuts/Measure Line',
	'shortcuts/Modify Attributes of Selected Features',
	'shortcuts/Move Label, Diagram or Callout',
	'shortcuts/New GeoPackage Layer…',
	'shortcuts/New Spatial Bookmark…',
	'shortcuts/Open Attribute Table (Selected Features)',
	'shortcuts/Open Attribute Table (Visible Features)',
	'shortcuts/Python Console',
	'shortcuts/QGIS Home Page',
	'shortcuts/Refresh',
	'shortcuts/Remove Layer/Group',
	'shortcuts/Rotate Label',
	'shortcuts/Rotate Point Symbols',
	'shortcuts/Save for All Layers',
	'shortcuts/Select Feature(s)',
	'shortcuts/Select Features by Expression…',
	'shortcuts/Select Features by Value…',
	'shortcuts/Set CRS of Layer(s)',
	'shortcuts/Show All Layers',
	'shortcuts/Show Spatial Bookmarks',
	'shortcuts/Split Features',
	'shortcuts/Stream Digitizing',
	'shortcuts/Temporary Scratch Layer…',
	'shortcuts/Text Annotation',
	'shortcuts/Toggle Editing',
	'shortcuts/Toggle Map Only',
	'shortcuts/Topological Editing',
	'shortcuts/Vertex Tool (All Layers)',
	'shortcuts/Zoom In',
	'shortcuts/Zoom Out',
	'shortcuts/mActionCatchForCustomization',

	'style/lastLoadStyleTypeSelection',
	'style/lastStyleCategories',

	'svg/searchPathsForSVG'
]
```

