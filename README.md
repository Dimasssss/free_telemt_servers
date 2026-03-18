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

# Server Metrics 2026-03-18 00:36:09 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 107452.2 (29h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1262847
telemt_connections_bad_total 9553
telemt_handshake_timeouts_total 32432
telemt_upstream_connect_attempt_total 24054
telemt_upstream_connect_success_total 23555
telemt_upstream_connect_fail_total 499
telemt_upstream_connect_attempts_per_request{bucket="1"} 24054
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12139
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11208
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 499
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 33032
telemt_me_reconnect_success_total 15896
telemt_me_reader_eof_total 17264
telemt_me_idle_close_by_peer_total 17263
telemt_me_route_drop_no_conn_total 556390
telemt_me_route_drop_channel_closed_total 158
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1160732
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7521
telemt_desync_full_logged_total 2204
telemt_desync_suppressed_total 5317
telemt_desync_frames_bucket_total{bucket="1_2"} 2011
telemt_desync_frames_bucket_total{bucket="3_10"} 2852
telemt_desync_frames_bucket_total{bucket="gt_10"} 2658
telemt_pool_swap_total 88
telemt_me_writer_removed_unexpected_total 16667
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 15874
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 771
telemt_user_connections_total{user="hello"} 1154944
telemt_user_connections_current{user="hello"} 532
telemt_user_octets_from_client{user="hello"} 22731243403 (21.17 GB)
telemt_user_octets_to_client{user="hello"} 415186679599 (386.67 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 252
telemt_user_unique_ips_recent_window{user="hello"} 62
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 107703.6 (29h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1341346
telemt_connections_bad_total 62101
telemt_handshake_timeouts_total 46018
telemt_upstream_connect_attempt_total 466604
telemt_upstream_connect_success_total 465058
telemt_upstream_connect_fail_total 1546
telemt_upstream_connect_attempts_per_request{bucket="1"} 466604
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 389215
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32493
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43348
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1546
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 343
telemt_me_reconnect_attempts_total 122196
telemt_me_reconnect_success_total 16767
telemt_me_reader_eof_total 18875
telemt_me_idle_close_by_peer_total 18865
telemt_me_route_drop_no_conn_total 346714
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 722542
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3295
telemt_desync_full_logged_total 1096
telemt_desync_suppressed_total 2199
telemt_desync_frames_bucket_total{bucket="1_2"} 642
telemt_desync_frames_bucket_total{bucket="3_10"} 1357
telemt_desync_frames_bucket_total{bucket="gt_10"} 1296
telemt_pool_swap_total 61
telemt_me_writer_removed_unexpected_total 18311
telemt_me_refill_failed_total 3289
telemt_me_writer_restored_same_endpoint_total 16749
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 6668
telemt_me_writer_removed_unexpected_minus_restored_total 1544
telemt_user_connections_total{user="hello"} 1164891
telemt_user_connections_current{user="hello"} 610
telemt_user_octets_from_client{user="hello"} 15836505881 (14.75 GB)
telemt_user_octets_to_client{user="hello"} 399175325706 (371.76 GB)
telemt_user_msgs_from_client{user="hello"} 7472583
telemt_user_msgs_to_client{user="hello"} 31958899
telemt_user_unique_ips_current{user="hello"} 239
telemt_user_unique_ips_recent_window{user="hello"} 54
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 107479.5 (29h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 793868
telemt_connections_bad_total 51696
telemt_handshake_timeouts_total 24051
telemt_upstream_connect_attempt_total 25263
telemt_upstream_connect_success_total 25118
telemt_upstream_connect_fail_total 145
telemt_upstream_connect_attempts_per_request{bucket="1"} 25263
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11516
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13507
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 145
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 40387
telemt_me_reconnect_success_total 19704
telemt_me_reader_eof_total 21466
telemt_me_idle_close_by_peer_total 21459
telemt_me_route_drop_no_conn_total 321066
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 674538
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2164
telemt_desync_full_logged_total 703
telemt_desync_suppressed_total 1461
telemt_desync_frames_bucket_total{bucket="1_2"} 614
telemt_desync_frames_bucket_total{bucket="3_10"} 835
telemt_desync_frames_bucket_total{bucket="gt_10"} 715
telemt_pool_swap_total 85
telemt_me_writer_removed_unexpected_total 20617
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 19692
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 913
telemt_user_connections_total{user="hello"} 672730
telemt_user_connections_current{user="hello"} 399
telemt_user_octets_from_client{user="hello"} 33234509756 (30.95 GB)
telemt_user_octets_to_client{user="hello"} 298050155692 (277.58 GB)
telemt_user_unique_ips_current{user="hello"} 170
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 107539.4 (29h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1280430
telemt_connections_bad_total 52798
telemt_handshake_timeouts_total 21814
telemt_upstream_connect_attempt_total 86389
telemt_upstream_connect_success_total 84969
telemt_upstream_connect_fail_total 1420
telemt_upstream_connect_attempts_per_request{bucket="1"} 86389
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 71404
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13175
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 30
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 360
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1420
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 315
telemt_me_reconnect_attempts_total 35947
telemt_me_reconnect_success_total 15586
telemt_me_reader_eof_total 17199
telemt_me_idle_close_by_peer_total 17197
telemt_me_route_drop_no_conn_total 524233
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1042374
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3927
telemt_desync_full_logged_total 1300
telemt_desync_suppressed_total 2627
telemt_desync_frames_bucket_total{bucket="1_2"} 959
telemt_desync_frames_bucket_total{bucket="3_10"} 1652
telemt_desync_frames_bucket_total{bucket="gt_10"} 1316
telemt_pool_swap_total 83
telemt_me_writer_removed_unexpected_total 16514
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 15576
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 928
telemt_user_connections_total{user="hello"} 1105496
telemt_user_connections_current{user="hello"} 509
telemt_user_octets_from_client{user="hello"} 17345633239 (16.15 GB)
telemt_user_octets_to_client{user="hello"} 516454426534 (480.99 GB)
telemt_user_msgs_from_client{user="hello"} 738254
telemt_user_msgs_to_client{user="hello"} 5205558
telemt_user_unique_ips_current{user="hello"} 183
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 107511.1 (29h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 838427
telemt_connections_bad_total 99059
telemt_handshake_timeouts_total 6766
telemt_upstream_connect_attempt_total 44390
telemt_upstream_connect_success_total 43777
telemt_upstream_connect_fail_total 613
telemt_upstream_connect_attempts_per_request{bucket="1"} 44390
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27640
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15725
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 412
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 613
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 56880
telemt_me_reconnect_success_total 21922
telemt_me_reader_eof_total 23811
telemt_me_idle_close_by_peer_total 23809
telemt_me_route_drop_no_conn_total 265532
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 674313
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3178
telemt_desync_full_logged_total 942
telemt_desync_suppressed_total 2236
telemt_desync_frames_bucket_total{bucket="1_2"} 1004
telemt_desync_frames_bucket_total{bucket="3_10"} 1272
telemt_desync_frames_bucket_total{bucket="gt_10"} 902
telemt_pool_swap_total 53
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 23371
telemt_me_refill_failed_total 1087
telemt_me_writer_restored_same_endpoint_total 21914
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1449
telemt_user_connections_total{user="hello"} 690921
telemt_user_connections_current{user="hello"} 459
telemt_user_octets_from_client{user="hello"} 13571637356 (12.64 GB)
telemt_user_octets_to_client{user="hello"} 347508169920 (323.64 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 199
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 107672.0 (29h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1077618
telemt_connections_bad_total 103637
telemt_handshake_timeouts_total 9619
telemt_upstream_connect_attempt_total 21404
telemt_upstream_connect_success_total 21285
telemt_upstream_connect_fail_total 119
telemt_upstream_connect_attempts_per_request{bucket="1"} 21404
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10160
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11008
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 107
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 119
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 27202
telemt_me_reconnect_success_total 15920
telemt_me_reader_eof_total 17278
telemt_me_idle_close_by_peer_total 17276
telemt_me_route_drop_no_conn_total 723109
telemt_me_route_drop_channel_closed_total 88
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1040997
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2106
telemt_desync_full_logged_total 737
telemt_desync_suppressed_total 1369
telemt_desync_frames_bucket_total{bucket="1_2"} 461
telemt_desync_frames_bucket_total{bucket="3_10"} 802
telemt_desync_frames_bucket_total{bucket="gt_10"} 843
telemt_pool_swap_total 94
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 16529
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 15906
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 609
telemt_user_connections_total{user="hello"} 895176
telemt_user_connections_current{user="hello"} 423
telemt_user_octets_from_client{user="hello"} 14402288816 (13.41 GB)
telemt_user_octets_to_client{user="hello"} 378886798940 (352.87 GB)
telemt_user_unique_ips_current{user="hello"} 163
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 55439.3 (15h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 392733
telemt_connections_bad_total 44682
telemt_handshake_timeouts_total 10840
telemt_upstream_connect_attempt_total 20824
telemt_upstream_connect_success_total 20635
telemt_upstream_connect_fail_total 189
telemt_upstream_connect_attempts_per_request{bucket="1"} 20824
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11046
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9493
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 189
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 29308
telemt_me_reconnect_success_total 17709
telemt_me_reader_eof_total 18735
telemt_me_idle_close_by_peer_total 18735
telemt_me_seq_mismatch_total 23
telemt_me_route_drop_no_conn_total 98368
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 290171
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 25
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1102
telemt_desync_full_logged_total 347
telemt_desync_suppressed_total 755
telemt_desync_frames_bucket_total{bucket="1_2"} 214
telemt_desync_frames_bucket_total{bucket="3_10"} 474
telemt_desync_frames_bucket_total{bucket="gt_10"} 414
telemt_pool_swap_total 35
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 18272
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 17678
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 563
telemt_user_connections_total{user="hello"} 290112
telemt_user_connections_current{user="hello"} 327
telemt_user_octets_from_client{user="hello"} 22211644377 (20.69 GB)
telemt_user_octets_to_client{user="hello"} 240315590546 (223.81 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 116
telemt_user_unique_ips_recent_window{user="hello"} 29
```