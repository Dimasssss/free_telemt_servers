# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt  
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### [Итог по хостингам](Reviews.md)

---

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

## hostvds.com
- Локация: Нидерланды, Амстердам
- Тариф: Burstable
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 10 Gbit/s
- Цена в месяц: €7.98
- Оплачен до: 13 апреля
- Ссылка:
```bash
tg://proxy?server=s6.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

# Server Metrics 2026-03-11 13:55:51 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 84582.5 (23h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 276548
telemt_connections_bad_total 3676
telemt_handshake_timeouts_total 4762
telemt_upstream_connect_attempt_total 255764
telemt_upstream_connect_success_total 255687
telemt_upstream_connect_fail_total 77
telemt_upstream_connect_attempts_per_request{bucket="1"} 255764
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 234024
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21604
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 77
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 255677
telemt_user_connections_current{user="hello"} 375
telemt_user_octets_from_client{user="hello"} 4947130542 (4.61 GB)
telemt_user_octets_to_client{user="hello"} 131838006291 (122.78 GB)
telemt_user_msgs_from_client{user="hello"} 5687216
telemt_user_msgs_to_client{user="hello"} 10401545
telemt_user_unique_ips_current{user="hello"} 99
telemt_user_unique_ips_recent_window{user="hello"} 51
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 84581.4 (23h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 108206
telemt_connections_bad_total 911
telemt_handshake_timeouts_total 3343
telemt_upstream_connect_attempt_total 99211
telemt_upstream_connect_success_total 99191
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 99210
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 85935
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12862
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 394
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 99183
telemt_user_connections_current{user="hello"} 166
telemt_user_octets_from_client{user="hello"} 5342865552 (4.98 GB)
telemt_user_octets_to_client{user="hello"} 66033366892 (61.50 GB)
telemt_user_msgs_from_client{user="hello"} 3637984
telemt_user_msgs_to_client{user="hello"} 18753018
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 84580.9 (23h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 151212
telemt_connections_bad_total 1250
telemt_handshake_timeouts_total 6868
telemt_upstream_connect_attempt_total 134684
telemt_upstream_connect_success_total 134670
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 134684
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 119728
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14842
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 99
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 134662
telemt_user_connections_current{user="hello"} 147
telemt_user_octets_from_client{user="hello"} 12628391522 (11.76 GB)
telemt_user_octets_to_client{user="hello"} 120863426370 (112.56 GB)
telemt_user_msgs_from_client{user="hello"} 6581368
telemt_user_msgs_to_client{user="hello"} 26528108
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 84579.9 (23h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 167389
telemt_connections_bad_total 5466
telemt_handshake_timeouts_total 1918
telemt_upstream_connect_attempt_total 153187
telemt_upstream_connect_success_total 152817
telemt_upstream_connect_fail_total 370
telemt_upstream_connect_attempts_per_request{bucket="1"} 153187
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 132800
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19516
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 88
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 413
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 370
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 152807
telemt_user_connections_current{user="hello"} 176
telemt_user_octets_from_client{user="hello"} 9216983699 (8.58 GB)
telemt_user_octets_to_client{user="hello"} 109549470295 (102.03 GB)
telemt_user_msgs_from_client{user="hello"} 5482465
telemt_user_msgs_to_client{user="hello"} 32381058
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 84581.2 (23h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 242918
telemt_connections_bad_total 18745
telemt_handshake_timeouts_total 6150
telemt_upstream_connect_attempt_total 196473
telemt_upstream_connect_success_total 195970
telemt_upstream_connect_fail_total 503
telemt_upstream_connect_attempts_per_request{bucket="1"} 196473
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 169496
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26131
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 343
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 503
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 195962
telemt_user_connections_current{user="hello"} 308
telemt_user_octets_from_client{user="hello"} 4852797967 (4.52 GB)
telemt_user_octets_to_client{user="hello"} 156476836471 (145.73 GB)
telemt_user_msgs_from_client{user="hello"} 4623675
telemt_user_msgs_to_client{user="hello"} 21652933
telemt_user_unique_ips_current{user="hello"} 78
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 63550.5 (17h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 441
telemt_connections_bad_total 419
telemt_handshake_timeouts_total 10
telemt_upstream_connect_attempt_total 17
telemt_upstream_connect_success_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 17
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11
telemt_user_octets_from_client{user="hello"} 7489 (7.31 KB)
telemt_user_octets_to_client{user="hello"} 2462 (2.40 KB)
telemt_user_msgs_from_client{user="hello"} 23
telemt_user_msgs_to_client{user="hello"} 15
```