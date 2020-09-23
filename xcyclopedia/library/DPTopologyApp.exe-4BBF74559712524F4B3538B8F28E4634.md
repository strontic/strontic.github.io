---
title: DPTopologyApp.exe | Intel(R) Graphics Control Panel
excerpt: What is DPTopologyApp.exe?
---

# DPTopologyApp.exe 

* File Path: `C:\WINDOWS\system32\DPTopologyApp.exe`
* Description: Intel(R) Graphics Control Panel

## Hashes

Type | Hash
-- | --
MD5 | `4BBF74559712524F4B3538B8F28E4634`
SHA1 | `7F11CE0A4CE06E4514C3F499157E236BB4E71F7E`
SHA256 | `16BE63235795B327149BBCCCABCEF53920124704F1E93F0DCC1EF4D0290DEFB5`
SHA384 | `F07AA4203AF2E07A85125F13EBF6F165BCD41239BD63E1308CB714AB9A1784103F30CC1CA22BD8C2C6B9EE1884A889B3`
SHA512 | `6A631AADE2C8A23D47D7EC43C18B946010D64E4EFBD8CB880187700711AA108C7824A1598751EB05E8FDC276B4A1B05D6B0011F785833E70B4FC23D7B075D187`
SSDEEP | `3072:5Sl5je/1K+tfLzs6iXzt4MGLD6DvtMJCU7DzpChJWn/qasQ0QE:5me/1NL+SODvtMJfDVChJW/qasFQE`

## Runtime Data

### Usage (stderr):
```cmhg

Unhandled Exception: System.NullReferenceException: Object reference not set to an instance of an object.
   at DPTopologyApp.MainWindow.GetDpTopologySelectionSubTitleString()
   at DPTopologyApp.MainWindow.port_Checked(Object sender, RoutedEventArgs e)
   at System.Windows.EventRoute.InvokeHandlersImpl(Object source, RoutedEventArgs args, Boolean reRaised)
   at System.Windows.UIElement.RaiseEventImpl(DependencyObject sender, RoutedEventArgs args)
   at System.Windows.Controls.RadioButton.OnChecked(RoutedEventArgs e)
   at System.Windows.Controls.Primitives.ToggleButton.OnIsCheckedChanged(DependencyObject d, DependencyPropertyChangedEventArgs e)
   at System.Windows.DependencyObject.OnPropertyChanged(DependencyPropertyChangedEventArgs e)
   at System.Windows.FrameworkElement.OnPropertyChanged(DependencyPropertyChangedEventArgs e)
   at System.Windows.DependencyObject.NotifyPropertyChange(DependencyPropertyChangedEventArgs args)
   at System.Windows.DependencyObject.UpdateEffectiveValue(EntryIndex entryIndex, DependencyProperty dp, PropertyMetadata metadata, EffectiveValueEntry oldEntry, EffectiveValueEntry& newEntry, Boolean coerceWithDeferredReference, Boolean coerceWithCurrentValue, OperationType operationType)
   at System.Windows.DependencyObject.SetValueCommon(DependencyProperty dp, Object value, PropertyMetadata metadata, Boolean coerceWithDeferredReference, Boolean coerceWithCurrentValue, OperationType operationType, Boolean isInternal)
   at System.Windows.Controls.Primitives.ToggleButton.set_IsChecked(Nullable`1 value)
   at DPTopologyApp.MainWindow.Init()
   at DPTopologyApp.MainWindow.DPTopologyWindowLoaded(Object sender, RoutedEventArgs e)
   at System.Windows.EventRoute.InvokeHandlersImpl(Object source, RoutedEventArgs args, Boolean reRaised)
   at System.Windows.UIElement.RaiseEventImpl(DependencyObject sender, RoutedEventArgs args)
   at System.Windows.BroadcastEventHelper.BroadcastEvent(DependencyObject root, RoutedEvent routedEvent)
   at System.Windows.BroadcastEventHelper.BroadcastLoadedEvent(Object root)
   at MS.Internal.LoadedOrUnloadedOperation.DoWork()
   at System.Windows.Media.MediaContext.FireLoadedPendingCallbacks()
   at System.Windows.Media.MediaContext.FireInvokeOnRenderCallbacks()
   at System.Windows.Media.MediaContext.RenderMessageHandlerCore(Object resizedCompositionTarget)
   at System.Windows.Media.MediaContext.RenderMessageHandler(Object resizedCompositionTarget)
   at System.Windows.Interop.HwndTarget.OnResize()
   at System.Windows.Interop.HwndTarget.HandleMessage(WindowMessage msg, IntPtr wparam, IntPtr lparam)
   at System.Windows.Interop.HwndSource.HwndTargetFilterMessage(IntPtr hwnd, Int32 msg, IntPtr wParam, IntPtr lParam, Boolean& handled)
   at MS.Win32.HwndWrapper.WndProc(IntPtr hwnd, Int32 msg, IntPtr wParam, IntPtr lParam, Boolean& handled)
   at MS.Win32.HwndSubclass.DispatcherCallbackOperation(Object o)
   at System.Windows.Threading.ExceptionWrapper.InternalRealCall(Delegate callback, Object args, Int32 numArgs)
   at System.Windows.Threading.ExceptionWrapper.TryCatchWhen(Object source, Delegate callback, Object args, Int32 numArgs, Delegate catchHandler)
   at System.Windows.Threading.Dispatcher.LegacyInvokeImpl(DispatcherPriority priority, TimeSpan timeout, Delegate method, Object args, Int32 numArgs)
   at MS.Win32.HwndSubclass.SubclassWndProc(IntPtr hwnd, Int32 msg, IntPtr wParam, IntPtr lParam)
   at MS.Win32.UnsafeNativeMethods.CallWindowProc(IntPtr wndProc, IntPtr hWnd, Int32 msg, IntPtr wParam, IntPtr lParam)
   at MS.Win32.HwndSubclass.DefWndProcWrapper(IntPtr hwnd, Int32 msg, IntPtr wParam, IntPtr lParam)
   at MS.Win32.UnsafeNativeMethods.CallWindowProc(IntPtr wndProc, IntPtr hWnd, Int32 msg, IntPtr wParam, IntPtr lParam)
   at MS.Win32.HwndSubclass.SubclassWndProc(IntPtr hwnd, Int32 msg, IntPtr wParam, IntPtr lParam)

