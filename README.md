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

## 4vps.su
- Локация: Польша, Варшава
- Тариф: PL-cx21
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 2 Gbit/s
- Цена в месяц: 770 RUB
- Оплачен до: 16 апреля
- Ссылка:
```bash
tg://proxy?server=s7.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

# Server Metrics 2026-03-18 09:25:48 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.20

telemt_uptime_seconds 2688.1 (0h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 118560
telemt_connections_bad_total 261
telemt_handshake_timeouts_total 2384
telemt_upstream_connect_attempt_total 63379
telemt_upstream_connect_success_total 62468
telemt_upstream_connect_fail_total 911
telemt_upstream_connect_attempts_per_request{bucket="1"} 63379
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 59129
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2757
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 582
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 911
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 505886
telemt_me_reconnect_success_total 370
telemt_me_reader_eof_total 273
telemt_me_idle_close_by_peer_total 271
telemt_me_route_drop_no_conn_total 15639
telemt_me_route_drop_channel_closed_total 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 39973
telemt_me_writer_pick_total{mode="p2c",result="full"} 21
telemt_me_writer_pick_total{mode="p2c",result="closed"} 54
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 143
telemt_desync_full_logged_total 45
telemt_desync_suppressed_total 98
telemt_desync_frames_bucket_total{bucket="1_2"} 54
telemt_desync_frames_bucket_total{bucket="3_10"} 48
telemt_desync_frames_bucket_total{bucket="gt_10"} 41
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 314
telemt_me_refill_failed_total 16481
telemt_me_writer_restored_same_endpoint_total 265
telemt_me_writer_restored_fallback_total 105
telemt_me_async_recovery_trigger_total 11769
telemt_user_connections_total{user="hello"} 101856
telemt_user_connections_current{user="hello"} 1525
telemt_user_octets_from_client{user="hello"} 1320735408 (1.23 GB)
telemt_user_octets_to_client{user="hello"} 20732197161 (19.31 GB)
telemt_user_msgs_from_client{user="hello"} 846607
telemt_user_msgs_to_client{user="hello"} 1165163
telemt_user_unique_ips_current{user="hello"} 470
telemt_user_unique_ips_recent_window{user="hello"} 206
```

## psb.hosting

```
telemt 3.3.20

telemt_uptime_seconds 2718.9 (0h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 253548
telemt_connections_bad_total 33966
telemt_handshake_timeouts_total 5739
telemt_upstream_connect_attempt_total 471
telemt_upstream_connect_success_total 471
telemt_upstream_connect_attempts_per_request{bucket="1"} 471
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 304
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 162
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_failed_total 1
telemt_me_reconnect_attempts_total 312
telemt_me_reconnect_success_total 302
telemt_me_reader_eof_total 258
telemt_me_idle_close_by_peer_total 258
telemt_me_route_drop_no_conn_total 80387
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 194925
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 949
telemt_desync_full_logged_total 227
telemt_desync_suppressed_total 722
telemt_desync_frames_bucket_total{bucket="1_2"} 188
telemt_desync_frames_bucket_total{bucket="3_10"} 378
telemt_desync_frames_bucket_total{bucket="gt_10"} 383
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 275
telemt_me_writer_restored_same_endpoint_total 301
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 1068
telemt_user_connections_total{user="hello"} 194207
telemt_user_connections_current{user="hello"} 3586
telemt_user_octets_from_client{user="hello"} 6031907752 (5.62 GB)
telemt_user_octets_to_client{user="hello"} 66206399500 (61.66 GB)
telemt_user_unique_ips_current{user="hello"} 1023
telemt_user_unique_ips_recent_window{user="hello"} 498
```

## koara.io

```
telemt 3.3.20

telemt_uptime_seconds 2634.3 (0h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 218060
telemt_connections_bad_total 11389
telemt_handshake_timeouts_total 4805
telemt_upstream_connect_attempt_total 8759
telemt_upstream_connect_success_total 8759
telemt_upstream_connect_attempts_per_request{bucket="1"} 8759
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7255
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1498
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 37
telemt_me_reconnect_attempts_total 606066
telemt_me_reconnect_success_total 398
telemt_me_reader_eof_total 356
telemt_me_idle_close_by_peer_total 356
telemt_me_route_drop_no_conn_total 132691
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 153585
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 274
telemt_desync_full_logged_total 105
telemt_desync_suppressed_total 169
telemt_desync_frames_bucket_total{bucket="1_2"} 55
telemt_desync_frames_bucket_total{bucket="3_10"} 115
telemt_desync_frames_bucket_total{bucket="gt_10"} 104
telemt_me_writer_removed_unexpected_total 384
telemt_me_refill_failed_total 19672
telemt_me_writer_restored_same_endpoint_total 363
telemt_me_writer_restored_fallback_total 35
telemt_me_async_recovery_trigger_total 14895
telemt_user_connections_total{user="hello"} 161657
telemt_user_connections_current{user="hello"} 2556
telemt_user_octets_from_client{user="hello"} 1285552667 (1.20 GB)
telemt_user_octets_to_client{user="hello"} 39994367604 (37.25 GB)
telemt_user_msgs_from_client{user="hello"} 68547
telemt_user_msgs_to_client{user="hello"} 285346
telemt_user_unique_ips_current{user="hello"} 698
telemt_user_unique_ips_recent_window{user="hello"} 345
```

## landvps.ru

