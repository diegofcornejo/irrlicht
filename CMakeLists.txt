project (irrlicht)


set (INCLUDE_FILES
    "include/IEventReceiver.h"
	"include/ILogger.h"
	"include/IOSOperator.h"
	"include/IReferenceCounted.h"
	"include/IrrCompileConfig.h"
	"include/irrlicht.h"
	"include/IrrlichtDevice.h"
	"include/irrTypes.h"
	"include/ITimer.h"
	"include/Keycodes.h"
	"include/SIrrCreationParameters.h"
	"include/SKeyMap.h"
	"include/IRandomizer.h"
)
source_group (include FILES ${INCLUDE_FILES})

set (INCLUDE_FILES_VIDEO
	"include/EDriverTypes.h"
    "include/IGeometryCreator.h"
    "include/IGPUProgrammingServices.h"
    "include/IImage.h"
    "include/IImageLoader.h"
    "include/IMaterialRenderer.h"
    "include/IMaterialRendererServices.h"
    "include/IShaderConstantSetCallBack.h"
    "include/ITexture.h"
    "include/IVideoDriver.h"
    "include/IVideoModeList.h"
    "include/S3DVertex.h"
    "include/SColor.h"
    "include/SExposedVideoData.h"
    "include/SLight.h"
    "include/SMaterial.h"
    "include/SMaterialLayer.h"
	"include/EDriverFeatures.h"
	"include/EMaterialFlags.h"
)
source_group (include\\video FILES ${INCLUDE_FILES_VIDEO})

set (INCLUDE_FILES_CORE
	"include/aabbox3d.h"
	"include/coreutil.h"
	"include/dimension2d.h"
	"include/heapsort.h"
	"include/irrAllocator.h"
	"include/irrArray.h"
	"include/irrList.h"
	"include/irrMap.h"
	"include/irrMath.h"
    "include/irrString.h"
    "include/line2d.h"
    "include/line3d.h"
    "include/matrix4.h"
    "include/plane3d.h"
    "include/position2d.h"
    "include/quaternion.h"
    "include/rect.h"
    "include/triangle3d.h"
    "include/vector2d.h"
    "include/vector3d.h"
)
source_group (include\\core FILES ${INCLUDE_FILES_CORE})

set (INCLUDE_FILES_IO
	"include/EAttributes.h"
    "include/IAttributeExchangingObject.h"
    "include/IAttributes.h"
    "include/IFileList.h"
    "include/IFileSystem.h"
    "include/IReadFile.h"
    "include/irrXML.h"
    "include/IWriteFile.h"
    "include/IXMLReader.h"
    "include/IXMLWriter.h"
    "include/path.h"
)
source_group (include\\io FILES ${INCLUDE_FILES_IO})

set (INCLUDE_FILES_SCENE
	"include/CDynamicMeshBuffer.h"
    "include/CIndexBuffer.h"
    "include/CMeshBuffer.h"
    "include/CVertexBuffer.h"
    "include/ECullingTypes.h"
    "include/EDebugSceneTypes.h"
    "include/EMeshWriterEnums.h"
    "include/EPrimitiveTypes.h"
    "include/ESceneNodeAnimatorTypes.h"
    "include/ESceneNodeTypes.h"
    "include/IAnimatedMesh.h"
    "include/IAnimatedMeshMD2.h"
    "include/IAnimatedMeshSceneNode.h"
    "include/IBillboardSceneNode.h"
    "include/ICameraSceneNode.h"
    "include/IDummyTransformationSceneNode.h"
    "include/ILightSceneNode.h"
    "include/IMesh.h"
    "include/IMeshBuffer.h"
    "include/IMeshCache.h"
    "include/IMeshLoader.h"
    "include/IMeshManipulator.h"
    "include/IMeshSceneNode.h"
    "include/IMeshWriter.h"
    "include/IMetaTriangleSelector.h"
    "include/IParticleAffector.h"
    "include/IParticleAnimatedMeshSceneNodeEmitter.h"
    "include/IParticleAttractionAffector.h"
    "include/IParticleBoxEmitter.h"
    "include/IParticleCylinderEmitter.h"
    "include/IParticleEmitter.h"
    "include/IParticleFadeOutAffector.h"
    "include/IParticleGravityAffector.h"
    "include/IParticleMeshEmitter.h"
    "include/IParticleRingEmitter.h"
    "include/IParticleRotationAffector.h"
    "include/IParticleSphereEmitter.h"
    "include/IParticleSystemSceneNode.h"
    "include/IQ3LevelMesh.h"
    "include/IQ3Shader.h"
    "include/ISceneCollisionManager.h"
    "include/ISceneManager.h"
    "include/ISceneNode.h"
    "include/ISceneNodeAnimator.h"
    "include/ISceneNodeAnimatorCameraFPS.h"
    "include/ISceneNodeAnimatorCameraMaya.h"
    "include/ISceneNodeAnimatorCollisionResponse.h"
    "include/ISceneNodeAnimatorFactory.h"
    "include/ISceneNodeFactory.h"
    "include/IShadowVolumeSceneNode.h"
    "include/ISkinnedMesh.h"
    "include/ITerrainSceneNode.h"
    "include/ITextSceneNode.h"
    "include/ITriangleSelector.h"
    "include/IVolumeLightSceneNode.h"
    "include/SAnimatedMesh.h"
    "include/SceneParameters.h"
    "include/SMesh.h"
    "include/SMeshBuffer.h"
    "include/SMeshBufferLightMap.h"
    "include/SMeshBufferTangents.h"
    "include/SParticle.h"
    "include/SSkinMeshBuffer.h"
    "include/SViewFrustum.h"
	"include/IAnimatedMeshMD3.h"
	"include/ISceneLoader.h"
)
source_group (include\\scene FILES ${INCLUDE_FILES_SCENE})

