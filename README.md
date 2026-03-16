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

# Server Metrics 2026-03-16 14:07:18 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 1765.1 (0h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 23244
telemt_connections_bad_total 140
telemt_handshake_timeouts_total 559
telemt_upstream_connect_attempt_total 260
telemt_upstream_connect_success_total 258
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 260
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 141
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 117
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 149
telemt_me_reconnect_success_total 147
telemt_me_reader_eof_total 115
telemt_me_idle_close_by_peer_total 115
telemt_me_route_drop_no_conn_total 6581
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 21460
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 23
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 17
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 9
telemt_desync_frames_bucket_total{bucket="gt_10"} 8
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 137
telemt_me_writer_restored_same_endpoint_total 145
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 36
telemt_user_connections_total{user="hello"} 21408
telemt_user_connections_current{user="hello"} 738
telemt_user_octets_from_client{user="hello"} 469138496 (447.41 MB)
telemt_user_octets_to_client{user="hello"} 15543779884 (14.48 GB)
telemt_user_unique_ips_current{user="hello"} 212
telemt_user_unique_ips_recent_window{user="hello"} 79
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 1268.5 (0h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14233
telemt_connections_bad_total 776
telemt_handshake_timeouts_total 70
telemt_upstream_connect_attempt_total 12839
telemt_upstream_connect_success_total 12820
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 12837
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10443
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 818
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1559
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 12818
telemt_user_connections_current{user="hello"} 605
telemt_user_octets_from_client{user="hello"} 75843913 (72.33 MB)
telemt_user_octets_to_client{user="hello"} 1538797648 (1.43 GB)
telemt_user_msgs_from_client{user="hello"} 138997
telemt_user_msgs_to_client{user="hello"} 538644
telemt_user_unique_ips_current{user="hello"} 117
telemt_user_unique_ips_recent_window{user="hello"} 64
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 1878.3 (0h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9641
telemt_connections_bad_total 3
telemt_handshake_timeouts_total 67
telemt_upstream_connect_attempt_total 1999
telemt_upstream_connect_success_total 1969
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 1999
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1216
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 734
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_reconnect_attempts_total 27897
telemt_me_reconnect_success_total 868
telemt_me_reader_eof_total 792
telemt_me_idle_close_by_peer_total 792
telemt_me_route_drop_no_conn_total 2176
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8025
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_writer_removed_unexpected_total 813
telemt_me_refill_failed_total 844
telemt_me_writer_restored_same_endpoint_total 824
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 1272
telemt_user_connections_total{user="hello"} 8982
telemt_user_connections_current{user="hello"} 315
telemt_user_octets_from_client{user="hello"} 81143354 (77.38 MB)
telemt_user_octets_to_client{user="hello"} 1406576458 (1.31 GB)
telemt_user_msgs_from_client{user="hello"} 4789
telemt_user_msgs_to_client{user="hello"} 14129
telemt_user_unique_ips_current{user="hello"} 106
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 2014.6 (0h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17632
telemt_connections_bad_total 16
telemt_handshake_timeouts_total 174
telemt_upstream_connect_attempt_total 453
telemt_upstream_connect_success_total 452
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 453
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 290
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 159
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 286
telemt_me_reconnect_success_total 277
telemt_me_reader_eof_total 253
telemt_me_idle_close_by_peer_total 253
telemt_me_route_drop_no_conn_total 5160
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16775
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 9
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 124
telemt_desync_full_logged_total 35
telemt_desync_suppressed_total 89
telemt_desync_frames_bucket_total{bucket="1_2"} 21
telemt_desync_frames_bucket_total{bucket="3_10"} 46
telemt_desync_frames_bucket_total{bucket="gt_10"} 57
telemt_me_writer_removed_unexpected_total 268
telemt_me_writer_restored_same_endpoint_total 273
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 18
telemt_user_connections_total{user="hello"} 16759
telemt_user_connections_current{user="hello"} 446
telemt_user_octets_from_client{user="hello"} 285813052 (272.57 MB)
telemt_user_octets_to_client{user="hello"} 3434368652 (3.20 GB)
telemt_user_unique_ips_current{user="hello"} 142
telemt_user_unique_ips_recent_window{user="hello"} 69
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 2004.0 (0h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12640
telemt_connections_bad_total 3864
telemt_handshake_timeouts_total 73
telemt_upstream_connect_attempt_total 468
telemt_upstream_connect_success_total 468
telemt_upstream_connect_attempts_per_request{bucket="1"} 468
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 213
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 255
telemt_me_reconnect_attempts_total 302
telemt_me_reconnect_success_total 297
telemt_me_reader_eof_total 277
telemt_me_idle_close_by_peer_total 277
telemt_me_route_drop_no_conn_total 1983
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8329
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2
telemt_desync_full_logged_total 2
telemt_desync_frames_bucket_total{bucket="1_2"} 1
telemt_desync_frames_bucket_total{bucket="3_10"} 1
telemt_me_writer_removed_unexpected_total 296
telemt_me_writer_restored_same_endpoint_total 296
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 14
telemt_user_connections_total{user="hello"} 8317
telemt_user_connections_current{user="hello"} 190
telemt_user_octets_from_client{user="hello"} 224286456 (213.90 MB)
telemt_user_octets_to_client{user="hello"} 1909999864 (1.78 GB)
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 1582.5 (0h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20037
telemt_connections_bad_total 370
telemt_handshake_timeouts_total 110
telemt_upstream_connect_attempt_total 285
telemt_upstream_connect_success_total 285
telemt_upstream_connect_attempts_per_request{bucket="1"} 285
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 182
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 103
telemt_me_reconnect_attempts_total 170
telemt_me_reconnect_success_total 169
telemt_me_reader_eof_total 138
telemt_me_idle_close_by_peer_total 138
telemt_me_route_drop_no_conn_total 9103
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 19043
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8
telemt_desync_full_logged_total 3
telemt_desync_suppressed_total 5
telemt_desync_frames_bucket_total{bucket="1_2"} 1
telemt_desync_frames_bucket_total{bucket="3_10"} 7
telemt_me_writer_removed_unexpected_total 160
telemt_me_writer_restored_same_endpoint_total 165
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 208
telemt_user_connections_total{user="hello"} 18919
telemt_user_connections_current{user="hello"} 715
telemt_user_octets_from_client{user="hello"} 404919244 (386.16 MB)
telemt_user_octets_to_client{user="hello"} 3801913672 (3.54 GB)
telemt_user_unique_ips_current{user="hello"} 265
telemt_user_unique_ips_recent_window{user="hello"} 107
```