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

# Server Metrics 2026-03-19 05:37:49 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 28161.9 (7h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 414010
telemt_connections_bad_total 40824
telemt_connections_current 1105
telemt_connections_me_current 1105
telemt_handshake_timeouts_total 21256
telemt_upstream_connect_attempt_total 5437
telemt_upstream_connect_success_total 5344
telemt_upstream_connect_fail_total 93
telemt_upstream_connect_attempts_per_request{bucket="1"} 5437
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2612
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2729
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 93
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 3943
telemt_me_reconnect_success_total 3924
telemt_me_reader_eof_total 4139
telemt_me_idle_close_by_peer_total 4138
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 109068
telemt_me_route_drop_channel_closed_total 25
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 305825
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2027
telemt_desync_full_logged_total 566
telemt_desync_suppressed_total 1461
telemt_desync_frames_bucket_total{bucket="1_2"} 731
telemt_desync_frames_bucket_total{bucket="3_10"} 797
telemt_desync_frames_bucket_total{bucket="gt_10"} 499
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 3959
telemt_me_writer_restored_same_endpoint_total 3907
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 303078
telemt_user_connections_current{user="hello"} 1105
telemt_user_octets_from_client{user="hello"} 3835128452 (3.57 GB)
telemt_user_octets_to_client{user="hello"} 102911240980 (95.84 GB)
telemt_user_unique_ips_current{user="hello"} 423
telemt_user_unique_ips_recent_window{user="hello"} 145
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 28166.0 (7h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 834365
telemt_connections_bad_total 48536
telemt_connections_current 2931
telemt_connections_me_current 2931
telemt_handshake_timeouts_total 24093
telemt_upstream_connect_attempt_total 5255
telemt_upstream_connect_success_total 5154
telemt_upstream_connect_fail_total 101
telemt_upstream_connect_attempts_per_request{bucket="1"} 5255
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2518
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2625
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 101
telemt_me_reconnect_attempts_total 3741
telemt_me_reconnect_success_total 3721
telemt_me_reader_eof_total 3928
telemt_me_idle_close_by_peer_total 3928
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 257867
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 691428
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 31
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2812
telemt_desync_full_logged_total 957
telemt_desync_suppressed_total 1855
telemt_desync_frames_bucket_total{bucket="1_2"} 533
telemt_desync_frames_bucket_total{bucket="3_10"} 1059
telemt_desync_frames_bucket_total{bucket="gt_10"} 1220
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 3787
telemt_me_writer_restored_same_endpoint_total 3702
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 66
telemt_user_connections_total{user="hello"} 691311
telemt_user_connections_current{user="hello"} 2931
telemt_user_octets_from_client{user="hello"} 16519645380 (15.39 GB)
telemt_user_octets_to_client{user="hello"} 301844713508 (281.11 GB)
telemt_user_unique_ips_current{user="hello"} 1111
telemt_user_unique_ips_recent_window{user="hello"} 427
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 28163.5 (7h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 708801
telemt_connections_bad_total 121649
telemt_connections_current 2493
telemt_connections_me_current 2493
telemt_handshake_timeouts_total 24454
telemt_upstream_connect_attempt_total 5125
telemt_upstream_connect_success_total 5125
telemt_upstream_connect_attempts_per_request{bucket="1"} 5125
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2628
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2490
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 3709
telemt_me_reconnect_success_total 3694
telemt_me_reader_eof_total 3916
telemt_me_idle_close_by_peer_total 3916
telemt_me_route_drop_no_conn_total 214483
telemt_me_route_drop_channel_closed_total 16
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 512508
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2689
telemt_desync_full_logged_total 874
telemt_desync_suppressed_total 1815
telemt_desync_frames_bucket_total{bucket="1_2"} 441
telemt_desync_frames_bucket_total{bucket="3_10"} 955
telemt_desync_frames_bucket_total{bucket="gt_10"} 1293
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 3760
telemt_me_writer_restored_same_endpoint_total 3678
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 66
telemt_user_connections_total{user="hello"} 512497
telemt_user_connections_current{user="hello"} 2493
telemt_user_octets_from_client{user="hello"} 10254610620 (9.55 GB)
telemt_user_octets_to_client{user="hello"} 311048460948 (289.69 GB)
telemt_user_unique_ips_current{user="hello"} 891
telemt_user_unique_ips_recent_window{user="hello"} 330
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 28216.3 (7h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 791061
telemt_connections_bad_total 87115
telemt_connections_current 2295
telemt_connections_me_current 2295
telemt_handshake_timeouts_total 19385
telemt_upstream_connect_attempt_total 4985
telemt_upstream_connect_success_total 4985
telemt_upstream_connect_attempts_per_request{bucket="1"} 4985
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2526
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2447
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_reconnect_attempts_total 3574
telemt_me_reconnect_success_total 3553
telemt_me_reader_eof_total 3750
telemt_me_idle_close_by_peer_total 3749
telemt_me_route_drop_no_conn_total 229508
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 508730
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1629
telemt_desync_full_logged_total 593
telemt_desync_suppressed_total 1036
telemt_desync_frames_bucket_total{bucket="1_2"} 297
telemt_desync_frames_bucket_total{bucket="3_10"} 671
telemt_desync_frames_bucket_total{bucket="gt_10"} 661
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 3600
telemt_me_writer_restored_same_endpoint_total 3529
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 272
telemt_me_writer_removed_unexpected_minus_restored_total 47
telemt_user_connections_total{user="hello"} 507647
telemt_user_connections_current{user="hello"} 2295
telemt_user_octets_from_client{user="hello"} 7610754544 (7.09 GB)
telemt_user_octets_to_client{user="hello"} 194400008692 (181.05 GB)
telemt_user_unique_ips_current{user="hello"} 814
telemt_user_unique_ips_recent_window{user="hello"} 359
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 28159.8 (7h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 938037
telemt_connections_bad_total 271091
telemt_connections_current 2427
telemt_connections_me_current 2427
telemt_handshake_timeouts_total 25726
telemt_upstream_connect_attempt_total 5082
telemt_upstream_connect_success_total 5051
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 5082
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2541
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2492
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_reconnect_attempts_total 3642
telemt_me_reconnect_success_total 3621
telemt_me_reader_eof_total 3833
telemt_me_idle_close_by_peer_total 3833
telemt_me_route_drop_no_conn_total 223939
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 545726
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2660
telemt_desync_full_logged_total 923
telemt_desync_suppressed_total 1737
telemt_desync_frames_bucket_total{bucket="1_2"} 649
telemt_desync_frames_bucket_total{bucket="3_10"} 1150
telemt_desync_frames_bucket_total{bucket="gt_10"} 861
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 3658
telemt_me_writer_restored_same_endpoint_total 3597
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 37
telemt_user_connections_total{user="hello"} 545637
telemt_user_connections_current{user="hello"} 2427
telemt_user_octets_from_client{user="hello"} 14972675876 (13.94 GB)
telemt_user_octets_to_client{user="hello"} 305815354552 (284.81 GB)
telemt_user_unique_ips_current{user="hello"} 920
telemt_user_unique_ips_recent_window{user="hello"} 362
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 28171.2 (7h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 159239
telemt_connections_bad_total 10639
telemt_connections_current 639
telemt_connections_me_current 639
telemt_handshake_timeouts_total 1259
telemt_upstream_connect_attempt_total 7799
telemt_upstream_connect_success_total 7592
telemt_upstream_connect_fail_total 207
telemt_upstream_connect_attempts_per_request{bucket="1"} 7799
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3677
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3915
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 207
telemt_me_reconnect_attempts_total 10600
telemt_me_reconnect_success_total 6163
telemt_me_reader_eof_total 6527
telemt_me_idle_close_by_peer_total 6527
telemt_me_route_drop_no_conn_total 64245
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 139213
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 186
telemt_desync_full_logged_total 71
telemt_desync_suppressed_total 115
telemt_desync_frames_bucket_total{bucket="1_2"} 55
telemt_desync_frames_bucket_total{bucket="3_10"} 80
telemt_desync_frames_bucket_total{bucket="gt_10"} 51
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 6322
telemt_me_refill_failed_total 138
telemt_me_writer_restored_same_endpoint_total 6133
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 159
telemt_user_connections_total{user="hello"} 139206
telemt_user_connections_current{user="hello"} 639
telemt_user_octets_from_client{user="hello"} 2369246692 (2.21 GB)
telemt_user_octets_to_client{user="hello"} 80909331452 (75.35 GB)
telemt_user_unique_ips_current{user="hello"} 246
telemt_user_unique_ips_recent_window{user="hello"} 108
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 28162.2 (7h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 547842
telemt_connections_bad_total 56997
telemt_connections_current 2226
telemt_connections_me_current 2226
telemt_handshake_timeouts_total 25867
telemt_upstream_connect_attempt_total 5782
telemt_upstream_connect_success_total 5782
telemt_upstream_connect_attempts_per_request{bucket="1"} 5782
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3070
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2709
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 4372
telemt_me_reconnect_success_total 4359
telemt_me_reader_eof_total 4604
telemt_me_idle_close_by_peer_total 4604
telemt_me_route_drop_no_conn_total 155620
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 447591
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2541
telemt_desync_full_logged_total 914
telemt_desync_suppressed_total 1627
telemt_desync_frames_bucket_total{bucket="1_2"} 530
telemt_desync_frames_bucket_total{bucket="3_10"} 973
telemt_desync_frames_bucket_total{bucket="gt_10"} 1038
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 4408
telemt_me_writer_restored_same_endpoint_total 4344
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 49
telemt_user_connections_total{user="hello"} 447633
telemt_user_connections_current{user="hello"} 2226
telemt_user_octets_from_client{user="hello"} 5684631112 (5.29 GB)
telemt_user_octets_to_client{user="hello"} 263318054536 (245.23 GB)
telemt_user_unique_ips_current{user="hello"} 777
telemt_user_unique_ips_recent_window{user="hello"} 279
```