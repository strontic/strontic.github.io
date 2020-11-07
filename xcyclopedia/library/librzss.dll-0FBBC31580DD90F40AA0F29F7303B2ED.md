---
title: librzss.dll | 
excerpt: What is librzss.dll?
---

# librzss.dll 

* File Path: `C:\Program Files (x86)\Cisco Systems\Cisco Jabber\librzss.dll`

## Hashes

Type | Hash
-- | --
MD5 | `0FBBC31580DD90F40AA0F29F7303B2ED`
SHA1 | `31AFD431BA77155D1530FD5587AB692CE589CED5`
SHA256 | `E0A025EEDF21623AFAF6F49789C67DAEF412F2E2A7EB88B12FD7933F1AEA5259`
SHA384 | `8F57D4DC69906CB04322844FE85E41376A9C8FF1D4C8BB5CB420CBBB2E7DDC435F5D5449FAC84B3F35CD0D6348EFC337`
SHA512 | `BA6276CE8F3AE4C087620814EF5813C749626BE0F24ABC29ADC2D8B6EA3843FD25BAF39739B68D7323B514A3E42442583875737CC685A0E6CCD688F300931794`
SSDEEP | `24576:K51HL2e8MJSkTZtQm1PG6JBl+nUhh/+mfkb2:A1r2eXSkTZtQm1PG6JuC/Zki`
IMP | `0AE830D4DAEADA1882946E679D9A4AD5`
PESHA1 | `068194E22E55F6C36BD0C28F785A08FEADF9A831`
PE256 | `101FAFBCAFADF5B612BFEBEB1189AE8E6345CF45DAB9E28856733485781A0E20`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`cexp_from_imag` | 25 | Exported Function
`ring_buffer_advance` | 52 | Exported Function
`resample_open` | 51 | Exported Function
`resample_close` | 50 | Exported Function
`RzssDecoder::remove441Resampler` | 23 | Exported Function
`RzssDecoder::processAudio` | 21 | Exported Function
`RzssDecoder::add441Resampler` | 13 | Exported Function
`ring_buffer_create` | 53 | Exported Function
`RzssDecoder::Message` | 20 | Exported Function
`RzssDecoder::Message` | 19 | Exported Function
`RzssDecoder::Chunk` | 17 | Exported Function
`RzssDecoder::Retainer` | 7 | Exported Function
`RzssDecoder::Listener` | 6 | Exported Function
`Retainer::wrongChecksum` | 24 | Exported Function
`Retainer::message` | 16 | Exported Function
`RzssDecoder::Message` | 18 | Exported Function
`ring_buffer_destroy` | 54 | Exported Function
`ring_buffer_peak` | 55 | Exported Function
`ring_buffer_size` | 56 | Exported Function
`ss_cfir_filter_process` | 71 | Exported Function
`ss_cfir_filter_drain` | 70 | Exported Function
`ss_cfir_filter_destroy` | 69 | Exported Function
`ss_cfir_filter_create` | 68 | Exported Function
`rzss_resample_process` | 67 | Exported Function
`rzss_encoder_message` | 66 | Exported Function
`rzss_encoder_drain` | 65 | Exported Function
`rzss_encoder_destroy` | 64 | Exported Function
`rzss_encoder_debug_test_set_all_user_vectors` | 63 | Exported Function
`rzss_encoder_create` | 62 | Exported Function
`rzss_encoder_chips` | 61 | Exported Function
`rzss_encoder_audio` | 60 | Exported Function
`rzss_crc` | 59 | Exported Function
`root_raised_cosine` | 58 | Exported Function
`ring_buffer_write` | 57 | Exported Function
`RzssDecoder::Retainer` | 10 | Exported Function
`testable_clock` | 72 | Exported Function
`RzssDecoder::Listener` | 9 | Exported Function
`Retainer::getAndResetMessageFlag` | 14 | Exported Function
`pons_decoder_create` | 37 | Exported Function
`pons_decoder_count_samples` | 36 | Exported Function
`pons_decoder_chunk_sample_distance` | 35 | Exported Function
`pons_decoder_chunk_b_best_vs_second` | 34 | Exported Function
`pons_decoder_chunk_b_best_vs_avg` | 33 | Exported Function
`pons_decoder_chunk_a_best_vs_second` | 32 | Exported Function
`pons_decoder_decode_chunk` | 38 | Exported Function
`pons_decoder_chunk_a_best_vs_avg` | 31 | Exported Function
`make_complex_float` | 29 | Exported Function
`generate_pons_matrix` | 28 | Exported Function
`conv_polyc` | 27 | Exported Function
`RzssDecoder::Retainer` | 12 | Exported Function
`RzssDecoder::Listener` | 11 | Exported Function
`chunk_to_user_vectors` | 26 | Exported Function
`pons_decoder_checksum_correct` | 30 | Exported Function
`pons_decoder_destroy` | 39 | Exported Function
`pons_decoder_has_message` | 40 | Exported Function
`pons_decoder_message_payload` | 41 | Exported Function
`public: __thiscall RzssDecoder::~RzssDecoder(void)` | 8 | Exported Function
`RzssDecoder::Listener` | 5 | Exported Function
`Retainer::Retainer` | 4 | Exported Function
`RzssDecoder::Retainer` | 3 | Exported Function
`Listener::Listener` | 2 | Exported Function
`RzssDecoder::Listener` | 1 | Exported Function
`RzssDecoder::processChunk` | 22 | Exported Function
`pons_matrix_pilot` | 49 | Exported Function
`pons_matrix_encode` | 48 | Exported Function
`pons_matrix_destroy` | 47 | Exported Function
`pons_matrix_decode` | 46 | Exported Function
`pons_matrix_create` | 45 | Exported Function
`pons_encode_to_user_vectors` | 44 | Exported Function
`pons_doppler_correlator` | 43 | Exported Function
`pons_decoder_reset` | 42 | Exported Function
`Retainer::getAndResetWrongChecksumFlag` | 15 | Exported Function
`user_vectors_to_chunk` | 73 | Exported Function


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
* VirusTotal Link: https://www.virustotal.com/gui/file/e0a025eedf21623afaf6f49789c67daef412f2e2a7eb88b12fd7933f1aea5259/detection/




MIT License. Copyright (c) 2020 Strontic.


