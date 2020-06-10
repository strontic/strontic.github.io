
# certutil.exe 
* File Path: `C:\Windows\SysWOW64\certutil.exe`
* Description: CertUtil.exe
* Comments: 

## Hashes
Type | Hash
-- | --
MD5 | `138DC8312317ED386C1CB62E19EA9269`
SHA1 | `E1F86B7B5246E4A63FEE14553ADF8F04DC2155C5`
SHA256 | `0994505DB3037CD793983FA7DCFC27367695177056D124A34E6E1AB691A138C2`
SHA384 | `11669B5D702EC16EF08399FEBB13D63CBDABFE1EF840ED093A5834E83F8D28837302B53DA08228DDCA42C962604149EA`
SHA415 | `150D94028D102F43C9B968FC88BE0E7F5779EFD8B64DB71220DD5C650F5222F42769910EF07B19701828A63860D5D165B9B6C82412603EC8C80312D8A453B0F6`
SSDEEP | `24576:IC9dAPbvxGaPIMePPyH1FTTkDW5GowZYReoo0j2FJ/dxXqlD:Zg5ZsnyH1FfknoGfqlD`

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
  -UI               -- Certificate Trust List:
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

  -verifykeys       -- Verify public/private key set
  -verify           -- Verify certificate, CRL or chain
  -verifyCTL        -- Verify AuthRoot or Disallowed Certificates CTL
  -syncWithWU       -- Sync with Windows Update
  -generateSSTFromWU -- Generate SST from Windows Update
  -generatePinRulesCTL -- Generate Pin Rules CTL
  -downloadOcsp     -- Download OCSP Responses and Write to Directory
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
* Serial: 3300000266BD1580EFA75CD6D3000000000266
* Thumbprint: A4341B9FD50FB9964283220A36A1EF6F6FAA7840
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: CertUtil.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


