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

# Server Metrics 2026-03-19 04:51:51 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 25403.3 (7h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 353415
telemt_connections_bad_total 36904
telemt_connections_current 1058
telemt_connections_me_current 1058
telemt_handshake_timeouts_total 20114
telemt_upstream_connect_attempt_total 4985
telemt_upstream_connect_success_total 4902
telemt_upstream_connect_fail_total 83
telemt_upstream_connect_attempts_per_request{bucket="1"} 4985
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2399
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2500
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 83
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 3631
telemt_me_reconnect_success_total 3614
telemt_me_reader_eof_total 3810
telemt_me_idle_close_by_peer_total 3809
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 91267
telemt_me_route_drop_channel_closed_total 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 259561
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1802
telemt_desync_full_logged_total 495
telemt_desync_suppressed_total 1307
telemt_desync_frames_bucket_total{bucket="1_2"} 667
telemt_desync_frames_bucket_total{bucket="3_10"} 731
telemt_desync_frames_bucket_total{bucket="gt_10"} 404
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 3643
telemt_me_writer_restored_same_endpoint_total 3597
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 256813
telemt_user_connections_current{user="hello"} 1058
telemt_user_octets_from_client{user="hello"} 2968539284 (2.76 GB)
telemt_user_octets_to_client{user="hello"} 80024087436 (74.53 GB)
telemt_user_unique_ips_current{user="hello"} 377
telemt_user_unique_ips_recent_window{user="hello"} 137
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 25407.5 (7h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 669466
telemt_connections_bad_total 40484
telemt_connections_current 2740
telemt_connections_me_current 2740
telemt_handshake_timeouts_total 20526
telemt_upstream_connect_attempt_total 4803
telemt_upstream_connect_success_total 4713
telemt_upstream_connect_fail_total 90
telemt_upstream_connect_attempts_per_request{bucket="1"} 4803
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2272
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2431
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 90
telemt_me_reconnect_attempts_total 3434
telemt_me_reconnect_success_total 3417
telemt_me_reader_eof_total 3608
telemt_me_idle_close_by_peer_total 3608
telemt_me_seq_mismatch_total 8
telemt_me_route_drop_no_conn_total 202169
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 555577
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 30
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2173
telemt_desync_full_logged_total 741
telemt_desync_suppressed_total 1432
telemt_desync_frames_bucket_total{bucket="1_2"} 434
telemt_desync_frames_bucket_total{bucket="3_10"} 803
telemt_desync_frames_bucket_total{bucket="gt_10"} 936
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 3476
telemt_me_writer_restored_same_endpoint_total 3399
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 59
telemt_user_connections_total{user="hello"} 555491
telemt_user_connections_current{user="hello"} 2740
telemt_user_octets_from_client{user="hello"} 15083006096 (14.05 GB)
telemt_user_octets_to_client{user="hello"} 244514522444 (227.72 GB)
telemt_user_unique_ips_current{user="hello"} 1010
telemt_user_unique_ips_recent_window{user="hello"} 387
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 25404.7 (7h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 567092
telemt_connections_bad_total 108482
telemt_connections_current 2164
telemt_connections_me_current 2164
telemt_handshake_timeouts_total 19433
telemt_upstream_connect_attempt_total 4693
telemt_upstream_connect_success_total 4693
telemt_upstream_connect_attempts_per_request{bucket="1"} 4693
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2380
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2306
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 3406
telemt_me_reconnect_success_total 3395
telemt_me_reader_eof_total 3593
telemt_me_idle_close_by_peer_total 3593
telemt_me_route_drop_no_conn_total 168087
telemt_me_route_drop_channel_closed_total 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 408077
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2201
telemt_desync_full_logged_total 717
telemt_desync_suppressed_total 1484
telemt_desync_frames_bucket_total{bucket="1_2"} 331
telemt_desync_frames_bucket_total{bucket="3_10"} 774
telemt_desync_frames_bucket_total{bucket="gt_10"} 1096
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 3452
telemt_me_writer_restored_same_endpoint_total 3379
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 408064
telemt_user_connections_current{user="hello"} 2164
telemt_user_octets_from_client{user="hello"} 8951473784 (8.34 GB)
telemt_user_octets_to_client{user="hello"} 257419186960 (239.74 GB)
telemt_user_unique_ips_current{user="hello"} 778
telemt_user_unique_ips_recent_window{user="hello"} 277
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 25457.9 (7h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 667434
telemt_connections_bad_total 85040
telemt_connections_current 1698
telemt_connections_me_current 1698
telemt_handshake_timeouts_total 14808
telemt_upstream_connect_attempt_total 4559
telemt_upstream_connect_success_total 4559
telemt_upstream_connect_attempts_per_request{bucket="1"} 4559
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2306
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2244
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_reconnect_attempts_total 3282
telemt_me_reconnect_success_total 3267
telemt_me_reader_eof_total 3449
telemt_me_idle_close_by_peer_total 3448
telemt_me_route_drop_no_conn_total 166144
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 402444
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1243
telemt_desync_full_logged_total 455
telemt_desync_suppressed_total 788
telemt_desync_frames_bucket_total{bucket="1_2"} 231
telemt_desync_frames_bucket_total{bucket="3_10"} 531
telemt_desync_frames_bucket_total{bucket="gt_10"} 481
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 3306
telemt_me_writer_restored_same_endpoint_total 3243
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 272
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 402211
telemt_user_connections_current{user="hello"} 1698
telemt_user_octets_from_client{user="hello"} 4975240636 (4.63 GB)
telemt_user_octets_to_client{user="hello"} 154890637816 (144.25 GB)
telemt_user_unique_ips_current{user="hello"} 651
telemt_user_unique_ips_recent_window{user="hello"} 254
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 25401.3 (7h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 738286
telemt_connections_bad_total 200251
telemt_connections_current 2070
telemt_connections_me_current 2070
telemt_handshake_timeouts_total 20472
telemt_upstream_connect_attempt_total 4687
telemt_upstream_connect_success_total 4658
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 4687
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2340
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2302
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_reconnect_attempts_total 3379
telemt_me_reconnect_success_total 3359
telemt_me_reader_eof_total 3552
telemt_me_idle_close_by_peer_total 3552
telemt_me_route_drop_no_conn_total 182509
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 437513
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1937
telemt_desync_full_logged_total 740
telemt_desync_suppressed_total 1197
telemt_desync_frames_bucket_total{bucket="1_2"} 454
telemt_desync_frames_bucket_total{bucket="3_10"} 817
telemt_desync_frames_bucket_total{bucket="gt_10"} 666
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 3392
telemt_me_writer_restored_same_endpoint_total 3335
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 437432
telemt_user_connections_current{user="hello"} 2070
telemt_user_octets_from_client{user="hello"} 13424710840 (12.50 GB)
telemt_user_octets_to_client{user="hello"} 255430249548 (237.89 GB)
telemt_user_unique_ips_current{user="hello"} 794
telemt_user_unique_ips_recent_window{user="hello"} 280
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 25412.9 (7h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 130724
telemt_connections_bad_total 10341
telemt_connections_current 476
telemt_connections_me_current 476
telemt_handshake_timeouts_total 598
telemt_upstream_connect_attempt_total 6994
telemt_upstream_connect_success_total 6805
telemt_upstream_connect_fail_total 189
telemt_upstream_connect_attempts_per_request{bucket="1"} 6994
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3236
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3569
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 189
telemt_me_reconnect_attempts_total 7354
telemt_me_reconnect_success_total 5511
telemt_me_reader_eof_total 5790
telemt_me_idle_close_by_peer_total 5790
telemt_me_route_drop_no_conn_total 53339
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 114738
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 128
telemt_desync_full_logged_total 47
telemt_desync_suppressed_total 81
telemt_desync_frames_bucket_total{bucket="1_2"} 43
telemt_desync_frames_bucket_total{bucket="3_10"} 53
telemt_desync_frames_bucket_total{bucket="gt_10"} 32
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 5585
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 5481
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 74
telemt_user_connections_total{user="hello"} 114730
telemt_user_connections_current{user="hello"} 476
telemt_user_octets_from_client{user="hello"} 2060685428 (1.92 GB)
telemt_user_octets_to_client{user="hello"} 72884971824 (67.88 GB)
telemt_user_unique_ips_current{user="hello"} 206
telemt_user_unique_ips_recent_window{user="hello"} 70
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 25403.7 (7h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 432331
telemt_connections_bad_total 47450
telemt_connections_current 1939
telemt_connections_me_current 1939
telemt_handshake_timeouts_total 22456
telemt_upstream_connect_attempt_total 5254
telemt_upstream_connect_success_total 5254
telemt_upstream_connect_attempts_per_request{bucket="1"} 5254
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2795
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2456
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 3976
telemt_me_reconnect_success_total 3964
telemt_me_reader_eof_total 4185
telemt_me_idle_close_by_peer_total 4185
telemt_me_route_drop_no_conn_total 121371
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 349025
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1871
telemt_desync_full_logged_total 705
telemt_desync_suppressed_total 1166
telemt_desync_frames_bucket_total{bucket="1_2"} 377
telemt_desync_frames_bucket_total{bucket="3_10"} 722
telemt_desync_frames_bucket_total{bucket="gt_10"} 772
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 4007
telemt_me_writer_restored_same_endpoint_total 3949
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 349038
telemt_user_connections_current{user="hello"} 1939
telemt_user_octets_from_client{user="hello"} 4301426184 (4.01 GB)
telemt_user_octets_to_client{user="hello"} 204242337084 (190.22 GB)
telemt_user_unique_ips_current{user="hello"} 645
telemt_user_unique_ips_recent_window{user="hello"} 227
```