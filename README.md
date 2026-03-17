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

# Server Metrics 2026-03-17 10:08:35 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 55393.2 (15h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 451771
telemt_connections_bad_total 3770
telemt_handshake_timeouts_total 12668
telemt_upstream_connect_attempt_total 14014
telemt_upstream_connect_success_total 13581
telemt_upstream_connect_fail_total 433
telemt_upstream_connect_attempts_per_request{bucket="1"} 14014
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7228
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6203
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 433
telemt_me_keepalive_timeout_total 104
telemt_me_reconnect_attempts_total 10051
telemt_me_reconnect_success_total 8521
telemt_me_reader_eof_total 9055
telemt_me_idle_close_by_peer_total 9054
telemt_me_route_drop_no_conn_total 142917
telemt_me_route_drop_channel_closed_total 40
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 408554
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3291
telemt_desync_full_logged_total 874
telemt_desync_suppressed_total 2417
telemt_desync_frames_bucket_total{bucket="1_2"} 870
telemt_desync_frames_bucket_total{bucket="3_10"} 1417
telemt_desync_frames_bucket_total{bucket="gt_10"} 1004
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 8698
telemt_me_refill_failed_total 43
telemt_me_writer_restored_same_endpoint_total 8499
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 177
telemt_user_connections_total{user="hello"} 410517
telemt_user_connections_current{user="hello"} 947
telemt_user_octets_from_client{user="hello"} 5928686071 (5.52 GB)
telemt_user_octets_to_client{user="hello"} 161153611267 (150.09 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 327
telemt_user_unique_ips_recent_window{user="hello"} 128
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 55644.7 (15h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 244856
telemt_connections_bad_total 2663
telemt_handshake_timeouts_total 14344
telemt_upstream_connect_attempt_total 14316
telemt_upstream_connect_success_total 14120
telemt_upstream_connect_fail_total 196
telemt_upstream_connect_attempts_per_request{bucket="1"} 14316
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6084
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7884
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 152
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 196
telemt_me_keepalive_timeout_total 6
telemt_me_reconnect_attempts_total 20083
telemt_me_reconnect_success_total 11373
telemt_me_reader_eof_total 12211
telemt_me_idle_close_by_peer_total 12211
telemt_me_route_drop_no_conn_total 89815
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 215712
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 575
telemt_desync_full_logged_total 220
telemt_desync_suppressed_total 355
telemt_desync_frames_bucket_total{bucket="1_2"} 172
telemt_desync_frames_bucket_total{bucket="3_10"} 250
telemt_desync_frames_bucket_total{bucket="gt_10"} 153
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 11760
telemt_me_refill_failed_total 271
telemt_me_writer_restored_same_endpoint_total 11357
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 387
telemt_user_connections_total{user="hello"} 215712
telemt_user_connections_current{user="hello"} 519
telemt_user_octets_from_client{user="hello"} 2637567316 (2.46 GB)
telemt_user_octets_to_client{user="hello"} 81911828980 (76.29 GB)
telemt_user_unique_ips_current{user="hello"} 156
telemt_user_unique_ips_recent_window{user="hello"} 61
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 55420.8 (15h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 150389
telemt_connections_bad_total 7600
telemt_handshake_timeouts_total 10985
telemt_upstream_connect_attempt_total 14793
telemt_upstream_connect_success_total 14715
telemt_upstream_connect_fail_total 78
telemt_upstream_connect_attempts_per_request{bucket="1"} 14793
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6529
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8121
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 78
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 12889
telemt_me_reconnect_success_total 11920
telemt_me_reader_eof_total 12721
telemt_me_idle_close_by_peer_total 12721
telemt_me_route_drop_no_conn_total 45254
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 122222
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 382
telemt_desync_full_logged_total 103
telemt_desync_suppressed_total 279
telemt_desync_frames_bucket_total{bucket="1_2"} 142
telemt_desync_frames_bucket_total{bucket="3_10"} 165
telemt_desync_frames_bucket_total{bucket="gt_10"} 75
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 12108
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 11909
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 188
telemt_user_connections_total{user="hello"} 122141
telemt_user_connections_current{user="hello"} 349
telemt_user_octets_from_client{user="hello"} 9642883440 (8.98 GB)
telemt_user_octets_to_client{user="hello"} 37768961188 (35.18 GB)
telemt_user_unique_ips_current{user="hello"} 106
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 55480.0 (15h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 333843
telemt_connections_bad_total 6198
telemt_handshake_timeouts_total 11423
telemt_upstream_connect_attempt_total 12704
telemt_upstream_connect_success_total 12585
telemt_upstream_connect_fail_total 119
telemt_upstream_connect_attempts_per_request{bucket="1"} 12704
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5946
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6557
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 74
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 119
telemt_me_keepalive_timeout_total 6
telemt_me_reconnect_attempts_total 10846
telemt_me_reconnect_success_total 9754
telemt_me_reader_eof_total 10368
telemt_me_idle_close_by_peer_total 10368
telemt_me_route_drop_no_conn_total 93412
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 271084
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 609
telemt_desync_full_logged_total 241
telemt_desync_suppressed_total 368
telemt_desync_frames_bucket_total{bucket="1_2"} 143
telemt_desync_frames_bucket_total{bucket="3_10"} 268
telemt_desync_frames_bucket_total{bucket="gt_10"} 198
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 9939
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 9746
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 185
telemt_user_connections_total{user="hello"} 271043
telemt_user_connections_current{user="hello"} 792
telemt_user_octets_from_client{user="hello"} 3333711398 (3.10 GB)
telemt_user_octets_to_client{user="hello"} 106647982709 (99.32 GB)
telemt_user_msgs_from_client{user="hello"} 65
telemt_user_msgs_to_client{user="hello"} 189
telemt_user_unique_ips_current{user="hello"} 213
telemt_user_unique_ips_recent_window{user="hello"} 105
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 55451.8 (15h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 185275
telemt_connections_bad_total 50815
telemt_handshake_timeouts_total 2844
telemt_upstream_connect_attempt_total 16935
telemt_upstream_connect_success_total 16715
telemt_upstream_connect_fail_total 220
telemt_upstream_connect_attempts_per_request{bucket="1"} 16935
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7464
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9043
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 220
telemt_me_reconnect_attempts_total 20948
telemt_me_reconnect_success_total 13824
telemt_me_reader_eof_total 14642
telemt_me_idle_close_by_peer_total 14642
telemt_me_route_drop_no_conn_total 48110
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 126091
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 429
telemt_desync_full_logged_total 108
telemt_desync_suppressed_total 321
telemt_desync_frames_bucket_total{bucket="1_2"} 199
telemt_desync_frames_bucket_total{bucket="3_10"} 162
telemt_desync_frames_bucket_total{bucket="gt_10"} 68
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 14220
telemt_me_refill_failed_total 220
telemt_me_writer_restored_same_endpoint_total 13816
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 396
telemt_user_connections_total{user="hello"} 126123
telemt_user_connections_current{user="hello"} 322
telemt_user_octets_from_client{user="hello"} 1886419947 (1.76 GB)
telemt_user_octets_to_client{user="hello"} 56850596474 (52.95 GB)
telemt_user_msgs_from_client{user="hello"} 265
telemt_user_msgs_to_client{user="hello"} 707
telemt_user_unique_ips_current{user="hello"} 110
telemt_user_unique_ips_recent_window{user="hello"} 47
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 55612.9 (15h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 430877
telemt_connections_bad_total 49456
telemt_handshake_timeouts_total 4363
telemt_upstream_connect_attempt_total 11290
telemt_upstream_connect_success_total 11228
telemt_upstream_connect_fail_total 62
telemt_upstream_connect_attempts_per_request{bucket="1"} 11290
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5520
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5688
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 62
telemt_me_keepalive_timeout_total 16
telemt_me_reconnect_attempts_total 12353
telemt_me_reconnect_success_total 8469
telemt_me_reader_eof_total 9146
telemt_me_idle_close_by_peer_total 9146
telemt_me_route_drop_no_conn_total 281757
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 432178
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 624
telemt_desync_full_logged_total 246
telemt_desync_suppressed_total 378
telemt_desync_frames_bucket_total{bucket="1_2"} 171
telemt_desync_frames_bucket_total{bucket="3_10"} 234
telemt_desync_frames_bucket_total{bucket="gt_10"} 219
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 8720
telemt_me_refill_failed_total 120
telemt_me_writer_restored_same_endpoint_total 8455
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 251
telemt_user_connections_total{user="hello"} 354055
telemt_user_connections_current{user="hello"} 831
telemt_user_octets_from_client{user="hello"} 5121377776 (4.77 GB)
telemt_user_octets_to_client{user="hello"} 192884768112 (179.64 GB)
telemt_user_unique_ips_current{user="hello"} 273
telemt_user_unique_ips_recent_window{user="hello"} 119
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 3380.1 (0h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3115
telemt_connections_bad_total 6
telemt_handshake_timeouts_total 28
telemt_upstream_connect_attempt_total 1375
telemt_upstream_connect_success_total 1351
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 1375
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 751
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 600
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_reconnect_attempts_total 1060
telemt_me_reconnect_success_total 1031
telemt_me_reader_eof_total 1073
telemt_me_idle_close_by_peer_total 1073
telemt_me_seq_mismatch_total 3
telemt_me_route_drop_no_conn_total 1095
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2863
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 1045
telemt_me_writer_restored_same_endpoint_total 1025
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 2969
telemt_user_connections_current{user="hello"} 73
telemt_user_octets_from_client{user="hello"} 42888369 (40.90 MB)
telemt_user_octets_to_client{user="hello"} 12041814754 (11.21 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 18
telemt_user_unique_ips_recent_window{user="hello"} 9
```