set (INCLUDE_FILES_GUI
	"include/EGUIAlignment.h"
    "include/EGUIElementTypes.h"
    "include/EMessageBoxFlags.h"
    "include/ICursorControl.h"
    "include/IGUIButton.h"
    "include/IGUICheckBox.h"
    "include/IGUIComboBox.h"
    "include/IGUIContextMenu.h"
    "include/IGUIEditBox.h"
    "include/IGUIElement.h"
    "include/IGUIElementFactory.h"
    "include/IGUIEnvironment.h"
    "include/IGUIFileOpenDialog.h"
    "include/IGUIFont.h"
    "include/IGUIImage.h"
    "include/IGUIImageList.h"
    "include/IGUIInOutFader.h"
    "include/IGUIListBox.h"
    "include/IGUIMeshViewer.h"
    "include/IGUIScrollBar.h"
    "include/IGUISkin.h"
    "include/IGUISpinBox.h"
    "include/IGUISpriteBank.h"
    "include/IGUIStaticText.h"
    "include/IGUITabControl.h"
    "include/IGUIToolbar.h"
    "include/IGUITreeView.h"
    "include/IGUIWindow.h"
)
source_group (include\\gui FILES ${INCLUDE_FILES_GUI})

set (INCLUDE_FILES
	${INCLUDE_FILES}
	${INCLUDE_FILES_VIDEO}
	${INCLUDE_FILES_CORE}
	${INCLUDE_FILES_IO}
	${INCLUDE_FILES_SCENE}
	${INCLUDE_FILES_GUI}
)


set (SRC_FILES_SCENE
	"src/CDefaultSceneNodeAnimatorFactory.h"
    "src/CDefaultSceneNodeFactory.h"
    "src/CGeometryCreator.h"
    "src/CMeshCache.h"
    "src/CMeshManipulator.h"
    "src/CSceneManager.h"
    "src/Octree.h"
	"src/CDefaultSceneNodeAnimatorFactory.cpp"
	"src/CDefaultSceneNodeFactory.cpp"
	"src/CGeometryCreator.cpp"
	"src/CMeshCache.cpp"
	"src/CMeshManipulator.cpp"
	"src/CSceneManager.cpp"
)
source_group (src\\scene FILES ${SRC_FILES_SCENE})

set (SRC_FILES_SCENE_LOADERS
	"src/C3DSMeshFileLoader.h"
    "src/CAnimatedMeshHalfLife.h"
    "src/CAnimatedMeshMD2.h"
    "src/CAnimatedMeshMD3.h"
    "src/CB3DMeshFileLoader.h"
    "src/CBSPMeshFileLoader.h"
    "src/CColladaFileLoader.h"
    "src/CCSMLoader.h"
    "src/CDMFLoader.h"
    "src/CIrrMeshFileLoader.h"
    "src/CLMTSMeshFileLoader.h"
    "src/CLWOMeshFileLoader.h"
    "src/CMD2MeshFileLoader.h"
    "src/CMD3MeshFileLoader.h"
    "src/CMS3DMeshFileLoader.h"
    "src/CMY3DHelper.h"
    "src/CMY3DMeshFileLoader.h"
    "src/COBJMeshFileLoader.h"
    "src/COCTLoader.h"
    "src/COgreMeshFileLoader.h"
    "src/CPLYMeshFileLoader.h"
    "src/CQ3LevelMesh.h"
    "src/CSkinnedMesh.h"
    "src/CSTLMeshFileLoader.h"
    "src/CXMeshFileLoader.h"
    "src/dmfsupport.h"
	"src/CSceneLoaderIrr.h"
	"src/CSMFMeshFileLoader.h"
	"src/C3DSMeshFileLoader.cpp"
	"src/CAnimatedMeshHalfLife.cpp"
	"src/CAnimatedMeshMD2.cpp"
	"src/CAnimatedMeshMD3.cpp"
	"src/CB3DMeshFileLoader.cpp"
	"src/CBSPMeshFileLoader.cpp"
	"src/CColladaFileLoader.cpp"
	"src/CCSMLoader.cpp"
	"src/CDMFLoader.cpp"
	"src/CIrrMeshFileLoader.cpp"
	"src/CLMTSMeshFileLoader.cpp"
	"src/CLWOMeshFileLoader.cpp"
	"src/CMD2MeshFileLoader.cpp"
	"src/CMD3MeshFileLoader.cpp"
	"src/CMS3DMeshFileLoader.cpp"
	"src/CMY3DMeshFileLoader.cpp"
	"src/COBJMeshFileLoader.cpp"
	"src/COCTLoader.cpp"
	"src/COgreMeshFileLoader.cpp"
	"src/CPLYMeshFileLoader.cpp"
	"src/CQ3LevelMesh.cpp"
	"src/CSkinnedMesh.cpp"
	"src/CSTLMeshFileLoader.cpp"
	"src/CXMeshFileLoader.cpp"
	"src/CSceneLoaderIrr.cpp"
	"src/CSMFMeshFileLoader.cpp"
)
source_group (src\\scene\\loaders FILES ${SRC_FILES_SCENE_LOADERS})

