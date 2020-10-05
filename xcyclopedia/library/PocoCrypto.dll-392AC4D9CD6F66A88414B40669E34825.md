---
title: PocoCrypto.dll | This file is part of the POCO C++ Libraries.
excerpt: What is PocoCrypto.dll?
---

# PocoCrypto.dll 

* File Path: `C:\Program Files (x86)\Sennheiser\SenncomSDK\PocoCrypto.dll`
* Description: This file is part of the POCO C++ Libraries.

## Hashes

Type | Hash
-- | --
MD5 | `392AC4D9CD6F66A88414B40669E34825`
SHA1 | `A10B02E45D1B36C0B380F500A35017188F2A4CCA`
SHA256 | `8E22013214C17342EFC7EEBB9E10FF07E4ED286EBA642BDD8C21A8DA13E6591A`
SHA384 | `F6E5A2E87403D6C0825F1654CC2355CE152AB59B00F0BBB583CE6AB81C49E1313AAC533464F08C8A2AA0AB34543C80F8`
SHA512 | `F9BBF8EF5C2E6E92B2E26B1DB63CE43FB030379AD8D9CF2C94CD0565FEBDF1545642CF9BC8052F3BE3EE60E1403D5789F5B7F0ABE591786E4FBB75F55FBE3F4A`
SSDEEP | `3072:o0tvWWeGGy81beZDr8EMi0lURohRMidcj3PKBNJ3RTTqic1GPK:o0t698sEWkohKidcjPKBNJ35Tqic1GS`
IMP | `28A8F0BC4E2E96C85C36EE5AAD9E775E`
PESHA1 | `310A3ECD985CEA069BC65CF7ED9F7F8DE6B2E6D4`
PE256 | `68379EEB936CC660855F0B488A45D1E7715CBBB94D1EA8FA4DC4BBE8F534BBE1`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`public: class std::vector<unsigned char,class std::allocator<unsigned char> > const & __thiscall Poco::Crypto::ECDSADigestEngine::signature(void)` | 254 | Exported Function
`public: class std::vector<unsigned char,class std::allocator<unsigned char> > const & __thiscall Poco::Crypto::RSADigestEngine::signature(void)` | 255 | Exported Function
`public: class std::vector<unsigned char,class std::allocator<unsigned char> > const & __thiscall Poco::Crypto::CipherKey::getIV(void)const ` | 195 | Exported Function
`public: class std::vector<unsigned char,class std::allocator<unsigned char> > const & __thiscall Poco::Crypto::CipherKey::getKey(void)const ` | 196 | Exported Function
`public: int __thiscall Poco::Crypto::CipherKey::blockSize(void)const ` | 154 | Exported Function
`public: int __thiscall Poco::Crypto::CipherKey::ivSize(void)const ` | 215 | Exported Function
`public: enum Poco::Crypto::CipherKeyImpl::Mode __thiscall Poco::Crypto::CipherKey::mode(void)const ` | 221 | Exported Function
`public: enum Poco::Crypto::KeyPair::Type __thiscall Poco::Crypto::KeyPair::type(void)const ` | 263 | Exported Function
`public: class std::vector<unsigned char,class std::allocator<unsigned char> > __thiscall Poco::Crypto::RSAKey::modulus(void)const ` | 222 | Exported Function
`public: class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const & __thiscall Poco::Crypto::X509Certificate::serialNumber(void)const ` | 245 | Exported Function
`public: class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const & __thiscall Poco::Crypto::X509Certificate::subjectName(void)const ` | 259 | Exported Function
`public: class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const & __thiscall Poco::Crypto::PKCS12Container::getFriendlyName(void)const ` | 193 | Exported Function
`public: class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const & __thiscall Poco::Crypto::X509Certificate::issuerName(void)const ` | 214 | Exported Function
`public: class std::vector<unsigned char,class std::allocator<unsigned char> > __thiscall Poco::Crypto::RSAKey::decryptionExponent(void)const ` | 169 | Exported Function
`public: class std::vector<unsigned char,class std::allocator<unsigned char> > __thiscall Poco::Crypto::RSAKey::encryptionExponent(void)const ` | 185 | Exported Function
`public: class std::vector<class Poco::Crypto::X509Certificate,class std::allocator<class Poco::Crypto::X509Certificate> > const & __thiscall Poco::Crypto::PKCS12Container::getCACerts(void)const ` | 190 | Exported Function
`public: class std::vector<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> >,class std::allocator<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > > > const & __thiscall Poco::Crypto::PKCS12Container::getFriendlyNamesCA(void)const ` | 194 | Exported Function
`public: static void __cdecl Poco::Crypto::OpenSSLInitializer::enableFIPSMode(bool)` | 182 | Exported Function
`public: static void __cdecl Poco::Crypto::OpenSSLInitializer::initialize(void)` | 208 | Exported Function
`public: static int __cdecl Poco::Crypto::ECKey::getCurveNID(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > &)` | 191 | Exported Function
`public: static struct evp_pkey_st * __cdecl Poco::Crypto::EVPPKey::duplicate(struct evp_pkey_st const *,struct evp_pkey_st * *)` | 178 | Exported Function
`public: struct x509_st * __thiscall Poco::Crypto::X509Certificate::dup(void)const ` | 177 | Exported Function
`public: struct x509_st const * __thiscall Poco::Crypto::X509Certificate::certificate(void)const ` | 155 | Exported Function
`public: static void __cdecl Poco::Crypto::OpenSSLInitializer::uninitialize(void)` | 264 | Exported Function
`public: static void __cdecl Poco::Crypto::X509Certificate::writePEM(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::vector<class Poco::Crypto::X509Certificate,class std::allocator<class Poco::Crypto::X509Certificate> > const &)` | 273 | Exported Function
`public: static class std::vector<class Poco::Crypto::X509Certificate,class std::allocator<class Poco::Crypto::X509Certificate> > __cdecl Poco::Crypto::X509Certificate::readPEM(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 233 | Exported Function
`public: int __thiscall Poco::Crypto::EVPPKey::type(void)const ` | 262 | Exported Function
`public: long __thiscall Poco::Crypto::X509Certificate::version(void)const ` | 272 | Exported Function
`public: int __thiscall Poco::Crypto::CipherKey::keySize(void)const ` | 216 | Exported Function
`public: int __thiscall Poco::Crypto::DigestEngine::nid(void)const ` | 228 | Exported Function
`public: static class Poco::Crypto::CipherFactory & __cdecl Poco::Crypto::CipherFactory::defaultFactory(void)` | 170 | Exported Function
`public: static class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __cdecl Poco::Crypto::ECKey::getCurveName(int)` | 192 | Exported Function
`public: static bool __cdecl Poco::Crypto::ECKey::hasCurve(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 199 | Exported Function
`public: static bool __cdecl Poco::Crypto::OpenSSLInitializer::isFIPSEnabled(void)` | 210 | Exported Function
`public: class Poco::Crypto::CryptoStreamBuf * __thiscall Poco::Crypto::CryptoIOS::rdbuf(void)` | 231 | Exported Function
`public: class Poco::Crypto::CryptoTransform & __thiscall Poco::Crypto::CryptoTransform::operator=(class Poco::Crypto::CryptoTransform const &)` | 94 | Exported Function
`public: class Poco::Crypto::CipherKey & __thiscall Poco::Crypto::CipherKey::operator=(class Poco::Crypto::CipherKey const &)` | 92 | Exported Function
`public: class Poco::Crypto::CryptoException & __thiscall Poco::Crypto::CryptoException::operator=(class Poco::Crypto::CryptoException const &)` | 93 | Exported Function
`public: class Poco::Crypto::EVPPKey & __thiscall Poco::Crypto::EVPPKey::operator=(class Poco::Crypto::EVPPKey const &)` | 97 | Exported Function
`public: class Poco::Crypto::EVPPKey __thiscall Poco::Crypto::PKCS12Container::getKey(void)const ` | 197 | Exported Function
`public: class Poco::Crypto::ECKey & __thiscall Poco::Crypto::ECKey::operator=(class Poco::Crypto::ECKey const &)` | 95 | Exported Function
`public: class Poco::Crypto::EVPPKey & __thiscall Poco::Crypto::EVPPKey::operator=(class Poco::Crypto::EVPPKey &&)` | 96 | Exported Function
`public: class Poco::Crypto::Cipher * __thiscall Poco::Crypto::CipherFactory::createCipher(class Poco::Crypto::RSAKey const &,enum RSAPaddingMode)` | 166 | Exported Function
`public: bool __thiscall Poco::Crypto::X509Certificate::issuedBy(class Poco::Crypto::X509Certificate const &)const ` | 212 | Exported Function
`public: class Poco::AutoPtr<class Poco::Crypto::CipherKeyImpl> __thiscall Poco::Crypto::CipherKey::impl(void)` | 203 | Exported Function
`public: bool __thiscall Poco::Crypto::RSADigestEngine::verify(class std::vector<unsigned char,class std::allocator<unsigned char> > const &)` | 271 | Exported Function
`public: bool __thiscall Poco::Crypto::X509Certificate::equals(class Poco::Crypto::X509Certificate const &)const ` | 186 | Exported Function
`public: class Poco::AutoPtr<class Poco::Crypto::RSAKeyImpl> __thiscall Poco::Crypto::RSAKey::impl(void)const ` | 206 | Exported Function
`public: class Poco::Crypto::Cipher * __thiscall Poco::Crypto::CipherFactory::createCipher(class Poco::Crypto::CipherKey const &)` | 165 | Exported Function
`public: class Poco::AutoPtr<class Poco::Crypto::ECKeyImpl> __thiscall Poco::Crypto::ECKey::impl(void)const ` | 204 | Exported Function
`public: class Poco::AutoPtr<class Poco::Crypto::KeyPairImpl> __thiscall Poco::Crypto::KeyPair::impl(void)const ` | 205 | Exported Function
`public: class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __thiscall Poco::Crypto::X509Certificate::issuerName(enum Poco::Crypto::X509Certificate::NID)const ` | 213 | Exported Function
`public: class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __thiscall Poco::Crypto::X509Certificate::signatureAlgorithm(void)const ` | 256 | Exported Function
`public: class Poco::DateTime __thiscall Poco::Crypto::X509Certificate::validFrom(void)const ` | 269 | Exported Function
`public: class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __thiscall Poco::Crypto::X509Certificate::commonName(void)const ` | 164 | Exported Function
`public: class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const & __thiscall Poco::Crypto::DigestEngine::algorithm(void)const ` | 153 | Exported Function
`public: class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const & __thiscall Poco::Crypto::KeyPair::name(void)const ` | 225 | Exported Function
`public: class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __thiscall Poco::Crypto::X509Certificate::subjectName(enum Poco::Crypto::X509Certificate::NID)const ` | 258 | Exported Function
`public: class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const & __thiscall Poco::Crypto::CipherKey::name(void)const ` | 223 | Exported Function
`public: class Poco::DateTime __thiscall Poco::Crypto::X509Certificate::expiresOn(void)const ` | 187 | Exported Function
`public: class Poco::Crypto::OpenSSLInitializer & __thiscall Poco::Crypto::OpenSSLInitializer::operator=(class Poco::Crypto::OpenSSLInitializer const &)` | 100 | Exported Function
`public: class Poco::Crypto::PKCS12Container & __thiscall Poco::Crypto::PKCS12Container::operator=(class Poco::Crypto::PKCS12Container &&)` | 101 | Exported Function
`public: class Poco::Crypto::KeyPair & __thiscall Poco::Crypto::KeyPair::operator=(class Poco::Crypto::KeyPair const &)` | 98 | Exported Function
`public: class Poco::Crypto::OpenSSLException & __thiscall Poco::Crypto::OpenSSLException::operator=(class Poco::Crypto::OpenSSLException const &)` | 99 | Exported Function
`public: class Poco::Crypto::X509Certificate & __thiscall Poco::Crypto::X509Certificate::operator=(class Poco::Crypto::X509Certificate const &)` | 104 | Exported Function
`public: class Poco::Crypto::X509Certificate const & __thiscall Poco::Crypto::PKCS12Container::getX509Certificate(void)const ` | 198 | Exported Function
`public: class Poco::Crypto::PKCS12Container & __thiscall Poco::Crypto::PKCS12Container::operator=(class Poco::Crypto::PKCS12Container const &)` | 102 | Exported Function
`public: class Poco::Crypto::RSAKey & __thiscall Poco::Crypto::RSAKey::operator=(class Poco::Crypto::RSAKey const &)` | 103 | Exported Function
`public: virtual __thiscall Poco::Crypto::Cipher::~Cipher(void)` | 68 | Exported Function
`public: void __thiscall Poco::Crypto::CryptoException::``default constructor closure'(void)` | 148 | Exported Function
`public: void __thiscall Poco::Crypto::CryptoInputStream::``vbase destructor'(void)` | 142 | Exported Function
`public: void __thiscall Poco::Crypto::CipherKey::setIV(class std::vector<unsigned char,class std::allocator<unsigned char> > const &)` | 247 | Exported Function
`public: void __thiscall Poco::Crypto::CipherKey::setKey(class std::vector<unsigned char,class std::allocator<unsigned char> > const &)` | 248 | Exported Function
`public: void __thiscall Poco::Crypto::CryptoOutputStream::close(void)` | 160 | Exported Function
`public: void __thiscall Poco::Crypto::CryptoStreamBuf::close(void)` | 161 | Exported Function
`public: void __thiscall Poco::Crypto::CryptoIOS::``vbase destructor'(void)` | 141 | Exported Function
`public: void __thiscall Poco::Crypto::CryptoOutputStream::``vbase destructor'(void)` | 143 | Exported Function
`public: virtual void __thiscall Poco::Crypto::RSADigestEngine::reset(void)` | 236 | Exported Function
`public: virtual void __thiscall Poco::Crypto::CryptoException::rethrow(void)const ` | 237 | Exported Function
`public: virtual void __thiscall Poco::Crypto::DigestEngine::reset(void)` | 234 | Exported Function
`public: virtual void __thiscall Poco::Crypto::Cipher::decrypt(class std::basic_istream<char,struct std::char_traits<char> > &,class std::basic_ostream<char,struct std::char_traits<char> > &,enum Poco::Crypto::Cipher::Encoding)` | 167 | Exported Function
`public: virtual void __thiscall Poco::Crypto::Cipher::encrypt(class std::basic_istream<char,struct std::char_traits<char> > &,class std::basic_ostream<char,struct std::char_traits<char> > &,enum Poco::Crypto::Cipher::Encoding)` | 183 | Exported Function
`public: virtual void __thiscall Poco::Crypto::KeyPair::save(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)const ` | 241 | Exported Function
`public: virtual void __thiscall Poco::Crypto::OpenSSLException::rethrow(void)const ` | 238 | Exported Function
`public: virtual void __thiscall Poco::Crypto::ECDSADigestEngine::reset(void)` | 235 | Exported Function
`public: virtual void __thiscall Poco::Crypto::KeyPair::save(class std::basic_ostream<char,struct std::char_traits<char> > *,class std::basic_ostream<char,struct std::char_traits<char> > *,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)const ` | 242 | Exported Function
`public: void __thiscall Poco::Crypto::X509Certificate::print(class std::basic_ostream<char,struct std::char_traits<char> > &)const ` | 230 | Exported Function
`public: void __thiscall Poco::Crypto::X509Certificate::save(class std::basic_ostream<char,struct std::char_traits<char> > &)const ` | 243 | Exported Function
`public: void __thiscall Poco::Crypto::OpenSSLException::``default constructor closure'(void)` | 150 | Exported Function
`public: void __thiscall Poco::Crypto::X509Certificate::extractNames(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > &,class std::set<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> >,struct std::less<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > >,class std::allocator<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > > > &)const ` | 189 | Exported Function
`void __cdecl Poco::Crypto::initializeCrypto(void)` | 209 | Exported Function
`void __cdecl Poco::Crypto::uninitializeCrypto(void)` | 265 | Exported Function
`public: void __thiscall Poco::Crypto::X509Certificate::save(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)const ` | 244 | Exported Function
`public: void __thiscall Poco::Crypto::X509Certificate::swap(class Poco::Crypto::X509Certificate &)` | 260 | Exported Function
`public: void __thiscall Poco::Crypto::KeyPair::``default constructor closure'(void)` | 149 | Exported Function
`public: void __thiscall Poco::Crypto::DecryptingOutputStream::close(void)` | 162 | Exported Function
`public: void __thiscall Poco::Crypto::EncryptingInputStream::``vbase destructor'(void)` | 146 | Exported Function
`public: void __thiscall Poco::Crypto::DecryptingInputStream::``vbase destructor'(void)` | 144 | Exported Function
`public: void __thiscall Poco::Crypto::DecryptingOutputStream::``vbase destructor'(void)` | 145 | Exported Function
`public: void __thiscall Poco::Crypto::EVPPKey::save(class std::basic_ostream<char,struct std::char_traits<char> > *,class std::basic_ostream<char,struct std::char_traits<char> > *,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)const ` | 240 | Exported Function
`public: void __thiscall Poco::Crypto::EVPPKey::save(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)const ` | 239 | Exported Function
`public: void __thiscall Poco::Crypto::EncryptingOutputStream::``vbase destructor'(void)` | 147 | Exported Function
`public: void __thiscall Poco::Crypto::EncryptingOutputStream::close(void)` | 163 | Exported Function
`public: virtual __thiscall Poco::Crypto::ECKey::~ECKey(void)` | 81 | Exported Function
`public: virtual __thiscall Poco::Crypto::EncryptingInputStream::~EncryptingInputStream(void)` | 83 | Exported Function
`public: virtual __thiscall Poco::Crypto::DigestEngine::~DigestEngine(void)` | 79 | Exported Function
`public: virtual __thiscall Poco::Crypto::ECDSADigestEngine::~ECDSADigestEngine(void)` | 80 | Exported Function
`public: virtual __thiscall Poco::Crypto::OpenSSLException::~OpenSSLException(void)` | 86 | Exported Function
`public: virtual __thiscall Poco::Crypto::RSADigestEngine::~RSADigestEngine(void)` | 89 | Exported Function
`public: virtual __thiscall Poco::Crypto::EncryptingOutputStream::~EncryptingOutputStream(void)` | 84 | Exported Function
`public: virtual __thiscall Poco::Crypto::KeyPair::~KeyPair(void)` | 85 | Exported Function
`public: virtual __thiscall Poco::Crypto::DecryptingOutputStream::~DecryptingOutputStream(void)` | 78 | Exported Function
`public: virtual __thiscall Poco::Crypto::CryptoInputStream::~CryptoInputStream(void)` | 73 | Exported Function
`public: virtual __thiscall Poco::Crypto::CryptoIOS::~CryptoIOS(void)` | 72 | Exported Function
`public: virtual __thiscall Poco::Crypto::CipherFactory::~CipherFactory(void)` | 69 | Exported Function
`public: virtual __thiscall Poco::Crypto::CryptoException::~CryptoException(void)` | 71 | Exported Function
`public: virtual __thiscall Poco::Crypto::CryptoTransform::~CryptoTransform(void)` | 76 | Exported Function
`public: virtual __thiscall Poco::Crypto::DecryptingInputStream::~DecryptingInputStream(void)` | 77 | Exported Function
`public: virtual __thiscall Poco::Crypto::CryptoOutputStream::~CryptoOutputStream(void)` | 74 | Exported Function
`public: virtual __thiscall Poco::Crypto::CryptoStreamBuf::~CryptoStreamBuf(void)` | 75 | Exported Function
`public: virtual class std::vector<unsigned char,class std::allocator<unsigned char> > const & __thiscall Poco::Crypto::RSADigestEngine::digest(void)` | 173 | Exported Function
`public: virtual int __thiscall Poco::Crypto::CryptoTransform::setPadding(int)` | 253 | Exported Function
`public: virtual class std::vector<unsigned char,class std::allocator<unsigned char> > const & __thiscall Poco::Crypto::DigestEngine::digest(void)` | 171 | Exported Function
`public: virtual class std::vector<unsigned char,class std::allocator<unsigned char> > const & __thiscall Poco::Crypto::ECDSADigestEngine::digest(void)` | 172 | Exported Function
`public: virtual unsigned int __thiscall Poco::Crypto::ECDSADigestEngine::digestLength(void)const ` | 175 | Exported Function
`public: virtual unsigned int __thiscall Poco::Crypto::RSADigestEngine::digestLength(void)const ` | 176 | Exported Function
`public: virtual int __thiscall Poco::Crypto::KeyPair::size(void)const ` | 257 | Exported Function
`public: virtual unsigned int __thiscall Poco::Crypto::DigestEngine::digestLength(void)const ` | 174 | Exported Function
`public: virtual class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __thiscall Poco::Crypto::Cipher::encryptString(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,enum Poco::Crypto::Cipher::Encoding)` | 184 | Exported Function
`public: virtual char const * __thiscall Poco::Crypto::CryptoException::name(void)const ` | 224 | Exported Function
`public: virtual char const * __thiscall Poco::Crypto::OpenSSLException::className(void)const ` | 157 | Exported Function
`public: virtual __thiscall Poco::Crypto::RSAKey::~RSAKey(void)` | 90 | Exported Function
`public: virtual char const * __thiscall Poco::Crypto::CryptoException::className(void)const ` | 156 | Exported Function
`public: virtual class Poco::Exception * __thiscall Poco::Crypto::OpenSSLException::clone(void)const ` | 159 | Exported Function
`public: virtual class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __thiscall Poco::Crypto::Cipher::decryptString(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,enum Poco::Crypto::Cipher::Encoding)` | 168 | Exported Function
`public: virtual char const * __thiscall Poco::Crypto::OpenSSLException::name(void)const ` | 226 | Exported Function
`public: virtual class Poco::Exception * __thiscall Poco::Crypto::CryptoException::clone(void)const ` | 158 | Exported Function
`protected: static struct CRYPTO_dynlock_value * __cdecl Poco::Crypto::OpenSSLInitializer::dynlockCreate(char const *,int)` | 180 | Exported Function
`protected: static unsigned long __cdecl Poco::Crypto::OpenSSLInitializer::id(void)` | 202 | Exported Function
`private: void __thiscall Poco::Crypto::PKCS12Container::load(struct PKCS12_st *,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 217 | Exported Function
`protected: __thiscall Poco::Crypto::Cipher::Cipher(void)` | 1 | Exported Function
`protected: static void __cdecl Poco::Crypto::OpenSSLInitializer::lock(int,int,char const *,int)` | 220 | Exported Function
`protected: virtual int __thiscall Poco::Crypto::CryptoStreamBuf::readFromDevice(char *,__int64)` | 232 | Exported Function
`protected: static void __cdecl Poco::Crypto::OpenSSLInitializer::dynlock(int,struct CRYPTO_dynlock_value *,char const *,int)` | 179 | Exported Function
`protected: static void __cdecl Poco::Crypto::OpenSSLInitializer::dynlockDestroy(struct CRYPTO_dynlock_value *,char const *,int)` | 181 | Exported Function
`private: void __thiscall Poco::Crypto::OpenSSLException::setExtMessage(void)` | 246 | Exported Function
`private: static int __cdecl Poco::Crypto::EVPPKey::type(struct evp_pkey_st const *)` | 261 | Exported Function
`private: void __thiscall Poco::Crypto::EVPPKey::newECKey(char const *)` | 227 | Exported Function
`private: static class Poco::FastMutex * Poco::Crypto::OpenSSLInitializer::_mutexes` | 151 | Exported Function
`private: static int __cdecl Poco::Crypto::EVPPKey::passCB(char *,int,int,void *)` | 229 | Exported Function
`private: void __thiscall Poco::Crypto::EVPPKey::setKey(struct ec_key_st *)` | 249 | Exported Function
`private: void __thiscall Poco::Crypto::EVPPKey::setKey(struct rsa_st *)` | 250 | Exported Function
`private: void __thiscall Poco::Crypto::EVPPKey::setKey(class Poco::Crypto::ECKey *)` | 251 | Exported Function
`private: void __thiscall Poco::Crypto::EVPPKey::setKey(class Poco::Crypto::RSAKey *)` | 252 | Exported Function
`public: __thiscall Poco::Crypto::CipherKey::CipherKey(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::vector<unsigned char,class std::allocator<unsigned char> > const &,class std::vector<unsigned char,class std::allocator<unsigned char> > const &)` | 6 | Exported Function
`public: __thiscall Poco::Crypto::CipherKey::~CipherKey(void)` | 70 | Exported Function
`public: __thiscall Poco::Crypto::CipherKey::CipherKey(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 5 | Exported Function
`public: __thiscall Poco::Crypto::CipherKey::CipherKey(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,int,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 4 | Exported Function
`public: __thiscall Poco::Crypto::CryptoException::CryptoException(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,int)` | 8 | Exported Function
`public: __thiscall Poco::Crypto::CryptoException::CryptoException(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,int)` | 10 | Exported Function
`public: __thiscall Poco::Crypto::CryptoException::CryptoException(class Poco::Crypto::CryptoException const &)` | 7 | Exported Function
`public: __thiscall Poco::Crypto::CryptoException::CryptoException(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class Poco::Exception const &,int)` | 9 | Exported Function
`public: __thiscall Poco::Crypto::CipherKey::CipherKey(class Poco::Crypto::CipherKey const &)` | 3 | Exported Function
`protected: virtual void __thiscall Poco::Crypto::ECDSADigestEngine::updateImpl(void const *,unsigned int)` | 267 | Exported Function
`protected: virtual void __thiscall Poco::Crypto::RSADigestEngine::updateImpl(void const *,unsigned int)` | 268 | Exported Function
`protected: virtual int __thiscall Poco::Crypto::CryptoStreamBuf::writeToDevice(char const *,__int64)` | 274 | Exported Function
`protected: virtual void __thiscall Poco::Crypto::DigestEngine::updateImpl(void const *,unsigned int)` | 266 | Exported Function
`protected: void __thiscall Poco::Crypto::X509Certificate::load(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 219 | Exported Function
`public: __thiscall Poco::Crypto::CipherFactory::CipherFactory(void)` | 2 | Exported Function
`protected: void __thiscall Poco::Crypto::X509Certificate::init(void)` | 207 | Exported Function
`protected: void __thiscall Poco::Crypto::X509Certificate::load(class std::basic_istream<char,struct std::char_traits<char> > &)` | 218 | Exported Function
`const Poco::Crypto::CryptoStreamBuf::``vftable'` | 115 | Exported Function
`const Poco::Crypto::CryptoTransform::``vftable'` | 116 | Exported Function
`const Poco::Crypto::CryptoOutputStream::``vbtable'{for ``std::basic_ostream<char,struct std::char_traits<char> >'}` | 131 | Exported Function
`const Poco::Crypto::CryptoOutputStream::``vftable'` | 114 | Exported Function
`const Poco::Crypto::DecryptingInputStream::``vftable'` | 117 | Exported Function
`const Poco::Crypto::DecryptingOutputStream::``vbtable'{for ``Poco::Crypto::CryptoIOS'}` | 136 | Exported Function
`const Poco::Crypto::DecryptingInputStream::``vbtable'{for ``Poco::Crypto::CryptoIOS'}` | 134 | Exported Function
`const Poco::Crypto::DecryptingInputStream::``vbtable'{for ``std::basic_istream<char,struct std::char_traits<char> >'}` | 133 | Exported Function
`const Poco::Crypto::CryptoOutputStream::``vbtable'{for ``Poco::Crypto::CryptoIOS'}` | 132 | Exported Function
`const Poco::Crypto::CryptoException::``vftable'` | 111 | Exported Function
`const Poco::Crypto::CryptoInputStream::``vbtable'{for ``Poco::Crypto::CryptoIOS'}` | 130 | Exported Function
`const Poco::Crypto::Cipher::``vftable'` | 109 | Exported Function
`const Poco::Crypto::CipherFactory::``vftable'` | 110 | Exported Function
`const Poco::Crypto::CryptoIOS::``vbtable'` | 128 | Exported Function
`const Poco::Crypto::CryptoIOS::``vftable'` | 112 | Exported Function
`const Poco::Crypto::CryptoInputStream::``vbtable'{for ``std::basic_istream<char,struct std::char_traits<char> >'}` | 129 | Exported Function
`const Poco::Crypto::CryptoInputStream::``vftable'` | 113 | Exported Function
`const Poco::Crypto::KeyPair::``vftable'` | 124 | Exported Function
`const Poco::Crypto::OpenSSLException::``vftable'` | 125 | Exported Function
`const Poco::Crypto::EncryptingOutputStream::``vbtable'{for ``std::basic_ostream<char,struct std::char_traits<char> >'}` | 139 | Exported Function
`const Poco::Crypto::EncryptingOutputStream::``vftable'` | 123 | Exported Function
`private: class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __thiscall Poco::Crypto::PKCS12Container::extractFriendlyName(struct x509_st *)` | 188 | Exported Function
`private: static class Poco::AtomicCounter Poco::Crypto::OpenSSLInitializer::_rc` | 152 | Exported Function
`const Poco::Crypto::RSADigestEngine::``vftable'` | 126 | Exported Function
`const Poco::Crypto::RSAKey::``vftable'` | 127 | Exported Function
`const Poco::Crypto::EncryptingOutputStream::``vbtable'{for ``Poco::Crypto::CryptoIOS'}` | 140 | Exported Function
`const Poco::Crypto::DigestEngine::``vftable'` | 119 | Exported Function
`const Poco::Crypto::ECDSADigestEngine::``vftable'` | 120 | Exported Function
`const Poco::Crypto::DecryptingOutputStream::``vbtable'{for ``std::basic_ostream<char,struct std::char_traits<char> >'}` | 135 | Exported Function
`const Poco::Crypto::DecryptingOutputStream::``vftable'` | 118 | Exported Function
`const Poco::Crypto::EncryptingInputStream::``vbtable'{for ``std::basic_istream<char,struct std::char_traits<char> >'}` | 137 | Exported Function
`const Poco::Crypto::EncryptingInputStream::``vftable'` | 122 | Exported Function
`const Poco::Crypto::ECKey::``vftable'` | 121 | Exported Function
`const Poco::Crypto::EncryptingInputStream::``vbtable'{for ``Poco::Crypto::CryptoIOS'}` | 138 | Exported Function
`public: __thiscall Poco::Crypto::CryptoException::CryptoException(int)` | 11 | Exported Function
`public: __thiscall Poco::Crypto::PKCS12Container::PKCS12Container(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 53 | Exported Function
`public: __thiscall Poco::Crypto::PKCS12Container::~PKCS12Container(void)` | 88 | Exported Function
`public: __thiscall Poco::Crypto::PKCS12Container::PKCS12Container(class Poco::Crypto::PKCS12Container const &)` | 52 | Exported Function
`public: __thiscall Poco::Crypto::PKCS12Container::PKCS12Container(class std::basic_istream<char,struct std::char_traits<char> > &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 51 | Exported Function
`public: __thiscall Poco::Crypto::RSAKey::RSAKey(class Poco::Crypto::EVPPKey const &)` | 58 | Exported Function
`public: __thiscall Poco::Crypto::RSAKey::RSAKey(class Poco::Crypto::PKCS12Container const &)` | 59 | Exported Function
`public: __thiscall Poco::Crypto::RSADigestEngine::RSADigestEngine(class Poco::Crypto::RSAKey const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 54 | Exported Function
`public: __thiscall Poco::Crypto::RSADigestEngine::RSADigestEngine(class Poco::Crypto::RSAKey const &,enum Poco::Crypto::RSADigestEngine::DigestType)` | 55 | Exported Function
`public: __thiscall Poco::Crypto::PKCS12Container::PKCS12Container(class Poco::Crypto::PKCS12Container &&)` | 50 | Exported Function
`public: __thiscall Poco::Crypto::OpenSSLException::OpenSSLException(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class Poco::Exception const &,int)` | 46 | Exported Function
`public: __thiscall Poco::Crypto::OpenSSLException::OpenSSLException(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,int)` | 45 | Exported Function
`public: __thiscall Poco::Crypto::KeyPair::KeyPair(class Poco::Crypto::KeyPair const &)` | 42 | Exported Function
`public: __thiscall Poco::Crypto::OpenSSLException::OpenSSLException(class Poco::Crypto::OpenSSLException const &)` | 44 | Exported Function
`public: __thiscall Poco::Crypto::OpenSSLInitializer::OpenSSLInitializer(void)` | 49 | Exported Function
`public: __thiscall Poco::Crypto::OpenSSLInitializer::~OpenSSLInitializer(void)` | 87 | Exported Function
`public: __thiscall Poco::Crypto::OpenSSLException::OpenSSLException(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,int)` | 47 | Exported Function
`public: __thiscall Poco::Crypto::OpenSSLException::OpenSSLException(int)` | 48 | Exported Function
`public: bool __thiscall Poco::Crypto::ECDSADigestEngine::verify(class std::vector<unsigned char,class std::allocator<unsigned char> > const &)` | 270 | Exported Function
`public: bool __thiscall Poco::Crypto::EVPPKey::isSupported(int)const ` | 211 | Exported Function
`public: __thiscall Poco::Crypto::X509Certificate::X509Certificate(struct x509_st *,bool)` | 67 | Exported Function
`public: __thiscall Poco::Crypto::X509Certificate::~X509Certificate(void)` | 91 | Exported Function
`public: bool __thiscall Poco::Crypto::PKCS12Container::hasKey(void)const ` | 200 | Exported Function
`public: bool __thiscall Poco::Crypto::PKCS12Container::hasX509Certificate(void)const ` | 201 | Exported Function
`public: bool __thiscall Poco::Crypto::EVPPKey::operator!=(class Poco::Crypto::EVPPKey const &)const ` | 106 | Exported Function
`public: bool __thiscall Poco::Crypto::EVPPKey::operator==(class Poco::Crypto::EVPPKey const &)const ` | 105 | Exported Function
`public: __thiscall Poco::Crypto::X509Certificate::X509Certificate(struct x509_st *)` | 66 | Exported Function
`public: __thiscall Poco::Crypto::RSAKey::RSAKey(class std::basic_istream<char,struct std::char_traits<char> > *,class std::basic_istream<char,struct std::char_traits<char> > *,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 61 | Exported Function
`public: __thiscall Poco::Crypto::RSAKey::RSAKey(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 57 | Exported Function
`public: __thiscall Poco::Crypto::RSAKey::RSAKey(class Poco::Crypto::RSAKey const &)` | 56 | Exported Function
`public: __thiscall Poco::Crypto::RSAKey::RSAKey(class Poco::Crypto::X509Certificate const &)` | 60 | Exported Function
`public: __thiscall Poco::Crypto::X509Certificate::X509Certificate(class std::basic_istream<char,struct std::char_traits<char> > &)` | 63 | Exported Function
`public: __thiscall Poco::Crypto::X509Certificate::X509Certificate(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 65 | Exported Function
`public: __thiscall Poco::Crypto::RSAKey::RSAKey(enum Poco::Crypto::RSAKey::KeyLength,enum Poco::Crypto::RSAKey::Exponent)` | 62 | Exported Function
`public: __thiscall Poco::Crypto::X509Certificate::X509Certificate(class Poco::Crypto::X509Certificate const &)` | 64 | Exported Function
`public: __thiscall Poco::Crypto::DecryptingOutputStream::DecryptingOutputStream(class std::basic_ostream<char,struct std::char_traits<char> > &,class Poco::Crypto::Cipher &,__int64)` | 23 | Exported Function
`public: __thiscall Poco::Crypto::DigestEngine::DigestEngine(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 24 | Exported Function
`public: __thiscall Poco::Crypto::CryptoTransform::CryptoTransform(void)` | 21 | Exported Function
`public: __thiscall Poco::Crypto::DecryptingInputStream::DecryptingInputStream(class std::basic_istream<char,struct std::char_traits<char> > &,class Poco::Crypto::Cipher &,__int64)` | 22 | Exported Function
`public: __thiscall Poco::Crypto::ECKey::ECKey(class Poco::Crypto::EVPPKey const &)` | 29 | Exported Function
`public: __thiscall Poco::Crypto::ECKey::ECKey(class Poco::Crypto::PKCS12Container const &)` | 30 | Exported Function
`public: __thiscall Poco::Crypto::ECDSADigestEngine::ECDSADigestEngine(class Poco::Crypto::ECKey const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 25 | Exported Function
`public: __thiscall Poco::Crypto::ECKey::ECKey(class Poco::Crypto::ECKey const &)` | 26 | Exported Function
`public: __thiscall Poco::Crypto::CryptoTransform::CryptoTransform(class Poco::Crypto::CryptoTransform const &)` | 20 | Exported Function
`public: __thiscall Poco::Crypto::CryptoIOS::CryptoIOS(class std::basic_istream<char,struct std::char_traits<char> > &,class Poco::Crypto::CryptoTransform *,__int64)` | 12 | Exported Function
`public: __thiscall Poco::Crypto::CryptoIOS::CryptoIOS(class std::basic_ostream<char,struct std::char_traits<char> > &,class Poco::Crypto::CryptoTransform *,__int64)` | 13 | Exported Function
`public: __thiscall Poco::Crypto::CryptoInputStream::CryptoInputStream(class std::basic_istream<char,struct std::char_traits<char> > &,class Poco::Crypto::Cipher &,__int64)` | 14 | Exported Function
`public: __thiscall Poco::Crypto::CryptoInputStream::CryptoInputStream(class std::basic_istream<char,struct std::char_traits<char> > &,class Poco::Crypto::CryptoTransform *,__int64)` | 15 | Exported Function
`public: __thiscall Poco::Crypto::CryptoStreamBuf::CryptoStreamBuf(class std::basic_istream<char,struct std::char_traits<char> > &,class Poco::Crypto::CryptoTransform *,__int64)` | 18 | Exported Function
`public: __thiscall Poco::Crypto::CryptoStreamBuf::CryptoStreamBuf(class std::basic_ostream<char,struct std::char_traits<char> > &,class Poco::Crypto::CryptoTransform *,__int64)` | 19 | Exported Function
`public: __thiscall Poco::Crypto::CryptoOutputStream::CryptoOutputStream(class std::basic_ostream<char,struct std::char_traits<char> > &,class Poco::Crypto::Cipher &,__int64)` | 16 | Exported Function
`public: __thiscall Poco::Crypto::CryptoOutputStream::CryptoOutputStream(class std::basic_ostream<char,struct std::char_traits<char> > &,class Poco::Crypto::CryptoTransform *,__int64)` | 17 | Exported Function
`public: __thiscall Poco::Crypto::EVPPKey::EVPPKey(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 35 | Exported Function
`public: __thiscall Poco::Crypto::EVPPKey::EVPPKey(struct evp_pkey_st *)` | 37 | Exported Function
`public: __thiscall Poco::Crypto::EVPPKey::EVPPKey(class std::basic_istream<char,struct std::char_traits<char> > *,class std::basic_istream<char,struct std::char_traits<char> > *,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 38 | Exported Function
`public: __thiscall Poco::Crypto::EVPPKey::EVPPKey(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 36 | Exported Function
`public: __thiscall Poco::Crypto::EVPPKey::~EVPPKey(void)` | 82 | Exported Function
`public: __thiscall Poco::Crypto::KeyPair::KeyPair(class Poco::AutoPtr<class Poco::Crypto::KeyPairImpl>)` | 43 | Exported Function
`public: __thiscall Poco::Crypto::EVPPKey::operator struct evp_pkey_st *(void)` | 107 | Exported Function
`public: __thiscall Poco::Crypto::EVPPKey::operator struct evp_pkey_st const *(void)const ` | 108 | Exported Function
`public: __thiscall Poco::Crypto::EVPPKey::EVPPKey(class Poco::Crypto::EVPPKey const &)` | 34 | Exported Function
`public: __thiscall Poco::Crypto::ECKey::ECKey(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 28 | Exported Function
`public: __thiscall Poco::Crypto::ECKey::ECKey(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 27 | Exported Function
`public: __thiscall Poco::Crypto::ECKey::ECKey(class Poco::Crypto::X509Certificate const &)` | 31 | Exported Function
`public: __thiscall Poco::Crypto::ECKey::ECKey(class std::basic_istream<char,struct std::char_traits<char> > *,class std::basic_istream<char,struct std::char_traits<char> > *,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 32 | Exported Function
`public: __thiscall Poco::Crypto::EVPPKey::EVPPKey(char const *)` | 39 | Exported Function
`public: __thiscall Poco::Crypto::EVPPKey::EVPPKey(class Poco::Crypto::EVPPKey &&)` | 33 | Exported Function
`public: __thiscall Poco::Crypto::EncryptingInputStream::EncryptingInputStream(class std::basic_istream<char,struct std::char_traits<char> > &,class Poco::Crypto::Cipher &,__int64)` | 40 | Exported Function
`public: __thiscall Poco::Crypto::EncryptingOutputStream::EncryptingOutputStream(class std::basic_ostream<char,struct std::char_traits<char> > &,class Poco::Crypto::Cipher &,__int64)` | 41 | Exported Function


## Signature

* Status: The file C:\Program Files (x86)\Sennheiser\SenncomSDK\PocoCrypto.dll is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at https:/go.microsoft.com/fwlink/?LinkID=135170
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

* VirusTotal Detections: 0/67
* VirusTotal Link: https://www.virustotal.com/gui/file/8e22013214c17342efc7eebb9e10ff07e4ed286eba642bdd8c21a8da13e6591a/detection/




MIT License. Copyright (c) 2020 Strontic.


