---
title: TelephonyRuntime.dll | TODO- <File description>
excerpt: What is TelephonyRuntime.dll?
---

# TelephonyRuntime.dll 

* File Path: `C:\Program Files (x86)\Cisco Systems\Cisco Jabber\Plugins\TelephonyRuntime\TelephonyRuntime.dll`
* Description: TODO: <File description>

## Hashes

Type | Hash
-- | --
MD5 | `A64C46406258C53898C87DCCCF9BBB8A`
SHA1 | `37374646E12B53261921C43B0CD14D29847CD588`
SHA256 | `6F19F365F3C93370970C93795828C4BE9E854257F04B0D1D6858104503EF45A4`
SHA384 | `D060EE784106A1487E8EC0BDE2156C008C9B6C7AA58826C08F1986C2C9F90166FAF18B00104E04F4C52F1C5D1EC1C6FB`
SHA512 | `5E088FA1EA0F24E26F6E70E1030FC6E4F3981276FF033C0F62672B165E22C266AAC7D70AE493EACC59B04F52ADB9B6EE44616F233DC9B2B7170290F2A19C7F29`
SSDEEP | `12288:aGtdpQy2apr9jYcXhxLz1DliKUtOxLKmtqylQ/rrf7z0a4jArZ5YmkSStFTNqg5p:NH1DliKuOsmtqeQwArZ5YmkSK53HZ`
IMP | `6F3C5BEEF90A351FC6AAAC4D4BC813F0`
PESHA1 | `3EEC50F897FDA0E154FFE2D32F6081660AF22BC6`
PE256 | `860D5FE11F10DD40C4292957C08E058CEA766AC92A6707E80CC7F424F0360354`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`protected: void __thiscall MultilineEventMgr::firePhoneModeSingleLineAvailable(void)` | 73 | Exported Function
`protected: void __thiscall MultilineEventMgr::enableSingleLine(void)` | 66 | Exported Function
`protected: void __thiscall MultilineEventMgr::destroySinglelineNotifier(void)` | 61 | Exported Function
`protected: void __thiscall MultilineEventMgr::firePhoneModeSingleLineEnabled(void)` | 76 | Exported Function
`protected: void __thiscall MultilineEventMgr::firePhoneModeSingleLineDisconnected(void)` | 75 | Exported Function
`protected: void __thiscall MultilineEventMgr::firePhoneModeSingleLineDisabled(void)` | 74 | Exported Function
`protected: virtual void __thiscall MultilineEventMgr::firePreferredLineUpdated(void)` | 78 | Exported Function
`protected: virtual void __thiscall MultilineEventMgr::fireMultilineUnavailable(void)` | 72 | Exported Function
`protected: virtual void __thiscall MultilineEventMgr::fireMultilineEnabled(void)` | 71 | Exported Function
`protected: virtual void __thiscall MultilineEventMgr::setSinglelineState(enum SINGLELINESTATE)` | 174 | Exported Function
`protected: virtual void __thiscall MultilineEventMgr::setMultilineState(enum MULTILINESTATE)` | 173 | Exported Function
`protected: virtual void __thiscall MultilineEventMgr::initMultilineNotifier(void)` | 94 | Exported Function
`public: __thiscall MultilineEventMgr::MultilineEventMgr(class MultilineEventMgr const &)` | 3 | Exported Function
`protected: void __thiscall MultilineEventMgr::onTelephonyDeviceChanged(bool)` | 154 | Exported Function
`protected: void __thiscall MultilineEventMgr::onSingleLineConnectionStatusChanged(void)` | 152 | Exported Function
`public: __thiscall RuntimeToolbarEvents::RuntimeToolbarEvents(class RuntimeToolbarEvents const &)` | 6 | Exported Function
`public: __thiscall MultilineEventMgr::MultilineEventMgr(void)` | 5 | Exported Function
`public: __thiscall MultilineEventMgr::MultilineEventMgr(class std::weak_ptr<class CSFUnified::TelephonyService>,struct IPluginRuntime *,class CSFUnified::ServiceFactory *)` | 4 | Exported Function
`protected: void __thiscall MultilineEventMgr::onConnectionStatusChanged(void)` | 116 | Exported Function
`protected: void __thiscall MultilineEventMgr::initSinglelineNotifier(void)` | 96 | Exported Function
`protected: void __thiscall MultilineEventMgr::firePhoneModeSingleLineUnavailable(void)` | 77 | Exported Function
`protected: void __thiscall MultilineEventMgr::onPreferredLineChanged(bool)` | 133 | Exported Function
`protected: void __thiscall MultilineEventMgr::onIsSingleLineConfiguredChanged(bool)` | 131 | Exported Function
`protected: void __thiscall MultilineEventMgr::onIsMultilineConfiguredChanged(bool)` | 130 | Exported Function
`protected: virtual void __thiscall MultilineEventMgr::fireMultilineDisconnected(void)` | 70 | Exported Function
`protected: virtual long __stdcall TelephonyRuntime::initPlugin(struct IPluginRuntime *,class IJabberContext *)` | 95 | Exported Function
`protected: virtual long __stdcall TelephonyRuntime::destroy(bool &)` | 59 | Exported Function
`protected: virtual enum SINGLELINESTATE __thiscall MultilineEventMgr::getSinglelineState(void)` | 89 | Exported Function
`protected: virtual long __stdcall TelephonyRuntime::logoutRequested(bool *)` | 106 | Exported Function
`protected: virtual long __stdcall TelephonyRuntime::loggedOut(void)` | 105 | Exported Function
`protected: virtual long __stdcall TelephonyRuntime::loggedIn(void)` | 104 | Exported Function
`protected: virtual class CSFUnified::ServiceFactory * __thiscall MultilineEventMgr::GetServiceFactory(void)` | 29 | Exported Function
`protected: class std::enable_shared_from_this<class RuntimeToolbarEvents> & __thiscall std::enable_shared_from_this<class RuntimeToolbarEvents>::operator=(class std::enable_shared_from_this<class RuntimeToolbarEvents> const &)` | 14 | Exported Function
`protected: class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __thiscall MultilineEventMgr::stateStr(enum MULTILINESTATE)` | 181 | Exported Function
`protected: virtual enum MULTILINESTATE __thiscall MultilineEventMgr::getMultilineState(void)` | 87 | Exported Function
`protected: virtual class std::shared_ptr<class CSFUnified::TelephonyService> __thiscall MultilineEventMgr::GetTelephonyService(void)` | 32 | Exported Function
`protected: virtual class std::shared_ptr<class CSFUnified::TelephonyDevice> __thiscall MultilineEventMgr::GetTelephonyDevice(void)` | 31 | Exported Function
`protected: virtual unsigned long __stdcall TelephonyRuntime::Release(void)` | 40 | Exported Function
`protected: virtual unsigned long __stdcall TelephonyRuntime::AddRef(void)` | 23 | Exported Function
`protected: virtual struct IPluginRuntime * __thiscall MultilineEventMgr::GetPluginRuntime(void)` | 26 | Exported Function
`protected: virtual void __thiscall MultilineEventMgr::fireMultilineDisabled(void)` | 69 | Exported Function
`protected: virtual void __thiscall MultilineEventMgr::fireMultilineAvailable(void)` | 68 | Exported Function
`protected: virtual void __thiscall MultilineEventMgr::destroyMultilineNotifier(void)` | 60 | Exported Function
`protected: virtual long __stdcall TelephonyRuntime::onDefaultActionRequested(class std::shared_ptr<class JabberSelectionContextStruct>,wchar_t *,bool &)` | 129 | Exported Function
`protected: virtual long __stdcall TelephonyRuntime::onBroadcastMessageReceived(wchar_t *)` | 109 | Exported Function
`protected: virtual long __stdcall TelephonyRuntime::onApplicationStateChanged(enum ApplicationState)` | 107 | Exported Function
`protected: virtual long __stdcall TelephonyRuntime::startPlugin(void)` | 180 | Exported Function
`protected: virtual long __stdcall TelephonyRuntime::QueryInterface(struct _GUID const &,void * *)` | 38 | Exported Function
`protected: virtual long __stdcall TelephonyRuntime::processLocalEvent(wchar_t *,unsigned int,long)` | 165 | Exported Function
`public: virtual long __stdcall RuntimeToolbarEvents::onToolbarLoaded(unsigned int,class std::shared_ptr<class JabberSelectionContextStruct>,enum ToolbarType,wchar_t *,struct HWND__ *)` | 160 | Exported Function
`public: virtual long __stdcall RuntimeToolbarEvents::onToolbarKeyDown(unsigned int,unsigned int,unsigned int,unsigned int,long)` | 159 | Exported Function
`public: virtual long __stdcall RuntimeToolbarEvents::onToolbarContextChanged(unsigned int,wchar_t *,class std::shared_ptr<class JabberSelectionContextStruct>,class std::shared_ptr<class JabberSelectionContextStruct>,struct HWND__ *)` | 158 | Exported Function
`public: virtual long __stdcall RuntimeToolbarEvents::onToolbarVisibilityChanged(unsigned int,unsigned int,bool)` | 163 | Exported Function
`public: virtual long __stdcall RuntimeToolbarEvents::onToolbarUnloaded(unsigned int)` | 162 | Exported Function
`public: virtual long __stdcall RuntimeToolbarEvents::onToolbarStatusAreaAdded(unsigned int,unsigned int,unsigned int)` | 161 | Exported Function
`public: virtual long __stdcall RuntimeToolbarEvents::onConversationWindowManagerUnloaded(unsigned int)` | 128 | Exported Function
`public: virtual long __stdcall RuntimeToolbarEvents::onConversationWindowManagerLoaded(unsigned int,struct IJabberIntegratedConversationWindow *)` | 127 | Exported Function
`public: virtual long __stdcall RuntimeToolbarEvents::onConversationWindowActive(unsigned int,unsigned int,bool)` | 126 | Exported Function
`public: virtual long __stdcall RuntimeToolbarEvents::onToolbarCommandExecuted(unsigned int,unsigned int,class std::shared_ptr<class JabberSelectionContextStruct>,struct tagRECT,wchar_t *,struct HWND__ *)` | 157 | Exported Function
`public: virtual long __stdcall RuntimeToolbarEvents::onToolbarButtonChanged(unsigned int,unsigned int,struct tagRECT)` | 156 | Exported Function
`public: virtual long __stdcall RuntimeToolbarEvents::onPopoutWindowClosed(unsigned int,unsigned int,unsigned int)` | 132 | Exported Function
`public: void __thiscall RuntimeToolbarEvents::onSearchboxAction(unsigned int,class std::shared_ptr<class JabberSelectionContextStruct>)` | 139 | Exported Function
`public: void __thiscall RuntimeToolbarEvents::OnJCFConversationsChanged(bool,class std::shared_ptr<class std::vector<class std::shared_ptr<class CSFUnified::Conversation>,class std::allocator<class std::shared_ptr<class CSFUnified::Conversation> > > >,class std::shared_ptr<class std::vector<class std::shared_ptr<class CSFUnified::Conversation>,class std::allocator<class std::shared_ptr<class CSFUnified::Conversation> > > >)` | 36 | Exported Function
`public: void __thiscall RuntimeToolbarEvents::OnBridgeConferencingChanged(int,unsigned int)` | 35 | Exported Function
`public: void __thiscall RuntimeToolbarEvents::onSearchboxSelection(unsigned int,class std::shared_ptr<class JabberSelectionContextStruct>)` | 148 | Exported Function
`public: void __thiscall RuntimeToolbarEvents::onSearchBoxRemoved(unsigned int)` | 136 | Exported Function
`public: void __thiscall RuntimeToolbarEvents::onSearchBoxInserted(unsigned int,class ATL::CComBSTR,wchar_t *)` | 134 | Exported Function
`public: virtual unsigned long __stdcall RuntimeToolbarEvents::AddRef(void)` | 22 | Exported Function
`public: virtual struct IPluginRuntime * __thiscall TelephonyRuntime::GetPluginRuntime(void)` | 27 | Exported Function
`public: virtual long __stdcall RuntimeToolbarEvents::QueryInterface(struct _GUID const &,void * *)` | 37 | Exported Function
`public: void __thiscall RuntimeToolbarEvents::disconnectBindings(void)` | 62 | Exported Function
`public: void __thiscall RuntimeToolbarEvents::connectBindings(void)` | 53 | Exported Function
`public: virtual unsigned long __stdcall RuntimeToolbarEvents::Release(void)` | 39 | Exported Function
`public: virtual long __stdcall RuntimeToolbarEvents::onConversationUpdated(unsigned int,unsigned int,wchar_t *,wchar_t *)` | 125 | Exported Function
`public: class std::shared_ptr<class RuntimeToolbarEvents> __thiscall std::enable_shared_from_this<class RuntimeToolbarEvents>::shared_from_this(void)` | 175 | Exported Function
`public: class std::shared_ptr<class RuntimeToolbarEvents const > __thiscall std::enable_shared_from_this<class RuntimeToolbarEvents>::shared_from_this(void)const ` | 176 | Exported Function
`public: class std::shared_ptr<class RuntimeCompositeDeviceMenuManager> __thiscall RuntimeToolbarEvents::GetRuntimeCompositeDeviceMenuManager(void)` | 28 | Exported Function
`public: class TelephonyRuntime & __thiscall TelephonyRuntime::operator=(class TelephonyRuntime const &)` | 15 | Exported Function
`public: class std::weak_ptr<class RuntimeToolbarEvents> __thiscall std::enable_shared_from_this<class RuntimeToolbarEvents>::weak_from_this(void)` | 192 | Exported Function
`public: class std::weak_ptr<class RuntimeToolbarEvents const > __thiscall std::enable_shared_from_this<class RuntimeToolbarEvents>::weak_from_this(void)const ` | 193 | Exported Function
`public: __thiscall TelephonyRuntime::TelephonyRuntime(class TelephonyRuntime const &)` | 8 | Exported Function
`public: __thiscall RuntimeToolbarEvents::~RuntimeToolbarEvents(void)` | 12 | Exported Function
`public: __thiscall RuntimeToolbarEvents::RuntimeToolbarEvents(struct IPluginRuntime *,class IRuntimeToolbarEventsStaticsAccessor &,class IToolbarButtonInterface &)` | 7 | Exported Function
`public: bool __thiscall RuntimeToolbarEvents::isConferenceDlgShown(void)` | 98 | Exported Function
`public: __thiscall TelephonyRuntime::~TelephonyRuntime(void)` | 13 | Exported Function
`public: __thiscall TelephonyRuntime::TelephonyRuntime(void)` | 9 | Exported Function
`public: virtual long __stdcall RuntimeToolbarEvents::onConversationCloseRequested(unsigned int,unsigned int,unsigned int,enum CLOSE_MESSAGE *,wchar_t * *)` | 120 | Exported Function
`public: virtual long __stdcall RuntimeToolbarEvents::onConversationClosed(unsigned int,unsigned int,bool,bool)` | 121 | Exported Function
`public: virtual long __stdcall RuntimeToolbarEvents::onConversationAdded(unsigned int,unsigned int)` | 119 | Exported Function
`public: virtual long __stdcall RuntimeToolbarEvents::onConversationSelected(unsigned int,unsigned int,unsigned int,bool)` | 124 | Exported Function
`public: virtual long __stdcall RuntimeToolbarEvents::onConversationRemoved(unsigned int,unsigned int)` | 123 | Exported Function
`public: virtual long __stdcall RuntimeToolbarEvents::onConversationPaneAdded(unsigned int,unsigned int,unsigned int,unsigned int,enum PaneOrientation,struct HWND__ *)` | 122 | Exported Function
`public: virtual class CSFUnified::ServiceFactory * __thiscall TelephonyRuntime::GetServiceFactory(void)` | 30 | Exported Function
`public: virtual __thiscall MultilineEventMgr::~MultilineEventMgr(void)` | 11 | Exported Function
`public: static void * RuntimeToolbarEvents::hModule` | 90 | Exported Function
`public: virtual long __stdcall RuntimeToolbarEvents::onContentDropped(unsigned int,unsigned int,unsigned int,unsigned int)` | 118 | Exported Function
`public: virtual long __stdcall RuntimeToolbarEvents::isContentDroppable(unsigned int,unsigned int,unsigned int,unsigned int,bool &)` | 99 | Exported Function
`public: virtual class IJabberContext * __thiscall TelephonyRuntime::GetJabberContext(void)` | 24 | Exported Function
`protected: __thiscall std::enable_shared_from_this<class RuntimeToolbarEvents>::~enable_shared_from_this<class RuntimeToolbarEvents>(void)` | 10 | Exported Function
`private: long __thiscall RuntimeToolbarEvents::addCallSplitButton(unsigned int,wchar_t *,class std::shared_ptr<class CSFUnified::Contact>,class std::shared_ptr<class JabberSelectionContextStruct>)` | 48 | Exported Function
`private: long __thiscall RuntimeToolbarEvents::addCallGroupButton(unsigned int,wchar_t *,class std::shared_ptr<class JabberSelectionContextStruct>)` | 47 | Exported Function
`private: long __thiscall RuntimeToolbarEvents::addCallDropDownMenuButton(unsigned int,wchar_t *,class std::shared_ptr<class CSFUnified::Contact>,class std::shared_ptr<class JabberSelectionContextStruct>)` | 46 | Exported Function
`private: long __thiscall RuntimeToolbarEvents::removeCallButtons(unsigned int)` | 170 | Exported Function
`private: long __thiscall RuntimeToolbarEvents::removeAudioDevicesButton(unsigned int)` | 169 | Exported Function
`private: long __thiscall RuntimeToolbarEvents::addConferenceOrJoinBridgeButton(int,unsigned int,class std::shared_ptr<class JabberSelectionContextStruct>)` | 50 | Exported Function
`private: long __thiscall RuntimeToolbarEvents::addCallButton(unsigned int,wchar_t *,class std::shared_ptr<class JabberSelectionContextStruct>)` | 42 | Exported Function
`private: long __stdcall RuntimeToolbarEvents::AddAudioDevicesButton(unsigned int,wchar_t *)` | 21 | Exported Function
`private: enum CSFUnified::BridgeConferencingStateEnum::BridgeConferencingState __thiscall RuntimeToolbarEvents::getConferencingCapability(int)` | 85 | Exported Function
`private: long __thiscall RuntimeToolbarEvents::addCallContactButton(unsigned int,wchar_t *,class std::shared_ptr<class CSFUnified::Contact>,class std::shared_ptr<class JabberSelectionContextStruct>)` | 45 | Exported Function
`private: long __thiscall RuntimeToolbarEvents::addCallConferenceButton(unsigned int,wchar_t *,class std::shared_ptr<class JabberSelectionContextStruct>)` | 44 | Exported Function
`private: long __thiscall RuntimeToolbarEvents::addCallButtonForFederatedContact(unsigned int,wchar_t *,class std::shared_ptr<class JabberSelectionContextStruct>)` | 43 | Exported Function
`private: virtual long __stdcall TelephonyRuntime::onSearchboxFocus(unsigned int,bool)` | 142 | Exported Function
`private: virtual long __stdcall TelephonyRuntime::onSearchboxEscapePressed(unsigned int,bool)` | 141 | Exported Function
`private: virtual long __stdcall TelephonyRuntime::onSearchboxAction(unsigned int,class std::shared_ptr<class JabberSelectionContextStruct>)` | 140 | Exported Function
`private: virtual long __stdcall TelephonyRuntime::onSearchboxOverlayDisplayed(unsigned int,bool)` | 144 | Exported Function
`private: virtual long __stdcall TelephonyRuntime::onSearchboxKeyDownAction(unsigned int,unsigned int,long)` | 143 | Exported Function
`private: virtual long __stdcall TelephonyRuntime::onSearchBoxInserted(unsigned int,wchar_t *,wchar_t *)` | 135 | Exported Function
`private: virtual class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __thiscall RuntimeToolbarEvents::createPhoneNumberMenu(struct tagRECT,class std::shared_ptr<class JabberSelectionContextStruct>,struct HWND__ *)` | 57 | Exported Function
`private: virtual bool __thiscall RuntimeToolbarEvents::callActive(int,wchar_t *)` | 52 | Exported Function
`private: static class CSFUnified::ServiceFactory * TelephonyRuntime::pServiceFactory` | 164 | Exported Function
`private: virtual long __stdcall TelephonyRuntime::onCallButtonFocus(unsigned int,bool)` | 112 | Exported Function
`private: virtual long __stdcall TelephonyRuntime::onCallButtonClicked(unsigned int,class csf::SecureString)` | 111 | Exported Function
`private: virtual long __stdcall TelephonyRuntime::HideLinesList(void)` | 34 | Exported Function
`private: class std::shared_ptr<class CSFUnified::Conversation> __thiscall RuntimeToolbarEvents::getConversation(int)` | 86 | Exported Function
`DllUnregisterServer` | 197 | Exported Function
`DllRegisterServer` | 196 | Exported Function
`DllGetClassObject` | 195 | Exported Function
`private: bool __thiscall RuntimeToolbarEvents::getBridgeCallButtonIcons(enum CSFUnified::BridgeConferencingStateEnum::BridgeConferencingState,unsigned int,unsigned int &,unsigned int &)` | 80 | Exported Function
`private: bool __thiscall RuntimeToolbarEvents::getBridgeCallButtonEnabled(enum CSFUnified::BridgeConferencingStateEnum::BridgeConferencingState,class std::shared_ptr<class JabberSelectionContextStruct>)` | 79 | Exported Function
`private: bool __thiscall RuntimeToolbarEvents::contextIsNULL(class std::shared_ptr<class JabberSelectionContextStruct>)` | 56 | Exported Function
`const RuntimeToolbarEvents::``vftable'{for ``IJabberToolbarEvents'}` | 18 | Exported Function
`const RuntimeToolbarEvents::``vftable'{for ``IJabberIntegratedConversationWindowEvents'}` | 17 | Exported Function
`const MultilineEventMgr::``vftable'` | 16 | Exported Function
`DllCanUnloadNow` | 194 | Exported Function
`const TelephonyRuntime::``vftable'{for ``IJabberSearchAreaEvents'}` | 20 | Exported Function
`const TelephonyRuntime::``vftable'{for ``IJabberPlugin'}` | 19 | Exported Function
`private: class AT::CStringT<wchar_t> __thiscall RuntimeToolbarEvents::GetLocalizedCString(unsigned int)` | 25 | Exported Function
`private: class AT::CStringT<wchar_t> __thiscall RuntimeToolbarEvents::getCallButtonToolTipForContact(class std::shared_ptr<class CSFUnified::Contact>)` | 84 | Exported Function
`private: class AT::CStringT<wchar_t> __thiscall RuntimeToolbarEvents::getBridgeCallButtonType(enum CSFUnified::BridgeConferencingStateEnum::BridgeConferencingState)` | 83 | Exported Function
`private: class JabberToolbarButton __thiscall RuntimeToolbarEvents::createToolbarButton(class AT::CStringT<wchar_t>,unsigned int,unsigned int,bool,bool,class ATL::CComBSTR,unsigned long)` | 58 | Exported Function
`private: class ATL::CComBSTR __thiscall RuntimeToolbarEvents::getBridgeCallButtonTitle(enum CSFUnified::BridgeConferencingStateEnum::BridgeConferencingState)` | 81 | Exported Function
`private: class AT::CStringT<wchar_t> __thiscall RuntimeToolbarEvents::GetUnformattedLocalizedCString(unsigned int)` | 33 | Exported Function
`private: bool __thiscall RuntimeToolbarEvents::isConversationGroupOrPersistentChat(int)` | 101 | Exported Function
`private: bool __thiscall RuntimeToolbarEvents::isConversationConnectedToBridgeConferencingNotifier(int)` | 100 | Exported Function
`private: bool __thiscall RuntimeToolbarEvents::isChatTelephonyEscalationLimitReached(int)` | 97 | Exported Function
`private: class AT::CStringT<wchar_t> __thiscall RuntimeToolbarEvents::getBridgeCallButtonTooltip(enum CSFUnified::BridgeConferencingStateEnum::BridgeConferencingState)` | 82 | Exported Function
`private: bool __thiscall RuntimeToolbarEvents::shouldShowCallButtonForToolBar(wchar_t *,class std::shared_ptr<class JabberSelectionContextStruct>)` | 177 | Exported Function
`private: bool __thiscall RuntimeToolbarEvents::isConversationPersistentChat(int)` | 102 | Exported Function
`private: void __thiscall RuntimeToolbarEvents::updateCallConferenceButton(unsigned int,wchar_t *,class std::shared_ptr<class JabberSelectionContextStruct>)` | 186 | Exported Function
`private: void __thiscall RuntimeToolbarEvents::updateCallButton(unsigned int,wchar_t *,class std::shared_ptr<class JabberSelectionContextStruct>)` | 185 | Exported Function
`private: void __thiscall RuntimeToolbarEvents::updateActiveToolsBars(void)` | 184 | Exported Function
`private: void __thiscall RuntimeToolbarEvents::updateCallGroupButton(unsigned int,wchar_t *,class std::shared_ptr<class JabberSelectionContextStruct>)` | 189 | Exported Function
`private: void __thiscall RuntimeToolbarEvents::updateCallDropDownMenuButton(unsigned int,class std::shared_ptr<class CSFUnified::Contact>)` | 188 | Exported Function
`private: void __thiscall RuntimeToolbarEvents::updateCallContactButton(unsigned int,class std::shared_ptr<class CSFUnified::Contact>)` | 187 | Exported Function
`private: void __thiscall RuntimeToolbarEvents::refreshMenu(void)` | 166 | Exported Function
`private: void __thiscall RuntimeToolbarEvents::onTelephonyCapabilitiesChanged(void)` | 153 | Exported Function
`private: void __thiscall RuntimeToolbarEvents::onShowCallMenuCommandExecuted(unsigned int,class std::shared_ptr<class JabberSelectionContextStruct>,struct tagRECT,struct HWND__ *)` | 151 | Exported Function
`private: void __thiscall RuntimeToolbarEvents::showWarningDialogIfChatTelephonyEscalationLimitReached(void)` | 179 | Exported Function
`private: void __thiscall RuntimeToolbarEvents::showWarningDialogIfBridgeNumberEmpty(void)` | 178 | Exported Function
`private: void __thiscall RuntimeToolbarEvents::removeCapabilityNotifier(class std::shared_ptr<class CSFUnified::Conversation>)` | 171 | Exported Function
`private: void __thiscall TelephonyRuntime::unregisterConfigKeyForChanges(class std::weak_ptr<class CSFUnified::PropertyNotifierConnection> &)` | 182 | Exported Function
`private: void __thiscall TelephonyRuntime::setClickToCallRegistryEntries(void)` | 172 | Exported Function
`private: void __thiscall TelephonyRuntime::registerForConfigChangeForStatus(void)` | 168 | Exported Function
`protected: __thiscall std::enable_shared_from_this<class RuntimeToolbarEvents>::enable_shared_from_this<class RuntimeToolbarEvents>(void)` | 2 | Exported Function
`protected: __thiscall std::enable_shared_from_this<class RuntimeToolbarEvents>::enable_shared_from_this<class RuntimeToolbarEvents>(class std::enable_shared_from_this<class RuntimeToolbarEvents> const &)` | 1 | Exported Function
`private: void __thiscall TelephonyRuntime::unregisterForConfigChangeForStatus(void)` | 183 | Exported Function
`private: void __thiscall TelephonyRuntime::disconnectNotifier(class std::weak_ptr<class CSFUnified::PropertyNotifierConnection> &)` | 65 | Exported Function
`private: void __thiscall RuntimeToolbarEvents::updateConferenceOrJoinBridgeButton(int,unsigned int,class std::shared_ptr<class JabberSelectionContextStruct>)` | 191 | Exported Function
`private: void __thiscall RuntimeToolbarEvents::updateCallSplitButton(unsigned int,class std::shared_ptr<class CSFUnified::Contact>)` | 190 | Exported Function
`private: void __thiscall TelephonyRuntime::registerConfigKeyForChanges(class std::basic_string<wchar_t,struct std::char_traits<wchar_t>,class std::allocator<wchar_t> > const &,class std::weak_ptr<class CSFUnified::PropertyNotifierConnection> &)` | 167 | Exported Function
`private: void __thiscall TelephonyRuntime::onThemeChanged(void)` | 155 | Exported Function
`private: void __thiscall TelephonyRuntime::onConfigChanged(class std::basic_string<wchar_t,struct std::char_traits<wchar_t>,class std::allocator<wchar_t> > const &)` | 115 | Exported Function
`private: void __thiscall RuntimeToolbarEvents::onContactP2PCapabilityChangedForToolbarWithId(unsigned int)` | 117 | Exported Function
`private: void __thiscall RuntimeToolbarEvents::addCapabilityNotifier(class std::shared_ptr<class CSFUnified::Conversation>)` | 49 | Exported Function
`private: virtual long __stdcall TelephonyRuntime::ShowLinesList(void)` | 41 | Exported Function
`private: virtual long __stdcall TelephonyRuntime::onSearchOverlayButtonClicked(unsigned int,unsigned int,class csf::SecureString)` | 138 | Exported Function
`private: void __thiscall RuntimeToolbarEvents::connectContactP2PCapabilityNotifier(unsigned int,class std::shared_ptr<class CSFUnified::Contact>)` | 55 | Exported Function
`private: void __thiscall RuntimeToolbarEvents::connectBridgeConferencingNotifier(int,unsigned int)` | 54 | Exported Function
`private: void __thiscall RuntimeToolbarEvents::buildMenu(class std::vector<class std::shared_ptr<class menu_v2::MenuItem>,class std::allocator<class std::shared_ptr<class menu_v2::MenuItem> > > &,class AT::CStringT<wchar_t>,class std::map<unsigned int,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> >,struct std::less<unsigned int>,class std::allocator<struct std::pair<unsigned int const ,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > > > > &,int,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> >,wchar_t * &)` | 51 | Exported Function
`private: virtual long __stdcall TelephonyRuntime::onSearchboxPreEscapePressed(unsigned int)` | 147 | Exported Function
`private: virtual long __stdcall TelephonyRuntime::onSearchboxPreActionEnter(unsigned int,class std::shared_ptr<class JabberSelectionContextStruct>)` | 146 | Exported Function
`private: virtual long __stdcall TelephonyRuntime::onSearchboxOverlaySelection(unsigned int,class std::shared_ptr<class JabberSelectionContextStruct>)` | 145 | Exported Function
`private: virtual long __stdcall TelephonyRuntime::onSearchboxTextChanged(unsigned int,class csf::SecureString)` | 150 | Exported Function
`private: virtual long __stdcall TelephonyRuntime::onSearchboxSelection(unsigned int,class std::shared_ptr<class JabberSelectionContextStruct>)` | 149 | Exported Function
`private: virtual long __stdcall TelephonyRuntime::onSearchBoxRemoved(unsigned int)` | 137 | Exported Function
`private: void __thiscall RuntimeToolbarEvents::onAudioDevicesButtonClicked(struct HWND__ *,struct tagRECT)` | 108 | Exported Function
`private: void __thiscall RuntimeToolbarEvents::logContextNumbers(class std::shared_ptr<class JabberSelectionContextStruct>)` | 103 | Exported Function
`private: void __thiscall RuntimeToolbarEvents::handleToolbarButtons(unsigned int,wchar_t *,class std::shared_ptr<class JabberSelectionContextStruct>,struct HWND__ *)` | 93 | Exported Function
`private: void __thiscall RuntimeToolbarEvents::onCallContactCommandExecuted(class std::shared_ptr<class JabberSelectionContextStruct>)` | 114 | Exported Function
`private: void __thiscall RuntimeToolbarEvents::onCallConferenceCommandExecuted(class std::shared_ptr<class JabberSelectionContextStruct>)` | 113 | Exported Function
`private: void __thiscall RuntimeToolbarEvents::onCallBridgeCommandExecuted(class std::shared_ptr<class JabberSelectionContextStruct>)` | 110 | Exported Function
`private: void __thiscall RuntimeToolbarEvents::escalateToBridgeConference(int)` | 67 | Exported Function
`private: void __thiscall RuntimeToolbarEvents::disconnectContactP2PCapabilityNotifier(unsigned int)` | 64 | Exported Function
`private: void __thiscall RuntimeToolbarEvents::disconnectBridgeConferencingNotifier(int)` | 63 | Exported Function
`private: void __thiscall RuntimeToolbarEvents::handleCallButton(unsigned int,wchar_t *,class std::shared_ptr<class JabberSelectionContextStruct>)` | 92 | Exported Function
`private: void __thiscall RuntimeToolbarEvents::handleAudioDevicesButton(unsigned int,wchar_t *,class std::shared_ptr<class JabberSelectionContextStruct>,struct HWND__ *)` | 91 | Exported Function
`private: void __thiscall RuntimeToolbarEvents::getPhoneIconResourceIdsForSingleContact(unsigned int,unsigned int &,unsigned int &)` | 88 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `59C5C9F46EA82C4C743981566B64BD6C`
* Thumbprint: `475DAEE5A6CC149389EFDE176DEA526C627D203A`
* Issuer: CN=Symantec Class 3 SHA256 Code Signing CA - G2, OU=Symantec Trust Network, O=Symantec Corporation, C=US
* Subject: CN=Cisco Systems Inc., O=Cisco Systems Inc., L=San Jose, S=California, C=US

## File Metadata

* Original Filename: TelephonyRuntime.rc
* Product Name: TODO: <Product name>
* Company Name: Cisco Systems, Inc
* File Version: 12.9.2.54247
* Product Version: 12.9.2.54247
* Language: English (United States)
* Legal Copyright: Copyright (C) 2012-2015 Cisco Systems Inc.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/6f19f365f3c93370970c93795828c4be9e854257f04b0d1d6858104503ef45a4/detection/




MIT License. Copyright (c) 2020 Strontic.


