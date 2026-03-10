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

# Server Metrics 2026-03-10 23:18:00 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 31912.0 (8h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 98003
telemt_connections_bad_total 3305
telemt_handshake_timeouts_total 2212
telemt_upstream_connect_attempt_total 88169
telemt_upstream_connect_success_total 88137
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 88169
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 80256
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7828
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 88133
telemt_user_connections_current{user="hello"} 172
telemt_user_octets_from_client{user="hello"} 2590585731 (2.41 GB)
telemt_user_octets_to_client{user="hello"} 72309915408 (67.34 GB)
telemt_user_msgs_from_client{user="hello"} 2567246
telemt_user_msgs_to_client{user="hello"} 4935641
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 31911.2 (8h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 38028
telemt_connections_bad_total 333
telemt_handshake_timeouts_total 867
telemt_upstream_connect_attempt_total 34560
telemt_upstream_connect_success_total 34551
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 34560
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29145
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5186
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 220
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 34547
telemt_user_connections_current{user="hello"} 34
telemt_user_octets_from_client{user="hello"} 1714500461 (1.60 GB)
telemt_user_octets_to_client{user="hello"} 36734079489 (34.21 GB)
telemt_user_msgs_from_client{user="hello"} 1432034
telemt_user_msgs_to_client{user="hello"} 9139301
telemt_user_unique_ips_current{user="hello"} 16
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 31910.8 (8h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 60559
telemt_connections_bad_total 448
telemt_handshake_timeouts_total 4081
telemt_upstream_connect_attempt_total 52530
telemt_upstream_connect_success_total 52528
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 52530
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 47281
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5199
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 47
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 52524
telemt_user_connections_current{user="hello"} 56
telemt_user_octets_from_client{user="hello"} 847038186 (807.80 MB)
telemt_user_octets_to_client{user="hello"} 51580590834 (48.04 GB)
telemt_user_msgs_from_client{user="hello"} 1144758
telemt_user_msgs_to_client{user="hello"} 7645754
telemt_user_unique_ips_current{user="hello"} 23
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 31909.9 (8h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 56306
telemt_connections_bad_total 87
telemt_handshake_timeouts_total 334
telemt_upstream_connect_attempt_total 54061
telemt_upstream_connect_success_total 53910
telemt_upstream_connect_fail_total 151
telemt_upstream_connect_attempts_per_request{bucket="1"} 54061
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 47368
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6372
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 17
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 153
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 151
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 53906
telemt_user_connections_current{user="hello"} 65
telemt_user_octets_from_client{user="hello"} 830603709 (792.13 MB)
telemt_user_octets_to_client{user="hello"} 37458081239 (34.89 GB)
telemt_user_msgs_from_client{user="hello"} 1136362
telemt_user_msgs_to_client{user="hello"} 7184668
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 31911.2 (8h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 82629
telemt_connections_bad_total 7764
telemt_handshake_timeouts_total 1468
telemt_upstream_connect_attempt_total 70222
telemt_upstream_connect_success_total 69974
telemt_upstream_connect_fail_total 248
telemt_upstream_connect_attempts_per_request{bucket="1"} 70222
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 60480
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9281
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 213
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 248
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 69970
telemt_user_connections_current{user="hello"} 108
telemt_user_octets_from_client{user="hello"} 2079991353 (1.94 GB)
telemt_user_octets_to_client{user="hello"} 57199431583 (53.27 GB)
telemt_user_msgs_from_client{user="hello"} 1973356
telemt_user_msgs_to_client{user="hello"} 8299307
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 10880.6 (3h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 40
telemt_connections_bad_total 38
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 2
telemt_upstream_connect_success_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
```