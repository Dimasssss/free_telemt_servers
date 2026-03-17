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

# Server Metrics 2026-03-17 19:09:50 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 87874.0 (24h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1080401
telemt_connections_bad_total 7823
telemt_handshake_timeouts_total 29836
telemt_upstream_connect_attempt_total 20416
telemt_upstream_connect_success_total 19929
telemt_upstream_connect_fail_total 487
telemt_upstream_connect_attempts_per_request{bucket="1"} 20416
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10363
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9363
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 203
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 487
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 226
telemt_me_reconnect_attempts_total 30354
telemt_me_reconnect_success_total 13227
telemt_me_reader_eof_total 14393
telemt_me_idle_close_by_peer_total 14392
telemt_me_route_drop_no_conn_total 488822
telemt_me_route_drop_channel_closed_total 141
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 988715
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6449
telemt_desync_full_logged_total 1851
telemt_desync_suppressed_total 4598
telemt_desync_frames_bucket_total{bucket="1_2"} 1764
telemt_desync_frames_bucket_total{bucket="3_10"} 2464
telemt_desync_frames_bucket_total{bucket="gt_10"} 2221
telemt_pool_swap_total 66
telemt_me_writer_removed_unexpected_total 13956
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 13205
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 729
telemt_user_connections_total{user="hello"} 982960
telemt_user_connections_current{user="hello"} 1025
telemt_user_octets_from_client{user="hello"} 14962980879 (13.94 GB)
telemt_user_octets_to_client{user="hello"} 343349208075 (319.77 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 339
telemt_user_unique_ips_recent_window{user="hello"} 135
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 88125.4 (24h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1055289
telemt_connections_bad_total 55881
telemt_handshake_timeouts_total 35878
telemt_upstream_connect_attempt_total 456008
telemt_upstream_connect_success_total 455139
telemt_upstream_connect_fail_total 869
telemt_upstream_connect_attempts_per_request{bucket="1"} 456008
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 382100
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29750
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43287
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 869
telemt_me_keepalive_timeout_total 342
telemt_me_reconnect_attempts_total 56884
telemt_me_reconnect_success_total 13735
telemt_me_reader_eof_total 15640
telemt_me_idle_close_by_peer_total 15640
telemt_me_route_drop_no_conn_total 258020
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 469027
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1795
telemt_desync_full_logged_total 581
telemt_desync_suppressed_total 1214
telemt_desync_frames_bucket_total{bucket="1_2"} 403
telemt_desync_frames_bucket_total{bucket="3_10"} 753
telemt_desync_frames_bucket_total{bucket="gt_10"} 639
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 15247
telemt_me_refill_failed_total 1344
telemt_me_writer_restored_same_endpoint_total 13719
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 1512
telemt_user_connections_total{user="hello"} 905474
telemt_user_connections_current{user="hello"} 1533
telemt_user_octets_from_client{user="hello"} 12455109806 (11.60 GB)
telemt_user_octets_to_client{user="hello"} 256313047050 (238.71 GB)
telemt_user_msgs_from_client{user="hello"} 7417237
telemt_user_msgs_to_client{user="hello"} 31692884
telemt_user_unique_ips_current{user="hello"} 419
telemt_user_unique_ips_recent_window{user="hello"} 160
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 87901.3 (24h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 548247
telemt_connections_bad_total 19297
telemt_handshake_timeouts_total 21718
telemt_upstream_connect_attempt_total 21530
telemt_upstream_connect_success_total 21408
telemt_upstream_connect_fail_total 122
telemt_upstream_connect_attempts_per_request{bucket="1"} 21530
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9747
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11570
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 86
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 122
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 37627
telemt_me_reconnect_success_total 16957
telemt_me_reader_eof_total 18538
telemt_me_idle_close_by_peer_total 18531
telemt_me_route_drop_no_conn_total 247018
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 480122
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1324
telemt_desync_full_logged_total 396
telemt_desync_suppressed_total 928
telemt_desync_frames_bucket_total{bucket="1_2"} 405
telemt_desync_frames_bucket_total{bucket="3_10"} 551
telemt_desync_frames_bucket_total{bucket="gt_10"} 368
telemt_pool_swap_total 64
telemt_me_writer_removed_unexpected_total 17832
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 16945
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 875
telemt_user_connections_total{user="hello"} 478318
telemt_user_connections_current{user="hello"} 1136
telemt_user_octets_from_client{user="hello"} 27111561776 (25.25 GB)
telemt_user_octets_to_client{user="hello"} 182667788792 (170.12 GB)
telemt_user_unique_ips_current{user="hello"} 303
telemt_user_unique_ips_recent_window{user="hello"} 112
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 87960.5 (24h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1041706
telemt_connections_bad_total 25379
telemt_handshake_timeouts_total 20125
telemt_upstream_connect_attempt_total 81197
telemt_upstream_connect_success_total 80794
telemt_upstream_connect_fail_total 403
telemt_upstream_connect_attempts_per_request{bucket="1"} 81197
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 69146
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11284
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 29
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 335
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 403
telemt_me_keepalive_timeout_total 273
telemt_me_reconnect_attempts_total 33320
telemt_me_reconnect_success_total 13017
telemt_me_reader_eof_total 14365
telemt_me_idle_close_by_peer_total 14364
telemt_me_route_drop_no_conn_total 433413
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 841821
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2751
telemt_desync_full_logged_total 893
telemt_desync_suppressed_total 1858
telemt_desync_frames_bucket_total{bucket="1_2"} 658
telemt_desync_frames_bucket_total{bucket="3_10"} 1198
telemt_desync_frames_bucket_total{bucket="gt_10"} 895
telemt_pool_swap_total 62
telemt_me_writer_removed_unexpected_total 13890
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 13008
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 873
telemt_user_connections_total{user="hello"} 904887
telemt_user_connections_current{user="hello"} 1366
telemt_user_octets_from_client{user="hello"} 12820112715 (11.94 GB)
telemt_user_octets_to_client{user="hello"} 336828701317 (313.70 GB)
telemt_user_msgs_from_client{user="hello"} 734453
telemt_user_msgs_to_client{user="hello"} 5166140
telemt_user_unique_ips_current{user="hello"} 393
telemt_user_unique_ips_recent_window{user="hello"} 134
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 87932.4 (24h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 603648
telemt_connections_bad_total 75806
telemt_handshake_timeouts_total 5155
telemt_upstream_connect_attempt_total 39822
telemt_upstream_connect_success_total 39295
telemt_upstream_connect_fail_total 527
telemt_upstream_connect_attempts_per_request{bucket="1"} 39822
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25574
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13339
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 382
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 527
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 50881
telemt_me_reconnect_success_total 18399
telemt_me_reader_eof_total 20064
telemt_me_idle_close_by_peer_total 20062
telemt_me_route_drop_no_conn_total 185520
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 472088
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2146
telemt_desync_full_logged_total 569
telemt_desync_suppressed_total 1577
telemt_desync_frames_bucket_total{bucket="1_2"} 778
telemt_desync_frames_bucket_total{bucket="3_10"} 839
telemt_desync_frames_bucket_total{bucket="gt_10"} 529
telemt_pool_swap_total 42
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 19727
telemt_me_refill_failed_total 1010
telemt_me_writer_restored_same_endpoint_total 18391
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1328
telemt_user_connections_total{user="hello"} 488743
telemt_user_connections_current{user="hello"} 1348
telemt_user_octets_from_client{user="hello"} 9081259676 (8.46 GB)
telemt_user_octets_to_client{user="hello"} 226980074956 (211.39 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 410
telemt_user_unique_ips_recent_window{user="hello"} 169
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 88094.0 (24h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 901473
telemt_connections_bad_total 61509
telemt_handshake_timeouts_total 8870
telemt_upstream_connect_attempt_total 17524
telemt_upstream_connect_success_total 17425
telemt_upstream_connect_fail_total 99
telemt_upstream_connect_attempts_per_request{bucket="1"} 17524
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8292
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9017
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 106
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 99
telemt_me_keepalive_timeout_total 138
telemt_me_reconnect_attempts_total 24292
telemt_me_reconnect_success_total 13018
telemt_me_reader_eof_total 14155
telemt_me_idle_close_by_peer_total 14153
telemt_me_route_drop_no_conn_total 651702
telemt_me_route_drop_channel_closed_total 83
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 917854
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1785
telemt_desync_full_logged_total 614
telemt_desync_suppressed_total 1171
telemt_desync_frames_bucket_total{bucket="1_2"} 431
telemt_desync_frames_bucket_total{bucket="3_10"} 684
telemt_desync_frames_bucket_total{bucket="gt_10"} 670
telemt_pool_swap_total 72
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 13591
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 13004
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 573
telemt_user_connections_total{user="hello"} 780898
telemt_user_connections_current{user="hello"} 837
telemt_user_octets_from_client{user="hello"} 11954172924 (11.13 GB)
telemt_user_octets_to_client{user="hello"} 337802159316 (314.60 GB)
telemt_user_unique_ips_current{user="hello"} 276
telemt_user_unique_ips_recent_window{user="hello"} 105
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 35860.6 (9h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 227602
telemt_connections_bad_total 28762
telemt_handshake_timeouts_total 6029
telemt_upstream_connect_attempt_total 15663
telemt_upstream_connect_success_total 15527
telemt_upstream_connect_fail_total 136
telemt_upstream_connect_attempts_per_request{bucket="1"} 15663
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8339
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7102
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 86
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 136
telemt_me_keepalive_timeout_total 75
telemt_me_reconnect_attempts_total 25148
telemt_me_reconnect_success_total 13563
telemt_me_reader_eof_total 14350
telemt_me_idle_close_by_peer_total 14350
telemt_me_seq_mismatch_total 16
telemt_me_route_drop_no_conn_total 54360
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 175785
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 515
telemt_desync_full_logged_total 140
telemt_desync_suppressed_total 375
telemt_desync_frames_bucket_total{bucket="1_2"} 143
telemt_desync_frames_bucket_total{bucket="3_10"} 194
telemt_desync_frames_bucket_total{bucket="gt_10"} 178
telemt_pool_swap_total 16
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 14087
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 13539
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 524
telemt_user_connections_total{user="hello"} 175729
telemt_user_connections_current{user="hello"} 923
telemt_user_octets_from_client{user="hello"} 17110733121 (15.94 GB)
telemt_user_octets_to_client{user="hello"} 152379035862 (141.91 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 239
telemt_user_unique_ips_recent_window{user="hello"} 72
```