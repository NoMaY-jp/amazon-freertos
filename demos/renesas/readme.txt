----------------------------------------------
Amazon FreeRTOS �|�[�e�B���O�L�^
----------------------------------------------
���w�i
���l�T�X�����R�~���j�e�B�u���ӂ����l�v��Amazon FreeRTOS�֘A��
�b�肪����ANoMaY�����܂Ƃ߂Ă��ꂽ��������RX65N��
Amazon FreeRTOS�𓮍삳���邱�Ƃ�ڎw���B
https://japan.renesasrulz.com/cafe_rene/f/forum21/4772/amazon-freertos-rx/

�{�L�^�́u���ӂ����l�v�Ŋ�������V�F���e�B���L���B

--------------------------------------------------------------------------
���J����
--------------------------------------------------------------------------
�{�[�h�FRX65N Envision Kit 
        https://www.renesas.com/ja-jp/products/software-tools/boards-and-kits/renesas-promotion-boards/rx65n-envision-kit.html
        Renesas Starter Kit+ for RX65N-2MB (Trusted Secure IP����)�@��
        https://www.renesas.com/ja-jp/products/software-tools/boards-and-kits/renesas-starter-kits/renesas-starter-kitplus-for-rx65n-2mb.html
�f�o�b�K�FE2OB(RX65N Envision Kit�̏ꍇ(�I���{�[�h�Ȃ̂Œǉ��w���s�v))
          E1�G�~�����[�^(RX65N Starter Kit+ for RX65N-2MB�̏ꍇ(�L�b�g�ɕt���̂��ߒǉ��w���s�v))
�R���p�C���FCC-RX V2.08
        https://www.renesas.com/ja-jp/products/software-tools/tools/compiler-assembler/compiler-package-for-rx-family-e2studio.html
IDE�Fe2 studio V6.2.0
        https://www.renesas.com/ja-jp/products/software-tools/tools/ide/e2studio.html
    ���J����RX65N Envision Kit �ōs���A
    �@�K�XRenesas Starter Kit+ for RX65N-2MB (Trusted Secure IP����)�ł�
�@�@�@�����悤�ɂ���B

--------------------------------------------------------------------------
���i��
--------------------------------------------------------------------------
RX65N Envision Kit�ARX65N RSK(2MB��/�Í��킠��i)���^�[�Q�b�g�ɃR�[�h�����e���ێ����܂��B
���L Amazon FreeRTOS 1.2.x �͓K�X�ŐV�R�[�h�ɍX�V���Ă����܂��B
2018/03/17���_�ł̓K�p�R�[�h�� 1.2.2 �ł��B

�@���l�T�XTCP/IP���^�[�Q�b�g�œ��삳����iEther�̓���m�F�j
�ASDIO����LAN�𓮍�m�F����������FreeRTOS 8.2.2���^�[�Q�b�g�œ��삳����
�B���l�T�X��FreeRTOS�p�b�P�[�W�A9.0.0���^�[�Q�b�g�œ��삳����
�CAmazon FreeRTOS 1.2.x��FreeRTOS�������^�[�Q�b�g�œ��삳����
�DAmazon FreeRTOS 1.2.x��FreeRTOS+TCP�������^�[�Q�b�g�œ��삳����
�EAmazon FreeRTOS 1.2.x��mbed TLS�������^�[�Q�b�g�œ��삳����
�FAmazon FreeRTOS 1.2.x��MQTT�������^�[�Q�b�g�œ��삳����iAWS�ւ̐ڑ������j
�GAmazon FreeRTOS 1.2.x��FreeRTOS+TCP�����̃l�b�g���[�N�w�̌����������H�v���āA
�@(1)Ether�A(2)SPI�ڑ�����LAN���W���[���A(3)SDIO����LAN���W���[����3��ނ�
�@�؂�ւ�����悤�ɂ���@�����܂������V�F���e�B
�HAmazon FreeRTOS 1.2.x��mbed TLS�����̈Í������v���~�e�B�u��
�@�\�t�g�E�F�A�����iAES�Ƃ�RSA�Ƃ��j��RX65N�����Í�����g����
�@�n�[�h�E�F�A�����ɒu��������@�����܂��������͉��
�IEther�w�̃[���R�s�[�ɑΉ�����
�JAmazon FreeRTOS�{�Ɗ��Ƀ}�[�W���AAmazon FreeRTOS�{�ƃR�[�h�ւ̒Ǐ]���ȒP�ɂł���悤�ɂ���
�KAmazon FreeRTOS ��Git��fork�ɓo�^����
�LAmazon FreeRTOS ��Certification���󌱂����i��Git�̖{�Ƃɓo�^����
�@docs.aws.amazon.com/.../freertos-qualification-program.html

--------------------------------------------------------------------------
���ۑ�܂Ƃ߁�
--------------------------------------------------------------------------
�@2018/03/17
�@�@2018/03/17�̃|�[�e�B���O�L�^�Q��
�@�@
�@2018/03/03�ȑO
�@�@NetworkInterface.c 
�@�@(2)�[���R�s�[�̊T�O�𖳎����邪...��
�@�@(4)(���M���̃[���R�s�[�̎d�g�݂��s���B������܂���Œ��ׂ遚)
�@�@(5)LAN�P�[�u���}���̃C�x���g��TCP/IP���ɒʒm����d�g�݂����邪...��

�@�@���̑�
�@�@�E�V�X�e�����O��SCI����o�͂���悤�ɃR�[�h�ǉ�����΂悢�B(����Ń����e)
�@�@�E�R���p�C���O�����̍\����͂ŃG���[�ɂȂ��Ă��銴���B�����c�[���J������ɖ₢���킹�Ă݂�B

�@���̑�
�@�@NoMaY���̒�Ă̒����B2018/3/11 0:00 �̃|�X�g�Q�ƁB
�@�@https://japan.renesasrulz.com/cafe_rene/f/forum21/4772/amazon-freertos-rx/27511#27511

--------------------------------------------------------------------------
���|�[�e�B���O�L�^	���󂪉������ׂ��ۑ�
--------------------------------------------------------------------------
2018/03/17
�@���͉�ЂɈ˗������i���E�F���߂��Ă����B
�@3/3���̐��ʂɑ΂��AAWS�ڑ�(MQTT������SSL/TLS����)���o�����悤���B
�@����Ői���E�F��OK�ƂȂ����B���@�m�F���A�m����MQTT��AWS�Ɍq������
�@HELLO WORLD�������Ă��邱�Ƃ��m�F�B���͉�Ђ͌��ݐi���H�̒�����i�߂Ă���B
�@
�@�V�F���e�B�͂��낻��G�������e����K�v�����肻���B
�@�ȉ��ɒ��߂Ō������s�����{���̖���LAN�Ή����j���L���B
�@
�@SPI�ڑ��̖���LAN���W���[���͎�v���Ŏg�p/�T�|�[�g�\�Ȃ��̂Ƃ���Silex��SX-ULPGN�A
�@�V����������Realtek��RTL8710��I��B�z�r�[���[�X������Espressif��ESP8266�B
�@Realtek�Ƃ����ƃV�F���e�B��g�ݍ��݃l�b�g���[�N�̐��E�ɗU������
�@���̃J�j�}�[�N�̃`�b�v�ARTL8019AS���v���o���B
�@�@https://www.google.co.jp/search?q=rtl8019as&source=lnms&tbm=isch&sa=X&ved=0ahUKEwjDvoyzsvLZAhVDGpQKHVjECycQ_AUICygC&biw=2021&bih=1014
�@
�@
�@SDIO�ڑ��̖���LAN���W���[���͌v��ʂ葺�c���쏊��Type 1FX�B
�@���ꂼ��SDK����肵�Ď����ł���悤��z��i�߂Ă����B
�@�C���^�t�F�[�X��PMOD�ɂȂ��Ă���΂ǂ̃��l�T�X�{�[�h�ɂ�
�@�������Őڑ��\�BPMOD�^�C�v������Ώ��ǂ��B
�@PMOD�^�C�v��SPI�ڑ��ŗD��B�iUART���ƒx������j
�@SDK�������SPI�ł�USB�ł�UART�ł��Ȃ�ł��ł���W�F�l���b�N�Ȋ������ǂ��B
�@
�@<<SPI�ڑ�����LAN���W���[��>>
�@Silex��SX-ULPGN
�@(SDK)�F������
�@�@http://www.silexamerica.com/products/connectivity-solutions/embedded-wireless/IoT-Modules/sx-ulpgn-evk/
�@(���W���[��)�F������
�@�@http://www.silexamerica.com/products/connectivity-solutions/embedded-wireless/IoT-Modules/sx-ulpgn-iot-qca4010-radio-module/
�@�@��PMOD�R���o�[�^����邩�H
�@�@
�@Realtek��RTL8710
�@(SDK)�F������
�@�@�ǂ��̂������B
�@(���W���[��)�F������
�@�@https://www.seeedstudio.com/RTL8710-WiFi-Module-p-2793.html
�@�@��PMOD�R���o�[�^����邩�H
�@
�@Espressif��ESP8266
�@(SDK)�F������
�@�@https://www.mouser.jp/ProductDetail/Olimex-Ltd/MOD-WIFI-ESP8266?qs=QGk6feVlqMKKopUWzCH4tA%3D%3D
�@(���W���[��)�F
�@�@��SDK�ŏ\���������H

�@<<SDIO�ڑ�����LAN���W���[��>>
�@���c���쏊��Type 1FX
�@(SDK)�F����ς݁i������1��̂݁B���͉�Зp�ɂ���1��ǉ��K�v�j
�@�@https://www.digikey.jp/product-detail/ja/murata-electronics-north-america/LBWA1KL1FX-TEMP-DS-SD/490-14857-ND/6612483
�@(���W���[���j�F������
�@�@https://wireless.murata.com/eng/products/rf-modules-1/embedded-wi-fi-1/type-1fx.html
�@�@
�@<<����LAN�h���C�o�J���̍��>>
�@SPI�ڑ��̖���LAN���W���[���̃h���C�o���͎��̋���f�ނɗǂ������B
�@���܂��Փx�͍����Ȃ��̂ŁA�f�[�^�V�[�g���Ȃ���Ƃɂ�������OK�B

�@SDIO�ڑ��̖���LAN���W���[���̃h���C�o���͋��͉�ЂɈ˗�����\��B
�@Type 1FX��Broadcom�̃`�b�v�Z�b�g�����ڂ���Ă���BBroadcom�̖������Ƃ�Cypress��
�@���p����Ă���A���ݖ���LAN�h���C�o(WICED)��Cypress����I�[�v���\�[�X�񋟂���Ă���B
�@Type 1FX�̑O�g�ł���Type ZX�p��WICED�͉ߋ�FreeRTOS��ł̓���m�F���ł����̂ŁA
�@�܂�Type ZX�p��WICED�\�t�g��p����Type ZX�œ���m�F��i�߂Ă݂�BType ZX��SDK�͓���ς݁B
�@Type 1FX�Ή���WICED�̃I�[�v���\�[�X���撣���Ď��͈ڐA���邩
�@���c���쏊�ɃT�|�[�g�˗����邩�����B
�@
�@�|���Ď茳�ł̐i���E�F�̃}�[�W���s���B
�@���̌�Amazon FreeRTOS�{�ƂƂ̃Y������m�F����B

�@rx65n_rsk_aws�Ŏ����J�n�B

�@<<�i���E�F�̃}�[�W>>
�@�܂��ω��_�𕪉����č\����c�����Ă����A���|�W�g���o�^���Ă����B
�@�܂��͒�Ԃ�grep�����B
�@�ȍ~�A�V�F���e�B�ł�{���A���͉�Дł��x���ƕ\������B
�@
�@rx65n_rsk_aws.c
�@�@���C���^�X�N�����B�x���ɂ�AWS�ڑ����s���^�X�N�N�����̏������ǉ�����Ă���B
�@�@�{���Ƀ}�[�W�B
�@�@�ȉ�2�֐����ǉ�����Ă���B���Ƃŗ�������B��
�@�@�@vApplicationGetIdleTaskMemory()
�@�@�@vApplicationGetTimerTaskMemory()
�@�@�ȉ��֐��Ăяo���������Ă���B���Ƃŗ�������B��
�@�@�@SYSTEM_Init()
�@�@�@
�@\rx65n_rsk_aws_\src\amazon-freertos-master
�@ \demos\common
�@�@�ȉ��t�@�C��/�t�H���_�������Ă���B�f���p�R�[�h�̗l�q�B�{���Ƀ}�[�W�B
�@�@���Ƃŗ�������B��
�@�@�@demo_runner
�@�@�@include�@�@�@���C���N���[�h�p�X��ǉ����Ă���
�@�@�@mqtt
�@�@�@tcp
�@
�@\rx65n_rsk_aws\src\amazon-freertos-master
�@ \demos\renesas\rx65n_envision_kit\common\application_code\renesas_code
�@  \entropy_hardware_poll.c
�@  Amazon FreeRTOS���v������G���g���s�[�\�[�X(������)�̎����B
�@  ���݂͌Œ�l���Ԃ�悤�Ɏ�������Ă��邪�A
�@  NetworkInterface.c��get_random_number()�֐�������̂ł��Ƃł����Ɍq���悤�ύX�B
�@  �ŏI�I��get_random_number()�͈Í�IP������`�b�v�̂Ƃ��͈Í�IP�̗����킩��
�@  �������擾����悤�ɕύX����B�Í�IP���Ȃ��`�b�v�̂Ƃ��͋^�������ɂ���B��
�@  
�@  ���łɁANetworkInterface.c�� uRand()�̎������o�O���Ă����̂ŏC���B
�@  uint32_t ulRand(void)
    {
	/* ��Ńn�[�h�E�F�A����(�Í���g�p)�ɕύX���܂� (�V�F���e�B) */
	uint32_t tmp;
	get_random_number(tmp, 4);
	return tmp;
    }
    ��
�@  uint32_t ulRand(void)
    {
	/* ��Ńn�[�h�E�F�A����(�Í���g�p)�ɕύX���܂� (�V�F���e�B) */
	uint32_t tmp;
	get_random_number(&tmp, 4);
	return tmp;
    }

�@\rx65n_rsk_aws\src\amazon-freertos-master
�@ \demos\renesas\rx65n_envision_kit\common\config_files
�@ �@�ȉ��R���t�B�O�t�@�C���������Ă���B�{���Ƀ}�[�W�B
�@ �@aws_bufferpool_config.h
�@ �@aws_demo_config.h
�@ �@aws_mqtt_agent_config.h
�@ �@aws_mqtt_config.h
�@ �@aws_secure_sockets_config.h
�@ �@
�@ �@�ȉ��R���t�B�O�t�@�C�����ύX����Ă���B�{���Ƀ}�[�W�B���Ƃŗ�������B��
�@ �@FreeRTOSConfig.h
�@ �@
�@�@ �@�ǉ��F
�@�@ �@#define configSUPPORT_STATIC_ALLOCATION              1

�@�@�@/*********************************************
�@�@�@ * FreeRTOS specific demos
�@�@�@ ********************************************/

�@�@�@/* The address of an echo server that will be used by the two demo echo client
�@�@�@ * tasks.
�@�@�@ * http://www.freertos.org/FreeRTOS-Plus/FreeRTOS_Plus_TCP/TCP_Echo_Clients.html
�@�@�@ * http://www.freertos.org/FreeRTOS-Plus/FreeRTOS_Plus_TCP/UDP_Echo_Clients.html */
�@�@�@#define configECHO_SERVER_ADDR0       192
�@�@�@#define configECHO_SERVER_ADDR1       168
�@�@�@#define configECHO_SERVER_ADDR2       0
�@�@�@#define configECHO_SERVER_ADDR3       1
�@�@�@#define configTCP_ECHO_CLIENT_PORT    8888

�@\rx65n_rsk_aws_\src\amazon-freertos-master
�@ \lib
�@ �@�ȉ��t�H���_�������Ă���B�{���Ƀ}�[�W�B
�@ �@�@bufferpool
�@ �@�@crypto
�@ �@�@mqtt
�@ �@�@pkcs11
�@ �@�@secure_sockets
�@ �@�@third_party
�@ �@�@�@\mbedtls\include�@���C���N���[�h�p�X��ǉ����Ă���
�@ �@�@�@ \mbedtls
�@ �@�@�@\pkcs11�@���C���N���[�h�p�X��ǉ����Ă���
�@ �@�@tls
�@ �@�@utils
�@
�@\rx65n_rsk_aws_\src\smc_gen
�@�@�ȉ��t�H���_�������Ă���B����̓��l�T�X�̃t���b�V��API��FIT���W���[�����B
�@�@�X�}�[�g�R���t�B�O���[�^�̋@�\�Ńt���b�V��API�̃��W���[����ǉ�����B
�@�@r_flash_rx
�@ 
�@�����܂łŎx����{���Ƀ}�[�W�����A�V�F���e�B�̊J���T�[�o�ɃR�~�b�g����B(r5128)
�@
�@<<Amazon FreeRTOS�{�ƂƂ̃Y������m�F>>
�@�ŐV��v1.2.2���_�E�����[�h����B�{�Ƃƌď̂���B
�@�@https://github.com/aws/amazon-freertos

�@amazon-freertos-master�t�H���_�S�̂�grep���Ė{�ƂƖ{���̍����m�F����B
�@\rx65n_rsk_aws\src\amazon-freertos-master\demos
�@ \common
�@  �{���ɂ͈ȉ��t�H���_������Ă��Ȃ��B�ŏI�I�ɂ͂ǂ����邩�����B��
�@  �@devmode_key_provisioning
�@  �@greengrass_connectivity
�@  �@logging
�@  �@ota
�@  �@shadow
�@
�@\rx65n_rsk_aws\src\amazon-freertos-master\demos
�@ \renesas\rx65n_envision_kit\common\application_code\renesas_code
�@  �{�Ƃ͊e�}�C�R���p��BSP��W���f�o�C�X�h���C�o�Amain�֐��A
�@  �v���W�F�N�g�t�@�C�����͂����ɓo�^����Ă���B�ŏI�I�ɂ̓��l�T�X�������z���B��
�@
�@\rx65n_rsk_aws\src\amazon-freertos-master
�@�@���C�Z���X�֌W�̈ȉ��t�@�C���������Ă���B�o�^�����B
�@�@�@change_log.txt
�@�@�@directories.txt
�@�@�@LICENSE
�@�@�@README.md
�@�@�@
�@\rx65n_rsk_aws\src\amazon-freertos-master\demos
�@ \common\include
�@ �@Amazon FreeRTOS v1.2.2�̍ŐV�R�[�h�ɒu�������B
�@ �@(RX�}�C�R���p�e�X�g�A�J�E���g�f�[�^�͎c��)
�@
�@\rx65n_rsk_aws\src\amazon-freertos-master
�@ \demos\common\demo_runner
�@  aws_demo_runner.c
�@ �@Amazon FreeRTOS v1.2.2�̍ŐV�R�[�h�ɒu�������B
�@ �@���}�[�N�̂Ƃ���i���͉�Ђɂ�钲���R�[�h�j�͎c���B��
�@
�@\rx65n_rsk_aws\src\amazon-freertos-master\lib
�@ \FreeRTOS\portable\Renesas\RX600v2
�@  port.c
�@   �C���N���[�h�t�@�C�����Aiodefine.h(�{��)��platform.h(�{��)�ƂňႤ�B
�@   �������Amazon�{�Ƃɂ��������A�{�ƃR�[�h�C�����K�v�B��
�@
�@\rx65n_rsk_aws\src\amazon-freertos-master\lib
�@ \FreeRTOS-Plus-TCP\include
�@ �@Amazon FreeRTOS v1.2.2�̍ŐV�R�[�h�ɒu�������B
�@
�@\rx65n_rsk_aws\src\amazon-freertos-master\lib
�@ \FreeRTOS-Plus-TCP\source
�@ �@Amazon FreeRTOS v1.2.2�̍ŐV�R�[�h�ɒu�������B
�@
�@\rx65n_rsk_aws\src\amazon-freertos-master\lib
�@ \FreeRTOS-Plus-TCP\source\portable\BufferManagement
�@ �@Amazon FreeRTOS v1.2.2�̍ŐV�R�[�h�ɒu�������B
�@ �@�@BufferAllocation_2.c ���啝�ɕς���Ă���B�v���ӁB���ƂŒ��ׂ�B��
�@ �@�@
�@\rx65n_rsk_aws\src\amazon-freertos-master\lib
�@ \FreeRTOS-Plus-TCP\source\portable\Compiler\Renesas
�@ �@Amazon FreeRTOS v1.2.2�̍ŐV�R�[�h�ɒu�������B
�@ �@�\���� pack �̒����R�[�h�B
�@   �������Amazon�{�Ƃɂ��������A�{�ƃR�[�h�C�����K�v�B��
�@
�@\rx65n_rsk_aws\src\amazon-freertos-master\lib
�@ \FreeRTOS-Plus-TCP\source\protocols
�@ �@Amazon FreeRTOS v1.2.2�̍ŐV�R�[�h�ɒu�������B
�@
�@�����܂łŖ{�� v1.2.2��{���Ƀ}�[�W�����B
�@�V�F���e�B�̊J���T�[�o�ɃR�~�b�g����B(r5129)
�@
�@RX65N Envision Kit�̊��������e����B
�@�@RX65N Envision Kit�̂ق���DHCP�̍ŏ���1��ڂ̃p�P�b�g�����ς�炸�R�P�Ă���B
�@�@DHCP�̍đ���҂���DHCP�������Ă���łȂ��ƃf���A�v����MQTT�ʐM��
�@�@���s����̂ŁArx65n_envision_kit_aws.c �ɂ�����DEMO_RUNNER_RunDemos()��
�@�@�Ăяo���܂ł̃E�F�C�g��2�b����10�b�ɕύX�B
�@�V�F���e�B�̊J���T�[�o�ɃR�~�b�g����B(r5130)
�@

--------------------------------------------------------------------------
2018/03/03
�@rx65n_rsk_aws�Ŏ����J�n�B
�@�J�����̃R���p�C���o�[�W�����̕\�L���Ԉ���Ă����B�C���BV2.07��V2.08�B
�@
�@���l�T�XTCP/IP(T4)�̊֐��Q���g�p���Ă���ӏ��𐮔����āA
�@FreeRTOS+TCP����Ether�h���C�o�𒼐ڌĂяo���悤�ɉ��ǂ���B

�@�X�}�[�g�R���t�B�O���[�^�̐ݒ肩��Ar_sys_time_rx�Ar_t4_driver_rx�A
�@r_t4_rx���폜���A���̏�ԂŃR�[�h�������s���B

�@�r���h����B���l�T�XTCP/IP(T4)�Ɋ֘A����֐��Ăяo���ŃG���[�ɂȂ�͂��B

�@(�R���p�C���G���[1)
�@../src/rx65n_rsk_aws.c(15):E0520005:Could not open source file "r_sys_time_rx_if.h"
�@../src/rx65n_rsk_aws.c(17):E0520005:Could not open source file "r_t4_itcpip.h"

�@main()�t�߂ŌĂяo���Ă���T4�֘A�̃w�b�_�A�֐��Ăяo���A�ϐ������폜���Ă����B

�@<<�����܂łŃR���p�C���ʂ���>>

�@(�����N�G���[1)
�@E0562310:Undefined external symbol "_get_random_number" referenced in ".\src\amazon-freertos-master\lib\FreeRTOS-Plus-TCP\source\portable\NetworkInterface\RX\NetworkInterface.obj"
�@E0562310:Undefined external symbol "_lan_read" referenced in ".\src\amazon-freertos-master\lib\FreeRTOS-Plus-TCP\source\portable\NetworkInterface\RX\NetworkInterface.obj"
�@E0562310:Undefined external symbol "_rcv_buff_release" referenced in ".\src\amazon-freertos-master\lib\FreeRTOS-Plus-TCP\source\portable\NetworkInterface\RX\NetworkInterface.obj"
�@E0562310:Undefined external symbol "_lan_open" referenced in ".\src\amazon-freertos-master\lib\FreeRTOS-Plus-TCP\source\portable\NetworkInterface\RX\NetworkInterface.obj"
�@E0562310:Undefined external symbol "_lan_write" referenced in ".\src\amazon-freertos-master\lib\FreeRTOS-Plus-TCP\source\portable\NetworkInterface\RX\NetworkInterface.obj"

�@�����܂łŁANetworkInterface.c�̎����݂̂ɍi��ꂽ�B
�@�_���ʂ�T4�֘A��API�Ăяo�������ɂȂ��Ă���B
�@��t4_driver.c ����֐��̒��g�������Ă���B
�@�@UB�Ƃ�UH�Ƃ���ITRON�̃f�[�^�^��`�́Auint8_t�Ƃ�uint16_t�Ƃ��̕W���^�ɒu��������B
�@�@
�@FreeRTOS_IPInit()�Őݒ肳���MAC�A�h���X�́ATCP/IP����RAM�ɕێ�����镪��
�@Ether�h���C�o�o�R(R_ETHER_Open_ZC2())��MAC�̃��W�X�^�ɕێ�����镪�Ɠ����l��
�@����K�v������BFreeRTOS_IPInit()�Őݒ肵�����Ƃ́A�ǂ����̕ϐ��ɕێ�����Ă��邩��
�@�����NetworkInterface.c�Ɉ����n���K�v�����邪�AxNetworkInterfaceInitialise()�ɂ�
�@�����n����Ă��Ȃ��B
�@ST�̃T���v��������ƁAucMACAddress[]�Ƃ����O���[�o���ϐ��Ŏ󂯓n�������Ă���B���܂����B
�@���߂āAFreeRTOSConfig.h�ɂ���R���t�B�O�l��匳�Ƃ��AFreeRTOS_IPInit()��
�@MAC�w�ɕ��z���Ă�����ׂ��ł��낤�B(FreeRTOSIPConfig.h�ł͂Ȃ��̂��H��������܂����j
�@
�@�����܂ł̉����ŁAr_sys_time_rx�Ar_t4_driver_rx�Ar_t4_rx���폜���A����m�F��OK�B
�@rx65n_envision_kit_aws�������������{������m�FOK�B

�@�����܂łŃR�~�b�g�B(r5091)
�@
�@NetworkInterface.c �ɍēx���ځB�ۑ�̐����B�ߋ��̉ۑ聚�̂���NetworkInterface.c�̂��̂��T���x�[�W�B
�@(1)�Ȃ��� lan_write()��-5��Ԃ��B���ƂŊm�F����B��
�@(2)�[���R�s�[�̊T�O�𖳎����邪...��
�@(3)�����Ether���荞�݋쓮�ɕK�������B
�@(4)(���M���̃[���R�s�[�̎d�g�݂��s���B������܂���Œ��ׂ遚)
�@(5)LAN�P�[�u���}���̃C�x���g��TCP/IP���ɒʒm����d�g�݂����邪...��

�@(1)�Ȃ��� lan_write()��-5��Ԃ��B���ƂŊm�F����B��
�@�@Ether�h���C�o�̃����N��Ԃ�\���ϐ��utransfer_enable_flag�v��ON�ɂȂ��Ă��炸
�@�@�ŏ���1�񂾂�lan_write()��-5��Ԃ��Ă���悤���B
�@�@��xNetworkInterfaceInitialise()����������Ether�̃����N�A�b�v���������Ă���Ƃ�����Ȃ��̂ŁA
�@�@�@���炩FreeRTOS+TCP�Ƀ����N�A�b�v/�_�E����ʒm����d�|��������Ǝv�����A�������炸�B
�@�@�@xNetworkInterfaceInitialise()�����������烊���N�A�b�v�͊������Ă���O��Ƃ���B
�@�@�@
�@�@�@R_ETHER_CheckLink_ZC()�Ń����N�`�F�b�N������͎̂�������PHY�̏�Ԃł���A
�@�@�@MAC(Ether�h���C�o)�������������Ă���Ƃ͌���Ȃ��B
�@�@�@�Ȃ̂�Ether�h���C�o����̏��������̃R�[���o�b�N(callback_link_on())�����Ă���
�@�@�@xNetworkInterfaceInitialise()���ɐi�߂�悤�ɂ���B
�@�@�@callback_link_on()������ƁAlink_detect��ETHER_FLAG_ON_LINK_ON�ɂȂ�̂ł���ő҂B
�@�@�@
�@�@�@�ȏォ��AxNetworkInterfaceInitialise()�̗���𐮗�����B
�@�@�@
�@�@�@�����O�F
�@�@�@�@(1)lan_open() (MAC/PHY�̏������A�I�[�g�l�S�V�G�[�V�����J�n)
�@�@�@�@(2)R_ETHER_CheckLink_ZC()�@PHY�����N�A�b�v�����҂�
�@�@�@�@(3)�\�t�g�E�F�A���[�v�@���K����
�@�@�@�@(4)��M�^�X�N�J�n
�@�@�@�@(5)MAC�w�����N�`�F�b�N�J�n
�@�@�@�@(6)xNetworkInterfaceInitialise()�I����DHCP���M��xNetworkInterfaceOutput()���s�i�܂�MAC�w�����������ĂȂ��j
�@�@�@�@�@�@��DHCP�^�C���A�E�g��DHCP�đ���xNetworkInterfaceOutput()����

�@�@�@������F
�@�@�@�@(1)lan_open() (MAC/PHY�̏������A�I�[�g�l�S�V�G�[�V�����J�n)
�@�@�@�@(2)MAC�w�����N�`�F�b�N�J�n
�@�@�@�@(3)MAC�w�����N�����҂�
�@�@�@�@(4)��M�^�X�N�J�n
�@�@�@�@(5)xNetworkInterfaceInitialise()�I����DHCP���M��xNetworkInterfaceOutput()����
�@�@�@�@�@�@�܂����؂��ł͂Ȃ��āA���쒆��LAN�P�[�u����
�@�@�@�@�@�@�������肳�������肷�铮��ɑΉ��ł��ĂȂ��B(�����}���j
�@�@�@�@�@�@�����_�ŁALAN�P�[�u���̑}���ɉ�����Ether�h���C�o�̓R�[���o�b�N�ł��邪�A
�@�@�@�@�@�@�����FreeRTOS+TCP�ɒʒm�����i���Ȃ��B
�@�@�@�@�@�@xSendEventStructToIPTask()�Œʒm�ł���悤�ȋC������̂Ō�Œ��ׂ�B
�@�@�@�@�@�@(5)�ɂ��Ƃ͔C���āA(1)�Ƃ��Ă͊����B
�@�@�@�@�@�@
�@(2)�[���R�s�[�̊T�O�𖳎����邪...��
�@�@����񂵁B
�@(3)�����Ether���荞�݋쓮�ɕK�������B
�@�@receive_check()�^�X�N��vTaskDelay()�ŉ������Ă���Ƃ�����T���v�����l�ɁAulTaskNotifyTake();���g�p����B
�@�@Ether���荞�݂�lan_inthdr()�ɓ�������̂ŁA������vTaskNotifyGiveFromISR()���g����
�@�@receive_check()�^�X�N�ɃC�x���g�ʒm����B
�@�@�������Ŏ��s���Ă݂邪�Atask.c��vTaskNotifyGiveFromISR()�̎��s����Assert�����s����ăt���[�Y���Ă��܂��B
�@�@�@���荞�݂���^�X�N�ɒʒm����̂͂�͂�Z���V�e�B�u�Ȃ悤���BOS�̋@�\�ɂ��Ē��ׂ�K�v������B
�@�@�@��task.c��vTaskNotifyGiveFromISR()��4799�s�ڂ�Assert�Ɏ~�܂��Ă���B
�@�@�@�@��ether_receive_check_task_handle�������������O�ɁAvTaskNotifyGiveFromISR()���Ă�ł��܂��Ă����B
�@�@�@�@�@��ether_receive_check_task_handle�ɒl�������Ă�����vTaskNotifyGiveFromISR���Ă�if����ǉ��B
�@�@�@�@�@�@��task.c��vTaskNotifyGiveFromISR()��4817�s�ڂ�portASSERT_IF_INTERRUPT_PRIORITY_INVALID()�Ńt���[�Y���Ă��܂��B
�@�@�@�@�@�@�@��portASSERT_IF_INTERRUPT_PRIORITY_INVALID()�𒲂ׂĂ݂�ƈȉ��̒ʂ�B
�@�@�@�@�@�@�@�@���݂�IPL��configMAX_SYSCALL_INTERRUPT_PRIORITY��菬������ASSERT�ƂȂ�悤���B
�@�@�@�@�@�@�@	#define portASSERT_IF_INTERRUPT_PRIORITY_INVALID() configASSERT( ( get_ipl() <= configMAX_SYSCALL_INTERRUPT_PRIORITY ) )
�@�@�@�@�@�@�@	��lan_inthdr()���s����get_ipl()���Ăяo����IPL�l������ƁA7�ƂȂ��Ă���B
�@�@�@�@�@�@�@	�@configMAX_SYSCALL_INTERRUPT_PRIORITY�̒l��6�������BconfigMAX_SYSCALL_INTERRUPT_PRIORITY��7�ɕύX�B
�@�@�@�@�@�@�@	�@�������܂ł̐ݒ�ŁA����OK�ƂȂ����Bping����������܂ōő�10ms�̃W�b�^�[�����������A
�@�@�@�@�@�@�@	�@�@Ether���荞�݂�FreeRTOS+TCP���q�����������ŁA���1ms�ȓ��ɉ�������悤�ɂȂ����B�����B
�@(4)(���M���̃[���R�s�[�̎d�g�݂��s���B������܂���Œ��ׂ遚)
�@�@����񂵁B
�@(5)LAN�P�[�u���}���̃C�x���g��TCP/IP���ɒʒm����d�g�݂����邪...��
�@�@���ۑ�Ƃ��Ă�(1)�Ɠ����B

�@�c�����ۑ�͈ȉ��B�[���R�s�[�Ɗ����}���ł���B
�@�@(2)�[���R�s�[�̊T�O�𖳎����邪...��
�@�@(4)(���M���̃[���R�s�[�̎d�g�݂��s���B������܂���Œ��ׂ遚)
�@�@(5)LAN�P�[�u���}���̃C�x���g��TCP/IP���ɒʒm����d�g�݂����邪...��

�@�����܂ł�Envision Kit��RSK�̃R�[�h�𓯊���������m�F���A��U�R�~�b�g����B(r5092)

�@�����āA�[���R�s�[�Ƀg���C���Ă݂�B
�@�@BufferAllocation_2.c���r���h���珜�O���ABufferAllocation_1.c ��L���ɂ���B
�@�@BufferAllocation_1.c���g�p����Ƃ��� vNetworkInterfaceAllocateRAMToBuffers() �͉��ƂȂ��������Ă���̂�
�@�@�r���h�͒ʂ�B���A�\�z�ʂ�A�G���[���b�Z�[�W��"INVALID BUFFER"�Ƃł�B
�@�@���̂Ƃ���vNetworkInterfaceAllocateRAMToBuffers()�̌��H���Ă����Ă݂�B

�@�@2/18�ɒ����������ɂ��ǂ蒅�����AFreeRTOS_IP.c��917�s�ڂ̕��򂪔Ɛl�B
�@�@�A���C�����g�����ĂȂ��B
�@�@
�@�@�������N���A���邽�߂ɂ́A
�@�@�[���R�s�[�Ή����邽�߂�second sample�Ƃ����̂��n�ǂ���K�v������B
�@�@https://www.freertos.org/FreeRTOS-Plus/FreeRTOS_Plus_TCP/Embedded_Ethernet_Porting.html#creating_a_zero_copy_network_port_layer

�@�@���ƂȂ������������A�������Ԃ������肻�����B���T�Ɏ������݁B
�@�@
--------------------------------------------------------------------------
2018/02/24
�@rx65n_rsk_aws�Ŏ����J�n�B
�@�|�[�e�B���O�K�C�h�����Ă�����x�����m�F�B
�@BufferAllocation_2.c�ŊȈՓI�Ɏ������邱�Ƃɂ����̂ŁA
�@first example�Ƃ����̂��������Ă݂�B
�@https://www.freertos.org/FreeRTOS-Plus/FreeRTOS_Plus_TCP/Embedded_Ethernet_Porting.html#creating_a_simple_network_interface_port_layer

�@xNetworkInterfaceInitialise()�̍\���͓��ɖ��Ȃ������B
�@xNetworkInterfaceOutput()�̎����́A���M�f�B�X�N���v�^�̊J���������Ă����B
�@�@�����M������ɁAvReleaseNetworkBufferAndDescriptor( pxDescriptor );��ǉ�
�@
�@���̎�M���ł��邪�ANOTE1��BufferAllocation_2.c���g�p����ꍇ��
�@���荞�݂̍Œ���discriptor��Ethernet buffers�̊��蓖�Ă��s���Ȃ��A
�@�Ə����Ă������B���̂��߁A�^�X�N��1�����グ�Ă����Ŏ�M���荞�݂���
�@�ʒm���󂯂���o�b�t�@���蓖�Ă��s���AIP�^�X�N�ɒʒm���s���Ƃ̂��ƁB
�@�����Deferrd Interrupt Handling�Ƃ����Ĉȉ��ɉ��������B
�@https://www.freertos.org/deferred_interrupt_processing.html
�@
�@����̓n�[�h�E�F�A���璼�ڌĂяo����銄�荞�݊֐��ł�
�@���荞�ݗv���̋L�^��OS�w�ւ̒ʒm�݂̂����{���A���₩�Ɋ��荞�݊֐���
�@�I�������邽�߂̃��J�j�Y���B
�@#OS�����݂��Ȃ��ꍇ�́A���荞�݃R���g���[���ɗD��x��ݒ肵��
�@ ���d���荞�݂��������@�ŏ��؂邪�A
�@ ���̎d�g�݂̓}�C�R���̎d�g�݂Ɉˑ�����B
�@ 
�@���荞�݊֐�����̒ʒm�́Adeferred interrupt handler task�Ƃ����̂�
�@���������B���̃^�X�N�͒ʏ�̃A�v���P�[�V�����^�X�N���D��x�������B
�@
�@When to use deferred interrupt handling�F
�@���̃��J�j�Y���͈ȉ�3�_�̂悤�ȃP�[�X�ɈЗ͂𔭊�����B
�@�E���荞�ݐM���ɉ����Ē����������K�v
�@�E���荞�ݏ������ŃN���e�B�J���ȏ��������͂Ŋ��S�Ɏ�������̂�����Ɗ�����ꍇ
�@�@(RTOS���񋟂���API�݂̂ō\�z�����ق����ȒP�E���S�ł��낤)
�@�E���܂肫������������Ȃ�������������ꍇ
�@�@�i���炩�̏����ɂ�菈�����Ԃ��L�яk�݂���ꍇ�j
�@�@
�@��Ether�̎�M�����͂܂��ɏ�L�P�[�X�ɊY������B
�@
�@Techniques for deferring interrupt processing to a task�F
�@�������@�͈ȉ�2�ʂ�Ƃ̂��ƁB
�@�@�@1�̃^�X�N�ŏW���Ǘ�����i���Ƃ��΃^�C�}�[�^�X�N�j
�@�@�u���荞�ݔ������t���OON���^�C�}�[�^�X�N�N����deferred interrupt�ŏ����v
�@�@�A�A�v�����R���g���[������iTask Notification���g�p�j
�@�@�u���荞�ݔ�����Noticication��deferred interrupt�ŏ����v
�@�@
�@�@�A�̗��_�͊��荞�ݔ������珈�����s�܂ł̃��C�e���V������A�Ƃ̂��ƁB
�@
�@�|�[�e�B���O�K�C�h��prvEMACDeferredInterruptHandlerTask()�̃T���v����
�@�A���g���Ă���悤���B�A���g���Ď������Ă݂�B
�@
�@Ether���Ď����Ė������[�v����^�X�N�����Breceive_check()�����̃^�X�N�Ƃ���B
�@
�@Ether�֘A�̏��������s��xNetworkInterfaceInitialise()�Ń^�X�N�����΂悢�ł��낤�B
�@xTaskCreate()�Ń^�X�N�n���h�������Areceive_check()��o�^����B
	return_code = xTaskCreate(receive_check, "ETHER_RECEIVE_CHECK_TASK", 100/* stack size (word) */, 0,  configMAX_PRIORITIES, &ether_receive_check_task_handle);
	if(return_code == xTaskCreate)
	{
        	/* The task was created.  Use the task's handle to delete the task. */
        	vTaskDelete( ether_receive_check_task_handle );
	}


�@����ɔ����Acheck_ether_link()��receive_check()�����s���Ă����̂���߂�B
�@����ŁANotify�Ŏ�M�C�x���g���󂯂�̂ł͂Ȃ��āA
�@vTaskDelay()��10ms��1��|�[�����O����ȈՎ����ɂ���B
�@
�@���łɁAxNetworkInterfaceInitialise()�Ń^�C�}�[�^�X�N������Ă݂�B
�@���́AR_CMT_CreatePeriodic()�Ŋ��荞�݊֐������I�ɌĂяo���Ă���Ƃ����
�@�^�C�}�[�^�X�N�ɒu��������B
�@https://www.freertos.org/FreeRTOS-timers-xTimerCreate.html
�@
�@xTimerCreate()�Ń^�C�}�[�n���h��������āA�����xTimerStart()�ɓ��͂��銴�����B
�@
�@timer_handle = xTimerCreate("ETHER_TIMER", 10, pdTRUE, &timer_id, check_ether_link);
�@xTimerStart(timer_handle, 0);
�@
�@�Ƃ������Ƃ��납�B����`�̕ϐ��̓O���[�o���Œ�`���Ă����B
�@����ŁAreceive_check()��FreeRTOS�z���̃^�X�N�Ƃ��ČĂяo���ꂽ�B
�@
�@�|�[�e�B���O�K�C�h��prvEMACDeferredInterruptHandlerTask()�̃T���v���ɏ]����
�@API�Ăяo���������m���߂Ă����B
�@
�@�E  ulTaskNotifyTake()
�@�@������͏�L�u�A�A�v�����R���g���[������v�ꍇ�ɕK�v�ȃC�x���g�ʒm��t���B
�@�@�@�����vTaskDelay()���g���ĉ������Ă���̂ŕs�v�B
�@�E pxGetNetworkBufferWithDescriptor( xBytesReceived, 0 );
�@�@����M�f�[�^���ɉ������o�b�t�@���m�ۂ��āA�f�B�X�N���v�^�𐶐����Ė߂�l��
�@�@�@�Ԃ��Ă����API�B
�@�@�@RX�}�C�R����Ether�R���g���[���h���C�o�́Alan_read()�̖߂�l�Ŏ�M�f�[�^����
�@�@�@�߂��Ă����Breceived_data_size�ɓ���Ă����B
�@�@�@�܂��A�����̃|�C���^�ɁA�o�b�t�@�|�C���^�������Ă����B
�@�@�@memcpy()�ŃR�s�[�����FreeRTOS+TCP���̃o�b�t�@�ɃR�s�[����΂悢�ł��낤�B
�@�@�@�i���ƂŃ[���R�s�[�Ή��ɐi��������j
�@�E�f�B�X�N���v�^�ւ̃f�[�^�ݒ�A�C�x���g�ʒm�p�̍\���̂̐ݒ�A���ɖ��Ȃ�����
�@				pxBufferDescriptor->xDataLength = received_data_size;
				xRxEvent.eEventType = eNetworkRxEvent;
				xRxEvent.pvData = pxBufferDescriptor;

�@���s���Ċm�F���Ă݂���A��͂�pxGetNetworkBufferWithDescriptor()������I�����Ȃ��B
�@pxGetNetworkBufferWithDescriptor()�ɐ����čĊm�F���Ă����B
�@
�@�Ȃ񂩃Z�}�t�H���������ĂȂ��l�q�H
�@���M��xNetworkInterfaceOutput()�Ńf�B�X�N���v�^���m�ۂ��đ��M���������Ƃ���
�@�����[�X�o�b�t�@��API���Ă�ł���͂������E�E�E�H
�@
�@�Ȃ���lan_write()�����M�������Ă���̂�-5��Ԃ��Ă��āAif�����U�ɂȂ��Ă����B
�@�b��ŋU�̂Ƃ��������[�X�o�b�t�@���ĂԂ悤�ɂ����B
�@
�@	return_code = lan_write(0, tmp_buf, 14, tmp_buf + 14, pxNetworkBuffer->xDataLength - 14);
	if(return_code > 0)
	{
		/* Call the standard trace macro to log the send event. */
		iptraceNETWORK_INTERFACE_TRANSMIT();

		vReleaseNetworkBufferAndDescriptor(pxNetworkBuffer);
	}
	else
	{
		/* �Ȃ��� lan_write()��-5��Ԃ��B���ƂŊm�F����B�� */
		vReleaseNetworkBufferAndDescriptor(pxNetworkBuffer);
	}
	
�@�����܂ł̎�����DHCP�V�[�P���X����������悤�ɂȂ����B
�@ping�������ł��Ă���B����FreeRTOS+TCP�̈ڐA�����I�I�I�I
�@�i���ۑ�R����ł����j
�@
�@RSK�œ���m�F���Ă����̂ŁAEnvision Kit���ɂ��l�b�g���[�N�C���^�t�F�[�X�̃R�[�h��
�@�o�^���ăR�~�b�g�B(r5066)
�@
--------------------------------------------------------------------------
2018/02/18
�@rx65n_envision_kit�ō�ƊJ�n�B
�@
�@�ǂ��ɂ��f�o�b�K���d�����BFreeRTOS�p�̃X�^�b�N(FreeRTOSConfig.h�Őݒ�)��
�@����Ă��Ȃ��悤�ȋC������BFreeRTOS���V�X�e���X�^�b�N���ɉe�����Ă��邩�H

�@���݂�RX65N��RAM�g�p�󋵂�ύX���Ă݂�B
�@���GUI���ڂ����Ƃ��Ƀ`�����h�~�̂��߃_�u���o�b�t�@�ɂ������������v�����Ȃ��B

�@0x00000000�Ԓn(256KB)�F�t���o�b�t�@1
�@0x00800000�Ԓn(256KB)�F�t���o�b�t�@2
�@0x00840000�Ԓn(128KB)�F�V�X�e���̈�
�@��
�@0x00000000�Ԓn(256KB)�F�V�X�e���̈�(B�Z�N�V����(FreeRTOS�X�^�b�N�A�q�[�v�A���̑��ϐ���))
�@0x00800000�Ԓn(256KB)�F�t���o�b�t�@2
�@0x00840000�Ԓn(128KB)�F�V�X�e���̈�(B�Z�N�V�����ȊO(�V�X�e���X�^�b�N��Ether�o�b�t�@��))

�@����ŁA�f�o�b�K�d�������ۂ����P���ꂽ�B
�@main()���[�v��vTaskDelay(10000);�����Ė������[�v�����A
�@main()���[�v�������Ă邩�m�F���郁�b�Z�[�W���o�͂���悤�ɂ����B
�@
�@����ғ����Ă���悤���B�������܂�DHCP Discover�p�P�b�g��
�@�o�͂��邽�߂̑��M�֐�xNetworkInterfaceOutput()�͌Ă΂�Ȃ��悤���B

�@���������I��FreeRTOS��FreeRTOS+TCP����͓�̃��O(�����������Ă���H)�͏o�͂���Ă���B(�����ׂ�)��OK
�@�����X�e�[�g�}�V���͓��������Ă���l�q���B

�@�ЂƂ܂����肵���̂ŁA��������R�~�b�g����B(r5008)

�@���b�Z�[�W�̕��������̌����͂����ƁA#include <stdio.h> ���������炾�B
�@FreeRTOS�{�̂̃R�[�h�ŃC���N���[�h����킯�ɂ������Ȃ����A�K���R���t�B�O�t�@�C����
�@���[�U��`�����ɓf���o����Ă���i�D�Ȃ̂ł������#include <stdio.h>��ǉ��B
�@\rx65n_envision_kit_aws\src\amazon-freertos-master\demos\renesas\rx65n_envision_kit\common\config_files
�@�@FreeRTOSConfig.h
�@�@FreeRTOSIPConfig.h

�@�������AFreeRTOS��FreeRTOS+TCP�̃V�X�e�����O�������悤�ɂȂ����B
�@�@�G���[���̃g���[�X���O��������݂����Ȃ̂ŁA���Ƃł�����o�͂Ɍq���ł݂悤�B
�@�@�t���\�������₩�ɂȂ��Ă����B
�@�@�o�b�N���O��������悤�ɁAUART�ł��o�͂����ق����悢�B
�@�@RSK�͕W����UART��USB�V���A���ϊ������USB����o�Ă��邪�A
�@�@Envision Kit�͂��̎d�|�����Ȃ��B�iE2OB�̋@�\�̓f�o�b�K�g�p����UART�o�͂ł��Ȃ��̂ŋp���j
�@�@Envision Kit��PMOD��SCI2���z������Ă��āAPMOD���W���[����USB�V���A���ϊ������邩��
�@�@�����t�����UART��USB����o����B�i�O�Ɏ����Ă����Ƃł����j
�@�@�@��https://store.digilentinc.com/pmod-usbuart-usb-to-uart-interface/
�@�@�@�@�������Envision Kit��CH14��1-6�ɑ}���΂悢�B
�@�@�@�@�@SCI2��UART���[�h�Ŏg�p�����PC�ɃV�X�e�����O�𑗂��B
�@�@�@�@�@�R�[�h�ł����ƁAlcd_conf.h�� my_sw_charput_function()��printf()�o�RBSP����Ă΂�邪�A
�@�@�@�@�@���͂����ɉt����1�����o�͂���悤�ɂ��Ă���Ƃ��낪����A�����ɕ��s����SCI����o�͂���
�@�@�@�@�@�悤�ɃR�[�h�ǉ�����΂悢�B(����Ń����e)

�@���ĉt���\���̃V�X�e�����O�����ł�������x�����N���Ă��邩������悤�ɂȂ����B
�@�V�X�e�����O���e��R�����Ă݂�B
�@�@���Ă̒�ADHCP discover�v���Z�X���A�������Ȃ��ă^�C���A�E�g���āA���g���C������������Ă���B
�@
�@�f�B�X�N���v�^��4�ݒ�ɂ����̂ɁA(now59)�Ƃ��\������Ă�̂ŁA�f�B�X�N���v�^����̒�����
�@���炩����ĂȂ��悤���B�����������M�֐�(xNetworkInterfaceOutput())����Ă΂�ĂȂ��̂ŁA
�@���M�����̍ŏ��̕��ł����Ă����B
�@�m������AFreeRTOSIPConfig.h��60��Ether�h���C�o���̒�`ETHER_CFG_EMAC_TX_DESCRIPTORS�i���g��4)��
�@�ǂݍ��ނ悤�ɂ����͂������E�E�E�H
�@
�@FreeRTOSIPConfig.h���m�F�����炢�̊Ԃɂ��f�t�H���g��60�ɖ߂��Ă��B
�@�K�`���K�`������Ăăf�t�H���g�ŏ㏑�����Ă��܂����悤���B������x�C���B
�@
�@���Ғʂ�(now59)�̕\����(now3)�ƂȂ����B�ˑR�Ƃ���xNetworkInterfaceOutput()�͌Ă΂�Ȃ��B
�@�����������Ƃ��Ă��邩�B
�@
�@FreeRTOS+TCP��IP�w�̎���(FreeRTOS_TCP_IP.c)���m�F���Ă����B
�@xNetworkInterfaceOutput()���Ăяo���Ă���̂�950�s��1�����̂݁B
�@�R�����g�� /* Send! */ �Ə����ėL���ċC���������Ă���̂ŊԈႢ�Ȃ����낤�B
�@
�@���̌Ăяo�����̎����́AprvTCPReturnPacket()�B���̊֐��̐擪�Ƀu���[�N��
�@����������A�����Ȃ��B��ʂɏ���Ă����B
�@
�@FreeRTOS_TCP_IP.c �̎����Ɋ֐��Ăяo�������L�ڂ���Ă���B���肪�����B
�@prvTCPReturnPacket()���Ăяo���Ă���Ƃ����Ђ��[����u���[�N�\���ĖԂ��͂�B
�@prvTCPSendRepeated()�AprvTCPPrepareSend()�AprvTCPHandleState()�̐擪�Ƀu���[�N�͂�B
�@
 * IP-Task:
 *		xTCPTimerCheck()				// Check all sockets ( declared in FreeRTOS_Sockets.c )
 *		xTCPSocketCheck()				// Either send a delayed ACK or call prvTCPSendPacket()
 *		prvTCPSendPacket()				// Either send a SYN or call prvTCPSendRepeated ( regular messages )
 *		prvTCPSendRepeated()			// Send at most 8 messages on a row
 *			prvTCPReturnPacket()		// Prepare for returning
 *			xNetworkInterfaceOutput()	// Sends data to the NIC ( declared in portable/NetworkInterface/xxx )
 
  *	xProcessReceivedTCPPacket()
 *		prvTCPHandleState()
 *			prvTCPPrepareSend()
 *				prvTCPReturnPacket()
 *				xNetworkInterfaceOutput()	// Sends data to the NIC
 *		prvTCPSendRepeated()
 *			prvTCPReturnPacket()		// Prepare for returning
 *			xNetworkInterfaceOutput()	// Sends data to the NIC
 
 
�@���ʁA�ǂ��ɂ��u���[�N���Ȃ��B
�@
�@��������IP�^�X�N�ɑ��M�v�����͂��ĂȂ��̂ł͂Ȃ����B
�@DHCP�v���Z�X����IP�^�X�N�ɑ��M�v�����o���������猩�����Ă݂�B
�@
�@DHCP�v���Z�X����IP�^�X�N�ɑ΂��鑗�M�v���́AFreeRTOS_DHCP.c��
�@926�s�ڂ�FreeRTOS_sendto()�Ǝv����B���̒����m�F���Ă����B
�@
�@�i��ł����ƁAFreeRTOS_Socket.c��855�s�ڂ�
�@pxUDPPayloadBuffer_to_NetworkBuffer()���Ă΂��B
�@�����܂ł̏����ɃG���[�Ȃǂ͔������Ă��Ȃ��l�q�B
�@
�@FreeRTOS_IP.c��917�s�ڂ̕���ɂ��ǂ蒅�����B
�@if( ( ( ( uint32_t ) pucBuffer ) & ( sizeof( pucBuffer ) - 1 ) ) == 0 )��
�@�U�ɂȂ邽�߁A�o�b�t�@�|�C���^���o�^���ꂸpxResult��NULL���Z�b�g����
�@�����Ă��܂��B���ꂪ�������B
�@
�@2/17�ɓK���Ɏ�������vNetworkInterfaceAllocateRAMToBuffers()���������B

�@��Lif()���̏������m�F����ƁA����瑗�M�o�b�t�@�̃A���C�����g��
�@���Ă��邩�ǂ������m�F���邽�߂̂��̗̂l�q�B
�@
�@���������߂��āAFreeRTOS_Socket.c��829�s�ڂ̏�������ňȉ�����B
�@if( ( xFlags & FREERTOS_ZERO_COPY ) == 0 )
�@
�@�����FREERTOS_ZERO_COPY��ON�̂ق��ɗ���Ă����Ă���̂������̂悤���B
�@�[���R�s�[�����͌�񂵂ɂ���ƌ��߂��̂ŁA�Ȃ�Ń[���R�s�[���L����
�@�Ȃ��Ă���̂����ׂ�B
�@
�@FreeRTOS_DHCP.c��926�s�ڂ��悭�݂�ƁAFREERTOS_ZERO_COPY�𒼐ڎw�肵�Ă����B
�@�Ƃ������Ƃ́ADHCP���g�p����Ƃ��̓[���R�s�[�K�{�Ƃ������ƁB
�@if( FreeRTOS_sendto( xDHCPData.xDHCPSocket, pucUDPPayloadBuffer, ( sizeof( DHCPMessage_t ) + xOptionsLength ), FREERTOS_ZERO_COPY, &xAddress, sizeof( xAddress ) ) == 0 )

�@DHCP�@�\�͂������ɐ؂邱�Ƃ͂ł��Ȃ��̂ŁA
�@��Ƀ[���R�s�[�̎������ς܂����ق����ǂ��������B
�@
�@Amazon FreeRTOS�S����ZERO_COPY��Grep�BPIC�̃T���v���Ɉȉ�2�s�𔭌��B
�@�����RX����FreeRTOSIPConfig.h�ɓ����B
�@#define ipconfigZERO_COPY_TX_DRIVER              ( 1 )
�@#define ipconfigZERO_COPY_RX_DRIVER              ( 1 )
�@
�@���ƁA#include "pack_struct_start.h"��#include "pack_struct_end.h"�ɋ��܂ꂽ�\���̂�
�@typedef�ɑ��R�[�h����̃V���{���Q��(Ctrl+���N���b�N)���ł����A�G���[�\���ɂȂ��Ă���B
�@�R���p�C���͒ʂ�̂ŃR���p�C���O�����̍\����͂ŃG���[�ɂȂ��Ă��銴���B
�@�����c�[���J������ɖ₢���킹�Ă݂�B
�@
�@�|���Ď茳�̎����B
�@FreeRTOS_IP.c��917�s�ڂ̕����������x���Ă݂�B���ꂪ�ʂ�Ȃ��Ɛ�ɐi�܂Ȃ��B
�@�@if( ( ( ( uint32_t ) pucBuffer ) & ( sizeof( pucBuffer ) - 1 ) ) == 0 )

�@�����ɍŏ��ɓ��B��������pucBuffer�̒l�́A0x84f716�B
�@���̒l���|�C���^�T�C�Y(4)����1���������l�Ń}�X�N�����
�@�������c������i��4�o�C�g�A���C�����g���ĂȂ���΁j�U�B
�@0x84f716��4�̔{���ɂȂ��Ă��Ȃ���Βʂ�Ȃ��Ƃ������ƁB
�@���̃P�[�X����4�̔{���ɂȂ��ĂȂ��̂Œʂ�Ȃ��B
�@
�@���̒l���ǂ����痈�Ă��邩�Ƃ����ƁA
�@FreeRTOS_DHCP.c��926�s�ڂ�pucUDPPayloadBuffer�ł���B
�@���̃|�C���^�́A921�s�ڂ�prvCreatePartDHCPMessage()�ŏo�͂����B���̒��g��T��B
�@�o�b�t�@�̈�́AFreeRTOS_GetUDPPayloadBuffer()�Ŏ擾����悤���B���̒��g��T��B

�@���̃o�b�t�@�̈�́ABufferAllocation_1.c���犄�蓖�Ă��Ă���l�q�Ȃ̂ŁA
�@BufferAllocation_1.c ���r���h���珜�O�ABufferAllocation_2.c���r���h�ΏۂƂ���B
�@BufferAllocation_2.c �̓[���R�s�[�p�̃��������蓖�ċ@�\���B
�@
�@�����܂ł̎����ŁAxNetworkInterfaceOutput()�ɑ��M�f�[�^�������n�����悤�ɂȂ����B

�@�Ȃ��A����M�o�b�t�@�̎�舵���͗v���ӂ��B
�@FreeRTOSIPConfig.h �ɁA ipconfigPACKET_FILLER_SIZE�Ƃ����}�N����2�Őݒ肳��Ă���B
�@����́AEther�p�P�b�g���ȉ��\���ɂȂ��Ă��āAIP�w�b�_�ȍ~��32�r�b�g�A���C�����g���Ă��Ȃ�
�@���ɋN������B����͐��E���ʂ̖��ł���A�ʏ�MAC�w��Ether�w�b�_��IP�w�b�_�̊Ԃ�2�o�C�g
�@�p�f�B���O�����ݍ���ŉ������Ă���B�i���邢�̓f�[�^���R�s�[���Ȃ������艽�炩�̃y�i���e�B��w�����Ď����j
�@RX�}�C�R����EtherMAC�͍K�����̃p�f�B���O�@�\�������Ă���̂Ń\�t�g����ŏ��ɉ����ł���͂��B
�@
�@Ether�p�P�b�g�\��
�@[ETHER_HEADER(14 byte)][IP_HEADER(20 byte)][TCP_HEADER(20 byte)][PAYLOAD(0-1460 byte)]
�@�����ۂɃn�[�h�E�F�A����M�f�[�^���������W�J�����
�@[ETHER_HEADER(14 byte)][IP_HEADER(20 byte)][TCP_HEADER(20 byte)][PAYLOAD(0-1460 byte)]�E�E�E�H�v����
�@[ETHER_HEADER(14 byte)][pad(2 byte)][IP_HEADER(20 byte)][TCP_HEADER(20 byte)][PAYLOAD(0-1460 byte)]�E�E�E�H�v�L��
�@
�@�ЂƂ܂�����̍\���łǂ̂悤�ɂ��̕ӂ肪���߂���Ă��邩�m�F���A���M���̎�����i�߂Ă����B
�@
�@�P����xNetworkInterfaceOutput()�ɓn���Ă����f�[�^��
�@t4_driver.c�������Ă��� lan_write() �֐��Ɉ����n���Ă݂�B
�@
�@�[���R�s�[�̊T�O�𖳎����邪�A���Ԃ�AxNetworkInterfaceOutput()�œn�����f�[�^��
�@Ether���M�o�b�t�@�̃|�C���^�ł��邽�߁A��������e���|�����Ɋi�[���Ă���
�@Ether�h���C�o�ɓn�����Ƃɂ���B�c�����܂��S�e��������Ȃ��̂Ŏd���Ȃ��B���ƂŕK�������B��
�@
�@�����܂łŁARX65N����ADHCP discover�p�P�b�g���o�͂ł���悤�ɂȂ����BWireshark�Ŋm�F�ρB
�@DHCP�T�[�o����DHCP offer�p�P�b�g���Ԃ��Ă����̂ŁA������DHCP discover�Ƃ��Ĉ���ꂽ�悤���B
�@RX65N���͂�����܂��󂯂����t���ĂȂ��̂ŁA����ȏ��DHCP�V�[�P���X�͐i��ł��Ȃ��B
�@
�@MAC�w�Ŏ�M�����EDMAC�]���͊������Ċ��荞�݂͔������Ă���̂ŁA
�@���̊��荞�݂��L���b�`����FreeRTOS+TCP���Ɏ�M���荞�݃C�x���g��`�������
�@���Ă��΂����͂����B
�@
�@�|�[�e�B���O�K�C�h�����Ă݂�B
�@xSendEventStructToIPTask()�Ŏ�M���荞�݃C�x���g��ʒm����΂����悤���B

�@���荞�݃C�x���g��t4_driver.c �� lan_inthdr()�܂ŏオ���Ă��Ă���͂�����
�@t4_driver.c �͍ŏI�I�ɂ͕s�v�Br_ether_rx��API�𒼐�NetworkInterface.c����
�@�Ăяo���Ă�����΂悢�B���͂Ƃ肠������Ether���荞�݂ł͂Ȃ��A
�@�����N��Ԃ����I�ɒ��ׂ� check_ether_link() �Ŏ�M�f�[�^���������ꍇ��
�@FreeRTOS+TCP��xSendEventStructToIPTask()���Ăяo���R�[�h��ǉ�����B
�@�����Ether���荞�݋쓮�ɕK�������B
�@
�@�������������A�ЂƂ܂���M�f�B�X�N���v�^�͐���ɉ�]���n�߂��B
�@��M���N�G�X�g���󂯎����FreeRTOS+TCP�́A�uCANNOT ADD 1�v�ƃ��b�Z�[�W��f���Ă���B
�@
�@��M������pxGetNetworkBufferWithDescriptor()�Ńo�b�t�@/�f�B�X�N���v�^���m�ۂ���
�@�f�B�X�N���v�^�Ƀo�b�t�@�|�C���^�Ǝ�M�f�[�^�������������xSendEventStructToIPTask()��
�@�n���Ηǂ��悤���B
�@
�@����x�A�|�[�e�B���O�K�C�h�̃o�b�t�@�Ǘ��̍����悭�ǂ�ł݂�B
�@https://www.freertos.org/FreeRTOS-Plus/FreeRTOS_Plus_TCP/Embedded_Ethernet_Buffer_Management.html
�@
�@BufferAllocation_1.c ��Ether�o�b�t�@���ÓI��Ether�h���C�o�����ɂ���ꍇ�A
�@BufferAllocation_2.c ��Ether�o�b�t�@�����I�Ƀq�[�v����m�ۂ����ꍇ�A�Ƃ���B

�@�[���R�s�[���g�����g��Ȃ����Ɗ��Ⴂ���Ă������A�����ł͂Ȃ������B
�@BufferAllocation_1.c ���g���悤�ɂ���B
�@
�@vNetworkInterfaceAllocateRAMToBuffers()�̎����̂͑��M�o�b�t�@�|�C���^��
�@�n���悤�ɂ��Ă������A��M�o�b�t�@�̃|�C���^��n���悤�ɕύX�����B
�@(���M���̃[���R�s�[�̎d�g�݂��s���B������܂���Œ��ׂ遚)
�@
�@BufferAllocation_1.c�ɕύX�������ƂŁA�f�B�X�N���v�^�̏����l�ɕs��������l�q�B
�@������M���N�G�X�g��xSendEventStructToIPTask()�Ŕ�΂��O��
�@pxGetNetworkBufferWithDescriptor()�����s����Ƃ��������Ȃ�B
�@vNetworkInterfaceAllocateRAMToBuffers()�̎������������K�v�����肻���B
�@
�@����Ƃ��Ă͈��肵�Ă���̂łЂƂ܂��R�~�b�g����B(r5009)
�@��������DHCP���M�͂ł��Ȃ��Ȃ��Ă���B�����炭�f�B�X�N���v�^�̕s���B
�@�@xNetworkInterfaceOutput()���Ă΂�Ă��Ȃ���ԁB
�@
�@rx65n_rsk ���ɃR�[�h�𔽉f�����B(r5010)
�@
�@�ЂƂ܂��ABufferAllocation_2.c���g�����Ƃɂ��āA
�@�S�̓�����m�F���邱�Ƃ�D�悷�邱�Ƃɂ���B
�@DHCP���M�܂ŏo���邱�Ƃ��m�F�B
�@��M�ɂ��Ă��C�x���g�ʒm��OS�w�܂œ͂��Ă��邪
�@�f�B�X�N���v�^���̎�M�o�b�t�@�|�C���^���ُ�l�Ȃ̂�
�@�f�[�^�̎󂯓n�����@�ɖ�肪����悤���B(r5011)

--------------------------------------------------------------------------
2018/02/17
�@rx65n_envision_kit�ō�ƊJ�n�B

�@NoMaY������̏���Amazon FreeRTOS�� 1.2.0 �Ƀo�[�W�����A�b�v����Ă���Ƃ̂��ƁB
�@1.2.0�̃R�[�h���_�E�����[�h���A�����m�F�B
�@NoMaY���̏��ʂ�AMQTT����̃Z�L�����e�B�������ǉ�����Ă���l�q�B
�@RX65N�ɈڐA�ς݂�FreeRTOS�{�̕����͓��ɉe���Ȃ��B
�@���|�W�g�����̃R�[�h��1.2.0�̂��̂ɒu�������Ă����B

�@���������΃o�[�W�����\�L�����ɂȂ�B"version"��Amazon FreeRTOS�S�̂�grep���Ă݂��B
�@Amazon FreeRTOS�S�̂��܂���o�[�W������`�͂܂��Ȃ��悤���B
�@Amazon FreeRTOS 1.2.0 �ɓ����\�t�g�̎�v�ȃo�[�W�����͈ȉ��̒ʂ�B
�@�E�A�v���Fv0.9.0
�@�@\amazon-freertos-master\demos\common\include\aws_application_version.h(29,13)  [SJIS]: #define APP_VERSION_MAJOR  0
�@�@\amazon-freertos-master\demos\common\include\aws_application_version.h(30,13)  [SJIS]: #define APP_VERSION_MINOR  9
�@�@\amazon-freertos-master\demos\common\include\aws_application_version.h(31,13)  [SJIS]: #define APP_VERSION_BUILD  0
�@�Embed TLS�Fv2.6.0
�@�@\amazon-freertos-master\lib\third_party\mbedtls\include\mbedtls\version.h(40,17)  [SJIS]: #define MBEDTLS_VERSION_MAJOR  2
�@�@\amazon-freertos-master\lib\third_party\mbedtls\include\mbedtls\version.h(41,17)  [SJIS]: #define MBEDTLS_VERSION_MINOR  6
�@�@\amazon-freertos-master\lib\third_party\mbedtls\include\mbedtls\version.h(42,17)  [SJIS]: #define MBEDTLS_VERSION_PATCH  0
�@�EPKCS11�Fv2.40.0
�@�@\amazon-freertos-master\lib\third_party\pkcs11\pkcs11t.h(14,18)  [SJIS]: #define CRYPTOKI_VERSION_MAJOR 2
�@�@\amazon-freertos-master\lib\third_party\pkcs11\pkcs11t.h(15,18)  [SJIS]: #define CRYPTOKI_VERSION_MINOR 40
�@�@\amazon-freertos-master\lib\third_party\pkcs11\pkcs11t.h(16,18)  [SJIS]: #define CRYPTOKI_VERSION_AMENDMENT 0
�@�EFreeRTOS�J�[�l���Fv10.0.1
�@�@\amazon-freertos-master\lib\include\task.h(46,19)  [SJIS]: #define tskKERNEL_VERSION_NUMBER "V10.0.1"
�@�@\amazon-freertos-master\lib\include\task.h(47,19)  [SJIS]: #define tskKERNEL_VERSION_MAJOR 10
�@�@\amazon-freertos-master\lib\include\task.h(48,19)  [SJIS]: #define tskKERNEL_VERSION_MINOR 0
�@�@\amazon-freertos-master\lib\include\task.h(49,19)  [SJIS]: #define tskKERNEL_VERSION_BUILD 1
�@�EFreeRTOS+TCP�F�����H

�@��Ƃɖ߂�B

�@�Ƃɂ����uFreeRTOS-Plus-TCP�v���v���W�F�N�g�o�^���Ă݂�B
�@�u\FreeRTOS-Plus-TCP\source\portable�v�Ƀf�o�C�X���̓Ǝ�������
�@�Ǝ��쐬����K�v������B�o�b�t�@�Ǘ��uBufferManagement�v�R���p�C������`�uCompiler�v
�@�l�b�g���[�N�w�uNetworkInterface�v��3��ނ�Ǝ��쐬���Ȃ���΂Ȃ�Ȃ��B

�@http://japan.renesasrulz.com/cafe_rene/f/forum21/4772/amazon-freertos-rx/26876#26876
�@��LURL��NoMaY���̐�s�����𓪂ɓ���Ȃ���A�R���p�C���J�n�B

�@(�R���p�C���G���[1)FreeRTOS+TCP�֘A�̃w�b�_�t�@�C��������Ȃ�
�@�@���u\amazon-freertos-master\lib\FreeRTOS-Plus-TCP\include�v�ɃC���N���[�h�p�X��ʂ�
�@(�R���p�C���G���[2)"FreeRTOSIPConfig.h"��������Ȃ�
�@�@���u\amazon-freertos-master\demos\vendor\board\common\�v�ɂ���悤���B
�@�@�@�x���_����BSP�̃R���t�B�O�ɓ����Ɨǂ��悤���B
�@�@�@�u\rx65n_envision_kit_aws\src\smc_gen\r_config�v�ɓ���Ă����B]
�@�@�@�@�����Ƃ� \amazon-freertos-master\demos\renesas\rx65n_envision_kit\common\config_files 
�@�@�@�@�@��FreeRTOS�̃R���t�B�O�����z���B������
�@(�R���p�C���G���[3)"pack_struct_start.h"��������Ȃ�
�@�@������́ATCP/IP�̃w�b�_��\���\���̂� pack �I�v�V������t���邽�߂�
�@�@�@�}���`�R�[�h�Ή��p�̃w�b�_�B
�@�@�@�u\rx65n_envision_kit_aws\src\FreeRTOS-Plus-TCP\source\portable\Compiler\Renesas�v�ɃC���N���[�h�p�X��ʂ�
�@(SH�p�R�[�h����������Ă���̂ŁARX�p�R�[�h�ɕύX/NoMaY���̐�s�����Q��)
�@�@��"pack_struct_start.h", "pack_struct_end.h"
�@(�R���p�C���G���[4)"FreeRTOS_HTTP_commands.h"��������Ȃ�
�@�@���u\rx65n_envision_kit_aws\src\FreeRTOS-Plus-TCP\source\protocols\include�v�ɂɃC���N���[�h�p�X��ʂ�
�@(�R���p�C���G���[5)"ff_stdio.h"��������Ȃ�
�@�@��"\rx65n_envision_kit_aws\src\FreeRTOS-Plus-TCP\source\protocols\HTTP\FreeRTOS_HTTP_server.c"
�@�@�@�G���[���͂��̃t�@�C���B
�@�@�@FTP�T�[�o�̃R�[�h����t�@�C���V�X�e���n�̃\�t�g���Ăяo����Ă���l�q�B
�@�@�@���͂܂�FTP�T�[�o�@�\�͗v��Ȃ��̂ŃR�[�h���̂��v���W�F�N�g���珜�O���Ă����B
�@�@�@TCP/IP�̏�ʂɂ�����v���g�R���Q�iHTTP��FTP��NTP�ƃT�[�o�ݒu�p�R�[�h�j�Ɋւ���ȉ��t�@�C�����v���W�F�N�g���珜�O�B
�@�@�@�EFreeRTOS_HTTP_server.c
�@�@�@�EFreeRTOS_HTTP_commands.c
�@�@�@�EFreeRTOS_FTP_server.c
�@�@�@�EFreeRTOS_FTP_commands.c
�@�@�@�EFreeRTOS_TCP_server.c
�@�@�@�ENTPDemo.c
�@�@(�R���p�C�����[�j���O1)
�@�@�@��pack�I�v�V��������̃��[�j���O�������ς��ł�̂ŁANoMaY���̐�s�������Q�l�ɏC���B
�@�@
�@�@<<�����܂łŃR���p�C���ʂ���>>
�@�@
�@�@(�����N�G���[1)
�@�@�@E0562300:Duplicate symbol "_uxGetMinimumFreeNetworkBuffers"
�@�@�@�@���o�b�t�@�Ǘ��uBufferManagement�v��2�����悤�ȃt�@�C���������Ă���̂������ł��낤�B
�@�@�@�@�@���g�͂��ƂŊm�F����Ƃ��āABufferAllocation_2.c���r���h���珜�O���Ƃ��B
�@�@�@�@�@
�@�@(�����N�G���[2)
�@�@�@E0562310:Undefined external symbol "_ulRand" referenced in ".\src\FreeRTOS-Plus-TCP\source\FreeRTOS_DHCP.obj"
�@�@�@E0562310:Undefined external symbol "_ulRand" referenced in ".\src\FreeRTOS-Plus-TCP\source\FreeRTOS_Sockets.obj"
�@�@�@E0562310:Undefined external symbol "_pcApplicationHostnameHook" referenced in ".\src\FreeRTOS-Plus-TCP\source\FreeRTOS_DHCP.obj"
�@�@�@E0562310:Undefined external symbol "_vNetworkInterfaceAllocateRAMToBuffers" referenced in ".\src\FreeRTOS-Plus-TCP\source\portable\BufferManagement\BufferAllocation_1.obj"
�@�@�@E0562310:Undefined external symbol "_xApplicationDNSQueryHook" referenced in ".\src\FreeRTOS-Plus-TCP\source\FreeRTOS_DNS.obj"
�@�@�@E0562310:Undefined external symbol "_vApplicationIPNetworkEventHook" referenced in ".\src\FreeRTOS-Plus-TCP\source\FreeRTOS_IP.obj"
�@�@�@E0562310:Undefined external symbol "_xNetworkInterfaceOutput" referenced in ".\src\FreeRTOS-Plus-TCP\source\FreeRTOS_ARP.obj"
�@�@�@E0562310:Undefined external symbol "_xNetworkInterfaceOutput" referenced in ".\src\FreeRTOS-Plus-TCP\source\FreeRTOS_IP.obj"
�@�@�@E0562310:Undefined external symbol "_xNetworkInterfaceOutput" referenced in ".\src\FreeRTOS-Plus-TCP\source\FreeRTOS_TCP_IP.obj"
�@�@�@E0562310:Undefined external symbol "_xNetworkInterfaceOutput" referenced in ".\src\FreeRTOS-Plus-TCP\source\FreeRTOS_UDP_IP.obj"
�@�@�@E0562310:Undefined external symbol "_xNetworkInterfaceInitialise" referenced in ".\src\FreeRTOS-Plus-TCP\source\FreeRTOS_IP.obj"

�@�@�@���l�b�g���[�N�w(IP�w)�ƃf�[�^�����N�w(Ether�w)�̃C���^�t�F�[�X�̎����̂����������B
�@�@�@�@�����FreeRTOS+TCP�̃|�[�e�B���O�K�C�h�ɏ]���Ď�������΂悳���B
�@�@�@�@���b�L�[�Ȃ��ƂɁASH2A�p��NetworkInterface.c���p�ӂ���Ă���ł͂Ȃ����B�iAmazon��SH2A�Ńg���C�A�������̂��ȁH�j
�@�@�@�@SH2A��RX��Ether�R���g���[���͓����ŁAEther�h���C�o�����������Ȃ̂ŁASH2A�p�̃R�[�h��q�؂��āA
�@�@�@�@�ȉ��t�@�C�����쐬�B
�@�@�@�@\rx65n_envision_kit_aws\src\FreeRTOS-Plus-TCP\source\portable\NetworkInterface\RX\NetworkInterface.c
�@�@
�@�@<<�V���ȃR�[�h��ǉ������̂ŃR���p�C���G���[����>>

�@�@(�R���p�C���G���[6)
�@�@�@E0520005:Could not open source file "hwEthernet.h"
�@�@�@�@��RX�}�C�R����Ether�h���C�o�̃w�b�_�t�@�C���́Ar_ether_rx_if.h�ł���B�ύX�B
�@�@
�@�@(�R���p�C���G���[7)
�@�@�@E0520020:Identifier "NetworkBufferDescriptor_t" is undefined
�@�@�@�@��Amazon FreeRTOS�S�̂�grep����ƁAFreeRTOS_IP.h �ɒ�`���������B
�@�@�@�@�@��NetworkInterface.c�� #include "FreeRTOS_IP.h" �𑫂��Ă�����B
�@�@�@�@
�@�@(�R���p�C���G���[8)
�@�@�@E0520136:Struct "xNETWORK_BUFFER" has no field "pucBuffer"
�@�@�@�@��xNETWORK_BUFFER�ɂ�pucBuffer�͖����悤���B
�@�@�@�@�@���̃G���[��vEMACCopyWrite()�֐����̂��̂ł���̂ŁA�����Ƒ��M���ł��Ȃ��Ȃ�
�@�@�@�@�@���낤����ǁA�ЂƂ܂��R�����g�A�E�g���Ă����B
�@�@�@�@
�@�@<<�����܂łŃR���p�C���ʂ���>>

�@�@(�����N�G���[3)
�@�@�@(�����N�G���[2)�Ɣ�r���āA_xNetworkInterfaceOutput()�A_xNetworkInterfaceInitialise()�̃����N�G���[���������B
�@�@�@������ǁA�܂��唼�̃C���^�t�F�[�X�֐����������BSH2A�ł̃R�[�h�̓g���C�A�����X�ɒ��߂�ꂽ�悤���B
�@�@�@���͋�֐�������Ă����āA���Ƃœ������|�[�e�B���O�K�C�h�����Ȃ���������Ă݂�B
�@�@�@�֐��̒�`�̓|�[�e�B���O�K�C�h�ɂ���͂����BNoMaY���̃���������B�ȉ��Q�l�ɂȂ肻���B
�@�@
�@�@�@Porting FreeRTOS+TCP to a Different Microcontroller
�@�@�@http://www.freertos.org/FreeRTOS-Plus/FreeRTOS_Plus_TCP/Embedded_Ethernet_Porting.html
�@�@�@
�@�@�@�����ƌ���ƁA���\���o�����߂ɂ́A���̃|�[�e�B���O�K�C�h��{�C�œǂޕK�v������B
�@�@�@�P�ɓ����������Ȃ�Ƃɂ����֐����m���Ȃ��ł�����Ηǂ������B
�@�@�@�K�v��API�͂��ł�RX�p��Ether�h���C�o�ɗL�銴���B
�@�@�@����LAN�Ή����������̎������L���ɂȂ�B
�@�@�@
�@�@�@_xNetworkInterfaceOutput()�ƁA_xNetworkInterfaceInitialise()���^��FreeRTOS+TCP����
�@�@�@�Ă΂��C���^�t�F�[�X�̂悤���B���̂͂ǂ����낤���B
�@�@�@�R�[�h�̂���������画�肵�Ă����B
�@�@�@
�@�@E0562310:Undefined external symbol "_ulRand" referenced in ".\src\FreeRTOS-Plus-TCP\source\FreeRTOS_DHCP.obj"
�@�@E0562310:Undefined external symbol "_ulRand" referenced in ".\src\FreeRTOS-Plus-TCP\source\FreeRTOS_Sockets.obj"
�@�@�@���֐�������A�������擾���邽�߂̊֐������҂��Ă���悤���B
�@�@�@�@NetworkInterface.c�ɋ�֐���p�ӂ��Ă����B���ƂŒ��g������B
�@�@�@�@���l�T�XTCP/IP��t4_driver.c�ɋ^�������𐶐����鎗���悤�Ȋ֐����L��̂ł���������Ă���B
�@�@�@�@�ŏI�I�ɂ�RX65N�����̈Í���ɂ��闐���������API���g���Ƃ悢�ł��낤�B
�@�@�@�@
�@�@�@�@�֐��v���g�^�C�v�� uint32_t ulRand(void); FreeRTOSIPConfig.h ��extern�Ő錾������B
�@�@�@�@NetworkInterface.c�Ɏ��́ANetworkInterface.h�Ƀv���g�^�C�v�錾��u���΂悢���ȁB
�@�@�@�@
�@�@E0562310:Undefined external symbol "_pcApplicationHostnameHook" referenced in ".\src\FreeRTOS-Plus-TCP\source\FreeRTOS_DHCP.obj"
�@�@�@���|�[�e�B���O�K�C�h�ɍڂ��ĂȂ��̂ŁAAmazon FreeRTOS�S��grep����\�z�B
�@�@�@�@DHCP�Ńz�X�g����o�^����@�\�����邪�A�z�X�g�������[�U��`�֐��ň����n����d�g�݂̂悤���B
�@�@�@�@DHCP���쒆�ɂ��̊֐����Ă΂�ă��[�U���w�肵�����O��DHCP�ɂ��擾�����B
�@�@�@�@FreeRTOS+TCP�R���t�B�O(FreeRTOSIPConfig.h)��ON/OFF�ł���B
�@�@�@�@#define ipconfigDHCP_REGISTER_HOSTNAME           1
�@�@�@
�@�@�@�@�������̃T���v��(PIC�p�AWin�p�j��main.c�Ɏ����̂��������B
�@�@�@�@�R�����g��ǂނƁADHCP�Ń��[�U�̖��O���l�b�g���[�N�ɓo�^����ۂ�
�@�@�@�@DHCP�̃R�[�h�����̃��[�U�̖��O��ǂݍ��ނƂ��ɌĂяo�����[�U��`�֐��ł���B
�@�@�@�@�܂�main�֐��t�߂Ɏ������Ă����̂��Ó��B
�@�@�@�@
�@�@�@�@�ȉ�PIC�̃T���v���BLLMNR�ANBNS��OFF�ADHCP_REGISTER_HOSTNAME��ON�̂Ƃ��ɕK�v�Ȋ֐��B
�@�@�@�@�ȉ�PIC�̃R�[�h�����̂܂�main�t��(rx65n_envision_kit_aws.c)�Ɏ����Ă���B
�@�@�@�@IP�R���t�B�O��LLMNR�ANBNS��OFF�ɂ��Ă����B
�@�@�@�@#include "FreeRTOSIPConfig.h"�̃C���N���[�h���ǉ����Ă����B
�@�@�@�@
�@�@�@�@#if ( ipconfigUSE_LLMNR != 0 ) || ( ipconfigUSE_NBNS != 0 ) || ( ipconfigDHCP_REGISTER_HOSTNAME == 1 )
�@�@�@�@const char * pcApplicationHostnameHook( void )
�@�@�@�@{
�@�@�@�@    /* Assign the name "FreeRTOS" to this network node.  This function will
�@�@�@�@     * be called during the DHCP: the machine will be registered with an IP
�@�@�@�@     * address plus this name. */
�@�@�@�@    return "RX65N_FREERTOS_TCP_TEST_BY_SHELTY";
�@�@�@�@}
�@�@�@�@#endif

�@�@E0562310:Undefined external symbol "_vNetworkInterfaceAllocateRAMToBuffers" referenced in ".\src\FreeRTOS-Plus-TCP\source\portable\BufferManagement\BufferAllocation_1.obj"
�@�@�@���|�[�e�B���O�K�C�h�ɍڂ��Ă�B
�@�@�@�@BufferAllocation_1.c�݂̂��g�p����ꍇ�ɕK�v�ɂȂ�֐��̂悤���B
�@�@�@�@��قǁABufferAllocation_2.c�̓r���h�ΏۊO�ɂ������A���̃o�b�t�@�m�ۂ����܂��g�����Ȃ��΁A
�@�@�@�@���\���オ�o���銴���B���Ԃ�AEther�w����f�[�^���z���グ�鎞��TCP/IP�w�ɑ΂���
�@�@�@�@�f�[�^�R�s�[�œn�����A�|�C���^�œn�����i�[���R�s�[�j�؂�ւ�����̂��B
�@�@�@�@�������[���R�s�[�͎������ʓ|�BRX�}�C�R����Ether�h���C�o�̓[���R�s�[�Ή��Ȃ̂ŁA
�@�@�@�@���Ƃł������萫�\�]�����Ȃ����荞�݂����Ă݂�B
�@�@�@�@���\�͂��Ƃŉ��P����Ƃ��āA����vNetworkInterfaceAllocateRAMToBuffers()���������Ă����B
�@�@�@�@�����̂͌�ōl����Ƃ��āA����vNetworkInterfaceAllocateRAMToBuffers����ɂ��Ă����B
�@�@�@
�@�@E0562310:Undefined external symbol "_xApplicationDNSQueryHook" referenced in ".\src\FreeRTOS-Plus-TCP\source\FreeRTOS_DNS.obj"
�@�@�@�����̊Ԃɂ������Ă��B���Ԃ�"pcApplicationHostnameHook"�̑Ώ�������Ɗ֌W���Ă���悤���B
�@�@�@�@��Œ��ׂ�B
�@�@�@�@
�@�@E0562310:Undefined external symbol "_vApplicationIPNetworkEventHook" referenced in ".\src\FreeRTOS-Plus-TCP\source\FreeRTOS_IP.obj"
�@�@�@���Ō��1���B
�@�@�@�@�|�[�e�B���O�K�C�h�ɍڂ��ĂȂ��̂ŁAAmazon FreeRTOS�S��grep����\�z�B
�@�@�@�@PIC�̃T���v�����q�b�g�BIP�w����̃C�x���g�ʒm�p�̗l�q�B
�@�@�@�@�R�[�h������ƁADHCP�����������������̃R�[���o�b�N��������Ă銴���B
�@�@�@�@���ɂ����낢��ȃC�x���g�����ł������BPIC�̃R�[�h��main�t��(rx65n_envision_kit_aws.c)�Ɏ����Ă���B
�@�@�@�@�l�b�g���[�N�C���^�t�F�[�X����荞�񂾂Ƃ��̓���m�F�ɖ��ɗ��ł��낤�B
�@�@�@�@
�@�@�@�@PIC���L�̈ȉ��R�[�h�͏��O���Ă����B
�@�@�@  /* The network is up so we can run. */
        if( ( SYSTEM_Init() == pdPASS ) && ( xTasksAlreadyCreated == pdFALSE ) )
        {
            /* Run all demos. */
            DEMO_RUNNER_RunDemos();
            xTasksAlreadyCreated = pdTRUE;
        }
�@�@�@
�@�@<<�����܂łŃ����N�ʂ���>>
�@�@
�@�@�@�_�E�����[�h���Ď��s���Ă݂�B
�@�@�@�]���ʂ�A���l�T�XTCP/IP���N�����A����DHCP��IP�A�h���X�擾�ł��Ă���B
�@�@�@FreeRTOS+TCP����ꂽ���ƂŁA�]���̓���(���Ether�h���C�o����)�ɉe���Ȃ����Ƃ��m�F�B
�@�@�@���ꂩ��Amain�t��(rx65n_envision_kit_aws.c)���������A���l�T�XTCP/IP�̏�����������
�@�@�@���O���Ă����A�����FreeRTOS+TCPno���������������Ă����B
�@�@�@
�@�@�@configPRINTF()��L���ɂ��邽�߁AFreeRTOS.h�̈ȉ���ύX
�@�@�@	#define configPRINTF( X )
�@�@�@	��
�@�@�@	#define configPRINTF( X ) printf X
�@�@�@	
�@�@�@FreeRTOS_debug_printf()��L���ɂ��邽�߁AFreeRTOSIPConfig.h�̈ȉ���ύX
�@�@�@	#define ipconfigHAS_DEBUG_PRINTF    0
�@�@�@	��
�@�@�@	#define ipconfigHAS_DEBUG_PRINTF    1
�@�@�@	
�@�@�@RX65N�̍���̃V�X�e����printf()�o�͂��t���\���Ɍq���ł���̂ŁA
�@�@�@�����FreeRTOS�֘A�̃V�X�e�����O���t���\���ɏo�Ă���͂��B
�@�@�@
�@�@�@PIC�̃R�[�h������ƁAFreeRTOS_IPInit()���Ăяo����TCP/IP�̏�����������悤���B
�@�@�@FreeRTOS_IPInit()�̎����̂��m�F����B
�@�@�@��1�`��4������IP�֘A�̃p�����[�^�BDHCP�L���ł���Ύ����擾����͂��Ȃ̂Őݒ�s�v�B
�@�@�@��5������MAC�A�h���X�͓��͕K�v�ł��낤�B�K����MAC�A�h���X�̔z�������ē��͂���B
      FreeRTOS_IPInit(0, 0, 0, 0, renesas_mac_address);
      ���̂Ƃ���main()�͈ȉ��̂悤�Ɏ����B

void main(void)
{
	char buff[256];

	R_Pins_Create();
	R_SYS_TIME_Open();
	lcd_open();
	R_SIMPLE_GRAPHIC_Open();

	/* hello message */
	sprintf(buff, "hello, this is RX65N Envision Kit system log.\r\n");
	printf("%s", buff);
	sprintf(buff, "built in %s, %s\r\n", __DATE__, __TIME__);
	printf("%s", buff);
	sprintf(buff, "\r\n");
	printf("%s", buff);

    	FreeRTOS_IPInit(0, 0, 0, 0, renesas_mac_address);
}

�@�@�@FreeRTOS_IPInit()�I����AIP�^�X�N���N�����āAprvIPTask()�͌Ă΂ꂽ�悤���B
�@�@�@eNetworkDownEvent��prvProcessNetworkDownEvent()���Ă΂ꂽ�Ƃ���Ŗ\���B
�@�@�@�ڍׂ�ǂ������Ă����B
�@�@�@
�@�@�@xNetworkInterfaceInitialise()���Ă΂�邪�������֐���������ԁB
�@�@�@�ЂƂ܂�lan_open()���Ă�ł����BxNetworkInterfaceInitialise()�Ƃ��Ă�
�@�@�@�߂�l�� 1(pdTRUE) �������̂悤�����Alan_open()�͐����� 0 ���߂�̂Œ������Ă����B
�@�@�@RX�}�C�R����Ether�́ALAN�P�[�u���}���̏�Ԃ��m�F���邽�߁AR_ETHER_LinkProcess()�����I��
�@�@�@�Ăяo���K�v������BFreeRTOS�Ń^�X�N�𐶐����ĊĎ�������Ηǂ����A
�@�@�@�܂�FreeRTOS�̎g�������悭�킩��Ȃ����߁ACMT��1�`���l������ĊĎ�������B(��Œ��ׂ�)����OK
�@�@�@
�@�@�@���Ԃ�ALAN�P�[�u���}���̃C�x���g��TCP/IP���ɒʒm����d�g�݂����邪�A�ЂƂ܂��A
�@�@�@xNetworkInterfaceInitialise()�����������Ƃ��Ƀ����N�A�b�v�������Ă���悤��
�@�@�@xNetworkInterfaceInitialise()�����ő҂悤�ɂ��Ă����B(��ł����Ǝ�������)��
�@�@�@
�@�@�@�\���͂Ȃ��Ȃ����B�ł�xNetworkInterfaceInitialise()�����s�������ɖ\������̂ł́H(��Œ��ׂ�)����������ɖ��Ȃ�
�@�@�@IP�^�X�N�̃��[�v�����������Ă��邱�Ƃ��m�F�B
�@�@�@
�@�@�@TCP/IP�N�����͂�����DHCP�������ł��낤����ADHCP�̏�����ǂ������Ă����B
�@�@�@�ǂ�����DHCP�̏���ł���ADHCP Discover Packet�̐������s���Ă��āA
�@�@�@���̌�A�l�b�g���[�N�w�ɑ��M����͂��ł���B
�@�@�@
�@�@�@DHCP�̑��M�̑O�ɁA�����������M��M�p�̃o�b�t�@���K�؂Ɋ��蓖�Ă��Ă��Ȃ��͂��B
�@�@�@�Ȃ��Ȃ�AvNetworkInterfaceAllocateRAMToBuffers()��������������B
�@�@�@�܂��͂���𒲐�����B
�@�@�@
�@�@�@�|�[�e�B���O�K�C�h������ƁAipconfigNUM_NETWORK_BUFFER_DESCRIPTORS �Œ�`����镪�����A
�@�@�@�o�b�t�@�����蓖�Ă�A�Ə����Ă���B��������ƁAFreeRTOSIPConfig.h��60�ƒ�`����Ă���B
�@�@�@�����炭�����Ŋ��蓖�Ă�ׂ��͑��M�o�b�t�@�݂̂Ǝv����B(�{�����H�j�������M�o�b�t�@�ł͂Ȃ���M�o�b�t�@�B
�@�@�@RX�}�C�R����Ether�̎��ۂ̑��M�o�b�t�@���́Ar_ether_rx_config.h��ETHER_CFG_EMAC_TX_DESCRIPTORS�Œ�`�����B
�@�@�@60�̑���ɁA�����ǂݍ���ł����B
�@�@�@
�@�@�@ETHER_CFG_EMAC_TX_DESCRIPTORS���f�t�H���g1������ǁA1�̂܂܂��Ɩ\������B
�@�@�@4�ɑ��₷�BETHER_CFG_EMAC_RX_DESCRIPTORS��4�ɑ��₷�B(�Ȃ����H�j����1�ł����v�ɂȂ����B
�@�@�@
�@�@�@vNetworkInterfaceAllocateRAMToBuffers()�̎����̂́AEther�h���C�o�ɂ�����
�@�@�@���M�o�b�t�@�̃|�C���^��FreeRTOS+TCP�ɓn���悤�Ɏ�������B
�@�@�@
�@�@�@vDHCPProcess()������ɐi�ށB
�@�@�@�@���g�͓`���I��switch-case�̃X�e�[�g�}�V���ł���B
�@�@�@�@�\�z�ʂ�A�ŏ��̏�Ԃ�discover request�̑��M���������B
�@�@�@�@/* Send the first discover request. */
�@�@�@�@prvSendDHCPDiscover()�ɐ����Ă����B
�@�@�@�@�@����ɑ��M���N�G�X�g���o�Ă���悤�����AvApplicationStackOverflowHook()�Œ�~����B
�@�@�@
�@�@�@r_bsp_config.h�ŃX�^�b�N�𑝂₵�Ă݂�BFreeRTOS�̓��[�U�X�^�b�N���g�p����悤���B
�@�@�@�@#pragma stacksize si=0x400
�@�@�@�@��
�@�@�@�@#pragma stacksize si=0x2000

�@�@�@�@#pragma stacksize su=0x1000
�@�@�@�@��
�@�@�@�@#pragma stacksize su=0x2000

�@�@�@�X�^�b�N�����G���Ă�����A���x��IP�^�X�N�̃��[�v��
�@�@�@���s�����Ƃ���Ŗ\������悤�ɂȂ��Ă��܂����B���ɂ��߂��Ȃ��Ȃ����B
�@�@�@(�����Ă����Ԃ��o�b�N�A�b�v���Ă����΂悩�����j
�@�@�@
�@�@�@�����͂����ŏI���I

--------------------------------------------------------------------------
2018/02/14
rx65n_rsk_aws�ō�ƊJ�n�B
FreeRTOS�� 8.2.2�̃R�[�h���������Ă����B

FreeRTOS����port.c�� #include "iodefine.h"���������̂ŁA 
#include "platform.h" �ɕύX

\rx65n_rsk_aws\src\amazon-freertos-master\lib\FreeRTOS\Source\portable\MemMang��
heap_3.c �� heap_4.c �������r���h�ΏۂɂȂ��Ă��邪�Aheap_4.c �݂̂��K�؁B
���ł����Ȃ̂��͒m��Ȃ��B�@�i�Ȃ�ł���Œ��ׂ�j

�C���N���[�h�t�@�C���p�X�̒����Ȃǂ��o�� 8.2.2�̊��œ���m�F�����B
FreeRTOS�̃R�[�h�� 9.0.0�ɕύX������m�F�����B
FreeRTOS�̃R�[�h�� 11.0.0�ɕύX������m�F�����B

rx65n_envision_kit�Ƀ{�[�h��ˑ������̃R�[�h���ڐA������m�F�B���Ȃ��B

--------------------------------------------------------------------------
2018/02/12
�R�[�h�����ĊJ�B

�悸�����l����BNoMaY���͏�ʃ��C���[����̒��������{���Ă���̂ŁA
���͉��ʃ��C���[����ςݏグ�Ă����A�ǂ��^�C�~���O�Ń}�[�W����̂��ǂ��B
NoMaY���̊������݂�Ƒ傫��4�_�X�e�b�v�����肻���B
�@FreeRTOS�œ��삳����
�AFreeRTOS+TCP�𓮍삳����
�Bmbed TLS�𓮍삳����
�C���ۂ�AWS�Ɍq��

�悸�͇@��Ή����邽�߁ARX65N�p�ɗp�ӂ��ꂽOS�p�b�P�[�W���Q�l�ɂ���B
https://www.renesas.com/en-us/software/D6001925.html

���̒��ɂ́A�����FIT���W���[���������Ă��邱�Ƃ�NoMaY���̒����ɂ��m�F�ς݁B
r_bsp_rtos
r_cmt_rtos

�����(2017/12/29)�̂��̂Ɋ܂܂��ȉ�2�_�ƒu�������Ă���
FreeRTOS�ƌ����ł���̂ł͂Ȃ����B
r_bsp
r_cmt_rx

diff���Ƃ��āA�N���e�B�J���ȂƂ����(2017/12/29)�ɔ��f���Ă����B

(1)r_bsp �� resetprg.c ��OS�p�̃C���N���[�h�t�@�C�����Ă�ł�Ƃ���
#if BSP_CFG_RTOS_USED == 0      // Non-OS
#elif BSP_CFG_RTOS_USED == 1    // FreeRTOS
    #include    "freertos_usr_func.h"    // FreeRTOS's user configuration
#elif BSP_CFG_RTOS_USED == 2    // SEGGER embOS
#elif BSP_CFG_RTOS_USED == 3    // Micrium MicroC/OS
#elif BSP_CFG_RTOS_USED == 4    // Renesas RI600V4 & RI600PX
#endif

(2) r_bsp �� resetprg.c �� r_cmt_rx �� r_cmt_rx.c �ɂ����āA
�@��L�}�N���ɔ���FreeRTOS�p�̃R�[�h�e��
�@�i�J�[�l���̃X�P�W���[�����Ăяo���Ă���Ƃ���Ȃǁj�����f�B

(3) r_bsp �� r_bsp.h ��FreeRTOS�̃w�b�_�t�@�C���Q�̃C���N���[�h��ǉ��B
�@���[�U�����RX�}�C�R����FIT�Q�̃w�b�_�t�@�C��platform.h ���C���N���[�h
�@����΂悢�悤�ɂȂ�B

#if BSP_CFG_RTOS_USED == 0      // Non-OS
#elif BSP_CFG_RTOS_USED == 1    // FreeRTOS
#include "FreeRTOS.h"
#include "task.h"
#include "semphr.h"
#include "queue.h"
#include "croutine.h"
#include "timers.h"
#include "event_groups.h"
#elif BSP_CFG_RTOS_USED == 2    // SEGGER embOS
#elif BSP_CFG_RTOS_USED == 3    // Micrium MicroC/OS
#elif BSP_CFG_RTOS_USED == 4    // Renesas RI600V4 & RI600PX
#endif

(3)BSP�̃R���t�B�O(r_bsp_config.h)�ɂ��郊�A���^�C��OS�؂�ւ���
�@�}�N��(BSP_CFG_RTOS_USED)��FreeRTOS��I������B
�@����ƁA(2)�Ŕ��f����������FreeRTOS�֘A�̃R�[�h���L���ɂȂ�B
�@FreeRTOS�ɑΉ�����}�N���ԍ���(1)�B
�@�f�t�H���g��(0)����RTOS���g��Ȃ��ݒ�ƂȂ�B

(4)BSP�̃R���t�B�O(r_bsp_config.h)�ɂ���^�C�}�`���l���̎w��ɂ��Ĉȉ��ǉ��B
/* This macro is used to select which CMT channel used for system timer of RTOS.
 * The setting of this macro is only valid if the macro BSP_CFG_RTOS_USED is set to a value other than 0. */
#if (BSP_CFG_RTOS_USED != 0)
/* Setting value.
 * 0      = CMT channel 0 used for system timer of RTOS (recommended to be used for RTOS).
 * 1      = CMT channel 1 used for system timer of RTOS.
 * 2      = CMT channel 2 used for system timer of RTOS.
 * 3      = CMT channel 3 used for system timer of RTOS.
 * Others = Invalid. */
#define BSP_CFG_RTOS_SYSTEM_TIMER		(0)
#endif

���āA���Ɏg�p����FreeRTOS�̃o�[�W�����B
��������m�F�������Ƃ�����̂�8.2.2�ŁA��LRX65N�p�ɗp�ӂ��ꂽ
OS�p�b�P�[�W��9.0.0�ŁAAmazon FreeRTOS��11.0.0�ł���B
�ЂƂ܂��A8.2.2�������Ă��āA�����𖄂߂Ă��������Ői�߂�B

���͉�ЂƘA�g���邽�߁A�{�[�h��RX65N RSK�ɏ�芷���B
�ȍ~�Arx65n_rsk_aws �t�H���_�Ɉړ��B

--------------------------------------------------------------------------
2018/02/09
������ɂ��J���ꎞ��~�B

--------------------------------------------------------------------------
2017/12/29 
RX65N Envision Kit��f�ނɂ���B
�w������LAN�R�l�N�^��SD�X���b�g�Ȃǂ��t���ĂȂ��̂ő��݂��K�v�B
�悸��e2 studio �̃X�}�[�g�R���t�B�O���[�^�@�\��
�ȉ����W���[�����C���|�[�g����B
- r_bsp
- r_cmt_rx
- r_ether_rx
- r_sys_time_rx
- r_t4_rx
- r_t4_driver_rx

�˂����Ether�֘A�̓���m�F���ł���B
�@�[�q�ݒ��RX65N Envision Kit�̃R�[�h�Ɠ��������ǂ������ׂȂ��璲���B
�@�����ɂ����Ether�֘A�͓����͂��B
- r_pincfg

FIT���W���[���ȊO�̈ȉ��\�[�X�R�[�h��RX65N Envision Kit�̃R�[�h���痬�p����B
- lcd_conf.c
- r_ascii.c
- r_ascii.h
- r_simple_graphic.c
- r_simple_graphic_if.h

�˂����printf()��RX65N Envision Kit�̉t���ɕ����\�����\�B
�@�V�X�e�����O����ʂɏo���B
�@�|�[�e�B���O���i�߂΁ASegger��GUI���ڂ��ăE�B���h�E�`���ɂ������B

�����܂ł̓���m�F��PC����ping���ʂ邱�Ƃ��m�F�����B
