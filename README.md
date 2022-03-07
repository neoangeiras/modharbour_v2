# modharbour v2

Versão 2.0 do mod_harbour compilado para Linux Ubuntu 18.04 64 bits

Copiar o arquivo mod_harbour.v2.so para /usr/lib/apache2/modules

Para configurar, incluir no apache2.conf:

- LoadModule harbourV2_module /usr/lib/apache2/modules/mod_harbour.v2.so
- <FilesMatch "\.prg|hrb)$">
   SetHandler harbour
  </FilesMatch> 
