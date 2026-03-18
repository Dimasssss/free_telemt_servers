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

# Server Metrics 2026-03-18 10:21:48 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.20

telemt_uptime_seconds 6047.9 (1h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 227664
telemt_connections_bad_total 1666
telemt_handshake_timeouts_total 4827
telemt_upstream_connect_attempt_total 64140
telemt_upstream_connect_success_total 63216
telemt_upstream_connect_fail_total 924
telemt_upstream_connect_attempts_per_request{bucket="1"} 64140
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 59537
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3096
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 583
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 924
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 507576
telemt_me_reconnect_success_total 935
telemt_me_reader_eof_total 895
telemt_me_idle_close_by_peer_total 893
telemt_me_route_drop_no_conn_total 89288
telemt_me_route_drop_channel_closed_total 38
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 138265
telemt_me_writer_pick_total{mode="p2c",result="full"} 21
telemt_me_writer_pick_total{mode="p2c",result="closed"} 54
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 678
telemt_desync_full_logged_total 212
telemt_desync_suppressed_total 466
telemt_desync_frames_bucket_total{bucket="1_2"} 200
telemt_desync_frames_bucket_total{bucket="3_10"} 250
telemt_desync_frames_bucket_total{bucket="gt_10"} 228
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 925
telemt_me_refill_failed_total 16516
telemt_me_writer_restored_same_endpoint_total 830
telemt_me_writer_restored_fallback_total 105
telemt_me_async_recovery_trigger_total 11769
telemt_user_connections_total{user="hello"} 198763
telemt_user_connections_current{user="hello"} 1477
telemt_user_octets_from_client{user="hello"} 2433548000 (2.27 GB)
telemt_user_octets_to_client{user="hello"} 49575402897 (46.17 GB)
telemt_user_msgs_from_client{user="hello"} 846607
telemt_user_msgs_to_client{user="hello"} 1165163
telemt_user_unique_ips_current{user="hello"} 479
telemt_user_unique_ips_recent_window{user="hello"} 250
```

## psb.hosting

```
telemt 3.3.20

telemt_uptime_seconds 6080.1 (1h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 538079
telemt_connections_bad_total 61820
telemt_handshake_timeouts_total 13080
telemt_upstream_connect_attempt_total 1029
telemt_upstream_connect_success_total 1019
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 1029
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 585
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 424
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_failed_total 1
telemt_me_reconnect_attempts_total 694
telemt_me_reconnect_success_total 671
telemt_me_reader_eof_total 644
telemt_me_idle_close_by_peer_total 644
telemt_me_route_drop_no_conn_total 222790
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 433053
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2135
telemt_desync_full_logged_total 586
telemt_desync_suppressed_total 1549
telemt_desync_frames_bucket_total{bucket="1_2"} 408
telemt_desync_frames_bucket_total{bucket="3_10"} 840
telemt_desync_frames_bucket_total{bucket="gt_10"} 887
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 658
telemt_me_writer_restored_same_endpoint_total 670
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 1068
telemt_user_connections_total{user="hello"} 432171
telemt_user_connections_current{user="hello"} 3634
telemt_user_octets_from_client{user="hello"} 9533882152 (8.88 GB)
telemt_user_octets_to_client{user="hello"} 161264617252 (150.19 GB)
telemt_user_unique_ips_current{user="hello"} 1129
telemt_user_unique_ips_recent_window{user="hello"} 514
```

## koara.io

```
telemt 3.3.20

telemt_uptime_seconds 5994.9 (1h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 418041
telemt_connections_bad_total 24883
telemt_handshake_timeouts_total 10774
telemt_upstream_connect_attempt_total 9458
telemt_upstream_connect_success_total 9458
telemt_upstream_connect_attempts_per_request{bucket="1"} 9458
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7631
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1819
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 40
telemt_me_reconnect_attempts_total 606587
telemt_me_reconnect_success_total 914
telemt_me_reader_eof_total 894
telemt_me_idle_close_by_peer_total 893
telemt_me_route_drop_no_conn_total 200299
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 310538
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 729
telemt_desync_full_logged_total 257
telemt_desync_suppressed_total 472
telemt_desync_frames_bucket_total{bucket="1_2"} 167
telemt_desync_frames_bucket_total{bucket="3_10"} 311
telemt_desync_frames_bucket_total{bucket="gt_10"} 251
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 910
telemt_me_refill_failed_total 19672
telemt_me_writer_restored_same_endpoint_total 879
telemt_me_writer_restored_fallback_total 35
telemt_me_async_recovery_trigger_total 14895
telemt_user_connections_total{user="hello"} 318447
telemt_user_connections_current{user="hello"} 2594
telemt_user_octets_from_client{user="hello"} 3274866535 (3.05 GB)
telemt_user_octets_to_client{user="hello"} 118390027604 (110.26 GB)
telemt_user_msgs_from_client{user="hello"} 68547
telemt_user_msgs_to_client{user="hello"} 285346
telemt_user_unique_ips_current{user="hello"} 756
telemt_user_unique_ips_recent_window{user="hello"} 376
```

## landvps.ru

```
telemt 3.3.20

telemt_uptime_seconds 6025.0 (1h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 781201
telemt_connections_bad_total 8456
telemt_handshake_timeouts_total 90241
telemt_upstream_connect_attempt_total 11731
telemt_upstream_connect_success_total 11611
telemt_upstream_connect_fail_total 120
telemt_upstream_connect_attempts_per_request{bucket="1"} 11731
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10471
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1104
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 120
telemt_me_keepalive_timeout_total 699
telemt_me_reconnect_attempts_total 2816073
telemt_me_reconnect_success_total 993
telemt_me_reader_eof_total 1120
telemt_me_idle_close_by_peer_total 1120
telemt_me_route_drop_no_conn_total 1396781
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 606542
telemt_me_writer_pick_total{mode="p2c",result="success_fallback"} 8840
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_writer_pick_blocking_fallback_total 8840
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 914
telemt_desync_full_logged_total 271
telemt_desync_suppressed_total 643
telemt_desync_frames_bucket_total{bucket="1_2"} 228
telemt_desync_frames_bucket_total{bucket="3_10"} 372
telemt_desync_frames_bucket_total{bucket="gt_10"} 314
telemt_me_writer_removed_unexpected_total 1152
telemt_me_refill_failed_total 99709
telemt_me_writer_restored_same_endpoint_total 898
telemt_me_writer_restored_fallback_total 95
telemt_me_async_recovery_trigger_total 365465
telemt_me_writer_removed_unexpected_minus_restored_total 159
telemt_user_connections_total{user="hello"} 625480
telemt_user_connections_current{user="hello"} 2606
telemt_user_octets_from_client{user="hello"} 4486396958 (4.18 GB)
telemt_user_octets_to_client{user="hello"} 81844364761 (76.22 GB)
telemt_user_msgs_from_client{user="hello"} 80007
telemt_user_msgs_to_client{user="hello"} 158054
telemt_user_unique_ips_current{user="hello"} 809
telemt_user_unique_ips_recent_window{user="hello"} 382
```

## rdp-onedash.ru

```
telemt 3.3.20

telemt_uptime_seconds 5919.9 (1h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 411609
telemt_connections_bad_total 11397
telemt_handshake_timeouts_total 6442
telemt_upstream_connect_attempt_total 10693
telemt_upstream_connect_success_total 10692
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 10693
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9580
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 895
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 217
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 61
telemt_me_reconnect_attempts_total 2982804
telemt_me_reconnect_success_total 853
telemt_me_reader_eof_total 807
telemt_me_idle_close_by_peer_total 807
telemt_me_route_drop_no_conn_total 177211
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 341264
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1236
telemt_desync_full_logged_total 414
telemt_desync_suppressed_total 822
telemt_desync_frames_bucket_total{bucket="1_2"} 208
telemt_desync_frames_bucket_total{bucket="3_10"} 477
telemt_desync_frames_bucket_total{bucket="gt_10"} 551
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 807
telemt_me_refill_failed_total 107153
telemt_me_writer_restored_same_endpoint_total 738
telemt_me_writer_restored_fallback_total 115
telemt_me_async_recovery_trigger_total 267383
telemt_user_connections_total{user="hello"} 349677
telemt_user_connections_current{user="hello"} 3015
telemt_user_octets_from_client{user="hello"} 5755406285 (5.36 GB)
telemt_user_octets_to_client{user="hello"} 138883983525 (129.35 GB)
telemt_user_msgs_from_client{user="hello"} 86293
telemt_user_msgs_to_client{user="hello"} 266108
telemt_user_unique_ips_current{user="hello"} 927
telemt_user_unique_ips_recent_window{user="hello"} 434
```

## hostvds.com

```
telemt 3.3.20

telemt_uptime_seconds 5805.1 (1h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 123924
telemt_connections_bad_total 16440
telemt_handshake_timeouts_total 713
telemt_upstream_connect_attempt_total 1096
telemt_upstream_connect_success_total 1096
telemt_upstream_connect_attempts_per_request{bucket="1"} 1096
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 586
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 510
telemt_me_reconnect_attempts_total 754
telemt_me_reconnect_success_total 746
telemt_me_reader_eof_total 746
telemt_me_idle_close_by_peer_total 746
telemt_me_route_drop_no_conn_total 53857
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 99011
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 220
telemt_desync_full_logged_total 83
telemt_desync_suppressed_total 137
telemt_desync_frames_bucket_total{bucket="1_2"} 39
telemt_desync_frames_bucket_total{bucket="3_10"} 91
telemt_desync_frames_bucket_total{bucket="gt_10"} 90
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 742
telemt_me_writer_restored_same_endpoint_total 738
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 130
telemt_user_connections_total{user="hello"} 96609
telemt_user_connections_current{user="hello"} 896
telemt_user_octets_from_client{user="hello"} 1575689536 (1.47 GB)
telemt_user_octets_to_client{user="hello"} 21284467956 (19.82 GB)
telemt_user_unique_ips_current{user="hello"} 322
telemt_user_unique_ips_recent_window{user="hello"} 130
```

## 4vps.su

```
telemt 3.3.20

telemt_uptime_seconds 5876.0 (1h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 300929
telemt_connections_bad_total 19667
telemt_handshake_timeouts_total 5578
telemt_upstream_connect_attempt_total 1142
telemt_upstream_connect_success_total 1123
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 1142
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 645
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 470
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_reconnect_attempts_total 786
telemt_me_reconnect_success_total 773
telemt_me_reader_eof_total 763
telemt_me_idle_close_by_peer_total 763
telemt_me_route_drop_no_conn_total 167732
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 255481
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 878
telemt_desync_full_logged_total 309
telemt_desync_suppressed_total 569
telemt_desync_frames_bucket_total{bucket="1_2"} 171
telemt_desync_frames_bucket_total{bucket="3_10"} 332
telemt_desync_frames_bucket_total{bucket="gt_10"} 375
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 765
telemt_me_writer_restored_same_endpoint_total 763
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 2494
telemt_user_connections_total{user="hello"} 255299
telemt_user_connections_current{user="hello"} 2185
telemt_user_octets_from_client{user="hello"} 4376098764 (4.08 GB)
telemt_user_octets_to_client{user="hello"} 123325708132 (114.86 GB)
telemt_user_unique_ips_current{user="hello"} 656
telemt_user_unique_ips_recent_window{user="hello"} 305
```