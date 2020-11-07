---
title: libwiretap.dll | Wireshark capture file library
excerpt: What is libwiretap.dll?
---

# libwiretap.dll 

* File Path: `C:\Program Files\Wireshark\libwiretap.dll`
* Description: Wireshark capture file library

## Hashes

Type | Hash
-- | --
MD5 | `0D5DB2A29745F3BF1A7E227F7B94AB7B`
SHA1 | `700FE0223BD5D1B4C0CDF15767B1618565A43B51`
SHA256 | `D68BA56FF61FF8B1CF23C033A38AC5BFFF70EECD78E06AEFDC22F765EABDBA6A`
SHA384 | `4968EB8380BCEBAB5092B8054A28469360C21E63E21BA73B60ED02F5A6C12B8336E257834EBB6C3F8BAB05A92CC232C8`
SHA512 | `1C1A49FDD5EE35EA0A10E9153A34A2068D54DD135F142041B5625182970835ED92DB1E3C2315F63F78C28A71FA5336C4F94F487FA1DC2B904EBBA639B68B1D58`
SSDEEP | `6144:MBgRX490uZgsR9+pEQfztOnuMVUEjfMIdjbkx91j0stYhcnIOwHWZJZc91VHsol:MoX4TgZROucnorWWZ/cJ`
IMP | `CBB4B20137A43277D96F8CB367A3A56D`
PESHA1 | `0359D4C0A944B1431318C3AF38ED95995556FC27`
PE256 | `6B32142DA631305B4A536F29769A5D97E160494F214CDDE0450D4C4DEE732427`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`file_eof` | 1 | Exported Function
`wtap_file_size` | 93 | Exported Function
`wtap_file_tsprec` | 94 | Exported Function
`wtap_file_type_subtype` | 95 | Exported Function
`wtap_file_type_subtype_short_string` | 96 | Exported Function
`wtap_file_type_subtype_string` | 97 | Exported Function
`wtap_free_extensions_list` | 98 | Exported Function
`wtap_file_get_shb_for_new_file` | 92 | Exported Function
`wtap_free_idb_info` | 99 | Exported Function
`wtap_get_all_capture_file_extensions_list` | 101 | Exported Function
`wtap_get_all_compression_type_extensions_list` | 102 | Exported Function
`wtap_get_all_file_extensions_list` | 103 | Exported Function
`wtap_get_bytes_dumped` | 104 | Exported Function
`wtap_get_compression_type` | 105 | Exported Function
`wtap_get_debug_if_descr` | 106 | Exported Function
`wtap_fstat` | 100 | Exported Function
`wtap_get_file_extension_type_extensions` | 107 | Exported Function
`wtap_file_get_shb` | 91 | Exported Function
`wtap_file_get_nrb` | 89 | Exported Function
`wtap_dump_open_stdout` | 75 | Exported Function
`wtap_dump_open_tempfile` | 76 | Exported Function
`wtap_dump_params_cleanup` | 77 | Exported Function
`wtap_dump_params_discard_decryption_secrets` | 78 | Exported Function
`wtap_dump_params_init` | 79 | Exported Function
`wtap_dump_set_addrinfo_list` | 80 | Exported Function
`wtap_file_get_nrb_for_new_file` | 90 | Exported Function
`wtap_dump_supports_comment_types` | 81 | Exported Function
`wtap_encap_name` | 83 | Exported Function
`wtap_encap_requires_phdr` | 84 | Exported Function
`wtap_fdclose` | 85 | Exported Function
`wtap_fdreopen` | 86 | Exported Function
`wtap_file_encap` | 87 | Exported Function
`wtap_file_get_idb_info` | 88 | Exported Function
`wtap_encap_description` | 82 | Exported Function
`wtap_get_file_extension_type_name` | 108 | Exported Function
`wtap_get_file_extensions_list` | 109 | Exported Function
`wtap_get_num_encap_types` | 110 | Exported Function
`wtap_register_file_type_extension` | 130 | Exported Function
`wtap_register_file_type_subtypes` | 131 | Exported Function
`wtap_register_open_info` | 132 | Exported Function
`wtap_register_plugin` | 133 | Exported Function
`wtap_seek_read` | 134 | Exported Function
`wtap_sequential_close` | 135 | Exported Function
`wtap_register_encap_type` | 129 | Exported Function
`wtap_set_bytes_dumped` | 136 | Exported Function
`wtap_set_cb_new_ipv6` | 138 | Exported Function
`wtap_set_cb_new_secrets` | 139 | Exported Function
`wtap_short_string_to_file_type_subtype` | 140 | Exported Function
`wtap_snapshot_length` | 141 | Exported Function
`wtap_strerror` | 142 | Exported Function
`wtap_tsprec_string` | 143 | Exported Function
`wtap_set_cb_new_ipv4` | 137 | Exported Function
`wtap_rec_init` | 128 | Exported Function
`wtap_rec_cleanup` | 127 | Exported Function
`wtap_read_so_far` | 126 | Exported Function
`wtap_get_num_file_type_extensions` | 111 | Exported Function
`wtap_get_num_file_types_subtypes` | 112 | Exported Function
`wtap_get_savable_file_types_subtypes` | 113 | Exported Function
`wtap_has_open_info` | 114 | Exported Function
`wtap_init` | 115 | Exported Function
`wtap_name_to_encap` | 116 | Exported Function
`wtap_open_offline` | 117 | Exported Function
`wtap_opttype_register_custom_block_type` | 118 | Exported Function
`wtap_opttypes_cleanup` | 119 | Exported Function
`wtap_opttypes_initialize` | 120 | Exported Function
`wtap_pcap_encap_to_wtap_encap` | 121 | Exported Function
`wtap_read` | 122 | Exported Function
`wtap_read_bytes` | 123 | Exported Function
`wtap_read_bytes_or_eof` | 124 | Exported Function
`wtap_read_packet_bytes` | 125 | Exported Function
`wtap_dump_open` | 74 | Exported Function
`wtap_write_shb_comment` | 144 | Exported Function
`wtap_dump_has_name_resolution` | 73 | Exported Function
`wtap_dump_flush` | 71 | Exported Function
`register_pcapng_option_handler` | 20 | Exported Function
`wtap_addrinfo_list_empty` | 21 | Exported Function
`wtap_block_add_custom_option` | 22 | Exported Function
`wtap_block_add_ipv4_option` | 23 | Exported Function
`wtap_block_add_ipv6_option` | 24 | Exported Function
`wtap_block_add_string_option` | 25 | Exported Function
`register_pcapng_block_type_handler` | 19 | Exported Function
`wtap_block_add_string_option_format` | 26 | Exported Function
`wtap_block_add_uint8_option` | 28 | Exported Function
`wtap_block_array_free` | 29 | Exported Function
`wtap_block_copy` | 30 | Exported Function
`wtap_block_create` | 31 | Exported Function
`wtap_block_foreach_option` | 32 | Exported Function
`wtap_block_free` | 33 | Exported Function
`wtap_block_add_uint64_option` | 27 | Exported Function
`wtap_block_get_custom_option_value` | 34 | Exported Function
`open_routines` | 18 | Exported Function
`merge_string_to_idb_merge_mode` | 16 | Exported Function
`file_error` | 2 | Exported Function
`file_getc` | 3 | Exported Function
`file_gets` | 4 | Exported Function
`file_getsp` | 5 | Exported Function
`file_iscompressed` | 6 | Exported Function
`file_peekc` | 7 | Exported Function
`open_info_name_to_type` | 17 | Exported Function
`file_read` | 8 | Exported Function
`file_tell` | 10 | Exported Function
`init_open_routines` | 11 | Exported Function
`merge_files` | 12 | Exported Function
`merge_files_to_stdout` | 13 | Exported Function
`merge_files_to_tempfile` | 14 | Exported Function
`merge_idb_merge_mode_to_string` | 15 | Exported Function
`file_seek` | 9 | Exported Function
`wtap_block_get_ipv4_option_value` | 35 | Exported Function
`wtap_block_get_ipv6_option_value` | 36 | Exported Function
`wtap_block_get_mandatory_data` | 37 | Exported Function
`wtap_default_file_extension` | 57 | Exported Function
`wtap_deregister_file_type_subtype` | 58 | Exported Function
`wtap_deregister_open_info` | 59 | Exported Function
`wtap_dump` | 60 | Exported Function
`wtap_dump_can_compress` | 61 | Exported Function
`wtap_dump_can_open` | 62 | Exported Function
`wtap_compression_type_extension` | 56 | Exported Function
`wtap_dump_can_write` | 63 | Exported Function
`wtap_dump_discard_decryption_secrets` | 65 | Exported Function
`wtap_dump_fdopen` | 66 | Exported Function
`wtap_dump_file_encap_type` | 67 | Exported Function
`wtap_dump_file_seek` | 68 | Exported Function
`wtap_dump_file_tell` | 69 | Exported Function
`wtap_dump_file_write` | 70 | Exported Function
`wtap_dump_close` | 64 | Exported Function
`wtap_compression_type_description` | 55 | Exported Function
`wtap_close` | 54 | Exported Function
`wtap_cleareof` | 53 | Exported Function
`wtap_block_get_nth_string_option_value` | 38 | Exported Function
`wtap_block_get_string_option_value` | 39 | Exported Function
`wtap_block_get_uint64_option_value` | 40 | Exported Function
`wtap_block_get_uint8_option_value` | 41 | Exported Function
`wtap_block_remove_nth_option_instance` | 42 | Exported Function
`wtap_block_remove_option` | 43 | Exported Function
`wtap_block_set_custom_option_value` | 44 | Exported Function
`wtap_block_set_ipv4_option_value` | 45 | Exported Function
`wtap_block_set_ipv6_option_value` | 46 | Exported Function
`wtap_block_set_nth_string_option_value` | 47 | Exported Function
`wtap_block_set_string_option_value` | 48 | Exported Function
`wtap_block_set_string_option_value_format` | 49 | Exported Function
`wtap_block_set_uint64_option_value` | 50 | Exported Function
`wtap_block_set_uint8_option_value` | 51 | Exported Function
`wtap_cleanup` | 52 | Exported Function
`wtap_dump_get_needs_reload` | 72 | Exported Function
`wtap_wtap_encap_to_pcap_encap` | 145 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `02CCD99F7D556C13CE8710C69D09B31A`
* Thumbprint: `E8EF7325044D018B0C0DCD8CBA4190B155857F3B`
* Issuer: CN=Sectigo RSA Code Signing CA, O=Sectigo Limited, L=Salford, S=Greater Manchester, C=GB
* Subject: CN="Wireshark Foundation, Inc.", O="Wireshark Foundation, Inc.", STREET=711 4th street, L=Davis, S=CA, PostalCode=95616, C=US

## File Metadata

* Original Filename: libwiretap.dll
* Product Name: Wireshark
* Company Name: The Wireshark developer community, https://www.wireshark.org/
* File Version: 3.2.7
* Product Version: 3.2.7
* Language: English (United States)
* Legal Copyright: Copyright  2000 Gerald Combs <gerald@wireshark.org>, Gilbert Ramirez <gram@alumni.rice.edu> and others
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/68
* VirusTotal Link: https://www.virustotal.com/gui/file/d68ba56ff61ff8b1cf23c033a38ac5bfff70eecd78e06aefdc22f765eabdba6a/detection/




MIT License. Copyright (c) 2020 Strontic.


