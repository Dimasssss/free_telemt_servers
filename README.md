# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt  
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

-----

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-40
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 марта
- Ссылка:
```bash
tg://proxy?server=s1.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## psb.hosting
- Локация: Finland
- Тариф: FI-200
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 12$
- Оплачен до: 25 марта
- Ссылка:
```bash
tg://proxy?server=s2.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## koara.io
- Локация: Германия, Франкфурт-на-Майне
- Тариф: DE-2
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 639 RUB
- Оплачен до: 25 марта
- Ссылка:
```bash
tg://proxy?server=s3.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## landvps.ru
- Локация: Финляндия
- Тариф: FL-2
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 200 Mbps/s
- Цена в месяц: 800 RUB
- Оплачен до: 26 марта
- Ссылка:
```bash
tg://proxy?server=s4.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## rdp-onedash.ru
- Локация: Нидерланды
- Тариф: Mini
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 844 RUB
- Оплачен до: 14 апреля
- Ссылка:
```bash
tg://proxy?server=s5.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

# Server Metrics 2026-03-10 13:43:15 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 138203.0 (38h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 315295
telemt_connections_bad_total 3479
telemt_handshake_timeouts_total 3287
telemt_upstream_connect_attempt_total 295304
telemt_upstream_connect_success_total 295147
telemt_upstream_connect_fail_total 157
telemt_upstream_connect_attempts_per_request{bucket="1"} 295304
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 272957
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22094
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 157
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 295133
telemt_user_connections_current{user="hello"} 306
telemt_user_octets_from_client{user="hello"} 6797366914 (6.33 GB)
telemt_user_octets_to_client{user="hello"} 194864076935 (181.48 GB)
telemt_user_msgs_from_client{user="hello"} 7074693
telemt_user_msgs_to_client{user="hello"} 11535997
telemt_user_unique_ips_current{user="hello"} 75
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 138201.8 (38h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 97352
telemt_connections_bad_total 3273
telemt_handshake_timeouts_total 1291
telemt_upstream_connect_attempt_total 87821
telemt_upstream_connect_success_total 87777
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 87821
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 78957
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8388
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 431
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 87763
telemt_user_connections_current{user="hello"} 79
telemt_user_octets_from_client{user="hello"} 2820302205 (2.63 GB)
telemt_user_octets_to_client{user="hello"} 37623187948 (35.04 GB)
telemt_user_msgs_from_client{user="hello"} 2301722
telemt_user_msgs_to_client{user="hello"} 10877071
telemt_user_unique_ips_current{user="hello"} 23
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 138202.3 (38h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 138613
telemt_connections_bad_total 1230
telemt_handshake_timeouts_total 6485
telemt_upstream_connect_attempt_total 103861
telemt_upstream_connect_success_total 103858
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 103861
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 91970
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11849
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 39
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 103844
telemt_user_connections_current{user="hello"} 89
telemt_user_octets_from_client{user="hello"} 6667756809 (6.21 GB)
telemt_user_octets_to_client{user="hello"} 68916857844 (64.18 GB)
telemt_user_msgs_from_client{user="hello"} 4531430
telemt_user_msgs_to_client{user="hello"} 11664160
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 138197.1 (38h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 143023
telemt_connections_bad_total 1062
telemt_handshake_timeouts_total 2938
telemt_upstream_connect_attempt_total 132182
telemt_upstream_connect_success_total 131885
telemt_upstream_connect_fail_total 297
telemt_upstream_connect_attempts_per_request{bucket="1"} 132182
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 117166
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14303
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 82
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 334
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 297
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 131871
telemt_user_connections_current{user="hello"} 142
telemt_user_octets_from_client{user="hello"} 5017643529 (4.67 GB)
telemt_user_octets_to_client{user="hello"} 93681372480 (87.25 GB)
telemt_user_msgs_from_client{user="hello"} 3857543
telemt_user_msgs_to_client{user="hello"} 21222986
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 138202.4 (38h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 211659
telemt_connections_bad_total 30934
telemt_handshake_timeouts_total 5844
telemt_upstream_connect_attempt_total 166040
telemt_upstream_connect_success_total 165078
telemt_upstream_connect_fail_total 962
telemt_upstream_connect_attempts_per_request{bucket="1"} 166040
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 142884
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21973
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 221
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 962
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 165064
telemt_user_connections_current{user="hello"} 217
telemt_user_octets_from_client{user="hello"} 3508878339 (3.27 GB)
telemt_user_octets_to_client{user="hello"} 118611415770 (110.47 GB)
telemt_user_msgs_from_client{user="hello"} 3758812
telemt_user_msgs_to_client{user="hello"} 16233912
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 35
```