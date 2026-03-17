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

# Server Metrics 2026-03-17 19:30:13 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 89096.2 (24h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1100279
telemt_connections_bad_total 7860
telemt_handshake_timeouts_total 30127
telemt_upstream_connect_attempt_total 20579
telemt_upstream_connect_success_total 20091
telemt_upstream_connect_fail_total 488
telemt_upstream_connect_attempts_per_request{bucket="1"} 20579
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10445
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9443
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 203
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 488
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 30471
telemt_me_reconnect_success_total 13344
telemt_me_reader_eof_total 14515
telemt_me_idle_close_by_peer_total 14514
telemt_me_route_drop_no_conn_total 496273
telemt_me_route_drop_channel_closed_total 144
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1006999
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6631
telemt_desync_full_logged_total 1896
telemt_desync_suppressed_total 4735
telemt_desync_frames_bucket_total{bucket="1_2"} 1800
telemt_desync_frames_bucket_total{bucket="3_10"} 2526
telemt_desync_frames_bucket_total{bucket="gt_10"} 2305
telemt_pool_swap_total 67
telemt_me_writer_removed_unexpected_total 14075
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 13322
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 731
telemt_user_connections_total{user="hello"} 1001246
telemt_user_connections_current{user="hello"} 1046
telemt_user_octets_from_client{user="hello"} 15170520887 (14.13 GB)
telemt_user_octets_to_client{user="hello"} 348820118003 (324.86 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 353
telemt_user_unique_ips_recent_window{user="hello"} 124
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 89348.0 (24h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1084668
telemt_connections_bad_total 56634
telemt_handshake_timeouts_total 37688
telemt_upstream_connect_attempt_total 456249
telemt_upstream_connect_success_total 455376
telemt_upstream_connect_fail_total 873
telemt_upstream_connect_attempts_per_request{bucket="1"} 456249
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 382216
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29870
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43288
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 873
telemt_me_keepalive_timeout_total 342
telemt_me_reconnect_attempts_total 57035
telemt_me_reconnect_success_total 13884
telemt_me_reader_eof_total 15804
telemt_me_idle_close_by_peer_total 15804
telemt_me_route_drop_no_conn_total 266926
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 494469
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1971
telemt_desync_full_logged_total 625
telemt_desync_suppressed_total 1346
telemt_desync_frames_bucket_total{bucket="1_2"} 425
telemt_desync_frames_bucket_total{bucket="3_10"} 831
telemt_desync_frames_bucket_total{bucket="gt_10"} 715
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 15399
telemt_me_refill_failed_total 1344
telemt_me_writer_restored_same_endpoint_total 13868
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 1515
telemt_user_connections_total{user="hello"} 930909
telemt_user_connections_current{user="hello"} 1586
telemt_user_octets_from_client{user="hello"} 12879880806 (12.00 GB)
telemt_user_octets_to_client{user="hello"} 278095621862 (259.00 GB)
telemt_user_msgs_from_client{user="hello"} 7417237
telemt_user_msgs_to_client{user="hello"} 31692884
telemt_user_unique_ips_current{user="hello"} 440
telemt_user_unique_ips_recent_window{user="hello"} 181
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 89123.7 (24h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 570953
telemt_connections_bad_total 21784
telemt_handshake_timeouts_total 21879
telemt_upstream_connect_attempt_total 21716
telemt_upstream_connect_success_total 21593
telemt_upstream_connect_fail_total 123
telemt_upstream_connect_attempts_per_request{bucket="1"} 21716
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9831
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11671
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 86
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 123
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 37766
telemt_me_reconnect_success_total 17095
telemt_me_reader_eof_total 18683
telemt_me_idle_close_by_peer_total 18676
telemt_me_route_drop_no_conn_total 255389
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 499493
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1470
telemt_desync_full_logged_total 429
telemt_desync_suppressed_total 1041
telemt_desync_frames_bucket_total{bucket="1_2"} 432
telemt_desync_frames_bucket_total{bucket="3_10"} 595
telemt_desync_frames_bucket_total{bucket="gt_10"} 443
telemt_pool_swap_total 65
telemt_me_writer_removed_unexpected_total 17970
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 17083
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 875
telemt_user_connections_total{user="hello"} 497718
telemt_user_connections_current{user="hello"} 1056
telemt_user_octets_from_client{user="hello"} 27434766256 (25.55 GB)
telemt_user_octets_to_client{user="hello"} 193120343584 (179.86 GB)
telemt_user_unique_ips_current{user="hello"} 300
telemt_user_unique_ips_recent_window{user="hello"} 109
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 89182.9 (24h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1069157
telemt_connections_bad_total 27099
telemt_handshake_timeouts_total 20480
telemt_upstream_connect_attempt_total 81394
telemt_upstream_connect_success_total 80990
telemt_upstream_connect_fail_total 404
telemt_upstream_connect_attempts_per_request{bucket="1"} 81394
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 69242
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11383
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 29
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 336
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 404
telemt_me_keepalive_timeout_total 273
telemt_me_reconnect_attempts_total 33442
telemt_me_reconnect_success_total 13138
telemt_me_reader_eof_total 14493
telemt_me_idle_close_by_peer_total 14492
telemt_me_route_drop_no_conn_total 441762
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 866065
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2872
telemt_desync_full_logged_total 931
telemt_desync_suppressed_total 1941
telemt_desync_frames_bucket_total{bucket="1_2"} 687
telemt_desync_frames_bucket_total{bucket="3_10"} 1247
telemt_desync_frames_bucket_total{bucket="gt_10"} 938
telemt_pool_swap_total 63
telemt_me_writer_removed_unexpected_total 14014
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 13129
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 876
telemt_user_connections_total{user="hello"} 929128
telemt_user_connections_current{user="hello"} 1487
telemt_user_octets_from_client{user="hello"} 13181023507 (12.28 GB)
telemt_user_octets_to_client{user="hello"} 351221368761 (327.10 GB)
telemt_user_msgs_from_client{user="hello"} 734453
telemt_user_msgs_to_client{user="hello"} 5166140
telemt_user_unique_ips_current{user="hello"} 402
telemt_user_unique_ips_recent_window{user="hello"} 140
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 89154.9 (24h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 624422
telemt_connections_bad_total 76031
telemt_handshake_timeouts_total 5338
telemt_upstream_connect_attempt_total 40033
telemt_upstream_connect_success_total 39500
telemt_upstream_connect_fail_total 533
telemt_upstream_connect_attempts_per_request{bucket="1"} 40033
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25655
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13462
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 383
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 533
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 51027
telemt_me_reconnect_success_total 18545
telemt_me_reader_eof_total 20221
telemt_me_idle_close_by_peer_total 20219
telemt_me_route_drop_no_conn_total 193741
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 491464
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2207
telemt_desync_full_logged_total 598
telemt_desync_suppressed_total 1609
telemt_desync_frames_bucket_total{bucket="1_2"} 782
telemt_desync_frames_bucket_total{bucket="3_10"} 878
telemt_desync_frames_bucket_total{bucket="gt_10"} 547
telemt_pool_swap_total 43
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 19877
telemt_me_refill_failed_total 1010
telemt_me_writer_restored_same_endpoint_total 18537
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1332
telemt_user_connections_total{user="hello"} 508115
telemt_user_connections_current{user="hello"} 1245
telemt_user_octets_from_client{user="hello"} 10257153388 (9.55 GB)
telemt_user_octets_to_client{user="hello"} 236481414772 (220.24 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 374
telemt_user_unique_ips_recent_window{user="hello"} 131
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 89316.4 (24h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 914476
telemt_connections_bad_total 61556
telemt_handshake_timeouts_total 8908
telemt_upstream_connect_attempt_total 17767
telemt_upstream_connect_success_total 17667
telemt_upstream_connect_fail_total 100
telemt_upstream_connect_attempts_per_request{bucket="1"} 17767
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8419
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9132
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 106
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 100
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 24448
telemt_me_reconnect_success_total 13174
telemt_me_reader_eof_total 14325
telemt_me_idle_close_by_peer_total 14323
telemt_me_route_drop_no_conn_total 657062
telemt_me_route_drop_channel_closed_total 85
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 929591
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1832
telemt_desync_full_logged_total 636
telemt_desync_suppressed_total 1196
telemt_desync_frames_bucket_total{bucket="1_2"} 438
telemt_desync_frames_bucket_total{bucket="3_10"} 705
telemt_desync_frames_bucket_total{bucket="gt_10"} 689
telemt_pool_swap_total 74
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 13748
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 13160
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 574
telemt_user_connections_total{user="hello"} 792630
telemt_user_connections_current{user="hello"} 756
telemt_user_octets_from_client{user="hello"} 12153611356 (11.32 GB)
telemt_user_octets_to_client{user="hello"} 343348904568 (319.77 GB)
telemt_user_unique_ips_current{user="hello"} 255
telemt_user_unique_ips_recent_window{user="hello"} 86
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 37083.1 (10h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 244323
telemt_connections_bad_total 32329
telemt_handshake_timeouts_total 6366
telemt_upstream_connect_attempt_total 16105
telemt_upstream_connect_success_total 15962
telemt_upstream_connect_fail_total 143
telemt_upstream_connect_attempts_per_request{bucket="1"} 16105
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8558
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7313
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 143
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 25495
telemt_me_reconnect_success_total 13908
telemt_me_reader_eof_total 14713
telemt_me_idle_close_by_peer_total 14713
telemt_me_seq_mismatch_total 17
telemt_me_route_drop_no_conn_total 58776
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 187186
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 570
telemt_desync_full_logged_total 149
telemt_desync_suppressed_total 421
telemt_desync_frames_bucket_total{bucket="1_2"} 163
telemt_desync_frames_bucket_total{bucket="3_10"} 216
telemt_desync_frames_bucket_total{bucket="gt_10"} 191
telemt_pool_swap_total 17
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 14435
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 13883
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 527
telemt_user_connections_total{user="hello"} 187126
telemt_user_connections_current{user="hello"} 768
telemt_user_octets_from_client{user="hello"} 18415700389 (17.15 GB)
telemt_user_octets_to_client{user="hello"} 157811505626 (146.97 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 211
telemt_user_unique_ips_recent_window{user="hello"} 80
```