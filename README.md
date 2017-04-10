1. STEAM KODU
-malloc=system +mat_antialias 0 window -USEALLAVAILABLECORES

2. CONFIG AYARLARI

Başlat'a "%APPDATA%" yazın -> [Local] – [TslGame] – [Saved] – [Config] – [WindowsNoEditor] dosyasını açın.
--------------------------------------------------------------------------------------------------------------------------------------

GameUserSettings.ini KODU

[ScalabilityGroups]
sg.ResolutionQuality=70
sg.ViewDistanceQuality=0
sg.AntiAliasingQuality=0
sg.ShadowQuality=0
sg.PostProcessQuality=0
sg.TextureQuality=0
sg.EffectsQuality=0
sg.FoliageQuality=0
sg.TrueSkyQuality=0
sg.GroundClutterQuality=0
sg.IBLQuality=0
sg.HeightFieldShadowQuality=0

------------------------------------------------------------------------------------------------------------------------------------

Engine.ini KODU

[Core.System]
Paths=../../../Engine/Content
Paths=%GAMEDIR%Content
Paths=../../../Engine/Plugins/OceanPlugin/Content
Paths=../../../Engine/Plugins/Mutable/Content
Paths=../../../Engine/Plugins/Runtime/Coherent/CoherentUIGTPlugin/Content
Paths=../../../Engine/Plugins/RoadEditor/Content
Paths=../../../Engine/Plugins/2D/Paper2D/Content
Paths=../../../Engine/Plugins/Wwise/Content

[/script/engine.engine]
bSmoothFrameRate=true
MinDesiredFrameRate=60
SmoothedFrameRateRange=(LowerBound=(Type="ERangeBoundTypes::Inclusive",Value=60),UpperBound=(Type="ERangeBoundTypes::Exclusive",Value=144))
MaxPixelShaderAdditiveComplexityCount=128
MaxES2PixelShaderAdditiveComplexityCount=45
TimeBetweenPurgingPendingKillObjects=30
bDisablePhysXHardwareSupport=True

[/script/engine.renderersettings]
r.SeparateTranslucency=False
r.CustomDepth=1
r.DefaultFeature.Bloom=False
r.DefaultFeature.AmbientOcclusion=False
r.DefaultFeature.AmbientOcclusionStaticFraction=False
r.DefaultFeature.MotionBlur=False
r.DefaultFeature.LensFlare=False
r.DefaultFeature.AntiAliasing=0
r.ViewDistanceScale=1
r.ShadowQuality=0
r.Shadow.CSM.MaxCascades=1
r.Shadow.MaxResolution=256
r.Shadow.RadiusThreshold=0.1
r.Shadow.DistanceScale=0.1
r.Shadow.CSM.TransitionScale=0
r.DistanceFieldAO=0
r.DepthOfFieldQuality=0
r.RenderTargetPoolMin=300
r.LensFlareQuality=0
r.SceneColorFringeQuality=0
r.FastBlurThreshold=0
r.Upscale.Quality=1
r.TonemapperQuality=0
r.RefractionQuality=0
r.SSR.Quality=0
r.SceneColorFormat=3
r.TranslucencyVolumeBlur=0
r.MaterialQualityLevel=0
r.SSS.Scale=0
r.SSS.SampleSet=0
r.EmitterSpawnRateScale=0.75
-----------------------------------------------------------------------------------
Scability.ini KODU

[ScalabilitySettings]
PerfIndexValues_ResolutionQuality="50 50 50 50"

[AntiAliasingQuality@0]
r.MSAA.CompositingSampleCount=1

[ViewDistanceQuality@0]
r.SkeletalMeshLODBias=5

[ShadowQuality@0]
r.LightFunctionQuality=0
r.ShadowQuality=0
r.Shadow.CSM.MaxCascades=0
r.Shadow.MaxResolution=32
r.Shadow.RadiusThreshold=0.24
r.Shadow.DistanceScale=0.1

[PostProcessQuality@0]
r.DepthOfFieldQuality=0
r.RenderTargetPoolMin=200
r.Upscale.Quality=0

[TextureQuality@0]
r.MaxAnisotropy=0

[EffectsQuality@0]
r.TranslucencyLightingVolumeDim=1
r.RefractionQuality=0
r.SceneColorFormat=3

[FoliageQuality@0]
r.ParticleLightQuality=0

-----------------------------------------------------------------------------------------------
