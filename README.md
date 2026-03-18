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

# Server Metrics 2026-03-18 09:36:01 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.20

telemt_uptime_seconds 3300.4 (0h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 140580
telemt_connections_bad_total 427
telemt_handshake_timeouts_total 2699
telemt_upstream_connect_attempt_total 63545
telemt_upstream_connect_success_total 62632
telemt_upstream_connect_fail_total 913
telemt_upstream_connect_attempts_per_request{bucket="1"} 63545
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 59220
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2830
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 582
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 913
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 506005
telemt_me_reconnect_success_total 488
telemt_me_reader_eof_total 394
telemt_me_idle_close_by_peer_total 392
telemt_me_route_drop_no_conn_total 22002
telemt_me_route_drop_channel_closed_total 16
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 57760
telemt_me_writer_pick_total{mode="p2c",result="full"} 21
telemt_me_writer_pick_total{mode="p2c",result="closed"} 54
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 289
telemt_desync_full_logged_total 81
telemt_desync_suppressed_total 208
telemt_desync_frames_bucket_total{bucket="1_2"} 94
telemt_desync_frames_bucket_total{bucket="3_10"} 100
telemt_desync_frames_bucket_total{bucket="gt_10"} 95
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 435
telemt_me_refill_failed_total 16481
telemt_me_writer_restored_same_endpoint_total 383
telemt_me_writer_restored_fallback_total 105
telemt_me_async_recovery_trigger_total 11769
telemt_user_connections_total{user="hello"} 119635
telemt_user_connections_current{user="hello"} 1583
telemt_user_octets_from_client{user="hello"} 1482933600 (1.38 GB)
telemt_user_octets_to_client{user="hello"} 24589683969 (22.90 GB)
telemt_user_msgs_from_client{user="hello"} 846607
telemt_user_msgs_to_client{user="hello"} 1165163
telemt_user_unique_ips_current{user="hello"} 482
telemt_user_unique_ips_recent_window{user="hello"} 235
```

## psb.hosting

```
telemt 3.3.20

telemt_uptime_seconds 3331.7 (0h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 303752
telemt_connections_bad_total 36851
telemt_handshake_timeouts_total 7243
telemt_upstream_connect_attempt_total 579
telemt_upstream_connect_success_total 579
telemt_upstream_connect_attempts_per_request{bucket="1"} 579
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 362
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 212
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_failed_total 1
telemt_me_reconnect_attempts_total 377
telemt_me_reconnect_success_total 367
telemt_me_reader_eof_total 329
telemt_me_idle_close_by_peer_total 329
telemt_me_route_drop_no_conn_total 94190
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 236910
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1134
telemt_desync_full_logged_total 280
telemt_desync_suppressed_total 854
telemt_desync_frames_bucket_total{bucket="1_2"} 222
telemt_desync_frames_bucket_total{bucket="3_10"} 453
telemt_desync_frames_bucket_total{bucket="gt_10"} 459
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 342
telemt_me_writer_restored_same_endpoint_total 366
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 1068
telemt_user_connections_total{user="hello"} 236181
telemt_user_connections_current{user="hello"} 3797
telemt_user_octets_from_client{user="hello"} 6682999344 (6.22 GB)
telemt_user_octets_to_client{user="hello"} 82456616676 (76.79 GB)
telemt_user_unique_ips_current{user="hello"} 1101
telemt_user_unique_ips_recent_window{user="hello"} 515
```

## koara.io

```
telemt 3.3.20

telemt_uptime_seconds 3246.5 (0h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 258653
telemt_connections_bad_total 13368
telemt_handshake_timeouts_total 6236
telemt_upstream_connect_attempt_total 8868
telemt_upstream_connect_success_total 8868
telemt_upstream_connect_attempts_per_request{bucket="1"} 8868
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7306
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1556
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 40
telemt_me_reconnect_attempts_total 606132
telemt_me_reconnect_success_total 463
telemt_me_reader_eof_total 425
telemt_me_idle_close_by_peer_total 424
telemt_me_route_drop_no_conn_total 141796
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 181858
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 428
telemt_desync_full_logged_total 151
telemt_desync_suppressed_total 277
telemt_desync_frames_bucket_total{bucket="1_2"} 83
telemt_desync_frames_bucket_total{bucket="3_10"} 197
telemt_desync_frames_bucket_total{bucket="gt_10"} 148
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 450
telemt_me_refill_failed_total 19672
telemt_me_writer_restored_same_endpoint_total 428
telemt_me_writer_restored_fallback_total 35
telemt_me_async_recovery_trigger_total 14895
telemt_user_connections_total{user="hello"} 189929
telemt_user_connections_current{user="hello"} 2731
telemt_user_octets_from_client{user="hello"} 1690513139 (1.57 GB)
telemt_user_octets_to_client{user="hello"} 55315364488 (51.52 GB)
telemt_user_msgs_from_client{user="hello"} 68547
telemt_user_msgs_to_client{user="hello"} 285346
telemt_user_unique_ips_current{user="hello"} 756
telemt_user_unique_ips_recent_window{user="hello"} 364
```

## landvps.ru

```
telemt 3.3.20

telemt_uptime_seconds 3276.9 (0h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 473805
telemt_connections_bad_total 5844
telemt_handshake_timeouts_total 53858
telemt_upstream_connect_attempt_total 11331
telemt_upstream_connect_success_total 11236
telemt_upstream_connect_fail_total 95
telemt_upstream_connect_attempts_per_request{bucket="1"} 11331
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10242
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 961
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 95
telemt_me_keepalive_timeout_total 355
telemt_me_reconnect_attempts_total 2811862
telemt_me_reconnect_success_total 753
telemt_me_reader_eof_total 760
telemt_me_idle_close_by_peer_total 760
telemt_me_route_drop_no_conn_total 388365
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 363938
telemt_me_writer_pick_total{mode="p2c",result="success_fallback"} 6263
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_writer_pick_blocking_fallback_total 6263
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 435
telemt_desync_full_logged_total 136
telemt_desync_suppressed_total 299
telemt_desync_frames_bucket_total{bucket="1_2"} 96
telemt_desync_frames_bucket_total{bucket="3_10"} 184
telemt_desync_frames_bucket_total{bucket="gt_10"} 155
telemt_me_writer_removed_unexpected_total 783
telemt_me_refill_failed_total 99585
telemt_me_writer_restored_same_endpoint_total 658
telemt_me_writer_restored_fallback_total 95
telemt_me_async_recovery_trigger_total 365465
telemt_me_writer_removed_unexpected_minus_restored_total 30
telemt_user_connections_total{user="hello"} 380358
telemt_user_connections_current{user="hello"} 4111
telemt_user_octets_from_client{user="hello"} 2458652678 (2.29 GB)
telemt_user_octets_to_client{user="hello"} 43532378969 (40.54 GB)
telemt_user_msgs_from_client{user="hello"} 80007
telemt_user_msgs_to_client{user="hello"} 158054
telemt_user_unique_ips_current{user="hello"} 911
telemt_user_unique_ips_recent_window{user="hello"} 770
```

## rdp-onedash.ru

```
telemt 3.3.20

telemt_uptime_seconds 3171.7 (0h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 223155
telemt_connections_bad_total 7989
telemt_handshake_timeouts_total 2584
telemt_upstream_connect_attempt_total 10280
telemt_upstream_connect_success_total 10279
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 10280
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9388
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 685
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 206
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 2982521
telemt_me_reconnect_success_total 573
telemt_me_reader_eof_total 508
telemt_me_idle_close_by_peer_total 508
telemt_me_route_drop_no_conn_total 61966
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 174480
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 474
telemt_desync_full_logged_total 178
telemt_desync_suppressed_total 296
telemt_desync_frames_bucket_total{bucket="1_2"} 73
telemt_desync_frames_bucket_total{bucket="3_10"} 171
telemt_desync_frames_bucket_total{bucket="gt_10"} 230
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 519
telemt_me_refill_failed_total 107153
telemt_me_writer_restored_same_endpoint_total 458
telemt_me_writer_restored_fallback_total 115
telemt_me_async_recovery_trigger_total 267383
telemt_user_connections_total{user="hello"} 183846
telemt_user_connections_current{user="hello"} 3112
telemt_user_octets_from_client{user="hello"} 3490353045 (3.25 GB)
telemt_user_octets_to_client{user="hello"} 73965936497 (68.89 GB)
telemt_user_msgs_from_client{user="hello"} 86293
telemt_user_msgs_to_client{user="hello"} 266108
telemt_user_unique_ips_current{user="hello"} 923
telemt_user_unique_ips_recent_window{user="hello"} 454
```

## hostvds.com

```
telemt 3.3.20

telemt_uptime_seconds 3056.5 (0h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 64897
telemt_connections_bad_total 9773
telemt_handshake_timeouts_total 357
telemt_upstream_connect_attempt_total 521
telemt_upstream_connect_success_total 521
telemt_upstream_connect_attempts_per_request{bucket="1"} 521
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 297
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 224
telemt_me_reconnect_attempts_total 313
telemt_me_reconnect_success_total 311
telemt_me_reader_eof_total 292
telemt_me_idle_close_by_peer_total 292
telemt_me_route_drop_no_conn_total 21560
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 52418
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 91
telemt_desync_full_logged_total 40
telemt_desync_suppressed_total 51
telemt_desync_frames_bucket_total{bucket="1_2"} 14
telemt_desync_frames_bucket_total{bucket="3_10"} 44
telemt_desync_frames_bucket_total{bucket="gt_10"} 33
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 299
telemt_me_writer_restored_same_endpoint_total 303
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 130
telemt_user_connections_total{user="hello"} 50041
telemt_user_connections_current{user="hello"} 910
telemt_user_octets_from_client{user="hello"} 1038653976 (990.54 MB)
telemt_user_octets_to_client{user="hello"} 12286514408 (11.44 GB)
telemt_user_unique_ips_current{user="hello"} 324
telemt_user_unique_ips_recent_window{user="hello"} 127
```

## 4vps.su

```
telemt 3.3.20

telemt_uptime_seconds 3127.7 (0h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 159292
telemt_connections_bad_total 4487
telemt_handshake_timeouts_total 2306
telemt_upstream_connect_attempt_total 534
telemt_upstream_connect_success_total 517
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 534
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 296
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 214
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_reconnect_attempts_total 315
telemt_me_reconnect_success_total 306
telemt_me_reader_eof_total 275
telemt_me_idle_close_by_peer_total 275
telemt_me_route_drop_no_conn_total 113701
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 142340
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 418
telemt_desync_full_logged_total 131
telemt_desync_suppressed_total 287
telemt_desync_frames_bucket_total{bucket="1_2"} 82
telemt_desync_frames_bucket_total{bucket="3_10"} 168
telemt_desync_frames_bucket_total{bucket="gt_10"} 168
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 292
telemt_me_writer_restored_same_endpoint_total 296
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 2494
telemt_user_connections_total{user="hello"} 142229
telemt_user_connections_current{user="hello"} 2709
telemt_user_octets_from_client{user="hello"} 1970738824 (1.84 GB)
telemt_user_octets_to_client{user="hello"} 58364541584 (54.36 GB)
telemt_user_unique_ips_current{user="hello"} 696
telemt_user_unique_ips_recent_window{user="hello"} 337
```