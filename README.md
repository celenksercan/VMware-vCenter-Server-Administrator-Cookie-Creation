Tüm komut dosyaları hem Linux hem de Windows sistemlerinde ve Python 3 ortamında çalışmaktadır.

VMware-fingerprinter.py: Bu dosya, otomatik ve çok iş parçacıklı bir şekilde VMware numaralandırma taraması yaparak birkaç önemli güvenlik açığını tespit eder.

VMware-vCenter-decryptor.py: Bu dosya, vCenter kurulumlarından ESXi Ana Bilgisayarlarının vpx kullanıcı şifrelerini taramak ve bu şifrelerin kodunu çözmek için tasarlanmıştır.

VMware-vCenter_saml_login.py: Bu dosya, MDB dosyası ile birlikte kullanıldığında vCenter için bir SSO tarayıcı çerezi oluşturur.

Önkoşullar: Bu komut dosyalarını çalıştırmak için gereken önkoşullar şunlardır:

python3 -m pip install requests bitstrings signxml python-dateutil
