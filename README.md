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

# Server Metrics 2026-03-17 23:19:49 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 102871.9 (28h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1231259
telemt_connections_bad_total 9042
telemt_handshake_timeouts_total 32261
telemt_upstream_connect_attempt_total 23182
telemt_upstream_connect_success_total 22687
telemt_upstream_connect_fail_total 495
telemt_upstream_connect_attempts_per_request{bucket="1"} 23182
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11692
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10787
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 495
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 32379
telemt_me_reconnect_success_total 15246
telemt_me_reader_eof_total 16562
telemt_me_idle_close_by_peer_total 16561
telemt_me_route_drop_no_conn_total 546102
telemt_me_route_drop_channel_closed_total 156
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1130518
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7444
telemt_desync_full_logged_total 2164
telemt_desync_suppressed_total 5280
telemt_desync_frames_bucket_total{bucket="1_2"} 1993
telemt_desync_frames_bucket_total{bucket="3_10"} 2814
telemt_desync_frames_bucket_total{bucket="gt_10"} 2637
telemt_pool_swap_total 83
telemt_me_writer_removed_unexpected_total 16003
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 15224
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 757
telemt_user_connections_total{user="hello"} 1124741
telemt_user_connections_current{user="hello"} 580
telemt_user_octets_from_client{user="hello"} 21560062755 (20.08 GB)
telemt_user_octets_to_client{user="hello"} 406075746763 (378.19 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 241
telemt_user_unique_ips_recent_window{user="hello"} 78
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 103123.3 (28h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1302830
telemt_connections_bad_total 60819
telemt_handshake_timeouts_total 45214
telemt_upstream_connect_attempt_total 458695
telemt_upstream_connect_success_total 457786
telemt_upstream_connect_fail_total 909
telemt_upstream_connect_attempts_per_request{bucket="1"} 458695
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 383292
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31201
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43291
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 909
telemt_me_keepalive_timeout_total 342
telemt_me_reconnect_attempts_total 58796
telemt_me_reconnect_success_total 15638
telemt_me_reader_eof_total 17671
telemt_me_idle_close_by_peer_total 17671
telemt_me_route_drop_no_conn_total 338618
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 694586
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3182
telemt_desync_full_logged_total 1041
telemt_desync_suppressed_total 2141
telemt_desync_frames_bucket_total{bucket="1_2"} 625
telemt_desync_frames_bucket_total{bucket="3_10"} 1302
telemt_desync_frames_bucket_total{bucket="gt_10"} 1255
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 17179
telemt_me_refill_failed_total 1344
telemt_me_writer_restored_same_endpoint_total 15622
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 1541
telemt_user_connections_total{user="hello"} 1131015
telemt_user_connections_current{user="hello"} 704
telemt_user_octets_from_client{user="hello"} 15557390634 (14.49 GB)
telemt_user_octets_to_client{user="hello"} 387849488510 (361.21 GB)
telemt_user_msgs_from_client{user="hello"} 7417237
telemt_user_msgs_to_client{user="hello"} 31692884
telemt_user_unique_ips_current{user="hello"} 258
telemt_user_unique_ips_recent_window{user="hello"} 76
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 102899.5 (28h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 766349
telemt_connections_bad_total 48149
telemt_handshake_timeouts_total 23683
telemt_upstream_connect_attempt_total 24286
telemt_upstream_connect_success_total 24145
telemt_upstream_connect_fail_total 140
telemt_upstream_connect_attempts_per_request{bucket="1"} 24285
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11095
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12955
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 140
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 39630
telemt_me_reconnect_success_total 18948
telemt_me_reader_eof_total 20657
telemt_me_idle_close_by_peer_total 20650
telemt_me_route_drop_no_conn_total 313318
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 651583
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2125
telemt_desync_full_logged_total 686
telemt_desync_suppressed_total 1439
telemt_desync_frames_bucket_total{bucket="1_2"} 602
telemt_desync_frames_bucket_total{bucket="3_10"} 822
telemt_desync_frames_bucket_total{bucket="gt_10"} 701
telemt_pool_swap_total 80
telemt_me_writer_removed_unexpected_total 19854
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 18936
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 906
telemt_user_connections_total{user="hello"} 649836
telemt_user_connections_current{user="hello"} 549
telemt_user_octets_from_client{user="hello"} 31617271936 (29.45 GB)
telemt_user_octets_to_client{user="hello"} 287362207916 (267.63 GB)
telemt_user_unique_ips_current{user="hello"} 199
telemt_user_unique_ips_recent_window{user="hello"} 58
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 102958.9 (28h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1254244
telemt_connections_bad_total 46387
telemt_handshake_timeouts_total 21640
telemt_upstream_connect_attempt_total 83890
telemt_upstream_connect_success_total 83453
telemt_upstream_connect_fail_total 437
telemt_upstream_connect_attempts_per_request{bucket="1"} 83890
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 70411
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12663
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 29
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 350
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 437
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 315
telemt_me_reconnect_attempts_total 35257
telemt_me_reconnect_success_total 14930
telemt_me_reader_eof_total 16444
telemt_me_idle_close_by_peer_total 16442
telemt_me_route_drop_no_conn_total 516846
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1025126
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3852
telemt_desync_full_logged_total 1266
telemt_desync_suppressed_total 2586
telemt_desync_frames_bucket_total{bucket="1_2"} 945
telemt_desync_frames_bucket_total{bucket="3_10"} 1615
telemt_desync_frames_bucket_total{bucket="gt_10"} 1292
telemt_pool_swap_total 78
telemt_me_writer_removed_unexpected_total 15840
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 14921
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 910
telemt_user_connections_total{user="hello"} 1087611
telemt_user_connections_current{user="hello"} 593
telemt_user_octets_from_client{user="hello"} 17126411227 (15.95 GB)
telemt_user_octets_to_client{user="hello"} 492286169185 (458.48 GB)
telemt_user_msgs_from_client{user="hello"} 734453
telemt_user_msgs_to_client{user="hello"} 5166140
telemt_user_unique_ips_current{user="hello"} 198
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 102930.8 (28h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 811520
telemt_connections_bad_total 96007
telemt_handshake_timeouts_total 6468
telemt_upstream_connect_attempt_total 43102
telemt_upstream_connect_success_total 42516
telemt_upstream_connect_fail_total 586
telemt_upstream_connect_attempts_per_request{bucket="1"} 43102
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27036
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15075
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 405
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 586
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 55834
telemt_me_reconnect_success_total 20880
telemt_me_reader_eof_total 22737
telemt_me_idle_close_by_peer_total 22735
telemt_me_route_drop_no_conn_total 257813
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 651385
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3055
telemt_desync_full_logged_total 896
telemt_desync_suppressed_total 2159
telemt_desync_frames_bucket_total{bucket="1_2"} 977
telemt_desync_frames_bucket_total{bucket="3_10"} 1221
telemt_desync_frames_bucket_total{bucket="gt_10"} 857
telemt_pool_swap_total 51
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 22323
telemt_me_refill_failed_total 1087
telemt_me_writer_restored_same_endpoint_total 20872
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1443
telemt_user_connections_total{user="hello"} 667995
telemt_user_connections_current{user="hello"} 501
telemt_user_octets_from_client{user="hello"} 12719756020 (11.85 GB)
telemt_user_octets_to_client{user="hello"} 331199582272 (308.45 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 205
telemt_user_unique_ips_recent_window{user="hello"} 51
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 103092.0 (28h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1044124
telemt_connections_bad_total 91421
telemt_handshake_timeouts_total 9535
telemt_upstream_connect_attempt_total 20410
telemt_upstream_connect_success_total 20295
telemt_upstream_connect_fail_total 115
telemt_upstream_connect_attempts_per_request{bucket="1"} 20410
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9696
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10482
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 107
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 115
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 26429
telemt_me_reconnect_success_total 15149
telemt_me_reader_eof_total 16446
telemt_me_idle_close_by_peer_total 16444
telemt_me_route_drop_no_conn_total 699939
telemt_me_route_drop_channel_closed_total 86
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1014173
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
telemt_pool_swap_total 89
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 15748
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 15135
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 599
telemt_user_connections_total{user="hello"} 877199
telemt_user_connections_current{user="hello"} 426
telemt_user_octets_from_client{user="hello"} 14092190428 (13.12 GB)
telemt_user_octets_to_client{user="hello"} 370988061572 (345.51 GB)
telemt_user_unique_ips_current{user="hello"} 163
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 50859.0 (14h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 371647
telemt_connections_bad_total 44601
telemt_handshake_timeouts_total 10675
telemt_upstream_connect_attempt_total 19416
telemt_upstream_connect_success_total 19237
telemt_upstream_connect_fail_total 179
telemt_upstream_connect_attempts_per_request{bucket="1"} 19416
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10279
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8862
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 179
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 28125
telemt_me_reconnect_success_total 16529
telemt_me_reader_eof_total 17477
telemt_me_idle_close_by_peer_total 17477
telemt_me_seq_mismatch_total 21
telemt_me_route_drop_no_conn_total 93251
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 279433
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1012
telemt_desync_full_logged_total 319
telemt_desync_suppressed_total 693
telemt_desync_frames_bucket_total{bucket="1_2"} 214
telemt_desync_frames_bucket_total{bucket="3_10"} 422
telemt_desync_frames_bucket_total{bucket="gt_10"} 376
telemt_pool_swap_total 30
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 17084
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 16500
telemt_me_writer_restored_fallback_total 29
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 555
telemt_user_connections_total{user="hello"} 279371
telemt_user_connections_current{user="hello"} 322
telemt_user_octets_from_client{user="hello"} 21957760729 (20.45 GB)
telemt_user_octets_to_client{user="hello"} 229404974466 (213.65 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 125
telemt_user_unique_ips_recent_window{user="hello"} 22
```