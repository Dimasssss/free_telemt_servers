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

# Server Metrics 2026-03-18 16:50:04 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 5081.6 (1h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 159851
telemt_connections_bad_total 12223
telemt_handshake_timeouts_total 5198
telemt_upstream_connect_attempt_total 731
telemt_upstream_connect_success_total 731
telemt_upstream_connect_attempts_per_request{bucket="1"} 731
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 363
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 345
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 446
telemt_me_reconnect_success_total 444
telemt_me_reader_eof_total 446
telemt_me_idle_close_by_peer_total 446
telemt_me_seq_mismatch_total 1
telemt_me_route_drop_no_conn_total 85093
telemt_me_route_drop_channel_closed_total 34
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 131599
telemt_me_writer_pick_total{mode="p2c",result="full"} 116
telemt_me_writer_pick_total{mode="p2c",result="closed"} 293
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 762
telemt_desync_full_logged_total 224
telemt_desync_suppressed_total 538
telemt_desync_frames_bucket_total{bucket="1_2"} 184
telemt_desync_frames_bucket_total{bucket="3_10"} 253
telemt_desync_frames_bucket_total{bucket="gt_10"} 325
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 458
telemt_me_writer_restored_same_endpoint_total 432
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 75
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 131539
telemt_user_connections_current{user="hello"} 1463
telemt_user_octets_from_client{user="hello"} 1843247516 (1.72 GB)
telemt_user_octets_to_client{user="hello"} 46924859164 (43.70 GB)
telemt_user_unique_ips_current{user="hello"} 484
telemt_user_unique_ips_recent_window{user="hello"} 179
```

## psb.hosting

```
telemt 3.3.22

