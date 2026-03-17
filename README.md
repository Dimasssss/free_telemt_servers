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

# Server Metrics 2026-03-17 13:48:06 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 68569.6 (19h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 692804
telemt_connections_bad_total 5632
telemt_handshake_timeouts_total 20532
telemt_upstream_connect_attempt_total 16869
telemt_upstream_connect_success_total 16415
telemt_upstream_connect_fail_total 454
telemt_upstream_connect_attempts_per_request{bucket="1"} 16869
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8578
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7687
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 454
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 121
telemt_me_reconnect_attempts_total 17977
telemt_me_reconnect_success_total 10676
telemt_me_reader_eof_total 11459
telemt_me_idle_close_by_peer_total 11458
telemt_me_route_drop_no_conn_total 243631
telemt_me_route_drop_channel_closed_total 71
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 627947
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4522
telemt_desync_full_logged_total 1257
telemt_desync_suppressed_total 3265
telemt_desync_frames_bucket_total{bucket="1_2"} 1280
telemt_desync_frames_bucket_total{bucket="3_10"} 1854
telemt_desync_frames_bucket_total{bucket="gt_10"} 1388
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 11056
telemt_me_refill_failed_total 223
telemt_me_writer_restored_same_endpoint_total 10654
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 380
telemt_user_connections_total{user="hello"} 629833
telemt_user_connections_current{user="hello"} 933
telemt_user_octets_from_client{user="hello"} 10132173971 (9.44 GB)
telemt_user_octets_to_client{user="hello"} 219281356319 (204.22 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 313
telemt_user_unique_ips_recent_window{user="hello"} 132
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 68821.3 (19h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 428437
telemt_connections_bad_total 25998
telemt_handshake_timeouts_total 21570
telemt_upstream_connect_attempt_total 21301
telemt_upstream_connect_success_total 20997
telemt_upstream_connect_fail_total 300
telemt_upstream_connect_attempts_per_request{bucket="1"} 21297
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10879
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9373
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 745
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 300
telemt_me_keepalive_timeout_total 262
telemt_me_reconnect_attempts_total 30394
telemt_me_reconnect_success_total 13306
telemt_me_reader_eof_total 14408
telemt_me_idle_close_by_peer_total 14408
telemt_me_route_drop_no_conn_total 184423
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 355073
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1419
telemt_desync_full_logged_total 448
telemt_desync_suppressed_total 971
telemt_desync_frames_bucket_total{bucket="1_2"} 313
telemt_desync_frames_bucket_total{bucket="3_10"} 620
telemt_desync_frames_bucket_total{bucket="gt_10"} 486
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 14003
telemt_me_refill_failed_total 530
telemt_me_writer_restored_same_endpoint_total 13290
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 697
telemt_user_connections_total{user="hello"} 359228
telemt_user_connections_current{user="hello"} 579
telemt_user_octets_from_client{user="hello"} 3844021508 (3.58 GB)
telemt_user_octets_to_client{user="hello"} 118386115797 (110.26 GB)
telemt_user_msgs_from_client{user="hello"} 40047
telemt_user_msgs_to_client{user="hello"} 122218
telemt_user_unique_ips_current{user="hello"} 163
telemt_user_unique_ips_recent_window{user="hello"} 119
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 68596.9 (19h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 227808
telemt_connections_bad_total 7806
telemt_handshake_timeouts_total 16709
telemt_upstream_connect_attempt_total 18176
telemt_upstream_connect_success_total 18084
telemt_upstream_connect_fail_total 92
telemt_upstream_connect_attempts_per_request{bucket="1"} 18176
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8039
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9969
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 92
telemt_me_keepalive_timeout_total 31
telemt_me_reconnect_attempts_total 19928
telemt_me_reconnect_success_total 14591
telemt_me_reader_eof_total 15633
telemt_me_idle_close_by_peer_total 15633
telemt_me_route_drop_no_conn_total 84748
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 191372
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 737
telemt_desync_full_logged_total 207
telemt_desync_suppressed_total 530
telemt_desync_frames_bucket_total{bucket="1_2"} 273
telemt_desync_frames_bucket_total{bucket="3_10"} 323
telemt_desync_frames_bucket_total{bucket="gt_10"} 141
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 14964
telemt_me_refill_failed_total 164
telemt_me_writer_restored_same_endpoint_total 14580
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 373
telemt_user_connections_total{user="hello"} 191255
telemt_user_connections_current{user="hello"} 323
telemt_user_octets_from_client{user="hello"} 15303861336 (14.25 GB)
telemt_user_octets_to_client{user="hello"} 52245845508 (48.66 GB)
telemt_user_unique_ips_current{user="hello"} 108
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 68656.2 (19h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 520667
telemt_connections_bad_total 8078
telemt_handshake_timeouts_total 12838
telemt_upstream_connect_attempt_total 16366
telemt_upstream_connect_success_total 16216
telemt_upstream_connect_fail_total 150
telemt_upstream_connect_attempts_per_request{bucket="1"} 16366
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8105
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7995
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 107
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 150
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 19357
telemt_me_reconnect_success_total 11714
telemt_me_reader_eof_total 12614
telemt_me_idle_close_by_peer_total 12614
telemt_me_route_drop_no_conn_total 155666
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 442368
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1572
telemt_desync_full_logged_total 544
telemt_desync_suppressed_total 1028
telemt_desync_frames_bucket_total{bucket="1_2"} 384
telemt_desync_frames_bucket_total{bucket="3_10"} 705
telemt_desync_frames_bucket_total{bucket="gt_10"} 483
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 12158
telemt_me_refill_failed_total 234
telemt_me_writer_restored_same_endpoint_total 11705
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 444
telemt_user_connections_total{user="hello"} 443242
telemt_user_connections_current{user="hello"} 833
telemt_user_octets_from_client{user="hello"} 5602685166 (5.22 GB)
telemt_user_octets_to_client{user="hello"} 149915232087 (139.62 GB)
telemt_user_msgs_from_client{user="hello"} 4070
telemt_user_msgs_to_client{user="hello"} 5224
telemt_user_unique_ips_current{user="hello"} 208
telemt_user_unique_ips_recent_window{user="hello"} 121
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 68628.0 (19h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 257739
telemt_connections_bad_total 56396
telemt_handshake_timeouts_total 3283
telemt_upstream_connect_attempt_total 19598
telemt_upstream_connect_success_total 19339
telemt_upstream_connect_fail_total 259
telemt_upstream_connect_attempts_per_request{bucket="1"} 19598
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8628
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10465
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 246
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 259
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 35626
telemt_me_reconnect_success_total 15754
telemt_me_reader_eof_total 17008
telemt_me_idle_close_by_peer_total 17008
telemt_me_route_drop_no_conn_total 69001
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 188292
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1092
telemt_desync_full_logged_total 228
telemt_desync_suppressed_total 864
telemt_desync_frames_bucket_total{bucket="1_2"} 545
telemt_desync_frames_bucket_total{bucket="3_10"} 418
telemt_desync_frames_bucket_total{bucket="gt_10"} 129
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 16580
telemt_me_refill_failed_total 618
telemt_me_writer_restored_same_endpoint_total 15746
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 826
telemt_user_connections_total{user="hello"} 188466
telemt_user_connections_current{user="hello"} 332
telemt_user_octets_from_client{user="hello"} 2520417003 (2.35 GB)
telemt_user_octets_to_client{user="hello"} 71509537266 (66.60 GB)
telemt_user_msgs_from_client{user="hello"} 265
telemt_user_msgs_to_client{user="hello"} 707
telemt_user_unique_ips_current{user="hello"} 96
telemt_user_unique_ips_recent_window{user="hello"} 51
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 68791.7 (19h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 619089
telemt_connections_bad_total 53264
telemt_handshake_timeouts_total 6118
telemt_upstream_connect_attempt_total 13922
telemt_upstream_connect_success_total 13847
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 13922
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6839
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6985
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 18051
telemt_me_reconnect_success_total 10395
telemt_me_reader_eof_total 11276
telemt_me_idle_close_by_peer_total 11276
telemt_me_route_drop_no_conn_total 427622
telemt_me_route_drop_channel_closed_total 35
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 623169
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 841
telemt_desync_full_logged_total 309
telemt_desync_suppressed_total 532
telemt_desync_frames_bucket_total{bucket="1_2"} 210
telemt_desync_frames_bucket_total{bucket="3_10"} 324
telemt_desync_frames_bucket_total{bucket="gt_10"} 307
telemt_pool_swap_total 60
telemt_me_writer_removed_unexpected_total 10794
telemt_me_refill_failed_total 237
telemt_me_writer_restored_same_endpoint_total 10381
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 399
telemt_user_connections_total{user="hello"} 527655
telemt_user_connections_current{user="hello"} 968
telemt_user_octets_from_client{user="hello"} 7970811224 (7.42 GB)
telemt_user_octets_to_client{user="hello"} 247860100996 (230.84 GB)
telemt_user_unique_ips_current{user="hello"} 326
telemt_user_unique_ips_recent_window{user="hello"} 134
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 16556.3 (4h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13038
telemt_connections_bad_total 58
telemt_handshake_timeouts_total 48
telemt_upstream_connect_attempt_total 9405
telemt_upstream_connect_success_total 9329
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 9405
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5049
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4273
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 16053
telemt_me_reconnect_success_total 8317
telemt_me_reader_eof_total 8758
telemt_me_idle_close_by_peer_total 8758
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 4397
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12608
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 11
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 8642
telemt_me_refill_failed_total 240
telemt_me_writer_restored_same_endpoint_total 8303
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 325
telemt_user_connections_total{user="hello"} 12709
telemt_user_connections_current{user="hello"} 73
telemt_user_octets_from_client{user="hello"} 358948961 (342.32 MB)
telemt_user_octets_to_client{user="hello"} 21979363502 (20.47 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 19
telemt_user_unique_ips_recent_window{user="hello"} 7
```