set (SRC_FILES_SCENE_SCENENODES
	"src/CAnimatedMeshSceneNode.h"
    "src/CBillboardSceneNode.h"
    "src/CBoneSceneNode.h"
    "src/CCameraSceneNode.h"
    "src/CCubeSceneNode.h"
    "src/CDummyTransformationSceneNode.h"
    "src/CEmptySceneNode.h"
    "src/CLightSceneNode.h"
    "src/CMeshSceneNode.h"
    "src/COctreeSceneNode.h"
    "src/CQuake3ShaderSceneNode.h"
    "src/CShadowVolumeSceneNode.h"
    "src/CSkyBoxSceneNode.h"
    "src/CSkyDomeSceneNode.h"
    "src/CSphereSceneNode.h"
    "src/CTerrainSceneNode.h"
    "src/CTextSceneNode.h"
    "src/CVolumeLightSceneNode.h"
    "src/CWaterSurfaceSceneNode.h"
	"src/CAnimatedMeshSceneNode.cpp"
	"src/CBillboardSceneNode.cpp"
	"src/CBoneSceneNode.cpp"
	"src/CCameraSceneNode.cpp"
	"src/CCubeSceneNode.cpp"
	"src/CDummyTransformationSceneNode.cpp"
	"src/CEmptySceneNode.cpp"
	"src/CLightSceneNode.cpp"
	"src/CMeshSceneNode.cpp"
	"src/COctreeSceneNode.cpp"
	"src/CQuake3ShaderSceneNode.cpp"
	"src/CShadowVolumeSceneNode.cpp"
	"src/CSkyBoxSceneNode.cpp"
	"src/CSkyDomeSceneNode.cpp"
	"src/CSphereSceneNode.cpp"
	"src/CTerrainSceneNode.cpp"
	"src/CTextSceneNode.cpp"
	"src/CVolumeLightSceneNode.cpp"
	"src/CWaterSurfaceSceneNode.cpp"
)
source_group (src\\scene\\sceneNodes FILES ${SRC_FILES_SCENE_SCENENODES})

set (SRC_FILES_SCENE_PARTICLESYSTEM
	"src/CParticleAnimatedMeshSceneNodeEmitter.h"
    "src/CParticleAttractionAffector.h"
    "src/CParticleBoxEmitter.h"
    "src/CParticleCylinderEmitter.h"
    "src/CParticleFadeOutAffector.h"
    "src/CParticleGravityAffector.h"
    "src/CParticleMeshEmitter.h"
    "src/CParticlePointEmitter.h"
    "src/CParticleRingEmitter.h"
    "src/CParticleRotationAffector.h"
    "src/CParticleScaleAffector.h"
    "src/CParticleSphereEmitter.h"
    "src/CParticleSystemSceneNode.h"
	"src/CParticleAnimatedMeshSceneNodeEmitter.cpp"
	"src/CParticleAttractionAffector.cpp"
	"src/CParticleBoxEmitter.cpp"
	"src/CParticleCylinderEmitter.cpp"
	"src/CParticleFadeOutAffector.cpp"
	"src/CParticleGravityAffector.cpp"
	"src/CParticleMeshEmitter.cpp"
	"src/CParticlePointEmitter.cpp"
	"src/CParticleRingEmitter.cpp"
	"src/CParticleRotationAffector.cpp"
	"src/CParticleScaleAffector.cpp"
	"src/CParticleSphereEmitter.cpp"
	"src/CParticleSystemSceneNode.cpp"
)
source_group (src\\scene\\particleSystem FILES ${SRC_FILES_SCENE_PARTICLESYSTEM})

set (SRC_FILES_SCENE_COLLISION
	"src/CMetaTriangleSelector.h"
    "src/COctreeTriangleSelector.h"
    "src/CSceneCollisionManager.h"
    "src/CTerrainTriangleSelector.h"
    "src/CTriangleBBSelector.h"
    "src/CTriangleSelector.h"
	"src/CMetaTriangleSelector.cpp"
	"src/COctreeTriangleSelector.cpp"
	"src/CSceneCollisionManager.cpp"
	"src/CTerrainTriangleSelector.cpp"
	"src/CTriangleBBSelector.cpp"
	"src/CTriangleSelector.cpp"
)
source_group (src\\scene\\collision FILES ${SRC_FILES_SCENE_COLLISION})

