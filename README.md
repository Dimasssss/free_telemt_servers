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

# Server Metrics 2026-03-11 02:06:02 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 41994.2 (11h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 112210
telemt_connections_bad_total 3353
telemt_handshake_timeouts_total 2548
telemt_upstream_connect_attempt_total 101210
telemt_upstream_connect_success_total 101174
telemt_upstream_connect_fail_total 36
telemt_upstream_connect_attempts_per_request{bucket="1"} 101210
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 92025
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9095
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 36
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 101170
telemt_user_connections_current{user="hello"} 147
telemt_user_octets_from_client{user="hello"} 2778370423 (2.59 GB)
telemt_user_octets_to_client{user="hello"} 80362358989 (74.84 GB)
telemt_user_msgs_from_client{user="hello"} 2861793
telemt_user_msgs_to_client{user="hello"} 5550242
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 41993.6 (11h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 46489
telemt_connections_bad_total 365
telemt_handshake_timeouts_total 2308
telemt_upstream_connect_attempt_total 41241
telemt_upstream_connect_success_total 41232
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 41241
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34871
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6137
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 224
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 41228
telemt_user_connections_current{user="hello"} 54
telemt_user_octets_from_client{user="hello"} 2171761533 (2.02 GB)
telemt_user_octets_to_client{user="hello"} 39080970732 (36.40 GB)
telemt_user_msgs_from_client{user="hello"} 1683256
telemt_user_msgs_to_client{user="hello"} 9726919
telemt_user_unique_ips_current{user="hello"} 21
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 41993.2 (11h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 67516
telemt_connections_bad_total 641
telemt_handshake_timeouts_total 4139
telemt_upstream_connect_attempt_total 58936
telemt_upstream_connect_success_total 58934
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 58936
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52575
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6310
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 58928
telemt_user_connections_current{user="hello"} 70
telemt_user_octets_from_client{user="hello"} 11733159458 (10.93 GB)
telemt_user_octets_to_client{user="hello"} 69851224645 (65.05 GB)
telemt_user_msgs_from_client{user="hello"} 5111744
telemt_user_msgs_to_client{user="hello"} 13077470
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 41992.3 (11h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 66344
telemt_connections_bad_total 134
telemt_handshake_timeouts_total 541
telemt_upstream_connect_attempt_total 63480
telemt_upstream_connect_success_total 63324
telemt_upstream_connect_fail_total 156
telemt_upstream_connect_attempts_per_request{bucket="1"} 63480
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 55255
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7873
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 169
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 156
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 63318
telemt_user_connections_current{user="hello"} 63
telemt_user_octets_from_client{user="hello"} 1751890340 (1.63 GB)
telemt_user_octets_to_client{user="hello"} 42566003191 (39.64 GB)
telemt_user_msgs_from_client{user="hello"} 1575915
telemt_user_msgs_to_client{user="hello"} 8328455
telemt_user_unique_ips_current{user="hello"} 20
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 41993.6 (11h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 96565
telemt_connections_bad_total 9773
telemt_handshake_timeouts_total 1517
telemt_upstream_connect_attempt_total 81670
telemt_upstream_connect_success_total 81422
telemt_upstream_connect_fail_total 248
telemt_upstream_connect_attempts_per_request{bucket="1"} 81670
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 70572
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10624
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 226
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 248
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 81418
telemt_user_connections_current{user="hello"} 103
telemt_user_octets_from_client{user="hello"} 2155582168 (2.01 GB)
telemt_user_octets_to_client{user="hello"} 67485213720 (62.85 GB)
telemt_user_msgs_from_client{user="hello"} 2157006
telemt_user_msgs_to_client{user="hello"} 9746648
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 20962.9 (5h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 63
telemt_connections_bad_total 59
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 2
telemt_upstream_connect_success_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
```