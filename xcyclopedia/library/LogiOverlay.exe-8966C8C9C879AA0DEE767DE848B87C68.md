
# LogiOverlay.exe 

* File Path: `C:\ProgramData\Logishrd\LogiOptions\Software\Current\LogiOverlay.exe`
* Description: Logi Overlay
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `8966C8C9C879AA0DEE767DE848B87C68`
SHA1 | `ECF3CAE5251C607CF5027E2902035FFE2C78666D`
SHA256 | `F52F9DB8F827B9A505FAF6608D89258D7B975BF66D78E455A5409EBB1F3547C1`
SHA384 | `F491B3FFB30A83CA4865D2D0E0DEE878C95F3DE2F52AB656656D524C40CFC2AC004C62C198BAAEF2278569822739F1F6`
SHA415 | `B535BCD075FF45E8D8BDC48D839CFC4B0C80D07B2F8DFD98A6EE40F39223DC49D3FDD11A13534320E11CE88F940D5F7A6E9CB9A50A728BDB1F1E609569E17146`
SSDEEP | `6144:Wj2orPqa3zvYHv4Y6RyAZ3S2wUNIpLrAKncoGOhvKOJYDRyAZ3S2CaF:jorPqa3zvYP/6Vd6MIrmoGOhKDVdE6`

## Runtime Data

