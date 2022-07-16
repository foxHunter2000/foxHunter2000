Google Git
Sign in
chromium / chromium / src / crypto / ea9486c56b3dde246fe005c2d337577f49182468
commit	ea9486c56b3dde246fe005c2d337577f49182468	[log] [tgz]
author	Daniel Cheng <dcheng@chromium.org>	Thu Jan 13 23:43:05 2022
committer	Copybara-Service <copybara-worker@google.com>	Thu Jan 13 23:54:58 2022
tree	e3a6515665e97b5fb5055c29532fb1cea00371f7
parent	d9c59b366189e851f72fd6db05b6cbaf866a9c56 [diff]
Convert WARN_UNUSED_RESULT to [[nodiscard]] in //crypto.

This is an automated conversion produced by the script and command in
the attached bug.

Bug: 1287045
Change-Id: I2d7cd19d5ab3052af5db668457ad85967a053712
Reviewed-on: https://chromium-review.googlesource.com/c/chromium/src/+/3387500
Commit-Queue: Daniel Cheng <dcheng@chromium.org>
Auto-Submit: Daniel Cheng <dcheng@chromium.org>
Reviewed-by: Adam Langley <agl@chromium.org>
Commit-Queue: Adam Langley <agl@chromium.org>
Cr-Commit-Position: refs/heads/main@{#958917}
NOKEYCHECK=True
GitOrigin-RevId: 1dca8cd5da8beada1e8a5f90f01e3932117a5200
hmac.h[diff]
nss_util_internal.h[diff]
2 files changed
tree: e3a6515665e97b5fb5055c29532fb1cea00371f7
BUILD.gn
DEPS
DIR_METADATA
OWNERS
aead.cc
aead.h
aead_unittest.cc
apple_keychain.h
apple_keychain_ios.mm
apple_keychain_mac.mm
capi_util.cc
capi_util.h
chaps_support.cc
chaps_support.h
crypto_export.h
ec_private_key.cc
ec_private_key.h
ec_private_key_unittest.cc
ec_signature_creator.cc
ec_signature_creator.h
ec_signature_creator_impl.cc
ec_signature_creator_impl.h
ec_signature_creator_unittest.cc
encryptor.cc
encryptor.h
encryptor_unittest.cc
hkdf.cc
hkdf.h
hmac.cc
hmac.h
hmac_unittest.cc
mac_security_services_lock.cc
mac_security_services_lock.h
mock_apple_keychain.cc
mock_apple_keychain.h
mock_apple_keychain_ios.cc
mock_apple_keychain_mac.cc
nss_crypto_module_delegate.h
nss_key_util.cc
nss_key_util.h
nss_key_util_unittest.cc
nss_util.cc
nss_util.h
nss_util_chromeos.cc
nss_util_internal.h
nss_util_unittest.cc
openssl_util.cc
openssl_util.h
p224_spake.cc
p224_spake.h
p224_spake_unittest.cc
random.cc
random.h
random_unittest.cc
rsa_private_key.cc
rsa_private_key.h
rsa_private_key_unittest.cc
scoped_capi_types.h
scoped_mock_unexportable_key_provider.cc
scoped_mock_unexportable_key_provider.h
scoped_nss_types.h
scoped_test_nss_chromeos_user.cc
scoped_test_nss_chromeos_user.h
scoped_test_nss_db.cc
scoped_test_nss_db.h
scoped_test_system_nss_key_slot.cc
scoped_test_system_nss_key_slot.h
secure_hash.cc
secure_hash.h
secure_hash_unittest.cc
secure_util.cc
secure_util.h
sha2.cc
sha2.h
sha2_unittest.cc
signature_creator.cc
signature_creator.h
signature_creator_unittest.cc
signature_verifier.cc
signature_verifier.h
signature_verifier_unittest.cc
symmetric_key.cc
symmetric_key.h
symmetric_key_unittest.cc
unexportable_key.cc
unexportable_key.h
unexportable_key_unittest.cc
unexportable_key_win.cc
Powered by Gitiles| Privacytxt json### Hi there 👋

<!--
**foxHunter2000/foxHunter2000** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ... mailto:philipp.hancke@googlemail.com
- ⚡ Fun fact: ...
-->
