---
title: csflogger.dll | 
excerpt: What is csflogger.dll?
---

# csflogger.dll 

* File Path: `C:\Program Files (x86)\Cisco Systems\Cisco Jabber\csflogger.dll`

## Hashes

Type | Hash
-- | --
MD5 | `B39E1E33535E627BECEEA71B4BDB085A`
SHA1 | `54A19374E0B2199A11C45AB56BCEB45549331876`
SHA256 | `FE5549A1B4060CF6F596D1EA41DD70B31860506EC52CA765193013FE7F599D14`
SHA384 | `236078A9650E6A75A5E9A2233A6BFB027CF3BC7C5498254B2BCB748A341A5B608F41DB217E420946F0CC203436F08B33`
SHA512 | `0DA63782E0F76DF215BF469C26E7D9DF0B2C871B8F3481C7B4831B1E0C7ADB952BB21C5FD3CD3ABFD6277F9CE42FBE9FFCA7D831C26637085E292D27134E91D3`
SSDEEP | `3072:oXIJTZRmwqR+q+aQLhiZWy7sInf06bixg2Y+gljnNkp:oYTRZZehbixQ+gljN+`
IMP | `FDCD44D6811176F7175657F65F070618`
PESHA1 | `D797B2D2265ADD8F4E268E1AD746799B0F60F020`
PE256 | `CAE88CA953A87215E9A5374B1ED505F4392AE6A03C1160E0824F23FFA887C582`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`public: virtual bool __thiscall CSF::csflogger::FileSystem::openOverwrite(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 139 | Exported Function
`public: virtual bool __thiscall CSF::csflogger::FileSystem::open(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 138 | Exported Function
`public: virtual bool __thiscall CSF::csflogger::FileSystem::renameFile(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 141 | Exported Function
`public: virtual bool __thiscall CSF::csflogger::LogController::getPIIDataHashEnablement(void)` | 132 | Exported Function
`public: virtual bool __thiscall CSF::csflogger::LogController::getFileWritingAllowed(void)` | 124 | Exported Function
`public: virtual bool __thiscall CSF::csflogger::FileSystem::deleteFile(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 100 | Exported Function
`public: virtual __thiscall CSF::csflogger::LogController::~LogController(void)` | 44 | Exported Function
`public: virtual __thiscall CSF::csflogger::FileSystemProvider::~FileSystemProvider(void)` | 43 | Exported Function
`public: virtual __thiscall CSF::csflogger::NSLogAppender::~NSLogAppender(void)` | 46 | Exported Function
`public: virtual bool __thiscall CSF::csflogger::Configuration::getFileWritingAllowed(void)` | 123 | Exported Function
`public: virtual __thiscall CSF::csflogger::Rollover::~Rollover(void)` | 47 | Exported Function
`public: virtual class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __thiscall CSF::csflogger::Configuration::getBeginSentinel(void)` | 115 | Exported Function
`public: virtual class std::shared_ptr<class CSF::csflogger::FileSystem> __thiscall CSF::csflogger::FileSystemProvider::getFileSystem(void)` | 122 | Exported Function
`public: virtual class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __thiscall CSF::csflogger::LogController::getLogDirectory(void)` | 128 | Exported Function
`public: virtual unsigned int __thiscall CSF::csflogger::Configuration::getBufferSize(void)` | 117 | Exported Function
`public: virtual unsigned int __thiscall CSF::csflogger::Configuration::getMaxNumberOfFiles(void)` | 131 | Exported Function
`public: virtual unsigned int __thiscall CSF::csflogger::Configuration::getMaxFileSize(void)` | 130 | Exported Function
`public: virtual class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __thiscall CSF::csflogger::FileSystem::getLastError(void)` | 127 | Exported Function
`public: virtual class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __thiscall CSF::csflogger::Configuration::getEndSentinel(void)` | 119 | Exported Function
`public: virtual class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __thiscall CSF::csflogger::Configuration::getDirectory(void)` | 118 | Exported Function
`public: virtual class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __thiscall CSF::csflogger::Configuration::getFileName(void)` | 120 | Exported Function
`public: virtual class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __thiscall CSF::csflogger::DefaultFormatter::formatMessage(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,enum CSFLogLevel,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,int,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 112 | Exported Function
`public: virtual class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __thiscall CSF::csflogger::Configuration::getFullPathFileName(void)` | 126 | Exported Function
`public: static class std::shared_ptr<class CSF::csflogger::LogController> __cdecl CSF::csflogger::LogController::GetInstance(void)` | 87 | Exported Function
`public: static class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __cdecl CSF::csflogger::StringUtils::generateHashBasedOnSHA256(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 113 | Exported Function
`public: static class std::vector<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> >,class std::allocator<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > > > __cdecl CSF::csflogger::FileUtils::getFilesWithSubStr(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> >,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 125 | Exported Function
`public: static void __cdecl CSF::csflogger::FileUtils::deleteMatchingLogs(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 105 | Exported Function
`public: static void __cdecl CSF::csflogger::FileUtils::deleteLogs(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 102 | Exported Function
`public: static class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __cdecl CSF::csflogger::FileUtils::getWritablePath(void)` | 133 | Exported Function
`public: int __thiscall csf::csflogger::ScopedLock::unlock(void)` | 162 | Exported Function
`public: int __thiscall csf::csflogger::Mutex::unlock(void)` | 161 | Exported Function
`public: static bool __cdecl CSF::csflogger::FileUtils::createDirectory(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 98 | Exported Function
`public: static class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __cdecl CSF::csflogger::FileUtils::FileSeparator(void)` | 86 | Exported Function
`public: static bool __cdecl CSF::csflogger::FileUtils::fileExists(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 107 | Exported Function
`public: static void __cdecl CSF::csflogger::FileUtils::removeDirectory(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 140 | Exported Function
`public: virtual __thiscall CSF::csflogger::ConsoleLogAppender::~ConsoleLogAppender(void)` | 39 | Exported Function
`public: virtual __thiscall CSF::csflogger::Configuration::~Configuration(void)` | 38 | Exported Function
`public: virtual __thiscall CSF::csflogger::DefaultFormatter::~DefaultFormatter(void)` | 40 | Exported Function
`public: virtual __thiscall CSF::csflogger::FileSystem::~FileSystem(void)` | 42 | Exported Function
`public: virtual __thiscall CSF::csflogger::FileAppender::~FileAppender(void)` | 41 | Exported Function
`public: virtual __thiscall CSF::csflogger::BufferedAppender::~BufferedAppender(void)` | 36 | Exported Function
`public: struct CSFLogger & __thiscall CSFLogger::operator=(struct CSFLogger &&)` | 52 | Exported Function
`public: static void __cdecl CSF::csflogger::LogController::ResetInstance(void)` | 88 | Exported Function
`public: struct CSFLogger & __thiscall CSFLogger::operator=(struct CSFLogger const &)` | 53 | Exported Function
`public: virtual __thiscall CSF::csflogger::BasicFileAppender::~BasicFileAppender(void)` | 35 | Exported Function
`public: virtual __int64 __thiscall CSF::csflogger::FileSystem::getFileSize(void)` | 121 | Exported Function
`public: virtual void __thiscall CSF::csflogger::LogController::setPIIDataHashEnablement(bool)` | 153 | Exported Function
`public: virtual void __thiscall CSF::csflogger::LogController::setMaxNumberOfFiles(unsigned int)` | 152 | Exported Function
`public: virtual void __thiscall CSF::csflogger::LogController::setThreadIdHandler(void (__cdecl*)(char *))` | 159 | Exported Function
`public: virtual void __thiscall CSF::csflogger::NSLogAppender::setThreadIdHandler(void (__cdecl*)(char *))` | 160 | Exported Function
`public: virtual void __thiscall CSF::csflogger::NSLogAppender::append(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,enum CSFLogLevel,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,int,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 93 | Exported Function
`public: virtual void __thiscall CSF::csflogger::LogController::setLogLevel(enum CSFLogLevel)` | 150 | Exported Function
`public: virtual void __thiscall CSF::csflogger::LogController::setAppenderType(enum CSF::csflogger::LogAppenderType)` | 143 | Exported Function
`public: virtual void __thiscall CSF::csflogger::LogController::log(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,enum CSFLogLevel,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,int,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 137 | Exported Function
`public: virtual void __thiscall CSF::csflogger::LogController::setBufferSize(unsigned int)` | 145 | Exported Function
`public: virtual void __thiscall CSF::csflogger::LogController::setFileWritingAllowed(bool)` | 148 | Exported Function
`public: virtual void __thiscall CSF::csflogger::LogController::setCanDeleteLogs(bool)` | 146 | Exported Function
`public: void __thiscall CSF::csflogger::BufferedAppender::appendToBuffer(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 94 | Exported Function
`public: void __thiscall CSF::csflogger::Rollover::write(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,unsigned int,unsigned int)` | 166 | Exported Function
`public: void __thiscall CSF::csflogger::Rollover::write(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 165 | Exported Function
`void __cdecl CSFLog(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> >,enum CSFLogLevel,char const *,int,char const *,class std::basic_string<wchar_t,struct std::char_traits<wchar_t>,class std::allocator<wchar_t> > const &)` | 83 | Exported Function
`void __cdecl CSFLog(struct CSFLogger *,enum CSFLogLevel,char const *,int,char const *,class std::basic_string<wchar_t,struct std::char_traits<wchar_t>,class std::allocator<wchar_t> > const &)` | 82 | Exported Function
`void __cdecl CSFLog(struct CSFLogger *,enum CSFLogLevel,char const *,int,char const *,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 81 | Exported Function
`public: void __thiscall CSF::csflogger::LogController::setAppender(class std::shared_ptr<class CSF::csflogger::LogAppender>)` | 142 | Exported Function
`public: void __thiscall CSF::csflogger::BufferedAppender::flushBuffer(void)` | 110 | Exported Function
`public: void __thiscall CSF::csflogger::BufferedAppender::clearBuffer(void)` | 95 | Exported Function
`public: void __thiscall CSF::csflogger::BufferedAppender::getBuffer(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > &)` | 116 | Exported Function
`public: void __thiscall CSF::csflogger::Configuration::setMaxNumberOfFiles(unsigned int)` | 151 | Exported Function
`public: void __thiscall CSF::csflogger::Configuration::setBufferSize(unsigned int)` | 144 | Exported Function
`public: virtual void __thiscall CSF::csflogger::ConsoleLogAppender::setThreadIdHandler(void (__cdecl*)(char *))` | 156 | Exported Function
`public: virtual void __thiscall CSF::csflogger::ConsoleLogAppender::append(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,enum CSFLogLevel,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,int,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 91 | Exported Function
`public: virtual void __thiscall CSF::csflogger::DefaultFormatter::setThreadIdHandler(void (__cdecl*)(char *))` | 157 | Exported Function
`public: virtual void __thiscall CSF::csflogger::FileAppender::setThreadIdHandler(void (__cdecl*)(char *))` | 158 | Exported Function
`public: virtual void __thiscall CSF::csflogger::FileAppender::append(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,enum CSFLogLevel,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,int,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 92 | Exported Function
`public: virtual void __thiscall CSF::csflogger::Configuration::setFullPathFileName(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> >)` | 149 | Exported Function
`public: virtual void __thiscall CSF::csflogger::BasicFileAppender::setThreadIdHandler(void (__cdecl*)(char *))` | 154 | Exported Function
`public: virtual void __thiscall CSF::csflogger::BasicFileAppender::append(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,enum CSFLogLevel,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,int,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 89 | Exported Function
`public: virtual void __thiscall CSF::csflogger::BufferedAppender::append(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,enum CSFLogLevel,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,int,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 90 | Exported Function
`public: virtual void __thiscall CSF::csflogger::Configuration::setFileWritingAllowed(bool)` | 147 | Exported Function
`public: virtual void __thiscall CSF::csflogger::BufferedAppender::setThreadIdHandler(void (__cdecl*)(char *))` | 155 | Exported Function
`public: virtual void __thiscall CSF::csflogger::FileSystem::close(void)` | 97 | Exported Function
`public: virtual void __thiscall CSF::csflogger::LogController::deleteMatchingLogs(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> >)` | 106 | Exported Function
`public: virtual void __thiscall CSF::csflogger::LogController::deleteLogsIfWritingNotAllowed(void)` | 104 | Exported Function
`public: virtual void __thiscall CSF::csflogger::LogController::flush(void)` | 109 | Exported Function
`public: virtual void __thiscall CSF::csflogger::LogController::init(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> >)` | 134 | Exported Function
`public: virtual void __thiscall CSF::csflogger::LogController::flushBufferIfAllowed(void)` | 111 | Exported Function
`public: virtual void __thiscall CSF::csflogger::LogController::deleteLogs(void)` | 103 | Exported Function
`public: virtual void __thiscall CSF::csflogger::FileSystem::flush(void)` | 108 | Exported Function
`public: virtual void __thiscall CSF::csflogger::FileSystem::deleteLogs(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 101 | Exported Function
`public: virtual void __thiscall CSF::csflogger::FileSystem::write(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 163 | Exported Function
`public: virtual void __thiscall CSF::csflogger::LogController::clearThreadIdHandler(void)` | 96 | Exported Function
`public: virtual void __thiscall CSF::csflogger::FileSystem::write(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,unsigned int,unsigned int)` | 164 | Exported Function
`CSFLogLevel_toString` | 168 | Exported Function
`CSFLogger_SetThreadIdHandler` | 174 | Exported Function
`CSFLogV` | 169 | Exported Function
`private: static class std::shared_ptr<class CSF::csflogger::LogController> CSF::csflogger::LogController::instance` | 135 | Exported Function
`private: static bool __cdecl CSF::csflogger::FileUtils::createDirectoryStructure(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 99 | Exported Function
`CSFLogger_setLogLevel` | 184 | Exported Function
`CSFLogger_getRootLogger` | 180 | Exported Function
`CSFLogger_getName` | 179 | Exported Function
`CSFLogger_init` | 181 | Exported Function
`CSFLogger_setGlobalLogLevel` | 183 | Exported Function
`CSFLogger_initialize` | 182 | Exported Function
`public: __thiscall CSF::csflogger::BasicFileAppender::BasicFileAppender(class CSF::csflogger::BasicFileAppender const &)` | 1 | Exported Function
`public: __thiscall CSF::csflogger::ConsoleLogAppender::ConsoleLogAppender(class std::shared_ptr<class CSF::csflogger::Configuration>,class std::shared_ptr<class CSF::csflogger::FileSystem>)` | 12 | Exported Function
`public: __thiscall CSF::csflogger::ConsoleLogAppender::ConsoleLogAppender(class CSF::csflogger::ConsoleLogAppender const &)` | 11 | Exported Function
`public: __thiscall CSF::csflogger::DefaultFormatter::DefaultFormatter(class CSF::csflogger::DefaultFormatter const &)` | 13 | Exported Function
`public: __thiscall CSF::csflogger::FileAppender::FileAppender(class CSF::csflogger::FileAppender const &)` | 15 | Exported Function
`public: __thiscall CSF::csflogger::DefaultFormatter::DefaultFormatter(void)` | 14 | Exported Function
`public: __thiscall CSF::csflogger::Configuration::Configuration(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> >,unsigned int,unsigned int,unsigned int,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> >,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> >)` | 10 | Exported Function
`public: __thiscall CSF::csflogger::BufferedAppender::BufferedAppender(class CSF::csflogger::BufferedAppender const &)` | 3 | Exported Function
`public: __thiscall CSF::csflogger::BasicFileAppender::BasicFileAppender(class std::shared_ptr<class CSF::csflogger::FileSystem>)` | 2 | Exported Function
`public: __thiscall CSF::csflogger::BufferedAppender::BufferedAppender(class std::shared_ptr<class CSF::csflogger::Configuration>,class std::shared_ptr<class CSF::csflogger::FileSystem>)` | 4 | Exported Function
`public: __thiscall CSF::csflogger::Configuration::Configuration(class CSF::csflogger::Configuration const &)` | 9 | Exported Function
`public: __thiscall CSF::csflogger::BufferedAppender::BufferedAppender(class std::shared_ptr<class CSF::csflogger::Configuration>,class std::shared_ptr<class CSF::csflogger::FileSystem>,class std::shared_ptr<class CSF::csflogger::Formatter>)` | 5 | Exported Function
`const CSF::csflogger::FileAppender::``vftable'` | 74 | Exported Function
`const CSF::csflogger::DefaultFormatter::``vftable'` | 73 | Exported Function
`const CSF::csflogger::FileSystem::``vftable'` | 75 | Exported Function
`const CSF::csflogger::LogAppender::``vftable'` | 77 | Exported Function
`const CSF::csflogger::FileSystemProvider::``vftable'` | 76 | Exported Function
`const CSF::csflogger::ConsoleLogAppender::``vftable'` | 72 | Exported Function
`class std::map<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> >,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> >,struct std::less<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > >,class std::allocator<struct std::pair<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const ,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > > > > __cdecl CSFLogger_getPIIDataList(void)` | 84 | Exported Function
`class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __cdecl CSFLogger_replacePIIData(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> >)` | 85 | Exported Function
`const CSF::csflogger::BasicFileAppender::``vftable'` | 69 | Exported Function
`const CSF::csflogger::Configuration::``vftable'` | 71 | Exported Function
`const CSF::csflogger::BufferedAppender::``vftable'` | 70 | Exported Function
`const CSF::csflogger::LogController::``vftable'` | 78 | Exported Function
`CSFLogger_flush` | 175 | Exported Function
`CSFLog_isTraceEnabled` | 173 | Exported Function
`CSFLogger_getGlobalLogLevel` | 176 | Exported Function
`CSFLogger_getLogLevel` | 177 | Exported Function
`CSFLogger_getLogger` | 178 | Exported Function
`CSFLog_isLogLevel` | 172 | Exported Function
`const CSF::csflogger::Rollover::``vftable'` | 80 | Exported Function
`const CSF::csflogger::NSLogAppender::``vftable'` | 79 | Exported Function
`CSFLog` | 167 | Exported Function
`CSFLog_isDebugEnabled` | 171 | Exported Function
`CSFLog_getCSFLogger` | 170 | Exported Function
`public: class CSF::csflogger::DefaultFormatter & __thiscall CSF::csflogger::DefaultFormatter::operator=(class CSF::csflogger::DefaultFormatter const &)` | 56 | Exported Function
`public: class CSF::csflogger::ConsoleLogAppender & __thiscall CSF::csflogger::ConsoleLogAppender::operator=(class CSF::csflogger::ConsoleLogAppender const &)` | 55 | Exported Function
`public: class CSF::csflogger::FileAppender & __thiscall CSF::csflogger::FileAppender::operator=(class CSF::csflogger::FileAppender const &)` | 57 | Exported Function
`public: class CSF::csflogger::FileSystemProvider & __thiscall CSF::csflogger::FileSystemProvider::operator=(class CSF::csflogger::FileSystemProvider const &)` | 59 | Exported Function
`public: class CSF::csflogger::FileSystem & __thiscall CSF::csflogger::FileSystem::operator=(class CSF::csflogger::FileSystem const &)` | 58 | Exported Function
`public: class CSF::csflogger::Configuration & __thiscall CSF::csflogger::Configuration::operator=(class CSF::csflogger::Configuration const &)` | 54 | Exported Function
`public: __thiscall CSFLogger::CSFLogger(void)` | 8 | Exported Function
`public: __thiscall CSFLogger::CSFLogger(struct CSFLogger const &)` | 7 | Exported Function
`public: __thiscall CSFLogger::~CSFLogger(void)` | 37 | Exported Function
`public: class CSF::csflogger::BufferedAppender & __thiscall CSF::csflogger::BufferedAppender::operator=(class CSF::csflogger::BufferedAppender const &)` | 51 | Exported Function
`public: class CSF::csflogger::BasicFileAppender & __thiscall CSF::csflogger::BasicFileAppender::operator=(class CSF::csflogger::BasicFileAppender const &)` | 50 | Exported Function
`public: class CSF::csflogger::FileUtils & __thiscall CSF::csflogger::FileUtils::operator=(class CSF::csflogger::FileUtils &&)` | 60 | Exported Function
`public: class CSF::csflogger::StringUtils & __thiscall CSF::csflogger::StringUtils::operator=(class CSF::csflogger::StringUtils const &)` | 68 | Exported Function
`public: class CSF::csflogger::StringUtils & __thiscall CSF::csflogger::StringUtils::operator=(class CSF::csflogger::StringUtils &&)` | 67 | Exported Function
`public: class std::shared_ptr<class CSF::csflogger::LogAppender> __thiscall CSF::csflogger::LogController::getAppender(void)` | 114 | Exported Function
`public: int __thiscall csf::csflogger::Mutex::lock(void)` | 136 | Exported Function
`public: enum CSFLogLevel __thiscall CSF::csflogger::LogController::getLogLevel(void)` | 129 | Exported Function
`public: class CSF::csflogger::Rollover & __thiscall CSF::csflogger::Rollover::operator=(class CSF::csflogger::Rollover const &)` | 66 | Exported Function
`public: class CSF::csflogger::LogAppender & __thiscall CSF::csflogger::LogAppender::operator=(class CSF::csflogger::LogAppender &&)` | 62 | Exported Function
`public: class CSF::csflogger::FileUtils & __thiscall CSF::csflogger::FileUtils::operator=(class CSF::csflogger::FileUtils const &)` | 61 | Exported Function
`public: class CSF::csflogger::LogAppender & __thiscall CSF::csflogger::LogAppender::operator=(class CSF::csflogger::LogAppender const &)` | 63 | Exported Function
`public: class CSF::csflogger::NSLogAppender & __thiscall CSF::csflogger::NSLogAppender::operator=(class CSF::csflogger::NSLogAppender const &)` | 65 | Exported Function
`public: class CSF::csflogger::LogController & __thiscall CSF::csflogger::LogController::operator=(class CSF::csflogger::LogController const &)` | 64 | Exported Function
`public: __thiscall CSF::csflogger::LogAppender::LogAppender(void)` | 23 | Exported Function
`public: __thiscall CSF::csflogger::LogAppender::LogAppender(class CSF::csflogger::LogAppender const &)` | 22 | Exported Function
`public: __thiscall CSF::csflogger::LogController::LogController(class CSF::csflogger::LogController const &)` | 24 | Exported Function
`public: __thiscall CSF::csflogger::LogController::LogController(class std::shared_ptr<class CSF::csflogger::FileSystemProvider>,enum CSF::csflogger::LogAppenderType)` | 26 | Exported Function
`public: __thiscall CSF::csflogger::LogController::LogController(class std::shared_ptr<class CSF::csflogger::Configuration>)` | 25 | Exported Function
`public: __thiscall CSF::csflogger::LogAppender::LogAppender(class CSF::csflogger::LogAppender &&)` | 21 | Exported Function
`public: __thiscall CSF::csflogger::FileSystem::FileSystem(class CSF::csflogger::FileSystem const &)` | 17 | Exported Function
`public: __thiscall CSF::csflogger::FileAppender::FileAppender(class std::shared_ptr<class CSF::csflogger::Configuration>,class std::shared_ptr<class CSF::csflogger::FileSystem>)` | 16 | Exported Function
`public: __thiscall CSF::csflogger::FileSystem::FileSystem(void)` | 18 | Exported Function
`public: __thiscall CSF::csflogger::FileSystemProvider::FileSystemProvider(void)` | 20 | Exported Function
`public: __thiscall CSF::csflogger::FileSystemProvider::FileSystemProvider(class CSF::csflogger::FileSystemProvider const &)` | 19 | Exported Function
`public: __thiscall CSF::csflogger::LogController::LogController(void)` | 27 | Exported Function
`public: __thiscall csf::csflogger::ScopedLock::~ScopedLock(void)` | 48 | Exported Function
`public: __thiscall csf::csflogger::ScopedLock::ScopedLock(class csf::csflogger::Mutex &)` | 33 | Exported Function
`public: __thiscall csf::csflogger::ScopedUnlock::ScopedUnlock(class csf::csflogger::Mutex &)` | 34 | Exported Function
`public: __thiscall CSFLogger::CSFLogger(struct CSFLogger &&)` | 6 | Exported Function
`public: __thiscall csf::csflogger::ScopedUnlock::~ScopedUnlock(void)` | 49 | Exported Function
`public: __thiscall CSF::csflogger::Rollover::Rollover(class std::shared_ptr<class CSF::csflogger::Configuration>,class std::shared_ptr<class CSF::csflogger::FileSystem>,class std::shared_ptr<class CSF::csflogger::Formatter>,bool)` | 32 | Exported Function
`public: __thiscall csf::csflogger::Mutex::~Mutex(void)` | 45 | Exported Function
`public: __thiscall csf::csflogger::Mutex::Mutex(void)` | 28 | Exported Function
`public: __thiscall CSF::csflogger::NSLogAppender::NSLogAppender(class CSF::csflogger::NSLogAppender const &)` | 29 | Exported Function
`public: __thiscall CSF::csflogger::Rollover::Rollover(class CSF::csflogger::Rollover const &)` | 31 | Exported Function
`public: __thiscall CSF::csflogger::NSLogAppender::NSLogAppender(class std::shared_ptr<class CSF::csflogger::Configuration>,class std::shared_ptr<class CSF::csflogger::FileSystem>)` | 30 | Exported Function


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

* VirusTotal Detections: 0/69
* VirusTotal Link: https://www.virustotal.com/gui/file/fe5549a1b4060cf6f596d1ea41dd70b31860506ec52ca765193013fe7f599d14/detection/




MIT License. Copyright (c) 2020 Strontic.


