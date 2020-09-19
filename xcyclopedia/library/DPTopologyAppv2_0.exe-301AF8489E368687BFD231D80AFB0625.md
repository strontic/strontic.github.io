---
title: DPTopologyAppv2_0.exe | Intel(R) Graphics Control Panel
---

# DPTopologyAppv2_0.exe 

* File Path: `C:\WINDOWS\system32\DPTopologyAppv2_0.exe`
* Description: Intel(R) Graphics Control Panel

## Hashes

Type | Hash
-- | --
MD5 | `301AF8489E368687BFD231D80AFB0625`
SHA1 | `EC1956876B1F1B2CEF6F9F052FEB4BF34B427427`
SHA256 | `A8FAB3EFB5AE5A2A19ED5EA9BDE60599FA4DEAEFB6FE726336377E8FDB660D9C`
SHA384 | `474A1BF1299235CEA7AA30071911F7BBB0BD7BB50303228F1F1A5CF17F83EAB10405903DCD9593287331C46CAB8880BB`
SHA512 | `D1076F9721380D4862AF729E1DEDE077A446EBDC5D6A5FB39EA5A5122E05B2FBAB36A1AA1C6E965AA5234F84CCE43221438CC3FE4D6848535855A2BFCCBECC2C`
SSDEEP | `3072:I7GFfLYMJlL1vZOwbJGLD6DvtMJCU7DzpChJWn/qaBQd:FFLY6mw+ODvtMJfDVChJW/qaBE`

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
   at System.Windows.DependencyObject.UpdateEffectiveValue(EntryIndex entryIndex, DependencyProperty dp, PropertyMetadata metadata, EffectiveValueEntry oldEntry, EffectiveValueEntry& newEntry, Boolean coerceWithDeferredReference, OperationType operationType)
   at System.Windows.DependencyObject.SetValueCommon(DependencyProperty dp, Object value, PropertyMetadata metadata, Boolean coerceWithDeferredReference, OperationType operationType, Boolean isInternal)
   at System.Windows.DependencyObject.SetValue(DependencyProperty dp, Object value)
   at System.Windows.Controls.Primitives.ToggleButton.set_IsChecked(Nullable`1 value)
   at DPTopologyApp.MainWindow.Init()
   at DPTopologyApp.MainWindow.DPTopologyWindowLoaded(Object sender, RoutedEventArgs e)
   at System.Windows.EventRoute.InvokeHandlersImpl(Object source, RoutedEventArgs args, Boolean reRaised)
   at System.Windows.UIElement.RaiseEventImpl(DependencyObject sender, RoutedEventArgs args)
   at MS.Internal.FrameworkObject.OnLoaded(RoutedEventArgs args)
   at System.Windows.BroadcastEventHelper.BroadcastEvent(DependencyObject root, RoutedEvent routedEvent)
   at System.Windows.BroadcastEventHelper.BroadcastLoadedEvent(Object root)
   at System.Windows.Media.MediaContext.FireLoadedPendingCallbacks()
   at System.Windows.Media.MediaContext.FireInvokeOnRenderCallbacks()
   at System.Windows.Media.MediaContext.RenderMessageHandlerCore(Object resizedCompositionTarget)
   at System.Windows.Media.MediaContext.RenderMessageHandler(Object resizedCompositionTarget)
   at System.Windows.Media.MediaContext.Resize(ICompositionTarget resizedCompositionTarget)
   at System.Windows.Interop.HwndTarget.OnResize()
   at System.Windows.Interop.HwndTarget.HandleMessage(Int32 msg, IntPtr wparam, IntPtr lparam)
   at System.Windows.Interop.HwndSource.HwndTargetFilterMessage(IntPtr hwnd, Int32 msg, IntPtr wParam, IntPtr lParam, Boolean& handled)
   at MS.Win32.HwndWrapper.WndProc(IntPtr hwnd, Int32 msg, IntPtr wParam, IntPtr lParam, Boolean& handled)
   at MS.Win32.HwndSubclass.DispatcherCallbackOperation(Object o)
   at System.Windows.Threading.ExceptionWrapper.InternalRealCall(Delegate callback, Object args, Boolean isSingleParameter)
   at System.Windows.Threading.ExceptionWrapper.TryCatchWhen(Object source, Delegate callback, Object args, Boolean isSingleParameter, Delegate catchHandler)
   at System.Windows.Threading.Dispatcher.InvokeImpl(DispatcherPriority priority, TimeSpan timeout, Delegate method, Object args, Boolean isSingleParameter)
   at MS.Win32.HwndSubclass.SubclassWndProc(IntPtr hwnd, Int32 msg, IntPtr wParam, IntPtr lParam)
   at MS.Win32.UnsafeNativeMethods.CallWindowProc(IntPtr wndProc, IntPtr hWnd, Int32 msg, IntPtr wParam, IntPtr lParam)
   at MS.Win32.HwndSubclass.DefWndProcWrapper(IntPtr hwnd, Int32 msg, IntPtr wParam, IntPtr lParam)
   at MS.Win32.UnsafeNativeMethods.CallWindowProc(IntPtr wndProc, IntPtr hWnd, Int32 msg, IntPtr wParam, IntPtr lParam)
   at MS.Win32.HwndSubclass.SubclassWndProc(IntPtr hwnd, Int32 msg, IntPtr wParam, IntPtr lParam)

```

### Child Processes:
dw20.exe

## Signature

* Status: Signature verified.
* Serial: `3300000010D1EBBCBE1C4C7C49000100000010`
* Thumbprint: `C802CA01BC3064BFC0510CC762FFAA20BFE8EC61`
* Issuer: CN=Microsoft Windows Hardware Compatibility PCA, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows Hardware Compatibility Publisher, OU=MOPR, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: DPTopologyAppv2_0.exe
* Product Name: Intel Graphics Control Panel
* Company Name: Intel Corporation
* File Version: 8.15.10.4248
* Product Version: 8.15.10.4248
* Language: Language Neutral
* Legal Copyright:  Intel Corporation.  All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\system32\DPTopologyApp.exe](DPTopologyApp.exe-4BBF74559712524F4B3538B8F28E4634.md) | 71
[C:\WINDOWS\system32\DriverStore\FileRepository\igdlh64.inf_amd64_69885addc92dcf91\DPTopologyApp.exe](DPTopologyApp.exe-7A1C2EF43CC4696FE295525630AB2F56.md) | 68
[C:\WINDOWS\system32\DriverStore\FileRepository\igdlh64.inf_amd64_69885addc92dcf91\DPTopologyAppv2_0.exe](DPTopologyAppv2_0.exe-9D5A50F61F6009E9B028E0EFFB947197.md) | 60
[C:\WINDOWS\system32\DriverStore\FileRepository\igdlh64.inf_amd64_69885addc92dcf91\GfxUIEx.exe](GfxUIEx.exe-9526B0F7E1DD6BFA9784163AA3CDB80E.md) | 36
[C:\WINDOWS\system32\DriverStore\FileRepository\igdlh64.inf_amd64_69885addc92dcf91\igfxTray.exe](igfxTray.exe-94CE60E4864942F14D34BE93FD8FE80B.md) | 43
[C:\WINDOWS\system32\GfxUIEx.exe](GfxUIEx.exe-F4B0CC2D2A1A48CA82EA949FFCB4F93B.md) | 36
[C:\WINDOWS\system32\igfxTray.exe](igfxTray.exe-7B5147E66B50A838C77345CF6D3065DC.md) | 49




MIT License. Copyright (c) 2020 Strontic.


