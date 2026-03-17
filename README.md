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

# Server Metrics 2026-03-17 10:23:53 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 56310.4 (15h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 466695
telemt_connections_bad_total 3861
telemt_handshake_timeouts_total 12776
telemt_upstream_connect_attempt_total 14176
telemt_upstream_connect_success_total 13741
telemt_upstream_connect_fail_total 435
telemt_upstream_connect_attempts_per_request{bucket="1"} 14176
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7317
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6274
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 435
telemt_me_keepalive_timeout_total 104
telemt_me_reconnect_attempts_total 10168
telemt_me_reconnect_success_total 8638
telemt_me_reader_eof_total 9181
telemt_me_idle_close_by_peer_total 9180
telemt_me_route_drop_no_conn_total 147347
telemt_me_route_drop_channel_closed_total 40
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 422778
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3376
telemt_desync_full_logged_total 900
telemt_desync_suppressed_total 2476
telemt_desync_frames_bucket_total{bucket="1_2"} 907
telemt_desync_frames_bucket_total{bucket="3_10"} 1454
telemt_desync_frames_bucket_total{bucket="gt_10"} 1015
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 8815
telemt_me_refill_failed_total 43
telemt_me_writer_restored_same_endpoint_total 8616
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 177
telemt_user_connections_total{user="hello"} 424737
telemt_user_connections_current{user="hello"} 1033
telemt_user_octets_from_client{user="hello"} 6162636263 (5.74 GB)
telemt_user_octets_to_client{user="hello"} 164616079523 (153.31 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 337
telemt_user_unique_ips_recent_window{user="hello"} 131
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 56562.0 (15h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 253648
telemt_connections_bad_total 4152
telemt_handshake_timeouts_total 14996
telemt_upstream_connect_attempt_total 14541
telemt_upstream_connect_success_total 14338
telemt_upstream_connect_fail_total 203
telemt_upstream_connect_attempts_per_request{bucket="1"} 14541
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6178
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7996
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 164
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 203
telemt_me_keepalive_timeout_total 6
telemt_me_reconnect_attempts_total 20258
telemt_me_reconnect_success_total 11546
telemt_me_reader_eof_total 12392
telemt_me_idle_close_by_peer_total 12392
telemt_me_route_drop_no_conn_total 92684
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 222131
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 594
telemt_desync_full_logged_total 227
telemt_desync_suppressed_total 367
telemt_desync_frames_bucket_total{bucket="1_2"} 175
telemt_desync_frames_bucket_total{bucket="3_10"} 257
telemt_desync_frames_bucket_total{bucket="gt_10"} 162
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 11941
telemt_me_refill_failed_total 271
telemt_me_writer_restored_same_endpoint_total 11530
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 395
telemt_user_connections_total{user="hello"} 222130
telemt_user_connections_current{user="hello"} 467
telemt_user_octets_from_client{user="hello"} 2701182948 (2.52 GB)
telemt_user_octets_to_client{user="hello"} 83599998868 (77.86 GB)
telemt_user_unique_ips_current{user="hello"} 162
telemt_user_unique_ips_recent_window{user="hello"} 62
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 56339.4 (15h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 154998
telemt_connections_bad_total 7605
telemt_handshake_timeouts_total 11561
telemt_upstream_connect_attempt_total 15075
telemt_upstream_connect_success_total 14996
telemt_upstream_connect_fail_total 79
telemt_upstream_connect_attempts_per_request{bucket="1"} 15075
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6639
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8290
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 79
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 14022
telemt_me_reconnect_success_total 12155
telemt_me_reader_eof_total 12988
telemt_me_idle_close_by_peer_total 12988
telemt_me_route_drop_no_conn_total 46441
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 126149
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 435
telemt_desync_full_logged_total 113
telemt_desync_suppressed_total 322
telemt_desync_frames_bucket_total{bucket="1_2"} 176
telemt_desync_frames_bucket_total{bucket="3_10"} 184
telemt_desync_frames_bucket_total{bucket="gt_10"} 75
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 12378
telemt_me_refill_failed_total 56
telemt_me_writer_restored_same_endpoint_total 12144
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 223
telemt_user_connections_total{user="hello"} 126061
telemt_user_connections_current{user="hello"} 345
telemt_user_octets_from_client{user="hello"} 9696190344 (9.03 GB)
telemt_user_octets_to_client{user="hello"} 38398430632 (35.76 GB)
telemt_user_unique_ips_current{user="hello"} 108
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 56397.0 (15h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 346585
telemt_connections_bad_total 6216
telemt_handshake_timeouts_total 11539
telemt_upstream_connect_attempt_total 12860
telemt_upstream_connect_success_total 12741
telemt_upstream_connect_fail_total 119
telemt_upstream_connect_attempts_per_request{bucket="1"} 12860
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6029
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6629
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 75
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 119
telemt_me_keepalive_timeout_total 6
telemt_me_reconnect_attempts_total 10958
telemt_me_reconnect_success_total 9864
telemt_me_reader_eof_total 10488
telemt_me_idle_close_by_peer_total 10488
telemt_me_route_drop_no_conn_total 96933
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 282973
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 679
telemt_desync_full_logged_total 263
telemt_desync_suppressed_total 416
telemt_desync_frames_bucket_total{bucket="1_2"} 163
telemt_desync_frames_bucket_total{bucket="3_10"} 303
telemt_desync_frames_bucket_total{bucket="gt_10"} 213
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 10052
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 9856
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 188
telemt_user_connections_total{user="hello"} 282928
telemt_user_connections_current{user="hello"} 706
telemt_user_octets_from_client{user="hello"} 3431121598 (3.20 GB)
telemt_user_octets_to_client{user="hello"} 109372455785 (101.86 GB)
telemt_user_msgs_from_client{user="hello"} 65
telemt_user_msgs_to_client{user="hello"} 189
telemt_user_unique_ips_current{user="hello"} 193
telemt_user_unique_ips_recent_window{user="hello"} 103
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 56368.9 (15h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 189820
telemt_connections_bad_total 51171
telemt_handshake_timeouts_total 2884
telemt_upstream_connect_attempt_total 17206
telemt_upstream_connect_success_total 16983
telemt_upstream_connect_fail_total 223
telemt_upstream_connect_attempts_per_request{bucket="1"} 17206
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7578
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9196
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 209
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 223
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 22193
telemt_me_reconnect_success_total 14045
telemt_me_reader_eof_total 14899
telemt_me_idle_close_by_peer_total 14899
telemt_me_route_drop_no_conn_total 49232
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 130032
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 507
telemt_desync_full_logged_total 117
telemt_desync_suppressed_total 390
telemt_desync_frames_bucket_total{bucket="1_2"} 249
telemt_desync_frames_bucket_total{bucket="3_10"} 184
telemt_desync_frames_bucket_total{bucket="gt_10"} 74
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 14477
telemt_me_refill_failed_total 252
telemt_me_writer_restored_same_endpoint_total 14037
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 432
telemt_user_connections_total{user="hello"} 130060
telemt_user_connections_current{user="hello"} 288
telemt_user_octets_from_client{user="hello"} 1919295879 (1.79 GB)
telemt_user_octets_to_client{user="hello"} 58099153498 (54.11 GB)
telemt_user_msgs_from_client{user="hello"} 265
telemt_user_msgs_to_client{user="hello"} 707
telemt_user_unique_ips_current{user="hello"} 100
telemt_user_unique_ips_recent_window{user="hello"} 50
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 56530.0 (15h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 441491
telemt_connections_bad_total 50046
telemt_handshake_timeouts_total 4426
telemt_upstream_connect_attempt_total 11435
telemt_upstream_connect_success_total 11373
telemt_upstream_connect_fail_total 62
telemt_upstream_connect_attempts_per_request{bucket="1"} 11435
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5590
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5763
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 62
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 12455
telemt_me_reconnect_success_total 8571
telemt_me_reader_eof_total 9256
telemt_me_idle_close_by_peer_total 9256
telemt_me_route_drop_no_conn_total 286057
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 441793
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 669
telemt_desync_full_logged_total 256
telemt_desync_suppressed_total 413
telemt_desync_frames_bucket_total{bucket="1_2"} 181
telemt_desync_frames_bucket_total{bucket="3_10"} 256
telemt_desync_frames_bucket_total{bucket="gt_10"} 232
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 8823
telemt_me_refill_failed_total 120
telemt_me_writer_restored_same_endpoint_total 8557
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 252
telemt_user_connections_total{user="hello"} 363664
telemt_user_connections_current{user="hello"} 857
telemt_user_octets_from_client{user="hello"} 5235399752 (4.88 GB)
telemt_user_octets_to_client{user="hello"} 194891292520 (181.51 GB)
telemt_user_unique_ips_current{user="hello"} 286
telemt_user_unique_ips_recent_window{user="hello"} 122
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 4296.9 (1h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3728
telemt_connections_bad_total 26
telemt_handshake_timeouts_total 32
telemt_upstream_connect_attempt_total 1870
telemt_upstream_connect_success_total 1843
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 1870
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1030
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 813
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_reconnect_attempts_total 1505
telemt_me_reconnect_success_total 1475
telemt_me_reader_eof_total 1522
telemt_me_idle_close_by_peer_total 1522
telemt_me_seq_mismatch_total 3
telemt_me_route_drop_no_conn_total 1347
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3443
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 1495
telemt_me_writer_restored_same_endpoint_total 1469
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 3549
telemt_user_connections_current{user="hello"} 101
telemt_user_octets_from_client{user="hello"} 64040753 (61.07 MB)
telemt_user_octets_to_client{user="hello"} 16010034906 (14.91 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 23
telemt_user_unique_ips_recent_window{user="hello"} 7
```