### Usage (stdout):
```Batchfile
App.xaml.cs(45):OnStartup - App. Mutex 'LogiOverlay' created, launching UI
NamedPipeMgrToUi.cs(32):CreatePipeServer - [OVERLAY] [PIPEIPC] Creating Server Message Dispatcher
NamedPipeMgrToUi.cs(38):CreatePipeServer - [OVERLAY] [PIPEIPC] Creating PipeServer, pipeName=LogiOverlay{00000000-0000-0000-0000-000000000000-1}
NamedPipeMgrToUi.cs(138):PipeServer - [OVERLAY] [PIPEIPC] PipeServer thread waiting for connection, pipeName=LogiOverlay{00000000-0000-0000-0000-000000000000-1}
MainWindow.xaml.cs(32):.ctor - MainWindow.MainWindow() - Start
MainWindow.xaml.cs(390):RegisterGlobalInstanceEvent -  - Global Instance event event key: Global\LDeviceManagerGlobal-{00000000-0000-0000-0000-000000000000}
MainWindow.xaml.cs(392):RegisterGlobalInstanceEvent -  - Obtained EventWaitHandleSecurity: System.Security.AccessControl.EventWaitHandleSecurity
MainWindow.xaml.cs(395):RegisterGlobalInstanceEvent -  - Added EventWaitHandleAccessRule for Everyone
MainWindow.xaml.cs(397):RegisterGlobalInstanceEvent -  - EventWaitHandle result (createdNew=True): System.Threading.EventWaitHandle
MainWindow.xaml.cs(408):RegisterGlobalShutdownEvent - MainWindow. - Start
MainWindow.xaml.cs(413):RegisterGlobalShutdownEvent - MainWindow. - Global Shutdown event key: Global\LDeviceManagerGlobal-{00000000-0000-0000-0000-000000000000}
MainWindow.xaml.cs(416):RegisterGlobalShutdownEvent - MainWindow. - Obtained EventWaitHandleSecurity: System.Security.AccessControl.EventWaitHandleSecurity
MainWindow.xaml.cs(420):RegisterGlobalShutdownEvent - MainWindow. - Added EventWaitHandleAccessRule for Everyone
MainWindow.xaml.cs(423):RegisterGlobalShutdownEvent - MainWindow. - EventWaitHandle result (createdNew=True): System.Threading.EventWaitHandle
MainWindow.xaml.cs(426):RegisterGlobalShutdownEvent - MainWindow. - Registered thread pool wait handle callback (done)
MainScreen.xaml.cs(99):MainScreen_Loaded - MainScreen. - Start
MainScreen.xaml.cs(111):PositionOverlay - MainScreen. - Start - desired width: 0,0, process id: 0
MainScreen.xaml.cs(119):PositionOverlay - MainScreen. - desired width: 0,0 is less than 100px so we are collapsing all windows
ApplicationTable.cs(80):ReloadApplicationTable - ApplicationTable. - Start
DPIScreen.xaml.cs(84):DPIScreen_Loaded - DPIScreen. - Start
DPIScreen.xaml.cs(96):PositionOverlay - DPIScreen. - Start - desired width: 0,0, process id: 0
DPIScreen.xaml.cs(106):PositionOverlay - DPIScreen. - desired width: 0,0 is less than 100px so we are collapsing all windows
NotificationScreen.xaml.cs(85):NotificationScreen_Loaded - NotificationScreen. - Start
NotificationScreen.xaml.cs(97):PositionOverlay - NotificationScreen. - Start - desired width: 0,0, process id: 0
NotificationViewModel.cs(23):ClearOverlayState - NotificationViewModel. - Start force:False
BaseViewModel.cs(166):IsFadeoutTimerStopRequested - BaseViewModel. - Start
BaseViewModel.cs(151):StopFadeoutTimer - BaseViewModel. - Start
BaseViewModel.cs(221):HideOverlayWindow - BaseViewModel.HideOverlayWindowWindow() - Start
BaseViewModel.cs(228):RaiseSetWindowSize - BaseViewModel. - Start - overlay size: 0,0, process id: 0, hide during render: True
NotificationScreen.xaml.cs(105):PositionOverlay - NotificationScreen. - desired width: 0,0 is less than 100px so we are collapsing all windows
MainWindow.xaml.cs(54):.ctor - MainWindow.MainWindow() - Initialized
App.xaml.cs(113):RegisterAllPlugins -  called
E:\BuildAgent\work\b6ea7879e2d24522\Source\Trava\TravaOverlay\App.xaml.cs(180):UnhandledException_Handler - App. exception: Could not find a part of the path 'C:\ProgramData\Logishrd\LogiOptions\Software\Current\Plugins'.
System.IO.DirectoryNotFoundException: Could not find a part of the path 'C:\ProgramData\Logishrd\LogiOptions\Software\Current\Plugins'.
   at System.IO.__Error.WinIOError(Int32 errorCode, String maybeFullPath)
   at System.IO.FileSystemEnumerableIterator`1.CommonInit()
   at System.IO.FileSystemEnumerableIterator`1..ctor(String path, String originalUserPath, String searchPattern, SearchOption searchOption, SearchResultHandler`1 resultHandler, Boolean checkHost)
   at System.IO.Directory.GetFileSystemEntries(String path, String searchPattern, SearchOption searchOption)
   at LogiOverlay.App.GetPluginPaths()
   at LogiOverlay.App.RegisterAllPlugins()
   at LogiOverlay.App.OnStartup(StartupEventArgs e)
   at System.Windows.Application.<.ctor>b__1_0(Object unused)
   at System.Windows.Threading.ExceptionWrapper.InternalRealCall(Delegate callback, Object args, Int32 numArgs)
   at System.Windows.Threading.ExceptionWrapper.TryCatchWhen(Object source, Delegate callback, Object args, Int32 numArgs, Delegate catchHandler)
   at System.Windows.Threading.DispatcherOperation.InvokeImpl()
   at System.Threading.ExecutionContext.RunInternal(ExecutionContext executionContext, ContextCallback callback, Object state, Boolean preserveSyncCtx)
   at System.Threading.ExecutionContext.Run(ExecutionContext executionContext, ContextCallback callback, Object state, Boolean preserveSyncCtx)
   at System.Threading.ExecutionContext.Run(ExecutionContext executionContext, ContextCallback callback, Object state)
   at MS.Internal.CulturePreservingExecutionContext.Run(CulturePreservingExecutionContext executionContext, ContextCallback callback, Object state)
   at System.Windows.Threading.DispatcherOperation.Invoke()
   at System.Windows.Threading.Dispatcher.ProcessQueue()
   at System.Windows.Threading.Dispatcher.WndProcHook(IntPtr hwnd, Int32 msg, IntPtr wParam, IntPtr lParam, Boolean& handled)
   at MS.Win32.HwndWrapper.WndProc(IntPtr hwnd, Int32 msg, IntPtr wParam, IntPtr lParam, Boolean& handled)
   at MS.Win32.HwndSubclass.DispatcherCallbackOperation(Object o)
   at System.Windows.Threading.ExceptionWrapper.InternalRealCall(Delegate callback, Object args, Int32 numArgs)
   at System.Windows.Threading.ExceptionWrapper.TryCatchWhen(Object source, Delegate callback, Object args, Int32 numArgs, Delegate catchHandler)
   at System.Windows.Threading.Dispatcher.LegacyInvokeImpl(DispatcherPriority priority, TimeSpan timeout, Delegate method, Object args, Int32 numArgs)
   at MS.Win32.HwndSubclass.SubclassWndProc(IntPtr hwnd, Int32 msg, IntPtr wParam, IntPtr lParam)
   at MS.Win32.UnsafeNativeMethods.DispatchMessage(MSG& msg)
   at System.Windows.Threading.Dispatcher.PushFrameImpl(DispatcherFrame frame)
   at System.Windows.Application.RunDispatcher(Object ignore)
   at System.Windows.Application.RunInternal(Window window)
   at LogiOverlay.App.Main()

