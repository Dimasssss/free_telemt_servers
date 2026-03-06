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

# Server Metrics 2026-03-06 08:24:41 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.3

telemt_uptime_seconds 851.3 (0h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2036
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 9
telemt_upstream_connect_attempt_total 1970
telemt_upstream_connect_success_total 1970
telemt_upstream_connect_attempts_per_request{bucket="1"} 1970
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1884
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 84
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1968
telemt_user_connections_current{user="hello"} 119
telemt_user_octets_from_client{user="hello"} 20898896 (19.93 MB)
telemt_user_octets_to_client{user="hello"} 1058904150 (1009.85 MB)
telemt_user_msgs_from_client{user="hello"} 31273
telemt_user_msgs_to_client{user="hello"} 156961
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## psb.hosting

```
telemt 3.3.3

telemt_uptime_seconds 851.6 (0h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 262
telemt_connections_bad_total 1
telemt_upstream_connect_attempt_total 261
telemt_upstream_connect_success_total 261
telemt_upstream_connect_attempts_per_request{bucket="1"} 261
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 246
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 259
telemt_user_connections_current{user="hello"} 29
telemt_user_octets_from_client{user="hello"} 2633361 (2.51 MB)
telemt_user_octets_to_client{user="hello"} 176263521 (168.10 MB)
telemt_user_msgs_from_client{user="hello"} 6612
telemt_user_msgs_to_client{user="hello"} 44981
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## koara.io

```
telemt 3.3.3

telemt_uptime_seconds 849.4 (0h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 182
telemt_connections_bad_total 1
telemt_upstream_connect_attempt_total 177
telemt_upstream_connect_success_total 177
telemt_upstream_connect_attempts_per_request{bucket="1"} 177
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 148
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 175
telemt_user_connections_current{user="hello"} 11
telemt_user_octets_from_client{user="hello"} 2041894 (1.95 MB)
telemt_user_octets_to_client{user="hello"} 61656664 (58.80 MB)
telemt_user_msgs_from_client{user="hello"} 3486
telemt_user_msgs_to_client{user="hello"} 14168
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## landvps.ru

```
telemt 3.3.3

telemt_uptime_seconds 852.0 (0h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 303
telemt_connections_bad_total 8
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 282
telemt_upstream_connect_success_total 281
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 282
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 255
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 279
telemt_user_connections_current{user="hello"} 22
telemt_user_octets_from_client{user="hello"} 2180203 (2.08 MB)
telemt_user_octets_to_client{user="hello"} 103111622 (98.33 MB)
telemt_user_msgs_from_client{user="hello"} 4800
telemt_user_msgs_to_client{user="hello"} 26044
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## rdp-onedash.ru

```
telemt 3.3.3

telemt_uptime_seconds 853.7 (0h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 710
telemt_connections_bad_total 416
telemt_upstream_connect_attempt_total 294
telemt_upstream_connect_success_total 294
telemt_upstream_connect_attempts_per_request{bucket="1"} 294
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 226
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 68
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 292
telemt_user_connections_current{user="hello"} 25
telemt_user_octets_from_client{user="hello"} 20125764 (19.19 MB)
telemt_user_octets_to_client{user="hello"} 382561316 (364.84 MB)
telemt_user_msgs_from_client{user="hello"} 15878
telemt_user_msgs_to_client{user="hello"} 74010
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 4
```