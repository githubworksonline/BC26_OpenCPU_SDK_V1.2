ע�⣺ ��Ϊ�����ں˰汾����Ҫ����TESTĿ¼��Ӧ���ȱ���һ��lib���ļ���������һ��С�汾�š�
Commands Discription:
1 ����basic���ܣ�
  A �޸Ĳ���debugPortCfg Ϊ BASIC_MODE,λ����[ custom\config\custom_sys_cfg.c ]
  B �򿪺�__OCPU_FOTA_BY_HTTP__ & __OCPU_FOTA_BY_FTP__ ��λ����[SDK_n_LIB\custom\config\custom_feature_def.h]
  C ����M66��Ŀ����Ҫ��fota_stress_http.c���޸�Ϊ #define HTTP_UPDATE_FILENAME    "M66_Fotaftp_app.bin"��
    ��fota_stress_ftp.c���޸�Ϊ #define FTP_FILENAME    "M66_Fotahttp_app.bin"
  D ����M26��Ŀ����Ҫ��fota_stress_http.c���޸�Ϊ #define HTTP_UPDATE_FILENAME    "M26_Fotaftp_app.bin"��
    ��fota_stress_ftp.c���޸�Ϊ #define FTP_FILENAME    "M26_Fotahttp_app.bin"
  E make2 test_basic
  F ����ʹ��quecFota����OpenCPU_FOTA_Package_Tool������Ӧ��������

2 ����advance���ܣ�
  A �޸Ĳ���debugPortCfg Ϊ ADVANCE_MODE,λ����[ custom\config\custom_sys_cfg.c ]
  B �򿪺�__OCPU_FOTA_BY_HTTP__ & __OCPU_FOTA_BY_FTP__ ��λ����[SDK_n_LIB\custom\config\custom_feature_def.h]
  C ����M66��Ŀ����Ҫ��fota_stress_http.c���޸�Ϊ #define HTTP_UPDATE_FILENAME    "M66_Fotaftp_app.bin"��
    ��fota_stress_ftp.c���޸�Ϊ #define FTP_FILENAME    "M66_Fotahttp_app.bin"
  D ����M26��Ŀ����Ҫ��fota_stress_http.c���޸�Ϊ #define HTTP_UPDATE_FILENAME    "M26_Fotaftp_app.bin"��
    ��fota_stress_ftp.c���޸�Ϊ #define FTP_FILENAME    "M26_Fotahttp_app.bin"
  E make2 test_advance
  F ����ʹ��quecFota����OpenCPU_FOTA_Package_Tool������Ӧ��������

3 ����LIB
  make2 newlib

4 Clean
  make2 clean