```

### Child Processes:
DPTopologyApp.exe WerFault.exe

## Signature

* Status: Signature verified.
* Serial: `3300000010D1EBBCBE1C4C7C49000100000010`
* Thumbprint: `C802CA01BC3064BFC0510CC762FFAA20BFE8EC61`
* Issuer: CN=Microsoft Windows Hardware Compatibility PCA, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows Hardware Compatibility Publisher, OU=MOPR, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: DPTopologyApp.exe
* Product Name: Intel Graphics Control Panel
* Company Name: Intel Corporation
* File Version: 8.15.10.4248
* Product Version: 8.15.10.4248
* Language: Language Neutral
* Legal Copyright:  Intel Corporation.  All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\system32\DPTopologyAppv2_0.exe](DPTopologyAppv2_0.exe-301AF8489E368687BFD231D80AFB0625.md) | 71
[C:\WINDOWS\system32\DriverStore\FileRepository\igdlh64.inf_amd64_69885addc92dcf91\DPTopologyApp.exe](DPTopologyApp.exe-7A1C2EF43CC4696FE295525630AB2F56.md) | 65
[C:\WINDOWS\system32\DriverStore\FileRepository\igdlh64.inf_amd64_69885addc92dcf91\DPTopologyAppv2_0.exe](DPTopologyAppv2_0.exe-9D5A50F61F6009E9B028E0EFFB947197.md) | 60
[C:\WINDOWS\system32\DriverStore\FileRepository\igdlh64.inf_amd64_69885addc92dcf91\GfxUIEx.exe](GfxUIEx.exe-9526B0F7E1DD6BFA9784163AA3CDB80E.md) | 43
[C:\WINDOWS\system32\DriverStore\FileRepository\igdlh64.inf_amd64_69885addc92dcf91\igfxTray.exe](igfxTray.exe-94CE60E4864942F14D34BE93FD8FE80B.md) | 38
[C:\WINDOWS\system32\GfxUIEx.exe](GfxUIEx.exe-F4B0CC2D2A1A48CA82EA949FFCB4F93B.md) | 38
[C:\WINDOWS\system32\igfxTray.exe](igfxTray.exe-7B5147E66B50A838C77345CF6D3065DC.md) | 41




MIT License. Copyright (c) 2020 Strontic.


