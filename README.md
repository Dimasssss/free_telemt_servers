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

# Server Metrics 2026-03-17 20:05:53 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 91236.7 (25h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1131519
telemt_connections_bad_total 8352
telemt_handshake_timeouts_total 30248
telemt_upstream_connect_attempt_total 20990
telemt_upstream_connect_success_total 20502
telemt_upstream_connect_fail_total 488
telemt_upstream_connect_attempts_per_request{bucket="1"} 20990
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10633
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9663
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 206
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 488
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 30753
telemt_me_reconnect_success_total 13625
telemt_me_reader_eof_total 14818
telemt_me_idle_close_by_peer_total 14817
telemt_me_route_drop_no_conn_total 507436
telemt_me_route_drop_channel_closed_total 152
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1036426
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6882
telemt_desync_full_logged_total 1967
telemt_desync_suppressed_total 4915
telemt_desync_frames_bucket_total{bucket="1_2"} 1854
telemt_desync_frames_bucket_total{bucket="3_10"} 2610
telemt_desync_frames_bucket_total{bucket="gt_10"} 2418
telemt_pool_swap_total 70
telemt_me_writer_removed_unexpected_total 14359
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 13603
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 734
telemt_user_connections_total{user="hello"} 1030663
telemt_user_connections_current{user="hello"} 816
telemt_user_octets_from_client{user="hello"} 15672367011 (14.60 GB)
telemt_user_octets_to_client{user="hello"} 360273852899 (335.53 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 314
telemt_user_unique_ips_recent_window{user="hello"} 102
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 91488.2 (25h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1134599
telemt_connections_bad_total 58628
telemt_handshake_timeouts_total 40471
telemt_upstream_connect_attempt_total 456529
telemt_upstream_connect_success_total 455653
telemt_upstream_connect_fail_total 876
telemt_upstream_connect_attempts_per_request{bucket="1"} 456529
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 382340
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30022
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43289
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 876
telemt_me_keepalive_timeout_total 342
telemt_me_reconnect_attempts_total 57225
telemt_me_reconnect_success_total 14073
telemt_me_reader_eof_total 16008
telemt_me_idle_close_by_peer_total 16008
telemt_me_route_drop_no_conn_total 282697
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 537882
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2262
telemt_desync_full_logged_total 731
telemt_desync_suppressed_total 1531
telemt_desync_frames_bucket_total{bucket="1_2"} 453
telemt_desync_frames_bucket_total{bucket="3_10"} 951
telemt_desync_frames_bucket_total{bucket="gt_10"} 858
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 15596
telemt_me_refill_failed_total 1344
telemt_me_writer_restored_same_endpoint_total 14057
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 1523
telemt_user_connections_total{user="hello"} 974315
telemt_user_connections_current{user="hello"} 1552
telemt_user_octets_from_client{user="hello"} 13542382970 (12.61 GB)
telemt_user_octets_to_client{user="hello"} 307975784586 (286.82 GB)
telemt_user_msgs_from_client{user="hello"} 7417237
telemt_user_msgs_to_client{user="hello"} 31692884
telemt_user_unique_ips_current{user="hello"} 446
telemt_user_unique_ips_recent_window{user="hello"} 170
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 91264.1 (25h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 612363
telemt_connections_bad_total 29478
telemt_handshake_timeouts_total 22120
telemt_upstream_connect_attempt_total 22173
telemt_upstream_connect_success_total 22044
telemt_upstream_connect_fail_total 129
telemt_upstream_connect_attempts_per_request{bucket="1"} 22173
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10060
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11892
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 87
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 129
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 38090
telemt_me_reconnect_success_total 17417
telemt_me_reader_eof_total 19022
telemt_me_idle_close_by_peer_total 19015
telemt_me_route_drop_no_conn_total 268384
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 531517
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1571
telemt_desync_full_logged_total 470
telemt_desync_suppressed_total 1101
telemt_desync_frames_bucket_total{bucket="1_2"} 453
telemt_desync_frames_bucket_total{bucket="3_10"} 622
telemt_desync_frames_bucket_total{bucket="gt_10"} 496
telemt_pool_swap_total 67
telemt_me_writer_removed_unexpected_total 18301
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 17405
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 884
telemt_user_connections_total{user="hello"} 529803
telemt_user_connections_current{user="hello"} 1120
telemt_user_octets_from_client{user="hello"} 27912069580 (26.00 GB)
telemt_user_octets_to_client{user="hello"} 212910740848 (198.29 GB)
telemt_user_unique_ips_current{user="hello"} 318
telemt_user_unique_ips_recent_window{user="hello"} 102
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 91323.6 (25h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1113593
telemt_connections_bad_total 31476
telemt_handshake_timeouts_total 20698
telemt_upstream_connect_attempt_total 81746
telemt_upstream_connect_success_total 81339
telemt_upstream_connect_fail_total 407
telemt_upstream_connect_attempts_per_request{bucket="1"} 81746
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 69407
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11567
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 29
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 336
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 407
telemt_me_keepalive_timeout_total 273
telemt_me_reconnect_attempts_total 33694
telemt_me_reconnect_success_total 13387
telemt_me_reader_eof_total 14765
telemt_me_idle_close_by_peer_total 14764
telemt_me_route_drop_no_conn_total 459198
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 904217
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3067
telemt_desync_full_logged_total 981
telemt_desync_suppressed_total 2086
telemt_desync_frames_bucket_total{bucket="1_2"} 743
telemt_desync_frames_bucket_total{bucket="3_10"} 1320
telemt_desync_frames_bucket_total{bucket="gt_10"} 1004
telemt_pool_swap_total 66
telemt_me_writer_removed_unexpected_total 14269
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 13378
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 882
telemt_user_connections_total{user="hello"} 967260
telemt_user_connections_current{user="hello"} 1427
telemt_user_octets_from_client{user="hello"} 13963055331 (13.00 GB)
telemt_user_octets_to_client{user="hello"} 380872593149 (354.72 GB)
telemt_user_msgs_from_client{user="hello"} 734453
telemt_user_msgs_to_client{user="hello"} 5166140
telemt_user_unique_ips_current{user="hello"} 400
telemt_user_unique_ips_recent_window{user="hello"} 132
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 91295.5 (25h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 666007
telemt_connections_bad_total 79988
telemt_handshake_timeouts_total 5607
telemt_upstream_connect_attempt_total 40416
telemt_upstream_connect_success_total 39880
telemt_upstream_connect_fail_total 536
telemt_upstream_connect_attempts_per_request{bucket="1"} 40416
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25831
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13664
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 385
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 536
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 51294
telemt_me_reconnect_success_total 18809
telemt_me_reader_eof_total 20509
telemt_me_idle_close_by_peer_total 20507
telemt_me_route_drop_no_conn_total 207989
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 527342
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2379
telemt_desync_full_logged_total 665
telemt_desync_suppressed_total 1714
telemt_desync_frames_bucket_total{bucket="1_2"} 828
telemt_desync_frames_bucket_total{bucket="3_10"} 948
telemt_desync_frames_bucket_total{bucket="gt_10"} 603
telemt_pool_swap_total 46
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 20145
telemt_me_refill_failed_total 1010
telemt_me_writer_restored_same_endpoint_total 18801
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1336
telemt_user_connections_total{user="hello"} 543991
telemt_user_connections_current{user="hello"} 1240
telemt_user_octets_from_client{user="hello"} 10893796672 (10.15 GB)
telemt_user_octets_to_client{user="hello"} 252192586092 (234.87 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 360
telemt_user_unique_ips_recent_window{user="hello"} 132
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 91456.5 (25h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 940532
telemt_connections_bad_total 64992
telemt_handshake_timeouts_total 9039
telemt_upstream_connect_attempt_total 18125
telemt_upstream_connect_success_total 18022
telemt_upstream_connect_fail_total 103
telemt_upstream_connect_attempts_per_request{bucket="1"} 18125
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8566
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9340
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 106
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 103
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 24716
telemt_me_reconnect_success_total 13441
telemt_me_reader_eof_total 14608
telemt_me_idle_close_by_peer_total 14606
telemt_me_route_drop_no_conn_total 667225
telemt_me_route_drop_channel_closed_total 85
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 949203
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1889
telemt_desync_full_logged_total 658
telemt_desync_suppressed_total 1231
telemt_desync_frames_bucket_total{bucket="1_2"} 442
telemt_desync_frames_bucket_total{bucket="3_10"} 726
telemt_desync_frames_bucket_total{bucket="gt_10"} 721
telemt_pool_swap_total 76
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 14018
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 13427
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 577
telemt_user_connections_total{user="hello"} 812239
telemt_user_connections_current{user="hello"} 728
telemt_user_octets_from_client{user="hello"} 12536573188 (11.68 GB)
telemt_user_octets_to_client{user="hello"} 351824085376 (327.66 GB)
telemt_user_unique_ips_current{user="hello"} 241
telemt_user_unique_ips_recent_window{user="hello"} 81
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 39223.6 (10h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 268380
telemt_connections_bad_total 36024
telemt_handshake_timeouts_total 6621
telemt_upstream_connect_attempt_total 16710
telemt_upstream_connect_success_total 16557
telemt_upstream_connect_fail_total 153
telemt_upstream_connect_attempts_per_request{bucket="1"} 16710
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8884
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7582
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 153
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 26005
telemt_me_reconnect_success_total 14416
telemt_me_reader_eof_total 15230
telemt_me_idle_close_by_peer_total 15230
telemt_me_seq_mismatch_total 19
telemt_me_route_drop_no_conn_total 65065
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 206436
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 625
telemt_desync_full_logged_total 166
telemt_desync_suppressed_total 459
telemt_desync_frames_bucket_total{bucket="1_2"} 170
telemt_desync_frames_bucket_total{bucket="3_10"} 238
telemt_desync_frames_bucket_total{bucket="gt_10"} 217
telemt_pool_swap_total 17
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 14951
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 14389
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 535
telemt_user_connections_total{user="hello"} 206383
telemt_user_connections_current{user="hello"} 781
telemt_user_octets_from_client{user="hello"} 19832559729 (18.47 GB)
telemt_user_octets_to_client{user="hello"} 171644766874 (159.86 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 227
telemt_user_unique_ips_recent_window{user="hello"} 75
```