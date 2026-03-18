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

# Server Metrics 2026-03-18 16:44:57 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 4775.4 (1h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 151994
telemt_connections_bad_total 11969
telemt_handshake_timeouts_total 5105
telemt_upstream_connect_attempt_total 688
telemt_upstream_connect_success_total 688
telemt_upstream_connect_attempts_per_request{bucket="1"} 688
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 341
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 324
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 403
telemt_me_reconnect_success_total 401
telemt_me_reader_eof_total 403
telemt_me_idle_close_by_peer_total 403
telemt_me_seq_mismatch_total 1
telemt_me_route_drop_no_conn_total 82603
telemt_me_route_drop_channel_closed_total 32
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 124555
telemt_me_writer_pick_total{mode="p2c",result="full"} 116
telemt_me_writer_pick_total{mode="p2c",result="closed"} 293
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 728
telemt_desync_full_logged_total 213
telemt_desync_suppressed_total 515
telemt_desync_frames_bucket_total{bucket="1_2"} 183
telemt_desync_frames_bucket_total{bucket="3_10"} 237
telemt_desync_frames_bucket_total{bucket="gt_10"} 308
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 415
telemt_me_writer_restored_same_endpoint_total 389
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 75
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 124502
telemt_user_connections_current{user="hello"} 1485
telemt_user_octets_from_client{user="hello"} 1715833668 (1.60 GB)
telemt_user_octets_to_client{user="hello"} 44212121456 (41.18 GB)
telemt_user_unique_ips_current{user="hello"} 501
telemt_user_unique_ips_recent_window{user="hello"} 189
```

## psb.hosting

```
telemt 3.3.22

