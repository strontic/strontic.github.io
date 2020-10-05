---
title: csfstorage.dll | 
excerpt: What is csfstorage.dll?
---

# csfstorage.dll 

* File Path: `C:\Program Files (x86)\Cisco Systems\Cisco Jabber\csfstorage.dll`

## Hashes

Type | Hash
-- | --
MD5 | `DDDF801D88C8DE532FEB6AE75FE04E2B`
SHA1 | `A007C07EB0567EB86D42C812B87DAEF6CA8515D4`
SHA256 | `86A3061B5E5BA3AD516EE2E7B0115FBA7086629CA6E89970EF59A58821023E00`
SHA384 | `1F647113E1308A34FBE4D7A93178302E92029C5BB0151D06D61E6DA7C8F5E449B41415F1B45F3ECE27DC43B808D60C56`
SHA512 | `68A30243CF7B0E3AA3B8A007F22A76B8418F4190EC826DB26DAF1D23053EBF58A10E07D5B543C1C1C0B489560196AC7E230FC02E413690076F43222460B803B8`
SSDEEP | `6144:/kdKFuaX3kRNsELKAm8oW7I6hGk26QDuWC71xJh:/kdKFBX3kRNNGk26Tff3`
IMP | `ADB337440F54E9E4373D35844BD93EFA`
PESHA1 | `621E68B35EDA81CD2C47733170B5372C398E2DED`
PE256 | `267900FEB1E004A6F1232E92F2A76A5706E073501AA56A79C2B3C2E78A81375D`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`public: static class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __cdecl csf::storage::CertificateContext::getCertificateIssuer(struct _CERT_CONTEXT const *)` | 126 | Exported Function
`public: static char * __cdecl csf::storage::CertificatesUtils::getCertificateIssuer(struct x509_st *)` | 127 | Exported Function
`public: static bool __cdecl csf::storage::EncryptFileUtils::writeDataToFile(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class csf::SecureString const &,enum csf::storage::FileCategoryType::FileCategory)` | 192 | Exported Function
`public: static class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __cdecl csf::storage::Win32Utils::getErrorString(unsigned long)` | 139 | Exported Function
`public: static class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __cdecl csf::storage::CertificateContext::getCertificateNamePrefix(void)` | 131 | Exported Function
`public: static class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __cdecl csf::storage::CertificateContext::getCertificateName(struct _CERT_CONTEXT const *)` | 130 | Exported Function
`public: static bool __cdecl csf::storage::EncryptFileUtils::initializeEncryptKeyManagerWithExistingEncryptKeysOnly(void)` | 156 | Exported Function
`public: static bool __cdecl csf::storage::EncryptFileUtils::getEncryptKeyForSQLite(class csf::SecureString &)` | 137 | Exported Function
`public: static bool __cdecl csf::storage::EncryptFileUtils::getEncryptKey(enum csf::storage::FileCategoryType::FileCategory,class csf::SecureString &)` | 134 | Exported Function
`public: static bool __cdecl csf::storage::EncryptFileUtils::resetEncryptKeyManager(void)` | 178 | Exported Function
`public: static bool __cdecl csf::storage::EncryptFileUtils::readDataFromFile(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class csf::SecureString &,enum csf::storage::FileCategoryType::FileCategory)` | 169 | Exported Function
`public: static bool __cdecl csf::storage::EncryptFileUtils::isEncryptKeyManagerInitialized(void)` | 158 | Exported Function
`public: static void __cdecl csf::storage::Win32Utils::printErrorToLog(unsigned long)` | 167 | Exported Function
`public: static void __cdecl csf::storage::EncryptFileUtils::initializeEncryptKeyManager(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 155 | Exported Function
`public: static enum csf::storage::CertificatePrivateKeyManagementResult::Result __cdecl csf::storage::CertificatePrivateKeyPairConverter::convert(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,struct csf::storage::CertificatePrivateKeyPair const &,class csf::storage::CertificateContext &)` | 103 | Exported Function
`public: struct csf::storage::CertificatePrivateKeyManagementResult & __thiscall csf::storage::CertificatePrivateKeyManagementResult::operator=(struct csf::storage::CertificatePrivateKeyManagementResult &&)` | 54 | Exported Function
`public: struct _CRYPT_KEY_PROV_INFO __thiscall csf::storage::PrivateKeyContext::getDefaultProviderInfo(void)const ` | 133 | Exported Function
`public: struct _CERT_CONTEXT const * __thiscall csf::storage::CertificateContext::getCertContext(void)const ` | 124 | Exported Function
`public: static class std::shared_ptr<class csf::storage::EncryptKeyStorageManager> __cdecl csf::storage::EncryptKeyStorageManager::getEncryptKeyStorageManagerPtr(void)` | 138 | Exported Function
`public: static class std::shared_ptr<class csf::storage::CertificatePrivateKeyManagement> __cdecl csf::storage::CertificatePrivateKeyManagement::createCertificatePrivateKeyManagement(bool)` | 106 | Exported Function
`public: static class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __cdecl csf::storage::Win32Utils::win32ErrorCodeToString(unsigned long)` | 190 | Exported Function
`public: static enum csf::storage::CertificatePrivateKeyManagementResult::Result __cdecl csf::storage::CertificatePrivateKeyPairConverter::convert(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class csf::storage::CertificateContext const &,struct csf::storage::CertificatePrivateKeyPair &)` | 104 | Exported Function
`public: static class std::shared_ptr<class csf::storage::UserCertificateRetrieval> __cdecl csf::storage::UserCertificateRetrieval::createUserCertificateRetrievalPtr(void)` | 110 | Exported Function
`public: static class std::shared_ptr<class csf::storage::EncryptManager> __cdecl csf::storage::EncryptManager::createEncryptManager(void)` | 107 | Exported Function
`public: class csf::storage::Win32Utils & __thiscall csf::storage::Win32Utils::operator=(class csf::storage::Win32Utils &&)` | 82 | Exported Function
`public: class csf::storage::Win32UserCertificateRetrievalImpl & __thiscall csf::storage::Win32UserCertificateRetrievalImpl::operator=(class csf::storage::Win32UserCertificateRetrievalImpl const &)` | 81 | Exported Function
`public: class csf::storage::Win32UserCertificateRetrievalImpl & __thiscall csf::storage::Win32UserCertificateRetrievalImpl::operator=(class csf::storage::Win32UserCertificateRetrievalImpl &&)` | 80 | Exported Function
`public: class std::shared_ptr<class csf::storage::DataBlob> __thiscall csf::storage::EncoderDecoderUtility::decode(char const *,void *,unsigned int)` | 111 | Exported Function
`public: class std::shared_ptr<class csf::storage::DataBlob> __thiscall csf::storage::CertificateContext::getProperty(unsigned long)const ` | 144 | Exported Function
`public: class csf::storage::Win32Utils & __thiscall csf::storage::Win32Utils::operator=(class csf::storage::Win32Utils const &)` | 83 | Exported Function
`public: class csf::storage::PrivateKeyContext & __thiscall csf::storage::PrivateKeyContext::operator=(class csf::storage::PrivateKeyContext const &)` | 76 | Exported Function
`public: class csf::storage::FileOperator & __thiscall csf::storage::FileOperator::operator=(class csf::storage::FileOperator const &)` | 75 | Exported Function
`public: class csf::storage::EncryptManager & __thiscall csf::storage::EncryptManager::operator=(class csf::storage::EncryptManager const &)` | 72 | Exported Function
`public: class csf::storage::Win32CertificatePrivateKeyManagementImpl & __thiscall csf::storage::Win32CertificatePrivateKeyManagementImpl::operator=(class csf::storage::Win32CertificatePrivateKeyManagementImpl const &)` | 79 | Exported Function
`public: class csf::storage::Win32CertificatePrivateKeyManagementImpl & __thiscall csf::storage::Win32CertificatePrivateKeyManagementImpl::operator=(class csf::storage::Win32CertificatePrivateKeyManagementImpl &&)` | 78 | Exported Function
`public: class csf::storage::UserCertificateRetrieval & __thiscall csf::storage::UserCertificateRetrieval::operator=(class csf::storage::UserCertificateRetrieval const &)` | 77 | Exported Function
`public: static bool __cdecl csf::storage::CertificatesUtils::convertBinaryCertificate2SSLCertificate(struct csf::storage::CertificatePrivateKeyPair const &,struct x509_st * *,struct evp_pkey_st * *)` | 105 | Exported Function
`public: static bool __cdecl csf::storage::CertificatePrivateKeyPairConverter::addIdentifierToCertificate(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class csf::storage::CertificateContext &)` | 101 | Exported Function
`public: enum csf::storage::CertificatePrivateKeyManagementResult::Result __thiscall csf::storage::CertificateStoreManager::removeAllJabberCertificates(void)` | 173 | Exported Function
`public: static bool __cdecl csf::storage::EncryptFileUtils::encrypt(class csf::SecureString const &,class std::vector<unsigned char,class std::allocator<unsigned char> > &,enum csf::storage::FileCategoryType::FileCategory)` | 116 | Exported Function
`public: static bool __cdecl csf::storage::EncryptFileUtils::decrypt(class std::vector<unsigned char,class std::allocator<unsigned char> > &,class csf::SecureString &,enum csf::storage::FileCategoryType::FileCategory)` | 112 | Exported Function
`public: static bool __cdecl csf::storage::CertificatesUtils::getBestMatchingCertificate(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::vector<struct csf::storage::CertificatePrivateKeyPair,class std::allocator<struct csf::storage::CertificatePrivateKeyPair> > const &,struct x509_st * *,struct evp_pkey_st * *)` | 123 | Exported Function
`public: enum csf::storage::CertificatePrivateKeyManagementResult::Result __thiscall csf::storage::CertificateStoreManager::add(class csf::storage::CertificateContext const &)` | 100 | Exported Function
`public: class std::shared_ptr<class csf::storage::EncryptKeyPersister> __thiscall csf::storage::EncryptKeyStorageManager::setEncryptKeyPersister(class std::shared_ptr<class csf::storage::EncryptKeyPersister> const &)` | 184 | Exported Function
`public: class std::shared_ptr<class csf::storage::DataBlob> __thiscall csf::storage::EncoderDecoderUtility::encode(char const *,void *)` | 115 | Exported Function
`public: enum csf::storage::CertificatePrivateKeyManagementResult::Result __thiscall csf::storage::CertificateStoreManager::getCertificateFromIssuer(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::vector<class std::shared_ptr<class csf::storage::CertificateContext>,class std::allocator<class std::shared_ptr<class csf::storage::CertificateContext> > > &)` | 125 | Exported Function
`public: enum csf::storage::CertificatePrivateKeyManagementResult::Result __thiscall csf::storage::CertificateStoreManager::get(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class csf::storage::CertificateContext &)` | 121 | Exported Function
`public: enum csf::storage::CertificatePrivateKeyManagementResult::Result __thiscall csf::storage::CertificateStoreManager::erase(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 118 | Exported Function
`public: virtual class csf::SecureString __thiscall csf::storage::DefaultEncryptKeyStorageManagerImpl::loadEncryptKey(enum csf::storage::FileCategoryType::FileCategory)` | 164 | Exported Function
`public: virtual class csf::SecureString __thiscall csf::storage::DefaultEncryptKeyStorageManagerImpl::initEncryptKey(enum csf::storage::FileCategoryType::FileCategory)` | 150 | Exported Function
`public: virtual bool __thiscall csf::storage::Win32UserCertificateRetrievalImpl::getCertificateMatchingIssuer(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::vector<struct csf::storage::CertificatePrivateKeyPair,class std::allocator<struct csf::storage::CertificatePrivateKeyPair> > &)` | 129 | Exported Function
`public: virtual class csf::SecureString __thiscall csf::storage::Win32EncryptKeyStorageManagerImpl::loadEncryptKey(enum csf::storage::FileCategoryType::FileCategory)` | 165 | Exported Function
`public: virtual class csf::SecureString __thiscall csf::storage::Win32EncryptKeyStorageManagerImpl::initEncryptKey(enum csf::storage::FileCategoryType::FileCategory)` | 151 | Exported Function
`public: virtual class csf::SecureString __thiscall csf::storage::EncryptKeyStorageManager::getEncryptKey(enum csf::storage::FileCategoryType::FileCategory)` | 135 | Exported Function
`public: virtual bool __thiscall csf::storage::EncryptManager::writeDataToFile(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class csf::SecureString const &,enum csf::storage::FileCategoryType::FileCategory)const ` | 193 | Exported Function
`public: virtual bool __thiscall csf::storage::EncryptManager::readDataFromFile(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class csf::SecureString &,enum csf::storage::FileCategoryType::FileCategory)const ` | 170 | Exported Function
`public: virtual bool __thiscall csf::storage::EncryptManager::encrypt(class csf::SecureString const &,class std::vector<unsigned char,class std::allocator<unsigned char> > &,enum csf::storage::FileCategoryType::FileCategory)const ` | 117 | Exported Function
`public: virtual bool __thiscall csf::storage::Win32EncryptKeyStorageManagerImpl::resetEncryptKeys(void)` | 180 | Exported Function
`public: virtual bool __thiscall csf::storage::FileOperator::write(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::vector<unsigned char,class std::allocator<unsigned char> > const &)const ` | 191 | Exported Function
`public: virtual bool __thiscall csf::storage::FileOperator::read(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::vector<unsigned char,class std::allocator<unsigned char> > &)const ` | 168 | Exported Function
`public: virtual void __thiscall csf::storage::EncryptKeyStorageManager::initialise(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 152 | Exported Function
`public: virtual enum csf::storage::CertificatePrivateKeyManagementResult::Result __thiscall csf::storage::Win32CertificatePrivateKeyManagementImpl::store(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,struct csf::storage::CertificatePrivateKeyPair const &)` | 188 | Exported Function
`public: virtual enum csf::storage::CertificatePrivateKeyManagementResult::Result __thiscall csf::storage::Win32CertificatePrivateKeyManagementImpl::retrieve(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,struct csf::storage::CertificatePrivateKeyPair &)` | 182 | Exported Function
`public: void __thiscall csf::storage::EncryptManager::setFileOperator(class std::shared_ptr<class csf::storage::FileOperator> const &)` | 185 | Exported Function
`public: void __thiscall csf::storage::EncryptManager::setEncryptKeyManager(class std::shared_ptr<class csf::storage::EncryptKeyStorageManager> const &)` | 183 | Exported Function
`public: void * __thiscall csf::storage::DataBlob::getObject(void)const ` | 142 | Exported Function
`public: virtual enum csf::storage::CertificatePrivateKeyManagementResult::Result __thiscall csf::storage::DefaultCertificatePrivateKeyManagementImpl::retrieve(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,struct csf::storage::CertificatePrivateKeyPair &)` | 181 | Exported Function
`public: virtual enum csf::storage::CertificatePrivateKeyManagementResult::Result __thiscall csf::storage::DefaultCertificatePrivateKeyManagementImpl::reset(void)` | 175 | Exported Function
`public: virtual enum csf::storage::CertificatePrivateKeyManagementResult::Result __thiscall csf::storage::DefaultCertificatePrivateKeyManagementImpl::remove(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 171 | Exported Function
`public: virtual enum csf::storage::CertificatePrivateKeyManagementResult::Result __thiscall csf::storage::Win32CertificatePrivateKeyManagementImpl::reset(void)` | 177 | Exported Function
`public: virtual enum csf::storage::CertificatePrivateKeyManagementResult::Result __thiscall csf::storage::Win32CertificatePrivateKeyManagementImpl::remove(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 172 | Exported Function
`public: virtual enum csf::storage::CertificatePrivateKeyManagementResult::Result __thiscall csf::storage::DefaultCertificatePrivateKeyManagementImpl::store(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,struct csf::storage::CertificatePrivateKeyPair const &)` | 187 | Exported Function
`public: virtual __thiscall csf::storage::DefaultEncryptKeyStorageManagerImpl::~DefaultEncryptKeyStorageManagerImpl(void)` | 41 | Exported Function
`public: virtual __thiscall csf::storage::DefaultCertificatePrivateKeyManagementImpl::~DefaultCertificatePrivateKeyManagementImpl(void)` | 40 | Exported Function
`public: virtual __thiscall csf::storage::CertificatePrivateKeyManagement::~CertificatePrivateKeyManagement(void)` | 36 | Exported Function
`public: virtual __thiscall csf::storage::EncryptKeyStorageManager::~EncryptKeyStorageManager(void)` | 44 | Exported Function
`public: virtual __thiscall csf::storage::EncryptKeyPersister::~EncryptKeyPersister(void)` | 43 | Exported Function
`public: virtual __thiscall csf::storage::DefaultUserCertificateRetrievalImpl::~DefaultUserCertificateRetrievalImpl(void)` | 42 | Exported Function
`public: struct csf::storage::CertificatePrivateKeyPair & __thiscall csf::storage::CertificatePrivateKeyPair::operator=(struct csf::storage::CertificatePrivateKeyPair const &)` | 57 | Exported Function
`public: struct csf::storage::CertificatePrivateKeyPair & __thiscall csf::storage::CertificatePrivateKeyPair::operator=(struct csf::storage::CertificatePrivateKeyPair &&)` | 56 | Exported Function
`public: struct csf::storage::CertificatePrivateKeyManagementResult & __thiscall csf::storage::CertificatePrivateKeyManagementResult::operator=(struct csf::storage::CertificatePrivateKeyManagementResult const &)` | 55 | Exported Function
`public: unsigned int __thiscall csf::storage::DataBlob::getSize(void)const ` | 145 | Exported Function
`public: struct csf::storage::FileCategoryType & __thiscall csf::storage::FileCategoryType::operator=(struct csf::storage::FileCategoryType const &)` | 74 | Exported Function
`public: struct csf::storage::FileCategoryType & __thiscall csf::storage::FileCategoryType::operator=(struct csf::storage::FileCategoryType &&)` | 73 | Exported Function
`public: virtual bool __thiscall csf::storage::EncryptKeyStorageManager::initialised(void)` | 154 | Exported Function
`public: virtual bool __thiscall csf::storage::DefaultUserCertificateRetrievalImpl::getCertificateMatchingIssuer(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::vector<struct csf::storage::CertificatePrivateKeyPair,class std::allocator<struct csf::storage::CertificatePrivateKeyPair> > &)` | 128 | Exported Function
`public: virtual bool __thiscall csf::storage::DefaultEncryptKeyStorageManagerImpl::resetEncryptKeys(void)` | 179 | Exported Function
`public: virtual bool __thiscall csf::storage::EncryptManager::decrypt(class std::vector<unsigned char,class std::allocator<unsigned char> > &,class csf::SecureString &,enum csf::storage::FileCategoryType::FileCategory)const ` | 113 | Exported Function
`public: virtual bool __thiscall csf::storage::EncryptKeyStorageManager::reset(void)` | 176 | Exported Function
`public: virtual bool __thiscall csf::storage::EncryptKeyStorageManager::initialiseWithExistingEncryptKeysOnly(void)` | 153 | Exported Function
`public: virtual __thiscall csf::storage::UserCertificateRetrieval::~UserCertificateRetrieval(void)` | 48 | Exported Function
`public: virtual __thiscall csf::storage::FileOperator::~FileOperator(void)` | 46 | Exported Function
`public: virtual __thiscall csf::storage::EncryptManager::~EncryptManager(void)` | 45 | Exported Function
`public: virtual __thiscall csf::storage::Win32UserCertificateRetrievalImpl::~Win32UserCertificateRetrievalImpl(void)` | 51 | Exported Function
`public: virtual __thiscall csf::storage::Win32EncryptKeyStorageManagerImpl::~Win32EncryptKeyStorageManagerImpl(void)` | 50 | Exported Function
`public: virtual __thiscall csf::storage::Win32CertificatePrivateKeyManagementImpl::~Win32CertificatePrivateKeyManagementImpl(void)` | 49 | Exported Function
`public: class csf::storage::EncryptKeyPersister & __thiscall csf::storage::EncryptKeyPersister::operator=(class csf::storage::EncryptKeyPersister const &)` | 71 | Exported Function
`protected: __thiscall csf::storage::CertificatePrivateKeyManagement::CertificatePrivateKeyManagement(void)` | 3 | Exported Function
`private: void __thiscall csf::storage::Win32EncryptKeyStorageManagerImpl::removeEncryptKey(enum csf::storage::FileCategoryType::FileCategory)` | 174 | Exported Function
`private: static class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __cdecl csf::storage::Win32EncryptKeyStorageManagerImpl::getEncryptKeyFilePath(enum csf::storage::FileCategoryType::FileCategory)` | 136 | Exported Function
`protected: bool __thiscall csf::storage::EncryptKeyStorageManager::isEncryptKeyInitialized(enum csf::storage::FileCategoryType::FileCategory)` | 157 | Exported Function
`protected: __thiscall csf::storage::UserCertificateRetrieval::UserCertificateRetrieval(void)` | 26 | Exported Function
`protected: __thiscall csf::storage::EncryptKeyStorageManager::EncryptKeyStorageManager(void)` | 19 | Exported Function
`private: static bool __cdecl csf::storage::CertificatePrivateKeyPairConverter::isPairEmpty(struct csf::storage::CertificatePrivateKeyPair const &)` | 160 | Exported Function
`private: class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __thiscall csf::storage::CertificateContext::getAllProperties(void)const ` | 122 | Exported Function
`private: bool __thiscall csf::storage::PrivateKeyContext::loadCrytographicProviderWithPersistentKeyAccess(struct _CRYPT_KEY_PROV_INFO)` | 163 | Exported Function
`private: static class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __cdecl csf::storage::Win32EncryptKeyStorageManagerImpl::generateSHA1Hash(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 120 | Exported Function
`private: static bool __cdecl csf::storage::Win32EncryptKeyStorageManagerImpl::generateEncryptKey(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class csf::SecureString &)` | 119 | Exported Function
`private: static bool __cdecl csf::storage::PrivateKeyContext::asBool(int)` | 102 | Exported Function
`public: __thiscall csf::storage::CertificatePrivateKeyPair::~CertificatePrivateKeyPair(void)` | 37 | Exported Function
`public: __thiscall csf::storage::CertificatePrivateKeyPair::CertificatePrivateKeyPair(void)` | 7 | Exported Function
`public: __thiscall csf::storage::CertificatePrivateKeyPair::CertificatePrivateKeyPair(struct csf::storage::CertificatePrivateKeyPair const &)` | 6 | Exported Function
`public: __thiscall csf::storage::DataBlob::DataBlob(unsigned int)` | 9 | Exported Function
`public: __thiscall csf::storage::CertificateStoreManager::~CertificateStoreManager(void)` | 38 | Exported Function
`public: __thiscall csf::storage::CertificateStoreManager::CertificateStoreManager(void)` | 8 | Exported Function
`public: __thiscall csf::storage::CertificateContext::CertificateContext(void)` | 2 | Exported Function
`public: __thiscall csf::storage::CertificateContext::CertificateContext(class csf::storage::CertificateContext const &)` | 1 | Exported Function
`protected: static class csf::SecureString csf::storage::EncryptKeyPersister::_key` | 99 | Exported Function
`public: __thiscall csf::storage::CertificatePrivateKeyPair::CertificatePrivateKeyPair(struct csf::storage::CertificatePrivateKeyPair &&)` | 5 | Exported Function
`public: __thiscall csf::storage::CertificatePrivateKeyManagement::CertificatePrivateKeyManagement(class csf::storage::CertificatePrivateKeyManagement const &)` | 4 | Exported Function
`public: __thiscall csf::storage::CertificateContext::~CertificateContext(void)` | 35 | Exported Function
`const csf::storage::EncryptKeyPersister::``vftable'` | 91 | Exported Function
`const csf::storage::DefaultUserCertificateRetrievalImpl::``vftable'` | 90 | Exported Function
`const csf::storage::DefaultEncryptKeyStorageManagerImpl::``vftable'` | 89 | Exported Function
`const csf::storage::FileOperator::``vftable'` | 94 | Exported Function
`const csf::storage::EncryptManager::``vftable'` | 93 | Exported Function
`const csf::storage::EncryptKeyStorageManager::``vftable'` | 92 | Exported Function
`class std::basic_ostream<char,struct std::char_traits<char> > & __cdecl csf::storage::operator<<(class std::basic_ostream<char,struct std::char_traits<char> > &,enum csf::storage::FileCategoryType::FileCategory const &)` | 85 | Exported Function
`class std::basic_ostream<char,struct std::char_traits<char> > & __cdecl csf::storage::operator<<(class std::basic_ostream<char,struct std::char_traits<char> > &,enum csf::storage::CertificatePrivateKeyManagementResult::Result const &)` | 86 | Exported Function
`class std::basic_istream<char,struct std::char_traits<char> > & __cdecl csf::storage::operator>>(class std::basic_istream<char,struct std::char_traits<char> > &,enum csf::storage::FileCategoryType::FileCategory &)` | 84 | Exported Function
`const csf::storage::DefaultCertificatePrivateKeyManagementImpl::``vftable'` | 88 | Exported Function
`const csf::storage::CertificatePrivateKeyManagement::``vftable'` | 87 | Exported Function
`class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __cdecl csf::storage::toString(enum csf::storage::FileCategoryType::FileCategory)` | 189 | Exported Function
`private: bool __thiscall csf::storage::PrivateKeyContext::getExistingCrytographicProvider(struct _CRYPT_KEY_PROV_INFO &)` | 140 | Exported Function
`private: bool __thiscall csf::storage::PrivateKeyContext::deleteExistingCrytographicProvider(struct _CRYPT_KEY_PROV_INFO &)` | 114 | Exported Function
`private: bool __thiscall csf::storage::PrivateKeyContext::createNewCrytographicProviderWithPrivateKeyAccess(struct _CRYPT_KEY_PROV_INFO &)` | 109 | Exported Function
`private: bool __thiscall csf::storage::PrivateKeyContext::loadCrytographicProvider(struct _CRYPT_KEY_PROV_INFO)` | 162 | Exported Function
`private: bool __thiscall csf::storage::PrivateKeyContext::healAndCreateCrytographicProviderWithPersistentKeyAccess(struct _CRYPT_KEY_PROV_INFO)` | 146 | Exported Function
`private: bool __thiscall csf::storage::PrivateKeyContext::getExistingCrytographicProviderWithPrivateKeyAccess(struct _CRYPT_KEY_PROV_INFO &)` | 141 | Exported Function
`const csf::storage::Win32EncryptKeyStorageManagerImpl::``vftable'` | 97 | Exported Function
`const csf::storage::Win32CertificatePrivateKeyManagementImpl::``vftable'` | 96 | Exported Function
`const csf::storage::UserCertificateRetrieval::``vftable'` | 95 | Exported Function
`private: bool __thiscall csf::storage::PrivateKeyContext::createNewCrytographicProvider(struct _CRYPT_KEY_PROV_INFO &)` | 108 | Exported Function
`private: bool __thiscall csf::storage::CertificateContext::isValidContext(struct _CERT_CONTEXT const *)const ` | 161 | Exported Function
`const csf::storage::Win32UserCertificateRetrievalImpl::``vftable'` | 98 | Exported Function
`public: class csf::SecureString __thiscall csf::storage::PrivateKeyContext::getPrivateKeyStr(void)const ` | 143 | Exported Function
`public: class csf::SecureString __thiscall csf::storage::CertificateContext::getCertificateStr(void)const ` | 132 | Exported Function
`public: bool __thiscall csf::storage::PrivateKeyContext::loadKeyFromCryptographicProvider(struct _CRYPT_KEY_PROV_INFO)` | 166 | Exported Function
`public: class csf::storage::CertificatePrivateKeyPairConverter & __thiscall csf::storage::CertificatePrivateKeyPairConverter::operator=(class csf::storage::CertificatePrivateKeyPairConverter &&)` | 58 | Exported Function
`public: class csf::storage::CertificatePrivateKeyManagement & __thiscall csf::storage::CertificatePrivateKeyManagement::operator=(class csf::storage::CertificatePrivateKeyManagement const &)` | 53 | Exported Function
`public: class csf::storage::CertificateContext & __thiscall csf::storage::CertificateContext::operator=(class csf::storage::CertificateContext const &)` | 52 | Exported Function
`public: bool __thiscall csf::storage::CertificateContext::importData(struct _CERT_CONTEXT const *)` | 148 | Exported Function
`public: bool __thiscall csf::storage::CertificateContext::importData(class csf::SecureString const &)` | 147 | Exported Function
`public: __thiscall csf::storage::Win32UserCertificateRetrievalImpl::Win32UserCertificateRetrievalImpl(void)` | 34 | Exported Function
`public: bool __thiscall csf::storage::PrivateKeyContext::importData(class csf::SecureString const &)` | 149 | Exported Function
`public: bool __thiscall csf::storage::DataBlob::isInitialised(void)const ` | 159 | Exported Function
`public: bool __thiscall csf::storage::CertificateContext::setProperty(unsigned long,void const *)` | 186 | Exported Function
`public: class csf::storage::EncoderDecoderUtility & __thiscall csf::storage::EncoderDecoderUtility::operator=(class csf::storage::EncoderDecoderUtility &&)` | 67 | Exported Function
`public: class csf::storage::DefaultUserCertificateRetrievalImpl & __thiscall csf::storage::DefaultUserCertificateRetrievalImpl::operator=(class csf::storage::DefaultUserCertificateRetrievalImpl const &)` | 66 | Exported Function
`public: class csf::storage::DefaultUserCertificateRetrievalImpl & __thiscall csf::storage::DefaultUserCertificateRetrievalImpl::operator=(class csf::storage::DefaultUserCertificateRetrievalImpl &&)` | 65 | Exported Function
`public: class csf::storage::EncryptFileUtils & __thiscall csf::storage::EncryptFileUtils::operator=(class csf::storage::EncryptFileUtils const &)` | 70 | Exported Function
`public: class csf::storage::EncryptFileUtils & __thiscall csf::storage::EncryptFileUtils::operator=(class csf::storage::EncryptFileUtils &&)` | 69 | Exported Function
`public: class csf::storage::EncoderDecoderUtility & __thiscall csf::storage::EncoderDecoderUtility::operator=(class csf::storage::EncoderDecoderUtility const &)` | 68 | Exported Function
`public: class csf::storage::CertificatesUtils & __thiscall csf::storage::CertificatesUtils::operator=(class csf::storage::CertificatesUtils &&)` | 61 | Exported Function
`public: class csf::storage::CertificateStoreManager & __thiscall csf::storage::CertificateStoreManager::operator=(class csf::storage::CertificateStoreManager const &)` | 60 | Exported Function
`public: class csf::storage::CertificatePrivateKeyPairConverter & __thiscall csf::storage::CertificatePrivateKeyPairConverter::operator=(class csf::storage::CertificatePrivateKeyPairConverter const &)` | 59 | Exported Function
`public: class csf::storage::DefaultCertificatePrivateKeyManagementImpl & __thiscall csf::storage::DefaultCertificatePrivateKeyManagementImpl::operator=(class csf::storage::DefaultCertificatePrivateKeyManagementImpl const &)` | 64 | Exported Function
`public: class csf::storage::DefaultCertificatePrivateKeyManagementImpl & __thiscall csf::storage::DefaultCertificatePrivateKeyManagementImpl::operator=(class csf::storage::DefaultCertificatePrivateKeyManagementImpl &&)` | 63 | Exported Function
`public: class csf::storage::CertificatesUtils & __thiscall csf::storage::CertificatesUtils::operator=(class csf::storage::CertificatesUtils const &)` | 62 | Exported Function
`public: __thiscall csf::storage::EncryptKeyPersister::EncryptKeyPersister(class csf::storage::EncryptKeyPersister const &)` | 17 | Exported Function
`public: __thiscall csf::storage::DefaultUserCertificateRetrievalImpl::DefaultUserCertificateRetrievalImpl(void)` | 16 | Exported Function
`public: __thiscall csf::storage::DefaultUserCertificateRetrievalImpl::DefaultUserCertificateRetrievalImpl(class csf::storage::DefaultUserCertificateRetrievalImpl const &)` | 15 | Exported Function
`public: __thiscall csf::storage::EncryptManager::EncryptManager(void)` | 21 | Exported Function
`public: __thiscall csf::storage::EncryptManager::EncryptManager(class csf::storage::EncryptManager const &)` | 20 | Exported Function
`public: __thiscall csf::storage::EncryptKeyPersister::EncryptKeyPersister(void)` | 18 | Exported Function
`public: __thiscall csf::storage::DefaultCertificatePrivateKeyManagementImpl::DefaultCertificatePrivateKeyManagementImpl(class csf::storage::DefaultCertificatePrivateKeyManagementImpl const &)` | 11 | Exported Function
`public: __thiscall csf::storage::DefaultCertificatePrivateKeyManagementImpl::DefaultCertificatePrivateKeyManagementImpl(class csf::storage::DefaultCertificatePrivateKeyManagementImpl &&)` | 10 | Exported Function
`public: __thiscall csf::storage::DataBlob::~DataBlob(void)` | 39 | Exported Function
`public: __thiscall csf::storage::DefaultUserCertificateRetrievalImpl::DefaultUserCertificateRetrievalImpl(class csf::storage::DefaultUserCertificateRetrievalImpl &&)` | 14 | Exported Function
`public: __thiscall csf::storage::DefaultEncryptKeyStorageManagerImpl::DefaultEncryptKeyStorageManagerImpl(void)` | 13 | Exported Function
`public: __thiscall csf::storage::DefaultCertificatePrivateKeyManagementImpl::DefaultCertificatePrivateKeyManagementImpl(void)` | 12 | Exported Function
`public: __thiscall csf::storage::Win32CertificatePrivateKeyManagementImpl::Win32CertificatePrivateKeyManagementImpl(void)` | 30 | Exported Function
`public: __thiscall csf::storage::Win32CertificatePrivateKeyManagementImpl::Win32CertificatePrivateKeyManagementImpl(class csf::storage::Win32CertificatePrivateKeyManagementImpl const &)` | 29 | Exported Function
`public: __thiscall csf::storage::Win32CertificatePrivateKeyManagementImpl::Win32CertificatePrivateKeyManagementImpl(class csf::storage::Win32CertificatePrivateKeyManagementImpl &&)` | 28 | Exported Function
`public: __thiscall csf::storage::Win32UserCertificateRetrievalImpl::Win32UserCertificateRetrievalImpl(class csf::storage::Win32UserCertificateRetrievalImpl const &)` | 33 | Exported Function
`public: __thiscall csf::storage::Win32UserCertificateRetrievalImpl::Win32UserCertificateRetrievalImpl(class csf::storage::Win32UserCertificateRetrievalImpl &&)` | 32 | Exported Function
`public: __thiscall csf::storage::Win32EncryptKeyStorageManagerImpl::Win32EncryptKeyStorageManagerImpl(void)` | 31 | Exported Function
`public: __thiscall csf::storage::PrivateKeyContext::PrivateKeyContext(class csf::storage::PrivateKeyContext const &)` | 24 | Exported Function
`public: __thiscall csf::storage::FileOperator::FileOperator(void)` | 23 | Exported Function
`public: __thiscall csf::storage::FileOperator::FileOperator(class csf::storage::FileOperator const &)` | 22 | Exported Function
`public: __thiscall csf::storage::UserCertificateRetrieval::UserCertificateRetrieval(class csf::storage::UserCertificateRetrieval const &)` | 27 | Exported Function
`public: __thiscall csf::storage::PrivateKeyContext::~PrivateKeyContext(void)` | 47 | Exported Function
`public: __thiscall csf::storage::PrivateKeyContext::PrivateKeyContext(void)` | 25 | Exported Function


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
* VirusTotal Link: https://www.virustotal.com/gui/file/86a3061b5e5ba3ad516ee2e7b0115fba7086629ca6e89970ef59a58821023e00/detection/




MIT License. Copyright (c) 2020 Strontic.


