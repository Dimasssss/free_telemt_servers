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

# Server Metrics 2026-03-18 20:51:11 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 19550.0 (5h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 469057
telemt_connections_bad_total 26926
telemt_handshake_timeouts_total 9550
telemt_upstream_connect_attempt_total 3443
telemt_upstream_connect_success_total 3440
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 3443
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1692
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1695
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 138
telemt_me_reconnect_attempts_total 2464
telemt_me_reconnect_success_total 2449
telemt_me_reader_eof_total 2556
telemt_me_idle_close_by_peer_total 2556
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 192648
telemt_me_route_drop_channel_closed_total 97
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 399878
telemt_me_writer_pick_total{mode="p2c",result="full"} 116
telemt_me_writer_pick_total{mode="p2c",result="closed"} 293
telemt_me_endpoint_quarantine_total 28
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2368
telemt_desync_full_logged_total 703
telemt_desync_suppressed_total 1665
telemt_desync_frames_bucket_total{bucket="1_2"} 546
telemt_desync_frames_bucket_total{bucket="3_10"} 759
telemt_desync_frames_bucket_total{bucket="gt_10"} 1063
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 2495
telemt_me_writer_restored_same_endpoint_total 2431
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 75
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 399697
telemt_user_connections_current{user="hello"} 909
telemt_user_octets_from_client{user="hello"} 7753227724 (7.22 GB)
telemt_user_octets_to_client{user="hello"} 146667058700 (136.59 GB)
telemt_user_unique_ips_current{user="hello"} 336
telemt_user_unique_ips_recent_window{user="hello"} 113
```

## psb.hosting

```
telemt 3.3.22

