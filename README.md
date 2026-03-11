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

# Server Metrics 2026-03-11 02:11:08 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 42299.8 (11h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 112610
telemt_connections_bad_total 3353
telemt_handshake_timeouts_total 2550
telemt_upstream_connect_attempt_total 101599
telemt_upstream_connect_success_total 101563
telemt_upstream_connect_fail_total 36
telemt_upstream_connect_attempts_per_request{bucket="1"} 101599
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 92372
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9137
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 36
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 101559
telemt_user_connections_current{user="hello"} 131
telemt_user_octets_from_client{user="hello"} 2783675323 (2.59 GB)
telemt_user_octets_to_client{user="hello"} 80450435982 (74.93 GB)
telemt_user_msgs_from_client{user="hello"} 2867670
telemt_user_msgs_to_client{user="hello"} 5563072
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 42298.9 (11h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 46629
telemt_connections_bad_total 366
telemt_handshake_timeouts_total 2310
telemt_upstream_connect_attempt_total 41372
telemt_upstream_connect_success_total 41362
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 41371
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34960
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6178
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 224
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 41358
telemt_user_connections_current{user="hello"} 30
telemt_user_octets_from_client{user="hello"} 2173889662 (2.02 GB)
telemt_user_octets_to_client{user="hello"} 39517364871 (36.80 GB)
telemt_user_msgs_from_client{user="hello"} 1689442
telemt_user_msgs_to_client{user="hello"} 9793255
telemt_user_unique_ips_current{user="hello"} 16
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 42298.6 (11h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 67686
telemt_connections_bad_total 641
telemt_handshake_timeouts_total 4140
telemt_upstream_connect_attempt_total 59098
telemt_upstream_connect_success_total 59096
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 59098
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52710
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6337
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 59090
telemt_user_connections_current{user="hello"} 49
telemt_user_octets_from_client{user="hello"} 11733792816 (10.93 GB)
telemt_user_octets_to_client{user="hello"} 69866416413 (65.07 GB)
telemt_user_msgs_from_client{user="hello"} 5113562
telemt_user_msgs_to_client{user="hello"} 13083884
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 42297.6 (11h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 66533
telemt_connections_bad_total 134
telemt_handshake_timeouts_total 541
telemt_upstream_connect_attempt_total 63663
telemt_upstream_connect_success_total 63507
telemt_upstream_connect_fail_total 156
telemt_upstream_connect_attempts_per_request{bucket="1"} 63663
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 55403
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7908
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 169
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 156
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 63501
telemt_user_connections_current{user="hello"} 61
telemt_user_octets_from_client{user="hello"} 1752540338 (1.63 GB)
telemt_user_octets_to_client{user="hello"} 42572651929 (39.65 GB)
telemt_user_msgs_from_client{user="hello"} 1577845
telemt_user_msgs_to_client{user="hello"} 8332060
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 42299.1 (11h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 97362
telemt_connections_bad_total 9838
telemt_handshake_timeouts_total 1517
telemt_upstream_connect_attempt_total 82369
telemt_upstream_connect_success_total 82121
telemt_upstream_connect_fail_total 248
telemt_upstream_connect_attempts_per_request{bucket="1"} 82369
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 71056
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10839
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 226
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 248
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 82117
telemt_user_connections_current{user="hello"} 125
telemt_user_octets_from_client{user="hello"} 2163430740 (2.01 GB)
telemt_user_octets_to_client{user="hello"} 68506842806 (63.80 GB)
telemt_user_msgs_from_client{user="hello"} 2166994
telemt_user_msgs_to_client{user="hello"} 9885419
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 21268.4 (5h 54m)
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