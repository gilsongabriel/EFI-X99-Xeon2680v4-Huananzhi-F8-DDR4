# EFI X99 Xeon2680v4 Huananzhi F8 DDR4

Esta EFI foi personalizada a partir da EFI base disponibilizada pelo [Gabriel Luchina do Universo Hackintoshi](https://github.com/luchina-gabriel) no seu repositório [BASE-EFI-INTEL-HEDT-5THGEN-X99-BROADWELL-E](https://github.com/luchina-gabriel/BASE-EFI-INTEL-HEDT-5THGEN-X99-BROADWELL-E)

Siga o Universo Hackintoshi para saber tudo sobre hackintosh.

## [Universo Hackintoshi no Youtube](https://www.youtube.com/c/GabrielLuchina)

## [Universo Hackintoshi no Discord](https://universohackintosh.com/DISCORD)

## Setup

```
Plataforma: Desktop | Intel X99
Placa Mãe: HuanaZhi F8
Processador: Intel Xeon E5-2680v4 2.4GHz 14C/28T
Vídeo: AMD Radeon RX 6600M 8GB GDDR6
Áudio: Realtek ALC892 codec
Rede: Realtek's Gigabit Ethernet
SMBIOS: iMacPro1,1
macOS: Monterey ou superiores
Opencore: 0.8.5
```

# IMPORTANTE!!!

## Antes de instalar o macOS, você deve fazer o seguinte

### 1. Atualize os dados da SMBIOS no arquivo config.plist

A SMBIOS iMacPro1,1 é a mais recomendada para este processador. Mas você pode usar a SMBIOS iMacPro7,1 de acordo com seu hardware. [Mais informações](https://github.com/luchina-gabriel/BASE-EFI-INTEL-HEDT-5THGEN-X99-BROADWELL-E#compatible-smbios)

### 2. Verificar sua placa de rede

A placa de rede configurada nesta EFI é a Realtek's Gigabit Ethernet, utilizando a kext [RealtekRTL8111 v2.4.2](https://github.com/Mieze/RTL8111_driver_for_OS_X/releases). Se você tiver uma placa de rede diferente, você deve incluir a kext correta para funcionamento do acesso à internet no momento da instalação. [Mais informações](https://github.com/luchina-gabriel/BASE-EFI-INTEL-HEDT-5THGEN-X99-BROADWELL-E#ethernet)