telemt_uptime_seconds 24378.2 (6h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2148598
telemt_connections_bad_total 149450
telemt_connections_current 2785
telemt_connections_me_current 2785
telemt_handshake_timeouts_total 36453
telemt_upstream_connect_attempt_total 3797
telemt_upstream_connect_success_total 3772
telemt_upstream_connect_fail_total 25
telemt_upstream_connect_attempts_per_request{bucket="1"} 3797
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1974
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1770
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 25
telemt_me_keepalive_timeout_total 260
telemt_me_reconnect_attempts_total 2550
telemt_me_reconnect_success_total 2532
telemt_me_reader_eof_total 2572
telemt_me_idle_close_by_peer_total 2571
telemt_me_route_drop_no_conn_total 1839808
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1861299
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6735
telemt_desync_full_logged_total 2174
telemt_desync_suppressed_total 4561
telemt_desync_frames_bucket_total{bucket="1_2"} 1163
telemt_desync_frames_bucket_total{bucket="3_10"} 2650
telemt_desync_frames_bucket_total{bucket="gt_10"} 2922
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 2498
telemt_me_writer_restored_same_endpoint_total 2530
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 2874
telemt_user_connections_total{user="hello"} 1856668
telemt_user_connections_current{user="hello"} 2785
telemt_user_octets_from_client{user="hello"} 28790547320 (26.81 GB)
telemt_user_octets_to_client{user="hello"} 646289330988 (601.90 GB)
telemt_user_unique_ips_current{user="hello"} 945
telemt_user_unique_ips_recent_window{user="hello"} 312
```

## koara.io

Не удалось получить метрики для этого сервера.

## landvps.ru

```
telemt 3.3.22

telemt_uptime_seconds 25020.8 (6h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2277838
telemt_connections_bad_total 73551
telemt_connections_current 1916
telemt_connections_me_current 1916
telemt_handshake_timeouts_total 22626
telemt_upstream_connect_attempt_total 3777
telemt_upstream_connect_success_total 3740
telemt_upstream_connect_fail_total 37
telemt_upstream_connect_attempts_per_request{bucket="1"} 3777
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1889
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1801
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 37
telemt_me_keepalive_timeout_total 18
telemt_me_reconnect_attempts_total 2500
telemt_me_reconnect_success_total 2471
telemt_me_reader_eof_total 2576
telemt_me_idle_close_by_peer_total 2575
telemt_me_route_drop_no_conn_total 3728152
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2023095
telemt_me_writer_pick_total{mode="p2c",result="full"} 30
telemt_me_writer_pick_total{mode="p2c",result="closed"} 61
telemt_me_endpoint_quarantine_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7675
telemt_desync_full_logged_total 2012
telemt_desync_suppressed_total 5663
telemt_desync_frames_bucket_total{bucket="1_2"} 1671
telemt_desync_frames_bucket_total{bucket="3_10"} 3529
telemt_desync_frames_bucket_total{bucket="gt_10"} 2475
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 2490
telemt_me_writer_restored_same_endpoint_total 2460
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 1000
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 2023003
telemt_user_connections_current{user="hello"} 1916
telemt_user_octets_from_client{user="hello"} 20991447000 (19.55 GB)
telemt_user_octets_to_client{user="hello"} 373934741368 (348.25 GB)
telemt_user_unique_ips_current{user="hello"} 692
telemt_user_unique_ips_recent_window{user="hello"} 210
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 19535.5 (5h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1321919
telemt_connections_bad_total 228436
telemt_handshake_timeouts_total 12558
telemt_upstream_connect_attempt_total 3472
telemt_upstream_connect_success_total 3369
telemt_upstream_connect_fail_total 103
telemt_upstream_connect_attempts_per_request{bucket="1"} 3472
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1736
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1591
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 103
telemt_me_keepalive_timeout_total 84
telemt_me_reconnect_attempts_total 6909
telemt_me_reconnect_success_total 2377
telemt_me_reader_eof_total 2587
telemt_me_idle_close_by_peer_total 2587
telemt_me_route_drop_no_conn_total 550692
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 976490
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3788
telemt_desync_full_logged_total 1358
telemt_desync_suppressed_total 2430
telemt_desync_frames_bucket_total{bucket="1_2"} 668
telemt_desync_frames_bucket_total{bucket="3_10"} 1282
telemt_desync_frames_bucket_total{bucket="gt_10"} 1838
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 2561
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 2351
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 786
telemt_me_writer_removed_unexpected_minus_restored_total 184
telemt_user_connections_total{user="hello"} 975854
telemt_user_connections_current{user="hello"} 2355
telemt_user_octets_from_client{user="hello"} 17631583496 (16.42 GB)
telemt_user_octets_to_client{user="hello"} 480025722852 (447.06 GB)
telemt_user_unique_ips_current{user="hello"} 856
telemt_user_unique_ips_recent_window{user="hello"} 262
```

## hostvds.com

```
telemt 3.3.22

telemt_uptime_seconds 24468.5 (6h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 373505
telemt_connections_bad_total 10706
telemt_connections_current 582
telemt_connections_me_current 582
telemt_relay_adaptive_promotions_total 18
telemt_relay_adaptive_hard_promotions_total 18
telemt_handshake_timeouts_total 4198
telemt_upstream_connect_attempt_total 8252
telemt_upstream_connect_success_total 8219
telemt_upstream_connect_fail_total 33
telemt_upstream_connect_attempts_per_request{bucket="1"} 8252
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4206
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3941
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 51
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33
telemt_me_reconnect_attempts_total 332606
telemt_me_reconnect_success_total 3136
telemt_me_reader_eof_total 3217
telemt_me_idle_close_by_peer_total 3217
telemt_me_route_drop_no_conn_total 221023
telemt_me_route_drop_channel_closed_total 105
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 332249
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 9
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 750
telemt_desync_full_logged_total 276
telemt_desync_suppressed_total 474
telemt_desync_frames_bucket_total{bucket="1_2"} 181
telemt_desync_frames_bucket_total{bucket="3_10"} 292
telemt_desync_frames_bucket_total{bucket="gt_10"} 277
telemt_pool_swap_total 23
telemt_pool_stale_pick_total 980
telemt_me_writer_removed_unexpected_total 3102
telemt_me_refill_failed_total 10448
telemt_me_writer_restored_same_endpoint_total 3125
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 40876
telemt_user_connections_total{user="hello"} 335934
telemt_user_connections_current{user="hello"} 582
telemt_user_octets_from_client{user="hello"} 7280685653 (6.78 GB)
telemt_user_octets_to_client{user="hello"} 83495653937 (77.76 GB)
telemt_user_msgs_from_client{user="hello"} 38712
telemt_user_msgs_to_client{user="hello"} 31668
telemt_user_unique_ips_current{user="hello"} 212
telemt_user_unique_ips_recent_window{user="hello"} 67
```

## 4vps.su

```
telemt 3.3.22

telemt_uptime_seconds 23540.2 (6h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1322862
telemt_connections_bad_total 104278
telemt_connections_current 2217
telemt_connections_me_current 2217
telemt_handshake_timeouts_total 28682
telemt_upstream_connect_attempt_total 3881
telemt_upstream_connect_success_total 3880
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 3881
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2091
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1760
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 18184
telemt_me_reconnect_success_total 2661
telemt_me_reader_eof_total 2730
telemt_me_idle_close_by_peer_total 2729
telemt_me_route_drop_no_conn_total 592569
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="base"} 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1106006
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5123
telemt_desync_full_logged_total 1681
telemt_desync_suppressed_total 3442
telemt_desync_frames_bucket_total{bucket="1_2"} 1222
telemt_desync_frames_bucket_total{bucket="3_10"} 1731
telemt_desync_frames_bucket_total{bucket="gt_10"} 2170
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 2648
telemt_me_refill_failed_total 741
telemt_me_writer_restored_same_endpoint_total 2600
telemt_me_writer_restored_fallback_total 61
telemt_me_async_recovery_trigger_total 9552
telemt_user_connections_total{user="hello"} 1104735
telemt_user_connections_current{user="hello"} 2217
telemt_user_octets_from_client{user="hello"} 22319581920 (20.79 GB)
telemt_user_octets_to_client{user="hello"} 642198904300 (598.09 GB)
telemt_user_unique_ips_current{user="hello"} 705
telemt_user_unique_ips_recent_window{user="hello"} 223
```