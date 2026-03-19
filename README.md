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

# Server Metrics 2026-03-19 13:59:13 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 1418.1 (0h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 95906
telemt_connections_bad_total 39
telemt_connections_current 102
telemt_connections_me_current 102
telemt_handshake_timeouts_total 86973
telemt_upstream_connect_attempt_total 810
telemt_upstream_connect_success_total 806
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 810
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 374
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 432
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 632
telemt_me_reconnect_success_total 623
telemt_me_reader_eof_total 555
telemt_me_idle_close_by_peer_total 555
telemt_me_seq_mismatch_total 1
telemt_me_route_drop_no_conn_total 2540
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3884
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 87
telemt_desync_full_logged_total 25
telemt_desync_suppressed_total 62
telemt_desync_frames_bucket_total{bucket="1_2"} 17
telemt_desync_frames_bucket_total{bucket="3_10"} 29
telemt_desync_frames_bucket_total{bucket="gt_10"} 41
telemt_me_writer_close_signal_drop_total 18
telemt_me_writer_removed_unexpected_total 574
telemt_me_writer_restored_same_endpoint_total 606
telemt_me_writer_restored_fallback_total 17
telemt_me_no_writer_failfast_total 10
telemt_me_async_recovery_trigger_total 102
telemt_user_connections_total{user="hello"} 3480
telemt_user_connections_current{user="hello"} 102
telemt_user_octets_from_client{user="hello"} 37738723 (35.99 MB)
telemt_user_octets_to_client{user="hello"} 1146546252 (1.07 GB)
telemt_user_msgs_from_client{user="hello"} 261
telemt_user_msgs_to_client{user="hello"} 430
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 4554.0 (1h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 484337
telemt_connections_bad_total 14440
telemt_connections_current 3802
telemt_connections_me_current 3802
telemt_handshake_timeouts_total 7787
telemt_upstream_connect_attempt_total 2251
telemt_upstream_connect_success_total 2239
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 2251
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1757
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 476
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_reconnect_attempts_total 3607
telemt_me_reconnect_success_total 751
telemt_me_reader_eof_total 794
telemt_me_idle_close_by_peer_total 794
telemt_me_route_drop_no_conn_total 425714
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 433756
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1352
telemt_desync_full_logged_total 443
telemt_desync_suppressed_total 909
telemt_desync_frames_bucket_total{bucket="1_2"} 243
telemt_desync_frames_bucket_total{bucket="3_10"} 507
telemt_desync_frames_bucket_total{bucket="gt_10"} 602
telemt_me_writer_close_signal_drop_total 25
telemt_me_writer_removed_unexpected_total 822
telemt_me_refill_failed_total 89
telemt_me_writer_restored_same_endpoint_total 696
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 71
telemt_user_connections_total{user="hello"} 434600
telemt_user_connections_current{user="hello"} 3802
telemt_user_octets_from_client{user="hello"} 6123258730 (5.70 GB)
telemt_user_octets_to_client{user="hello"} 108313894514 (100.88 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1306
telemt_user_unique_ips_recent_window{user="hello"} 632
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 4532.3 (1h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 542754
telemt_connections_bad_total 52834
telemt_connections_current 3042
telemt_connections_me_current 3042
telemt_handshake_timeouts_total 5452
telemt_upstream_connect_attempt_total 716
telemt_upstream_connect_success_total 710
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 716
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 431
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 279
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_reconnect_attempts_total 1352
telemt_me_reconnect_success_total 454
telemt_me_reader_eof_total 388
telemt_me_idle_close_by_peer_total 387
telemt_me_route_drop_no_conn_total 532674
telemt_me_route_drop_channel_closed_total 26
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 405211
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1443
telemt_desync_full_logged_total 365
telemt_desync_suppressed_total 1078
telemt_desync_frames_bucket_total{bucket="1_2"} 393
telemt_desync_frames_bucket_total{bucket="3_10"} 544
telemt_desync_frames_bucket_total{bucket="gt_10"} 506
telemt_pool_swap_total 2
telemt_me_writer_close_signal_drop_total 28
telemt_me_writer_removed_unexpected_total 409
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 453
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_user_connections_total{user="hello"} 402982
telemt_user_connections_current{user="hello"} 3042
telemt_user_octets_from_client{user="hello"} 3518950680 (3.28 GB)
telemt_user_octets_to_client{user="hello"} 96479976300 (89.85 GB)
telemt_user_unique_ips_current{user="hello"} 1042
telemt_user_unique_ips_recent_window{user="hello"} 484
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 4519.9 (1h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 393810
telemt_connections_bad_total 38281
telemt_connections_current 3015
telemt_connections_me_current 3015
telemt_handshake_timeouts_total 6516
telemt_upstream_connect_attempt_total 4211
telemt_upstream_connect_success_total 4052
telemt_upstream_connect_fail_total 159
telemt_upstream_connect_attempts_per_request{bucket="1"} 4211
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3566
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 443
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 159
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 503
telemt_me_reconnect_success_total 479
telemt_me_reader_eof_total 454
telemt_me_idle_close_by_peer_total 453
telemt_me_route_drop_no_conn_total 236631
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 315459
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1284
telemt_desync_full_logged_total 438
telemt_desync_suppressed_total 846
telemt_desync_frames_bucket_total{bucket="1_2"} 240
telemt_desync_frames_bucket_total{bucket="3_10"} 480
telemt_desync_frames_bucket_total{bucket="gt_10"} 564
telemt_pool_swap_total 2
telemt_me_writer_close_signal_drop_total 24
telemt_me_writer_removed_unexpected_total 473
telemt_me_writer_restored_same_endpoint_total 476
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 402
telemt_user_connections_total{user="hello"} 318501
telemt_user_connections_current{user="hello"} 3015
telemt_user_octets_from_client{user="hello"} 5166303119 (4.81 GB)
telemt_user_octets_to_client{user="hello"} 74109307978 (69.02 GB)
telemt_user_msgs_from_client{user="hello"} 5613
telemt_user_msgs_to_client{user="hello"} 6373
telemt_user_unique_ips_current{user="hello"} 1016
telemt_user_unique_ips_recent_window{user="hello"} 492
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 58243.4 (16h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3991853
telemt_connections_bad_total 762157
telemt_connections_current 3538
telemt_connections_me_current 3538
telemt_relay_adaptive_promotions_total 22
telemt_relay_adaptive_demotions_total 1819
telemt_relay_adaptive_hard_promotions_total 20
telemt_handshake_timeouts_total 78552
telemt_upstream_connect_attempt_total 62185
telemt_upstream_connect_success_total 59702
telemt_upstream_connect_fail_total 2483
telemt_upstream_connect_attempts_per_request{bucket="1"} 62185
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 51539
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7147
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1016
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2483
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 70668
telemt_me_reconnect_success_total 7608
telemt_me_reader_eof_total 7948
telemt_me_idle_close_by_peer_total 7945
telemt_me_route_drop_no_conn_total 1901991
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2720952
telemt_me_writer_pick_total{mode="p2c",result="full"} 8278
telemt_me_writer_pick_total{mode="p2c",result="closed"} 806
telemt_me_writer_pick_blocking_fallback_total 9050
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11725
telemt_desync_full_logged_total 3621
telemt_desync_suppressed_total 8104
telemt_desync_frames_bucket_total{bucket="1_2"} 2042
telemt_desync_frames_bucket_total{bucket="3_10"} 5042
telemt_desync_frames_bucket_total{bucket="gt_10"} 4641
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 7743
telemt_me_refill_failed_total 1967
telemt_me_writer_restored_same_endpoint_total 7584
telemt_me_writer_restored_fallback_total 24
telemt_me_no_writer_failfast_total 1478
telemt_me_async_recovery_trigger_total 7229
telemt_me_writer_removed_unexpected_minus_restored_total 135
telemt_user_connections_total{user="hello"} 2769665
telemt_user_connections_current{user="hello"} 3538
telemt_user_octets_from_client{user="hello"} 44688525427 (41.62 GB)
telemt_user_octets_to_client{user="hello"} 989694308692 (921.72 GB)
telemt_user_msgs_from_client{user="hello"} 549175
telemt_user_msgs_to_client{user="hello"} 1884577
telemt_user_unique_ips_current{user="hello"} 1146
telemt_user_unique_ips_recent_window{user="hello"} 563
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 4485.0 (1h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 112203
telemt_connections_bad_total 5326
telemt_connections_current 880
telemt_connections_me_current 880
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 4789
telemt_upstream_connect_attempt_total 3394
telemt_upstream_connect_success_total 3258
telemt_upstream_connect_fail_total 136
telemt_upstream_connect_attempts_per_request{bucket="1"} 3394
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1129
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1975
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 149
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 136
telemt_me_reconnect_attempts_total 497
telemt_me_reconnect_success_total 479
telemt_me_reader_eof_total 430
telemt_me_idle_close_by_peer_total 430
telemt_me_route_drop_no_conn_total 86499
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 94872
telemt_me_writer_pick_total{mode="p2c",result="success_fallback"} 464
telemt_me_writer_pick_total{mode="p2c",result="full"} 2833
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_writer_pick_blocking_fallback_total 3285
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 194
telemt_desync_full_logged_total 72
telemt_desync_suppressed_total 122
telemt_desync_frames_bucket_total{bucket="1_2"} 30
telemt_desync_frames_bucket_total{bucket="3_10"} 84
telemt_desync_frames_bucket_total{bucket="gt_10"} 80
telemt_pool_swap_total 3
telemt_me_writer_close_signal_drop_total 34
telemt_me_writer_removed_unexpected_total 441
telemt_me_writer_restored_same_endpoint_total 470
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 179
telemt_me_async_recovery_trigger_total 1239
telemt_user_connections_total{user="hello"} 97511
telemt_user_connections_current{user="hello"} 880
telemt_user_octets_from_client{user="hello"} 1369692808 (1.28 GB)
telemt_user_octets_to_client{user="hello"} 22608200858 (21.06 GB)
telemt_user_msgs_from_client{user="hello"} 7378
telemt_user_msgs_to_client{user="hello"} 12667
telemt_user_unique_ips_current{user="hello"} 336
telemt_user_unique_ips_recent_window{user="hello"} 133
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 4484.6 (1h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 310992
telemt_connections_bad_total 26275
telemt_connections_current 3128
telemt_connections_me_current 3128
telemt_handshake_timeouts_total 5529
telemt_upstream_connect_attempt_total 665
telemt_upstream_connect_success_total 661
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 665
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 352
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 309
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 421
telemt_me_reconnect_success_total 414
telemt_me_reader_eof_total 421
telemt_me_idle_close_by_peer_total 421
telemt_me_route_drop_no_conn_total 93825
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 269332
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1251
telemt_desync_full_logged_total 376
telemt_desync_suppressed_total 875
telemt_desync_frames_bucket_total{bucket="1_2"} 198
telemt_desync_frames_bucket_total{bucket="3_10"} 432
telemt_desync_frames_bucket_total{bucket="gt_10"} 621
telemt_pool_swap_total 3
telemt_me_writer_close_signal_drop_total 23
telemt_me_writer_removed_unexpected_total 426
telemt_me_writer_restored_same_endpoint_total 397
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 269246
telemt_user_connections_current{user="hello"} 3128
telemt_user_octets_from_client{user="hello"} 3204648336 (2.98 GB)
telemt_user_octets_to_client{user="hello"} 112422808452 (104.70 GB)
telemt_user_unique_ips_current{user="hello"} 1062
telemt_user_unique_ips_recent_window{user="hello"} 456
```