```
telemt 3.3.20

telemt_uptime_seconds 2664.1 (0h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 248763
telemt_connections_bad_total 5497
telemt_handshake_timeouts_total 31732
telemt_upstream_connect_attempt_total 11201
telemt_upstream_connect_success_total 11115
telemt_upstream_connect_fail_total 86
telemt_upstream_connect_attempts_per_request{bucket="1"} 11201
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10167
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 916
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 86
telemt_me_reconnect_attempts_total 2810505
telemt_me_reconnect_success_total 676
telemt_me_reader_eof_total 642
telemt_me_idle_close_by_peer_total 642
telemt_me_route_drop_no_conn_total 106968
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 180011
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 334
telemt_desync_full_logged_total 109
telemt_desync_suppressed_total 225
telemt_desync_frames_bucket_total{bucket="1_2"} 74
telemt_desync_frames_bucket_total{bucket="3_10"} 130
telemt_desync_frames_bucket_total{bucket="gt_10"} 130
telemt_me_writer_removed_unexpected_total 665
telemt_me_refill_failed_total 99545
telemt_me_writer_restored_same_endpoint_total 581
telemt_me_writer_restored_fallback_total 95
telemt_me_async_recovery_trigger_total 365465
telemt_user_connections_total{user="hello"} 190189
telemt_user_connections_current{user="hello"} 3757
telemt_user_octets_from_client{user="hello"} 2013264274 (1.87 GB)
telemt_user_octets_to_client{user="hello"} 42830843533 (39.89 GB)
telemt_user_msgs_from_client{user="hello"} 80007
telemt_user_msgs_to_client{user="hello"} 158054
telemt_user_unique_ips_current{user="hello"} 895
telemt_user_unique_ips_recent_window{user="hello"} 635
```

## rdp-onedash.ru

```
telemt 3.3.20

telemt_uptime_seconds 2559.0 (0h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 177496
telemt_connections_bad_total 6777
telemt_handshake_timeouts_total 1927
telemt_upstream_connect_attempt_total 10184
telemt_upstream_connect_success_total 10183
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 10184
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9339
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 638
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 206
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 2982468
telemt_me_reconnect_success_total 520
telemt_me_reader_eof_total 449
telemt_me_idle_close_by_peer_total 449
telemt_me_route_drop_no_conn_total 51224
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 140250
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 366
telemt_desync_full_logged_total 139
telemt_desync_suppressed_total 227
telemt_desync_frames_bucket_total{bucket="1_2"} 44
telemt_desync_frames_bucket_total{bucket="3_10"} 129
telemt_desync_frames_bucket_total{bucket="gt_10"} 193
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 463
telemt_me_refill_failed_total 107153
telemt_me_writer_restored_same_endpoint_total 405
telemt_me_writer_restored_fallback_total 115
telemt_me_async_recovery_trigger_total 267383
telemt_user_connections_total{user="hello"} 149655
telemt_user_connections_current{user="hello"} 3013
telemt_user_octets_from_client{user="hello"} 2675995645 (2.49 GB)
telemt_user_octets_to_client{user="hello"} 59094457773 (55.04 GB)
telemt_user_msgs_from_client{user="hello"} 86293
telemt_user_msgs_to_client{user="hello"} 266108
telemt_user_unique_ips_current{user="hello"} 908
telemt_user_unique_ips_recent_window{user="hello"} 442
```

## hostvds.com

```
telemt 3.3.20

telemt_uptime_seconds 2444.2 (0h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 53121
telemt_connections_bad_total 9470
telemt_handshake_timeouts_total 256
telemt_upstream_connect_attempt_total 402
telemt_upstream_connect_success_total 402
telemt_upstream_connect_attempts_per_request{bucket="1"} 402
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 234
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 168
telemt_me_reconnect_attempts_total 237
telemt_me_reconnect_success_total 236
telemt_me_reader_eof_total 208
telemt_me_idle_close_by_peer_total 208
telemt_me_route_drop_no_conn_total 17327
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 42251
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 67
telemt_desync_full_logged_total 32
telemt_desync_suppressed_total 35
telemt_desync_frames_bucket_total{bucket="1_2"} 10
telemt_desync_frames_bucket_total{bucket="3_10"} 33
telemt_desync_frames_bucket_total{bucket="gt_10"} 24
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 222
telemt_me_writer_restored_same_endpoint_total 228
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 130
telemt_user_connections_total{user="hello"} 40360
telemt_user_connections_current{user="hello"} 840
telemt_user_octets_from_client{user="hello"} 915974144 (873.54 MB)
telemt_user_octets_to_client{user="hello"} 10065080980 (9.37 GB)
telemt_user_unique_ips_current{user="hello"} 302
telemt_user_unique_ips_recent_window{user="hello"} 119
```

## 4vps.su

```
telemt 3.3.20

telemt_uptime_seconds 2515.0 (0h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 126150
telemt_connections_bad_total 803
telemt_handshake_timeouts_total 2067
telemt_upstream_connect_attempt_total 413
telemt_upstream_connect_success_total 399
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 413
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 238
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 154
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_reconnect_attempts_total 240
telemt_me_reconnect_success_total 231
telemt_me_reader_eof_total 195
telemt_me_idle_close_by_peer_total 195
telemt_me_route_drop_no_conn_total 105666
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 115813
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 331
telemt_desync_full_logged_total 106
telemt_desync_suppressed_total 225
telemt_desync_frames_bucket_total{bucket="1_2"} 52
telemt_desync_frames_bucket_total{bucket="3_10"} 135
telemt_desync_frames_bucket_total{bucket="gt_10"} 144
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 217
telemt_me_writer_restored_same_endpoint_total 221
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 2494
telemt_user_connections_total{user="hello"} 115723
telemt_user_connections_current{user="hello"} 2059
telemt_user_octets_from_client{user="hello"} 1463523140 (1.36 GB)
telemt_user_octets_to_client{user="hello"} 45618813840 (42.49 GB)
telemt_user_unique_ips_current{user="hello"} 599
telemt_user_unique_ips_recent_window{user="hello"} 258
```