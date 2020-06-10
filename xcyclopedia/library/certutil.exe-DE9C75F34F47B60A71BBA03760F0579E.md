
# certutil.exe 
* File Path: `C:\WINDOWS\system32\certutil.exe`
* Description: CertUtil.exe
* Comments: 

## Hashes
Type | Hash
-- | --
MD5 | `DE9C75F34F47B60A71BBA03760F0579E`
SHA1 | `41875CABE350022579F070EC2A059C9806770474`
SHA256 | `12F06D3B1601004DB3F7F1A07E7D3AF4CC838E890E0FF50C51E4A0C9366719ED`
SHA384 | `853FC2F28B25B7A1CC6A3C8BDCD32817E47548012450D45A8DEC5619B6F32A594EC9B1D424CB40FA21DB2CBD69C23C8E`
SHA415 | `6FE3B4026AC6E8C5F50C13995F81143C764032C7C9AE7943BC77E90A60612EEB1FBC944B94DF03F01685C0F35689E67B459198C282401115A264808FE8413424`
SSDEEP | `24576:NYLCYvmm3rc2IL6yK0C13VNiEl78YUEI01/ul1wM61MFUiMdQefoCPTvi20:NYLCY+m3rcD2ycNieuEI3N6EUiMWem2`

## Runtime Data
### Usage (stdout):
```Batchfile

Verbs:
  -dump             -- Dump configuration information or file
  -dumpPFX          -- Dump PFX structure
  -asn              -- Parse ASN.1 file

  -decodehex        -- Decode hexadecimal-encoded file
  -decode           -- Decode Base64-encoded file
  -encode           -- Encode file to Base64

  -deny             -- Deny pending request
  -resubmit         -- Resubmit pending request
  -setattributes    -- Set attributes for pending request
  -setextension     -- Set extension for pending request
  -revoke           -- Revoke Certificate
  -isvalid          -- Display current certificate disposition

  -getconfig        -- Get default configuration string
  -ping             -- Ping Active Directory Certificate Services Request interface
  -pingadmin        -- Ping Active Directory Certificate Services Admin interface
  -CAInfo           -- Display CA Information
  -ca.cert          -- Retrieve the CA's certificate
  -ca.chain         -- Retrieve the CA's certificate chain
  -GetCRL           -- Get CRL
  -CRL              -- Publish new CRLs [or delta CRLs only]
  -shutdown         -- Shutdown Active Directory Certificate Services

  -installCert      -- Install Certification Authority certificate
  -renewCert        -- Renew Certification Authority certificate

  -schema           -- Dump Certificate Schema
  -view             -- Dump Certificate View
  -db               -- Dump Raw Database
  -deleterow        -- Delete server database row

  -backup           -- Backup Active Directory Certificate Services
  -backupDB         -- Backup Active Directory Certificate Services database
  -backupKey        -- Backup Active Directory Certificate Services certificate and private key
  -restore          -- Restore Active Directory Certificate Services
  -restoreDB        -- Restore Active Directory Certificate Services database
  -restoreKey       -- Restore Active Directory Certificate Services certificate and private key
  -importPFX        -- Import certificate and private key
  -dynamicfilelist  -- Display dynamic file List
  -databaselocations -- Display database locations
  -hashfile         -- Generate and display cryptographic hash over a file

  -store            -- Dump certificate store
  -enumstore        -- Enumerate certificate stores
  -addstore         -- Add certificate to store
  -delstore         -- Delete certificate from store
  -verifystore      -- Verify certificate in store
  -repairstore      -- Repair key association or update certificate properties or key security descriptor
  -viewstore        -- Dump certificate store
  -viewdelstore     -- Delete certificate from store
  -UI               -- invoke CryptUI
  -attest           -- Verify Key Attestation Request

  -dsPublish        -- Publish certificate or CRL to Active Directory

  -ADTemplate       -- Display AD templates
  -Template         -- Display Enrollment Policy templates
  -TemplateCAs      -- Display CAs for template
  -CATemplates      -- Display templates for CA
  -SetCASites       -- Manage Site Names for CAs
  -enrollmentServerURL -- Display, add or delete enrollment server URLs associated with a CA
  -ADCA             -- Display AD CAs
  -CA               -- Display Enrollment Policy CAs
  -Policy           -- Display Enrollment Policy
  -PolicyCache      -- Display or delete Enrollment Policy Cache entries
  -CredStore        -- Display, add or delete Credential Store entries
  -InstallDefaultTemplates -- Install default certificate templates
  -URLCache         -- Display or delete URL cache entries
  -pulse            -- Pulse autoenrollment event or NGC task
  -MachineInfo      -- Display Active Directory machine object information
  -DCInfo           -- Display domain controller information
  -EntInfo          -- Display enterprise information
  -TCAInfo          -- Display CA information
  -SCInfo           -- Display smart card information

  -SCRoots          -- Manage smart card root certificates

  -DeleteHelloContainer -- Delete Hello Logon container.  
     ** Users need to sign out after using this option for it to complete. **
  -verifykeys       -- Verify public/private key set
  -verify           -- Verify certificate, CRL or chain
  -verifyCTL        -- Verify AuthRoot or Disallowed Certificates CTL
  -syncWithWU       -- Sync with Windows Update
  -generateSSTFromWU -- Generate SST from Windows Update
  -generatePinRulesCTL -- Generate Pin Rules CTL
  -downloadOcsp     -- Download OCSP Responses and Write to Directory
  -generateHpkpHeader -- Generate HPKP header using certificates in specified file or directory
  -flushCache       -- Flush specified caches in selected process, such as, lsass.exe
  -addEccCurve      -- Add ECC Curve
  -deleteEccCurve   -- Delete ECC Curve
  -displayEccCurve  -- Display ECC Curve
  -sign             -- Re-sign CRL or certificate

  -vroot            -- Create/delete web virtual roots and file shares
  -vocsproot        -- Create/delete web virtual roots for OCSP web proxy
  -addEnrollmentServer -- Add an Enrollment Server application
  -deleteEnrollmentServer -- Delete an Enrollment Server application
  -addPolicyServer  -- Add a Policy Server application
  -deletePolicyServer -- Delete a Policy Server application
  -oid              -- Display ObjectId or set display name
  -error            -- Display error code message text
  -getreg           -- Display registry value
  -setreg           -- Set registry value
  -delreg           -- Delete registry value

  -ImportKMS        -- Import user keys and certificates into server database for key archival
  -ImportCert       -- Import a certificate file into the database
  -GetKey           -- Retrieve archived private key recovery blob, generate a recovery script,
      or recover archived keys
  -RecoverKey       -- Recover archived private key
  -MergePFX         -- Merge PFX files
  -ConvertEPF       -- Convert PFX files to EPF file

  -add-chain        -- (-AddChain) Add certificate chain
  -add-pre-chain    -- (-AddPrechain) Add pre-certificate chain
  -get-sth          -- (-GetSTH) Get signed tree head
  -get-sth-consistency -- (-GetSTHConsistency) Get signed tree head changes
  -get-proof-by-hash -- (-GetProofByHash) Get proof by hash
  -get-entries      -- (-GetEntries) Get entries
  -get-roots        -- (-GetRoots) Get roots
  -get-entry-and-proof -- (-GetEntryAndProof) Get entry and proof
  -VerifyCT         -- Verify certificate SCT
  -?                -- Display this usage message


CertUtil -?              -- Display a verb list (command list)
CertUtil -dump -?        -- Display help text for the "dump" verb
CertUtil -v -?           -- Display all help text for all verbs

CertUtil: -? command completed successfully.

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: 330000023241FB59996DCC4DFF000000000232
* Thumbprint: FF82BC38E1DA5E596DF374C53E3617F7EDA36B06
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: CertUtil.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


