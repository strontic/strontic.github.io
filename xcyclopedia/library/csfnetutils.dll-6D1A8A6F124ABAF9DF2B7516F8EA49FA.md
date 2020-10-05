---
title: csfnetutils.dll | 
excerpt: What is csfnetutils.dll?
---

# csfnetutils.dll 

* File Path: `C:\Program Files (x86)\Cisco Systems\Cisco Jabber\csfnetutils.dll`

## Hashes

Type | Hash
-- | --
MD5 | `6D1A8A6F124ABAF9DF2B7516F8EA49FA`
SHA1 | `4C039C0211E9614B16F7744110B72FF90DD3007F`
SHA256 | `73B50C8DF89DA987B8E51BE37269023E7ED23FDD37408762ECC35AE4AFB5A4E7`
SHA384 | `9E2F154ADE54F6580FEA3A6D8234AA64C989EEBC4CDE6A6D17F35B813AD83EB7A4110ED81F565AF3AE962E97C53C44C0`
SHA512 | `3C05A25E0E325DBAD9C46964DCE027B4E4C1296344885EB73FAE8E2CFDFEF5C3FE89689E41CEEBC94B8C505B3D93D450159FA32F603B543199A3207E477C1712`
SSDEEP | `24576:aC3BKNNnNhoYM7f3GvpCAsw5v96l2o+BL7g9+AQ:viN47f6EAsw5vhHg9+AQ`
IMP | `73DF93E5E037E4481B152A9E9B693B0B`
PESHA1 | `EA41572B0F600617E941851B92C75B2185959744`
PE256 | `70C39E41B1DB9074B092EAC2F675334BF86EF64A94A645D84FB2387989B9DEA1`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`public: static long __cdecl csf::http::OpenSSLOptions::getOptions(long)` | 795 | Exported Function
`public: static long const csf::http::CurlHttpUtils::DEFAULT_CONNECTION_TIMEOUT_MS` | 541 | Exported Function
`public: static int __cdecl csf::http::CurlHttpUtils::curlTraceCallback(void *,enum curl_infotype,char *,unsigned int,void *)` | 680 | Exported Function
`public: static int __cdecl csf::http::SslUtils::verifyCb(struct x509_store_ctx_st *,void *)` | 1066 | Exported Function
`public: static struct _CERT_CONTEXT const * __cdecl csf::cert::Win32CertVerifier::createWindowsCertificateContext(struct x509_st const *)` | 673 | Exported Function
`public: static struct x509_st * __cdecl csf::cert::CertUtils::loadCertificate(unsigned char const *,int,enum csf::cert::CertEncoding::Format)` | 893 | Exported Function
`public: static long const csf::http::CurlHttpUtils::DEFAULT_LOW_TRANSFER_SPEED_TIMEOUT_SECONDS` | 542 | Exported Function
`public: static long const csf::http::CurlHttpUtils::DEFAULT_TRANSFER_TIMEOUT_MS` | 544 | Exported Function
`public: static enum csf::cert::CertAcceptanceDecision::Decision __cdecl csf::cert::CertVerificationFailureManager::manageCertValidationFailure(class std::shared_ptr<class csf::cert::CertificateData>,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::set<enum csf::cert::CertStatus::Status,struct std::less<enum csf::cert::CertStatus::Status>,class std::allocator<enum csf::cert::CertStatus::Status> > &,class std::shared_ptr<class csf::common::Policy>)` | 899 | Exported Function
`public: static enum csf::cert::InvalidCertNotificationManager::PromptDecision::Decision __cdecl csf::cert::InvalidCertNotificationManager::PromptDecision::build(enum csf::cert::CertAcceptanceDecision::Decision)` | 603 | Exported Function
`public: static class std::shared_ptr<class csf::netutils::NetworkEventReporterObserver> __cdecl csf::netutils::NetworkEventReporterObserver::getInstance(void)` | 776 | Exported Function
`public: static enum csf::cert::CertAcceptanceDecision::Decision __cdecl csf::cert::CertVerificationFailureManager::checkCertificateCachedDecision(class std::shared_ptr<class csf::cert::CertificateData>,class std::set<enum csf::cert::CertStatus::Status,struct std::less<enum csf::cert::CertStatus::Status>,class std::allocator<enum csf::cert::CertStatus::Status> > &,class std::shared_ptr<class csf::common::Policy>)` | 629 | Exported Function
`public: static enum CURLcode __cdecl csf::http::CurlHttpUtils::curlSSLCallback(void *,void *,void *)` | 679 | Exported Function
`public: static int __cdecl csf::http::CurlHttpUtils::curlProgressFunction(void *,double,double,double,double)` | 677 | Exported Function
`public: static enum csf::http::CurlHttpUtils::RequestPhase::Phase __cdecl csf::http::CurlHttpUtils::matchPhase(struct std::pair<enum curl_infotype,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > > const &)` | 901 | Exported Function
`public: static enum csf::http::CurlHttpUtils::RequestPhase::Phase __cdecl csf::http::CurlHttpUtils::matchPhaseFromInfoData(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 902 | Exported Function
`public: static unsigned int __cdecl csf::common::DefaultPoliciesStore::getNumObservers(void)` | 792 | Exported Function
`public: static void __cdecl csf::cert::CertificateValidityCache::addAcceptedValidCertificate(struct x509_st const *)` | 576 | Exported Function
`public: static void __cdecl csf::cert::CertificateValidityCache::addRejectedInvalidCertificate(struct x509_st const *,enum csf::cert::CertStatus::Status)` | 589 | Exported Function
`public: static void __cdecl csf::cert::CertCacheInterface::clearInvalidCertificateCache(void)` | 643 | Exported Function
`public: static void __cdecl csf::cert::CertificateValidityCache::addAcceptedInvalidCertificate(struct x509_st const *,enum csf::cert::CertStatus::Status)` | 575 | Exported Function
`public: static void __cdecl csf::cert::CertificateValidityCache::removeFromAcceptedInvalidCache(struct x509_st const *)` | 942 | Exported Function
`public: static void __cdecl csf::cert::CertificateValidityCache::removeFromRejectedInvalidCache(struct x509_st const *)` | 943 | Exported Function
`public: static void __cdecl csf::cert::CertificateValidityCache::clear(void)` | 632 | Exported Function
`public: static void __cdecl csf::cert::CertificateValidityCache::clearAcceptedInvalidCerts(void)` | 635 | Exported Function
`public: static unsigned int __cdecl csf::http::CurlHttpUtils::curlReadFileData(void *,unsigned int,unsigned int,class csf::http::RequestWrapper *)` | 678 | Exported Function
`public: static unsigned int __cdecl csf::http::CurlHttpUtils::curlWriteCallback(char *,unsigned int,unsigned int,void *)` | 681 | Exported Function
`public: static unsigned int __cdecl csf::common::SequenceNumber::getSequenceNumber(void)` | 812 | Exported Function
`public: static unsigned int __cdecl csf::http::CurlHttpUtils::curlHeaderCallback(char *,unsigned int,unsigned int,void *)` | 676 | Exported Function
`public: static unsigned long __cdecl csf::cert::CertUtils::stringToBytes(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> >,char *,unsigned long)` | 1042 | Exported Function
`public: static void __cdecl csf::cert::CertCacheInterface::clearAcceptedInvalidCerts(void)` | 634 | Exported Function
`public: static unsigned int __cdecl csf::http::HttpUtils::extractPortFromHttpUrl(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 721 | Exported Function
`public: static unsigned int const csf::netutils::TomcatPortModifier::DEFAULT_TOMCAT_PORT` | 543 | Exported Function
`public: static class std::shared_ptr<class csf::netutils::adapters::Nat64PrefixChangeAdapter> __cdecl csf::netutils::adapters::Nat64PrefixChangeAdapter::buildNat64PrefixChangeAdapter(void)` | 622 | Exported Function
`public: static class std::shared_ptr<class csf::common::Policy> const csf::http::SystemProxyUsagePolicy::NEVER_USE_SYSTEM_PROXY_POLICY` | 564 | Exported Function
`public: static class std::shared_ptr<class csf::common::Policy> const csf::http::SystemProxyUsagePolicy::USE_SYSTEM_PROXY_WHEN_REQUESTED_POLICY` | 573 | Exported Function
`public: static class std::shared_ptr<class csf::common::Policy> const csf::http::EdgePolicy::USE_EDGE_IF_REQUIRED_AUTHENTICATE_WITH_X_EDGE_AUTH_POLICY` | 571 | Exported Function
`public: static class std::shared_ptr<class csf::common::Policy> const csf::http::EdgePolicy::USE_EDGE_IF_REQUIRED_POLICY` | 572 | Exported Function
`public: static class std::shared_ptr<class csf::common::Policy> const csf::ip::IpFamilyPreferencePolicy::IPV6_ONLY_POLICY` | 559 | Exported Function
`public: static class std::shared_ptr<class csf::edge::EdgeDetectionControllerImpl> __cdecl csf::edge::EdgeDetectionControllerImpl::build(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> >,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> >,bool)` | 595 | Exported Function
`public: static class std::shared_ptr<class csf::common::Policy> const csf::ip::IpFamilyPreferencePolicy::DUAL_STACK_POLICY` | 547 | Exported Function
`public: static class std::shared_ptr<class csf::common::Policy> const csf::ip::IpFamilyPreferencePolicy::IPV4_ONLY_POLICY` | 558 | Exported Function
`public: static class std::shared_ptr<class csf::common::Policy> const csf::http::CommonCriteriaUsagePolicy::COMMON_CRITERIA_DISABLED_POLICY` | 539 | Exported Function
`public: static class std::shared_ptr<class csf::common::Policy> const csf::http::CommonCriteriaUsagePolicy::COMMON_CRITERIA_ENABLED_POLICY` | 540 | Exported Function
`public: static class std::shared_ptr<class csf::common::Policy> const csf::edge::EdgeCapabilityPolicy::EDGE_DISABLED_POLICY` | 548 | Exported Function
`public: static class std::shared_ptr<class csf::common::Policy> const csf::edge::EdgeCapabilityPolicy::EDGE_ENABLED_POLICY` | 549 | Exported Function
`public: static class std::shared_ptr<class csf::common::Policy> const csf::http::EdgePolicy::USE_EDGE_IF_REQUIRED_AUTHENTICATE_EDGE_TOKEN_AND_UNITY_COOKIE_POLICY` | 569 | Exported Function
`public: static class std::shared_ptr<class csf::common::Policy> const csf::http::EdgePolicy::USE_EDGE_IF_REQUIRED_AUTHENTICATE_WITH_REQUEST_OAUTH_TOKEN_POLICY` | 570 | Exported Function
`public: static class std::shared_ptr<class csf::common::Policy> const csf::http::EdgePolicy::ALWAYS_USE_EDGE_POLICY` | 538 | Exported Function
`public: static class std::shared_ptr<class csf::common::Policy> const csf::http::EdgePolicy::NEVER_USE_EDGE_POLICY` | 563 | Exported Function
`public: static class std::shared_ptr<class csf::edge::EdgeTransitionDetectionControllerImpl> __cdecl csf::edge::EdgeTransitionDetectionControllerImpl::build(void)` | 596 | Exported Function
`public: static class std::shared_ptr<class csf::http::ProxyAuthenticationHandler> __cdecl csf::http::ProxyAuthenticationHandler::getInstance(void)` | 777 | Exported Function
`public: static class std::shared_ptr<class csf::ip::ConnectionInformation> __cdecl csf::ip::ConnectionInformation::buildConnectionInformation(void)` | 612 | Exported Function
`public: static class std::shared_ptr<class csf::http::MultiHttpClientImpl> __cdecl csf::http::MultiHttpClientImpl::buildMultiHttpClientImpl(class std::shared_ptr<class csf::http::EdgeTransformer>,class std::shared_ptr<class csf::http::CertVerifier>,class std::shared_ptr<class csf::http::HttpNetworkEventReporter>,class std::shared_ptr<class csf::dns::DnsHostResolver>,unsigned int)` | 618 | Exported Function
`public: static class std::shared_ptr<class csf::http::MultiHttpClientImpl> __cdecl csf::http::MultiHttpClientImpl::buildMultiHttpClientImpl(class std::shared_ptr<class csf::http::EdgeTransformer>,class std::shared_ptr<class csf::http::CertVerifier>,class std::shared_ptr<class csf::http::HttpNetworkEventReporter>,unsigned int)` | 617 | Exported Function
`public: static class std::shared_ptr<class csf::ip::Nat64Prefix> __cdecl csf::ip::Nat64Prefix::buildNat64Prefix(void)` | 620 | Exported Function
`public: static class std::shared_ptr<class csf::netutils::adapters::Nat64PrefixChangeAdapter> __cdecl csf::netutils::adapters::Nat64PrefixChangeAdapter::buildNat64PrefixChangeAdapter(class std::shared_ptr<class csf::ip::Nat64Prefix>)` | 621 | Exported Function
`public: static class std::shared_ptr<class csf::ip::ConnectionInformation> __cdecl csf::ip::ConnectionInformation::buildConnectionInformationWithStaticPolicy(class std::shared_ptr<class csf::common::Policy>)` | 613 | Exported Function
`public: static class std::shared_ptr<class csf::ip::Nat64Prefix> __cdecl csf::ip::Nat64Prefix::buildNat64Prefix(class std::shared_ptr<class csf::dns::DnsUtilsInterface>,bool)` | 619 | Exported Function
`public: static class std::shared_ptr<class csf::edge::GlobalEdgeStateImpl> __cdecl csf::edge::GlobalEdgeStateImpl::build(class std::shared_ptr<class csf::edge::EdgeConfigRequest>,class std::shared_ptr<class csf::edge::EdgeDetectionController>,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,bool,bool)` | 597 | Exported Function
`public: static class std::shared_ptr<class csf::edge::NetworkSensingEventRegistrator> __cdecl csf::edge::NetworkSensingEventRegistrator::build(class std::weak_ptr<class csf::edge::NetworkSensingObserver>)` | 600 | Exported Function
`public: static class std::shared_ptr<class csf::edge::EdgeUtils> & __cdecl csf::edge::EdgeUtils::getInstance(void)` | 774 | Exported Function
`public: static class std::shared_ptr<class csf::edge::GlobalEdgeState> __cdecl csf::netutils::GlobalEdgeStateController::getGlobalEdgeState(void)` | 769 | Exported Function
`public: static class std::shared_ptr<class csf::http::HttpClientData> __cdecl csf::http::HttpClientData::build(class std::shared_ptr<class csf::http::HttpNetworkEventReporter>,class std::shared_ptr<class csf::http::EdgeTransformer>)` | 598 | Exported Function
`public: static class std::shared_ptr<class csf::http::MultiHttpClientData> __cdecl csf::http::MultiHttpClientData::build(class std::shared_ptr<class csf::http::HttpNetworkEventReporter>,class std::shared_ptr<class csf::http::EdgeTransformer>,class std::shared_ptr<class csf::http::HttpRequestData>)` | 599 | Exported Function
`public: static class std::shared_ptr<class csf::edge::NetworkSensingEventRegistrator> __cdecl csf::edge::NetworkSensingEventRegistrator::buildForTesting(class std::weak_ptr<class csf::edge::NetworkSensingObserver>,class std::shared_ptr<class csf::common::BackgroundTimer>,class std::shared_ptr<class csf::edge::EdgeDetectionController>)` | 614 | Exported Function
`public: static class std::shared_ptr<class csf::http::BasicHttpClientImpl> __cdecl csf::http::BasicHttpClientImpl::buildBasicHttpClientImpl(class std::shared_ptr<class csf::http::EdgeTransformer>,class std::shared_ptr<class csf::http::CertVerifier>,class std::shared_ptr<class csf::ThreadPool>,class std::shared_ptr<class csf::http::HttpNetworkEventReporter>)` | 606 | Exported Function
`public: static void __cdecl csf::cert::CertVerifierFactory::setCertVerifier(class std::shared_ptr<class csf::cert::CertVerifier>)` | 971 | Exported Function
`public: struct csf::edge::EdgeService __thiscall csf::edge::EdgeConfig::getXmppEdgeService(void)const ` | 831 | Exported Function
`public: struct csf::edge::EdgeServiceRecordData & __thiscall csf::edge::EdgeServiceRecordData::operator=(struct csf::edge::EdgeServiceRecordData const &)` | 357 | Exported Function
`public: struct csf::edge::EdgeService __thiscall csf::edge::EdgeConfig::getSipEdgeService(void)const ` | 814 | Exported Function
`public: struct csf::edge::EdgeService __thiscall csf::edge::EdgeConfig::getTurnEdgeService(void)const ` | 819 | Exported Function
`public: struct csf::edge::EdgeTransitionDetectionController::DelayedSensingTimerExpiryEvent * __thiscall csf::edge::EdgeTransitionDetectionController::createDelayedSensingTimerExpiryEvent(void)const ` | 657 | Exported Function
`public: struct csf::edge::EdgeTransitionDetectionController::HintNetworkInterfaceDroppedEvent * __thiscall csf::edge::EdgeTransitionDetectionController::createHintNetworkInterfaceDroppedEvent(void)const ` | 659 | Exported Function
`public: struct csf::edge::EdgeTransitionDetectionController::AllIpInterfaceDownEvent * __thiscall csf::edge::EdgeTransitionDetectionController::createAllIpInterfaceDownEvent(void)const ` | 650 | Exported Function
`public: struct csf::edge::EdgeTransitionDetectionController::ApplicationWakeupEvent * __thiscall csf::edge::EdgeTransitionDetectionController::createApplicationWakeupEvent(void)const ` | 651 | Exported Function
`public: struct csf::edge::CollabEdgeServiceSensorStrategy & __thiscall csf::edge::CollabEdgeServiceSensorStrategy::operator=(struct csf::edge::CollabEdgeServiceSensorStrategy const &)` | 338 | Exported Function
`public: struct csf::edge::DetectDirectConnectAvailableFsm::Statistics & __thiscall csf::edge::DetectDirectConnectAvailableFsm::Statistics::operator=(struct csf::edge::DetectDirectConnectAvailableFsm::Statistics &&)` | 424 | Exported Function
`public: struct csf::dns::DnsQueryResult & __thiscall csf::dns::DnsQueryResult::operator=(struct csf::dns::DnsQueryResult const &)` | 348 | Exported Function
`public: struct csf::edge::CollabEdgeServiceSensorStrategy & __thiscall csf::edge::CollabEdgeServiceSensorStrategy::operator=(struct csf::edge::CollabEdgeServiceSensorStrategy &&)` | 337 | Exported Function
`public: struct csf::edge::DetectDirectConnectUnavailableFsm::Statistics & __thiscall csf::edge::DetectDirectConnectUnavailableFsm::Statistics::operator=(struct csf::edge::DetectDirectConnectUnavailableFsm::Statistics const &)` | 427 | Exported Function
`public: struct csf::edge::EdgeService __thiscall csf::edge::EdgeConfig::getHttpEdgeService(void)const ` | 771 | Exported Function
`public: struct csf::edge::DetectDirectConnectAvailableFsm::Statistics & __thiscall csf::edge::DetectDirectConnectAvailableFsm::Statistics::operator=(struct csf::edge::DetectDirectConnectAvailableFsm::Statistics const &)` | 425 | Exported Function
`public: struct csf::edge::DetectDirectConnectUnavailableFsm::Statistics & __thiscall csf::edge::DetectDirectConnectUnavailableFsm::Statistics::operator=(struct csf::edge::DetectDirectConnectUnavailableFsm::Statistics &&)` | 426 | Exported Function
`public: struct csf::edge::EdgeTransitionDetectionController::HintNetworkStackNotReadyEvent * __thiscall csf::edge::EdgeTransitionDetectionController::createHintNetworkStackNotReadyEvent(void)const ` | 660 | Exported Function
`public: struct csf::edge::OnPremService __thiscall csf::edge::EdgeConfig::getOnPremService(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)const ` | 793 | Exported Function
`public: struct csf::http::AuthenticationType & __thiscall csf::http::AuthenticationType::operator=(struct csf::http::AuthenticationType &&)` | 307 | Exported Function
`public: struct csf::edge::NetworkSensingEvent & __thiscall csf::edge::NetworkSensingEvent::operator=(struct csf::edge::NetworkSensingEvent &&)` | 399 | Exported Function
`public: struct csf::edge::NetworkSensingEvent & __thiscall csf::edge::NetworkSensingEvent::operator=(struct csf::edge::NetworkSensingEvent const &)` | 400 | Exported Function
`public: struct csf::http::EdgeTransformer::TransformRequestResult & __thiscall csf::http::EdgeTransformer::TransformRequestResult::operator=(struct csf::http::EdgeTransformer::TransformRequestResult const &)` | 432 | Exported Function
`public: struct csf::http::HttpClientError & __thiscall csf::http::HttpClientError::operator=(struct csf::http::HttpClientError &&)` | 370 | Exported Function
`public: struct csf::http::AuthenticationType & __thiscall csf::http::AuthenticationType::operator=(struct csf::http::AuthenticationType const &)` | 308 | Exported Function
`public: struct csf::http::EdgeTransformer::TransformRequestResult & __thiscall csf::http::EdgeTransformer::TransformRequestResult::operator=(struct csf::http::EdgeTransformer::TransformRequestResult &&)` | 431 | Exported Function
`public: struct csf::edge::EdgeTransitionDetectionController::StartMonitoringFromInsideEvent * __thiscall csf::edge::EdgeTransitionDetectionController::createStartMonitoringFromInsideEvent(struct csf::edge::DetectionParameters const &)const ` | 671 | Exported Function
`public: struct csf::edge::EdgeTransitionDetectionController::StartPollingFromOutsideEvent * __thiscall csf::edge::EdgeTransitionDetectionController::createStartPollingFromOutsideEvent(struct csf::edge::DetectionParameters const &)const ` | 672 | Exported Function
`public: struct csf::edge::EdgeTransitionDetectionController::IpInterfaceChangedEvent * __thiscall csf::edge::EdgeTransitionDetectionController::createIpInterfaceChangedEvent(void)const ` | 663 | Exported Function
`public: struct csf::edge::EdgeTransitionDetectionController::NetworkActivityEvent * __thiscall csf::edge::EdgeTransitionDetectionController::createNetworkActivityEvent(void)const ` | 668 | Exported Function
`public: struct csf::edge::GlobalEdgeState::TerminateEdgeSessionResult & __thiscall csf::edge::GlobalEdgeState::TerminateEdgeSessionResult::operator=(struct csf::edge::GlobalEdgeState::TerminateEdgeSessionResult &&)` | 428 | Exported Function
`public: struct csf::edge::GlobalEdgeState::TerminateEdgeSessionResult & __thiscall csf::edge::GlobalEdgeState::TerminateEdgeSessionResult::operator=(struct csf::edge::GlobalEdgeState::TerminateEdgeSessionResult const &)` | 429 | Exported Function
`public: struct csf::edge::EnterpriseNetworkSensorStrategy & __thiscall csf::edge::EnterpriseNetworkSensorStrategy::operator=(struct csf::edge::EnterpriseNetworkSensorStrategy &&)` | 361 | Exported Function
`public: struct csf::edge::EnterpriseNetworkSensorStrategy & __thiscall csf::edge::EnterpriseNetworkSensorStrategy::operator=(struct csf::edge::EnterpriseNetworkSensorStrategy const &)` | 362 | Exported Function
`public: struct csf::dns::DnsQueryResult & __thiscall csf::dns::DnsQueryResult::operator=(struct csf::dns::DnsQueryResult &&)` | 347 | Exported Function
`public: static void __cdecl csf::netutils::GlobalEdgeStateController::reset(void)` | 952 | Exported Function
`public: static void __cdecl csf::netutils::GlobalEdgeStateController::resetForTesting(void)` | 958 | Exported Function
`public: static void __cdecl csf::netutils::GlobalEdgeStateController::clearCache(void)` | 637 | Exported Function
`public: static void __cdecl csf::netutils::GlobalEdgeStateController::init(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,bool,bool)` | 838 | Exported Function
`public: static void __cdecl csf::netutils::NetworkEventReporterImpl::stop(void)` | 1039 | Exported Function
`public: static void __cdecl csf::netutils::NetworkEventReporterObserver::resetForTesting(void)` | 959 | Exported Function
`public: static void __cdecl csf::netutils::NetworkEventReporterImpl::disableNetworkEventReporterForTesting(void)` | 682 | Exported Function
`public: static void __cdecl csf::netutils::NetworkEventReporterImpl::enableNetworkEventReporterForTesting(void)` | 687 | Exported Function
`public: static void __cdecl csf::common::DefaultPoliciesStore::reset(void)` | 951 | Exported Function
`public: static void __cdecl csf::common::DefaultPoliciesStore::setPolicy(class std::shared_ptr<class csf::common::Policy>)` | 1009 | Exported Function
`public: static void __cdecl csf::common::DefaultPoliciesStore::registerForDefaultPoliciesChanges(class std::weak_ptr<class csf::common::DefaultPoliciesStoreObserver>)` | 937 | Exported Function
`public: static void __cdecl csf::common::DefaultPoliciesStore::removePolicy(enum csf::common::Policy::PolicyNature::Nature)` | 944 | Exported Function
`public: static void __cdecl csf::http::CurlHttpUtils::closeFile(struct _iobuf * *)` | 645 | Exported Function
`public: static void __cdecl csf::http::CurlHttpUtils::logOperationTiming(class std::shared_ptr<class csf::http::HttpRequestData>)` | 895 | Exported Function
`public: static void __cdecl csf::common::DefaultPoliciesStore::unregister(class std::weak_ptr<class csf::common::DefaultPoliciesStoreObserver>)` | 1057 | Exported Function
`public: static void __cdecl csf::edge::EdgeInfrastructureEventController::setInstance(class std::shared_ptr<class csf::edge::EdgeInfrastructureEventController>)` | 996 | Exported Function
`public: static void __cdecl csf::netutils::SNIUtil::setEdgeDomain(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 984 | Exported Function
`public: struct csf::cert::CertResult __thiscall csf::cert::XmppCertVerifier::verifyXmppCertificate(struct x509_store_ctx_st const *,class std::vector<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> >,class std::allocator<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > > > const &)` | 1076 | Exported Function
`public: struct csf::cert::CertResult __thiscall csf::cert::XmppCertVerifier::verifyXmppCertificate(struct x509_store_ctx_st const *,class std::vector<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> >,class std::allocator<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > > > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 1077 | Exported Function
`public: struct csf::cert::CertResult __thiscall csf::cert::XmppCertVerifier::verifyXmppCertificate(struct x509_st const *,class std::vector<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> >,class std::allocator<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > > > const &)` | 1074 | Exported Function
`public: struct csf::cert::CertResult __thiscall csf::cert::XmppCertVerifier::verifyXmppCertificate(struct x509_st const *,class std::vector<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> >,class std::allocator<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > > > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 1075 | Exported Function
`public: struct csf::cert::InvalidCertNotificationManager::PromptDecision & __thiscall csf::cert::InvalidCertNotificationManager::PromptDecision::operator=(struct csf::cert::InvalidCertNotificationManager::PromptDecision &&)` | 412 | Exported Function
`public: struct csf::cert::InvalidCertNotificationManager::PromptDecision & __thiscall csf::cert::InvalidCertNotificationManager::PromptDecision::operator=(struct csf::cert::InvalidCertNotificationManager::PromptDecision const &)` | 413 | Exported Function
`public: struct csf::cert::InvalidCertNotificationManager::AcceptanceOptions & __thiscall csf::cert::InvalidCertNotificationManager::AcceptanceOptions::operator=(struct csf::cert::InvalidCertNotificationManager::AcceptanceOptions &&)` | 303 | Exported Function
`public: struct csf::cert::InvalidCertNotificationManager::AcceptanceOptions & __thiscall csf::cert::InvalidCertNotificationManager::AcceptanceOptions::operator=(struct csf::cert::InvalidCertNotificationManager::AcceptanceOptions const &)` | 304 | Exported Function
`public: struct csf::cert::CertEncoding & __thiscall csf::cert::CertEncoding::operator=(struct csf::cert::CertEncoding &&)` | 317 | Exported Function
`public: struct csf::cert::CertEncoding & __thiscall csf::cert::CertEncoding::operator=(struct csf::cert::CertEncoding const &)` | 318 | Exported Function
`public: struct csf::cert::CertAcceptanceDecision & __thiscall csf::cert::CertAcceptanceDecision::operator=(struct csf::cert::CertAcceptanceDecision &&)` | 311 | Exported Function
`public: struct csf::cert::CertAcceptanceDecision & __thiscall csf::cert::CertAcceptanceDecision::operator=(struct csf::cert::CertAcceptanceDecision const &)` | 312 | Exported Function
`public: struct csf::cert::CertKeyUsageResult & __thiscall csf::cert::CertKeyUsageResult::operator=(struct csf::cert::CertKeyUsageResult &&)` | 321 | Exported Function
`public: struct csf::cert::CertKeyUsageResult & __thiscall csf::cert::CertKeyUsageResult::operator=(struct csf::cert::CertKeyUsageResult const &)` | 322 | Exported Function
`public: struct csf::cert::CertKeyStrengthResult & __thiscall csf::cert::CertKeyStrengthResult::operator=(struct csf::cert::CertKeyStrengthResult &&)` | 319 | Exported Function
`public: struct csf::cert::CertKeyStrengthResult & __thiscall csf::cert::CertKeyStrengthResult::operator=(struct csf::cert::CertKeyStrengthResult const &)` | 320 | Exported Function
`public: static class std::shared_ptr<class csf::common::Policy> const csf::common::Policy::UNKNOWN_POLICY` | 568 | Exported Function
`public: enum csf::edge::EdgeConfigResponse::Result __thiscall csf::edge::EdgeConfigResponse::parse(class csf::edge::EdgeConfig &)` | 923 | Exported Function
`public: enum csf::http::CommonCriteriaUsagePolicy::PolicyValue::Value __thiscall csf::http::CommonCriteriaUsagePolicy::getValue(void)const ` | 823 | Exported Function
`public: enum csf::common::Policy::PolicyNature::Nature __thiscall csf::common::Policy::getNature(void)const ` | 790 | Exported Function
`public: enum csf::dns::DnsQueryType __thiscall csf::dns::QueryResponse::getType(void)const ` | 820 | Exported Function
`public: enum csf::http::HttpClientResult::Result __thiscall csf::http::HttpRequestData::enforceIpFamilyPreferencePolicy(void)` | 699 | Exported Function
`public: enum csf::http::SystemProxyUsagePolicy::PolicyValue::Value __thiscall csf::http::SystemProxyUsagePolicy::getValue(void)const ` | 828 | Exported Function
`public: enum csf::http::EdgePolicy::PolicyValue::Value __thiscall csf::http::EdgePolicy::getValue(void)` | 825 | Exported Function
`public: enum csf::http::HttpClientResult::Result __thiscall csf::http::HttpRequestData::enforceCommonCriteriaUsagePolicy(void)` | 698 | Exported Function
`public: enum csf::common::Policy::PolicyEnforcingResult::EnforcingResult __thiscall csf::edge::EdgeCapabilityPolicy::enforce(bool &)const ` | 690 | Exported Function
`public: enum csf::common::Policy::PolicyEnforcingResult::EnforcingResult __thiscall csf::http::CommonCriteriaUsagePolicy::enforce(void *)const ` | 689 | Exported Function
`public: enum csf::common::Policy::PolicyEnforcingResult::EnforcingResult __thiscall csf::cert::UserInteractingInvalidCertManagementPolicy::enforceWithoutUserInteraction(class std::set<enum csf::cert::CertStatus::Status,struct std::less<enum csf::cert::CertStatus::Status>,class std::allocator<enum csf::cert::CertStatus::Status> > const &,class std::set<enum csf::cert::CertStatus::Status,struct std::less<enum csf::cert::CertStatus::Status>,class std::allocator<enum csf::cert::CertStatus::Status> > const &,bool &)const ` | 700 | Exported Function
`public: enum csf::common::Policy::PolicyEnforcingResult::EnforcingResult __thiscall csf::common::FailureManagementPolicy::enforce(class csf::common::Policy const &,bool &)const ` | 693 | Exported Function
`public: enum csf::common::Policy::PolicyEnforcingResult::EnforcingResult __thiscall csf::http::SystemProxyUsagePolicy::enforce(class std::shared_ptr<class csf::http::Proxy> &)const ` | 696 | Exported Function
`public: enum csf::common::Policy::PolicyEnforcingResult::EnforcingResult __thiscall csf::ip::IpFamilyPreferencePolicy::enforce(void *)const ` | 695 | Exported Function
`public: enum csf::common::Policy::PolicyEnforcingResult::EnforcingResult __thiscall csf::http::EdgePolicy::enforce(class std::shared_ptr<class csf::http::HttpRequestData>,class std::shared_ptr<class csf::http::EdgeTransformer>)const ` | 692 | Exported Function
`public: enum csf::common::Policy::PolicyEnforcingResult::EnforcingResult __thiscall csf::http::EdgePolicy::enforce(struct csf::http::Response &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::shared_ptr<class csf::http::EdgeTransformer>)const ` | 691 | Exported Function
`public: enum csf::ip::IpFamilyPreferencePolicy::PolicyValue::Value __thiscall csf::ip::IpFamilyPreferencePolicy::getValue(void)const ` | 827 | Exported Function
`public: static bool __cdecl csf::common::FipsUtils::isFipsEnabled(void)` | 854 | Exported Function
`public: static bool __cdecl csf::http::CurlHttpUtils::addOauthToken(class std::shared_ptr<class csf::http::HttpRequestData>)` | 581 | Exported Function
`public: static bool __cdecl csf::cert::CertStatus::representsVerificationSuccess(class std::set<enum csf::cert::CertStatus::Status,struct std::less<enum csf::cert::CertStatus::Status>,class std::allocator<enum csf::cert::CertStatus::Status> > const &)` | 950 | Exported Function
`public: static bool __cdecl csf::cert::Win32CertVerifier::loadCertificateChain(struct _CERT_CONTEXT const *,struct _CERT_CHAIN_CONTEXT const * &)` | 894 | Exported Function
`public: static bool __cdecl csf::http::CurlHttpUtils::getIpAddress(class std::shared_ptr<class csf::http::HttpRequestData>)` | 779 | Exported Function
`public: static bool __cdecl csf::http::CurlHttpUtils::getResponseCode(class csf::http::HttpRequestData *)` | 811 | Exported Function
`public: static bool __cdecl csf::http::CurlHttpUtils::configureEasyRequest(class std::shared_ptr<class csf::http::HttpRequestData>)` | 646 | Exported Function
`public: static bool __cdecl csf::http::CurlHttpUtils::configureMultiformRequest(class std::shared_ptr<class csf::http::HttpRequestData>)` | 647 | Exported Function
`public: int __thiscall csf::common::Reactor::getCountEventsProcessed(void)const ` | 748 | Exported Function
`public: int __thiscall csf::edge::RecentlyUsedServers::getErrorCode(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 766 | Exported Function
`public: int __thiscall csf::common::Reactor::getCountEventsDequeued(void)const ` | 746 | Exported Function
`public: int __thiscall csf::common::Reactor::getCountEventsEnqueued(void)const ` | 747 | Exported Function
`public: static bool __cdecl csf::cert::CertificateValidityCache::findInAcceptedValidCache(struct x509_st const *)` | 725 | Exported Function
`public: static bool __cdecl csf::cert::CertificateValidityCache::verifyAcceptedCertificate(struct x509_st const *)` | 1064 | Exported Function
`public: long __thiscall csf::common::Cookie::getExpirationDate(void)const ` | 767 | Exported Function
`public: static bool __cdecl csf::cert::CertificateValidityCache::findInAcceptedValidCache(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 724 | Exported Function
`public: enum csf::common::FailureManagementPolicy::PolicyValue::Value __thiscall csf::common::FailureManagementPolicy::getValue(void)` | 826 | Exported Function
`public: class std::shared_ptr<class csf::http::HttpClientData> __thiscall std::enable_shared_from_this<class csf::http::HttpClientData>::shared_from_this(void)` | 1030 | Exported Function
`public: class std::shared_ptr<class csf::http::HttpClientListener> __thiscall csf::http::Request::getListener(void)const ` | 783 | Exported Function
`public: class std::shared_ptr<class csf::http::EasyCURLConnection> __thiscall csf::http::HttpRequestData::getCurlConnection(void)` | 750 | Exported Function
`public: class std::shared_ptr<class csf::http::HttpClientData const > __thiscall std::enable_shared_from_this<class csf::http::HttpClientData>::shared_from_this(void)const ` | 1031 | Exported Function
`public: class std::shared_ptr<class csf::http::MultiHttpClient> __thiscall csf::netutils::NetUtilsFactory::createMultiHttpClient(unsigned int)` | 666 | Exported Function
`public: class std::shared_ptr<class csf::http::Proxy> __thiscall csf::http::Request::getProxy(void)const ` | 805 | Exported Function
`public: class std::shared_ptr<class csf::http::HttpRequestData> __thiscall csf::http::MultiHttpClientData::getHttpRequestData(void)` | 773 | Exported Function
`public: class std::shared_ptr<class csf::http::MultiHttpClient> __thiscall csf::netutils::NetUtilsFactory::createMultiHttpClient(class std::shared_ptr<class csf::cert::CertVerifier>,unsigned int)` | 667 | Exported Function
`public: class std::shared_ptr<class csf::http::BasicHttpClient> __thiscall csf::netutils::NetUtilsFactory::createBasicHttpClient(class std::shared_ptr<class csf::cert::CertVerifier>)` | 653 | Exported Function
`public: class std::shared_ptr<class csf::http::BasicHttpClient> __thiscall csf::netutils::NetUtilsFactory::createBasicHttpClient(class std::shared_ptr<class csf::ThreadPool>)` | 654 | Exported Function
`public: class std::shared_ptr<class csf::edge::NetworkSensingEventRegistrator const > __thiscall std::enable_shared_from_this<class csf::edge::NetworkSensingEventRegistrator>::shared_from_this(void)const ` | 1033 | Exported Function
`public: class std::shared_ptr<class csf::edge::NetworkSensingEventRegistrator> __thiscall std::enable_shared_from_this<class csf::edge::NetworkSensingEventRegistrator>::shared_from_this(void)` | 1032 | Exported Function
`public: class std::shared_ptr<class csf::http::EasyCURLConnection> __thiscall csf::http::BasicHttpClientImpl::getEasyCURLConnection(void)` | 759 | Exported Function
`public: class std::shared_ptr<class csf::http::EasyCURLConnection> __thiscall csf::http::HttpClientData::getEasyCURLConnection(void)` | 760 | Exported Function
`public: class std::shared_ptr<class csf::http::BasicHttpClient> __thiscall csf::netutils::NetUtilsFactory::createBasicHttpClient(void)` | 655 | Exported Function
`public: class std::shared_ptr<class csf::http::CurlAnswerEvaluator> __thiscall csf::http::HttpClientData::getCurlAnswerEvaluator(void)` | 749 | Exported Function
`public: class std::shared_ptr<class csf::netutils::NetworkEventReporter> __thiscall csf::netutils::NetUtilsFactory::createNetworkEventReporter(void)` | 669 | Exported Function
`public: class std::weak_ptr<class csf::dns::DnsQuery> __thiscall std::enable_shared_from_this<class csf::dns::DnsQuery>::weak_from_this(void)` | 1081 | Exported Function
`public: class std::weak_ptr<class csf::edge::NetworkSensingEventRegistrator const > __thiscall std::enable_shared_from_this<class csf::edge::NetworkSensingEventRegistrator>::weak_from_this(void)const ` | 1086 | Exported Function
`public: class std::vector<unsigned char,class std::allocator<unsigned char> > __thiscall csf::ip::Nat64PrefixParser::getPrefix(void)const ` | 804 | Exported Function
`public: class std::weak_ptr<class csf::dns::DnsQuery const > __thiscall std::enable_shared_from_this<class csf::dns::DnsQuery>::weak_from_this(void)const ` | 1082 | Exported Function
`public: class std::weak_ptr<class csf::http::HttpClientData> __thiscall std::enable_shared_from_this<class csf::http::HttpClientData>::weak_from_this(void)` | 1083 | Exported Function
`public: enum csf::cert::InvalidCertNotificationManager::PromptDecision::Decision __thiscall csf::cert::InvalidCertNotificationManager::promptUserForAction(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::set<enum csf::cert::CertStatus::Status,struct std::less<enum csf::cert::CertStatus::Status>,class std::allocator<enum csf::cert::CertStatus::Status> >,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::vector<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> >,class std::allocator<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > > > const` | 928 | Exported Function
`public: class std::weak_ptr<class csf::edge::NetworkSensingEventRegistrator> __thiscall std::enable_shared_from_this<class csf::edge::NetworkSensingEventRegistrator>::weak_from_this(void)` | 1085 | Exported Function
`public: class std::weak_ptr<class csf::http::HttpClientData const > __thiscall std::enable_shared_from_this<class csf::http::HttpClientData>::weak_from_this(void)const ` | 1084 | Exported Function
`public: class std::vector<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> >,class std::allocator<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > > > __thiscall csf::edge::EdgeConfig::getSipRoutes(void)const ` | 815 | Exported Function
`public: class std::vector<struct csf::edge::EdgeServiceRecordData,class std::allocator<struct csf::edge::EdgeServiceRecordData> > __thiscall csf::edge::ReachableEdgeServerManager::getEdgeServiceRecordData(class std::vector<struct csf::edge::EdgeServiceRecordData,class std::allocator<struct csf::edge::EdgeServiceRecordData> > const &)` | 764 | Exported Function
`public: class std::shared_ptr<struct csf::http::HttpRequestOptions> __thiscall csf::http::Request::getOptions(void)const ` | 796 | Exported Function
`public: class std::vector<class csf::common::Cookie,class std::allocator<class csf::common::Cookie> > __thiscall csf::edge::EdgeConfig::getCookies(void)const ` | 745 | Exported Function
`public: class std::vector<struct csf::http::FailedUrlInfo,class std::allocator<struct csf::http::FailedUrlInfo> > __thiscall csf::http::HttpRequestData::getFailedUrlInfo(void)` | 768 | Exported Function
`public: class std::vector<unsigned char,class std::allocator<unsigned char> > __thiscall csf::ip::IpAddress::getBytes(void)const ` | 737 | Exported Function
`public: class std::vector<struct csf::edge::EdgeServiceRecordData,class std::allocator<struct csf::edge::EdgeServiceRecordData> > __thiscall csf::edge::ReachableEdgeServerManager::getOrderedListOfUpdatedEdgeHosts(class std::vector<struct csf::edge::EdgeServiceRecordData,class std::allocator<struct csf::edge::EdgeServiceRecordData> > const &,class std::vector<struct csf::edge::EdgeServiceRecordData,class std::allocator<struct csf::edge::EdgeServiceRecordData> > const &)` | 797 | Exported Function
`public: class std::vector<struct csf::edge::OnPremService,class std::allocator<struct csf::edge::OnPremService> > __thiscall csf::edge::EdgeConfig::getOnPremServices(void)const ` | 794 | Exported Function
`public: static bool __cdecl csf::http::CurlHttpUtils::isFileProtocol(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> >)` | 853 | Exported Function
`public: static class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __cdecl csf::netutils::SNIUtil::getServerNameForSNI(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 813 | Exported Function
`public: static class std::set<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> >,struct std::less<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > >,class std::allocator<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > > > __cdecl csf::cert::CertificateValidityCache::getAcceptedValidFingerprints(void)` | 730 | Exported Function
`public: static class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __cdecl csf::ip::IpUtils::appendPortToAddress(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,unsigned int)` | 593 | Exported Function
`public: static class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __cdecl csf::ip::IpUtils::appendPortToAddress(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,unsigned short)` | 592 | Exported Function
`public: static class std::set<enum csf::cert::CertStatus::Status,struct std::less<enum csf::cert::CertStatus::Status>,class std::allocator<enum csf::cert::CertStatus::Status> > __cdecl csf::cert::CertificateValidityCache::getRejectedInvalidCacheValue(struct x509_st const *)` | 809 | Exported Function
`public: static class std::set<enum csf::cert::CertStatus::Status,struct std::less<enum csf::cert::CertStatus::Status>,class std::allocator<enum csf::cert::CertStatus::Status> > __cdecl csf::cert::Win32CertVerifier::convertCertificateVerificationError(unsigned long)` | 649 | Exported Function
`public: static class std::set<class std::shared_ptr<class csf::common::Policy>,struct std::less<class std::shared_ptr<class csf::common::Policy> >,class std::allocator<class std::shared_ptr<class csf::common::Policy> > > const __cdecl csf::common::DefaultPoliciesStore::getAllPolicies(void)` | 733 | Exported Function
`public: static class std::set<enum csf::cert::CertStatus::Status,struct std::less<enum csf::cert::CertStatus::Status>,class std::allocator<enum csf::cert::CertStatus::Status> > __cdecl csf::cert::CertificateValidityCache::getAcceptedInvalidCacheValue(struct x509_st const *)` | 729 | Exported Function
`public: static class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __cdecl csf::http::HttpUtils::extractFullDomainFromHttpUrl(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 718 | Exported Function
`public: static class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __cdecl csf::http::HttpUtils::extractHostFromHttpUrl(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 719 | Exported Function
`public: static class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __cdecl csf::http::HttpUtils::extractFilenameFromHttpUrl(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 716 | Exported Function
`public: static class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __cdecl csf::http::HttpUtils::extractFqdnFromStr(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 717 | Exported Function
`public: static class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __cdecl csf::http::HttpUtils::extractRequestFromHttpUrl(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 723 | Exported Function
`public: static class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __cdecl csf::http::HttpUtils::getProxyFromList(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::vector<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> >,class std::allocator<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > > > const &)` | 807 | Exported Function
`public: static class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __cdecl csf::http::HttpUtils::extractHostnameFromStr(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 720 | Exported Function
`public: static class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __cdecl csf::http::HttpUtils::extractProtocolFromHttpUrl(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 722 | Exported Function
`public: static class std::shared_ptr<class csf::cert::CertVerifier> __cdecl csf::cert::CertVerifierFactory::createCertVerifier(void)` | 656 | Exported Function
`public: static class std::shared_ptr<class csf::common::Policy> const csf::cert::PersistInvalidCertDecisionPolicy::DO_NOT_PERSIST_DECISION_POLICY` | 546 | Exported Function
`public: static class std::shared_ptr<class csf::common::Policy> const csf::cert::PersistInvalidCertDecisionPolicy::PERSIST_DECISION_POLICY` | 565 | Exported Function
`public: static class std::shared_ptr<class csf::common::Policy> const csf::cert::InvalidCertManagementPolicy::SILENTLY_FAIL_POLICY` | 566 | Exported Function
`public: static class std::shared_ptr<class csf::common::Policy> const csf::cert::InvalidCertManagementPolicy::SILENTLY_SUCCEED_POLICY` | 567 | Exported Function
`public: static class std::shared_ptr<class csf::common::Policy> const csf::common::FailureManagementPolicy::IGNORE_SOFT_FAILURE_POLICY` | 555 | Exported Function
`public: static class std::shared_ptr<class csf::common::Policy> const csf::common::FailureManagementPolicy::NEVER_IGNORE_FAILURE_POLICY` | 562 | Exported Function
`public: static class std::shared_ptr<class csf::common::Policy> const csf::common::FailureManagementPolicy::ALWAYS_IGNORE_FAILURE_POLICY` | 537 | Exported Function
`public: static class std::shared_ptr<class csf::common::Policy> const csf::common::FailureManagementPolicy::IGNORE_HARD_FAILURE_POLICY` | 553 | Exported Function
`public: static class std::shared_ptr<class csf::cert::XmppCertVerifier> __cdecl csf::cert::CertVerifierFactory::createXmppCertVerifier(void)` | 674 | Exported Function
`public: static class std::shared_ptr<class csf::common::Policy> const __cdecl csf::common::DefaultPoliciesStore::getPolicy(enum csf::common::Policy::PolicyNature::Nature)` | 801 | Exported Function
`public: static class std::shared_ptr<class csf::cert::InvalidCertNotificationManager> __cdecl csf::cert::InvalidCertNotificationManager::getInstance(void)` | 775 | Exported Function
`public: static class std::shared_ptr<class csf::cert::PlatformCertVerifier> __cdecl csf::cert::PlatformCertVerifier::createInstance(void)` | 661 | Exported Function
`public: static class std::shared_ptr<class csf::common::Policy> const csf::cert::IgnoreInvalidCertConditionPolicy::IGNORE_WEAK_KEY_ERRORS_POLICY` | 556 | Exported Function
`public: static class std::shared_ptr<class csf::common::Policy> const csf::cert::IgnoreInvalidCertConditionPolicy::IGNORE_WRONG_KEY_USAGE_ERRORS_POLICY` | 557 | Exported Function
`public: static class std::shared_ptr<class csf::common::Policy> const csf::cert::IgnoreInvalidCertConditionPolicy::DO_NOT_IGNORE_FALURE_CONDITIONS_POLICY` | 545 | Exported Function
`public: static class std::shared_ptr<class csf::common::Policy> const csf::cert::IgnoreInvalidCertConditionPolicy::IGNORE_REVOCATION_INFO_UNAVAILABLE_ERRORS_POLICY` | 554 | Exported Function
`public: static class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __cdecl csf::http::HttpUtils::extractBaseUrlFromHttpUrl(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 715 | Exported Function
`public: static bool __cdecl csf::ip::HostnameValidator::isValidHostname(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 885 | Exported Function
`public: static bool __cdecl csf::ip::IpUtils::getIpAddressesFromCurl(void *,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > &)` | 780 | Exported Function
`public: static bool __cdecl csf::http::CurlHttpUtils::storeCookies(class std::shared_ptr<class csf::http::HttpRequestData>)` | 1041 | Exported Function
`public: static bool __cdecl csf::http::HttpUtils::checkUrlForIpV6(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 631 | Exported Function
`public: static bool __cdecl csf::ip::IpUtils::isIpv6Address(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 863 | Exported Function
`public: static bool __cdecl csf::netutils::GlobalEdgeStateController::isInitialized(void)` | 855 | Exported Function
`public: static bool __cdecl csf::ip::IpUtils::isIpAddress(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 857 | Exported Function
`public: static bool __cdecl csf::ip::IpUtils::isIpv4Address(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 861 | Exported Function
`public: static bool __cdecl csf::http::CurlHttpUtils::isValidCurlString(char *,unsigned int,unsigned int)` | 884 | Exported Function
`public: static bool __cdecl csf::http::CurlHttpUtils::resetCurlPassword(class std::shared_ptr<class csf::http::HttpRequestData>)` | 955 | Exported Function
`public: static bool __cdecl csf::http::CurlHttpUtils::isResponseSuccessful(int)` | 876 | Exported Function
`public: static bool __cdecl csf::http::CurlHttpUtils::isSetOptError(enum CURLcode,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 881 | Exported Function
`public: static bool __cdecl csf::http::CurlHttpUtils::setHeadersFromHttpRequestData(class std::shared_ptr<class csf::http::HttpRequestData>)` | 992 | Exported Function
`public: static bool __cdecl csf::http::CurlHttpUtils::setUrl(class std::shared_ptr<class csf::http::HttpRequestData>)` | 1023 | Exported Function
`public: static bool __cdecl csf::http::CurlHttpUtils::setCookieMandatory(class std::shared_ptr<class csf::http::HttpRequestData>)` | 976 | Exported Function
`public: static bool __cdecl csf::http::CurlHttpUtils::setCookies(class std::shared_ptr<class csf::http::HttpRequestData>)` | 977 | Exported Function
`public: static bool __cdecl csf::netutils::GlobalEdgeStateController::isIpAddressChanged(void)` | 858 | Exported Function
`public: static class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __cdecl csf::http::CurlHttpUtils::getResolvedIp(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 810 | Exported Function
`public: static class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __cdecl csf::http::CurlHttpUtils::getSslVersion(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 817 | Exported Function
`public: static class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __cdecl csf::edge::EdgeConfigRequestImpl::createRequestUrl(struct csf::edge::EdgeConfigParams const &)` | 670 | Exported Function
`public: static class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __cdecl csf::http::CurlHttpUtils::getCipherSuite(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 740 | Exported Function
`public: static class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __cdecl csf::http::CurlHttpUtils::normalizeIp(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 906 | Exported Function
`public: static class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __cdecl csf::http::HttpUtils::encodeForHttp(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 688 | Exported Function
`public: static class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __cdecl csf::http::CurlHttpUtils::loggableFilePath(class csf::http::RequestWrapper const &)` | 896 | Exported Function
`public: static class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __cdecl csf::http::CurlHttpUtils::loggableUrl(class std::shared_ptr<class csf::http::Request>)` | 897 | Exported Function
`public: static class csf::ip::IpAddress __cdecl csf::ip::IpAddress::createIpAddress(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 662 | Exported Function
`public: static class csf::ip::Ipv4Address __cdecl csf::ip::Ipv4Address::createIpv4Address(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 664 | Exported Function
`public: static bool __cdecl csf::netutils::SNIUtil::isMatchedWithEdgeDomain(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 866 | Exported Function
`public: static class csf::edge::Timestamp __cdecl csf::edge::Timestamp::never(void)` | 904 | Exported Function
`public: static class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __cdecl csf::cert::CertificateValidityCache::generateFingerprint(struct x509_st const *,struct env_md_st const *)` | 728 | Exported Function
`public: static class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __cdecl csf::cert::CertUtils::bytesToString(unsigned char const *,unsigned long)` | 623 | Exported Function
`public: static class csf::ip::Ipv6Address __cdecl csf::ip::Ipv6Address::createIpv6Address(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 665 | Exported Function
`public: static class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __cdecl csf::cert::CertificateValidityCache::generateFingerprint(struct x509_st const *)` | 727 | Exported Function
`public: struct csf::http::HttpClientError & __thiscall csf::http::HttpClientError::operator=(struct csf::http::HttpClientError const &)` | 371 | Exported Function
`public: void __thiscall csf::cert::InvalidCertNotificationManager::registerInvalidCertListener(class std::shared_ptr<class csf::cert::InvalidCertListener>)` | 939 | Exported Function
`public: void __thiscall csf::cert::InvalidCertNotificationManager::reportRejectedCert(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::set<enum csf::cert::CertStatus::Status,struct std::less<enum csf::cert::CertStatus::Status>,class std::allocator<enum csf::cert::CertStatus::Status> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::vector<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> >,class std::allocator<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > > > const &)` | 948 | Exported Function
`public: void __thiscall csf::cert::InvalidCertNotificationManager::clearForTesting(void)` | 642 | Exported Function
`public: void __thiscall csf::cert::InvalidCertNotificationManager::displayCertWarning(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::set<enum csf::cert::CertStatus::Status,struct std::less<enum csf::cert::CertStatus::Status>,class std::allocator<enum csf::cert::CertStatus::Status> >,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::vector<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> >,class std::allocator<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > > > const &,bool,class csf::cert::CertificateCacheAccessor const &)` | 683 | Exported Function
`public: void __thiscall csf::common::PolicySet::addPolicy(class std::shared_ptr<class csf::common::Policy>)` | 588 | Exported Function
`public: void __thiscall csf::common::PolicySet::removePolicy(enum csf::common::Policy::PolicyNature::Nature)` | 946 | Exported Function
`public: void __thiscall csf::common::BackgroundTimerImpl::killTimer(void)` | 887 | Exported Function
`public: void __thiscall csf::common::PolicySet::addAll(class std::set<class std::shared_ptr<class csf::common::Policy>,struct std::less<class std::shared_ptr<class csf::common::Policy> >,class std::allocator<class std::shared_ptr<class csf::common::Policy> > > const &)` | 577 | Exported Function
`public: virtual void __thiscall csf::netutils::NetworkEventReporterObserver::registerForNetworkEvents(class std::shared_ptr<class csf::netutils::NetworkEventCallback>)` | 938 | Exported Function
`public: void __thiscall csf::cert::BaseCertVerifier::setAltNameParserFactory(class std::shared_ptr<class csf::cert::AltNameParserFactory>)` | 965 | Exported Function
`public: virtual void __thiscall csf::netutils::adapters::Nat64PrefixChangeAdapter::onNetworkSensingEvent(struct csf::edge::NetworkSensingEvent const &)` | 918 | Exported Function
`public: virtual void __thiscall csf::netutils::NetworkEventReporterObserver::onNetworkEvent(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 917 | Exported Function
`public: void __thiscall csf::cert::BaseCertVerifier::setKeyStrengthParserFactory(class std::shared_ptr<class csf::cert::KeyStrengthParserFactory>)` | 1001 | Exported Function
`public: void __thiscall csf::cert::BaseCertVerifier::setKeyUsageParserFactory(class std::shared_ptr<class csf::cert::KeyUsageParserFactory>)` | 1002 | Exported Function
`public: void __thiscall csf::cert::BaseCertVerifier::setCertContainerFactory(class std::shared_ptr<class csf::cert::CertContainerFactory>)` | 970 | Exported Function
`public: void __thiscall csf::cert::BaseCertVerifier::setCertificateDataFactory(class std::shared_ptr<class csf::cert::CertificateDataFactory>)` | 972 | Exported Function
`public: void __thiscall csf::edge::EdgeConfig::addCookie(class csf::common::Cookie const &)` | 578 | Exported Function
`public: void __thiscall csf::edge::EdgeInfrastructureEventControllerImpl::setFailoverMonitoringWindowsInSeconds(unsigned int)` | 989 | Exported Function
`public: void __thiscall csf::edge::EdgeInfrastructureEventControllerImpl::setMinimumRefetchPeriodInSeconds(unsigned int)` | 1006 | Exported Function
`public: void __thiscall csf::edge::EdgeDetectionDnsRecordReader::setExternalDomainName(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 988 | Exported Function
`public: void __thiscall csf::edge::EdgeDetectionDnsRecordReader::setInternalDomainName(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 997 | Exported Function
`public: void __thiscall csf::edge::EdgeTransitionDetectionControllerImpl::getDetectDirectConnectUnavailableFsmStatistics(struct csf::edge::DetectDirectConnectUnavailableFsm::Statistics &)const ` | 755 | Exported Function
`public: void __thiscall csf::edge::EdgeTransitionDetectionControllerImpl::setDelayedSensingDelayForTestOnly(class std::chrono::duration<__int64,struct std::ratio<1,1000> > const &,class std::chrono::duration<__int64,struct std::ratio<1,1000> > const &,class std::chrono::duration<__int64,struct std::ratio<1,1000> > const &)` | 982 | Exported Function
`public: void __thiscall csf::edge::EdgeInfrastructureEventControllerImpl::start(void)` | 1035 | Exported Function
`public: void __thiscall csf::edge::EdgeTransitionDetectionControllerImpl::getDetectDirectConnectAvailableFsmStatistics(struct csf::edge::DetectDirectConnectAvailableFsm::Statistics &)const ` | 753 | Exported Function
`public: void __thiscall csf::edge::EdgeConfig::setHttpEdgeService(struct csf::edge::EdgeService const &)` | 993 | Exported Function
`public: void __thiscall csf::edge::EdgeConfig::setSipEdgeService(struct csf::edge::EdgeService const &)` | 1016 | Exported Function
`public: void __thiscall csf::edge::EdgeConfig::addOnPremService(struct csf::edge::OnPremService const &)` | 582 | Exported Function
`public: void __thiscall csf::edge::EdgeConfig::addSipRoute(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 590 | Exported Function
`public: void __thiscall csf::edge::EdgeDetectionControllerImpl::setEdgeServiceSensorExternal(class std::shared_ptr<class csf::edge::CollabEdgeServiceSensor>)` | 986 | Exported Function
`public: void __thiscall csf::edge::EdgeDetectionControllerImpl::setInternalNetworkSensor(class std::shared_ptr<class csf::edge::EnterpriseNetworkSensor>)` | 998 | Exported Function
`public: void __thiscall csf::edge::EdgeConfig::setTurnEdgeService(struct csf::edge::EdgeService const &)` | 1022 | Exported Function
`public: void __thiscall csf::edge::EdgeConfig::setXmppEdgeService(struct csf::edge::EdgeService const &)` | 1027 | Exported Function
`public: virtual void __thiscall csf::ip::Nat64PrefixImpl::setAlternativeWellKnownIpv4Name(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 966 | Exported Function
`public: virtual enum csf::http::EdgeTransformer::TransformRequestResult::Result __thiscall csf::netutils::adapters::EdgeUtilsAdapter::transformRequestUsingRequestOAuthToken(class std::shared_ptr<class csf::http::HttpRequestData>)` | 1054 | Exported Function
`public: virtual enum csf::http::EdgeTransformer::TransformRequestResult::Result __thiscall csf::netutils::adapters::EdgeUtilsAdapter::transformRequestUsingXEdgeAuth(class std::shared_ptr<class csf::http::HttpRequestData>)` | 1055 | Exported Function
`public: virtual enum csf::http::EdgeTransformer::TransformRequestResult::Result __thiscall csf::netutils::adapters::EdgeUtilsAdapter::transformRequest(class std::shared_ptr<class csf::http::HttpRequestData>)` | 1052 | Exported Function
`public: virtual enum csf::http::EdgeTransformer::TransformRequestResult::Result __thiscall csf::netutils::adapters::EdgeUtilsAdapter::transformRequestUsingEdgeTokenAndUnityCookie(class std::shared_ptr<class csf::http::HttpRequestData>)` | 1053 | Exported Function
`public: virtual struct x509_st const * __thiscall csf::cert::CertContainerImpl::getLeafCert(void)const ` | 782 | Exported Function
`public: virtual struct x509_store_ctx_st const * __thiscall csf::cert::CertContainerImpl::getCertChain(void)const ` | 739 | Exported Function
`public: virtual enum csf::http::HttpClientResult::Result __thiscall csf::http::CurlAnswerEvaluator::curlCodeToResult(enum CURLcode,class csf::http::HttpRequestData *)` | 675 | Exported Function
`public: virtual struct csf::edge::ServiceRecord __thiscall csf::edge::InternalNetworkVisibilityTester::getInternalServiceRecord(void)const ` | 778 | Exported Function
`public: virtual enum csf::cert::CertKeyUsageResult::Result __thiscall csf::cert::KeyUsageParserImpl::parse(struct x509_st const *)` | 925 | Exported Function
`public: virtual enum csf::cert::CertKeyUsageResult::Result __thiscall csf::cert::KeyUsageParserImpl::verifyBasicKeyUsage(class std::vector<enum csf::cert::BasicKeyUsage::Usage,class std::allocator<enum csf::cert::BasicKeyUsage::Usage> > const &)const ` | 1065 | Exported Function
`public: virtual enum csf::cert::CertKeyStrengthResult::Result __thiscall csf::cert::KeyStrengthParserImpl::parse(struct x509_st const *)` | 924 | Exported Function
`public: virtual enum csf::cert::CertKeyStrengthResult::Result __thiscall csf::cert::KeyStrengthParserImpl::verify(int)const ` | 1063 | Exported Function
`public: virtual enum csf::common::Policy::PolicyEnforcingResult::EnforcingResult __thiscall csf::cert::UserInteractingInvalidCertManagementPolicy::enforce(class std::set<enum csf::cert::CertStatus::Status,struct std::less<enum csf::cert::CertStatus::Status>,class std::allocator<enum csf::cert::CertStatus::Status> > &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::vector<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> >,class std::allocator<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > > > con` | 697 | Exported Function
`public: virtual enum csf::http::EdgeTransformer::TransformRequestResult::Result __thiscall csf::netutils::adapters::EdgeUtilsAdapter::removeTransformedCookies(struct csf::http::Response &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 947 | Exported Function
`public: virtual enum csf::cert::CertKeyUsageResult::Result __thiscall csf::cert::KeyUsageParserImpl::verifyExtendedKeyUsage(class std::vector<enum csf::cert::ExtendedKeyUsage::Usage,class std::allocator<enum csf::cert::ExtendedKeyUsage::Usage> > const &)const ` | 1070 | Exported Function
`public: virtual enum csf::common::Policy::PolicyEnforcingResult::EnforcingResult __thiscall csf::cert::InvalidCertManagementPolicy::enforce(class std::set<enum csf::cert::CertStatus::Status,struct std::less<enum csf::cert::CertStatus::Status>,class std::allocator<enum csf::cert::CertStatus::Status> > &,class std::shared_ptr<class csf::cert::CertificateData>)const ` | 694 | Exported Function
`public: virtual void __thiscall csf::cert::BaseCertVerifier::addPolicy(class std::shared_ptr<class csf::common::Policy>)` | 586 | Exported Function
`public: virtual void __thiscall csf::edge::EdgeDetectionControllerImpl::resetForTesting(void)` | 957 | Exported Function
`public: virtual void __thiscall csf::edge::EdgeDetectionControllerImpl::setDomains(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,bool)` | 983 | Exported Function
`public: virtual void __thiscall csf::common::Reactor::stop(void)` | 1040 | Exported Function
`public: virtual void __thiscall csf::edge::EdgeDetectionControllerImpl::registerVisibilityChangeObserver(class std::shared_ptr<class csf::edge::VisibilityChangeObserver>)` | 941 | Exported Function
`public: virtual void __thiscall csf::edge::NetworkSensingEventRegistrator::onTimer(void)` | 921 | Exported Function
`public: virtual void __thiscall csf::ip::Nat64PrefixImpl::clearCache(void)` | 638 | Exported Function
`public: virtual void __thiscall csf::edge::EdgeDetectionControllerImpl::setLastSucceededEdgeRecordAndServer(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,bool)` | 1003 | Exported Function
`public: virtual void __thiscall csf::edge::EdgeDetectionControllerImpl::terminateEdgeSession(void)` | 1046 | Exported Function
`public: virtual void __thiscall csf::common::BackgroundTimerImpl::onAppEvent(enum CSFSystemMonitor::AppStateEventTypeEnum::AppEventType)` | 914 | Exported Function
`public: virtual void __thiscall csf::common::BackgroundTimerImpl::onPowerEvent(enum CSFSystemMonitor::PowerEventTypeEnum::PowerEventType)` | 919 | Exported Function
`public: virtual void __thiscall csf::common::BackgroundTimer::cancelTimer(void)` | 626 | Exported Function
`public: virtual void __thiscall csf::common::BackgroundTimer::setTimer(class std::weak_ptr<class csf::common::BackgroundTimerCallback>,class std::chrono::duration<__int64,struct std::ratio<1,1> > const &)` | 1020 | Exported Function
`public: virtual void __thiscall csf::common::PolicyDriven::onDefaultPoliciesStoreUpdate(void)` | 915 | Exported Function
`public: virtual void __thiscall csf::common::PolicyDriven::removePolicy(enum csf::common::Policy::PolicyNature::Nature)` | 945 | Exported Function
`public: virtual void __thiscall csf::common::BackgroundTimerImpl::onTimer(void)` | 920 | Exported Function
`public: virtual void __thiscall csf::common::PolicyDriven::addPolicy(class std::shared_ptr<class csf::common::Policy>)` | 587 | Exported Function
`public: void __thiscall csf::edge::EdgeTransitionDetectionControllerImpl::setMockDirectConnectivityTester(class csf::edge::NetworkTester *)` | 1007 | Exported Function
`public: void __thiscall csf::http::Proxy::setProxyServer(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,enum csf::http::ProxyType::Type)` | 1013 | Exported Function
`public: void __thiscall csf::http::ProxyAuthenticationHandler::getProxyCredential(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > &,class csf::SecureString &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > &)` | 806 | Exported Function
`public: void __thiscall csf::http::Proxy::setAuthentication(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class csf::SecureString const &,enum csf::http::ProxyAuthentication::Type)` | 967 | Exported Function
`public: void __thiscall csf::http::Proxy::setBypassList(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> >)` | 968 | Exported Function
`public: void __thiscall csf::http::ProxyAuthenticationHandler::registerProxyAuthenticationCallback(class std::shared_ptr<class csf::http::ProxyAuthenticationCallback>)` | 940 | Exported Function
`public: void __thiscall csf::http::ProxyAuthenticationHandler::reset(void)` | 953 | Exported Function
`public: void __thiscall csf::http::ProxyAuthenticationHandler::handleProxyAuthRequired(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,bool,class std::function<void __cdecl(void)>,class std::function<void __cdecl(void)>)` | 832 | Exported Function
`public: void __thiscall csf::http::ProxyAuthenticationHandler::initProxyCredential(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class csf::SecureString const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 839 | Exported Function
`public: void __thiscall csf::http::HttpRequestData::switchToNextUrl(enum csf::http::HttpClientResult::Result)` | 1044 | Exported Function
`public: void __thiscall csf::http::MultiformRequest::addPartFromBuffer(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,char const *,unsigned int,class std::shared_ptr<class std::vector<struct std::pair<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> >,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > >,class std::allocator<struct std::pair<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> >,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > > > > >)` | 583 | Exported Function
`public: void __thiscall csf::http::HttpRequestData::setIpFamilyPreferencePolicy(class std::shared_ptr<class csf::ip::IpFamilyPreferencePolicy>)` | 999 | Exported Function
`public: void __thiscall csf::http::HttpRequestData::setIpFamilyPreferencePolicyCanBeIgnored(bool)` | 1000 | Exported Function
`public: void __thiscall csf::http::MultiHttpClientData::provideEasyCURLConnection(void)` | 930 | Exported Function
`public: void __thiscall csf::http::MultiHttpClientImpl::setCurlAnswerEvaluator(class std::shared_ptr<class csf::http::CurlAnswerEvaluator>)` | 980 | Exported Function
`public: void __thiscall csf::http::MultiformRequest::addPartFromFile(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::shared_ptr<class std::vector<struct std::pair<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> >,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > >,class std::allocator<struct std::pair<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> >,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > > > > >)` | 584 | Exported Function
`public: void __thiscall csf::http::MultiformRequest::addPartFromString(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::shared_ptr<class std::vector<struct std::pair<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> >,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > >,class std::allocator<struct std::pair<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> >,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > > > > >)` | 585 | Exported Function
`public: void __thiscall csf::http::ProxyAuthenticationHandler::setProxyCredential(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class csf::SecureString const &)` | 1012 | Exported Function
`public: void __thiscall csf::netutils::adapters::EdgeHttpAdapter::setCustomHttpClientForTesting(class std::shared_ptr<class csf::http::BasicHttpClient>)` | 981 | Exported Function
`void * __cdecl csf::netutils::libcurl_calloc_callback(unsigned int,unsigned int)` | 888 | Exported Function
`public: void __thiscall csf::http::UnresolvedHostCache::clear(void)` | 633 | Exported Function
`public: void __thiscall csf::http::UnresolvedHostCache::setTimeoutInSec(unsigned int)` | 1019 | Exported Function
`void __cdecl csf::netutils::GlobalCleanup(void)` | 550 | Exported Function
`void __cdecl csf::netutils::libcurl_free_callback(void *)` | 889 | Exported Function
`void * __cdecl csf::netutils::libcurl_malloc_callback(unsigned int)` | 890 | Exported Function
`void * __cdecl csf::netutils::libcurl_realloc_callback(void *,unsigned int)` | 891 | Exported Function
`public: void __thiscall csf::http::Request::setListener(class std::shared_ptr<class csf::http::HttpClientListener>)` | 1005 | Exported Function
`public: void __thiscall csf::http::Request::setProxy(class std::shared_ptr<class csf::http::Proxy>)` | 1011 | Exported Function
`public: void __thiscall csf::http::ProxyAuthenticationHandler::updateProxyInfo(bool,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> >)` | 1059 | Exported Function
`public: void __thiscall csf::http::Request::cancel(void)` | 625 | Exported Function
`public: void __thiscall csf::http::Request::waitUntilProxyCredentialReady(bool)` | 1080 | Exported Function
`public: void __thiscall csf::http::SystemProxyResolver::setHttpProxyConfigurationReader(class std::shared_ptr<class csf::http::HttpProxyConfigurationReader>)` | 994 | Exported Function
`public: void __thiscall csf::http::Request::setSystemProxyResolver(class std::shared_ptr<class csf::http::SystemProxyResolver>)` | 1017 | Exported Function
`public: void __thiscall csf::http::Request::useSystemProxy(bool)` | 1060 | Exported Function
`public: void __thiscall csf::http::HttpRequestData::setFailoverUrls(class std::deque<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> >,class std::allocator<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > > > const &)` | 990 | Exported Function
`public: void __thiscall csf::edge::ReachableEdgeServerManager::reset(void)` | 954 | Exported Function
`public: void __thiscall csf::edge::ReachableEdgeServerManager::setLastSucceededEdgeRecordAndServer(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,bool)` | 1004 | Exported Function
`public: void __thiscall csf::edge::PolicyDrivenEdgeVisibility::setVisible(bool)` | 1026 | Exported Function
`public: void __thiscall csf::edge::ReachableEdgeServerManager::clearCache(void)` | 639 | Exported Function
`public: void __thiscall csf::edge::RecentlyUsedServers::clearCache(void)` | 640 | Exported Function
`public: void __thiscall csf::edge::RecentlyUsedServers::clearCachedEdgeConfig(void)` | 641 | Exported Function
`public: void __thiscall csf::edge::ReachableEdgeServerManager::terminateEdgeSession(void)` | 1047 | Exported Function
`public: void __thiscall csf::edge::RecentlyUsedServers::clearAll(void)` | 636 | Exported Function
`public: void __thiscall csf::edge::GlobalEdgeStateImpl::setRefreshTimerFireTime(long)` | 1015 | Exported Function
`public: void __thiscall csf::edge::GlobalEdgeStateImpl::setTokenRefreshTimeRate(float)` | 1021 | Exported Function
`public: void __thiscall csf::edge::EdgeTransitionDetectionControllerImpl::setMockInternalNetworkVisibilityTester(class csf::edge::InternalNetworkVisibilityTester *)` | 1008 | Exported Function
`public: void __thiscall csf::edge::GlobalEdgeStateImpl::setRecentlyUsedServers(class std::shared_ptr<class csf::edge::RecentlyUsedServers>)` | 1014 | Exported Function
`public: void __thiscall csf::edge::IpInterfaceChangeMonitor::stop(void)` | 1038 | Exported Function
`public: void __thiscall csf::edge::PolicyDrivenEdgeVisibility::setPolicyDriver(class std::weak_ptr<class csf::common::PolicyDriven>)` | 1010 | Exported Function
`public: void __thiscall csf::edge::IpInterfaceChangeLocalAddress::addLocalIPAddress(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 580 | Exported Function
`public: void __thiscall csf::edge::IpInterfaceChangeMonitor::start(void)` | 1036 | Exported Function
`public: void __thiscall csf::edge::RecentlyUsedServers::clearSuccessfulServers(void)` | 644 | Exported Function
`public: void __thiscall csf::http::HttpNetworkEvent::notifyNetworkEventReporter(enum csf::http::HttpClientResult::Result,class std::shared_ptr<class csf::http::HttpRequestData>,class std::shared_ptr<class csf::common::Policy>)` | 911 | Exported Function
`public: void __thiscall csf::http::HttpRequestData::consumeEasyCURLConnection(class std::shared_ptr<class csf::http::EasyCURLConnection>,class std::shared_ptr<class csf::http::HttpClientData>)` | 648 | Exported Function
`public: void __thiscall csf::http::HttpClientData::setEdgePolicy(class std::shared_ptr<class csf::common::Policy>)` | 985 | Exported Function
`public: void __thiscall csf::http::HttpClientData::setEdgeUsagePolicyCanBeIgnored(bool)` | 987 | Exported Function
`public: void __thiscall csf::http::HttpRequestData::setCommonCriteriaUsagePolicy(class std::shared_ptr<class csf::http::CommonCriteriaUsagePolicy>)` | 974 | Exported Function
`public: void __thiscall csf::http::HttpRequestData::setConnectToList(struct curl_slist *)` | 975 | Exported Function
`public: void __thiscall csf::http::HttpRequestData::returnEasyCURLConnection(void)` | 962 | Exported Function
`public: void __thiscall csf::http::HttpRequestData::setCommonCriteriaUsageCanBeIgnored(bool)` | 973 | Exported Function
`public: void __thiscall csf::edge::RecentlyUsedServers::setTimeoutInSec(unsigned int)` | 1018 | Exported Function
`public: void __thiscall csf::http::BasicHttpClientImpl::setCurlAnswerEvaluator(class std::shared_ptr<class csf::http::CurlAnswerEvaluator>)` | 978 | Exported Function
`public: void __thiscall csf::edge::RecentlyUsedServers::initiateCachedEdgeConfig(void)` | 840 | Exported Function
`public: void __thiscall csf::edge::RecentlyUsedServers::setCachedEdgeConfig(class csf::edge::EdgeConfig const &)` | 969 | Exported Function
`public: void __thiscall csf::http::HttpClientData::resetEasyCURLConnection(void)` | 956 | Exported Function
`public: void __thiscall csf::http::HttpClientData::setCurlAnswerEvaluator(class std::shared_ptr<class csf::http::CurlAnswerEvaluator>)` | 979 | Exported Function
`public: void __thiscall csf::http::HttpClientData::onEasyCURLConnectionReturned(void)` | 916 | Exported Function
`public: void __thiscall csf::http::HttpClientData::provideEasyCURLConnection(class std::shared_ptr<class csf::http::HttpRequestData>)` | 929 | Exported Function
`public: virtual enum csf::cert::CertIdentifierStatus::Status __thiscall csf::cert::AltNameParserImpl::verifyXmpp(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)const ` | 1073 | Exported Function
`public: virtual __thiscall csf::edge::EdgeDetectionController::~EdgeDetectionController(void)` | 241 | Exported Function
`public: virtual __thiscall csf::edge::EdgeDetectionControllerImpl::~EdgeDetectionControllerImpl(void)` | 242 | Exported Function
`public: virtual __thiscall csf::edge::EdgeConfigHttpClient::~EdgeConfigHttpClient(void)` | 238 | Exported Function
`public: virtual __thiscall csf::edge::EdgeConfigRequest::~EdgeConfigRequest(void)` | 239 | Exported Function
`public: virtual __thiscall csf::edge::EdgeUtils::~EdgeUtils(void)` | 247 | Exported Function
`public: virtual __thiscall csf::edge::EnterpriseNetworkSensor::~EnterpriseNetworkSensor(void)` | 249 | Exported Function
`public: virtual __thiscall csf::edge::EdgeInfrastructureEvent::~EdgeInfrastructureEvent(void)` | 244 | Exported Function
`public: virtual __thiscall csf::edge::EdgeInfrastructureEventController::~EdgeInfrastructureEventController(void)` | 245 | Exported Function
`public: virtual __thiscall csf::dns::DnsHostResolver::~DnsHostResolver(void)` | 235 | Exported Function
`public: virtual __thiscall csf::dns::DnsUtilsImpl::~DnsUtilsImpl(void)` | 236 | Exported Function
`public: virtual __thiscall csf::common::Reactor::Event::~Event(void)` | 250 | Exported Function
`public: virtual __thiscall csf::common::Reactor::~Reactor(void)` | 289 | Exported Function
`public: virtual __thiscall csf::edge::CollabEdgeServiceSensor::~CollabEdgeServiceSensor(void)` | 228 | Exported Function
`public: virtual __thiscall csf::edge::CredentialsManager::~CredentialsManager(void)` | 231 | Exported Function
`public: virtual __thiscall csf::dns::DnsUtilsInterface::~DnsUtilsInterface(void)` | 237 | Exported Function
`public: virtual __thiscall csf::edge::CcmcipServerManager::~CcmcipServerManager(void)` | 221 | Exported Function
`public: virtual __thiscall csf::edge::GetEdgeConfigurationListener::~GetEdgeConfigurationListener(void)` | 251 | Exported Function
`public: virtual __thiscall csf::http::CertVerifier::~CertVerifier(void)` | 226 | Exported Function
`public: virtual __thiscall csf::http::CurlAnswerEvaluator::~CurlAnswerEvaluator(void)` | 232 | Exported Function
`public: virtual __thiscall csf::edge::RecentlyUsedServers::~RecentlyUsedServers(void)` | 290 | Exported Function
`public: virtual __thiscall csf::edge::VisibilityChangeObserver::~VisibilityChangeObserver(void)` | 299 | Exported Function
`public: virtual __thiscall csf::http::HttpClientListener::~HttpClientListener(void)` | 254 | Exported Function
`public: virtual __thiscall csf::http::HttpProxyConfigurationReader::~HttpProxyConfigurationReader(void)` | 257 | Exported Function
`public: virtual __thiscall csf::http::EdgeTransformer::~EdgeTransformer(void)` | 246 | Exported Function
`public: virtual __thiscall csf::http::HttpClientData::~HttpClientData(void)` | 253 | Exported Function
`public: virtual __thiscall csf::edge::InternalNetworkVisibilityTester::~InternalNetworkVisibilityTester(void)` | 261 | Exported Function
`public: virtual __thiscall csf::edge::MRAPolicyManager::~MRAPolicyManager(void)` | 271 | Exported Function
`public: virtual __thiscall csf::edge::GlobalEdgeStateObserver::~GlobalEdgeStateObserver(void)` | 252 | Exported Function
`public: virtual __thiscall csf::edge::InternalConnectivityObserver::~InternalConnectivityObserver(void)` | 260 | Exported Function
`public: virtual __thiscall csf::edge::NetworkTester::~NetworkTester(void)` | 279 | Exported Function
`public: virtual __thiscall csf::edge::ReachableEdgeServerManager::~ReachableEdgeServerManager(void)` | 288 | Exported Function
`public: virtual __thiscall csf::edge::NetworkSensingEventRegistrator::~NetworkSensingEventRegistrator(void)` | 277 | Exported Function
`public: virtual __thiscall csf::edge::NetworkSensingObserver::~NetworkSensingObserver(void)` | 278 | Exported Function
`public: virtual __thiscall csf::common::Policy::~Policy(void)` | 282 | Exported Function
`public: struct curl_slist * __thiscall csf::http::HttpRequestData::getConnectToList(void)` | 743 | Exported Function
`public: virtual __thiscall csf::cert::AltNameParser::~AltNameParser(void)` | 216 | Exported Function
`public: struct csf::storage::FileCategoryType & __thiscall csf::storage::FileCategoryType::operator=(struct csf::storage::FileCategoryType &&)` | 364 | Exported Function
`public: struct csf::storage::FileCategoryType & __thiscall csf::storage::FileCategoryType::operator=(struct csf::storage::FileCategoryType const &)` | 365 | Exported Function
`public: virtual __thiscall csf::cert::CertContainerFactory::~CertContainerFactory(void)` | 223 | Exported Function
`public: virtual __thiscall csf::cert::CertContainerImpl::~CertContainerImpl(void)` | 224 | Exported Function
`public: virtual __thiscall csf::cert::AltNameParserFactory::~AltNameParserFactory(void)` | 217 | Exported Function
`public: virtual __thiscall csf::cert::CertContainer::~CertContainer(void)` | 222 | Exported Function
`public: struct csf::http::HttpMethod & __thiscall csf::http::HttpMethod::operator=(struct csf::http::HttpMethod &&)` | 375 | Exported Function
`public: struct csf::http::HttpMethod & __thiscall csf::http::HttpMethod::operator=(struct csf::http::HttpMethod const &)` | 376 | Exported Function
`public: struct csf::http::HttpClientResult & __thiscall csf::http::HttpClientResult::operator=(struct csf::http::HttpClientResult &&)` | 373 | Exported Function
`public: struct csf::http::HttpClientResult & __thiscall csf::http::HttpClientResult::operator=(struct csf::http::HttpClientResult const &)` | 374 | Exported Function
`public: struct csf::http::ProxyAuthentication & __thiscall csf::http::ProxyAuthentication::operator=(struct csf::http::ProxyAuthentication &&)` | 414 | Exported Function
`public: struct csf::http::ProxyAuthentication & __thiscall csf::http::ProxyAuthentication::operator=(struct csf::http::ProxyAuthentication const &)` | 415 | Exported Function
`public: struct csf::http::ProgressData & __thiscall csf::http::ProgressData::operator=(struct csf::http::ProgressData &&)` | 410 | Exported Function
`public: struct csf::http::ProgressData & __thiscall csf::http::ProgressData::operator=(struct csf::http::ProgressData const &)` | 411 | Exported Function
`public: virtual __thiscall csf::cert::CertificateDataFactory::~CertificateDataFactory(void)` | 227 | Exported Function
`public: virtual __thiscall csf::cert::UserInteractingInvalidCertManagementPolicy::~UserInteractingInvalidCertManagementPolicy(void)` | 298 | Exported Function
`public: virtual __thiscall csf::common::BackgroundTimer::~BackgroundTimer(void)` | 218 | Exported Function
`public: virtual __thiscall csf::cert::KeyUsageParserImpl::~KeyUsageParserImpl(void)` | 270 | Exported Function
`public: virtual __thiscall csf::cert::PlatformCertVerifier::~PlatformCertVerifier(void)` | 280 | Exported Function
`public: virtual __thiscall csf::common::DefaultPoliciesStoreObserver::~DefaultPoliciesStoreObserver(void)` | 233 | Exported Function
`public: virtual __thiscall csf::common::InputIndependentPolicy::~InputIndependentPolicy(void)` | 259 | Exported Function
`public: virtual __thiscall csf::common::BackgroundTimerCallback::~BackgroundTimerCallback(void)` | 219 | Exported Function
`public: virtual __thiscall csf::common::BackgroundTimerImpl::~BackgroundTimerImpl(void)` | 220 | Exported Function
`public: virtual __thiscall csf::cert::InvalidCertManagementPolicy::~InvalidCertManagementPolicy(void)` | 263 | Exported Function
`public: virtual __thiscall csf::cert::KeyStrengthParser::~KeyStrengthParser(void)` | 265 | Exported Function
`public: virtual __thiscall csf::cert::CertVerifier::~CertVerifier(void)` | 225 | Exported Function
`public: virtual __thiscall csf::cert::InvalidCertListener::~InvalidCertListener(void)` | 262 | Exported Function
`public: virtual __thiscall csf::cert::KeyUsageParser::~KeyUsageParser(void)` | 268 | Exported Function
`public: virtual __thiscall csf::cert::KeyUsageParserFactory::~KeyUsageParserFactory(void)` | 269 | Exported Function
`public: virtual __thiscall csf::cert::KeyStrengthParserFactory::~KeyStrengthParserFactory(void)` | 266 | Exported Function
`public: virtual __thiscall csf::cert::KeyStrengthParserImpl::~KeyStrengthParserImpl(void)` | 267 | Exported Function
`public: virtual __thiscall csf::http::MultiHttpClientData::~MultiHttpClientData(void)` | 272 | Exported Function
`public: virtual class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __thiscall csf::ip::IpFamilyPreferencePolicy::getName(void)const ` | 787 | Exported Function
`public: virtual class std::shared_ptr<class csf::cert::AltNameParser> __thiscall csf::cert::AltNameParserFactory::buildAltNameParser(void)` | 605 | Exported Function
`public: virtual class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __thiscall csf::http::CommonCriteriaUsagePolicy::getName(void)const ` | 784 | Exported Function
`public: virtual class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __thiscall csf::http::SystemProxyUsagePolicy::getName(void)const ` | 789 | Exported Function
`public: virtual class std::shared_ptr<class csf::cert::CertificateData> __thiscall csf::cert::CertificateDataFactory::buildCertificateData(class std::shared_ptr<class csf::cert::CertContainer>)` | 611 | Exported Function
`public: virtual class std::shared_ptr<class csf::cert::CertificateData> __thiscall csf::cert::CertificateDataFactory::buildCertificateData(struct x509_st const *)` | 609 | Exported Function
`public: virtual class std::shared_ptr<class csf::cert::CertContainer> __thiscall csf::cert::CertContainerFactory::buildCertContainer(struct x509_st const *)` | 607 | Exported Function
`public: virtual class std::shared_ptr<class csf::cert::CertContainer> __thiscall csf::cert::CertContainerFactory::buildCertContainer(struct x509_store_ctx_st const *)` | 608 | Exported Function
`public: virtual bool __thiscall csf::netutils::adapters::EdgeUtilsAdapter::isRequestTransformed(class csf::http::RequestWrapper const &)const ` | 874 | Exported Function
`public: virtual class csf::common::PolicySet::VerifyPoliciesResult __thiscall csf::common::PolicyDriven::verifyPolicies(void)` | 1072 | Exported Function
`public: virtual bool __thiscall csf::http::SystemProxyUsagePolicy::equals(class csf::common::Policy const &)const ` | 707 | Exported Function
`public: virtual bool __thiscall csf::ip::IpFamilyPreferencePolicy::equals(class csf::common::Policy const &)const ` | 705 | Exported Function
`public: virtual class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __thiscall csf::common::Policy::getName(void)const ` | 788 | Exported Function
`public: virtual class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __thiscall csf::edge::EdgeInfrastructureEvent::toString(void)const ` | 1050 | Exported Function
`public: virtual class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __thiscall csf::cert::AltNameParserImpl::getCommonName(void)` | 742 | Exported Function
`public: virtual class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __thiscall csf::cert::InvalidCertManagementPolicy::getName(void)const ` | 786 | Exported Function
`public: virtual class std::shared_ptr<class csf::cert::CertificateData> __thiscall csf::cert::CertificateDataFactory::buildCertificateData(struct x509_store_ctx_st const *)` | 610 | Exported Function
`public: virtual class std::vector<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> >,class std::allocator<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > > > __thiscall csf::cert::AltNameParserImpl::getSrvNames(void)` | 816 | Exported Function
`public: virtual class std::vector<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> >,class std::allocator<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > > > __thiscall csf::cert::AltNameParserImpl::getXmppAddresses(void)` | 830 | Exported Function
`public: virtual class std::vector<class csf::ip::Ipv6Address,class std::allocator<class csf::ip::Ipv6Address> > __thiscall csf::ip::Nat64PrefixImpl::getSynthesisedIpv6Address(class csf::ip::Ipv4Address const &)` | 818 | Exported Function
`public: virtual class std::vector<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> >,class std::allocator<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > > > __thiscall csf::cert::AltNameParserImpl::getDnsNames(void)` | 756 | Exported Function
`public: virtual enum csf::cert::CertIdentifierStatus::Status __thiscall csf::cert::AltNameParserImpl::parse(struct x509_st const *)` | 922 | Exported Function
`public: virtual enum csf::cert::CertIdentifierStatus::Status __thiscall csf::cert::AltNameParserImpl::verify(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)const ` | 1062 | Exported Function
`public: virtual class std::vector<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> >,class std::allocator<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > > > __thiscall csf::http::ProxyBypassReader::getBypassListTokens(void)` | 736 | Exported Function
`public: virtual class std::vector<struct csf::edge::EdgeServiceRecordData,class std::allocator<struct csf::edge::EdgeServiceRecordData> > __thiscall csf::edge::EdgeDetectionControllerImpl::getEdgeServiceRecordData(void)` | 763 | Exported Function
`public: virtual class std::shared_ptr<class csf::common::Policy> __thiscall csf::cert::UserInteractingInvalidCertManagementPolicy::NotifyingFailingAvoidableUserInteractingInvalidCertManagementPolicyBuilder::build(void)` | 601 | Exported Function
`public: virtual class std::shared_ptr<class csf::common::Policy> __thiscall csf::cert::UserInteractingInvalidCertManagementPolicy::NotifyingSucceedingAvoidableUserInteractingInvalidCertManagementPolicyBuilder::build(void)` | 602 | Exported Function
`public: virtual class std::shared_ptr<class csf::cert::KeyStrengthParser> __thiscall csf::cert::KeyStrengthParserFactory::buildKeyStrengthParser(void)` | 615 | Exported Function
`public: virtual class std::shared_ptr<class csf::cert::KeyUsageParser> __thiscall csf::cert::KeyUsageParserFactory::buildKeyUsageParser(void)` | 616 | Exported Function
`public: virtual class std::shared_ptr<class csf::http::Proxy> __thiscall csf::http::HttpProxyConfigurationReader::getHttpProxyForUrl(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)const ` | 772 | Exported Function
`public: virtual class std::shared_ptr<class csf::http::Proxy> __thiscall csf::http::SystemProxyResolver::resolveSystemProxy(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 961 | Exported Function
`public: virtual class std::shared_ptr<class csf::common::Policy> __thiscall csf::cert::UserInteractingInvalidCertManagementPolicy::PromptingAvoidableUserInteractingInvalidCertManagementPolicyBuilder::build(void)` | 604 | Exported Function
`public: virtual class std::shared_ptr<class csf::common::Policy> __thiscall csf::common::PolicyDriven::getPolicy(enum csf::common::Policy::PolicyNature::Nature)const ` | 802 | Exported Function
`public: virtual bool __thiscall csf::http::ProxyBypassReader::isProxyRequired(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> >)` | 870 | Exported Function
`public: virtual bool __thiscall csf::cert::InvalidCertManagementPolicy::equals(class csf::common::Policy const &)const ` | 704 | Exported Function
`public: virtual bool __thiscall csf::cert::InvalidCertManagementPolicy::verifyEnforceability(class std::set<enum csf::cert::CertStatus::Status,struct std::less<enum csf::cert::CertStatus::Status>,class std::allocator<enum csf::cert::CertStatus::Status> > const &,class std::shared_ptr<class csf::cert::CertificateData>)const ` | 1067 | Exported Function
`public: virtual bool __thiscall csf::cert::CertContainerImpl::isLeafCert(void)const ` | 865 | Exported Function
`public: virtual bool __thiscall csf::cert::CertContainerImpl::isValid(void)const ` | 883 | Exported Function
`public: virtual bool __thiscall csf::cert::KeyUsageParserImpl::hasExtendedKeyUsage(void)const ` | 834 | Exported Function
`public: virtual bool __thiscall csf::cert::KeyUsageParserImpl::isAnyExtendedKeyUsageSet(void)const ` | 843 | Exported Function
`public: virtual bool __thiscall csf::cert::KeyStrengthParserImpl::parsed(void)const ` | 926 | Exported Function
`public: virtual bool __thiscall csf::cert::KeyUsageParserImpl::hasBasicKeyUsage(void)const ` | 833 | Exported Function
`public: virtual __thiscall csf::http::ProxyBypassReader::~ProxyBypassReader(void)` | 287 | Exported Function
`public: virtual __thiscall csf::http::UnresolvedHostCache::~UnresolvedHostCache(void)` | 297 | Exported Function
`public: virtual __thiscall csf::http::ProxyAuthenticationCallback::~ProxyAuthenticationCallback(void)` | 285 | Exported Function
`public: virtual __thiscall csf::http::ProxyAuthenticationHandler::~ProxyAuthenticationHandler(void)` | 286 | Exported Function
`public: virtual __thiscall csf::netutils::NetworkEventReporterObserver::~NetworkEventReporterObserver(void)` | 275 | Exported Function
`public: virtual bool __thiscall csf::cert::CertContainerImpl::hasValidLeafCert(void)const ` | 836 | Exported Function
`public: virtual __thiscall csf::netutils::adapters::EdgeUtilsAdapter::~EdgeUtilsAdapter(void)` | 248 | Exported Function
`public: virtual __thiscall csf::netutils::NetworkEventCallback::~NetworkEventCallback(void)` | 273 | Exported Function
`public: virtual bool __thiscall csf::cert::KeyUsageParserImpl::parsed(void)const ` | 927 | Exported Function
`public: virtual bool __thiscall csf::edge::EdgeDetectionControllerImpl::isOnPremServerAvailable(void)` | 868 | Exported Function
`public: virtual bool __thiscall csf::edge::EnterpriseNetworkSensor::evaluate(struct csf::edge::ServiceRecord &)` | 711 | Exported Function
`public: virtual bool __thiscall csf::edge::DirectConnectivityTester::test(void)` | 1048 | Exported Function
`public: virtual bool __thiscall csf::edge::EdgeDetectionControllerImpl::isEdgeAvailable(void)` | 844 | Exported Function
`public: virtual bool __thiscall csf::http::CommonCriteriaUsagePolicy::equals(class csf::common::Policy const &)const ` | 702 | Exported Function
`public: virtual bool __thiscall csf::http::CurlAnswerEvaluator::representServerFailure(enum CURLcode)` | 949 | Exported Function
`public: virtual bool __thiscall csf::edge::InternalNetworkVisibilityTester::test(void)` | 1049 | Exported Function
`public: virtual bool __thiscall csf::edge::NetworkSensingEventRegistrator::doRegistration(class std::shared_ptr<class csf::edge::NetworkSensingObserver>)` | 684 | Exported Function
`public: virtual bool __thiscall csf::common::BackgroundTimer::isSet(void)` | 880 | Exported Function
`public: virtual bool __thiscall csf::common::InputIndependentPolicy::equals(class csf::common::Policy const &)const ` | 703 | Exported Function
`public: virtual bool __thiscall csf::cert::UserInteractingInvalidCertManagementPolicy::equals(class csf::common::Policy const &)const ` | 708 | Exported Function
`public: virtual bool __thiscall csf::cert::UserInteractingInvalidCertManagementPolicy::verifyEnforceability(class std::set<enum csf::cert::CertStatus::Status,struct std::less<enum csf::cert::CertStatus::Status>,class std::allocator<enum csf::cert::CertStatus::Status> > &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::vector<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> >,class std::allocator<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > > > const &)const ` | 1068 | Exported Function
`public: virtual bool __thiscall csf::edge::CollabEdgeServiceSensor::evaluate(class std::back_insert_iterator<class std::vector<struct csf::edge::EdgeServiceRecordData,class std::allocator<struct csf::edge::EdgeServiceRecordData> > >)const ` | 709 | Exported Function
`public: virtual bool __thiscall csf::edge::CollabEdgeServiceSensor::evaluate(class std::back_insert_iterator<class std::vector<struct csf::edge::EdgeServiceRecordData,class std::allocator<struct csf::edge::EdgeServiceRecordData> > >,int &)const ` | 710 | Exported Function
`public: virtual bool __thiscall csf::common::Policy::equals(class csf::common::Policy const &)const ` | 706 | Exported Function
`public: virtual bool __thiscall csf::dns::DnsHostResolver::isResolvable(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 875 | Exported Function
`public: __thiscall csf::cert::CertContainerImpl::CertContainerImpl(struct x509_st const *)` | 25 | Exported Function
`public: __thiscall csf::cert::CertContainerImpl::CertContainerImpl(struct x509_store_ctx_st const *)` | 26 | Exported Function
`public: __thiscall csf::cert::CertContainerFactory::CertContainerFactory(void)` | 22 | Exported Function
`public: __thiscall csf::cert::CertContainerImpl::CertContainerImpl(class csf::cert::CertContainerImpl const &)` | 24 | Exported Function
`public: __thiscall csf::cert::CertificateDataFactory::CertificateDataFactory(class csf::cert::CertificateDataFactory const &)` | 36 | Exported Function
`public: __thiscall csf::cert::CertificateDataFactory::CertificateDataFactory(void)` | 37 | Exported Function
`public: __thiscall csf::cert::CertIdentifierStatus::CertIdentifierStatus(void)` | 27 | Exported Function
`public: __thiscall csf::cert::CertificateCacheAccessor::CertificateCacheAccessor(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::set<enum csf::cert::CertStatus::Status,struct std::less<enum csf::cert::CertStatus::Status>,class std::allocator<enum csf::cert::CertStatus::Status> > &,class std::shared_ptr<class csf::cert::InvalidCertManagementPolicy>)` | 35 | Exported Function
`public: __thiscall csf::cert::AltNameParserFactory::AltNameParserFactory(void)` | 10 | Exported Function
`public: __thiscall csf::cert::AltNameParserImpl::AltNameParserImpl(class std::vector<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> >,class std::allocator<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > > > const &,class std::vector<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> >,class std::allocator<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > > > const &,class std::vector<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> >,class std::allocator<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > > > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 11 | Exported Function
`public: __thiscall csf::cert::AltNameParser::AltNameParser(void)` | 8 | Exported Function
`public: __thiscall csf::cert::AltNameParserFactory::AltNameParserFactory(class csf::cert::AltNameParserFactory const &)` | 9 | Exported Function
`public: __thiscall csf::cert::CertContainer::CertContainer(void)` | 20 | Exported Function
`public: __thiscall csf::cert::CertContainerFactory::CertContainerFactory(class csf::cert::CertContainerFactory const &)` | 21 | Exported Function
`public: __thiscall csf::cert::AltNameParserImpl::AltNameParserImpl(void)` | 12 | Exported Function
`public: __thiscall csf::cert::CertContainer::CertContainer(class csf::cert::CertContainer const &)` | 19 | Exported Function
`public: __thiscall csf::cert::CertificateVerificationListener::CertificateVerificationListener(class csf::cert::CertificateVerificationListener &&)` | 38 | Exported Function
`public: __thiscall csf::cert::KeyStrengthParser::KeyStrengthParser(void)` | 123 | Exported Function
`public: __thiscall csf::cert::KeyStrengthParserFactory::KeyStrengthParserFactory(class csf::cert::KeyStrengthParserFactory const &)` | 124 | Exported Function
`public: __thiscall csf::cert::InvalidCertListener::InvalidCertListener(void)` | 119 | Exported Function
`public: __thiscall csf::cert::KeyStrengthParser::KeyStrengthParser(class csf::cert::KeyStrengthParser const &)` | 122 | Exported Function
`public: __thiscall csf::cert::KeyStrengthParserImpl::KeyStrengthParserImpl(class csf::cert::KeyStrengthParserImpl const &)` | 127 | Exported Function
`public: __thiscall csf::cert::KeyStrengthParserImpl::KeyStrengthParserImpl(void)` | 128 | Exported Function
`public: __thiscall csf::cert::KeyStrengthParserFactory::KeyStrengthParserFactory(void)` | 125 | Exported Function
`public: __thiscall csf::cert::KeyStrengthParserImpl::KeyStrengthParserImpl(class csf::cert::KeyStrengthParserImpl &&)` | 126 | Exported Function
`public: __thiscall csf::cert::CertResult::CertResult(void)` | 28 | Exported Function
`public: __thiscall csf::cert::CertVerifier::CertVerifier(class std::shared_ptr<class csf::cert::PlatformCertVerifier>)` | 29 | Exported Function
`public: __thiscall csf::cert::CertificateVerificationListener::CertificateVerificationListener(class csf::cert::CertificateVerificationListener const &)` | 39 | Exported Function
`public: __thiscall csf::cert::CertificateVerificationListener::CertificateVerificationListener(void)` | 40 | Exported Function
`public: __thiscall csf::cert::CertVerifierTask::CertVerifierTask(void)` | 34 | Exported Function
`public: __thiscall csf::cert::InvalidCertListener::InvalidCertListener(class csf::cert::InvalidCertListener const &)` | 118 | Exported Function
`public: __thiscall csf::cert::CertVerifierTask::CertVerifierTask(class csf::cert::CertVerifierTask &&)` | 32 | Exported Function
`public: __thiscall csf::cert::CertVerifierTask::CertVerifierTask(class csf::cert::CertVerifierTask const &)` | 33 | Exported Function
`public: __thiscall csf::cert::AltNameParser::AltNameParser(class csf::cert::AltNameParser const &)` | 7 | Exported Function
`protected: __thiscall csf::ip::Nat64Prefix::Nat64Prefix(void)` | 141 | Exported Function
`protected: __thiscall csf::netutils::NetworkEventReporter::NetworkEventReporter(void)` | 147 | Exported Function
`protected: __thiscall csf::http::HttpClientData::HttpClientData(class std::shared_ptr<class csf::http::HttpNetworkEventReporter>,class std::shared_ptr<class csf::http::EdgeTransformer>)` | 98 | Exported Function
`protected: __thiscall csf::http::HttpNetworkEventReporter::HttpNetworkEventReporter(void)` | 106 | Exported Function
`protected: __thiscall std::enable_shared_from_this<class csf::dns::DnsQuery>::enable_shared_from_this<class csf::dns::DnsQuery>(void)` | 2 | Exported Function
`protected: __thiscall std::enable_shared_from_this<class csf::dns::DnsQuery>::~enable_shared_from_this<class csf::dns::DnsQuery>(void)` | 211 | Exported Function
`protected: __thiscall csf::netutils::NetworkEventReporterObserver::NetworkEventReporterObserver(void)` | 150 | Exported Function
`protected: __thiscall std::enable_shared_from_this<class csf::dns::DnsQuery>::enable_shared_from_this<class csf::dns::DnsQuery>(class std::enable_shared_from_this<class csf::dns::DnsQuery> const &)` | 1 | Exported Function
`protected: __thiscall csf::common::PolicyDriven::PolicyDriven(class std::set<class std::shared_ptr<class csf::common::Policy>,struct std::less<class std::shared_ptr<class csf::common::Policy> >,class std::allocator<class std::shared_ptr<class csf::common::Policy> > >,bool)` | 169 | Exported Function
`protected: __thiscall csf::common::Reactor::Event::Event(void)` | 90 | Exported Function
`protected: __thiscall csf::common::Policy::Policy(enum csf::common::Policy::PolicyNature::Nature,enum csf::common::Policy::PolicyFailureClass::FailureClass,bool)` | 167 | Exported Function
`protected: __thiscall csf::common::PolicyDriven::PolicyDriven(bool)` | 170 | Exported Function
`protected: __thiscall csf::edge::InternalNetworkVisibilityTester::InternalNetworkVisibilityTester(void)` | 116 | Exported Function
`protected: __thiscall csf::edge::NetworkSensingEventRegistrator::NetworkSensingEventRegistrator(class std::weak_ptr<class csf::edge::NetworkSensingObserver>,class std::shared_ptr<class csf::common::BackgroundTimer>)` | 154 | Exported Function
`protected: __thiscall csf::dns::QueryResponse::QueryResponse(enum csf::dns::DnsQueryType)` | 181 | Exported Function
`protected: __thiscall csf::edge::EdgeInfrastructureEventController::EdgeInfrastructureEventController(void)` | 79 | Exported Function
`protected: __thiscall std::enable_shared_from_this<class csf::edge::NetworkSensingEventRegistrator>::enable_shared_from_this<class csf::edge::NetworkSensingEventRegistrator>(class std::enable_shared_from_this<class csf::edge::NetworkSensingEventRegistrator> const &)` | 5 | Exported Function
`protected: virtual __thiscall csf::netutils::NetworkEventReporter::~NetworkEventReporter(void)` | 274 | Exported Function
`protected: virtual enum csf::cert::CertIdentifierStatus::Status __thiscall csf::cert::CertVerifier::checkIdentifier(class std::shared_ptr<class csf::cert::AltNameParser>,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 630 | Exported Function
`protected: class std::enable_shared_from_this<class csf::http::HttpClientData> & __thiscall std::enable_shared_from_this<class csf::http::HttpClientData>::operator=(class std::enable_shared_from_this<class csf::http::HttpClientData> const &)` | 301 | Exported Function
`protected: virtual __thiscall csf::http::HttpNetworkEventReporter::~HttpNetworkEventReporter(void)` | 256 | Exported Function
`protected: void __thiscall csf::common::Reactor::startServingThread(void)` | 1037 | Exported Function
`public: __int64 __thiscall csf::edge::Timestamp::valueInMicroseconds(void)const ` | 1061 | Exported Function
`protected: virtual void __thiscall csf::common::PolicyDriven::resetForTesting(void)` | 960 | Exported Function
`protected: void __thiscall csf::common::Reactor::enqueueBase(class csf::common::Reactor::Event const *)` | 701 | Exported Function
`protected: __thiscall std::enable_shared_from_this<class csf::http::HttpClientData>::enable_shared_from_this<class csf::http::HttpClientData>(class std::enable_shared_from_this<class csf::http::HttpClientData> const &)` | 3 | Exported Function
`protected: __thiscall std::enable_shared_from_this<class csf::http::HttpClientData>::enable_shared_from_this<class csf::http::HttpClientData>(void)` | 4 | Exported Function
`protected: __thiscall std::enable_shared_from_this<class csf::edge::NetworkSensingEventRegistrator>::enable_shared_from_this<class csf::edge::NetworkSensingEventRegistrator>(void)` | 6 | Exported Function
`protected: __thiscall std::enable_shared_from_this<class csf::edge::NetworkSensingEventRegistrator>::~enable_shared_from_this<class csf::edge::NetworkSensingEventRegistrator>(void)` | 213 | Exported Function
`protected: class std::enable_shared_from_this<class csf::dns::DnsQuery> & __thiscall std::enable_shared_from_this<class csf::dns::DnsQuery>::operator=(class std::enable_shared_from_this<class csf::dns::DnsQuery> const &)` | 300 | Exported Function
`protected: class std::enable_shared_from_this<class csf::edge::NetworkSensingEventRegistrator> & __thiscall std::enable_shared_from_this<class csf::edge::NetworkSensingEventRegistrator>::operator=(class std::enable_shared_from_this<class csf::edge::NetworkSensingEventRegistrator> const &)` | 302 | Exported Function
`protected: __thiscall std::enable_shared_from_this<class csf::http::HttpClientData>::~enable_shared_from_this<class csf::http::HttpClientData>(void)` | 212 | Exported Function
`protected: bool __thiscall csf::common::Reactor::isEqualToLastEventInQueue(class csf::common::Reactor::Event const *)` | 850 | Exported Function
`public: __thiscall csf::cert::KeyUsageParser::KeyUsageParser(class csf::cert::KeyUsageParser const &)` | 129 | Exported Function
`public: __thiscall csf::edge::CollabEdgeServiceSensor::CollabEdgeServiceSensor(enum csf::edge::CollabEdgeServiceSensorStrategy::Strategy,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 41 | Exported Function
`public: __thiscall csf::edge::Credentials::Credentials(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class csf::SecureString const &,class csf::SecureString const &)` | 48 | Exported Function
`public: __thiscall csf::edge::CcmcipServerManager::CcmcipServerManager(class csf::edge::CcmcipServerManager const &)` | 17 | Exported Function
`public: __thiscall csf::edge::CcmcipServerManager::CcmcipServerManager(void)` | 18 | Exported Function
`public: __thiscall csf::edge::CredentialsManager::CredentialsManager(void)` | 51 | Exported Function
`public: __thiscall csf::edge::DetectDirectConnectAvailableFsm::Statistics::Statistics(void)` | 195 | Exported Function
`public: __thiscall csf::edge::Credentials::Credentials(void)` | 49 | Exported Function
`public: __thiscall csf::edge::CredentialsManager::CredentialsManager(class csf::edge::CredentialsManager const &)` | 50 | Exported Function
`public: __thiscall csf::dns::ServiceResourceRecord::~ServiceResourceRecord(void)` | 293 | Exported Function
`public: __thiscall csf::dns::ServiceResourceRecordSorter::ServiceResourceRecordSorter(class csf::dns::ServiceResourceRecordSorter &&)` | 191 | Exported Function
`public: __thiscall csf::dns::DnsUtilsScopedSetCustomServerAddress::DnsUtilsScopedSetCustomServerAddress(class csf::dns::DnsUtilsScopedSetCustomServerAddress const &)` | 64 | Exported Function
`public: __thiscall csf::dns::PointerRecord::~PointerRecord(void)` | 281 | Exported Function
`public: __thiscall csf::dns::SOARecord::~SOARecord(void)` | 292 | Exported Function
`public: __thiscall csf::dns::TXTRecord::~TXTRecord(void)` | 295 | Exported Function
`public: __thiscall csf::dns::ServiceResourceRecordSorter::ServiceResourceRecordSorter(class csf::dns::ServiceResourceRecordSorter const &)` | 192 | Exported Function
`public: __thiscall csf::dns::ServiceResourceRecordSorter::~ServiceResourceRecordSorter(void)` | 294 | Exported Function
`public: __thiscall csf::edge::DetectDirectConnectUnavailableFsm::Statistics::Statistics(void)` | 196 | Exported Function
`public: __thiscall csf::edge::EdgeConfigResponse::EdgeConfigResponse(class csf::edge::EdgeConfigResponse const &)` | 73 | Exported Function
`public: __thiscall csf::edge::EdgeConfigResponse::EdgeConfigResponse(struct csf::edge::HttpClientResponse const &)` | 72 | Exported Function
`public: __thiscall csf::edge::EdgeConfigRequest::EdgeConfigRequest(void)` | 70 | Exported Function
`public: __thiscall csf::edge::EdgeConfigRequestImpl::EdgeConfigRequestImpl(class std::shared_ptr<class csf::edge::EdgeConfigHttpClient>)` | 71 | Exported Function
`public: __thiscall csf::edge::EdgeDetectionController::EdgeDetectionController(void)` | 75 | Exported Function
`public: __thiscall csf::edge::EdgeDetectionDnsRecordReader::EdgeDetectionDnsRecordReader(void)` | 76 | Exported Function
`public: __thiscall csf::edge::EdgeConfigResponse::~EdgeConfigResponse(void)` | 240 | Exported Function
`public: __thiscall csf::edge::EdgeDetectionController::EdgeDetectionController(class csf::edge::EdgeDetectionController const &)` | 74 | Exported Function
`public: __thiscall csf::edge::DirectConnectivityTester::DirectConnectivityTester(struct csf::edge::TcpEndpoint const &,int)` | 57 | Exported Function
`public: __thiscall csf::edge::EdgeConfig::EdgeConfig(void)` | 65 | Exported Function
`public: __thiscall csf::edge::DetectionParameters::DetectionParameters(void)` | 56 | Exported Function
`public: __thiscall csf::edge::DetectionParameters::~DetectionParameters(void)` | 234 | Exported Function
`public: __thiscall csf::edge::EdgeConfigParams::EdgeConfigParams(void)` | 68 | Exported Function
`public: __thiscall csf::edge::EdgeConfigRequest::EdgeConfigRequest(class csf::edge::EdgeConfigRequest const &)` | 69 | Exported Function
`public: __thiscall csf::edge::EdgeConfigHttpClient::EdgeConfigHttpClient(class csf::edge::EdgeConfigHttpClient const &)` | 66 | Exported Function
`public: __thiscall csf::edge::EdgeConfigHttpClient::EdgeConfigHttpClient(void)` | 67 | Exported Function
`public: __thiscall csf::dns::DnsUtilsInterface::DnsUtilsInterface(void)` | 63 | Exported Function
`public: __thiscall csf::cert::UserInteractingInvalidCertManagementPolicy::PromptingAvoidableUserInteractingInvalidCertManagementPolicyBuilder::PromptingAvoidableUserInteractingInvalidCertManagementPolicyBuilder(void)` | 175 | Exported Function
`public: __thiscall csf::cert::XmppCertVerifier::XmppCertVerifier(class std::shared_ptr<class csf::cert::PlatformCertVerifier>)` | 210 | Exported Function
`public: __thiscall csf::cert::UserInteractingInvalidCertManagementPolicy::NotifyingFailingAvoidableUserInteractingInvalidCertManagementPolicyBuilder::NotifyingFailingAvoidableUserInteractingInvalidCertManagementPolicyBuilder(void)` | 161 | Exported Function
`public: __thiscall csf::cert::UserInteractingInvalidCertManagementPolicy::NotifyingSucceedingAvoidableUserInteractingInvalidCertManagementPolicyBuilder::NotifyingSucceedingAvoidableUserInteractingInvalidCertManagementPolicyBuilder(void)` | 162 | Exported Function
`public: __thiscall csf::common::BackgroundTimerCallback::BackgroundTimerCallback(void)` | 15 | Exported Function
`public: __thiscall csf::common::BackgroundTimerImpl::BackgroundTimerImpl(class std::weak_ptr<class csf::common::BackgroundTimerCallback>,class std::chrono::duration<__int64,struct std::ratio<1,1> > const &)` | 16 | Exported Function
`public: __thiscall csf::common::BackgroundTimer::BackgroundTimer(void)` | 13 | Exported Function
`public: __thiscall csf::common::BackgroundTimerCallback::BackgroundTimerCallback(class csf::common::BackgroundTimerCallback const &)` | 14 | Exported Function
`public: __thiscall csf::cert::KeyUsageParserFactory::KeyUsageParserFactory(void)` | 132 | Exported Function
`public: __thiscall csf::cert::KeyUsageParserImpl::KeyUsageParserImpl(class csf::cert::KeyUsageParserImpl &&)` | 133 | Exported Function
`public: __thiscall csf::cert::KeyUsageParser::KeyUsageParser(void)` | 130 | Exported Function
`public: __thiscall csf::cert::KeyUsageParserFactory::KeyUsageParserFactory(class csf::cert::KeyUsageParserFactory const &)` | 131 | Exported Function
`public: __thiscall csf::cert::PlatformCertVerifier::PlatformCertVerifier(class csf::cert::PlatformCertVerifier const &)` | 165 | Exported Function
`public: __thiscall csf::cert::PlatformCertVerifier::PlatformCertVerifier(void)` | 166 | Exported Function
`public: __thiscall csf::cert::KeyUsageParserImpl::KeyUsageParserImpl(class csf::cert::KeyUsageParserImpl const &)` | 134 | Exported Function
`public: __thiscall csf::cert::KeyUsageParserImpl::KeyUsageParserImpl(void)` | 135 | Exported Function
`public: __thiscall csf::common::Cookie::Cookie(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 46 | Exported Function
`public: __thiscall csf::dns::ARecord::~ARecord(void)` | 215 | Exported Function
`public: __thiscall csf::dns::DnsHostResolver::DnsHostResolver(class csf::dns::DnsHostResolver const &)` | 58 | Exported Function
`public: __thiscall csf::common::Reactor::Reactor(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 183 | Exported Function
`public: __thiscall csf::dns::AAAARecord::~AAAARecord(void)` | 214 | Exported Function
`public: __thiscall csf::dns::DnsUtilsImpl::DnsUtilsImpl(class csf::dns::DnsUtilsImpl const &)` | 61 | Exported Function
`public: __thiscall csf::dns::DnsUtilsInterface::DnsUtilsInterface(class csf::dns::DnsUtilsInterface const &)` | 62 | Exported Function
`public: __thiscall csf::dns::DnsHostResolver::DnsHostResolver(void)` | 59 | Exported Function
`public: __thiscall csf::dns::DnsUtilsImpl::DnsUtilsImpl(class csf::dns::DnsUtilsImpl &&)` | 60 | Exported Function
`public: __thiscall csf::common::DefaultPoliciesStoreObserver::DefaultPoliciesStoreObserver(class csf::common::DefaultPoliciesStoreObserver const &)` | 54 | Exported Function
`public: __thiscall csf::common::DefaultPoliciesStoreObserver::DefaultPoliciesStoreObserver(void)` | 55 | Exported Function
`public: __thiscall csf::common::Cookie::Cookie(void)` | 47 | Exported Function
`public: __thiscall csf::common::Cookie::~Cookie(void)` | 230 | Exported Function
`public: __thiscall csf::common::PolicySet::VerifyPoliciesResult::VerifyPoliciesResult(void)` | 207 | Exported Function
`public: __thiscall csf::common::Reactor::Event::Event(class csf::common::Reactor::Event const &)` | 91 | Exported Function
`public: __thiscall csf::common::EmailAddressParser::EmailAddressParser(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 88 | Exported Function
`public: __thiscall csf::common::PolicySet::PolicySet(void)` | 173 | Exported Function
`protected: __thiscall csf::common::Policy::Policy(enum csf::common::Policy::PolicyNature::Nature,bool)` | 168 | Exported Function
`const csf::cert::AltNameParserFactory::``vftable'` | 490 | Exported Function
`const csf::cert::CertContainer::``vftable'` | 493 | Exported Function
`class std::basic_string<wchar_t,struct std::char_traits<wchar_t>,class std::allocator<wchar_t> > __cdecl csf::http::getWindowsErrorMessage(unsigned long)` | 829 | Exported Function
`const csf::cert::AltNameParser::``vftable'` | 489 | Exported Function
`const csf::cert::CertificateDataFactory::``vftable'` | 498 | Exported Function
`const csf::cert::CertificateVerificationListener::``vftable'` | 499 | Exported Function
`const csf::cert::CertContainerFactory::``vftable'` | 494 | Exported Function
`const csf::cert::CertContainerImpl::``vftable'` | 495 | Exported Function
`class std::basic_ostream<char,struct std::char_traits<char> > & __cdecl csf::http::operator<<(class std::basic_ostream<char,struct std::char_traits<char> > &,enum csf::http::HttpClientError::Error const &)` | 468 | Exported Function
`class std::basic_ostream<char,struct std::char_traits<char> > & __cdecl csf::http::operator<<(class std::basic_ostream<char,struct std::char_traits<char> > &,enum csf::http::HttpClientResult::Result const &)` | 469 | Exported Function
`class std::basic_ostream<char,struct std::char_traits<char> > & __cdecl csf::http::operator<<(class std::basic_ostream<char,struct std::char_traits<char> > &,class csf::http::EdgePolicy)` | 471 | Exported Function
`class std::basic_ostream<char,struct std::char_traits<char> > & __cdecl csf::http::operator<<(class std::basic_ostream<char,struct std::char_traits<char> > &,enum csf::http::EdgeTransformer::TransformRequestResult::Result const &)` | 470 | Exported Function
`class std::basic_ostream<char,struct std::char_traits<char> > & __cdecl csf::ip::operator<<(class std::basic_ostream<char,struct std::char_traits<char> > &,enum csf::ip::ConnectionInformationResult::Result const &)` | 474 | Exported Function
`class std::basic_ostream<char,struct std::char_traits<char> > & __cdecl csf::netutils::adapters::operator<<(class std::basic_ostream<char,struct std::char_traits<char> > &,enum csf::edge::EdgeConfigHttpClient::Result)` | 435 | Exported Function
`class std::basic_ostream<char,struct std::char_traits<char> > & __cdecl csf::ip::operator<<(class std::basic_ostream<char,struct std::char_traits<char> > &,class csf::ip::ConnectionInformationResult const &)` | 472 | Exported Function
`class std::basic_ostream<char,struct std::char_traits<char> > & __cdecl csf::ip::operator<<(class std::basic_ostream<char,struct std::char_traits<char> > &,class csf::ip::IpAddress const &)` | 473 | Exported Function
`const csf::cert::CertVerifierTask::``vftable'` | 497 | Exported Function
`const csf::common::Reactor::Event::``vftable'` | 510 | Exported Function
`const csf::dns::DnsHostResolver::``vftable'` | 503 | Exported Function
`const csf::common::BackgroundTimerCallback::``vftable'` | 491 | Exported Function
`const csf::common::DefaultPoliciesStoreObserver::``vftable'` | 502 | Exported Function
`const csf::edge::CcmcipServerManager::``vftable'` | 492 | Exported Function
`const csf::edge::CredentialsManager::``vftable'` | 500 | Exported Function
`const csf::dns::DnsUtilsImpl::``vftable'` | 504 | Exported Function
`const csf::dns::DnsUtilsInterface::``vftable'` | 505 | Exported Function
`const csf::cert::KeyStrengthParserFactory::``vftable'` | 520 | Exported Function
`const csf::cert::KeyStrengthParserImpl::``vftable'` | 521 | Exported Function
`const csf::cert::InvalidCertListener::``vftable'` | 518 | Exported Function
`const csf::cert::KeyStrengthParser::``vftable'` | 519 | Exported Function
`const csf::cert::KeyUsageParserImpl::``vftable'` | 524 | Exported Function
`const csf::cert::PlatformCertVerifier::``vftable'` | 533 | Exported Function
`const csf::cert::KeyUsageParser::``vftable'` | 522 | Exported Function
`const csf::cert::KeyUsageParserFactory::``vftable'` | 523 | Exported Function
`class std::basic_ostream<char,struct std::char_traits<char> > & __cdecl csf::edge::operator<<(class std::basic_ostream<char,struct std::char_traits<char> > &,struct csf::edge::TcpEndpoint const &)` | 461 | Exported Function
`class std::basic_ostream<char,struct std::char_traits<char> > & __cdecl csf::cert::operator<<(class std::basic_ostream<char,struct std::char_traits<char> > &,enum csf::cert::CertResult::Result const &)` | 445 | Exported Function
`class std::basic_ostream<char,struct std::char_traits<char> > & __cdecl csf::cert::operator<<(class std::basic_ostream<char,struct std::char_traits<char> > &,enum csf::cert::CertStatus::Status const &)` | 447 | Exported Function
`class std::basic_ostream<char,struct std::char_traits<char> > & __cdecl csf::cert::operator<<(class std::basic_ostream<char,struct std::char_traits<char> > &,enum csf::cert::CertKeyStrengthResult::Result const &)` | 443 | Exported Function
`class std::basic_ostream<char,struct std::char_traits<char> > & __cdecl csf::cert::operator<<(class std::basic_ostream<char,struct std::char_traits<char> > &,enum csf::cert::CertKeyUsageResult::Result const &)` | 444 | Exported Function
`class std::basic_ostream<char,struct std::char_traits<char> > & __cdecl csf::cert::operator<<(class std::basic_ostream<char,struct std::char_traits<char> > &,enum csf::cert::InvalidCertNotificationManager::PromptDecision::Decision const &)` | 441 | Exported Function
`class std::basic_ostream<char,struct std::char_traits<char> > & __cdecl csf::cert::operator<<(class std::basic_ostream<char,struct std::char_traits<char> > &,struct csf::cert::CertIdentifierStatus const &)` | 437 | Exported Function
`class std::basic_ostream<char,struct std::char_traits<char> > & __cdecl csf::cert::operator<<(class std::basic_ostream<char,struct std::char_traits<char> > &,enum csf::cert::ExtendedKeyUsage::Usage const &)` | 449 | Exported Function
`class std::basic_ostream<char,struct std::char_traits<char> > & __cdecl csf::cert::operator<<(class std::basic_ostream<char,struct std::char_traits<char> > &,enum csf::cert::InvalidCertNotificationManager::AcceptanceOptions::Options const &)` | 442 | Exported Function
`class std::basic_ostream<char,struct std::char_traits<char> > & __cdecl csf::cert::operator<<(class std::basic_ostream<char,struct std::char_traits<char> > &,class csf::cert::InvalidCertManagementPolicy)` | 450 | Exported Function
`class std::basic_ostream<char,struct std::char_traits<char> > & __cdecl csf::cert::operator<<(class std::basic_ostream<char,struct std::char_traits<char> > &,class csf::cert::PersistInvalidCertDecisionPolicy)` | 451 | Exported Function
`bool __cdecl csf::edge::operator==(struct csf::edge::NetworkSensingEvent const &,struct csf::edge::NetworkSensingEvent const &)` | 482 | Exported Function
`char * __cdecl csf::netutils::libcurl_strdup_callback(char const *)` | 892 | Exported Function
`class std::basic_ostream<char,struct std::char_traits<char> > & __cdecl csf::cert::operator<<(class std::basic_ostream<char,struct std::char_traits<char> > &,enum csf::cert::CertAcceptanceDecision::Decision const &)` | 440 | Exported Function
`class std::basic_ostream<char,struct std::char_traits<char> > & __cdecl csf::cert::operator<<(class std::basic_ostream<char,struct std::char_traits<char> > &,enum csf::cert::CertIdentifierStatus::Status const &)` | 446 | Exported Function
`class std::basic_ostream<char,struct std::char_traits<char> > & __cdecl csf::cert::operator<<(class std::basic_ostream<char,struct std::char_traits<char> > &,class std::set<enum csf::cert::CertStatus::Status,struct std::less<enum csf::cert::CertStatus::Status>,class std::allocator<enum csf::cert::CertStatus::Status> > const &)` | 439 | Exported Function
`class std::basic_ostream<char,struct std::char_traits<char> > & __cdecl csf::cert::operator<<(class std::basic_ostream<char,struct std::char_traits<char> > &,enum csf::cert::BasicKeyUsage::Usage const &)` | 448 | Exported Function
`class std::basic_ostream<char,struct std::char_traits<char> > & __cdecl csf::cert::operator<<(class std::basic_ostream<char,struct std::char_traits<char> > &,struct csf::cert::CertResult const &)` | 438 | Exported Function
`class std::basic_ostream<char,struct std::char_traits<char> > & __cdecl csf::edge::operator<<(class std::basic_ostream<char,struct std::char_traits<char> > &,enum csf::edge::GlobalEdgeState::TerminateEdgeSessionResult::Result const &)` | 466 | Exported Function
`class std::basic_ostream<char,struct std::char_traits<char> > & __cdecl csf::edge::operator<<(class std::basic_ostream<char,struct std::char_traits<char> > &,struct csf::edge::DetectDirectConnectAvailableFsm::FsmEvent const &)` | 457 | Exported Function
`class std::basic_ostream<char,struct std::char_traits<char> > & __cdecl csf::edge::operator<<(class std::basic_ostream<char,struct std::char_traits<char> > &,enum csf::edge::EdgeConfigResponse::Result const &)` | 464 | Exported Function
`class std::basic_ostream<char,struct std::char_traits<char> > & __cdecl csf::edge::operator<<(class std::basic_ostream<char,struct std::char_traits<char> > &,enum csf::edge::GlobalEdgeState::GetEdgeConfigurationResult::Result const &)` | 465 | Exported Function
`class std::basic_ostream<char,struct std::char_traits<char> > & __cdecl csf::edge::operator<<(class std::basic_ostream<char,struct std::char_traits<char> > &,struct csf::edge::EdgeServiceRecordData const &)` | 456 | Exported Function
`class std::basic_ostream<char,struct std::char_traits<char> > & __cdecl csf::edge::operator<<(class std::basic_ostream<char,struct std::char_traits<char> > &,struct csf::edge::NetworkSensingEvent const &)` | 458 | Exported Function
`class std::basic_ostream<char,struct std::char_traits<char> > & __cdecl csf::edge::operator<<(class std::basic_ostream<char,struct std::char_traits<char> > &,struct csf::edge::DetectDirectConnectAvailableFsm::Statistics const &)` | 459 | Exported Function
`class std::basic_ostream<char,struct std::char_traits<char> > & __cdecl csf::edge::operator<<(class std::basic_ostream<char,struct std::char_traits<char> > &,struct csf::edge::DetectDirectConnectUnavailableFsm::Statistics const &)` | 460 | Exported Function
`class std::basic_ostream<char,struct std::char_traits<char> > & __cdecl csf::common::operator<<(class std::basic_ostream<char,struct std::char_traits<char> > &,class csf::common::Reactor const &)` | 452 | Exported Function
`class std::basic_ostream<char,struct std::char_traits<char> > & __cdecl csf::common::operator<<(class std::basic_ostream<char,struct std::char_traits<char> > &,enum csf::common::Policy::PolicyEnforcingResult::EnforcingResult)` | 454 | Exported Function
`class std::basic_ostream<char,struct std::char_traits<char> > & __cdecl csf::cert::operator<<(class std::basic_ostream<char,struct std::char_traits<char> > &,struct std::pair<bool,class std::set<enum csf::cert::InvalidCertNotificationManager::AcceptanceOptions::Options,struct std::less<enum csf::cert::InvalidCertNotificationManager::AcceptanceOptions::Options>,class std::allocator<enum csf::cert::InvalidCertNotificationManager::AcceptanceOptions::Options> > > const &)` | 436 | Exported Function
`class std::basic_ostream<char,struct std::char_traits<char> > & __cdecl csf::common::operator<<(class std::basic_ostream<char,struct std::char_traits<char> > &,class csf::common::FailureManagementPolicy)` | 453 | Exported Function
`class std::basic_ostream<char,struct std::char_traits<char> > & __cdecl csf::edge::operator<<(class std::basic_ostream<char,struct std::char_traits<char> > &,enum csf::edge::EdgeConfigHttpClient::Result const &)` | 462 | Exported Function
`class std::basic_ostream<char,struct std::char_traits<char> > & __cdecl csf::edge::operator<<(class std::basic_ostream<char,struct std::char_traits<char> > &,enum csf::edge::EdgeConfigRequest::Result const &)` | 463 | Exported Function
`class std::basic_ostream<char,struct std::char_traits<char> > & __cdecl csf::common::operator<<(class std::basic_ostream<char,struct std::char_traits<char> > &,enum csf::common::Policy::PolicyNature::Nature)` | 455 | Exported Function
`class std::basic_ostream<char,struct std::char_traits<char> > & __cdecl csf::edge::operator<<(class std::basic_ostream<char,struct std::char_traits<char> > &,class csf::edge::EdgeCapabilityPolicy)` | 467 | Exported Function
`const csf::edge::EdgeConfigHttpClient::``vftable'` | 506 | Exported Function
`private: static class std::shared_ptr<class csf::http::ProxyAuthenticationHandler> csf::http::ProxyAuthenticationHandler::instance_` | 842 | Exported Function
`private: static class std::shared_ptr<class csf::netutils::NetworkEventReporterObserver> csf::netutils::NetworkEventReporterObserver::instance_` | 841 | Exported Function
`private: static class std::set<struct std::pair<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> >,enum csf::http::CurlHttpUtils::RequestPhase::Phase>,struct std::less<struct std::pair<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> >,enum csf::http::CurlHttpUtils::RequestPhase::Phase> >,class std::allocator<struct std::pair<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> >,enum csf::http::CurlHttpUtils::RequestPhase::Phase> > > __cdecl csf::http::CurlHttpUtils::getPhaseMap(void)` | 800 | Exported Function
`private: static class std::shared_ptr<class csf::cert::CertVerifier> csf::cert::CertVerifierFactory::certVerifier` | 627 | Exported Function
`private: static enum csf::cert::CertAcceptanceDecision::Decision __cdecl csf::cert::CertVerificationFailureManager::managePolicyEnforcementResult(enum csf::common::Policy::PolicyEnforcingResult::EnforcingResult,class std::set<enum csf::cert::CertStatus::Status,struct std::less<enum csf::cert::CertStatus::Status>,class std::allocator<enum csf::cert::CertStatus::Status> >)` | 900 | Exported Function
`private: static long __cdecl csf::http::OpenSSLOptions::getDefaultOptions(void)` | 751 | Exported Function
`private: static class std::shared_ptr<class csf::ThreadPool> csf::netutils::NetworkEventReporterObserver::eventNotificationThreadPool_` | 712 | Exported Function
`private: static enum csf::cert::CertAcceptanceDecision::Decision __cdecl csf::cert::CertVerificationFailureManager::canBeAccepted(class std::shared_ptr<class csf::cert::CertificateData>,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::set<enum csf::cert::CertStatus::Status,struct std::less<enum csf::cert::CertStatus::Status>,class std::allocator<enum csf::cert::CertStatus::Status> > &,class std::shared_ptr<class csf::cert::InvalidCertManagementPolicy>,class csf::cert::CertificateCacheAccessor const &)` | 624 | Exported Function
`private: static bool __cdecl csf::http::CurlHttpUtils::setUrlWithSNI(class std::shared_ptr<class csf::http::HttpRequestData>,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 1024 | Exported Function
`private: static class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __cdecl csf::cert::KeyStrengthParserImpl::publicKeyTypeToString(int)` | 931 | Exported Function
`private: static bool __cdecl csf::http::CurlHttpUtils::setHeaders(class std::shared_ptr<class csf::http::HttpRequestData>,class std::shared_ptr<class std::vector<struct std::pair<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> >,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > >,class std::allocator<struct std::pair<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> >,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > > > > >)` | 991 | Exported Function
`private: static bool __cdecl csf::http::CurlHttpUtils::setUrlWithoutSNI(class std::shared_ptr<class csf::http::HttpRequestData>)` | 1025 | Exported Function
`private: static class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __cdecl csf::http::CurlHttpUtils::getPhaseKey(enum csf::http::CurlHttpUtils::RequestPhase::Phase)` | 799 | Exported Function
`private: static class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __cdecl csf::http::OpenSSLOptions::toString(long)` | 1051 | Exported Function
`private: static class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __cdecl csf::cert::KeyUsageParserImpl::basicKeyUsageAsString(unsigned long)` | 594 | Exported Function
`private: static class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __cdecl csf::cert::KeyUsageParserImpl::extendedKeyUsageAsString(unsigned long)` | 714 | Exported Function
`private: static long __cdecl csf::http::OpenSSLOptions::translateTlsVersions(long)` | 1056 | Exported Function
`private: void __thiscall csf::http::HttpNetworkEvent::notifySuccessfulFailoverEdgeEvents(enum csf::http::HttpClientResult::Result,class std::shared_ptr<class csf::http::HttpRequestData>)` | 913 | Exported Function
`private: void __thiscall csf::http::HttpRequestData::switchUrls(enum csf::http::HttpClientResult::Result)` | 1045 | Exported Function
`private: void __thiscall csf::http::HttpNetworkEvent::notifyHttpErrorEdgeEvents(enum csf::http::HttpClientResult::Result,class std::shared_ptr<class csf::http::HttpRequestData>,class std::shared_ptr<class csf::common::Policy>)` | 909 | Exported Function
`private: void __thiscall csf::http::HttpNetworkEvent::notifyHttpEvents(enum csf::http::HttpClientResult::Result)` | 910 | Exported Function
`protected: __thiscall csf::common::InputIndependentPolicy::InputIndependentPolicy(enum csf::common::Policy::PolicyNature::Nature)` | 112 | Exported Function
`protected: __thiscall csf::common::InputIndependentPolicy::InputIndependentPolicy(enum csf::common::Policy::PolicyNature::Nature,enum csf::common::Policy::PolicyFailureClass::FailureClass)` | 113 | Exported Function
`private: void __thiscall csf::http::ProxyAuthenticationHandler::executeHttpFunctions(bool)` | 713 | Exported Function
`private: void __thiscall csf::http::ProxyAuthenticationHandler::notifyOnProxyAuthenticationRequired(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 912 | Exported Function
`private: static void __cdecl csf::http::CurlHttpUtils::setIdentifiers(class std::shared_ptr<class csf::http::HttpRequestData>,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 995 | Exported Function
`private: unsigned int __thiscall csf::http::HttpRequestData::getNextRequestId(void)` | 791 | Exported Function
`private: static unsigned int csf::netutils::NetUtilsFactory::MAX_DEFAULT_THREADPOOL_SIZE` | 560 | Exported Function
`private: static unsigned int csf::netutils::NetUtilsFactory::MIN_DEFAULT_THREADPOOL_SIZE` | 561 | Exported Function
`private: void __thiscall csf::http::HttpNetworkEvent::notifyConnectionFailureEdgeEvents(enum csf::http::HttpClientResult::Result,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 907 | Exported Function
`private: void __thiscall csf::http::HttpNetworkEvent::notifyEdgeInfrastructureEvent(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 908 | Exported Function
`private: unsigned long __thiscall csf::cert::KeyUsageParserImpl::long2KUsage(unsigned long)` | 898 | Exported Function
`private: unsigned long __thiscall csf::cert::KeyUsageParserImpl::nid2ExKUsage(int)` | 905 | Exported Function
`private: static bool __cdecl csf::cert::KeyStrengthParserImpl::isKeyStrengthCheckRequiredForType(int)` | 864 | Exported Function
`const csf::http::CertVerifier::``vftable'` | 496 | Exported Function
`const csf::http::CurlAnswerEvaluator::``vftable'` | 501 | Exported Function
`const csf::edge::NetworkTester::``vftable'` | 532 | Exported Function
`const csf::edge::VisibilityChangeObserver::``vftable'` | 536 | Exported Function
`const csf::http::HttpClientListener::``vftable'` | 514 | Exported Function
`const csf::http::HttpNetworkEventReporter::``vftable'` | 515 | Exported Function
`const csf::http::EdgeTransformer::``vftable'` | 509 | Exported Function
`const csf::http::HttpClientData::``vftable'` | 513 | Exported Function
`const csf::edge::GetEdgeConfigurationListener::``vftable'` | 511 | Exported Function
`const csf::edge::GlobalEdgeStateObserver::``vftable'` | 512 | Exported Function
`const csf::edge::EdgeConfigRequest::``vftable'` | 507 | Exported Function
`const csf::edge::EdgeDetectionController::``vftable'` | 508 | Exported Function
`const csf::edge::NetworkSensingEventRegistrator::``vftable'` | 530 | Exported Function
`const csf::edge::NetworkSensingObserver::``vftable'` | 531 | Exported Function
`const csf::edge::InternalConnectivityObserver::``vftable'` | 517 | Exported Function
`const csf::edge::MRAPolicyManager::``vftable'` | 525 | Exported Function
`const csf::http::HttpProxyConfigurationReader::``vftable'` | 516 | Exported Function
`private: __thiscall csf::http::MultiHttpClientData::MultiHttpClientData(class std::shared_ptr<class csf::http::HttpNetworkEventReporter>,class std::shared_ptr<class csf::http::EdgeTransformer>,class std::shared_ptr<class csf::http::HttpRequestData>)` | 138 | Exported Function
`private: __thiscall csf::http::ProxyAuthenticationHandler::ProxyAuthenticationHandler(void)` | 179 | Exported Function
`private: __thiscall csf::cert::CertContainerImpl::CertContainerImpl(void)` | 23 | Exported Function
`private: __thiscall csf::edge::Timestamp::Timestamp(__int64)` | 199 | Exported Function
`private: bool __thiscall csf::http::HttpNetworkEvent::isOauthExpiredResponse(class std::shared_ptr<class csf::http::HttpRequestData>,class std::shared_ptr<class csf::common::Policy>)` | 867 | Exported Function
`private: class std::shared_ptr<class csf::http::BasicHttpClient> __thiscall csf::netutils::NetUtilsFactory::createBasicHttpClient(class std::shared_ptr<class csf::cert::CertVerifier>,class std::shared_ptr<class csf::ThreadPool>)` | 652 | Exported Function
`private: bool __thiscall csf::http::HttpNetworkEvent::isEdgeRequest(class std::shared_ptr<class csf::http::HttpRequestData>)` | 845 | Exported Function
`private: bool __thiscall csf::http::HttpNetworkEvent::isFailedOverEdgeRequest(class std::shared_ptr<class csf::http::HttpRequestData>)` | 852 | Exported Function
`const csf::http::ProxyAuthenticationHandler::``vftable'` | 535 | Exported Function
`const csf::netutils::NetworkEventCallback::``vftable'` | 527 | Exported Function
`const csf::http::MultiHttpClientData::``vftable'` | 526 | Exported Function
`const csf::http::ProxyAuthenticationCallback::``vftable'` | 534 | Exported Function
`int __cdecl csf::netutils::GlobalInit(void)` | 551 | Exported Function
`int __cdecl csf::netutils::GlobalInitLibCurlOnly(void)` | 552 | Exported Function
`const csf::netutils::NetworkEventReporter::``vftable'` | 528 | Exported Function
`const csf::netutils::NetworkEventReporterObserver::``vftable'` | 529 | Exported Function
`public: __thiscall csf::edge::EdgeDetectionDnsRecordReader::~EdgeDetectionDnsRecordReader(void)` | 243 | Exported Function
`public: class csf::cert::UserInteractingInvalidCertManagementPolicy::AvoidableUserInteractingInvalidCertManagementPolicyBuilder * __thiscall csf::cert::UserInteractingInvalidCertManagementPolicy::AvoidableUserInteractingInvalidCertManagementPolicyBuilder::acceptTransaction(enum csf::cert::CertStatus::Status,enum csf::cert::CertStatus::Status)` | 574 | Exported Function
`public: class csf::common::BackgroundTimerCallback & __thiscall csf::common::BackgroundTimerCallback::operator=(class csf::common::BackgroundTimerCallback const &)` | 309 | Exported Function
`public: class csf::cert::KeyUsageParserImpl & __thiscall csf::cert::KeyUsageParserImpl::operator=(class csf::cert::KeyUsageParserImpl const &)` | 393 | Exported Function
`public: class csf::cert::PlatformCertVerifier & __thiscall csf::cert::PlatformCertVerifier::operator=(class csf::cert::PlatformCertVerifier const &)` | 407 | Exported Function
`public: class csf::common::FipsUtils & __thiscall csf::common::FipsUtils::operator=(class csf::common::FipsUtils const &)` | 367 | Exported Function
`public: class csf::common::PolicySet::VerifyPoliciesResult & __thiscall csf::common::PolicySet::VerifyPoliciesResult::operator=(class csf::common::PolicySet::VerifyPoliciesResult const &)` | 433 | Exported Function
`public: class csf::common::DefaultPoliciesStoreObserver & __thiscall csf::common::DefaultPoliciesStoreObserver::operator=(class csf::common::DefaultPoliciesStoreObserver const &)` | 345 | Exported Function
`public: class csf::common::FipsUtils & __thiscall csf::common::FipsUtils::operator=(class csf::common::FipsUtils &&)` | 366 | Exported Function
`public: class csf::cert::KeyStrengthParserFactory & __thiscall csf::cert::KeyStrengthParserFactory::operator=(class csf::cert::KeyStrengthParserFactory const &)` | 387 | Exported Function
`public: class csf::cert::KeyStrengthParserImpl & __thiscall csf::cert::KeyStrengthParserImpl::operator=(class csf::cert::KeyStrengthParserImpl &&)` | 388 | Exported Function
`public: class csf::cert::InvalidCertListener & __thiscall csf::cert::InvalidCertListener::operator=(class csf::cert::InvalidCertListener const &)` | 384 | Exported Function
`public: class csf::cert::KeyStrengthParser & __thiscall csf::cert::KeyStrengthParser::operator=(class csf::cert::KeyStrengthParser const &)` | 386 | Exported Function
`public: class csf::cert::KeyUsageParserFactory & __thiscall csf::cert::KeyUsageParserFactory::operator=(class csf::cert::KeyUsageParserFactory const &)` | 391 | Exported Function
`public: class csf::cert::KeyUsageParserImpl & __thiscall csf::cert::KeyUsageParserImpl::operator=(class csf::cert::KeyUsageParserImpl &&)` | 392 | Exported Function
`public: class csf::cert::KeyStrengthParserImpl & __thiscall csf::cert::KeyStrengthParserImpl::operator=(class csf::cert::KeyStrengthParserImpl const &)` | 389 | Exported Function
`public: class csf::cert::KeyUsageParser & __thiscall csf::cert::KeyUsageParser::operator=(class csf::cert::KeyUsageParser const &)` | 390 | Exported Function
`public: class csf::common::PolicySet::VerifyPoliciesResult __thiscall csf::common::PolicySet::verifyInputIndependentPolicies(void)` | 1071 | Exported Function
`public: class csf::dns::QueryResponse & __thiscall csf::dns::QueryResponse::operator=(class csf::dns::QueryResponse const &)` | 418 | Exported Function
`public: class csf::dns::ServiceResourceRecord & __thiscall csf::dns::ServiceResourceRecord::operator=(class csf::dns::ServiceResourceRecord const &)` | 423 | Exported Function
`public: class csf::dns::PointerRecord & __thiscall csf::dns::PointerRecord::operator=(class csf::dns::PointerRecord const &)` | 408 | Exported Function
`public: class csf::dns::QueryResponse & __thiscall csf::dns::QueryResponse::operator=(class csf::dns::QueryResponse &&)` | 417 | Exported Function
`public: class csf::edge::CredentialsManager & __thiscall csf::edge::CredentialsManager::operator=(class csf::edge::CredentialsManager const &)` | 341 | Exported Function
`public: class csf::edge::EdgeConfig __thiscall csf::edge::RecentlyUsedServers::getEdgeConfig(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 761 | Exported Function
`public: class csf::dns::SOARecord & __thiscall csf::dns::SOARecord::operator=(class csf::dns::SOARecord const &)` | 420 | Exported Function
`public: class csf::edge::CcmcipServerManager & __thiscall csf::edge::CcmcipServerManager::operator=(class csf::edge::CcmcipServerManager const &)` | 310 | Exported Function
`public: class csf::common::SequenceNumber & __thiscall csf::common::SequenceNumber::operator=(class csf::common::SequenceNumber const &)` | 422 | Exported Function
`public: class csf::dns::DnsHostResolver & __thiscall csf::dns::DnsHostResolver::operator=(class csf::dns::DnsHostResolver const &)` | 346 | Exported Function
`public: class csf::common::Reactor::Event & __thiscall csf::common::Reactor::Event::operator=(class csf::common::Reactor::Event const &)` | 363 | Exported Function
`public: class csf::common::SequenceNumber & __thiscall csf::common::SequenceNumber::operator=(class csf::common::SequenceNumber &&)` | 421 | Exported Function
`public: class csf::dns::DnsUtilsInterface & __thiscall csf::dns::DnsUtilsInterface::operator=(class csf::dns::DnsUtilsInterface const &)` | 351 | Exported Function
`public: class csf::dns::DnsUtilsScopedSetCustomServerAddress & __thiscall csf::dns::DnsUtilsScopedSetCustomServerAddress::operator=(class csf::dns::DnsUtilsScopedSetCustomServerAddress const &)` | 352 | Exported Function
`public: class csf::dns::DnsUtilsImpl & __thiscall csf::dns::DnsUtilsImpl::operator=(class csf::dns::DnsUtilsImpl &&)` | 349 | Exported Function
`public: class csf::dns::DnsUtilsImpl & __thiscall csf::dns::DnsUtilsImpl::operator=(class csf::dns::DnsUtilsImpl const &)` | 350 | Exported Function
`public: class csf::cert::CertVerifierTask & __thiscall csf::cert::CertVerifierTask::operator=(class csf::cert::CertVerifierTask const &)` | 333 | Exported Function
`public: bool __thiscall csf::ip::IpAddress::isEmpty(void)const ` | 847 | Exported Function
`public: bool __thiscall csf::ip::IpAddress::isIpv4Address(void)const ` | 860 | Exported Function
`public: bool __thiscall csf::http::UnresolvedHostCache::isEmpty(void)` | 849 | Exported Function
`public: bool __thiscall csf::http::UnresolvedHostCache::isRecentlyUnresolved(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 873 | Exported Function
`public: bool __thiscall csf::ip::IpAddress::operator==(class csf::ip::IpAddress const &)const ` | 478 | Exported Function
`public: class csf::cert::AltNameParser & __thiscall csf::cert::AltNameParser::operator=(class csf::cert::AltNameParser const &)` | 305 | Exported Function
`public: bool __thiscall csf::ip::IpAddress::isIpv6Address(void)const ` | 862 | Exported Function
`public: bool __thiscall csf::ip::IpAddress::operator!=(class csf::ip::IpAddress const &)const ` | 484 | Exported Function
`public: bool __thiscall csf::edge::RecentlyUsedServers::isRecentlySucceeded(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 872 | Exported Function
`public: bool __thiscall csf::http::HttpClientData::getEdgeUsagePolicyCanBeIgnored(void)` | 765 | Exported Function
`public: bool __thiscall csf::edge::RecentlyUsedServers::isEmpty(void)` | 848 | Exported Function
`public: bool __thiscall csf::edge::RecentlyUsedServers::isRecentlyFailed(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 871 | Exported Function
`public: bool __thiscall csf::http::Request::shouldWaitUntilProxyCredentialReady(void)` | 1034 | Exported Function
`public: bool __thiscall csf::http::UnresolvedHostCache::hostCanBeResolved(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 837 | Exported Function
`public: bool __thiscall csf::http::HttpRequestData::hasFailoverUrl(void)const ` | 835 | Exported Function
`public: bool __thiscall csf::http::Request::getIsUseSystemProxy(void)` | 781 | Exported Function
`public: class csf::cert::AltNameParserFactory & __thiscall csf::cert::AltNameParserFactory::operator=(class csf::cert::AltNameParserFactory const &)` | 306 | Exported Function
`public: class csf::cert::CertUtils & __thiscall csf::cert::CertUtils::operator=(class csf::cert::CertUtils const &)` | 326 | Exported Function
`public: class csf::cert::CertVerificationFailureManager & __thiscall csf::cert::CertVerificationFailureManager::operator=(class csf::cert::CertVerificationFailureManager &&)` | 327 | Exported Function
`public: class csf::cert::CertStatus & __thiscall csf::cert::CertStatus::operator=(class csf::cert::CertStatus const &)` | 324 | Exported Function
`public: class csf::cert::CertUtils & __thiscall csf::cert::CertUtils::operator=(class csf::cert::CertUtils &&)` | 325 | Exported Function
`public: class csf::cert::CertVerifierFactory & __thiscall csf::cert::CertVerifierFactory::operator=(class csf::cert::CertVerifierFactory const &)` | 331 | Exported Function
`public: class csf::cert::CertVerifierTask & __thiscall csf::cert::CertVerifierTask::operator=(class csf::cert::CertVerifierTask &&)` | 332 | Exported Function
`public: class csf::cert::CertVerificationFailureManager & __thiscall csf::cert::CertVerificationFailureManager::operator=(class csf::cert::CertVerificationFailureManager const &)` | 328 | Exported Function
`public: class csf::cert::CertVerifierFactory & __thiscall csf::cert::CertVerifierFactory::operator=(class csf::cert::CertVerifierFactory &&)` | 330 | Exported Function
`public: class csf::cert::CertContainer & __thiscall csf::cert::CertContainer::operator=(class csf::cert::CertContainer const &)` | 315 | Exported Function
`public: class csf::cert::CertContainerFactory & __thiscall csf::cert::CertContainerFactory::operator=(class csf::cert::CertContainerFactory const &)` | 316 | Exported Function
`public: class csf::cert::CertCacheInterface & __thiscall csf::cert::CertCacheInterface::operator=(class csf::cert::CertCacheInterface &&)` | 313 | Exported Function
`public: class csf::cert::CertCacheInterface & __thiscall csf::cert::CertCacheInterface::operator=(class csf::cert::CertCacheInterface const &)` | 314 | Exported Function
`public: class csf::cert::CertificateVerificationListener & __thiscall csf::cert::CertificateVerificationListener::operator=(class csf::cert::CertificateVerificationListener const &)` | 336 | Exported Function
`public: class csf::cert::CertStatus & __thiscall csf::cert::CertStatus::operator=(class csf::cert::CertStatus &&)` | 323 | Exported Function
`public: class csf::cert::CertificateDataFactory & __thiscall csf::cert::CertificateDataFactory::operator=(class csf::cert::CertificateDataFactory const &)` | 334 | Exported Function
`public: class csf::cert::CertificateVerificationListener & __thiscall csf::cert::CertificateVerificationListener::operator=(class csf::cert::CertificateVerificationListener &&)` | 335 | Exported Function
`public: class csf::edge::EdgeConfigHttpClient & __thiscall csf::edge::EdgeConfigHttpClient::operator=(class csf::edge::EdgeConfigHttpClient const &)` | 353 | Exported Function
`public: class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __thiscall csf::common::Cookie::getValue(void)const ` | 824 | Exported Function
`public: class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __thiscall csf::common::EmailAddressParser::getDomain(void)` | 758 | Exported Function
`public: class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __thiscall csf::common::Cookie::getPath(void)const ` | 798 | Exported Function
`public: class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __thiscall csf::common::Cookie::getRawFormat(void)const ` | 808 | Exported Function
`public: class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __thiscall csf::edge::EdgeTransitionDetectionControllerImpl::getDetectDirectConnectUnavailableFsmState(void)const ` | 754 | Exported Function
`public: class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __thiscall csf::http::CommonCriteriaUsagePolicy::getCipherSuits(void)const ` | 741 | Exported Function
`public: class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __thiscall csf::common::EmailAddressParser::getUsername(void)` | 822 | Exported Function
`public: class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __thiscall csf::edge::EdgeTransitionDetectionControllerImpl::getDetectDirectConnectAvailableFsmState(void)const ` | 752 | Exported Function
`public: class csf::netutils::NetworkEventCallback & __thiscall csf::netutils::NetworkEventCallback::operator=(class csf::netutils::NetworkEventCallback const &)` | 397 | Exported Function
`public: class csf::netutils::NetworkEventReporter & __thiscall csf::netutils::NetworkEventReporter::operator=(class csf::netutils::NetworkEventReporter const &)` | 398 | Exported Function
`public: class csf::netutils::NetUtilsFactory & __thiscall csf::netutils::NetUtilsFactory::operator=(class csf::netutils::NetUtilsFactory &&)` | 395 | Exported Function
`public: class csf::netutils::NetUtilsFactory & __thiscall csf::netutils::NetUtilsFactory::operator=(class csf::netutils::NetUtilsFactory const &)` | 396 | Exported Function
`public: class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __thiscall csf::common::Cookie::getDomain(void)const ` | 757 | Exported Function
`public: class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __thiscall csf::common::Cookie::getName(void)const ` | 785 | Exported Function
`public: class csf::storage::EncryptFileUtils & __thiscall csf::storage::EncryptFileUtils::operator=(class csf::storage::EncryptFileUtils &&)` | 359 | Exported Function
`public: class csf::storage::EncryptFileUtils & __thiscall csf::storage::EncryptFileUtils::operator=(class csf::storage::EncryptFileUtils const &)` | 360 | Exported Function
`public: class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __thiscall csf::http::HttpRequestData::formattedRequestID(void)const ` | 726 | Exported Function
`public: class std::shared_ptr<class csf::common::Policy> __thiscall csf::cert::IgnoreInvalidCertConditionPolicy::stripOut(class std::shared_ptr<class csf::cert::IgnoreInvalidCertConditionPolicy>)` | 1043 | Exported Function
`public: class std::shared_ptr<class csf::common::Policy> __thiscall csf::http::HttpClientData::getEdgePolicy(void)` | 762 | Exported Function
`public: class std::set<class std::shared_ptr<class csf::common::Policy>,struct std::less<class std::shared_ptr<class csf::common::Policy> >,class std::allocator<class std::shared_ptr<class csf::common::Policy> > > const __thiscall csf::common::PolicySet::getAll(void)` | 732 | Exported Function
`public: class std::shared_ptr<class csf::common::Policy> __thiscall csf::cert::IgnoreInvalidCertConditionPolicy::merge(class std::shared_ptr<class csf::cert::IgnoreInvalidCertConditionPolicy>)` | 903 | Exported Function
`public: class std::shared_ptr<class csf::dns::DnsQuery> __thiscall std::enable_shared_from_this<class csf::dns::DnsQuery>::shared_from_this(void)` | 1028 | Exported Function
`public: class std::shared_ptr<class csf::edge::EdgeConfigRequest> __thiscall csf::netutils::NetUtilsFactory::createEdgeConfigRequest(void)` | 658 | Exported Function
`public: class std::shared_ptr<class csf::common::Policy> const __thiscall csf::common::PolicySet::getPolicy(enum csf::common::Policy::PolicyNature::Nature)const ` | 803 | Exported Function
`public: class std::shared_ptr<class csf::dns::DnsQuery const > __thiscall std::enable_shared_from_this<class csf::dns::DnsQuery>::shared_from_this(void)const ` | 1029 | Exported Function
`public: class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __thiscall csf::http::Proxy::serialize(void)const ` | 963 | Exported Function
`public: class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __thiscall csf::http::Request::serialize(void)const ` | 964 | Exported Function
`public: class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __thiscall csf::http::Proxy::getBypassList(void)const ` | 735 | Exported Function
`public: class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __thiscall csf::http::Proxy::getURL(void)const ` | 821 | Exported Function
`public: class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __thiscall csf::netutils::TomcatPortModifier::changeDefaultTomcatPort(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 628 | Exported Function
`public: class std::set<class std::shared_ptr<class csf::common::Policy>,struct std::less<class std::shared_ptr<class csf::common::Policy> >,class std::allocator<class std::shared_ptr<class csf::common::Policy> > > const __thiscall csf::common::PolicyDriven::getAllPolicies(void)` | 734 | Exported Function
`public: class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __thiscall csf::http::Response::getHeader(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)const ` | 770 | Exported Function
`public: class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __thiscall csf::ip::IpAddress::getAddress(void)const ` | 731 | Exported Function
`public: class csf::ip::ConnectionInformationResult __thiscall csf::ip::ConnectionInformation::getConnectionInformationForHost(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,unsigned long,unsigned long,bool,enum csf::ip::IpFamilyPreferencePolicy::PolicyValue::Value)const ` | 744 | Exported Function
`public: class csf::edge::NetworkSensingObserver & __thiscall csf::edge::NetworkSensingObserver::operator=(class csf::edge::NetworkSensingObserver const &)` | 403 | Exported Function
`public: class csf::edge::NetworkTester & __thiscall csf::edge::NetworkTester::operator=(class csf::edge::NetworkTester const &)` | 404 | Exported Function
`public: class csf::edge::NetworkSensingEventRegistrator & __thiscall csf::edge::NetworkSensingEventRegistrator::operator=(class csf::edge::NetworkSensingEventRegistrator &&)` | 401 | Exported Function
`public: class csf::edge::NetworkSensingEventRegistrator & __thiscall csf::edge::NetworkSensingEventRegistrator::operator=(class csf::edge::NetworkSensingEventRegistrator const &)` | 402 | Exported Function
`public: class csf::edge::VisibilityChangeObserver & __thiscall csf::edge::VisibilityChangeObserver::operator=(class csf::edge::VisibilityChangeObserver const &)` | 434 | Exported Function
`public: class csf::http::CertVerifier & __thiscall csf::http::CertVerifier::operator=(class csf::http::CertVerifier const &)` | 329 | Exported Function
`public: class csf::edge::PolicyDrivenEdgeVisibility & __thiscall csf::edge::PolicyDrivenEdgeVisibility::operator=(class csf::edge::PolicyDrivenEdgeVisibility const &)` | 409 | Exported Function
`public: class csf::edge::Timestamp & __thiscall csf::edge::Timestamp::operator=(class csf::edge::Timestamp const &)` | 430 | Exported Function
`public: class csf::edge::EdgeDetectionController & __thiscall csf::edge::EdgeDetectionController::operator=(class csf::edge::EdgeDetectionController const &)` | 356 | Exported Function
`public: class csf::edge::GetEdgeConfigurationListener & __thiscall csf::edge::GetEdgeConfigurationListener::operator=(class csf::edge::GetEdgeConfigurationListener const &)` | 368 | Exported Function
`public: class csf::edge::EdgeConfigRequest & __thiscall csf::edge::EdgeConfigRequest::operator=(class csf::edge::EdgeConfigRequest const &)` | 354 | Exported Function
`public: class csf::edge::EdgeConfigResponse & __thiscall csf::edge::EdgeConfigResponse::operator=(class csf::edge::EdgeConfigResponse const &)` | 355 | Exported Function
`public: class csf::edge::IpInterfaceChangeMonitor & __thiscall csf::edge::IpInterfaceChangeMonitor::operator=(class csf::edge::IpInterfaceChangeMonitor const &)` | 385 | Exported Function
`public: class csf::edge::MRAPolicyManager & __thiscall csf::edge::MRAPolicyManager::operator=(class csf::edge::MRAPolicyManager const &)` | 394 | Exported Function
`public: class csf::edge::GlobalEdgeStateObserver & __thiscall csf::edge::GlobalEdgeStateObserver::operator=(class csf::edge::GlobalEdgeStateObserver const &)` | 369 | Exported Function
`public: class csf::edge::InternalConnectivityObserver & __thiscall csf::edge::InternalConnectivityObserver::operator=(class csf::edge::InternalConnectivityObserver const &)` | 383 | Exported Function
`public: class csf::http::CurlAnswerEvaluator & __thiscall csf::http::CurlAnswerEvaluator::operator=(class csf::http::CurlAnswerEvaluator const &)` | 342 | Exported Function
`public: class csf::http::OpenSSLOptions & __thiscall csf::http::OpenSSLOptions::operator=(class csf::http::OpenSSLOptions &&)` | 405 | Exported Function
`public: class csf::http::OpenSSLOptions & __thiscall csf::http::OpenSSLOptions::operator=(class csf::http::OpenSSLOptions const &)` | 406 | Exported Function
`public: class csf::http::HttpUtils & __thiscall csf::http::HttpUtils::operator=(class csf::http::HttpUtils &&)` | 381 | Exported Function
`public: class csf::http::HttpUtils & __thiscall csf::http::HttpUtils::operator=(class csf::http::HttpUtils const &)` | 382 | Exported Function
`public: class csf::ip::ConnectionInformationResult & __thiscall csf::ip::ConnectionInformationResult::operator=(class csf::ip::ConnectionInformationResult &&)` | 339 | Exported Function
`public: class csf::ip::ConnectionInformationResult & __thiscall csf::ip::ConnectionInformationResult::operator=(class csf::ip::ConnectionInformationResult const &)` | 340 | Exported Function
`public: class csf::http::ProxyAuthenticationCallback & __thiscall csf::http::ProxyAuthenticationCallback::operator=(class csf::http::ProxyAuthenticationCallback const &)` | 416 | Exported Function
`public: class csf::http::RequestWrapper & __thiscall csf::http::RequestWrapper::operator=(class csf::http::RequestWrapper const &)` | 419 | Exported Function
`public: class csf::http::EdgeTransformer & __thiscall csf::http::EdgeTransformer::operator=(class csf::http::EdgeTransformer const &)` | 358 | Exported Function
`public: class csf::http::HttpClientListener & __thiscall csf::http::HttpClientListener::operator=(class csf::http::HttpClientListener const &)` | 372 | Exported Function
`public: class csf::http::CurlHttpUtils & __thiscall csf::http::CurlHttpUtils::operator=(class csf::http::CurlHttpUtils &&)` | 343 | Exported Function
`public: class csf::http::CurlHttpUtils & __thiscall csf::http::CurlHttpUtils::operator=(class csf::http::CurlHttpUtils const &)` | 344 | Exported Function
`public: class csf::http::HttpNetworkEventReporter & __thiscall csf::http::HttpNetworkEventReporter::operator=(class csf::http::HttpNetworkEventReporter const &)` | 379 | Exported Function
`public: class csf::http::HttpProxyConfigurationReader & __thiscall csf::http::HttpProxyConfigurationReader::operator=(class csf::http::HttpProxyConfigurationReader const &)` | 380 | Exported Function
`public: class csf::http::HttpNetworkEvent & __thiscall csf::http::HttpNetworkEvent::operator=(class csf::http::HttpNetworkEvent &&)` | 377 | Exported Function
`public: class csf::http::HttpNetworkEvent & __thiscall csf::http::HttpNetworkEvent::operator=(class csf::http::HttpNetworkEvent const &)` | 378 | Exported Function
`public: bool __thiscall csf::edge::RecentlyUsedServers::getCachedEdgeConfig(class csf::edge::EdgeConfig &)` | 738 | Exported Function
`public: __thiscall csf::edge::Timestamp::Timestamp(class csf::edge::Timestamp const &)` | 200 | Exported Function
`public: __thiscall csf::edge::Timestamp::Timestamp(void)` | 201 | Exported Function
`public: __thiscall csf::edge::RecentlyUsedServers::RecentlyUsedServers(void)` | 184 | Exported Function
`public: __thiscall csf::edge::TcpEndpoint::TcpEndpoint(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,unsigned short)` | 198 | Exported Function
`public: __thiscall csf::edge::VisibilityChangeObserver::VisibilityChangeObserver(void)` | 209 | Exported Function
`public: __thiscall csf::http::CertVerifier::CertVerifier(class csf::http::CertVerifier const &)` | 30 | Exported Function
`public: __thiscall csf::edge::Timestamp::~Timestamp(void)` | 296 | Exported Function
`public: __thiscall csf::edge::VisibilityChangeObserver::VisibilityChangeObserver(class csf::edge::VisibilityChangeObserver const &)` | 208 | Exported Function
`public: __thiscall csf::edge::OnPremService::OnPremService(void)` | 163 | Exported Function
`public: __thiscall csf::edge::OnPremServiceLocation::OnPremServiceLocation(void)` | 164 | Exported Function
`public: __thiscall csf::edge::NetworkTester::NetworkTester(class csf::edge::NetworkTester const &)` | 159 | Exported Function
`public: __thiscall csf::edge::NetworkTester::NetworkTester(void)` | 160 | Exported Function
`public: __thiscall csf::edge::PolicyDrivenEdgeVisibility::~PolicyDrivenEdgeVisibility(void)` | 283 | Exported Function
`public: __thiscall csf::edge::ReachableEdgeServerManager::ReachableEdgeServerManager(void)` | 182 | Exported Function
`public: __thiscall csf::edge::PolicyDrivenEdgeVisibility::PolicyDrivenEdgeVisibility(bool)` | 172 | Exported Function
`public: __thiscall csf::edge::PolicyDrivenEdgeVisibility::PolicyDrivenEdgeVisibility(class csf::edge::PolicyDrivenEdgeVisibility const &)` | 171 | Exported Function
`public: __thiscall csf::http::CertVerifier::CertVerifier(void)` | 31 | Exported Function
`public: __thiscall csf::http::HttpNetworkEvent::~HttpNetworkEvent(void)` | 255 | Exported Function
`public: __thiscall csf::http::HttpNetworkEventReporter::HttpNetworkEventReporter(class csf::http::HttpNetworkEventReporter const &)` | 107 | Exported Function
`public: __thiscall csf::http::HttpNetworkEvent::HttpNetworkEvent(class csf::http::HttpNetworkEvent const &)` | 104 | Exported Function
`public: __thiscall csf::http::HttpNetworkEvent::HttpNetworkEvent(class std::shared_ptr<class csf::http::HttpNetworkEventReporter>,class std::shared_ptr<class csf::http::EdgeTransformer>)` | 105 | Exported Function
`public: __thiscall csf::http::HttpRequestData::HttpRequestData(class std::shared_ptr<class csf::http::Request>,class std::shared_ptr<class csf::http::CertVerifier>)` | 110 | Exported Function
`public: __thiscall csf::http::HttpRequestData::~HttpRequestData(void)` | 258 | Exported Function
`public: __thiscall csf::http::HttpProxyConfigurationReader::HttpProxyConfigurationReader(class csf::http::HttpProxyConfigurationReader const &)` | 108 | Exported Function
`public: __thiscall csf::http::HttpProxyConfigurationReader::HttpProxyConfigurationReader(void)` | 109 | Exported Function
`public: __thiscall csf::http::EdgeTransformer::EdgeTransformer(class csf::http::EdgeTransformer const &)` | 85 | Exported Function
`public: __thiscall csf::http::EdgeTransformer::EdgeTransformer(void)` | 86 | Exported Function
`public: __thiscall csf::http::CurlAnswerEvaluator::CurlAnswerEvaluator(class csf::http::CurlAnswerEvaluator const &)` | 52 | Exported Function
`public: __thiscall csf::http::CurlAnswerEvaluator::CurlAnswerEvaluator(void)` | 53 | Exported Function
`public: __thiscall csf::http::HttpClientListener::HttpClientListener(void)` | 101 | Exported Function
`public: __thiscall csf::http::HttpNetworkEvent::HttpNetworkEvent(class csf::http::HttpNetworkEvent &&)` | 103 | Exported Function
`public: __thiscall csf::http::HttpClientData::HttpClientData(class csf::http::HttpClientData const &)` | 99 | Exported Function
`public: __thiscall csf::http::HttpClientListener::HttpClientListener(class csf::http::HttpClientListener const &)` | 100 | Exported Function
`public: __thiscall csf::edge::NetworkSensingObserver::NetworkSensingObserver(void)` | 158 | Exported Function
`public: __thiscall csf::edge::EdgeUtils::TransformHttpUrlResult::TransformHttpUrlResult(class std::deque<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> >,class std::allocator<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > > > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,enum csf::edge::EdgeUtils::TransformHttpUrlResult::Result)` | 204 | Exported Function
`public: __thiscall csf::edge::EdgeUtils::TransformHttpUrlResult::TransformHttpUrlResult(class std::deque<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> >,class std::allocator<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > > > const &,enum csf::edge::EdgeUtils::TransformHttpUrlResult::Result)` | 205 | Exported Function
`public: __thiscall csf::edge::EdgeTransitionDetectionController::StartMonitoringFromInsideEvent::StartMonitoringFromInsideEvent(struct csf::edge::DetectionParameters const &)` | 193 | Exported Function
`public: __thiscall csf::edge::EdgeTransitionDetectionController::StartPollingFromOutsideEvent::StartPollingFromOutsideEvent(struct csf::edge::DetectionParameters const &)` | 194 | Exported Function
`public: __thiscall csf::edge::GetEdgeConfigurationListener::GetEdgeConfigurationListener(void)` | 93 | Exported Function
`public: __thiscall csf::edge::GlobalEdgeState::GetEdgeConfigurationResult::GetEdgeConfigurationResult(class csf::edge::EdgeConfig const &,enum csf::edge::GlobalEdgeState::GetEdgeConfigurationResult::Result)` | 94 | Exported Function
`public: __thiscall csf::edge::EnterpriseNetworkSensor::EnterpriseNetworkSensor(enum csf::edge::EnterpriseNetworkSensorStrategy::Strategy,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 89 | Exported Function
`public: __thiscall csf::edge::GetEdgeConfigurationListener::GetEdgeConfigurationListener(class csf::edge::GetEdgeConfigurationListener const &)` | 92 | Exported Function
`public: __thiscall csf::edge::EdgeServiceLocation::EdgeServiceLocation(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> >,unsigned int,unsigned int)` | 81 | Exported Function
`public: __thiscall csf::edge::EdgeServiceLocation::EdgeServiceLocation(void)` | 82 | Exported Function
`public: __thiscall csf::edge::EdgeInfrastructureEvent::EdgeInfrastructureEvent(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 78 | Exported Function
`public: __thiscall csf::edge::EdgeInfrastructureEventControllerImpl::EdgeInfrastructureEventControllerImpl(class std::shared_ptr<class csf::edge::GlobalEdgeState>)` | 80 | Exported Function
`public: __thiscall csf::edge::EdgeTransitionDetectionController::ControllerEvent::ControllerEvent(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 45 | Exported Function
`public: __thiscall csf::edge::EdgeTransitionDetectionController::NetworkActivityEvent::NetworkActivityEvent(void)` | 144 | Exported Function
`public: __thiscall csf::edge::EdgeServiceRecordData::EdgeServiceRecordData(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> >,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> >,unsigned int,unsigned int,unsigned int)` | 83 | Exported Function
`public: __thiscall csf::edge::EdgeServiceRecordData::EdgeServiceRecordData(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> >,unsigned int,unsigned int,unsigned int)` | 84 | Exported Function
`public: __thiscall csf::edge::GlobalEdgeStateObserver::GlobalEdgeStateObserver(class csf::edge::GlobalEdgeStateObserver const &)` | 95 | Exported Function
`public: __thiscall csf::edge::NetworkSensingEvent::NetworkSensingEvent(struct csf::edge::NetworkSensingEvent &&)` | 151 | Exported Function
`public: __thiscall csf::edge::NetworkSensingEvent::NetworkSensingEvent(struct csf::edge::NetworkSensingEvent const &)` | 152 | Exported Function
`public: __thiscall csf::edge::MRAPolicyManager::MRAPolicyManager(void)` | 137 | Exported Function
`public: __thiscall csf::edge::NetworkSensingEvent::NetworkSensingEvent(bool,bool,bool,bool,enum csf::edge::NetworkSensingEvent::VisibilityMode,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 153 | Exported Function
`public: __thiscall csf::edge::NetworkSensingEventRegistrator::NetworkSensingEventRegistrator(class csf::edge::NetworkSensingEventRegistrator const &)` | 156 | Exported Function
`public: __thiscall csf::edge::NetworkSensingObserver::NetworkSensingObserver(class csf::edge::NetworkSensingObserver const &)` | 157 | Exported Function
`public: __thiscall csf::edge::NetworkSensingEvent::~NetworkSensingEvent(void)` | 276 | Exported Function
`public: __thiscall csf::edge::NetworkSensingEventRegistrator::NetworkSensingEventRegistrator(class csf::edge::NetworkSensingEventRegistrator &&)` | 155 | Exported Function
`public: __thiscall csf::edge::InternalConnectivityObserver::InternalConnectivityObserver(void)` | 115 | Exported Function
`public: __thiscall csf::edge::InternalNetworkVisibilityTester::InternalNetworkVisibilityTester(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::vector<struct csf::edge::TcpEndpoint,class std::allocator<struct csf::edge::TcpEndpoint> > const &,class std::shared_ptr<class csf::edge::EnterpriseNetworkSensor>)` | 117 | Exported Function
`public: __thiscall csf::edge::GlobalEdgeStateObserver::GlobalEdgeStateObserver(void)` | 96 | Exported Function
`public: __thiscall csf::edge::InternalConnectivityObserver::InternalConnectivityObserver(class csf::edge::InternalConnectivityObserver const &)` | 114 | Exported Function
`public: __thiscall csf::edge::IpInterfaceChangeMonitor::~IpInterfaceChangeMonitor(void)` | 264 | Exported Function
`public: __thiscall csf::edge::MRAPolicyManager::MRAPolicyManager(class csf::edge::MRAPolicyManager const &)` | 136 | Exported Function
`public: __thiscall csf::edge::IpInterfaceChangeLocalAddress::IpInterfaceChangeLocalAddress(void)` | 120 | Exported Function
`public: __thiscall csf::edge::IpInterfaceChangeMonitor::IpInterfaceChangeMonitor(class csf::edge::EdgeTransitionDetectionController *)` | 121 | Exported Function
`public: __thiscall csf::http::HttpRequestOptions::HttpRequestOptions(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 111 | Exported Function
`public: bool __thiscall csf::edge::EdgeConfig::operator==(class csf::edge::EdgeConfig const &)const ` | 476 | Exported Function
`public: bool __thiscall csf::edge::EdgeDetectionDnsRecordReader::queryCiscoUdsSrvRecord(struct csf::edge::ServiceRecord &)const ` | 932 | Exported Function
`public: bool __thiscall csf::common::Reactor::isProcessingEvents(void)const ` | 869 | Exported Function
`public: bool __thiscall csf::edge::Credentials::isSameCredentials(struct csf::edge::Credentials const &)` | 877 | Exported Function
`public: bool __thiscall csf::edge::EdgeDetectionDnsRecordReader::queryCollabEdgeSrvRecord(void)const ` | 935 | Exported Function
`public: bool __thiscall csf::edge::EdgeDetectionDnsRecordReader::queryCuploginSrvRecord(struct csf::edge::ServiceRecord &)const ` | 936 | Exported Function
`public: bool __thiscall csf::edge::EdgeDetectionDnsRecordReader::queryCollabEdgeSrvRecord(class std::vector<struct csf::edge::EdgeServiceRecordData,class std::allocator<struct csf::edge::EdgeServiceRecordData> > &)const ` | 933 | Exported Function
`public: bool __thiscall csf::edge::EdgeDetectionDnsRecordReader::queryCollabEdgeSrvRecord(class std::vector<struct csf::edge::EdgeServiceRecordData,class std::allocator<struct csf::edge::EdgeServiceRecordData> > &,int &)const ` | 934 | Exported Function
`public: bool __thiscall csf::cert::XmppCertVerifier::verifyXmppCertificateAsync(struct x509_store_ctx_st const *,class std::vector<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> >,class std::allocator<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > > > const &,class std::shared_ptr<class csf::cert::CertificateVerificationListener>,struct csf::cert::CertResult &,unsigned int &)` | 1079 | Exported Function
`public: bool __thiscall csf::common::BackgroundTimerImpl::isExpired(void)` | 851 | Exported Function
`public: bool __thiscall csf::cert::UserInteractingInvalidCertManagementPolicy::verifyEnforceabilityWithoutUserInteraction(class std::set<enum csf::cert::CertStatus::Status,struct std::less<enum csf::cert::CertStatus::Status>,class std::allocator<enum csf::cert::CertStatus::Status> > const &,class std::set<enum csf::cert::CertStatus::Status,struct std::less<enum csf::cert::CertStatus::Status>,class std::allocator<enum csf::cert::CertStatus::Status> > const &)const ` | 1069 | Exported Function
`public: bool __thiscall csf::cert::XmppCertVerifier::verifyXmppCertificateAsync(struct x509_store_ctx_st const *,class std::vector<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> >,class std::allocator<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > > > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::shared_ptr<class csf::cert::CertificateVerificationListener>,struct csf::cert::CertResult &,unsigned int &)` | 1078 | Exported Function
`public: bool __thiscall csf::common::Cookie::isTailMatchAllowed(void)const ` | 882 | Exported Function
`public: bool __thiscall csf::common::Cookie::operator==(class csf::common::Cookie const &)const ` | 475 | Exported Function
`public: bool __thiscall csf::common::Cookie::isEmpty(void)const ` | 846 | Exported Function
`public: bool __thiscall csf::common::Cookie::isSecureConnectionRequired(void)const ` | 878 | Exported Function
`public: bool __thiscall csf::edge::EdgeService::isServiceAvailable(void)const ` | 879 | Exported Function
`public: bool __thiscall csf::edge::PolicyDrivenEdgeVisibility::operator==(class csf::edge::PolicyDrivenEdgeVisibility const &)` | 480 | Exported Function
`public: bool __thiscall csf::edge::PolicyDrivenEdgeVisibility::operator==(class csf::edge::PolicyDrivenEdgeVisibility const &)const ` | 481 | Exported Function
`public: bool __thiscall csf::edge::PolicyDrivenEdgeVisibility::operator!=(class csf::edge::PolicyDrivenEdgeVisibility const &)` | 486 | Exported Function
`public: bool __thiscall csf::edge::PolicyDrivenEdgeVisibility::operator!=(class csf::edge::PolicyDrivenEdgeVisibility const &)const ` | 487 | Exported Function
`public: bool __thiscall csf::edge::RecentlyUsedServers::addFailedServer(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,int)` | 579 | Exported Function
`public: bool __thiscall csf::edge::RecentlyUsedServers::addSuccessfulServer(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class csf::edge::EdgeConfig const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 591 | Exported Function
`public: bool __thiscall csf::edge::ReachableEdgeServerManager::edgeServerRecordExists(struct csf::edge::EdgeServiceRecordData const &,class std::vector<struct csf::edge::EdgeServiceRecordData,class std::allocator<struct csf::edge::EdgeServiceRecordData> > const &)` | 685 | Exported Function
`public: bool __thiscall csf::edge::ReachableEdgeServerManager::updateEdgeSrvRecordsWithSucceededRecord(class std::vector<struct csf::edge::EdgeServiceRecordData,class std::allocator<struct csf::edge::EdgeServiceRecordData> > &)` | 1058 | Exported Function
`public: bool __thiscall csf::edge::EdgeServiceRecordData::operator>(struct csf::edge::EdgeServiceRecordData const &)const ` | 488 | Exported Function
`public: bool __thiscall csf::edge::IpInterfaceChangeLocalAddress::empty(void)const ` | 686 | Exported Function
`public: bool __thiscall csf::edge::EdgeService::operator!=(struct csf::edge::EdgeService const &)const ` | 483 | Exported Function
`public: bool __thiscall csf::edge::EdgeServiceRecordData::operator==(struct csf::edge::EdgeServiceRecordData const &)const ` | 477 | Exported Function
`public: bool __thiscall csf::edge::OnPremService::operator!=(struct csf::edge::OnPremService const &)const ` | 485 | Exported Function
`public: bool __thiscall csf::edge::PolicyDrivenEdgeVisibility::isVisible(void)const ` | 886 | Exported Function
`public: bool __thiscall csf::edge::IpInterfaceChangeLocalAddress::operator==(class csf::edge::IpInterfaceChangeLocalAddress const &)const ` | 479 | Exported Function
`public: bool __thiscall csf::edge::IpInterfaceChangeMonitor::isIpAddressChanged(void)` | 859 | Exported Function
`public: bool __thiscall csf::cert::InvalidCertNotificationManager::isInitialized(void)` | 856 | Exported Function
`public: __thiscall csf::http::RequestWrapper::RequestWrapper(class csf::http::RequestWrapper const &)` | 187 | Exported Function
`public: __thiscall csf::http::RequestWrapper::RequestWrapper(class std::shared_ptr<class csf::http::Request>)` | 188 | Exported Function
`public: __thiscall csf::http::Request::Request(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 185 | Exported Function
`public: __thiscall csf::http::Request::Request(class std::shared_ptr<struct csf::http::HttpRequestOptions>)` | 186 | Exported Function
`public: __thiscall csf::http::Response::Response(void)` | 190 | Exported Function
`public: __thiscall csf::http::SystemProxyResolver::SystemProxyResolver(void)` | 197 | Exported Function
`public: __thiscall csf::http::RequestWrapper::RequestWrapper(class std::shared_ptr<class csf::http::Request>,double,enum csf::http::HTTPFileOperation::Method,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> >)` | 189 | Exported Function
`public: __thiscall csf::http::RequestWrapper::~RequestWrapper(void)` | 291 | Exported Function
`public: __thiscall csf::http::ProgressData::ProgressData(void)` | 174 | Exported Function
`public: __thiscall csf::http::Proxy::Proxy(void)` | 176 | Exported Function
`public: __thiscall csf::http::MultiformRequest::MultiformRequest(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 140 | Exported Function
`public: __thiscall csf::http::MultiHttpClientData::MultiHttpClientData(class csf::http::MultiHttpClientData const &)` | 139 | Exported Function
`public: __thiscall csf::http::ProxyAuthenticationCallback::ProxyAuthenticationCallback(void)` | 178 | Exported Function
`public: __thiscall csf::http::ProxyBypassReader::ProxyBypassReader(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> >)` | 180 | Exported Function
`public: __thiscall csf::http::Proxy::~Proxy(void)` | 284 | Exported Function
`public: __thiscall csf::http::ProxyAuthenticationCallback::ProxyAuthenticationCallback(class csf::http::ProxyAuthenticationCallback const &)` | 177 | Exported Function
`public: __thiscall csf::http::UnresolvedHostCache::UnresolvedHostCache(class std::shared_ptr<class csf::dns::DnsHostResolver>)` | 206 | Exported Function
`public: __thiscall csf::netutils::NetworkEventCallback::NetworkEventCallback(class csf::netutils::NetworkEventCallback const &)` | 145 | Exported Function
`public: __thiscall csf::netutils::NetworkEventCallback::NetworkEventCallback(void)` | 146 | Exported Function
`public: __thiscall csf::netutils::adapters::HttpEventReporterAdapter::HttpEventReporterAdapter(class std::shared_ptr<class csf::netutils::NetworkEventReporter>)` | 102 | Exported Function
`public: __thiscall csf::netutils::NetUtilsFactory::NetUtilsFactory(void)` | 143 | Exported Function
`public: __thiscall csf::netutils::TomcatPortModifier::TomcatPortModifier(class std::shared_ptr<class csf::edge::EdgeDetectionController>)` | 202 | Exported Function
`public: __thiscall csf::netutils::TomcatPortModifier::TomcatPortModifier(void)` | 203 | Exported Function
`public: __thiscall csf::netutils::NetworkEventReporter::NetworkEventReporter(class csf::netutils::NetworkEventReporter const &)` | 148 | Exported Function
`public: __thiscall csf::netutils::NetworkEventReporterImpl::NetworkEventReporterImpl(class std::shared_ptr<class csf::netutils::NetworkEventReporterObserver>)` | 149 | Exported Function
`public: __thiscall csf::ip::ConnectionInformationResult::ConnectionInformationResult(enum csf::ip::ConnectionInformationResult::Result,class csf::ip::IpAddress,class csf::ip::IpAddress)` | 44 | Exported Function
`public: __thiscall csf::ip::ConnectionInformationResult::~ConnectionInformationResult(void)` | 229 | Exported Function
`public: __thiscall csf::ip::ConnectionInformationResult::ConnectionInformationResult(class csf::ip::ConnectionInformationResult &&)` | 42 | Exported Function
`public: __thiscall csf::ip::ConnectionInformationResult::ConnectionInformationResult(class csf::ip::ConnectionInformationResult const &)` | 43 | Exported Function
`public: __thiscall csf::netutils::adapters::EdgeUtilsAdapter::EdgeUtilsAdapter(class std::shared_ptr<class csf::edge::EdgeUtils>)` | 87 | Exported Function
`public: __thiscall csf::netutils::adapters::HttpCertAdapter::HttpCertAdapter(class std::shared_ptr<class csf::cert::CertVerifier>)` | 97 | Exported Function
`public: __thiscall csf::ip::Nat64PrefixParser::Nat64PrefixParser(class csf::ip::Ipv6Address const &)` | 142 | Exported Function
`public: __thiscall csf::netutils::adapters::EdgeHttpAdapter::EdgeHttpAdapter(void)` | 77 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `59C5C9F46EA82C4C743981566B64BD6C`
* Thumbprint: `475DAEE5A6CC149389EFDE176DEA526C627D203A`
* Issuer: CN=Symantec Class 3 SHA256 Code Signing CA - G2, OU=Symantec Trust Network, O=Symantec Corporation, C=US
* Subject: CN=Cisco Systems Inc., O=Cisco Systems Inc., L=San Jose, S=California, C=US

## File Metadata

* Original Filename: 
* Product Name: 
* Company Name: 
* File Version: 
* Product Version: 
* Language: 
* Legal Copyright: 
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/73b50c8df89da987b8e51be37269023e7ed23fdd37408762ecc35ae4afb5a4e7/detection/




MIT License. Copyright (c) 2020 Strontic.