telemt_uptime_seconds 9603.6 (2h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 996701
telemt_connections_bad_total 63073
telemt_connections_current 3552
telemt_connections_me_current 3552
telemt_handshake_timeouts_total 15311
telemt_upstream_connect_attempt_total 1758
telemt_upstream_connect_success_total 1749
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 1758
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 964
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 773
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_reconnect_attempts_total 1244
telemt_me_reconnect_success_total 1234
telemt_me_reader_eof_total 1179
telemt_me_idle_close_by_peer_total 1178
telemt_me_route_drop_no_conn_total 996032
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 869051
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2430
telemt_desync_full_logged_total 767
telemt_desync_suppressed_total 1663
telemt_desync_frames_bucket_total{bucket="1_2"} 489
telemt_desync_frames_bucket_total{bucket="3_10"} 982
telemt_desync_frames_bucket_total{bucket="gt_10"} 959
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1166
telemt_me_writer_restored_same_endpoint_total 1232
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 2874
telemt_user_connections_total{user="hello"} 868212
telemt_user_connections_current{user="hello"} 3552
telemt_user_octets_from_client{user="hello"} 11142435816 (10.38 GB)
telemt_user_octets_to_client{user="hello"} 247113230044 (230.14 GB)
telemt_user_unique_ips_current{user="hello"} 1156
telemt_user_unique_ips_recent_window{user="hello"} 496
```

## koara.io

```
telemt 3.3.22

telemt_uptime_seconds 9532.1 (2h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 667335
telemt_connections_bad_total 45237
telemt_connections_current 3164
telemt_connections_me_current 3164
telemt_handshake_timeouts_total 14680
telemt_upstream_connect_attempt_total 1347
telemt_upstream_connect_success_total 1341
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 1347
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 703
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 626
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 29
telemt_me_reconnect_attempts_total 835
telemt_me_reconnect_success_total 825
telemt_me_reader_eof_total 868
telemt_me_idle_close_by_peer_total 868
telemt_me_route_drop_no_conn_total 339266
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 566111
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2322
telemt_desync_full_logged_total 663
telemt_desync_suppressed_total 1659
telemt_desync_frames_bucket_total{bucket="1_2"} 527
telemt_desync_frames_bucket_total{bucket="3_10"} 871
telemt_desync_frames_bucket_total{bucket="gt_10"} 924
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 854
telemt_me_writer_restored_same_endpoint_total 808
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 652
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 565811
telemt_user_connections_current{user="hello"} 3164
telemt_user_octets_from_client{user="hello"} 10425989364 (9.71 GB)
telemt_user_octets_to_client{user="hello"} 228035681180 (212.37 GB)
telemt_user_unique_ips_current{user="hello"} 986
telemt_user_unique_ips_recent_window{user="hello"} 396
```

## landvps.ru

```
telemt 3.3.22

telemt_uptime_seconds 10246.5 (2h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 956298
telemt_connections_bad_total 21105
telemt_connections_current 2680
telemt_connections_me_current 2680
telemt_handshake_timeouts_total 12357
telemt_upstream_connect_attempt_total 1656
telemt_upstream_connect_success_total 1644
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 1656
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 856
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 775
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 18
telemt_me_reconnect_attempts_total 1090
telemt_me_reconnect_success_total 1080
telemt_me_reader_eof_total 1090
telemt_me_idle_close_by_peer_total 1089
telemt_me_route_drop_no_conn_total 1543105
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 858472
telemt_me_writer_pick_total{mode="p2c",result="full"} 30
telemt_me_writer_pick_total{mode="p2c",result="closed"} 61
telemt_me_endpoint_quarantine_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3284
telemt_desync_full_logged_total 824
telemt_desync_suppressed_total 2460
telemt_desync_frames_bucket_total{bucket="1_2"} 769
telemt_desync_frames_bucket_total{bucket="3_10"} 1490
telemt_desync_frames_bucket_total{bucket="gt_10"} 1025
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 1072
telemt_me_writer_restored_same_endpoint_total 1069
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 1000
telemt_user_connections_total{user="hello"} 858425
telemt_user_connections_current{user="hello"} 2680
telemt_user_octets_from_client{user="hello"} 7758212728 (7.23 GB)
telemt_user_octets_to_client{user="hello"} 156118361424 (145.40 GB)
telemt_user_unique_ips_current{user="hello"} 828
telemt_user_unique_ips_recent_window{user="hello"} 450
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 4761.3 (1h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 376142
telemt_connections_bad_total 76875
telemt_handshake_timeouts_total 3631
telemt_upstream_connect_attempt_total 904
telemt_upstream_connect_success_total 877
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 904
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 498
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 373
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_keepalive_timeout_total 14
telemt_me_reconnect_attempts_total 1586
telemt_me_reconnect_success_total 587
telemt_me_reader_eof_total 606
telemt_me_idle_close_by_peer_total 606
telemt_me_route_drop_no_conn_total 147897
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 267189
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 939
telemt_desync_full_logged_total 319
telemt_desync_suppressed_total 620
telemt_desync_frames_bucket_total{bucket="1_2"} 146
telemt_desync_frames_bucket_total{bucket="3_10"} 295
telemt_desync_frames_bucket_total{bucket="gt_10"} 498
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 620
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 561
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 786
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 266863
telemt_user_connections_current{user="hello"} 3210
telemt_user_octets_from_client{user="hello"} 4035182544 (3.76 GB)
telemt_user_octets_to_client{user="hello"} 103445276056 (96.34 GB)
telemt_user_unique_ips_current{user="hello"} 1029
telemt_user_unique_ips_recent_window{user="hello"} 432
```

## hostvds.com

```
telemt 3.3.22

telemt_uptime_seconds 9696.5 (2h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 181372
telemt_connections_bad_total 7418
telemt_connections_current 857
telemt_connections_me_current 857
telemt_relay_adaptive_promotions_total 18
telemt_relay_adaptive_hard_promotions_total 18
telemt_handshake_timeouts_total 1726
telemt_upstream_connect_attempt_total 5867
telemt_upstream_connect_success_total 5856
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 5867
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3217
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2596
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 28
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_reconnect_attempts_total 330978
telemt_me_reconnect_success_total 1516
telemt_me_reader_eof_total 1471
telemt_me_idle_close_by_peer_total 1471
telemt_me_route_drop_no_conn_total 100421
telemt_me_route_drop_channel_closed_total 36
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 159470
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 9
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 351
telemt_desync_full_logged_total 126
telemt_desync_suppressed_total 225
telemt_desync_frames_bucket_total{bucket="1_2"} 59
telemt_desync_frames_bucket_total{bucket="3_10"} 142
telemt_desync_frames_bucket_total{bucket="gt_10"} 150
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1450
telemt_me_refill_failed_total 10448
telemt_me_writer_restored_same_endpoint_total 1505
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 40876
telemt_user_connections_total{user="hello"} 163196
telemt_user_connections_current{user="hello"} 857
telemt_user_octets_from_client{user="hello"} 2443326533 (2.28 GB)
telemt_user_octets_to_client{user="hello"} 35050067149 (32.64 GB)
telemt_user_msgs_from_client{user="hello"} 38712
telemt_user_msgs_to_client{user="hello"} 31668
telemt_user_unique_ips_current{user="hello"} 309
telemt_user_unique_ips_recent_window{user="hello"} 106
```

## 4vps.su

```
telemt 3.3.22

telemt_uptime_seconds 8765.7 (2h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 529884
telemt_connections_bad_total 20434
telemt_connections_current 2566
telemt_connections_me_current 2566
telemt_handshake_timeouts_total 9967
telemt_upstream_connect_attempt_total 1638
telemt_upstream_connect_success_total 1637
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 1638
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 891
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 737
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 16675
telemt_me_reconnect_success_total 1165
telemt_me_reader_eof_total 1128
telemt_me_idle_close_by_peer_total 1128
telemt_me_route_drop_no_conn_total 350644
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="base"} 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 458751
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1455
telemt_desync_full_logged_total 523
telemt_desync_suppressed_total 932
telemt_desync_frames_bucket_total{bucket="1_2"} 318
telemt_desync_frames_bucket_total{bucket="3_10"} 516
telemt_desync_frames_bucket_total{bucket="gt_10"} 621
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1123
telemt_me_refill_failed_total 741
telemt_me_writer_restored_same_endpoint_total 1104
telemt_me_writer_restored_fallback_total 61
telemt_me_async_recovery_trigger_total 9552
telemt_user_connections_total{user="hello"} 457836
telemt_user_connections_current{user="hello"} 2566
telemt_user_octets_from_client{user="hello"} 8031131568 (7.48 GB)
telemt_user_octets_to_client{user="hello"} 205173993176 (191.08 GB)
telemt_user_unique_ips_current{user="hello"} 821
telemt_user_unique_ips_recent_window{user="hello"} 304
```