set (SRC_FILES_SCENE_ANIMATORS
	"src/CSceneNodeAnimatorCameraFPS.h"
    "src/CSceneNodeAnimatorCameraMaya.h"
    "src/CSceneNodeAnimatorCollisionResponse.h"
    "src/CSceneNodeAnimatorDelete.h"
    "src/CSceneNodeAnimatorFlyCircle.h"
    "src/CSceneNodeAnimatorFlyStraight.h"
    "src/CSceneNodeAnimatorFollowSpline.h"
    "src/CSceneNodeAnimatorRotation.h"
    "src/CSceneNodeAnimatorTexture.h"
	"src/CSceneNodeAnimatorCameraFPS.cpp"
	"src/CSceneNodeAnimatorCameraMaya.cpp"
	"src/CSceneNodeAnimatorCollisionResponse.cpp"
	"src/CSceneNodeAnimatorDelete.cpp"
	"src/CSceneNodeAnimatorFlyCircle.cpp"
	"src/CSceneNodeAnimatorFlyStraight.cpp"
	"src/CSceneNodeAnimatorFollowSpline.cpp"
	"src/CSceneNodeAnimatorRotation.cpp"
	"src/CSceneNodeAnimatorTexture.cpp"
)
source_group (src\\scene\\animators FILES ${SRC_FILES_SCENE_ANIMATORS})

set (SRC_FILES_SCENE_WRITERS
	"src/CColladaMeshWriter.h"
    "src/CIrrMeshWriter.h"
    "src/COBJMeshWriter.h"
    "src/CPLYMeshWriter.h"
    "src/CSTLMeshWriter.h"
	"src/CColladaMeshWriter.cpp"
	"src/CIrrMeshWriter.cpp"
	"src/COBJMeshWriter.cpp"
	"src/CPLYMeshWriter.cpp"
	"src/CSTLMeshWriter.cpp"
)
source_group (src\\scene\\writers FILES ${SRC_FILES_SCENE_WRITERS})

set (SRC_FILES_SCENE
	${SRC_FILES_SCENE}
	${SRC_FILES_SCENE_LOADERS}
	${SRC_FILES_SCENE_SCENENODES}
	${SRC_FILES_SCENE_PARTICLESYSTEM}
	${SRC_FILES_SCENE_COLLISION}
	${SRC_FILES_SCENE_ANIMATORS}
	${SRC_FILES_SCENE_WRITERS}
)


set (SRC_FILES_VIDEO
	"src/CVideoModeList.h"
	"src/CCgMaterialRenderer.h"
	"src/CVideoModeList.cpp"
	"src/CCgMaterialRenderer.cpp"
)
source_group (src\\video FILES ${SRC_FILES_VIDEO})

set (SRC_FILES_VIDEO_SOFTWARE
    "src/CSoftwareDriver.h"
    "src/CSoftwareTexture.h"
    "src/CTRTextureGouraud.h"
    "src/CZBuffer.h"
    "src/ITriangleRenderer.h"
    "src/IZBuffer.h"
    "src/S2DVertex.h"
	"src/CSoftwareDriver.cpp"
	"src/CSoftwareTexture.cpp"
	"src/CTRFlat.cpp"
	"src/CTRFlatWire.cpp"
	"src/CTRGouraud.cpp"
	"src/CTRGouraudWire.cpp"
	"src/CTRTextureFlat.cpp"
	"src/CTRTextureFlatWire.cpp"
	"src/CTRTextureGouraud.cpp"
	"src/CTRTextureGouraudAdd.cpp"
	"src/CTRTextureGouraudNoZ.cpp"
	"src/CTRTextureGouraudWire.cpp"
	"src/CZBuffer.cpp"
)
source_group (src\\video\\Software FILES ${SRC_FILES_VIDEO_SOFTWARE})

set (SRC_FILES_VIDEO_OPENGL
    "src/COpenGLDriver.h"
    "src/COpenGLExtensionHandler.h"
    "src/COpenGLMaterialRenderer.h"
    "src/COpenGLNormalMapRenderer.h"
    "src/COpenGLParallaxMapRenderer.h"
    "src/COpenGLShaderMaterialRenderer.h"
    "src/COpenGLSLMaterialRenderer.h"
    "src/COpenGLTexture.h"
    "src/glext.h"
    "src/wglext.h"
	"src/COpenGLCgMaterialRenderer.h"
	"src/COpenGLDriver.cpp"
	"src/COpenGLExtensionHandler.cpp"
	"src/COpenGLNormalMapRenderer.cpp"
	"src/COpenGLParallaxMapRenderer.cpp"
	"src/COpenGLShaderMaterialRenderer.cpp"
	"src/COpenGLSLMaterialRenderer.cpp"
	"src/COpenGLTexture.cpp"
	"src/COpenGLCgMaterialRenderer.cpp"
)
source_group (src\\video\\OpenGL FILES ${SRC_FILES_VIDEO_OPENGL})

