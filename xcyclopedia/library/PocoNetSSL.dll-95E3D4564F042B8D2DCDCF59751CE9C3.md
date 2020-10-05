---
title: PocoNetSSL.dll | This file is part of the POCO C++ Libraries.
excerpt: What is PocoNetSSL.dll?
---

# PocoNetSSL.dll 

* File Path: `C:\Program Files (x86)\Sennheiser\SenncomSDK\PocoNetSSL.dll`
* Description: This file is part of the POCO C++ Libraries.

## Hashes

Type | Hash
-- | --
MD5 | `95E3D4564F042B8D2DCDCF59751CE9C3`
SHA1 | `00918D9E92B7EF78F6104B0EB0478AC3534EA351`
SHA256 | `53C574A6B32E3AC907A96AA7EBA26D54A58B133F707F3A53A8BE0C8962574305`
SHA384 | `D8E67C7D7C4D6DF6F667D17F23476171DC37B251CF7422A4AB6A7E88E7147062D6CE545E831A540478AC6D3ED42FAEA8`
SHA512 | `81015C25BE4FB009863C9C6A9E73CB76BDD2E8D7851499DC2F69840339EDBC2405F3B61F60A593CD2053610C3793DE5798B8CFDD9BF90E5CE776165E6EEC471D`
SSDEEP | `3072:o2lYb50COlvz8rwG0Q7Pjp2z75IxdA7w8T0I8q7c8hBmC+UPq:o2A0tTGk9EdA7wnHq7c2l+P`
IMP | `FCC3EE623D5590F54BC9634CD7E85853`
PESHA1 | `8CED04DA593E470814EA74A70CA09AF9D4BE3C2F`
PE256 | `AA2BC4C236E38AC0E7B97A750DEE2666343D0FC5DA678439DF4AA49F19A6C583`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`public: static class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const Poco::Net::SSLManager::CFG_SERVER_PREFIX` | 221 | Exported Function
`public: static enum Poco::Net::Context::VerificationMode __cdecl Poco::Net::Utility::convertVerificationMode(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 298 | Exported Function
`public: static void __cdecl Poco::Net::HTTPSSessionInstantiator::registerInstantiator(class Poco::AutoPtr<class Poco::Net::Context>)` | 382 | Exported Function
`public: static class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const Poco::Net::SSLManager::CFG_CLIENT_PREFIX` | 207 | Exported Function
`public: static class Poco::Net::SSLManager & __cdecl Poco::Net::SSLManager::instance(void)` | 346 | Exported Function
`public: static class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __cdecl Poco::Net::Utility::convertCertificateError(long)` | 297 | Exported Function
`public: static class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __cdecl Poco::Net::Utility::getLastError(void)` | 323 | Exported Function
`public: static void __cdecl Poco::Net::Utility::clearErrorStack(void)` | 265 | Exported Function
`public: struct Poco::Net::Context::Params & __thiscall Poco::Net::Context::Params::operator=(struct Poco::Net::Context::Params const &)` | 152 | Exported Function
`public: struct ssl_ctx_st * __thiscall Poco::Net::Context::sslContext(void)const ` | 426 | Exported Function
`public: static void __cdecl Poco::Net::HTTPSStreamFactory::unregisterFactory(void)` | 432 | Exported Function
`public: static void __cdecl Poco::Net::HTTPSSessionInstantiator::registerInstantiator(void)` | 383 | Exported Function
`public: static void __cdecl Poco::Net::HTTPSSessionInstantiator::unregisterInstantiator(void)` | 433 | Exported Function
`public: static void __cdecl Poco::Net::HTTPSStreamFactory::registerFactory(void)` | 381 | Exported Function
`public: int __thiscall Poco::Net::VerificationErrorArgs::errorNumber(void)const ` | 317 | Exported Function
`public: long __thiscall Poco::Net::Context::getSessionTimeout(void)const ` | 330 | Exported Function
`public: static bool __cdecl Poco::Net::SSLManager::isFIPSEnabled(void)` | 347 | Exported Function
`public: int __thiscall Poco::Net::VerificationErrorArgs::errorDepth(void)const ` | 315 | Exported Function
`public: int __thiscall Poco::Net::SecureSocketImpl::sendBytes(void const *,int,int)` | 396 | Exported Function
`public: int __thiscall Poco::Net::SecureStreamSocket::completeHandshake(void)` | 277 | Exported Function
`public: int __thiscall Poco::Net::SecureStreamSocketImpl::completeHandshake(void)` | 278 | Exported Function
`public: static class Poco::Net::SecureStreamSocket __cdecl Poco::Net::SecureStreamSocket::attach(class Poco::Net::StreamSocket const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 248 | Exported Function
`public: static class Poco::Net::SecureStreamSocket __cdecl Poco::Net::SecureStreamSocket::attach(class Poco::Net::StreamSocket const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class Poco::AutoPtr<class Poco::Net::Context>)` | 249 | Exported Function
`public: static class Poco::Net::SecureStreamSocket __cdecl Poco::Net::SecureStreamSocket::attach(class Poco::Net::StreamSocket const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class Poco::AutoPtr<class Poco::Net::Context>,class Poco::AutoPtr<class Poco::Net::Session>)` | 250 | Exported Function
`public: static class Poco::Net::SecureStreamSocket __cdecl Poco::Net::SecureStreamSocket::attach(class Poco::Net::StreamSocket const &,class Poco::AutoPtr<class Poco::Net::Context>,class Poco::AutoPtr<class Poco::Net::Session>)` | 252 | Exported Function
`public: static bool __cdecl Poco::Net::X509Certificate::verify(class Poco::Crypto::X509Certificate const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 442 | Exported Function
`public: static class Poco::Net::SecureStreamSocket __cdecl Poco::Net::SecureStreamSocket::attach(class Poco::Net::StreamSocket const &)` | 247 | Exported Function
`public: static class Poco::Net::SecureStreamSocket __cdecl Poco::Net::SecureStreamSocket::attach(class Poco::Net::StreamSocket const &,class Poco::AutoPtr<class Poco::Net::Context>)` | 251 | Exported Function
`public: virtual __thiscall Poco::Net::PrivateKeyFactoryRegistrar::~PrivateKeyFactoryRegistrar(void)` | 125 | Exported Function
`public: virtual __thiscall Poco::Net::PrivateKeyPassphraseHandler::~PrivateKeyPassphraseHandler(void)` | 126 | Exported Function
`public: virtual __thiscall Poco::Net::RejectCertificateHandler::~RejectCertificateHandler(void)` | 127 | Exported Function
`public: virtual __thiscall Poco::Net::PrivateKeyFactory::~PrivateKeyFactory(void)` | 123 | Exported Function
`public: virtual __thiscall Poco::Net::InvalidCertificateHandler::~InvalidCertificateHandler(void)` | 119 | Exported Function
`public: virtual __thiscall Poco::Net::KeyConsoleHandler::~KeyConsoleHandler(void)` | 120 | Exported Function
`public: virtual __thiscall Poco::Net::KeyFileHandler::~KeyFileHandler(void)` | 121 | Exported Function
`public: virtual __thiscall Poco::Net::SSLConnectionUnexpectedlyClosedException::~SSLConnectionUnexpectedlyClosedException(void)` | 128 | Exported Function
`public: virtual __thiscall Poco::Net::SSLContextException::~SSLContextException(void)` | 129 | Exported Function
`public: virtual __thiscall Poco::Net::SSLException::~SSLException(void)` | 130 | Exported Function
`public: virtual __thiscall Poco::Net::SecureStreamSocket::~SecureStreamSocket(void)` | 136 | Exported Function
`public: virtual __thiscall Poco::Net::SecureServerSocket::~SecureServerSocket(void)` | 133 | Exported Function
`public: virtual __thiscall Poco::Net::SecureSMTPClientSession::~SecureSMTPClientSession(void)` | 132 | Exported Function
`public: virtual __thiscall Poco::Net::SecureSocketImpl::~SecureSocketImpl(void)` | 135 | Exported Function
`public: virtual __thiscall Poco::Net::AcceptCertificateHandler::~AcceptCertificateHandler(void)` | 108 | Exported Function
`public: virtual __thiscall Poco::Net::CertificateHandlerFactory::~CertificateHandlerFactory(void)` | 109 | Exported Function
`public: virtual __thiscall Poco::Net::CertificateHandlerFactoryRegistrar::~CertificateHandlerFactoryRegistrar(void)` | 111 | Exported Function
`public: unsigned int __thiscall Poco::Net::SecureSocketImpl::sockfd(void)` | 425 | Exported Function
`public: struct ssl_session_st * __thiscall Poco::Net::Session::sslSession(void)const ` | 428 | Exported Function
`public: struct x509_st * __thiscall Poco::Net::SecureSocketImpl::peerCertificate(void)const ` | 367 | Exported Function
`public: unsigned int __thiscall Poco::Net::Context::getSessionCacheSize(void)const ` | 329 | Exported Function
`public: virtual __thiscall Poco::Net::HTTPSSessionInstantiator::~HTTPSSessionInstantiator(void)` | 116 | Exported Function
`public: virtual __thiscall Poco::Net::HTTPSStreamFactory::~HTTPSStreamFactory(void)` | 117 | Exported Function
`public: virtual __thiscall Poco::Net::InvalidCertificateException::~InvalidCertificateException(void)` | 118 | Exported Function
`public: virtual __thiscall Poco::Net::HTTPSClientSession::~HTTPSClientSession(void)` | 115 | Exported Function
`public: virtual __thiscall Poco::Net::CertificateValidationException::~CertificateValidationException(void)` | 112 | Exported Function
`public: virtual __thiscall Poco::Net::ConsoleCertificateHandler::~ConsoleCertificateHandler(void)` | 113 | Exported Function
`public: virtual __thiscall Poco::Net::Context::~Context(void)` | 114 | Exported Function
`public: int __thiscall Poco::Net::SecureSocketImpl::receiveBytes(void *,int,int)` | 377 | Exported Function
`public: class Poco::Net::KeyConsoleHandler & __thiscall Poco::Net::KeyConsoleHandler::operator=(class Poco::Net::KeyConsoleHandler const &)` | 150 | Exported Function
`public: class Poco::Net::KeyFileHandler & __thiscall Poco::Net::KeyFileHandler::operator=(class Poco::Net::KeyFileHandler const &)` | 151 | Exported Function
`public: class Poco::Net::PrivateKeyFactory & __thiscall Poco::Net::PrivateKeyFactory::operator=(class Poco::Net::PrivateKeyFactory const &)` | 153 | Exported Function
`public: class Poco::Net::InvalidCertificateHandler & __thiscall Poco::Net::InvalidCertificateHandler::operator=(class Poco::Net::InvalidCertificateHandler const &)` | 149 | Exported Function
`public: class Poco::Net::ConsoleCertificateHandler & __thiscall Poco::Net::ConsoleCertificateHandler::operator=(class Poco::Net::ConsoleCertificateHandler const &)` | 146 | Exported Function
`public: class Poco::Net::HTTPSSessionInstantiator & __thiscall Poco::Net::HTTPSSessionInstantiator::operator=(class Poco::Net::HTTPSSessionInstantiator const &)` | 147 | Exported Function
`public: class Poco::Net::InvalidCertificateException & __thiscall Poco::Net::InvalidCertificateException::operator=(class Poco::Net::InvalidCertificateException const &)` | 148 | Exported Function
`public: class Poco::Net::PrivateKeyPassphraseHandler & __thiscall Poco::Net::PrivateKeyPassphraseHandler::operator=(class Poco::Net::PrivateKeyPassphraseHandler const &)` | 156 | Exported Function
`public: class Poco::Net::RejectCertificateHandler & __thiscall Poco::Net::RejectCertificateHandler::operator=(class Poco::Net::RejectCertificateHandler const &)` | 157 | Exported Function
`public: class Poco::Net::SecureServerSocket & __thiscall Poco::Net::SecureServerSocket::operator=(class Poco::Net::SecureServerSocket const &)` | 162 | Exported Function
`public: class Poco::Net::PrivateKeyFactoryRegistrar & __thiscall Poco::Net::PrivateKeyFactoryRegistrar::operator=(class Poco::Net::PrivateKeyFactoryRegistrar const &)` | 155 | Exported Function
`public: class Poco::Net::PrivateKeyFactory const * __thiscall Poco::Net::PrivateKeyFactoryMgr::getFactory(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)const ` | 321 | Exported Function
`public: class Poco::Net::PrivateKeyFactoryMgr & __thiscall Poco::Net::PrivateKeyFactoryMgr::operator=(class Poco::Net::PrivateKeyFactoryMgr const &)` | 154 | Exported Function
`public: class Poco::Net::PrivateKeyFactoryMgr & __thiscall Poco::Net::SSLManager::privateKeyFactoryMgr(void)` | 371 | Exported Function
`public: class Poco::AutoPtr<class Poco::Net::Session> __thiscall Poco::Net::SecureSocketImpl::currentSession(void)` | 301 | Exported Function
`public: class Poco::AutoPtr<class Poco::Net::Session> __thiscall Poco::Net::SecureStreamSocket::currentSession(void)` | 302 | Exported Function
`public: class Poco::AutoPtr<class Poco::Net::Session> __thiscall Poco::Net::SecureStreamSocketImpl::currentSession(void)` | 303 | Exported Function
`public: class Poco::AutoPtr<class Poco::Net::Session> __thiscall Poco::Net::HTTPSClientSession::sslSession(void)` | 427 | Exported Function
`public: class Poco::AutoPtr<class Poco::Net::Context> __thiscall Poco::Net::SecureStreamSocketImpl::context(void)const ` | 296 | Exported Function
`public: class Poco::AutoPtr<class Poco::Net::Context> __thiscall Poco::Net::SSLManager::defaultClientContext(void)` | 304 | Exported Function
`public: class Poco::AutoPtr<class Poco::Net::Context> __thiscall Poco::Net::SSLManager::defaultServerContext(void)` | 305 | Exported Function
`public: class Poco::Net::CertificateHandlerFactoryMgr & __thiscall Poco::Net::SSLManager::certificateHandlerFactoryMgr(void)` | 259 | Exported Function
`public: class Poco::Net::CertificateHandlerFactoryRegistrar & __thiscall Poco::Net::CertificateHandlerFactoryRegistrar::operator=(class Poco::Net::CertificateHandlerFactoryRegistrar const &)` | 144 | Exported Function
`public: class Poco::Net::CertificateValidationException & __thiscall Poco::Net::CertificateValidationException::operator=(class Poco::Net::CertificateValidationException const &)` | 145 | Exported Function
`public: class Poco::Net::CertificateHandlerFactoryMgr & __thiscall Poco::Net::CertificateHandlerFactoryMgr::operator=(class Poco::Net::CertificateHandlerFactoryMgr const &)` | 143 | Exported Function
`public: class Poco::Net::AcceptCertificateHandler & __thiscall Poco::Net::AcceptCertificateHandler::operator=(class Poco::Net::AcceptCertificateHandler const &)` | 141 | Exported Function
`public: class Poco::Net::CertificateHandlerFactory & __thiscall Poco::Net::CertificateHandlerFactory::operator=(class Poco::Net::CertificateHandlerFactory const &)` | 142 | Exported Function
`public: class Poco::Net::CertificateHandlerFactory const * __thiscall Poco::Net::CertificateHandlerFactoryMgr::getFactory(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)const ` | 320 | Exported Function
`public: class Poco::SharedPtr<class Poco::Net::PrivateKeyPassphraseHandler,class Poco::ReferenceCounter,class Poco::ReleasePolicy<class Poco::Net::PrivateKeyPassphraseHandler> > __thiscall Poco::Net::SSLManager::clientPassphraseHandler(void)` | 267 | Exported Function
`public: class Poco::SharedPtr<class Poco::Net::PrivateKeyPassphraseHandler,class Poco::ReferenceCounter,class Poco::ReleasePolicy<class Poco::Net::PrivateKeyPassphraseHandler> > __thiscall Poco::Net::SSLManager::serverPassphraseHandler(void)` | 404 | Exported Function
`public: class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const & __thiscall Poco::Net::SecureSocketImpl::getPeerHostName(void)const ` | 326 | Exported Function
`public: class Poco::SharedPtr<class Poco::Net::InvalidCertificateHandler,class Poco::ReferenceCounter,class Poco::ReleasePolicy<class Poco::Net::InvalidCertificateHandler> > __thiscall Poco::Net::SSLManager::serverCertificateHandler(void)` | 403 | Exported Function
`public: class Poco::Net::X509Certificate __thiscall Poco::Net::SecureStreamSocketImpl::peerCertificate(void)const ` | 369 | Exported Function
`public: class Poco::Net::X509Certificate const & __thiscall Poco::Net::VerificationErrorArgs::certificate(void)const ` | 258 | Exported Function
`public: class Poco::SharedPtr<class Poco::Net::InvalidCertificateHandler,class Poco::ReferenceCounter,class Poco::ReleasePolicy<class Poco::Net::InvalidCertificateHandler> > __thiscall Poco::Net::SSLManager::clientCertificateHandler(void)` | 266 | Exported Function
`public: enum Poco::Net::Context::VerificationMode __thiscall Poco::Net::Context::verificationMode(void)const ` | 440 | Exported Function
`public: int __thiscall Poco::Net::SecureSocketImpl::available(void)const ` | 253 | Exported Function
`public: int __thiscall Poco::Net::SecureSocketImpl::completeHandshake(void)` | 276 | Exported Function
`public: enum Poco::Net::Context::Usage __thiscall Poco::Net::Context::usage(void)const ` | 434 | Exported Function
`public: class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const & __thiscall Poco::Net::SecureStreamSocket::getPeerHostName(void)const ` | 327 | Exported Function
`public: class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const & __thiscall Poco::Net::SecureStreamSocketImpl::getPeerHostName(void)const ` | 328 | Exported Function
`public: class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const & __thiscall Poco::Net::VerificationErrorArgs::errorMessage(void)const ` | 316 | Exported Function
`public: class Poco::Net::SocketImpl * __thiscall Poco::Net::SecureSocketImpl::acceptConnection(class Poco::Net::SocketAddress &)` | 240 | Exported Function
`public: class Poco::Net::SSLConnectionUnexpectedlyClosedException & __thiscall Poco::Net::SSLConnectionUnexpectedlyClosedException::operator=(class Poco::Net::SSLConnectionUnexpectedlyClosedException const &)` | 158 | Exported Function
`public: class Poco::Net::SSLContextException & __thiscall Poco::Net::SSLContextException::operator=(class Poco::Net::SSLContextException const &)` | 159 | Exported Function
`public: class Poco::Net::SecureStreamSocket & __thiscall Poco::Net::SecureStreamSocket::operator=(class Poco::Net::Socket const &)` | 165 | Exported Function
`public: class Poco::Net::SecureServerSocket & __thiscall Poco::Net::SecureServerSocket::operator=(class Poco::Net::Socket const &)` | 163 | Exported Function
`public: class Poco::Net::SecureSMTPClientSession & __thiscall Poco::Net::SecureSMTPClientSession::operator=(class Poco::Net::SecureSMTPClientSession const &)` | 161 | Exported Function
`public: class Poco::Net::SecureStreamSocket & __thiscall Poco::Net::SecureStreamSocket::operator=(class Poco::Net::SecureStreamSocket const &)` | 164 | Exported Function
`public: class Poco::Net::X509Certificate & __thiscall Poco::Net::X509Certificate::operator=(class Poco::Net::X509Certificate const &)` | 168 | Exported Function
`public: class Poco::Net::X509Certificate __thiscall Poco::Net::HTTPSClientSession::serverCertificate(void)` | 402 | Exported Function
`public: class Poco::Net::X509Certificate __thiscall Poco::Net::SecureStreamSocket::peerCertificate(void)const ` | 368 | Exported Function
`public: class Poco::Net::X509Certificate & __thiscall Poco::Net::X509Certificate::operator=(class Poco::Crypto::X509Certificate const &)` | 169 | Exported Function
`public: class Poco::Net::SSLException & __thiscall Poco::Net::SSLException::operator=(class Poco::Net::SSLException const &)` | 160 | Exported Function
`public: class Poco::Net::Utility & __thiscall Poco::Net::Utility::operator=(class Poco::Net::Utility const &)` | 166 | Exported Function
`public: class Poco::Net::VerificationErrorArgs & __thiscall Poco::Net::VerificationErrorArgs::operator=(class Poco::Net::VerificationErrorArgs const &)` | 167 | Exported Function
`public: void __thiscall Poco::Net::Context::useCertificate(class Poco::Crypto::X509Certificate const &)` | 435 | Exported Function
`public: void __thiscall Poco::Net::Context::usePrivateKey(class Poco::Crypto::RSAKey const &)` | 436 | Exported Function
`public: void __thiscall Poco::Net::InvalidCertificateException::``default constructor closure'(void)` | 198 | Exported Function
`public: void __thiscall Poco::Net::Context::setSessionTimeout(long)` | 419 | Exported Function
`public: void __thiscall Poco::Net::Context::flushSessionCache(void)` | 319 | Exported Function
`public: void __thiscall Poco::Net::Context::preferServerCiphers(void)` | 370 | Exported Function
`public: void __thiscall Poco::Net::Context::setSessionCacheSize(unsigned int)` | 418 | Exported Function
`public: void __thiscall Poco::Net::SecureSocketImpl::close(void)` | 274 | Exported Function
`public: void __thiscall Poco::Net::SecureSocketImpl::connect(class Poco::Net::SocketAddress const &,bool)` | 283 | Exported Function
`public: void __thiscall Poco::Net::SecureSocketImpl::connect(class Poco::Net::SocketAddress const &,class Poco::Timespan const &,bool)` | 282 | Exported Function
`public: void __thiscall Poco::Net::SecureSocketImpl::bind(class Poco::Net::SocketAddress const &,bool)` | 256 | Exported Function
`public: void __thiscall Poco::Net::PrivateKeyFactoryMgr::removeFactory(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 385 | Exported Function
`public: void __thiscall Poco::Net::PrivateKeyFactoryMgr::setFactory(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class Poco::Net::PrivateKeyFactory *)` | 411 | Exported Function
`public: void __thiscall Poco::Net::SecureSocketImpl::abort(void)` | 234 | Exported Function
`public: void __thiscall Poco::Net::CertificateHandlerFactoryMgr::removeFactory(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 384 | Exported Function
`public: void __thiscall Poco::Net::CertificateHandlerFactoryMgr::setFactory(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class Poco::Net::CertificateHandlerFactory *)` | 410 | Exported Function
`public: void __thiscall Poco::Net::CertificateValidationException::``default constructor closure'(void)` | 197 | Exported Function
`public: virtual void __thiscall Poco::Net::SSLException::rethrow(void)const ` | 391 | Exported Function
`public: virtual void __thiscall Poco::Net::SecureStreamSocketImpl::shutdownSend(void)` | 424 | Exported Function
`public: virtual void __thiscall Poco::Net::SSLConnectionUnexpectedlyClosedException::rethrow(void)const ` | 389 | Exported Function
`public: virtual void __thiscall Poco::Net::SSLContextException::rethrow(void)const ` | 390 | Exported Function
`public: void __thiscall Poco::Net::Context::enableExtendedCertificateVerification(bool)` | 308 | Exported Function
`public: void __thiscall Poco::Net::Context::enableSessionCache(bool)` | 309 | Exported Function
`public: void __thiscall Poco::Net::Context::enableSessionCache(bool,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 310 | Exported Function
`public: void __thiscall Poco::Net::Context::disableStatelessSessionResumption(void)` | 307 | Exported Function
`public: void __thiscall Poco::Net::Context::addCertificateAuthority(class Poco::Crypto::X509Certificate const &)` | 244 | Exported Function
`public: void __thiscall Poco::Net::Context::addChainCertificate(class Poco::Crypto::X509Certificate const &)` | 245 | Exported Function
`public: void __thiscall Poco::Net::Context::disableProtocols(int)` | 306 | Exported Function
`public: void __thiscall Poco::Net::SecureStreamSocketImpl::verifyPeerCertificate(void)` | 450 | Exported Function
`public: void __thiscall Poco::Net::SSLConnectionUnexpectedlyClosedException::``default constructor closure'(void)` | 199 | Exported Function
`public: void __thiscall Poco::Net::SSLContextException::``default constructor closure'(void)` | 200 | Exported Function
`public: void __thiscall Poco::Net::SecureStreamSocketImpl::verifyPeerCertificate(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 449 | Exported Function
`public: void __thiscall Poco::Net::SecureStreamSocketImpl::setLazyHandshake(bool)` | 414 | Exported Function
`public: void __thiscall Poco::Net::SecureStreamSocketImpl::setPeerHostName(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 417 | Exported Function
`public: void __thiscall Poco::Net::SecureStreamSocketImpl::useSession(class Poco::AutoPtr<class Poco::Net::Session>)` | 439 | Exported Function
`public: void __thiscall Poco::Net::VerificationErrorArgs::setIgnoreError(bool)` | 412 | Exported Function
`void __cdecl Poco::Net::initializeSSL(void)` | 344 | Exported Function
`void __cdecl Poco::Net::uninitializeSSL(void)` | 431 | Exported Function
`public: void __thiscall Poco::Net::SSLManager::shutdown(void)` | 420 | Exported Function
`public: void __thiscall Poco::Net::SSLException::``default constructor closure'(void)` | 201 | Exported Function
`public: void __thiscall Poco::Net::SSLManager::initializeClient(class Poco::SharedPtr<class Poco::Net::PrivateKeyPassphraseHandler,class Poco::ReferenceCounter,class Poco::ReleasePolicy<class Poco::Net::PrivateKeyPassphraseHandler> >,class Poco::SharedPtr<class Poco::Net::InvalidCertificateHandler,class Poco::ReferenceCounter,class Poco::ReleasePolicy<class Poco::Net::InvalidCertificateHandler> >,class Poco::AutoPtr<class Poco::Net::Context>)` | 343 | Exported Function
`public: void __thiscall Poco::Net::SSLManager::initializeServer(class Poco::SharedPtr<class Poco::Net::PrivateKeyPassphraseHandler,class Poco::ReferenceCounter,class Poco::ReleasePolicy<class Poco::Net::PrivateKeyPassphraseHandler> >,class Poco::SharedPtr<class Poco::Net::InvalidCertificateHandler,class Poco::ReferenceCounter,class Poco::ReleasePolicy<class Poco::Net::InvalidCertificateHandler> >,class Poco::AutoPtr<class Poco::Net::Context>)` | 345 | Exported Function
`public: void __thiscall Poco::Net::SecureSocketImpl::useSession(class Poco::AutoPtr<class Poco::Net::Session>)` | 437 | Exported Function
`public: void __thiscall Poco::Net::SecureSocketImpl::verifyPeerCertificate(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 445 | Exported Function
`public: void __thiscall Poco::Net::SecureSocketImpl::verifyPeerCertificate(void)` | 446 | Exported Function
`public: void __thiscall Poco::Net::SecureSocketImpl::shutdown(void)` | 421 | Exported Function
`public: void __thiscall Poco::Net::SecureSocketImpl::connectNB(class Poco::Net::SocketAddress const &)` | 287 | Exported Function
`public: void __thiscall Poco::Net::SecureSocketImpl::listen(int)` | 352 | Exported Function
`public: void __thiscall Poco::Net::SecureSocketImpl::setPeerHostName(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 415 | Exported Function
`public: void __thiscall Poco::Net::SecureStreamSocket::verifyPeerCertificate(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 447 | Exported Function
`public: void __thiscall Poco::Net::SecureStreamSocket::verifyPeerCertificate(void)` | 448 | Exported Function
`public: void __thiscall Poco::Net::SecureStreamSocketImpl::abort(void)` | 236 | Exported Function
`public: void __thiscall Poco::Net::SecureStreamSocket::useSession(class Poco::AutoPtr<class Poco::Net::Session>)` | 438 | Exported Function
`public: void __thiscall Poco::Net::SecureStreamSocket::abort(void)` | 235 | Exported Function
`public: void __thiscall Poco::Net::SecureStreamSocket::setLazyHandshake(bool)` | 413 | Exported Function
`public: void __thiscall Poco::Net::SecureStreamSocket::setPeerHostName(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 416 | Exported Function
`public: virtual void __thiscall Poco::Net::SecureStreamSocketImpl::shutdownReceive(void)` | 423 | Exported Function
`public: virtual class Poco::Net::HTTPClientSession * __thiscall Poco::Net::HTTPSSessionInstantiator::createClientSession(class Poco::URI const &)` | 299 | Exported Function
`public: virtual class Poco::Net::SocketImpl * __thiscall Poco::Net::SecureServerSocketImpl::acceptConnection(class Poco::Net::SocketAddress &)` | 239 | Exported Function
`public: virtual class Poco::Net::SocketImpl * __thiscall Poco::Net::SecureStreamSocketImpl::acceptConnection(class Poco::Net::SocketAddress &)` | 241 | Exported Function
`public: virtual class Poco::Exception * __thiscall Poco::Net::SSLException::clone(void)const ` | 272 | Exported Function
`public: virtual class Poco::Exception * __thiscall Poco::Net::InvalidCertificateException::clone(void)const ` | 269 | Exported Function
`public: virtual class Poco::Exception * __thiscall Poco::Net::SSLConnectionUnexpectedlyClosedException::clone(void)const ` | 270 | Exported Function
`public: virtual class Poco::Exception * __thiscall Poco::Net::SSLContextException::clone(void)const ` | 271 | Exported Function
`public: virtual int __thiscall Poco::Net::SecureServerSocketImpl::receiveFrom(void *,int,class Poco::Net::SocketAddress &,int)` | 379 | Exported Function
`public: virtual int __thiscall Poco::Net::SecureServerSocketImpl::sendBytes(void const *,int,int)` | 395 | Exported Function
`public: virtual int __thiscall Poco::Net::SecureServerSocketImpl::sendTo(void const *,int,class Poco::Net::SocketAddress const &,int)` | 398 | Exported Function
`public: virtual int __thiscall Poco::Net::SecureServerSocketImpl::receiveBytes(void *,int,int)` | 376 | Exported Function
`public: virtual class Poco::Net::StreamSocket __thiscall Poco::Net::SecureServerSocket::acceptConnection(class Poco::Net::SocketAddress &)` | 237 | Exported Function
`public: virtual class Poco::Net::StreamSocket __thiscall Poco::Net::SecureServerSocket::acceptConnection(void)` | 238 | Exported Function
`public: virtual class std::basic_istream<char,struct std::char_traits<char> > * __thiscall Poco::Net::HTTPSStreamFactory::open(class Poco::URI const &)` | 366 | Exported Function
`public: virtual char const * __thiscall Poco::Net::CertificateValidationException::name(void)const ` | 356 | Exported Function
`public: virtual char const * __thiscall Poco::Net::InvalidCertificateException::className(void)const ` | 261 | Exported Function
`public: virtual char const * __thiscall Poco::Net::InvalidCertificateException::name(void)const ` | 357 | Exported Function
`public: virtual char const * __thiscall Poco::Net::CertificateValidationException::className(void)const ` | 260 | Exported Function
`public: virtual bool __thiscall Poco::Net::HTTPSClientSession::secure(void)const ` | 392 | Exported Function
`public: virtual bool __thiscall Poco::Net::SecureServerSocketImpl::secure(void)const ` | 393 | Exported Function
`public: virtual bool __thiscall Poco::Net::SecureStreamSocketImpl::secure(void)const ` | 394 | Exported Function
`public: virtual char const * __thiscall Poco::Net::SSLException::className(void)const ` | 264 | Exported Function
`public: virtual char const * __thiscall Poco::Net::SSLException::name(void)const ` | 360 | Exported Function
`public: virtual class Poco::Exception * __thiscall Poco::Net::CertificateValidationException::clone(void)const ` | 268 | Exported Function
`public: virtual char const * __thiscall Poco::Net::SSLContextException::name(void)const ` | 359 | Exported Function
`public: virtual char const * __thiscall Poco::Net::SSLConnectionUnexpectedlyClosedException::className(void)const ` | 262 | Exported Function
`public: virtual char const * __thiscall Poco::Net::SSLConnectionUnexpectedlyClosedException::name(void)const ` | 358 | Exported Function
`public: virtual char const * __thiscall Poco::Net::SSLContextException::className(void)const ` | 263 | Exported Function
`public: virtual void __thiscall Poco::Net::SecureServerSocketImpl::listen(int)` | 351 | Exported Function
`public: virtual void __thiscall Poco::Net::SecureServerSocketImpl::sendUrgent(unsigned char)` | 400 | Exported Function
`public: virtual void __thiscall Poco::Net::SecureStreamSocketImpl::bind(class Poco::Net::SocketAddress const &,bool)` | 257 | Exported Function
`public: virtual void __thiscall Poco::Net::SecureServerSocketImpl::connectNB(class Poco::Net::SocketAddress const &)` | 286 | Exported Function
`public: virtual void __thiscall Poco::Net::SecureServerSocketImpl::close(void)` | 273 | Exported Function
`public: virtual void __thiscall Poco::Net::SecureServerSocketImpl::connect(class Poco::Net::SocketAddress const &)` | 280 | Exported Function
`public: virtual void __thiscall Poco::Net::SecureServerSocketImpl::connect(class Poco::Net::SocketAddress const &,class Poco::Timespan const &)` | 281 | Exported Function
`public: virtual void __thiscall Poco::Net::SecureStreamSocketImpl::listen(int)` | 353 | Exported Function
`public: virtual void __thiscall Poco::Net::SecureStreamSocketImpl::sendUrgent(unsigned char)` | 401 | Exported Function
`public: virtual void __thiscall Poco::Net::SecureStreamSocketImpl::shutdown(void)` | 422 | Exported Function
`public: virtual void __thiscall Poco::Net::SecureStreamSocketImpl::connectNB(class Poco::Net::SocketAddress const &)` | 288 | Exported Function
`public: virtual void __thiscall Poco::Net::SecureStreamSocketImpl::close(void)` | 275 | Exported Function
`public: virtual void __thiscall Poco::Net::SecureStreamSocketImpl::connect(class Poco::Net::SocketAddress const &)` | 284 | Exported Function
`public: virtual void __thiscall Poco::Net::SecureStreamSocketImpl::connect(class Poco::Net::SocketAddress const &,class Poco::Timespan const &)` | 285 | Exported Function
`public: virtual int __thiscall Poco::Net::SecureStreamSocketImpl::sendTo(void const *,int,class Poco::Net::SocketAddress const &,int)` | 399 | Exported Function
`public: virtual void __thiscall Poco::Net::AcceptCertificateHandler::onInvalidCertificate(void const *,class Poco::Net::VerificationErrorArgs &)` | 361 | Exported Function
`public: virtual void __thiscall Poco::Net::CertificateValidationException::rethrow(void)const ` | 387 | Exported Function
`public: virtual int __thiscall Poco::Net::SecureStreamSocketImpl::sendBytes(void const *,int,int)` | 397 | Exported Function
`public: virtual int __thiscall Poco::Net::SecureStreamSocketImpl::available(void)` | 254 | Exported Function
`public: virtual int __thiscall Poco::Net::SecureStreamSocketImpl::receiveBytes(void *,int,int)` | 378 | Exported Function
`public: virtual int __thiscall Poco::Net::SecureStreamSocketImpl::receiveFrom(void *,int,class Poco::Net::SocketAddress &,int)` | 380 | Exported Function
`public: virtual void __thiscall Poco::Net::KeyFileHandler::onPrivateKeyRequested(void const *,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > &)` | 365 | Exported Function
`public: virtual void __thiscall Poco::Net::RejectCertificateHandler::onInvalidCertificate(void const *,class Poco::Net::VerificationErrorArgs &)` | 363 | Exported Function
`public: virtual void __thiscall Poco::Net::SecureServerSocketImpl::bind(class Poco::Net::SocketAddress const &,bool)` | 255 | Exported Function
`public: virtual void __thiscall Poco::Net::KeyConsoleHandler::onPrivateKeyRequested(void const *,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > &)` | 364 | Exported Function
`public: virtual void __thiscall Poco::Net::ConsoleCertificateHandler::onInvalidCertificate(void const *,class Poco::Net::VerificationErrorArgs &)` | 362 | Exported Function
`public: virtual void __thiscall Poco::Net::HTTPSClientSession::abort(void)` | 233 | Exported Function
`public: virtual void __thiscall Poco::Net::InvalidCertificateException::rethrow(void)const ` | 388 | Exported Function
`protected: static class Poco::Util::AbstractConfiguration & __cdecl Poco::Net::SSLManager::appConfig(void)` | 246 | Exported Function
`protected: static int __cdecl Poco::Net::SecureStreamSocketImpl::lastError(void)` | 350 | Exported Function
`protected: static int __cdecl Poco::Net::SSLManager::privateKeyPassphraseCallback(char *,int,int,void *)` | 372 | Exported Function
`protected: static bool __cdecl Poco::Net::X509Certificate::matchWildcard(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 354 | Exported Function
`protected: long __thiscall Poco::Net::SecureSocketImpl::verifyPeerCertificateImpl(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 451 | Exported Function
`protected: static bool __cdecl Poco::Net::SecureSocketImpl::isLocalHost(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 349 | Exported Function
`protected: static bool __cdecl Poco::Net::X509Certificate::containsWildcards(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 291 | Exported Function
`protected: static void __cdecl Poco::Net::SecureStreamSocketImpl::error(int,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 313 | Exported Function
`protected: static void __cdecl Poco::Net::SecureStreamSocketImpl::error(void)` | 314 | Exported Function
`protected: virtual __thiscall Poco::Net::SecureServerSocketImpl::~SecureServerSocketImpl(void)` | 134 | Exported Function
`protected: static void __cdecl Poco::Net::SecureStreamSocketImpl::error(int)` | 312 | Exported Function
`protected: static int __cdecl Poco::Net::SSLManager::verifyClientCallback(int,struct x509_store_ctx_st *)` | 444 | Exported Function
`protected: static int __cdecl Poco::Net::SSLManager::verifyServerCallback(int,struct x509_store_ctx_st *)` | 452 | Exported Function
`protected: static void __cdecl Poco::Net::SecureStreamSocketImpl::error(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 311 | Exported Function
`private: void __thiscall Poco::Net::Context::initDH(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 338 | Exported Function
`private: void __thiscall Poco::Net::Context::initECDH(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 340 | Exported Function
`private: void __thiscall Poco::Net::SSLManager::initCertificateHandler(bool)` | 337 | Exported Function
`private: void __thiscall Poco::Net::Context::init(struct Poco::Net::Context::Params const &)` | 336 | Exported Function
`private: static int __cdecl Poco::Net::SSLManager::verifyCallback(bool,int,struct x509_store_ctx_st *)` | 443 | Exported Function
`private: static int const Poco::Net::SSLManager::VAL_VER_DEPTH` | 231 | Exported Function
`private: void __thiscall Poco::Net::Context::createSSLContext(void)` | 300 | Exported Function
`protected: __thiscall Poco::Net::Session::Session(struct ssl_session_st *)` | 99 | Exported Function
`protected: bool __thiscall Poco::Net::SecureSocketImpl::mustRetry(int)` | 355 | Exported Function
`protected: int __thiscall Poco::Net::SecureSocketImpl::handleError(int)` | 331 | Exported Function
`protected: __thiscall Poco::Net::SecureStreamSocket::SecureStreamSocket(class Poco::Net::SocketImpl *)` | 85 | Exported Function
`private: void __thiscall Poco::Net::SSLManager::initDefaultContext(bool)` | 339 | Exported Function
`private: void __thiscall Poco::Net::SSLManager::initEvents(bool)` | 341 | Exported Function
`private: void __thiscall Poco::Net::SSLManager::initPassphraseHandler(bool)` | 342 | Exported Function
`public: __thiscall Poco::Net::CertificateHandlerFactoryRegistrar::CertificateHandlerFactoryRegistrar(class Poco::Net::CertificateHandlerFactoryRegistrar const &)` | 7 | Exported Function
`public: __thiscall Poco::Net::CertificateHandlerFactoryRegistrar::CertificateHandlerFactoryRegistrar(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class Poco::Net::CertificateHandlerFactory *)` | 8 | Exported Function
`public: __thiscall Poco::Net::CertificateValidationException::CertificateValidationException(class Poco::Net::CertificateValidationException const &)` | 9 | Exported Function
`public: __thiscall Poco::Net::CertificateHandlerFactoryMgr::~CertificateHandlerFactoryMgr(void)` | 110 | Exported Function
`public: __thiscall Poco::Net::CertificateHandlerFactory::CertificateHandlerFactory(void)` | 4 | Exported Function
`public: __thiscall Poco::Net::CertificateHandlerFactoryMgr::CertificateHandlerFactoryMgr(class Poco::Net::CertificateHandlerFactoryMgr const &)` | 5 | Exported Function
`public: __thiscall Poco::Net::CertificateHandlerFactoryMgr::CertificateHandlerFactoryMgr(void)` | 6 | Exported Function
`public: __thiscall Poco::Net::ConsoleCertificateHandler::ConsoleCertificateHandler(bool)` | 15 | Exported Function
`public: __thiscall Poco::Net::ConsoleCertificateHandler::ConsoleCertificateHandler(class Poco::Net::ConsoleCertificateHandler const &)` | 14 | Exported Function
`public: __thiscall Poco::Net::Context::Context(enum Poco::Net::Context::Usage,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,enum Poco::Net::Context::VerificationMode,int,bool,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 17 | Exported Function
`public: __thiscall Poco::Net::CertificateValidationException::CertificateValidationException(int)` | 13 | Exported Function
`public: __thiscall Poco::Net::CertificateValidationException::CertificateValidationException(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class Poco::Exception const &,int)` | 11 | Exported Function
`public: __thiscall Poco::Net::CertificateValidationException::CertificateValidationException(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,int)` | 10 | Exported Function
`public: __thiscall Poco::Net::CertificateValidationException::CertificateValidationException(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,int)` | 12 | Exported Function
`protected: virtual void __thiscall Poco::Net::HTTPSClientSession::connect(class Poco::Net::SocketAddress const &)` | 279 | Exported Function
`protected: virtual void __thiscall Poco::Net::HTTPSClientSession::proxyAuthenticate(class Poco::Net::HTTPRequest &)` | 373 | Exported Function
`protected: void __thiscall Poco::Net::SecureSocketImpl::acceptSSL(void)` | 242 | Exported Function
`protected: virtual int __thiscall Poco::Net::HTTPSClientSession::read(char *,__int64)` | 375 | Exported Function
`protected: virtual __thiscall Poco::Net::SecureStreamSocketImpl::~SecureStreamSocketImpl(void)` | 137 | Exported Function
`protected: virtual __thiscall Poco::Net::Session::~Session(void)` | 138 | Exported Function
`protected: virtual class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __thiscall Poco::Net::HTTPSClientSession::proxyRequestPrefix(void)const ` | 374 | Exported Function
`public: __thiscall Poco::Net::AcceptCertificateHandler::AcceptCertificateHandler(bool)` | 2 | Exported Function
`public: __thiscall Poco::Net::AcceptCertificateHandler::AcceptCertificateHandler(class Poco::Net::AcceptCertificateHandler const &)` | 1 | Exported Function
`public: __thiscall Poco::Net::CertificateHandlerFactory::CertificateHandlerFactory(class Poco::Net::CertificateHandlerFactory const &)` | 3 | Exported Function
`protected: void __thiscall Poco::Net::SecureStreamSocketImpl::connectSSL(void)` | 290 | Exported Function
`protected: void __thiscall Poco::Net::SecureSocketImpl::connectSSL(bool)` | 289 | Exported Function
`protected: void __thiscall Poco::Net::SecureSocketImpl::reset(void)` | 386 | Exported Function
`protected: void __thiscall Poco::Net::SecureStreamSocketImpl::acceptSSL(void)` | 243 | Exported Function
`private: static enum Poco::Net::Context::VerificationMode const Poco::Net::SSLManager::VAL_VER_MODE` | 232 | Exported Function
`const Poco::Net::SecureServerSocketImpl::``vftable'` | 192 | Exported Function
`const Poco::Net::SecureSMTPClientSession::``vftable'` | 190 | Exported Function
`const Poco::Net::SecureSocketImpl::``vftable'` | 193 | Exported Function
`const Poco::Net::SecureServerSocket::``vftable'` | 191 | Exported Function
`const Poco::Net::PrivateKeyFactoryRegistrar::``vftable'` | 184 | Exported Function
`const Poco::Net::PrivateKeyPassphraseHandler::``vftable'` | 185 | Exported Function
`const Poco::Net::RejectCertificateHandler::``vftable'` | 186 | Exported Function
`const Poco::Net::SSLContextException::``vftable'` | 188 | Exported Function
`const Poco::Net::SSLException::``vftable'` | 189 | Exported Function
`private: __thiscall Poco::Net::SSLManager::SSLManager(void)` | 71 | Exported Function
`const Poco::Net::SSLConnectionUnexpectedlyClosedException::``vftable'` | 187 | Exported Function
`const Poco::Net::SecureStreamSocket::``vftable'` | 194 | Exported Function
`const Poco::Net::SecureStreamSocketImpl::``vftable'` | 195 | Exported Function
`const Poco::Net::Session::``vftable'` | 196 | Exported Function
`const Poco::Net::ConsoleCertificateHandler::``vftable'` | 174 | Exported Function
`const Poco::Net::Context::``vftable'` | 175 | Exported Function
`const Poco::Net::HTTPSClientSession::``vftable'` | 176 | Exported Function
`const Poco::Net::CertificateValidationException::``vftable'` | 173 | Exported Function
`const Poco::Net::AcceptCertificateHandler::``vftable'` | 170 | Exported Function
`const Poco::Net::CertificateHandlerFactory::``vftable'` | 171 | Exported Function
`const Poco::Net::CertificateHandlerFactoryRegistrar::``vftable'` | 172 | Exported Function
`const Poco::Net::KeyConsoleHandler::``vftable'` | 181 | Exported Function
`const Poco::Net::KeyFileHandler::``vftable'` | 182 | Exported Function
`const Poco::Net::PrivateKeyFactory::``vftable'` | 183 | Exported Function
`const Poco::Net::InvalidCertificateHandler::``vftable'` | 180 | Exported Function
`const Poco::Net::HTTPSSessionInstantiator::``vftable'` | 177 | Exported Function
`const Poco::Net::HTTPSStreamFactory::``vftable'` | 178 | Exported Function
`const Poco::Net::InvalidCertificateException::``vftable'` | 179 | Exported Function
`private: static class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const Poco::Net::SSLManager::CFG_REQUIRE_TLSV1_1` | 219 | Exported Function
`private: static class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const Poco::Net::SSLManager::CFG_REQUIRE_TLSV1_2` | 220 | Exported Function
`private: static class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const Poco::Net::SSLManager::CFG_SESSION_CACHE_SIZE` | 222 | Exported Function
`private: static class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const Poco::Net::SSLManager::CFG_REQUIRE_TLSV1` | 218 | Exported Function
`private: static class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const Poco::Net::SSLManager::CFG_EXTENDED_VERIFICATION` | 214 | Exported Function
`private: static class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const Poco::Net::SSLManager::CFG_PREFER_SERVER_CIPHERS` | 215 | Exported Function
`private: static class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const Poco::Net::SSLManager::CFG_PRIV_KEY_FILE` | 217 | Exported Function
`private: static class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const Poco::Net::SSLManager::VAL_CERTIFICATE_HANDLER` | 227 | Exported Function
`private: static class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const Poco::Net::SSLManager::VAL_CIPHER_LIST` | 228 | Exported Function
`private: static class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const Poco::Net::SSLManager::VAL_DELEGATE_HANDLER` | 229 | Exported Function
`private: static class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const Poco::Net::SSLManager::CFG_VER_MODE` | 226 | Exported Function
`private: static class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const Poco::Net::SSLManager::CFG_SESSION_ID_CONTEXT` | 223 | Exported Function
`private: static class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const Poco::Net::SSLManager::CFG_SESSION_TIMEOUT` | 224 | Exported Function
`private: static class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const Poco::Net::SSLManager::CFG_VER_DEPTH` | 225 | Exported Function
`private: static class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const Poco::Net::SSLManager::CFG_CACHE_SESSIONS` | 202 | Exported Function
`private: static class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const Poco::Net::SSLManager::CFG_CERTIFICATE_FILE` | 204 | Exported Function
`private: static class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const Poco::Net::SSLManager::CFG_CERTIFICATE_HANDLER` | 205 | Exported Function
`private: static class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const Poco::Net::SSLManager::CFG_CA_LOCATION` | 203 | Exported Function
`private: __thiscall Poco::Net::SSLManager::~SSLManager(void)` | 131 | Exported Function
`private: static bool const Poco::Net::SSLManager::VAL_ENABLE_DEFAULT_CA` | 230 | Exported Function
`private: static class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const Poco::Net::KeyFileHandler::CFG_PRIV_KEY_FILE` | 216 | Exported Function
`private: static class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const Poco::Net::SSLManager::CFG_DISABLE_PROTOCOLS` | 211 | Exported Function
`private: static class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const Poco::Net::SSLManager::CFG_ECDH_CURVE` | 212 | Exported Function
`private: static class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const Poco::Net::SSLManager::CFG_ENABLE_DEFAULT_CA` | 213 | Exported Function
`private: static class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const Poco::Net::SSLManager::CFG_DH_PARAMS_FILE` | 210 | Exported Function
`private: static class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const Poco::Net::SSLManager::CFG_CIPHER_LIST` | 206 | Exported Function
`private: static class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const Poco::Net::SSLManager::CFG_CYPHER_LIST` | 208 | Exported Function
`private: static class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const Poco::Net::SSLManager::CFG_DELEGATE_HANDLER` | 209 | Exported Function
`public: __thiscall Poco::Net::SSLContextException::SSLContextException(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,int)` | 64 | Exported Function
`public: __thiscall Poco::Net::SSLContextException::SSLContextException(int)` | 65 | Exported Function
`public: __thiscall Poco::Net::SSLException::SSLException(class Poco::Net::SSLException const &)` | 66 | Exported Function
`public: __thiscall Poco::Net::SSLContextException::SSLContextException(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,int)` | 62 | Exported Function
`public: __thiscall Poco::Net::SSLConnectionUnexpectedlyClosedException::SSLConnectionUnexpectedlyClosedException(int)` | 60 | Exported Function
`public: __thiscall Poco::Net::SSLContextException::SSLContextException(class Poco::Net::SSLContextException const &)` | 61 | Exported Function
`public: __thiscall Poco::Net::SSLContextException::SSLContextException(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class Poco::Exception const &,int)` | 63 | Exported Function
`public: __thiscall Poco::Net::VerificationErrorArgs::VerificationErrorArgs(class Poco::Net::VerificationErrorArgs const &)` | 100 | Exported Function
`public: __thiscall Poco::Net::VerificationErrorArgs::VerificationErrorArgs(class Poco::Net::X509Certificate const &,int,int,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 101 | Exported Function
`public: __thiscall Poco::Net::VerificationErrorArgs::~VerificationErrorArgs(void)` | 139 | Exported Function
`public: __thiscall Poco::Net::SSLException::SSLException(int)` | 70 | Exported Function
`public: __thiscall Poco::Net::SSLException::SSLException(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class Poco::Exception const &,int)` | 68 | Exported Function
`public: __thiscall Poco::Net::SSLException::SSLException(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,int)` | 67 | Exported Function
`public: __thiscall Poco::Net::SSLException::SSLException(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,int)` | 69 | Exported Function
`public: __thiscall Poco::Net::SecureStreamSocket::SecureStreamSocket(class Poco::Net::SocketAddress const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 89 | Exported Function
`public: __thiscall Poco::Net::SecureStreamSocket::SecureStreamSocket(class Poco::Net::SocketAddress const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class Poco::AutoPtr<class Poco::Net::Context>)` | 90 | Exported Function
`public: __thiscall Poco::Net::SecureStreamSocket::SecureStreamSocket(class Poco::Net::SocketAddress const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class Poco::AutoPtr<class Poco::Net::Context>,class Poco::AutoPtr<class Poco::Net::Session>)` | 91 | Exported Function
`public: __thiscall Poco::Net::SecureStreamSocket::SecureStreamSocket(class Poco::Net::SocketAddress const &,class Poco::AutoPtr<class Poco::Net::Context>,class Poco::AutoPtr<class Poco::Net::Session>)` | 93 | Exported Function
`public: __thiscall Poco::Net::SecureStreamSocket::SecureStreamSocket(class Poco::Net::Socket const &)` | 87 | Exported Function
`public: __thiscall Poco::Net::SecureStreamSocket::SecureStreamSocket(class Poco::Net::SocketAddress const &)` | 88 | Exported Function
`public: __thiscall Poco::Net::SecureStreamSocket::SecureStreamSocket(class Poco::Net::SocketAddress const &,class Poco::AutoPtr<class Poco::Net::Context>)` | 92 | Exported Function
`public: __thiscall Poco::Net::SSLConnectionUnexpectedlyClosedException::SSLConnectionUnexpectedlyClosedException(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class Poco::Exception const &,int)` | 58 | Exported Function
`public: __thiscall Poco::Net::SSLConnectionUnexpectedlyClosedException::SSLConnectionUnexpectedlyClosedException(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,int)` | 57 | Exported Function
`public: __thiscall Poco::Net::SSLConnectionUnexpectedlyClosedException::SSLConnectionUnexpectedlyClosedException(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,int)` | 59 | Exported Function
`public: __thiscall Poco::Net::SSLConnectionUnexpectedlyClosedException::SSLConnectionUnexpectedlyClosedException(class Poco::Net::SSLConnectionUnexpectedlyClosedException const &)` | 56 | Exported Function
`public: __thiscall Poco::Net::SecureStreamSocket::SecureStreamSocket(void)` | 96 | Exported Function
`public: __thiscall Poco::Net::SecureStreamSocketImpl::SecureStreamSocketImpl(class Poco::AutoPtr<class Poco::Net::Context>)` | 98 | Exported Function
`public: __thiscall Poco::Net::SecureStreamSocketImpl::SecureStreamSocketImpl(class Poco::Net::StreamSocketImpl *,class Poco::AutoPtr<class Poco::Net::Context>)` | 97 | Exported Function
`public: bool __thiscall Poco::Net::SecureStreamSocket::sessionWasReused(void)` | 408 | Exported Function
`public: bool __thiscall Poco::Net::SecureStreamSocketImpl::getLazyHandshake(void)const ` | 325 | Exported Function
`public: bool __thiscall Poco::Net::SecureStreamSocketImpl::havePeerCertificate(void)const ` | 335 | Exported Function
`public: bool __thiscall Poco::Net::SecureStreamSocket::havePeerCertificate(void)const ` | 334 | Exported Function
`public: bool __thiscall Poco::Net::SecureSMTPClientSession::startTLS(void)` | 430 | Exported Function
`public: bool __thiscall Poco::Net::SecureSocketImpl::sessionWasReused(void)` | 407 | Exported Function
`public: bool __thiscall Poco::Net::SecureStreamSocket::getLazyHandshake(void)const ` | 324 | Exported Function
`public: class Poco::AutoPtr<class Poco::Net::Context> __thiscall Poco::Net::SecureServerSocketImpl::context(void)const ` | 293 | Exported Function
`public: class Poco::AutoPtr<class Poco::Net::Context> __thiscall Poco::Net::SecureSocketImpl::context(void)const ` | 294 | Exported Function
`public: class Poco::AutoPtr<class Poco::Net::Context> __thiscall Poco::Net::SecureStreamSocket::context(void)const ` | 295 | Exported Function
`public: class Poco::AutoPtr<class Poco::Net::Context> __thiscall Poco::Net::SecureServerSocket::context(void)const ` | 292 | Exported Function
`public: bool __thiscall Poco::Net::SecureStreamSocketImpl::sessionWasReused(void)` | 409 | Exported Function
`public: bool __thiscall Poco::Net::VerificationErrorArgs::getIgnoreError(void)const ` | 322 | Exported Function
`public: bool __thiscall Poco::Net::X509Certificate::verify(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)const ` | 441 | Exported Function
`public: __thiscall Poco::Net::X509Certificate::X509Certificate(struct x509_st *)` | 106 | Exported Function
`public: __thiscall Poco::Net::X509Certificate::X509Certificate(struct x509_st *,bool)` | 107 | Exported Function
`public: __thiscall Poco::Net::X509Certificate::~X509Certificate(void)` | 140 | Exported Function
`public: __thiscall Poco::Net::X509Certificate::X509Certificate(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 105 | Exported Function
`public: __thiscall Poco::Net::X509Certificate::X509Certificate(class Poco::Crypto::X509Certificate const &)` | 104 | Exported Function
`public: __thiscall Poco::Net::X509Certificate::X509Certificate(class Poco::Net::X509Certificate const &)` | 103 | Exported Function
`public: __thiscall Poco::Net::X509Certificate::X509Certificate(class std::basic_istream<char,struct std::char_traits<char> > &)` | 102 | Exported Function
`public: bool __thiscall Poco::Net::PrivateKeyFactoryMgr::hasFactory(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)const ` | 333 | Exported Function
`public: bool __thiscall Poco::Net::PrivateKeyPassphraseHandler::serverSide(void)const ` | 405 | Exported Function
`public: bool __thiscall Poco::Net::SecureSMTPClientSession::startTLS(class Poco::AutoPtr<class Poco::Net::Context>)` | 429 | Exported Function
`public: bool __thiscall Poco::Net::Context::sessionCacheEnabled(void)const ` | 406 | Exported Function
`public: bool __thiscall Poco::Net::CertificateHandlerFactoryMgr::hasFactory(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)const ` | 332 | Exported Function
`public: bool __thiscall Poco::Net::Context::extendedCertificateVerificationEnabled(void)const ` | 318 | Exported Function
`public: bool __thiscall Poco::Net::Context::isForServerUse(void)const ` | 348 | Exported Function
`public: __thiscall Poco::Net::SecureStreamSocket::SecureStreamSocket(class Poco::Net::SecureStreamSocket const &)` | 86 | Exported Function
`public: __thiscall Poco::Net::HTTPSStreamFactory::HTTPSStreamFactory(void)` | 32 | Exported Function
`public: __thiscall Poco::Net::InvalidCertificateException::InvalidCertificateException(class Poco::Net::InvalidCertificateException const &)` | 33 | Exported Function
`public: __thiscall Poco::Net::InvalidCertificateException::InvalidCertificateException(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class Poco::Exception const &,int)` | 35 | Exported Function
`public: __thiscall Poco::Net::HTTPSStreamFactory::HTTPSStreamFactory(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,unsigned short,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 30 | Exported Function
`public: __thiscall Poco::Net::HTTPSSessionInstantiator::HTTPSSessionInstantiator(class Poco::Net::HTTPSSessionInstantiator const &)` | 27 | Exported Function
`public: __thiscall Poco::Net::HTTPSSessionInstantiator::HTTPSSessionInstantiator(void)` | 29 | Exported Function
`public: __thiscall Poco::Net::HTTPSStreamFactory::HTTPSStreamFactory(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,unsigned short)` | 31 | Exported Function
`public: __thiscall Poco::Net::InvalidCertificateHandler::InvalidCertificateHandler(class Poco::Net::InvalidCertificateHandler const &)` | 38 | Exported Function
`public: __thiscall Poco::Net::KeyConsoleHandler::KeyConsoleHandler(bool)` | 41 | Exported Function
`public: __thiscall Poco::Net::KeyConsoleHandler::KeyConsoleHandler(class Poco::Net::KeyConsoleHandler const &)` | 40 | Exported Function
`public: __thiscall Poco::Net::InvalidCertificateHandler::InvalidCertificateHandler(bool)` | 39 | Exported Function
`public: __thiscall Poco::Net::InvalidCertificateException::InvalidCertificateException(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,int)` | 34 | Exported Function
`public: __thiscall Poco::Net::InvalidCertificateException::InvalidCertificateException(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,int)` | 36 | Exported Function
`public: __thiscall Poco::Net::InvalidCertificateException::InvalidCertificateException(int)` | 37 | Exported Function
`public: __thiscall Poco::Net::Context::Params::~Params(void)` | 122 | Exported Function
`public: __thiscall Poco::Net::HTTPSClientSession::HTTPSClientSession(class Poco::AutoPtr<class Poco::Net::Context>)` | 24 | Exported Function
`public: __thiscall Poco::Net::HTTPSClientSession::HTTPSClientSession(class Poco::AutoPtr<class Poco::Net::Context>,class Poco::AutoPtr<class Poco::Net::Session>)` | 25 | Exported Function
`public: __thiscall Poco::Net::Context::Params::Params(void)` | 45 | Exported Function
`public: __thiscall Poco::Net::Context::Context(enum Poco::Net::Context::Usage,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,enum Poco::Net::Context::VerificationMode,int,bool,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 18 | Exported Function
`public: __thiscall Poco::Net::Context::Context(enum Poco::Net::Context::Usage,struct Poco::Net::Context::Params const &)` | 16 | Exported Function
`public: __thiscall Poco::Net::Context::Params::Params(struct Poco::Net::Context::Params const &)` | 44 | Exported Function
`public: __thiscall Poco::Net::HTTPSClientSession::HTTPSClientSession(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,unsigned short,class Poco::AutoPtr<class Poco::Net::Context>,class Poco::AutoPtr<class Poco::Net::Session>)` | 21 | Exported Function
`public: __thiscall Poco::Net::HTTPSClientSession::HTTPSClientSession(void)` | 26 | Exported Function
`public: __thiscall Poco::Net::HTTPSSessionInstantiator::HTTPSSessionInstantiator(class Poco::AutoPtr<class Poco::Net::Context>)` | 28 | Exported Function
`public: __thiscall Poco::Net::HTTPSClientSession::HTTPSClientSession(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,unsigned short,class Poco::AutoPtr<class Poco::Net::Context>)` | 20 | Exported Function
`public: __thiscall Poco::Net::HTTPSClientSession::HTTPSClientSession(class Poco::Net::SecureStreamSocket const &)` | 22 | Exported Function
`public: __thiscall Poco::Net::HTTPSClientSession::HTTPSClientSession(class Poco::Net::SecureStreamSocket const &,class Poco::AutoPtr<class Poco::Net::Session>)` | 23 | Exported Function
`public: __thiscall Poco::Net::HTTPSClientSession::HTTPSClientSession(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,unsigned short)` | 19 | Exported Function
`public: __thiscall Poco::Net::SecureServerSocket::SecureServerSocket(unsigned short,int)` | 79 | Exported Function
`public: __thiscall Poco::Net::SecureServerSocket::SecureServerSocket(unsigned short,int,class Poco::AutoPtr<class Poco::Net::Context>)` | 80 | Exported Function
`public: __thiscall Poco::Net::SecureServerSocket::SecureServerSocket(void)` | 82 | Exported Function
`public: __thiscall Poco::Net::SecureServerSocket::SecureServerSocket(class Poco::Net::SocketAddress const &,int,class Poco::AutoPtr<class Poco::Net::Context>)` | 78 | Exported Function
`public: __thiscall Poco::Net::SecureServerSocket::SecureServerSocket(class Poco::Net::SecureServerSocket const &)` | 75 | Exported Function
`public: __thiscall Poco::Net::SecureServerSocket::SecureServerSocket(class Poco::Net::Socket const &)` | 76 | Exported Function
`public: __thiscall Poco::Net::SecureServerSocket::SecureServerSocket(class Poco::Net::SocketAddress const &,int)` | 77 | Exported Function
`public: __thiscall Poco::Net::SecureSocketImpl::SecureSocketImpl(class Poco::AutoPtr<class Poco::Net::SocketImpl>,class Poco::AutoPtr<class Poco::Net::Context>)` | 84 | Exported Function
`public: __thiscall Poco::Net::SecureStreamSocket::SecureStreamSocket(class Poco::AutoPtr<class Poco::Net::Context>)` | 94 | Exported Function
`public: __thiscall Poco::Net::SecureStreamSocket::SecureStreamSocket(class Poco::AutoPtr<class Poco::Net::Context>,class Poco::AutoPtr<class Poco::Net::Session>)` | 95 | Exported Function
`public: __thiscall Poco::Net::SecureSMTPClientSession::SecureSMTPClientSession(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,unsigned short)` | 73 | Exported Function
`public: __thiscall Poco::Net::SecureServerSocketImpl::SecureServerSocketImpl(class Poco::AutoPtr<class Poco::Net::Context>)` | 83 | Exported Function
`public: __thiscall Poco::Net::SecureSMTPClientSession::SecureSMTPClientSession(class Poco::Net::SecureSMTPClientSession const &)` | 72 | Exported Function
`public: __thiscall Poco::Net::SecureSMTPClientSession::SecureSMTPClientSession(class Poco::Net::StreamSocket const &)` | 74 | Exported Function
`public: __thiscall Poco::Net::PrivateKeyFactoryMgr::PrivateKeyFactoryMgr(class Poco::Net::PrivateKeyFactoryMgr const &)` | 48 | Exported Function
`public: __thiscall Poco::Net::PrivateKeyFactoryMgr::PrivateKeyFactoryMgr(void)` | 49 | Exported Function
`public: __thiscall Poco::Net::PrivateKeyFactoryMgr::~PrivateKeyFactoryMgr(void)` | 124 | Exported Function
`public: __thiscall Poco::Net::PrivateKeyFactory::PrivateKeyFactory(void)` | 47 | Exported Function
`public: __thiscall Poco::Net::KeyFileHandler::KeyFileHandler(bool)` | 43 | Exported Function
`public: __thiscall Poco::Net::KeyFileHandler::KeyFileHandler(class Poco::Net::KeyFileHandler const &)` | 42 | Exported Function
`public: __thiscall Poco::Net::PrivateKeyFactory::PrivateKeyFactory(class Poco::Net::PrivateKeyFactory const &)` | 46 | Exported Function
`public: __thiscall Poco::Net::RejectCertificateHandler::RejectCertificateHandler(bool)` | 55 | Exported Function
`public: __thiscall Poco::Net::RejectCertificateHandler::RejectCertificateHandler(class Poco::Net::RejectCertificateHandler const &)` | 54 | Exported Function
`public: __thiscall Poco::Net::SecureServerSocket::SecureServerSocket(class Poco::AutoPtr<class Poco::Net::Context>)` | 81 | Exported Function
`public: __thiscall Poco::Net::PrivateKeyPassphraseHandler::PrivateKeyPassphraseHandler(class Poco::Net::PrivateKeyPassphraseHandler const &)` | 52 | Exported Function
`public: __thiscall Poco::Net::PrivateKeyFactoryRegistrar::PrivateKeyFactoryRegistrar(class Poco::Net::PrivateKeyFactoryRegistrar const &)` | 50 | Exported Function
`public: __thiscall Poco::Net::PrivateKeyFactoryRegistrar::PrivateKeyFactoryRegistrar(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class Poco::Net::PrivateKeyFactory *)` | 51 | Exported Function
`public: __thiscall Poco::Net::PrivateKeyPassphraseHandler::PrivateKeyPassphraseHandler(bool)` | 53 | Exported Function


## Signature

* Status: The file C:\Program Files (x86)\Sennheiser\SenncomSDK\PocoNetSSL.dll is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at https:/go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: 
* Product Name: POCO C++ Libraries - http://pocoproject.org
* Company Name: Applied Informatics Software Engineering GmbH
* File Version: 1.9.4
* Product Version: 1.9.4
* Language: Language Neutral
* Legal Copyright: Copyright (C) 2004-2019, Applied Informatics Software Engineering GmbH and Contributors.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/66
* VirusTotal Link: https://www.virustotal.com/gui/file/53c574a6b32e3ac907a96aa7eba26d54a58b133f707f3a53a8be0c8962574305/detection/




MIT License. Copyright (c) 2020 Strontic.


