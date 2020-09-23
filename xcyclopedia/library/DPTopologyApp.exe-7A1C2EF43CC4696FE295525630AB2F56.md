---
title: DPTopologyApp.exe | Intel(R) Graphics Control Panel
excerpt: What is DPTopologyApp.exe?
---

# DPTopologyApp.exe 

* File Path: `C:\WINDOWS\system32\DriverStore\FileRepository\igdlh64.inf_amd64_69885addc92dcf91\DPTopologyApp.exe`
* Description: Intel(R) Graphics Control Panel

## Hashes

Type | Hash
-- | --
MD5 | `7A1C2EF43CC4696FE295525630AB2F56`
SHA1 | `AEDE3CA915A56188C63ECA20FE2D58EC2901CD31`
SHA256 | `2CAC12F641CB6B7A1A62B7C4C5F9D5248C2DABC55E6076CD0221556D3669FD5E`
SHA384 | `6D62F9F8C06029FB5E0F689B725D4DCA51080B8614FC5FFA9BEC4A259600892247C3A94BA04B6506A64C6E79C1805516`
SHA512 | `567B484B1142739F0A59F9F98A736D9F1E6B2DC71C5AB5A72D2759D22AB705B473C950931B0BD4D39E78AE039C7CE626C4DF3309E73407748C39A004FAB613F0`
SSDEEP | `3072:E/FfLGdjl6kopZE7J8cGLD6DvtMJCU7DzpChJWn/qa2bzooS:E/FLO8ECODvtMJfDVChJW/qa2ooS`

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
* Serial: `330000002D4E7AEC99B0F05F7300000000002D`
* Thumbprint: `431FA5538299F973C06FDE9D6E97CC81C047AB0E`
* Issuer: CN=Microsoft Windows Third Party Component CA 2012, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows Hardware Compatibility Publisher, OU=MOPR, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: DPTopologyApp.exe
* Product Name: Intel Graphics Control Panel
* Company Name: Intel Corporation
* File Version: 8.15.10.3682
* Product Version: 8.15.10.3682
* Language: Language Neutral
* Legal Copyright:  Intel Corporation.  All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\system32\DPTopologyApp.exe](DPTopologyApp.exe-4BBF74559712524F4B3538B8F28E4634.md) | 65
[C:\WINDOWS\system32\DPTopologyAppv2_0.exe](DPTopologyAppv2_0.exe-301AF8489E368687BFD231D80AFB0625.md) | 68
[C:\WINDOWS\system32\DriverStore\FileRepository\igdlh64.inf_amd64_69885addc92dcf91\DPTopologyAppv2_0.exe](DPTopologyAppv2_0.exe-9D5A50F61F6009E9B028E0EFFB947197.md) | 61
[C:\WINDOWS\system32\DriverStore\FileRepository\igdlh64.inf_amd64_69885addc92dcf91\GfxUIEx.exe](GfxUIEx.exe-9526B0F7E1DD6BFA9784163AA3CDB80E.md) | 33
[C:\WINDOWS\system32\DriverStore\FileRepository\igdlh64.inf_amd64_69885addc92dcf91\igfxTray.exe](igfxTray.exe-94CE60E4864942F14D34BE93FD8FE80B.md) | 40
[C:\WINDOWS\system32\GfxUIEx.exe](GfxUIEx.exe-F4B0CC2D2A1A48CA82EA949FFCB4F93B.md) | 33
[C:\WINDOWS\system32\igfxTray.exe](igfxTray.exe-7B5147E66B50A838C77345CF6D3065DC.md) | 47




MIT License. Copyright (c) 2020 Strontic.


