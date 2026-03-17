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

# Server Metrics 2026-03-17 17:17:39 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 81142.5 (22h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 970835
telemt_connections_bad_total 6518
telemt_handshake_timeouts_total 27666
telemt_upstream_connect_attempt_total 19214
telemt_upstream_connect_success_total 18736
telemt_upstream_connect_fail_total 478
telemt_upstream_connect_attempts_per_request{bucket="1"} 19214
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9769
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8804
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 163
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 478
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 169
telemt_me_reconnect_attempts_total 29462
telemt_me_reconnect_success_total 12346
telemt_me_reader_eof_total 13459
telemt_me_idle_close_by_peer_total 13458
telemt_me_route_drop_no_conn_total 444983
telemt_me_route_drop_channel_closed_total 121
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 887360
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5928
telemt_desync_full_logged_total 1675
telemt_desync_suppressed_total 4253
telemt_desync_frames_bucket_total{bucket="1_2"} 1651
telemt_desync_frames_bucket_total{bucket="3_10"} 2285
telemt_desync_frames_bucket_total{bucket="gt_10"} 1992
telemt_pool_swap_total 60
telemt_me_writer_removed_unexpected_total 13053
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 12324
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 707
telemt_user_connections_total{user="hello"} 881625
telemt_user_connections_current{user="hello"} 1152
telemt_user_octets_from_client{user="hello"} 13560663119 (12.63 GB)
telemt_user_octets_to_client{user="hello"} 299039404575 (278.50 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 377
telemt_user_unique_ips_recent_window{user="hello"} 157
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 81394.8 (22h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 796780
telemt_connections_bad_total 48158
telemt_handshake_timeouts_total 30492
telemt_upstream_connect_attempt_total 293696
telemt_upstream_connect_success_total 292976
telemt_upstream_connect_fail_total 717
telemt_upstream_connect_attempts_per_request{bucket="1"} 293693
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 242427
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23048
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27499
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 717
telemt_me_keepalive_timeout_total 342
telemt_me_reconnect_attempts_total 49834
telemt_me_reconnect_success_total 13565
telemt_me_reader_eof_total 15250
telemt_me_idle_close_by_peer_total 15250
telemt_me_route_drop_no_conn_total 231631
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 407565
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1536
telemt_desync_full_logged_total 486
telemt_desync_suppressed_total 1050
telemt_desync_frames_bucket_total{bucket="1_2"} 346
telemt_desync_frames_bucket_total{bucket="3_10"} 671
telemt_desync_frames_bucket_total{bucket="gt_10"} 519
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 14861
telemt_me_refill_failed_total 1129
telemt_me_writer_restored_same_endpoint_total 13549
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 1296
telemt_user_connections_total{user="hello"} 682779
telemt_user_connections_current{user="hello"} 2276
telemt_user_octets_from_client{user="hello"} 9037213058 (8.42 GB)
telemt_user_octets_to_client{user="hello"} 185239775674 (172.52 GB)
telemt_user_msgs_from_client{user="hello"} 4535220
telemt_user_msgs_to_client{user="hello"} 18774001
telemt_user_unique_ips_current{user="hello"} 488
telemt_user_unique_ips_recent_window{user="hello"} 275
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 81170.5 (22h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 405802
telemt_connections_bad_total 11470
telemt_handshake_timeouts_total 20483
telemt_upstream_connect_attempt_total 20468
telemt_upstream_connect_success_total 20351
telemt_upstream_connect_fail_total 117
telemt_upstream_connect_attempts_per_request{bucket="1"} 20468
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9246
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11019
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 81
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 117
telemt_me_keepalive_timeout_total 76
telemt_me_reconnect_attempts_total 36874
telemt_me_reconnect_success_total 16207
telemt_me_reader_eof_total 17735
telemt_me_idle_close_by_peer_total 17728
telemt_me_route_drop_no_conn_total 197599
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 353896
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1023
telemt_desync_full_logged_total 312
telemt_desync_suppressed_total 711
telemt_desync_frames_bucket_total{bucket="1_2"} 343
telemt_desync_frames_bucket_total{bucket="3_10"} 445
telemt_desync_frames_bucket_total{bucket="gt_10"} 235
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 17069
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 16195
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 862
telemt_user_connections_total{user="hello"} 352063
telemt_user_connections_current{user="hello"} 1633
telemt_user_octets_from_client{user="hello"} 23792507788 (22.16 GB)
telemt_user_octets_to_client{user="hello"} 120917672484 (112.61 GB)
telemt_user_unique_ips_current{user="hello"} 409
telemt_user_unique_ips_recent_window{user="hello"} 200
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 81229.7 (22h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 868968
telemt_connections_bad_total 19289
telemt_handshake_timeouts_total 16222
telemt_upstream_connect_attempt_total 80233
telemt_upstream_connect_success_total 79840
telemt_upstream_connect_fail_total 393
telemt_upstream_connect_attempts_per_request{bucket="1"} 80233
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 68660
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10827
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 28
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 325
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 393
telemt_me_keepalive_timeout_total 168
telemt_me_reconnect_attempts_total 32665
telemt_me_reconnect_success_total 12368
telemt_me_reader_eof_total 13662
telemt_me_idle_close_by_peer_total 13661
telemt_me_route_drop_no_conn_total 370745
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 691695
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2219
telemt_desync_full_logged_total 715
telemt_desync_suppressed_total 1504
telemt_desync_frames_bucket_total{bucket="1_2"} 528
telemt_desync_frames_bucket_total{bucket="3_10"} 992
telemt_desync_frames_bucket_total{bucket="gt_10"} 699
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 13220
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 12359
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 852
telemt_user_connections_total{user="hello"} 754826
telemt_user_connections_current{user="hello"} 2091
telemt_user_octets_from_client{user="hello"} 9132296551 (8.51 GB)
telemt_user_octets_to_client{user="hello"} 238228157393 (221.87 GB)
telemt_user_msgs_from_client{user="hello"} 734453
telemt_user_msgs_to_client{user="hello"} 5166140
telemt_user_unique_ips_current{user="hello"} 500
telemt_user_unique_ips_recent_window{user="hello"} 234
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 81201.3 (22h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 443187
telemt_connections_bad_total 70684
telemt_handshake_timeouts_total 4347
telemt_upstream_connect_attempt_total 38612
telemt_upstream_connect_success_total 38112
telemt_upstream_connect_fail_total 500
telemt_upstream_connect_attempts_per_request{bucket="1"} 38612
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24988
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12769
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 355
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 500
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 49938
telemt_me_reconnect_success_total 17525
telemt_me_reader_eof_total 19134
telemt_me_idle_close_by_peer_total 19132
telemt_me_route_drop_no_conn_total 130008
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 332530
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1484
telemt_desync_full_logged_total 353
telemt_desync_suppressed_total 1131
telemt_desync_frames_bucket_total{bucket="1_2"} 637
telemt_desync_frames_bucket_total{bucket="3_10"} 593
telemt_desync_frames_bucket_total{bucket="gt_10"} 254
telemt_pool_swap_total 37
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 18826
telemt_me_refill_failed_total 1008
telemt_me_writer_restored_same_endpoint_total 17517
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1301
telemt_user_connections_total{user="hello"} 349231
telemt_user_connections_current{user="hello"} 1984
telemt_user_octets_from_client{user="hello"} 5819823944 (5.42 GB)
telemt_user_octets_to_client{user="hello"} 153627071220 (143.08 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 464
telemt_user_unique_ips_recent_window{user="hello"} 254
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 81363.0 (22h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 820933
telemt_connections_bad_total 60273
telemt_handshake_timeouts_total 7779
telemt_upstream_connect_attempt_total 16425
telemt_upstream_connect_success_total 16334
telemt_upstream_connect_fail_total 91
telemt_upstream_connect_attempts_per_request{bucket="1"} 16425
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7830
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8438
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 91
telemt_me_keepalive_timeout_total 117
telemt_me_reconnect_attempts_total 23503
telemt_me_reconnect_success_total 12235
telemt_me_reader_eof_total 13317
telemt_me_idle_close_by_peer_total 13315
telemt_me_route_drop_no_conn_total 616376
telemt_me_route_drop_channel_closed_total 71
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 847195
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1468
telemt_desync_full_logged_total 514
telemt_desync_suppressed_total 954
telemt_desync_frames_bucket_total{bucket="1_2"} 337
telemt_desync_frames_bucket_total{bucket="3_10"} 577
telemt_desync_frames_bucket_total{bucket="gt_10"} 554
telemt_pool_swap_total 65
telemt_me_writer_removed_unexpected_total 12791
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 12221
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 556
telemt_user_connections_total{user="hello"} 710267
telemt_user_connections_current{user="hello"} 923
telemt_user_octets_from_client{user="hello"} 10375397000 (9.66 GB)
telemt_user_octets_to_client{user="hello"} 313886245256 (292.33 GB)
telemt_user_unique_ips_current{user="hello"} 317
telemt_user_unique_ips_recent_window{user="hello"} 131
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 29129.5 (8h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 99888
telemt_connections_bad_total 6391
telemt_handshake_timeouts_total 677
telemt_upstream_connect_attempt_total 14236
telemt_upstream_connect_success_total 14116
telemt_upstream_connect_fail_total 120
telemt_upstream_connect_attempts_per_request{bucket="1"} 14236
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7602
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6459
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 55
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 120
telemt_me_keepalive_timeout_total 51
telemt_me_reconnect_attempts_total 24039
telemt_me_reconnect_success_total 12464
telemt_me_reader_eof_total 13198
telemt_me_idle_close_by_peer_total 13198
telemt_me_seq_mismatch_total 15
telemt_me_route_drop_no_conn_total 26336
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 87124
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 17
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 142
telemt_desync_full_logged_total 41
telemt_desync_suppressed_total 101
telemt_desync_frames_bucket_total{bucket="1_2"} 37
telemt_desync_frames_bucket_total{bucket="3_10"} 52
telemt_desync_frames_bucket_total{bucket="gt_10"} 53
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 12972
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 12441
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 508
telemt_user_connections_total{user="hello"} 87107
telemt_user_connections_current{user="hello"} 1249
telemt_user_octets_from_client{user="hello"} 4061310369 (3.78 GB)
telemt_user_octets_to_client{user="hello"} 93285494534 (86.88 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 294
telemt_user_unique_ips_recent_window{user="hello"} 132
```