set (SRC_FILES_VIDEO_DIRECT3D8
    "src/CD3D8Driver.h"
    "src/CD3D8MaterialRenderer.h"
    "src/CD3D8NormalMapRenderer.h"
    "src/CD3D8ParallaxMapRenderer.h"
    "src/CD3D8ShaderMaterialRenderer.h"
    "src/CD3D8Texture.h"
	"src/CD3D8Driver.cpp"
	"src/CD3D8NormalMapRenderer.cpp"
	"src/CD3D8ParallaxMapRenderer.cpp"
	"src/CD3D8ShaderMaterialRenderer.cpp"
	"src/CD3D8Texture.cpp"
)
source_group (src\\video\\Direct3D8 FILES ${SRC_FILES_VIDEO_DIRECT3D8})

set (SRC_FILES_VIDEO_NULL
    "src/CColorConverter.h"
    "src/CFPSCounter.h"
    "src/CImage.h"
    "src/CNullDriver.h"
    "src/IImagePresenter.h"
	"src/CColorConverter.cpp"
	"src/CFPSCounter.cpp"
	"src/CImage.cpp"
	"src/CNullDriver.cpp"
)
source_group (src\\video\\Null FILES ${SRC_FILES_VIDEO_NULL})

set (SRC_FILES_VIDEO_NULL_WRITER
    "src/CImageWriterBMP.h"
    "src/CImageWriterJPG.h"
    "src/CImageWriterPCX.h"
    "src/CImageWriterPNG.h"
    "src/CImageWriterPPM.h"
    "src/CImageWriterPSD.h"
    "src/CImageWriterTGA.h"
	"src/CImageWriterBMP.cpp"
	"src/CImageWriterJPG.cpp"
	"src/CImageWriterPCX.cpp"
	"src/CImageWriterPNG.cpp"
	"src/CImageWriterPPM.cpp"
	"src/CImageWriterPSD.cpp"
	"src/CImageWriterTGA.cpp"
)
source_group (src\\video\\Null\\Writer FILES ${SRC_FILES_VIDEO_NULL_WRITER})

set (SRC_FILES_VIDEO_NULL_LOADER
    "src/CImageLoaderBMP.h"
    "src/CImageLoaderDDS.h"
    "src/CImageLoaderJPG.h"
    "src/CImageLoaderPCX.h"
    "src/CImageLoaderPNG.h"
    "src/CImageLoaderPPM.h"
    "src/CImageLoaderPSD.h"
    "src/CImageLoaderRGB.h"
    "src/CImageLoaderTGA.h"
    "src/CImageLoaderWAL.h"
	"src/CImageLoaderBMP.cpp"
	"src/CImageLoaderDDS.cpp"
	"src/CImageLoaderJPG.cpp"
	"src/CImageLoaderPCX.cpp"
	"src/CImageLoaderPNG.cpp"
	"src/CImageLoaderPPM.cpp"
	"src/CImageLoaderPSD.cpp"
	"src/CImageLoaderRGB.cpp"
	"src/CImageLoaderTGA.cpp"
	"src/CImageLoaderWAL.cpp"
)
source_group (src\\video\\Null\\Loader FILES ${SRC_FILES_VIDEO_NULL_LOADER})

set (SRC_FILES_VIDEO_DIRECT3D9
    "src/CD3D9Driver.h"
    "src/CD3D9HLSLMaterialRenderer.h"
    "src/CD3D9MaterialRenderer.h"
    "src/CD3D9NormalMapRenderer.h"
    "src/CD3D9ParallaxMapRenderer.h"
    "src/CD3D9ShaderMaterialRenderer.h"
    "src/CD3D9Texture.h"
	"src/CD3D9CgMaterialRenderer.h"
	"src/CD3D9Driver.cpp"
	"src/CD3D9HLSLMaterialRenderer.cpp"
	"src/CD3D9NormalMapRenderer.cpp"
	"src/CD3D9ParallaxMapRenderer.cpp"
	"src/CD3D9ShaderMaterialRenderer.cpp"
	"src/CD3D9Texture.cpp"
	"src/CD3D9CgMaterialRenderer.cpp"
)
source_group (src\\video\\Direct3D9 FILES ${SRC_FILES_VIDEO_DIRECT3D9})