telemt_uptime_seconds 9910.7 (2h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1019009
telemt_connections_bad_total 64748
telemt_connections_current 3538
telemt_connections_me_current 3538
telemt_handshake_timeouts_total 15544
telemt_upstream_connect_attempt_total 1782
telemt_upstream_connect_success_total 1773
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 1782
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 973
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 788
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_reconnect_attempts_total 1268
telemt_me_reconnect_success_total 1258
telemt_me_reader_eof_total 1203
telemt_me_idle_close_by_peer_total 1202
telemt_me_route_drop_no_conn_total 1004419
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 888446
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2494
telemt_desync_full_logged_total 795
telemt_desync_suppressed_total 1699
telemt_desync_frames_bucket_total{bucket="1_2"} 500
telemt_desync_frames_bucket_total{bucket="3_10"} 1005
telemt_desync_frames_bucket_total{bucket="gt_10"} 989
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1190
telemt_me_writer_restored_same_endpoint_total 1256
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 2874
telemt_user_connections_total{user="hello"} 887605
telemt_user_connections_current{user="hello"} 3538
telemt_user_octets_from_client{user="hello"} 11371948012 (10.59 GB)
telemt_user_octets_to_client{user="hello"} 255256713628 (237.73 GB)
telemt_user_unique_ips_current{user="hello"} 1156
telemt_user_unique_ips_recent_window{user="hello"} 485
```

## koara.io

```
telemt 3.3.22

telemt_uptime_seconds 9839.2 (2h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 688004
telemt_connections_bad_total 46962
telemt_connections_current 3118
telemt_connections_me_current 3118
telemt_handshake_timeouts_total 15087
telemt_upstream_connect_attempt_total 1366
telemt_upstream_connect_success_total 1360
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 1366
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 715
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 633
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 29
telemt_me_reconnect_attempts_total 854
telemt_me_reconnect_success_total 843
telemt_me_reader_eof_total 887
telemt_me_idle_close_by_peer_total 887
telemt_me_route_drop_no_conn_total 345482
telemt_me_route_drop_channel_closed_total 31
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 583228
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2380
telemt_desync_full_logged_total 684
telemt_desync_suppressed_total 1696
telemt_desync_frames_bucket_total{bucket="1_2"} 542
telemt_desync_frames_bucket_total{bucket="3_10"} 890
telemt_desync_frames_bucket_total{bucket="gt_10"} 948
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 873
telemt_me_writer_restored_same_endpoint_total 826
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 652
telemt_me_writer_removed_unexpected_minus_restored_total 30
telemt_user_connections_total{user="hello"} 582928
telemt_user_connections_current{user="hello"} 3118
telemt_user_octets_from_client{user="hello"} 10657077240 (9.93 GB)
telemt_user_octets_to_client{user="hello"} 238148103228 (221.79 GB)
telemt_user_unique_ips_current{user="hello"} 996
telemt_user_unique_ips_recent_window{user="hello"} 390
```

## landvps.ru

```
telemt 3.3.22

telemt_uptime_seconds 10553.4 (2h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1004529
telemt_connections_bad_total 22974
telemt_connections_current 2553
telemt_connections_me_current 2553
telemt_handshake_timeouts_total 12834
telemt_upstream_connect_attempt_total 1678
telemt_upstream_connect_success_total 1666
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 1678
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 867
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 786
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 18
telemt_me_reconnect_attempts_total 1112
telemt_me_reconnect_success_total 1102
telemt_me_reader_eof_total 1112
telemt_me_idle_close_by_peer_total 1111
telemt_me_route_drop_no_conn_total 1673163
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 901042
telemt_me_writer_pick_total{mode="p2c",result="full"} 30
telemt_me_writer_pick_total{mode="p2c",result="closed"} 61
telemt_me_endpoint_quarantine_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3373
telemt_desync_full_logged_total 842
telemt_desync_suppressed_total 2531
telemt_desync_frames_bucket_total{bucket="1_2"} 784
telemt_desync_frames_bucket_total{bucket="3_10"} 1545
telemt_desync_frames_bucket_total{bucket="gt_10"} 1044
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 1094
telemt_me_writer_restored_same_endpoint_total 1091
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 1000
telemt_user_connections_total{user="hello"} 900988
telemt_user_connections_current{user="hello"} 2553
telemt_user_octets_from_client{user="hello"} 7942369748 (7.40 GB)
telemt_user_octets_to_client{user="hello"} 160062082228 (149.07 GB)
telemt_user_unique_ips_current{user="hello"} 840
telemt_user_unique_ips_recent_window{user="hello"} 478
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 5068.5 (1h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 399283
telemt_connections_bad_total 81197
telemt_handshake_timeouts_total 3735
telemt_upstream_connect_attempt_total 927
telemt_upstream_connect_success_total 900
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 927
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 507
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 387
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 1609
telemt_me_reconnect_success_total 610
telemt_me_reader_eof_total 630
telemt_me_idle_close_by_peer_total 630
telemt_me_route_drop_no_conn_total 160345
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 284599
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1010
telemt_desync_full_logged_total 349
telemt_desync_suppressed_total 661
telemt_desync_frames_bucket_total{bucket="1_2"} 158
telemt_desync_frames_bucket_total{bucket="3_10"} 318
telemt_desync_frames_bucket_total{bucket="gt_10"} 534
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 643
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 584
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 786
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 284252
telemt_user_connections_current{user="hello"} 3385
telemt_user_octets_from_client{user="hello"} 4314211988 (4.02 GB)
telemt_user_octets_to_client{user="hello"} 111900457120 (104.22 GB)
telemt_user_unique_ips_current{user="hello"} 1081
telemt_user_unique_ips_recent_window{user="hello"} 429
```

## hostvds.com

```
telemt 3.3.22

telemt_uptime_seconds 10003.3 (2h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 185461
telemt_connections_bad_total 7431
telemt_connections_current 781
telemt_connections_me_current 781
telemt_relay_adaptive_promotions_total 18
telemt_relay_adaptive_hard_promotions_total 18
telemt_handshake_timeouts_total 1816
telemt_upstream_connect_attempt_total 5933
telemt_upstream_connect_success_total 5922
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 5933
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3250
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2629
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 28
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_reconnect_attempts_total 331003
telemt_me_reconnect_success_total 1541
telemt_me_reader_eof_total 1496
telemt_me_idle_close_by_peer_total 1496
telemt_me_route_drop_no_conn_total 102304
telemt_me_route_drop_channel_closed_total 36
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 163254
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 9
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 359
telemt_desync_full_logged_total 130
telemt_desync_suppressed_total 229
telemt_desync_frames_bucket_total{bucket="1_2"} 59
telemt_desync_frames_bucket_total{bucket="3_10"} 147
telemt_desync_frames_bucket_total{bucket="gt_10"} 153
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1475
telemt_me_refill_failed_total 10448
telemt_me_writer_restored_same_endpoint_total 1530
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 40876
telemt_user_connections_total{user="hello"} 166980
telemt_user_connections_current{user="hello"} 781
telemt_user_octets_from_client{user="hello"} 2496108909 (2.32 GB)
telemt_user_octets_to_client{user="hello"} 36090895785 (33.61 GB)
telemt_user_msgs_from_client{user="hello"} 38712
telemt_user_msgs_to_client{user="hello"} 31668
telemt_user_unique_ips_current{user="hello"} 291
telemt_user_unique_ips_recent_window{user="hello"} 112
```

## 4vps.su

```
telemt 3.3.22

telemt_uptime_seconds 9072.7 (2h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 545746
telemt_connections_bad_total 22438
telemt_connections_current 2570
telemt_connections_me_current 2570
telemt_handshake_timeouts_total 10460
telemt_upstream_connect_attempt_total 1685
telemt_upstream_connect_success_total 1684
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 1685
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 922
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 753
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 16690
telemt_me_reconnect_success_total 1180
telemt_me_reader_eof_total 1143
telemt_me_idle_close_by_peer_total 1143
telemt_me_route_drop_no_conn_total 354846
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="base"} 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 471677
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1536
telemt_desync_full_logged_total 548
telemt_desync_suppressed_total 988
telemt_desync_frames_bucket_total{bucket="1_2"} 340
telemt_desync_frames_bucket_total{bucket="3_10"} 543
telemt_desync_frames_bucket_total{bucket="gt_10"} 653
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1138
telemt_me_refill_failed_total 741
telemt_me_writer_restored_same_endpoint_total 1119
telemt_me_writer_restored_fallback_total 61
telemt_me_async_recovery_trigger_total 9552
telemt_user_connections_total{user="hello"} 470764
telemt_user_connections_current{user="hello"} 2570
telemt_user_octets_from_client{user="hello"} 8275039748 (7.71 GB)
telemt_user_octets_to_client{user="hello"} 213612156468 (198.94 GB)
telemt_user_unique_ips_current{user="hello"} 848
telemt_user_unique_ips_recent_window{user="hello"} 331
```