```

### Usage (stderr):
```Batchfile

Unhandled Exception: System.IO.DirectoryNotFoundException: Could not find a part of the path 'C:\ProgramData\Logishrd\LogiOptions\Software\Current\Plugins'.
   at System.IO.__Error.WinIOError(Int32 errorCode, String maybeFullPath)
   at System.IO.FileSystemEnumerableIterator`1.CommonInit()
   at System.IO.FileSystemEnumerableIterator`1..ctor(String path, String originalUserPath, String searchPattern, SearchOption searchOption, SearchResultHandler`1 resultHandler, Boolean checkHost)
   at System.IO.Directory.GetFileSystemEntries(String path, String searchPattern, SearchOption searchOption)
   at LogiOverlay.App.GetPluginPaths()
   at LogiOverlay.App.RegisterAllPlugins()
   at LogiOverlay.App.OnStartup(StartupEventArgs e)
   at System.Windows.Application.<.ctor>b__1_0(Object unused)
   at System.Windows.Threading.ExceptionWrapper.InternalRealCall(Delegate callback, Object args, Int32 numArgs)
   at System.Windows.Threading.ExceptionWrapper.TryCatchWhen(Object source, Delegate callback, Object args, Int32 numArgs, Delegate catchHandler)
   at System.Windows.Threading.DispatcherOperation.InvokeImpl()
   at System.Threading.ExecutionContext.RunInternal(ExecutionContext executionContext, ContextCallback callback, Object state, Boolean preserveSyncCtx)
   at System.Threading.ExecutionContext.Run(ExecutionContext executionContext, ContextCallback callback, Object state, Boolean preserveSyncCtx)
   at System.Threading.ExecutionContext.Run(ExecutionContext executionContext, ContextCallback callback, Object state)
   at MS.Internal.CulturePreservingExecutionContext.Run(CulturePreservingExecutionContext executionContext, ContextCallback callback, Object state)
   at System.Windows.Threading.DispatcherOperation.Invoke()
   at System.Windows.Threading.Dispatcher.ProcessQueue()
   at System.Windows.Threading.Dispatcher.WndProcHook(IntPtr hwnd, Int32 msg, IntPtr wParam, IntPtr lParam, Boolean& handled)
   at MS.Win32.HwndWrapper.WndProc(IntPtr hwnd, Int32 msg, IntPtr wParam, IntPtr lParam, Boolean& handled)
   at MS.Win32.HwndSubclass.DispatcherCallbackOperation(Object o)
   at System.Windows.Threading.ExceptionWrapper.InternalRealCall(Delegate callback, Object args, Int32 numArgs)
   at System.Windows.Threading.ExceptionWrapper.TryCatchWhen(Object source, Delegate callback, Object args, Int32 numArgs, Delegate catchHandler)
   at System.Windows.Threading.Dispatcher.LegacyInvokeImpl(DispatcherPriority priority, TimeSpan timeout, Delegate method, Object args, Int32 numArgs)
   at MS.Win32.HwndSubclass.SubclassWndProc(IntPtr hwnd, Int32 msg, IntPtr wParam, IntPtr lParam)
   at MS.Win32.UnsafeNativeMethods.DispatchMessage(MSG& msg)
   at System.Windows.Threading.Dispatcher.PushFrameImpl(DispatcherFrame frame)
   at System.Windows.Application.RunDispatcher(Object ignore)
   at System.Windows.Application.RunInternal(Window window)
   at LogiOverlay.App.Main()

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: 0C4F13796AF8A01FC4EC4C83A621C557
* Thumbprint: A424D23B48C2C05F3FEEFCA592D6411C12C45116
* Issuer: CN=DigiCert EV Code Signing CA (SHA2), OU=www.digicert.com, O=DigiCert Inc, C=US
* Subject: CN=Logitech Inc, O=Logitech Inc, L=Newark, S=California, C=US, SERIALNUMBER=C1067879, OID.2.5.4.15=Private Organization, OID.1.3.6.1.4.1.311.60.2.1.2=California, OID.1.3.6.1.4.1.311.60.2.1.3=US

## File Metadata

* Original Filename: LogiOverlay.exe
* Product Name: Logi Overlay
* Company Name: Logitech
* File Version: 8.20.329
* Product Version: 8.20.329
* Language: Language Neutral
* Legal Copyright: (C)  1998-2019  Logitech. All rights reserved.

MIT License. Copyright (c) 2020 Strontic.