set (SRC_FILES_VIDEO_BURNINGVIDEO
    "src/CDepthBuffer.h"
    "src/CSoftware2MaterialRenderer.h"
    "src/CSoftwareDriver2.h"
    "src/CSoftwareTexture2.h"
    "src/IBurningShader.h"
    "src/IDepthBuffer.h"
    "src/S4DVertex.h"
    "src/SoftwareDriver2_compile_config.h"
    "src/SoftwareDriver2_helper.h"
	"src/CBurningShader_Raster_Reference.cpp"
	"src/CDepthBuffer.cpp"
	"src/CSoftwareDriver2.cpp"
	"src/CSoftwareTexture2.cpp"
	"src/CTRGouraud2.cpp"
	"src/CTRGouraudAlpha2.cpp"
	"src/CTRGouraudAlphaNoZ2.cpp"
	"src/CTRNormalMap.cpp"
	"src/CTRStencilShadow.cpp"
	"src/CTRTextureBlend.cpp"
	"src/CTRTextureDetailMap2.cpp"
	"src/CTRTextureGouraud2.cpp"
	"src/CTRTextureGouraudAdd2.cpp"
	"src/CTRTextureGouraudAddNoZ2.cpp"
	"src/CTRTextureGouraudAlpha.cpp"
	"src/CTRTextureGouraudAlphaNoZ.cpp"
	"src/CTRTextureGouraudNoZ2.cpp"
	"src/CTRTextureGouraudVertexAlpha2.cpp"
	"src/CTRTextureLightMap2_Add.cpp"
	"src/CTRTextureLightMap2_M1.cpp"
	"src/CTRTextureLightMap2_M2.cpp"
	"src/CTRTextureLightMap2_M4.cpp"
	"src/CTRTextureLightMapGouraud2_M4.cpp"
	"src/CTRTextureWire2.cpp"
	"src/IBurningShader.cpp"
)
source_group (src\\video\\BurningVideo FILES ${SRC_FILES_VIDEO_BURNINGVIDEO})

set (SRC_FILES_VIDEO
	${SRC_FILES_VIDEO}
	${SRC_FILES_VIDEO_SOFTWARE}
	${SRC_FILES_VIDEO_OPENGL}
	${SRC_FILES_VIDEO_DIRECT3D8}
	${SRC_FILES_VIDEO_NULL}
	${SRC_FILES_VIDEO_NULL_WRITER}
	${SRC_FILES_VIDEO_NULL_LOADER}
	${SRC_FILES_VIDEO_DIRECT3D9}
	${SRC_FILES_VIDEO_BURNINGVIDEO}
)


set (SRC_FILES_IRR
	"src/CLogger.h"
    "src/COSOperator.h"
    "src/CTimer.h"
    "src/os.h"
	"src/CLogger.cpp"
	"src/COSOperator.cpp"
	"src/Irrlicht.cpp"
	"src/os.cpp"
)
source_group (src\\irr FILES ${SRC_FILES_IRR})

set (SRC_FILES_IRR_EXTERN
    "src/lzma/LzmaDec.h"
	"src/lzma/LzmaDec.c"
    "src/lzma/Types.h"
)
source_group (src\\irr\\extern FILES ${SRC_FILES_IRR_EXTERN})

set (SRC_FILES_IRR_EXTERN_ZLIB
    "src/zlib/crc32.h"
    "src/zlib/deflate.h"
    "src/zlib/inffast.h"
    "src/zlib/inffixed.h"
    "src/zlib/inftrees.h"
    "src/zlib/trees.h"
    "src/zlib/zconf.h"
    "src/zlib/zlib.h"
    "src/zlib/zutil.h"
	"src/zlib/adler32.c"
	"src/zlib/compress.c"
	"src/zlib/crc32.c"
	"src/zlib/deflate.c"
	"src/zlib/inffast.c"
	"src/zlib/inflate.c"
	"src/zlib/inftrees.c"
	"src/zlib/trees.c"
	"src/zlib/uncompr.c"
	"src/zlib/zutil.c"
)
source_group (src\\irr\\extern\\zlib FILES ${SRC_FILES_IRR_EXTERN_ZLIB})

