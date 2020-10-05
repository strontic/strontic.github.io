---
title: libaudiopairing.dll | 
excerpt: What is libaudiopairing.dll?
---

# libaudiopairing.dll 

* File Path: `C:\Program Files (x86)\Cisco Systems\Cisco Jabber\libaudiopairing.dll`

## Hashes

Type | Hash
-- | --
MD5 | `B204D62E9D4D783EEF693627687D22C2`
SHA1 | `1406AEC7E68A6BF225EC9FA722A6550D395BC65D`
SHA256 | `65DAEEE394CED81E33A8451CB42CA67B817286B151B8999494017E6372C4529A`
SHA384 | `E919A0B3ACBC367540FF766E1296FAACF0AB4E2229DE5A6360BD31BBE3F76C2878C01B4C324CEF84FC2AF39E5A1228B4`
SHA512 | `2AF04924C1C3A20D8E8D390A063C003C3A53E3290640740BB1B02747DDE0A2A278A340AD6791421DCCD6F500F62FAF0F08DD78D79CE9FCD7A044C0546224DB22`
SSDEEP | `24576:jDq5w2xTTmnryp9GiIv9lm6rjNC8j06Dw78vF:XqB5mnryp9GiIv9lmUNvF`
IMP | `B4BDADD280BEEB920BBED744580D048C`
PESHA1 | `54CEF6479D863CE33334340853D33867318A9357`
PE256 | `8B092AD66FAACEC8789B064E8836D92FC77403C0C77A97ACC79FD1720E849207`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`public: int __thiscall AudioAnalyzer::get_offset_adjustment(void)const ` | 57 | Exported Function
`public: int __thiscall MessageRetainer::messageLength(void)const ` | 63 | Exported Function
`public: float __thiscall AudioMessageReader::getUltrasoundSignalLevel(void)const ` | 54 | Exported Function
`public: float __thiscall AudioAnalyzer::get_ultrasound_signal_level(void)const ` | 59 | Exported Function
`public: float __thiscall AudioMessageReader::getUltrasoundNoiseLevel(void)const ` | 53 | Exported Function
`public: struct ReceptionInfo & __thiscall ReceptionInfo::operator=(struct ReceptionInfo const &)` | 31 | Exported Function
`public: struct ReceptionInfo __thiscall MessageRetainer::reception_info(void)const ` | 68 | Exported Function
`public: struct ReceptionInfo & __thiscall ReceptionInfo::operator=(struct ReceptionInfo &&)` | 30 | Exported Function
`public: struct AudioParams & __thiscall AudioParams::operator=(struct AudioParams &&)` | 24 | Exported Function
`public: struct AudioParams & __thiscall AudioParams::operator=(struct AudioParams const &)` | 25 | Exported Function
`public: float __thiscall AudioAnalyzer::get_ultrasound_noise_level(void)const ` | 58 | Exported Function
`public: bool __thiscall AudioAnalyzer::is_data_ready(void)const ` | 61 | Exported Function
`public: bool __thiscall MessageRetainer::get_and_reset_message_flag(void)` | 55 | Exported Function
`public: __thiscall RingBuffer::~RingBuffer(void)` | 23 | Exported Function
`public: __thiscall MessageRetainer::MessageRetainer(void)` | 16 | Exported Function
`public: __thiscall RingBuffer::RingBuffer(unsigned int)` | 17 | Exported Function
`public: class MessageRetainer & __thiscall MessageRetainer::operator=(class MessageRetainer const &)` | 29 | Exported Function
`public: float __thiscall AudioAnalyzer::get_bit_in_band(int)const ` | 56 | Exported Function
`public: class MessageRetainer & __thiscall MessageRetainer::operator=(class MessageRetainer &&)` | 28 | Exported Function
`public: class MessageListener & __thiscall MessageListener::operator=(class MessageListener const &)` | 26 | Exported Function
`public: class MessageReceiver & __thiscall MessageReceiver::operator=(class MessageReceiver const &)` | 27 | Exported Function
`public: unsigned char const * __thiscall MessageRetainer::message(void)const ` | 62 | Exported Function
`public: void __thiscall AudioParams::``default constructor closure'(void)` | 37 | Exported Function
`public: void __thiscall MessageAssembler::addBit(float)` | 43 | Exported Function
`public: void __thiscall AudioMessageReader::setErrorCorrection(int)` | 72 | Exported Function
`public: void __thiscall AudioAnalyzer::reset(void)` | 69 | Exported Function
`public: void __thiscall AudioMessageReader::receiveAudioData(void const *,unsigned int)` | 67 | Exported Function
`public: void __thiscall RingBuffer::peak(char *,unsigned int)const ` | 66 | Exported Function
`public: void __thiscall RingBuffer::write(char const *,unsigned int)` | 81 | Exported Function
`public: void __thiscall RingBuffer::advance(unsigned int)` | 44 | Exported Function
`public: void __thiscall MessageAssembler::setBitFlips(int)` | 71 | Exported Function
`public: void __thiscall MessageAssembler::symbolAdded(void)` | 76 | Exported Function
`public: void __thiscall AudioAnalyzer::analyze(float *)` | 45 | Exported Function
`public: virtual __thiscall AudioAnalyzer::~AudioAnalyzer(void)` | 18 | Exported Function
`public: virtual __thiscall AudioMessageReader::~AudioMessageReader(void)` | 19 | Exported Function
`public: unsigned int __thiscall RingBuffer::size(void)const ` | 73 | Exported Function
`public: unsigned int __thiscall MessageAssembler::getBitsSinceLastMessage(void)` | 51 | Exported Function
`public: unsigned int __thiscall MessageAssembler::getErrorCorrectionCount(void)` | 52 | Exported Function
`public: virtual void __thiscall AudioMessageReader::onMessage(unsigned char const *,int)` | 64 | Exported Function
`public: virtual void __thiscall MessageRetainer::onMessage(unsigned char const *,int,struct ReceptionInfo)` | 65 | Exported Function
`public: virtual __thiscall MessageRetainer::~MessageRetainer(void)` | 22 | Exported Function
`public: virtual __thiscall MessageListener::~MessageListener(void)` | 20 | Exported Function
`public: virtual __thiscall MessageReceiver::~MessageReceiver(void)` | 21 | Exported Function
`public: __thiscall MessageRetainer::MessageRetainer(class MessageRetainer const &)` | 15 | Exported Function
`private: static int const AudioAnalyzer::fft_length` | 49 | Exported Function
`private: static int const AudioAnalyzer::MAX_OFFSET_ADJUSTMENT` | 39 | Exported Function
`private: int __thiscall MessageAssembler::compareBits(int,int)` | 46 | Exported Function
`private: bool __thiscall MessageAssembler::testBitArrayForMessage(float *)` | 77 | Exported Function
`private: float __thiscall AudioAnalyzer::energy(float *,int)` | 47 | Exported Function
`private: static unsigned int const MessageAssembler::MESSAGE_BYTE_LEN` | 41 | Exported Function
`private: static unsigned int const MessageAssembler::MESSAGE_SYMBOL_LEN` | 42 | Exported Function
`private: static unsigned int const MessageAssembler::MESSAGE_BIT_LEN` | 40 | Exported Function
`private: static int const AudioAnalyzer::subBandFftWidth` | 75 | Exported Function
`private: static unsigned int const MessageAssembler::BITS_PER_SYMBOL` | 38 | Exported Function
`fft_fftReal512SparseProcess` | 87 | Exported Function
`const MessageListener::``vftable'` | 34 | Exported Function
`const MessageReceiver::``vftable'` | 35 | Exported Function
`const AudioMessageReader::``vftable'` | 33 | Exported Function
`_crc32` | 82 | Exported Function
`const AudioAnalyzer::``vftable'` | 32 | Exported Function
`crc32_is_valid` | 85 | Exported Function
`fft_fftReal512Process` | 86 | Exported Function
`crc16_is_valid` | 84 | Exported Function
`const MessageRetainer::``vftable'` | 36 | Exported Function
`crc16` | 83 | Exported Function
`private: void __thiscall AudioAnalyzer::fade(float *)` | 48 | Exported Function
`public: __thiscall MessageAssembler::MessageAssembler(class MessageAssembler &&)` | 8 | Exported Function
`public: __thiscall MessageAssembler::MessageAssembler(class MessageListener *,int,float)` | 9 | Exported Function
`public: __thiscall AudioParams::AudioParams(struct AudioParams &&)` | 6 | Exported Function
`public: __thiscall AudioMessageReader::AudioMessageReader(class MessageReceiver *,struct AudioParams const &)` | 5 | Exported Function
`public: __thiscall AudioParams::AudioParams(float)` | 7 | Exported Function
`public: __thiscall MessageReceiver::MessageReceiver(void)` | 13 | Exported Function
`public: __thiscall MessageRetainer::MessageRetainer(class MessageRetainer &&)` | 14 | Exported Function
`public: __thiscall MessageReceiver::MessageReceiver(class MessageReceiver const &)` | 12 | Exported Function
`public: __thiscall MessageListener::MessageListener(class MessageListener const &)` | 10 | Exported Function
`public: __thiscall MessageListener::MessageListener(void)` | 11 | Exported Function
`public: __thiscall AudioMessageReader::AudioMessageReader(class MessageReceiver *)` | 4 | Exported Function
`private: void __thiscall AudioMessageReader::init(struct AudioParams const &)` | 60 | Exported Function
`private: void __thiscall MessageAssembler::flipBits(int,int)` | 50 | Exported Function
`private: void __thiscall AudioAnalyzer::updateSignalStrength(void)` | 80 | Exported Function
`private: void __thiscall AudioAnalyzer::selectPrimaryLane(void)` | 70 | Exported Function
`private: void __thiscall AudioAnalyzer::updateOffsetAdjustment(void)` | 79 | Exported Function
`public: __thiscall AudioAnalyzer::AudioAnalyzer(struct AudioParams const &)` | 1 | Exported Function
`public: __thiscall AudioMessageReader::AudioMessageReader(class AudioMessageReader const &)` | 3 | Exported Function
`public: __thiscall AudioAnalyzer::AudioAnalyzer(class AudioAnalyzer const &)` | 2 | Exported Function
`private: void __thiscall MessageAssembler::sortIndexes(void)` | 74 | Exported Function
`private: void __thiscall MessageAssembler::testForMessage(void)` | 78 | Exported Function


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
* VirusTotal Link: https://www.virustotal.com/gui/file/65daeee394ced81e33a8451cb42ca67b817286b151b8999494017e6372c4529a/detection/




MIT License. Copyright (c) 2020 Strontic.


