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

# Server Metrics 2026-03-18 23:19:34 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 5466.6 (1h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 65013
telemt_connections_bad_total 6520
telemt_connections_current 671
telemt_connections_me_current 671
telemt_handshake_timeouts_total 727
telemt_upstream_connect_attempt_total 986
telemt_upstream_connect_success_total 974
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 986
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 462
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 510
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 671
telemt_me_reconnect_success_total 669
telemt_me_reader_eof_total 674
telemt_me_idle_close_by_peer_total 674
telemt_me_seq_mismatch_total 1
telemt_me_route_drop_no_conn_total 22737
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 57220
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 299
telemt_desync_full_logged_total 103
telemt_desync_suppressed_total 196
telemt_desync_frames_bucket_total{bucket="1_2"} 67
telemt_desync_frames_bucket_total{bucket="3_10"} 125
telemt_desync_frames_bucket_total{bucket="gt_10"} 107
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 664
telemt_me_writer_restored_same_endpoint_total 658
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 136
telemt_user_connections_total{user="hello"} 54464
telemt_user_connections_current{user="hello"} 671
telemt_user_octets_from_client{user="hello"} 568193372 (541.87 MB)
telemt_user_octets_to_client{user="hello"} 23667798908 (22.04 GB)
telemt_user_unique_ips_current{user="hello"} 278
telemt_user_unique_ips_recent_window{user="hello"} 82
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 5470.4 (1h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 155171
telemt_connections_bad_total 12720
telemt_connections_current 1606
telemt_connections_me_current 1606
telemt_handshake_timeouts_total 1220
telemt_upstream_connect_attempt_total 1016
telemt_upstream_connect_success_total 987
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 1016
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 477
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 505
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_reconnect_attempts_total 690
telemt_me_reconnect_success_total 689
telemt_me_reader_eof_total 697
telemt_me_idle_close_by_peer_total 697
telemt_me_seq_mismatch_total 2
telemt_me_route_drop_no_conn_total 49032
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 132900
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 519
telemt_desync_full_logged_total 176
telemt_desync_suppressed_total 343
telemt_desync_frames_bucket_total{bucket="1_2"} 95
telemt_desync_frames_bucket_total{bucket="3_10"} 185
telemt_desync_frames_bucket_total{bucket="gt_10"} 239
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 703
telemt_me_writer_restored_same_endpoint_total 678
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 132980
telemt_user_connections_current{user="hello"} 1606
telemt_user_octets_from_client{user="hello"} 9971452376 (9.29 GB)
telemt_user_octets_to_client{user="hello"} 51916257180 (48.35 GB)
telemt_user_unique_ips_current{user="hello"} 645
telemt_user_unique_ips_recent_window{user="hello"} 129
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 5467.6 (1h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 121640
telemt_connections_bad_total 17759
telemt_connections_current 1151
telemt_connections_me_current 1151
telemt_handshake_timeouts_total 3418
telemt_upstream_connect_attempt_total 1048
telemt_upstream_connect_success_total 1048
telemt_upstream_connect_attempts_per_request{bucket="1"} 1048
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 542
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 506
telemt_me_reconnect_attempts_total 735
telemt_me_reconnect_success_total 734
telemt_me_reader_eof_total 747
telemt_me_idle_close_by_peer_total 747
telemt_me_route_drop_no_conn_total 41602
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 97079
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 416
telemt_desync_full_logged_total 164
telemt_desync_suppressed_total 252
telemt_desync_frames_bucket_total{bucket="1_2"} 79
telemt_desync_frames_bucket_total{bucket="3_10"} 172
telemt_desync_frames_bucket_total{bucket="gt_10"} 165
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 742
telemt_me_writer_restored_same_endpoint_total 718
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 8
telemt_user_connections_total{user="hello"} 97081
telemt_user_connections_current{user="hello"} 1151
telemt_user_octets_from_client{user="hello"} 1347215104 (1.25 GB)
telemt_user_octets_to_client{user="hello"} 61964386884 (57.71 GB)
telemt_user_unique_ips_current{user="hello"} 519
telemt_user_unique_ips_recent_window{user="hello"} 124
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 5520.8 (1h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 134988
telemt_connections_bad_total 23354
telemt_connections_current 1046
telemt_connections_me_current 1046
telemt_handshake_timeouts_total 2952
telemt_upstream_connect_attempt_total 975
telemt_upstream_connect_success_total 975
telemt_upstream_connect_attempts_per_request{bucket="1"} 975
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 524
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 448
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 652
telemt_me_reconnect_success_total 649
telemt_me_reader_eof_total 660
telemt_me_idle_close_by_peer_total 660
telemt_me_route_drop_no_conn_total 54824
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 102533
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 254
telemt_desync_full_logged_total 93
telemt_desync_suppressed_total 161
telemt_desync_frames_bucket_total{bucket="1_2"} 50
telemt_desync_frames_bucket_total{bucket="3_10"} 103
telemt_desync_frames_bucket_total{bucket="gt_10"} 101
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 660
telemt_me_writer_restored_same_endpoint_total 625
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 268
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 102462
telemt_user_connections_current{user="hello"} 1046
telemt_user_octets_from_client{user="hello"} 1054293932 (1005.45 MB)
telemt_user_octets_to_client{user="hello"} 38184549708 (35.56 GB)
telemt_user_unique_ips_current{user="hello"} 443
telemt_user_unique_ips_recent_window{user="hello"} 91
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 5464.4 (1h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 132279
telemt_connections_bad_total 6072
telemt_connections_current 1262
telemt_connections_me_current 1262
telemt_handshake_timeouts_total 4137
telemt_upstream_connect_attempt_total 976
telemt_upstream_connect_success_total 969
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 975
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 489
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 477
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_reconnect_attempts_total 661
telemt_me_reconnect_success_total 659
telemt_me_reader_eof_total 666
telemt_me_idle_close_by_peer_total 666
telemt_me_route_drop_no_conn_total 39755
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 104710
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 460
telemt_desync_full_logged_total 187
telemt_desync_suppressed_total 273
telemt_desync_frames_bucket_total{bucket="1_2"} 122
telemt_desync_frames_bucket_total{bucket="3_10"} 162
telemt_desync_frames_bucket_total{bucket="gt_10"} 176
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 661
telemt_me_writer_restored_same_endpoint_total 635
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 104668
telemt_user_connections_current{user="hello"} 1262
telemt_user_octets_from_client{user="hello"} 1356604720 (1.26 GB)
telemt_user_octets_to_client{user="hello"} 63108670692 (58.77 GB)
telemt_user_unique_ips_current{user="hello"} 540
telemt_user_unique_ips_recent_window{user="hello"} 122
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 5475.9 (1h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 30779
telemt_connections_bad_total 6203
telemt_connections_current 391
telemt_connections_me_current 391
telemt_handshake_timeouts_total 86
telemt_upstream_connect_attempt_total 1697
telemt_upstream_connect_success_total 1644
telemt_upstream_connect_fail_total 52
telemt_upstream_connect_attempts_per_request{bucket="1"} 1696
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 914
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 730
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 52
telemt_me_reconnect_attempts_total 2144
telemt_me_reconnect_success_total 1342
telemt_me_reader_eof_total 1338
telemt_me_idle_close_by_peer_total 1338
telemt_me_route_drop_no_conn_total 10180
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 23787
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 24
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 18
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 10
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 1341
telemt_me_refill_failed_total 25
telemt_me_writer_restored_same_endpoint_total 1312
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_user_connections_total{user="hello"} 23787
telemt_user_connections_current{user="hello"} 391
telemt_user_octets_from_client{user="hello"} 301159764 (287.21 MB)
telemt_user_octets_to_client{user="hello"} 18322034696 (17.06 GB)
telemt_user_unique_ips_current{user="hello"} 165
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 5466.6 (1h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 98975
telemt_connections_bad_total 13230
telemt_connections_current 1074
telemt_connections_me_current 1074
telemt_handshake_timeouts_total 3234
telemt_upstream_connect_attempt_total 998
telemt_upstream_connect_success_total 998
telemt_upstream_connect_attempts_per_request{bucket="1"} 998
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 519
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 478
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 685
telemt_me_reconnect_success_total 683
telemt_me_reader_eof_total 695
telemt_me_idle_close_by_peer_total 695
telemt_me_route_drop_no_conn_total 29710
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 80368
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 589
telemt_desync_full_logged_total 223
telemt_desync_suppressed_total 366
telemt_desync_frames_bucket_total{bucket="1_2"} 105
telemt_desync_frames_bucket_total{bucket="3_10"} 243
telemt_desync_frames_bucket_total{bucket="gt_10"} 241
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 692
telemt_me_writer_restored_same_endpoint_total 668
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 80386
telemt_user_connections_current{user="hello"} 1074
telemt_user_octets_from_client{user="hello"} 847066584 (807.83 MB)
telemt_user_octets_to_client{user="hello"} 46291738668 (43.11 GB)
telemt_user_unique_ips_current{user="hello"} 476
telemt_user_unique_ips_recent_window{user="hello"} 82
```