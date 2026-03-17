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

# Server Metrics 2026-03-17 20:56:52 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 94296.0 (26h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1163943
telemt_connections_bad_total 8633
telemt_handshake_timeouts_total 30622
telemt_upstream_connect_attempt_total 21473
telemt_upstream_connect_success_total 20983
telemt_upstream_connect_fail_total 490
telemt_upstream_connect_attempts_per_request{bucket="1"} 21473
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10856
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9920
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 207
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 490
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 31105
telemt_me_reconnect_success_total 13975
telemt_me_reader_eof_total 15194
telemt_me_idle_close_by_peer_total 15193
telemt_me_route_drop_no_conn_total 520710
telemt_me_route_drop_channel_closed_total 155
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1067249
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7106
telemt_desync_full_logged_total 2039
telemt_desync_suppressed_total 5067
telemt_desync_frames_bucket_total{bucket="1_2"} 1911
telemt_desync_frames_bucket_total{bucket="3_10"} 2694
telemt_desync_frames_bucket_total{bucket="gt_10"} 2501
telemt_pool_swap_total 73
telemt_me_writer_removed_unexpected_total 14718
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 13953
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 743
telemt_user_connections_total{user="hello"} 1061484
telemt_user_connections_current{user="hello"} 675
telemt_user_octets_from_client{user="hello"} 19004374175 (17.70 GB)
telemt_user_octets_to_client{user="hello"} 374014697007 (348.33 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 255
telemt_user_unique_ips_recent_window{user="hello"} 84
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 94547.4 (26h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1199337
telemt_connections_bad_total 59446
telemt_handshake_timeouts_total 43156
telemt_upstream_connect_attempt_total 456984
telemt_upstream_connect_success_total 456100
telemt_upstream_connect_fail_total 884
telemt_upstream_connect_attempts_per_request{bucket="1"} 456984
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 382560
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30249
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43289
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 884
telemt_me_keepalive_timeout_total 342
telemt_me_reconnect_attempts_total 57531
telemt_me_reconnect_success_total 14378
telemt_me_reader_eof_total 16334
telemt_me_idle_close_by_peer_total 16334
telemt_me_route_drop_no_conn_total 303573
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 597230
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2603
telemt_desync_full_logged_total 838
telemt_desync_suppressed_total 1765
telemt_desync_frames_bucket_total{bucket="1_2"} 496
telemt_desync_frames_bucket_total{bucket="3_10"} 1091
telemt_desync_frames_bucket_total{bucket="gt_10"} 1016
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 15906
telemt_me_refill_failed_total 1344
telemt_me_writer_restored_same_endpoint_total 14362
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 1528
telemt_user_connections_total{user="hello"} 1033657
telemt_user_connections_current{user="hello"} 1412
telemt_user_octets_from_client{user="hello"} 14362418430 (13.38 GB)
telemt_user_octets_to_client{user="hello"} 341256295470 (317.82 GB)
telemt_user_msgs_from_client{user="hello"} 7417237
telemt_user_msgs_to_client{user="hello"} 31692884
telemt_user_unique_ips_current{user="hello"} 425
telemt_user_unique_ips_recent_window{user="hello"} 139
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 94323.4 (26h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 668075
telemt_connections_bad_total 38329
telemt_handshake_timeouts_total 22375
telemt_upstream_connect_attempt_total 22636
telemt_upstream_connect_success_total 22506
telemt_upstream_connect_fail_total 130
telemt_upstream_connect_attempts_per_request{bucket="1"} 22636
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10291
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12121
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 130
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 38422
telemt_me_reconnect_success_total 17748
telemt_me_reader_eof_total 19370
telemt_me_idle_close_by_peer_total 19363
telemt_me_route_drop_no_conn_total 284600
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 575504
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1830
telemt_desync_full_logged_total 550
telemt_desync_suppressed_total 1280
telemt_desync_frames_bucket_total{bucket="1_2"} 512
telemt_desync_frames_bucket_total{bucket="3_10"} 720
telemt_desync_frames_bucket_total{bucket="gt_10"} 598
telemt_pool_swap_total 70
telemt_me_writer_removed_unexpected_total 18635
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 17736
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 887
telemt_user_connections_total{user="hello"} 573776
telemt_user_connections_current{user="hello"} 1018
telemt_user_octets_from_client{user="hello"} 28589456816 (26.63 GB)
telemt_user_octets_to_client{user="hello"} 238795363384 (222.40 GB)
telemt_user_unique_ips_current{user="hello"} 296
telemt_user_unique_ips_recent_window{user="hello"} 99
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 94382.7 (26h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1170107
telemt_connections_bad_total 35316
telemt_handshake_timeouts_total 21171
telemt_upstream_connect_attempt_total 82202
telemt_upstream_connect_success_total 81789
telemt_upstream_connect_fail_total 413
telemt_upstream_connect_attempts_per_request{bucket="1"} 82202
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 69619
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11802
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 29
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 339
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 413
telemt_me_keepalive_timeout_total 273
telemt_me_reconnect_attempts_total 34017
telemt_me_reconnect_success_total 13703
telemt_me_reader_eof_total 15100
telemt_me_idle_close_by_peer_total 15099
telemt_me_route_drop_no_conn_total 487631
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 954926
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3280
telemt_desync_full_logged_total 1044
telemt_desync_suppressed_total 2236
telemt_desync_frames_bucket_total{bucket="1_2"} 805
telemt_desync_frames_bucket_total{bucket="3_10"} 1391
telemt_desync_frames_bucket_total{bucket="gt_10"} 1084
telemt_pool_swap_total 69
telemt_me_writer_removed_unexpected_total 14591
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 13694
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 888
telemt_user_connections_total{user="hello"} 1017444
telemt_user_connections_current{user="hello"} 1222
telemt_user_octets_from_client{user="hello"} 15182051007 (14.14 GB)
telemt_user_octets_to_client{user="hello"} 422335345809 (393.33 GB)
telemt_user_msgs_from_client{user="hello"} 734453
telemt_user_msgs_to_client{user="hello"} 5166140
telemt_user_unique_ips_current{user="hello"} 336
telemt_user_unique_ips_recent_window{user="hello"} 133
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 94354.5 (26h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 724721
telemt_connections_bad_total 90511
telemt_handshake_timeouts_total 6183
telemt_upstream_connect_attempt_total 41018
telemt_upstream_connect_success_total 40471
telemt_upstream_connect_fail_total 547
telemt_upstream_connect_attempts_per_request{bucket="1"} 41018
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26087
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13992
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 392
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 547
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 51755
telemt_me_reconnect_success_total 19270
telemt_me_reader_eof_total 20987
telemt_me_idle_close_by_peer_total 20985
telemt_me_route_drop_no_conn_total 226085
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 572333
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2637
telemt_desync_full_logged_total 761
telemt_desync_suppressed_total 1876
telemt_desync_frames_bucket_total{bucket="1_2"} 877
telemt_desync_frames_bucket_total{bucket="3_10"} 1058
telemt_desync_frames_bucket_total{bucket="gt_10"} 702
telemt_pool_swap_total 47
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 20613
telemt_me_refill_failed_total 1010
telemt_me_writer_restored_same_endpoint_total 19262
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1343
telemt_user_connections_total{user="hello"} 588954
telemt_user_connections_current{user="hello"} 1145
telemt_user_octets_from_client{user="hello"} 11544781160 (10.75 GB)
telemt_user_octets_to_client{user="hello"} 282486169308 (263.09 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 334
telemt_user_unique_ips_recent_window{user="hello"} 107
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 94515.8 (26h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 972551
telemt_connections_bad_total 69463
telemt_handshake_timeouts_total 9222
telemt_upstream_connect_attempt_total 18672
telemt_upstream_connect_success_total 18563
telemt_upstream_connect_fail_total 109
telemt_upstream_connect_attempts_per_request{bucket="1"} 18672
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8837
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9610
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 106
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 109
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 25128
telemt_me_reconnect_success_total 13851
telemt_me_reader_eof_total 15045
telemt_me_idle_close_by_peer_total 15043
telemt_me_route_drop_no_conn_total 678209
telemt_me_route_drop_channel_closed_total 86
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 971746
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1962
telemt_desync_full_logged_total 685
telemt_desync_suppressed_total 1277
telemt_desync_frames_bucket_total{bucket="1_2"} 452
telemt_desync_frames_bucket_total{bucket="3_10"} 742
telemt_desync_frames_bucket_total{bucket="gt_10"} 768
telemt_pool_swap_total 79
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 14432
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 13837
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 581
telemt_user_connections_total{user="hello"} 834780
telemt_user_connections_current{user="hello"} 580
telemt_user_octets_from_client{user="hello"} 12959150652 (12.07 GB)
telemt_user_octets_to_client{user="hello"} 360258932940 (335.52 GB)
telemt_user_unique_ips_current{user="hello"} 217
telemt_user_unique_ips_recent_window{user="hello"} 74
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 42282.8 (11h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 304991
telemt_connections_bad_total 40228
telemt_handshake_timeouts_total 9032
telemt_upstream_connect_attempt_total 17315
telemt_upstream_connect_success_total 17155
telemt_upstream_connect_fail_total 160
telemt_upstream_connect_attempts_per_request{bucket="1"} 17315
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9199
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7865
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 160
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 26474
telemt_me_reconnect_success_total 14882
telemt_me_reader_eof_total 15724
telemt_me_idle_close_by_peer_total 15724
telemt_me_seq_mismatch_total 20
telemt_me_route_drop_no_conn_total 75363
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 234418
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 732
telemt_desync_full_logged_total 203
telemt_desync_suppressed_total 529
telemt_desync_frames_bucket_total{bucket="1_2"} 198
telemt_desync_frames_bucket_total{bucket="3_10"} 282
telemt_desync_frames_bucket_total{bucket="gt_10"} 252
telemt_pool_swap_total 20
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 15419
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 14854
telemt_me_writer_restored_fallback_total 28
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 537
telemt_user_connections_total{user="hello"} 234365
telemt_user_connections_current{user="hello"} 703
telemt_user_octets_from_client{user="hello"} 20725542885 (19.30 GB)
telemt_user_octets_to_client{user="hello"} 196636367966 (183.13 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 205
telemt_user_unique_ips_recent_window{user="hello"} 63
```