set (SRC_FILES_IRR_EXTERN_JPEGLIB
    "src/jpeglib/cderror.h"
    "src/jpeglib/jconfig.h"
    "src/jpeglib/jdct.h"
    "src/jpeglib/jerror.h"
    "src/jpeglib/jinclude.h"
    "src/jpeglib/jmemsys.h"
    "src/jpeglib/jmorecfg.h"
    "src/jpeglib/jpegint.h"
    "src/jpeglib/jpeglib.h"
    "src/jpeglib/jversion.h"
	"src/jpeglib/jaricom.c"
	"src/jpeglib/jcapimin.c"
	"src/jpeglib/jcapistd.c"
	"src/jpeglib/jcarith.c"
	"src/jpeglib/jccoefct.c"
	"src/jpeglib/jccolor.c"
	"src/jpeglib/jcdctmgr.c"
	"src/jpeglib/jchuff.c"
	"src/jpeglib/jcinit.c"
	"src/jpeglib/jcmainct.c"
	"src/jpeglib/jcmarker.c"
	"src/jpeglib/jcmaster.c"
	"src/jpeglib/jcomapi.c"
	"src/jpeglib/jcparam.c"
	"src/jpeglib/jcprepct.c"
	"src/jpeglib/jcsample.c"
	"src/jpeglib/jctrans.c"
	"src/jpeglib/jdapimin.c"
	"src/jpeglib/jdapistd.c"
	"src/jpeglib/jdarith.c"
	"src/jpeglib/jdatadst.c"
	"src/jpeglib/jdatasrc.c"
	"src/jpeglib/jdcoefct.c"
	"src/jpeglib/jdcolor.c"
	"src/jpeglib/jddctmgr.c"
	"src/jpeglib/jdhuff.c"
	"src/jpeglib/jdinput.c"
	"src/jpeglib/jdmainct.c"
	"src/jpeglib/jdmarker.c"
	"src/jpeglib/jdmaster.c"
	"src/jpeglib/jdmerge.c"
	"src/jpeglib/jdpostct.c"
	"src/jpeglib/jdsample.c"
	"src/jpeglib/jdtrans.c"
	"src/jpeglib/jerror.c"
	"src/jpeglib/jfdctflt.c"
	"src/jpeglib/jfdctfst.c"
	"src/jpeglib/jfdctint.c"
	"src/jpeglib/jidctflt.c"
	"src/jpeglib/jidctfst.c"
	"src/jpeglib/jidctint.c"
	"src/jpeglib/jmemmgr.c"
	"src/jpeglib/jmemnobs.c"
	"src/jpeglib/jquant1.c"
	"src/jpeglib/jquant2.c"
	"src/jpeglib/jutils.c"
)
source_group (src\\irr\\extern\\jpeglib FILES ${SRC_FILES_IRR_EXTERN_JPEGLIB})

set (SRC_FILES_IRR_EXTERN_LIBPNG
    "src/libpng/png.h"
    "src/libpng/pngconf.h"
	"src/libpng/png.c"
	"src/libpng/pngerror.c"
	"src/libpng/pngget.c"
	"src/libpng/pngmem.c"
	"src/libpng/pngpread.c"
	"src/libpng/pngread.c"
	"src/libpng/pngrio.c"
	"src/libpng/pngrtran.c"
	"src/libpng/pngrutil.c"
	"src/libpng/pngset.c"
	"src/libpng/pngtrans.c"
	"src/libpng/pngwio.c"
	"src/libpng/pngwrite.c"
	"src/libpng/pngwtran.c"
	"src/libpng/pngwutil.c"
)
source_group (src\\irr\\extern\\libpng FILES ${SRC_FILES_IRR_EXTERN_LIBPNG})

set (SRC_FILES_IRR_EXTERN_AESGLADMAN
    "src/aesGladman/aes.h"
    "src/aesGladman/aesopt.h"
    "src/aesGladman/fileenc.h"
    "src/aesGladman/hmac.h"
    "src/aesGladman/prng.h"
    "src/aesGladman/pwd2key.h"
    "src/aesGladman/sha1.h"
    "src/aesGladman/sha2.h"
	"src/aesGladman/aescrypt.cpp"
	"src/aesGladman/aeskey.cpp"
	"src/aesGladman/aestab.cpp"
	"src/aesGladman/fileenc.cpp"
	"src/aesGladman/hmac.cpp"
	"src/aesGladman/prng.cpp"
	"src/aesGladman/pwd2key.cpp"
	"src/aesGladman/sha1.cpp"
	"src/aesGladman/sha2.cpp"
)
source_group (src\\irr\\extern\\aesGladman FILES ${SRC_FILES_IRR_EXTERN_AESGLADMAN})

set (SRC_FILES_IRR_EXTERN_BZIP2
    "src/bzip2/bzlib.h"
    "src/bzip2/bzlib_private.h"
	"src/bzip2/blocksort.c"
	"src/bzip2/bzcompress.c"
	"src/bzip2/bzlib.c"
	"src/bzip2/crctable.c"
	"src/bzip2/decompress.c"
	"src/bzip2/huffman.c"
	"src/bzip2/randtable.c"
)
source_group (src\\irr\\extern\\bzip2 FILES ${SRC_FILES_IRR_EXTERN_BZIP2})

set (SRC_FILES_IRR_DEVICE
    "src/CIrrDeviceConsole.h"
    "src/CIrrDeviceFB.h"
    "src/CIrrDeviceLinux.h"
    "src/CIrrDeviceSDL.h"
    "src/CIrrDeviceStub.h"
    "src/CIrrDeviceWin32.h"
    "src/CIrrDeviceWinCE.h"
	"src/CIrrDeviceConsole.cpp"
	"src/CIrrDeviceFB.cpp"
	"src/CIrrDeviceLinux.cpp"
	"src/CIrrDeviceSDL.cpp"
	"src/CIrrDeviceStub.cpp"
	"src/CIrrDeviceWin32.cpp"
	"src/CIrrDeviceWinCE.cpp"
)
source_group (src\\irr\\device FILES ${SRC_FILES_IRR_DEVICE})

