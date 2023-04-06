# Unity SW Pack
> This extension provides a Unity development environment for VS Code.

## Preliminaries

* Install [.NET SDK](https://dotnet.microsoft.com/en-us/download) which includes runtime and .NET commands
* [Windows only] Restart Windows for changes to %PATH% to take effect
* [macOS only] To avoid "There was a problem loading some projects. Review the output for more information." download/stable/#download-mac) install the release

### Install Build Tools for Visual Studio (Windows only)

C# extensions are no longer shipped with the Microsoft Build Tools and must be installed manually.
* Download [Build Tools for Visual Studio 2022](https://visualstudio.microsoft.com/en/downloads/).
* Install the .NET Desktop Build Tools workload. No other components are required.

## Main function

* Code snippets for Unity are provided in Korean.
![CodeSnippets](gifs/01.gif)
* [ON/OFF] Shows Scene and Prefab referenced by Unity script.
![UsageScenePrefab](gifs/02.gif)
* [ON/OFF] Indicates Unity event function.
![UnityEventMessage](gifs/03.gif)
* [ON/OFF] Displays explanations of Unity messages on Hover.
![Hover](gifs/04.gif)
* [ON/OFF] Provide function signature change (type toggle) between void-IEnumerator.
![TypeToggle](gifs/05.gif)
* [ON/OFF] Checks for changes in .meta files and syncs them if there are any.
![metaFile](gifs/06.gif)
* [ON/OFF] Provides documentation navigation for Unity messages. (Shortcut: Shift+1)
* [ON/OFF] Unity SW Pack Dark Theme is provided.
* Handle `"omnisharp.useModernNet": false` of C# Extension for Unity development.

## Provided code snippet
* Game classes:
	* `MonoBehaviour`
	* `NetworkBehaviour`
	* `ScriptableObject`

* Editor Classes:
	* `Editor`

* Visual Studio Tools for Unity:
	* `Debug.Log()` (type _`log`_)
	* `Debug.LogError()` (type _`logError`_)
	* `Debug.LogWarning()` (type _`logWarning`_)

* MonoBehaviour Methods:
	* `Awake()`
	* `FixedUpdate()`
	* `LateUpdate()`
	* `OnAnimatorIK()`
	* `OnAnimatorMove()`
	* `OnApplicationFocus()`
	* `OnApplicationPause()`
	* `OnApplicationQuit()`
	* `OnAudioFilterRead()`
	* `OnBecameInvisible()`
	* `OnBecameVisible()`
	* `OnBeforeTransformParentChanged()`
	* `OnCanvasGroupChanged()`
	* `OnCollisionEnter()`
	* `OnCollisionEnter2D()`
	* `OnCollisionExit()`
	* `OnCollisionExit2D()`
	* `OnCollisionStay()`
	* `OnCollisionStay2D()`
	* `OnConnectedToServer()`
	* `OnControllerColliderHit()`
	* `OnDestroy()`
	* `OnDisable()`
	* `OnDisconnectedFromMasterServer()`
	* `OnDisconnectedFromServer()`
	* `OnDrawGizmos()`
	* `OnDrawGizmosSelected()`
	* `OnEnable()`
	* `OnFailedToConnect()`
	* `OnFailedToConnectToMasterServer()`
	* `OnGUI()`
	* `OnJointBreak()`
	* `OnJointBreak2D()`
	* `OnLevelWasLoaded()`
	* `OnMasterServerEvent()`
	* `OnMouseDown()`
	* `OnMouseDrag()`
	* `OnMouseEnter()`
	* `OnMouseExit()`
	* `OnMouseOver()`
	* `OnMouseUp()`
	* `OnMouseUpAsButton()`
	* `OnNetworkInstantiate()`
	* `OnParticleCollision()`
	* `OnParticleSystemStopped()`
	* `OnParticleTrigger()`
	* `OnParticleUpdateJobScheduled()`
	* `OnPlayerConnected()`
	* `OnPlayerDisconnected()`
	* `OnPostRender()`
	* `OnPreCull()`
	* `OnPreRender()`
	* `OnRectTransformDimensionsChange()`
	* `OnRectTransformRemoved()`
	* `OnRenderImage()`
	* `OnRenderObject()`
	* `OnSerializeNetworkView()`
	* `OnServerInitialized()`
	* `OnTransformChildrenChanged()`
	* `OnTransformParentChanged()`
	* `OnTriggerEnter()`
	* `OnTriggerEnter2D()`
	* `OnTriggerExit()`
	* `OnTriggerExit2D()`
	* `OnTriggerStay()`
	* `OnTriggerStay2D()`
	* `OnValidate()`
	* `OnWillRenderObject()`
	* `Reset()`
	* `Start()`
	* `Update()`
