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

# Server Metrics 2026-03-17 18:54:33 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 86957.0 (24h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1065283
telemt_connections_bad_total 7522
telemt_handshake_timeouts_total 29464
telemt_upstream_connect_attempt_total 20242
telemt_upstream_connect_success_total 19757
telemt_upstream_connect_fail_total 485
telemt_upstream_connect_attempts_per_request{bucket="1"} 20242
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10278
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9286
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 193
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 485
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 177
telemt_me_reconnect_attempts_total 30224
telemt_me_reconnect_success_total 13102
telemt_me_reader_eof_total 14255
telemt_me_idle_close_by_peer_total 14254
telemt_me_route_drop_no_conn_total 483355
telemt_me_route_drop_channel_closed_total 139
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 974903
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6398
telemt_desync_full_logged_total 1827
telemt_desync_suppressed_total 4571
telemt_desync_frames_bucket_total{bucket="1_2"} 1758
telemt_desync_frames_bucket_total{bucket="3_10"} 2454
telemt_desync_frames_bucket_total{bucket="gt_10"} 2186
telemt_pool_swap_total 65
telemt_me_writer_removed_unexpected_total 13825
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 13080
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 723
telemt_user_connections_total{user="hello"} 969146
telemt_user_connections_current{user="hello"} 1027
telemt_user_octets_from_client{user="hello"} 14788068139 (13.77 GB)
telemt_user_octets_to_client{user="hello"} 338435925155 (315.19 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 339
telemt_user_unique_ips_recent_window{user="hello"} 132
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 87208.5 (24h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1031324
telemt_connections_bad_total 55852
telemt_handshake_timeouts_total 34932
telemt_upstream_connect_attempt_total 455871
telemt_upstream_connect_success_total 455002
telemt_upstream_connect_fail_total 869
telemt_upstream_connect_attempts_per_request{bucket="1"} 455871
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 382029
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29685
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43286
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 869
telemt_me_keepalive_timeout_total 342
telemt_me_reconnect_attempts_total 56790
telemt_me_reconnect_success_total 13641
telemt_me_reader_eof_total 15540
telemt_me_idle_close_by_peer_total 15540
telemt_me_route_drop_no_conn_total 249941
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 448943
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1672
telemt_desync_full_logged_total 537
telemt_desync_suppressed_total 1135
telemt_desync_frames_bucket_total{bucket="1_2"} 380
telemt_desync_frames_bucket_total{bucket="3_10"} 715
telemt_desync_frames_bucket_total{bucket="gt_10"} 577
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 15152
telemt_me_refill_failed_total 1344
telemt_me_writer_restored_same_endpoint_total 13625
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 1511
telemt_user_connections_total{user="hello"} 885492
telemt_user_connections_current{user="hello"} 1597
telemt_user_octets_from_client{user="hello"} 12068668350 (11.24 GB)
telemt_user_octets_to_client{user="hello"} 238411473598 (222.04 GB)
telemt_user_msgs_from_client{user="hello"} 7417237
telemt_user_msgs_to_client{user="hello"} 31692884
telemt_user_unique_ips_current{user="hello"} 407
telemt_user_unique_ips_recent_window{user="hello"} 150
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 86984.7 (24h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 532412
telemt_connections_bad_total 19041
telemt_handshake_timeouts_total 21574
telemt_upstream_connect_attempt_total 21384
telemt_upstream_connect_success_total 21266
telemt_upstream_connect_fail_total 118
telemt_upstream_connect_attempts_per_request{bucket="1"} 21384
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9679
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11500
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 82
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 118
telemt_me_keepalive_timeout_total 103
telemt_me_reconnect_attempts_total 37528
telemt_me_reconnect_success_total 16859
telemt_me_reader_eof_total 18433
telemt_me_idle_close_by_peer_total 18426
telemt_me_route_drop_no_conn_total 240927
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 465524
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1285
telemt_desync_full_logged_total 384
telemt_desync_suppressed_total 901
telemt_desync_frames_bucket_total{bucket="1_2"} 398
telemt_desync_frames_bucket_total{bucket="3_10"} 538
telemt_desync_frames_bucket_total{bucket="gt_10"} 349
telemt_pool_swap_total 63
telemt_me_writer_removed_unexpected_total 17731
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 16847
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 872
telemt_user_connections_total{user="hello"} 463690
telemt_user_connections_current{user="hello"} 1192
telemt_user_octets_from_client{user="hello"} 26856178600 (25.01 GB)
telemt_user_octets_to_client{user="hello"} 175228986268 (163.19 GB)
telemt_user_unique_ips_current{user="hello"} 329
telemt_user_unique_ips_recent_window{user="hello"} 141
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 87043.8 (24h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1021460
telemt_connections_bad_total 24780
telemt_handshake_timeouts_total 19589
telemt_upstream_connect_attempt_total 81062
telemt_upstream_connect_success_total 80660
telemt_upstream_connect_fail_total 402
telemt_upstream_connect_attempts_per_request{bucket="1"} 81062
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 69079
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11218
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 29
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 334
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 402
telemt_me_keepalive_timeout_total 273
telemt_me_reconnect_attempts_total 33229
telemt_me_reconnect_success_total 12927
telemt_me_reader_eof_total 14267
telemt_me_idle_close_by_peer_total 14266
telemt_me_route_drop_no_conn_total 425929
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 824332
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2654
telemt_desync_full_logged_total 861
telemt_desync_suppressed_total 1793
telemt_desync_frames_bucket_total{bucket="1_2"} 637
telemt_desync_frames_bucket_total{bucket="3_10"} 1164
telemt_desync_frames_bucket_total{bucket="gt_10"} 853
telemt_pool_swap_total 61
telemt_me_writer_removed_unexpected_total 13797
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 12918
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 870
telemt_user_connections_total{user="hello"} 887401
telemt_user_connections_current{user="hello"} 1408
telemt_user_octets_from_client{user="hello"} 12571756307 (11.71 GB)
telemt_user_octets_to_client{user="hello"} 325451617549 (303.10 GB)
telemt_user_msgs_from_client{user="hello"} 734453
telemt_user_msgs_to_client{user="hello"} 5166140
telemt_user_unique_ips_current{user="hello"} 409
telemt_user_unique_ips_recent_window{user="hello"} 137
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 87015.7 (24h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 587596
telemt_connections_bad_total 75636
telemt_handshake_timeouts_total 5091
telemt_upstream_connect_attempt_total 39669
telemt_upstream_connect_success_total 39146
telemt_upstream_connect_fail_total 523
telemt_upstream_connect_attempts_per_request{bucket="1"} 39669
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25518
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13247
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 381
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 523
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 50775
telemt_me_reconnect_success_total 18294
telemt_me_reader_eof_total 19951
telemt_me_idle_close_by_peer_total 19949
telemt_me_route_drop_no_conn_total 178587
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 456841
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2075
telemt_desync_full_logged_total 537
telemt_desync_suppressed_total 1538
telemt_desync_frames_bucket_total{bucket="1_2"} 757
telemt_desync_frames_bucket_total{bucket="3_10"} 813
telemt_desync_frames_bucket_total{bucket="gt_10"} 505
telemt_pool_swap_total 41
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 19621
telemt_me_refill_failed_total 1010
telemt_me_writer_restored_same_endpoint_total 18286
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1327
telemt_user_connections_total{user="hello"} 473503
telemt_user_connections_current{user="hello"} 1315
telemt_user_octets_from_client{user="hello"} 8520030800 (7.93 GB)
telemt_user_octets_to_client{user="hello"} 219552921332 (204.47 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 405
telemt_user_unique_ips_recent_window{user="hello"} 153
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 87176.7 (24h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 891712
telemt_connections_bad_total 61441
telemt_handshake_timeouts_total 8724
telemt_upstream_connect_attempt_total 17372
telemt_upstream_connect_success_total 17275
telemt_upstream_connect_fail_total 97
telemt_upstream_connect_attempts_per_request{bucket="1"} 17372
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8220
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8939
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 106
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 97
telemt_me_keepalive_timeout_total 138
telemt_me_reconnect_attempts_total 24185
telemt_me_reconnect_success_total 12912
telemt_me_reader_eof_total 14044
telemt_me_idle_close_by_peer_total 14042
telemt_me_route_drop_no_conn_total 647052
telemt_me_route_drop_channel_closed_total 82
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 908652
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1753
telemt_desync_full_logged_total 601
telemt_desync_suppressed_total 1152
telemt_desync_frames_bucket_total{bucket="1_2"} 419
telemt_desync_frames_bucket_total{bucket="3_10"} 675
telemt_desync_frames_bucket_total{bucket="gt_10"} 659
telemt_pool_swap_total 71
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 13484
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 12898
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 572
telemt_user_connections_total{user="hello"} 771700
telemt_user_connections_current{user="hello"} 803
telemt_user_octets_from_client{user="hello"} 11783229924 (10.97 GB)
telemt_user_octets_to_client{user="hello"} 333718373224 (310.80 GB)
telemt_user_unique_ips_current{user="hello"} 270
telemt_user_unique_ips_recent_window{user="hello"} 83
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 34944.0 (9h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 208310
telemt_connections_bad_total 21509
telemt_handshake_timeouts_total 5895
telemt_upstream_connect_attempt_total 15415
telemt_upstream_connect_success_total 15280
telemt_upstream_connect_fail_total 135
telemt_upstream_connect_attempts_per_request{bucket="1"} 15415
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8210
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6995
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 75
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 135
telemt_me_keepalive_timeout_total 51
telemt_me_reconnect_attempts_total 24944
telemt_me_reconnect_success_total 13362
telemt_me_reader_eof_total 14145
telemt_me_idle_close_by_peer_total 14145
telemt_me_seq_mismatch_total 16
telemt_me_route_drop_no_conn_total 50651
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 165394
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 454
telemt_desync_full_logged_total 122
telemt_desync_suppressed_total 332
telemt_desync_frames_bucket_total{bucket="1_2"} 126
telemt_desync_frames_bucket_total{bucket="3_10"} 176
telemt_desync_frames_bucket_total{bucket="gt_10"} 152
telemt_pool_swap_total 16
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 13882
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 13338
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 520
telemt_user_connections_total{user="hello"} 165340
telemt_user_connections_current{user="hello"} 934
telemt_user_octets_from_client{user="hello"} 13795174025 (12.85 GB)
telemt_user_octets_to_client{user="hello"} 145834804526 (135.82 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 231
telemt_user_unique_ips_recent_window{user="hello"} 92
```