set (SRC_FILES_IRR
	${SRC_FILES_IRR}
	${SRC_FILES_IRR_EXTERN}
	${SRC_FILES_IRR_EXTERN_ZLIB}
	${SRC_FILES_IRR_EXTERN_JPEGLIB}
	${SRC_FILES_IRR_EXTERN_LIBPNG}
	${SRC_FILES_IRR_EXTERN_AESGLADMAN}
	${SRC_FILES_IRR_EXTERN_BZIP2}
	${SRC_FILES_IRR_DEVICE}
)


set (SRC_FILES_IO
	"src/CAttributeImpl.h"
    "src/CAttributes.h"
    "src/CFileList.h"
    "src/CFileSystem.h"
    "src/CLimitReadFile.h"
    "src/CMemoryFile.h"
    "src/CMountPointReader.h"
    "src/CNPKReader.h"
    "src/CPakReader.h"
    "src/CReadFile.h"
    "src/CTarReader.h"
    "src/CWADReader.h"
    "src/CWriteFile.h"
    "src/CXMLReader.h"
    "src/CXMLReaderImpl.h"
    "src/CXMLWriter.h"
    "src/CZipReader.h"
    "src/IAttribute.h"
	"src/CAttributes.cpp"
	"src/CFileList.cpp"
	"src/CFileSystem.cpp"
	"src/CLimitReadFile.cpp"
	"src/CMemoryFile.cpp"
	"src/CMountPointReader.cpp"
	"src/CNPKReader.cpp"
	"src/CPakReader.cpp"
	"src/CReadFile.cpp"
	"src/CTarReader.cpp"
	"src/CWADReader.cpp"
	"src/CWriteFile.cpp"
	"src/CXMLReader.cpp"
	"src/CXMLWriter.cpp"
	"src/CZipReader.cpp"
	"src/irrXML.cpp"
)
source_group (src\\io FILES ${SRC_FILES_IO})


set (SRC_FILES_GUI
    "src/BuiltInFont.h"
    "src/CDefaultGUIElementFactory.h"
    "src/CGUIButton.h"
    "src/CGUICheckBox.h"
    "src/CGUIColorSelectDialog.h"
    "src/CGUIComboBox.h"
    "src/CGUIContextMenu.h"
    "src/CGUIEditBox.h"
    "src/CGUIEnvironment.h"
    "src/CGUIFileOpenDialog.h"
    "src/CGUIFont.h"
    "src/CGUIImage.h"
    "src/CGUIImageList.h"
    "src/CGUIInOutFader.h"
    "src/CGUIListBox.h"
    "src/CGUIMenu.h"
    "src/CGUIMeshViewer.h"
    "src/CGUIMessageBox.h"
    "src/CGUIModalScreen.h"
    "src/CGUIScrollBar.h"
    "src/CGUISkin.h"
    "src/CGUISpinBox.h"
    "src/CGUISpriteBank.h"
    "src/CGUIStaticText.h"
    "src/CGUITabControl.h"
    "src/CGUITable.h"
    "src/CGUIToolBar.h"
    "src/CGUITreeView.h"
    "src/CGUIWindow.h"
	"src/CDefaultGUIElementFactory.cpp"
	"src/CGUIButton.cpp"
	"src/CGUICheckBox.cpp"
	"src/CGUIColorSelectDialog.cpp"
	"src/CGUIComboBox.cpp"
	"src/CGUIContextMenu.cpp"
	"src/CGUIEditBox.cpp"
	"src/CGUIEnvironment.cpp"
	"src/CGUIFileOpenDialog.cpp"
	"src/CGUIFont.cpp"
	"src/CGUIImage.cpp"
	"src/CGUIImageList.cpp"
	"src/CGUIInOutFader.cpp"
	"src/CGUIListBox.cpp"
	"src/CGUIMenu.cpp"
	"src/CGUIMeshViewer.cpp"
	"src/CGUIMessageBox.cpp"
	"src/CGUIModalScreen.cpp"
	"src/CGUIScrollBar.cpp"
	"src/CGUISkin.cpp"
	"src/CGUISpinBox.cpp"
	"src/CGUISpriteBank.cpp"
	"src/CGUIStaticText.cpp"
	"src/CGUITabControl.cpp"
	"src/CGUITable.cpp"
	"src/CGUIToolBar.cpp"
	"src/CGUITreeView.cpp"
	"src/CGUIWindow.cpp"
)
source_group (src\\gui FILES ${SRC_FILES_GUI})


set (SRC_FILES
	${SRC_FILES_SCENE}
	${SRC_FILES_VIDEO}
	${SRC_FILES_IRR}
	${SRC_FILES_IO}
	${SRC_FILES_GUI}
)


include_directories ( include src/zlib src/jpeglib src/libpng )

add_definitions ("-D_IRR_STATIC_LIB_")

if (CMAKE_C_COMPILER MATCHES "cc")
	add_definitions ("-U__STRICT_ANSI__")
endif ()

if (WIN32)
	include_directories ( $ENV{DXSDK_DIR}/include )
	if (MSVC)
        add_definitions ("-DIRRLICHT_FAST_MATH")
	endif ()
endif ()

add_library (irrlicht STATIC ${INCLUDE_FILES} ${SRC_FILES})
