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

# Server Metrics 2026-03-18 21:21:50 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 21389.5 (5h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 495823
telemt_connections_bad_total 28448
telemt_handshake_timeouts_total 9720
telemt_upstream_connect_attempt_total 3838
telemt_upstream_connect_success_total 3835
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 3838
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1863
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1919
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 144
telemt_me_reconnect_attempts_total 2773
telemt_me_reconnect_success_total 2757
telemt_me_reader_eof_total 2871
telemt_me_idle_close_by_peer_total 2871
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 200618
telemt_me_route_drop_channel_closed_total 98
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 421430
telemt_me_writer_pick_total{mode="p2c",result="full"} 116
telemt_me_writer_pick_total{mode="p2c",result="closed"} 293
telemt_me_endpoint_quarantine_total 30
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2552
telemt_desync_full_logged_total 759
telemt_desync_suppressed_total 1793
telemt_desync_frames_bucket_total{bucket="1_2"} 588
telemt_desync_frames_bucket_total{bucket="3_10"} 818
telemt_desync_frames_bucket_total{bucket="gt_10"} 1146
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 2807
telemt_me_writer_restored_same_endpoint_total 2737
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 75
telemt_me_writer_removed_unexpected_minus_restored_total 50
telemt_user_connections_total{user="hello"} 421248
telemt_user_connections_current{user="hello"} 839
telemt_user_octets_from_client{user="hello"} 8090630172 (7.53 GB)
telemt_user_octets_to_client{user="hello"} 156197901772 (145.47 GB)
telemt_user_unique_ips_current{user="hello"} 313
telemt_user_unique_ips_recent_window{user="hello"} 92
```

## psb.hosting

```
telemt 3.3.22

telemt_uptime_seconds 26217.8 (7h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2232180
telemt_connections_bad_total 157067
telemt_connections_current 2603
telemt_connections_me_current 2603
telemt_handshake_timeouts_total 37071
telemt_upstream_connect_attempt_total 4071
telemt_upstream_connect_success_total 4044
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 4071
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2120
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1895
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_keepalive_timeout_total 260
telemt_me_reconnect_attempts_total 2720
telemt_me_reconnect_success_total 2700
telemt_me_reader_eof_total 2753
telemt_me_idle_close_by_peer_total 2752
telemt_me_route_drop_no_conn_total 1868732
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1931192
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6973
telemt_desync_full_logged_total 2266
telemt_desync_suppressed_total 4707
telemt_desync_frames_bucket_total{bucket="1_2"} 1213
telemt_desync_frames_bucket_total{bucket="3_10"} 2739
telemt_desync_frames_bucket_total{bucket="gt_10"} 3021
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 2671
telemt_me_writer_restored_same_endpoint_total 2698
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 2874
telemt_user_connections_total{user="hello"} 1926582
telemt_user_connections_current{user="hello"} 2603
telemt_user_octets_from_client{user="hello"} 31525425556 (29.36 GB)
telemt_user_octets_to_client{user="hello"} 680692122748 (633.94 GB)
telemt_user_unique_ips_current{user="hello"} 906
telemt_user_unique_ips_recent_window{user="hello"} 288
```

## koara.io

```
telemt 3.3.22

telemt_uptime_seconds 26145.9 (7h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1710351
telemt_connections_bad_total 140756
telemt_connections_current 2052
telemt_connections_me_current 2052
telemt_handshake_timeouts_total 40973
telemt_upstream_connect_attempt_total 3766
telemt_upstream_connect_success_total 3745
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 3766
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1957
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1766
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 29
telemt_me_reconnect_attempts_total 2448
telemt_me_reconnect_success_total 2427
telemt_me_reader_eof_total 2578
telemt_me_idle_close_by_peer_total 2578
telemt_me_route_drop_no_conn_total 690080
telemt_me_route_drop_channel_closed_total 64
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1380854
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6712
telemt_desync_full_logged_total 2050
telemt_desync_suppressed_total 4662
telemt_desync_frames_bucket_total{bucket="1_2"} 1650
telemt_desync_frames_bucket_total{bucket="3_10"} 2512
telemt_desync_frames_bucket_total{bucket="gt_10"} 2550
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 2485
telemt_me_writer_restored_same_endpoint_total 2410
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 652
telemt_me_writer_removed_unexpected_minus_restored_total 58
telemt_user_connections_total{user="hello"} 1380053
telemt_user_connections_current{user="hello"} 2052
telemt_user_octets_from_client{user="hello"} 29702819524 (27.66 GB)
telemt_user_octets_to_client{user="hello"} 706928899788 (658.38 GB)
telemt_user_unique_ips_current{user="hello"} 743
telemt_user_unique_ips_recent_window{user="hello"} 211
```

## landvps.ru

```
telemt 3.3.22

telemt_uptime_seconds 26860.9 (7h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2358205
telemt_connections_bad_total 90145
telemt_connections_current 1678
telemt_connections_me_current 1678
telemt_handshake_timeouts_total 23067
telemt_upstream_connect_attempt_total 4060
telemt_upstream_connect_success_total 4022
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 4060
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2030
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1940
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_keepalive_timeout_total 18
telemt_me_reconnect_attempts_total 2696
telemt_me_reconnect_success_total 2666
telemt_me_reader_eof_total 2787
telemt_me_idle_close_by_peer_total 2786
telemt_me_route_drop_no_conn_total 3752349
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2069477
telemt_me_writer_pick_total{mode="p2c",result="full"} 30
telemt_me_writer_pick_total{mode="p2c",result="closed"} 61
telemt_me_endpoint_quarantine_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7872
telemt_desync_full_logged_total 2071
telemt_desync_suppressed_total 5801
telemt_desync_frames_bucket_total{bucket="1_2"} 1732
telemt_desync_frames_bucket_total{bucket="3_10"} 3583
telemt_desync_frames_bucket_total{bucket="gt_10"} 2557
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 2689
telemt_me_writer_restored_same_endpoint_total 2655
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 1000
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 2069378
telemt_user_connections_current{user="hello"} 1678
telemt_user_octets_from_client{user="hello"} 21654713648 (20.17 GB)
telemt_user_octets_to_client{user="hello"} 397188834992 (369.91 GB)
telemt_user_unique_ips_current{user="hello"} 635
telemt_user_unique_ips_recent_window{user="hello"} 198
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 21375.5 (5h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1393757
telemt_connections_bad_total 234309
telemt_handshake_timeouts_total 13284
telemt_upstream_connect_attempt_total 3947
telemt_upstream_connect_success_total 3827
telemt_upstream_connect_fail_total 120
telemt_upstream_connect_attempts_per_request{bucket="1"} 3947
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1957
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1824
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 120
telemt_me_keepalive_timeout_total 94
telemt_me_reconnect_attempts_total 7278
telemt_me_reconnect_success_total 2745
telemt_me_reader_eof_total 2960
telemt_me_idle_close_by_peer_total 2960
telemt_me_route_drop_no_conn_total 573600
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1035333
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4047
telemt_desync_full_logged_total 1471
telemt_desync_suppressed_total 2576
telemt_desync_frames_bucket_total{bucket="1_2"} 708
telemt_desync_frames_bucket_total{bucket="3_10"} 1373
telemt_desync_frames_bucket_total{bucket="gt_10"} 1966
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 2934
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 2719
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 786
telemt_me_writer_removed_unexpected_minus_restored_total 189
telemt_user_connections_total{user="hello"} 1034695
telemt_user_connections_current{user="hello"} 2142
telemt_user_octets_from_client{user="hello"} 18467429980 (17.20 GB)
telemt_user_octets_to_client{user="hello"} 511957949688 (476.80 GB)
telemt_user_unique_ips_current{user="hello"} 820
telemt_user_unique_ips_recent_window{user="hello"} 232
```

## hostvds.com

```
telemt 3.3.22

telemt_uptime_seconds 26308.2 (7h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 387341
telemt_connections_bad_total 10815
telemt_connections_current 603
telemt_connections_me_current 603
telemt_relay_adaptive_promotions_total 18
telemt_relay_adaptive_hard_promotions_total 18
telemt_handshake_timeouts_total 4282
telemt_upstream_connect_attempt_total 8600
telemt_upstream_connect_success_total 8563
telemt_upstream_connect_fail_total 37
telemt_upstream_connect_attempts_per_request{bucket="1"} 8600
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4361
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4129
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 51
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 37
telemt_me_reconnect_attempts_total 332864
telemt_me_reconnect_success_total 3392
telemt_me_reader_eof_total 3495
telemt_me_idle_close_by_peer_total 3495
telemt_me_route_drop_no_conn_total 227463
telemt_me_route_drop_channel_closed_total 107
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 345563
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 9
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 817
telemt_desync_full_logged_total 297
telemt_desync_suppressed_total 520
telemt_desync_frames_bucket_total{bucket="1_2"} 207
telemt_desync_frames_bucket_total{bucket="3_10"} 328
telemt_desync_frames_bucket_total{bucket="gt_10"} 282
telemt_pool_swap_total 25
telemt_pool_stale_pick_total 980
telemt_me_writer_removed_unexpected_total 3362
telemt_me_refill_failed_total 10448
telemt_me_writer_restored_same_endpoint_total 3381
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 40876
telemt_user_connections_total{user="hello"} 349083
telemt_user_connections_current{user="hello"} 603
telemt_user_octets_from_client{user="hello"} 7525433505 (7.01 GB)
telemt_user_octets_to_client{user="hello"} 93825278133 (87.38 GB)
telemt_user_msgs_from_client{user="hello"} 38712
telemt_user_msgs_to_client{user="hello"} 31668
telemt_user_unique_ips_current{user="hello"} 190
telemt_user_unique_ips_recent_window{user="hello"} 54
```

## 4vps.su

```
telemt 3.3.22

telemt_uptime_seconds 25380.1 (7h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1386138
telemt_connections_bad_total 107781
telemt_connections_current 2066
telemt_connections_me_current 2066
telemt_handshake_timeouts_total 31076
telemt_upstream_connect_attempt_total 4177
telemt_upstream_connect_success_total 4176
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 4177
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2249
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1897
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 18394
telemt_me_reconnect_success_total 2869
telemt_me_reader_eof_total 2952
telemt_me_idle_close_by_peer_total 2951
telemt_me_route_drop_no_conn_total 612924
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="base"} 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1160126
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5596
telemt_desync_full_logged_total 1815
telemt_desync_suppressed_total 3781
telemt_desync_frames_bucket_total{bucket="1_2"} 1378
telemt_desync_frames_bucket_total{bucket="3_10"} 1881
telemt_desync_frames_bucket_total{bucket="gt_10"} 2337
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 2860
telemt_me_refill_failed_total 741
telemt_me_writer_restored_same_endpoint_total 2808
telemt_me_writer_restored_fallback_total 61
telemt_me_async_recovery_trigger_total 9552
telemt_user_connections_total{user="hello"} 1158809
telemt_user_connections_current{user="hello"} 2066
telemt_user_octets_from_client{user="hello"} 22996066100 (21.42 GB)
telemt_user_octets_to_client{user="hello"} 677331369408 (630.81 GB)
telemt_user_unique_ips_current{user="hello"} 684
telemt_user_unique_ips_recent_window{user="hello"} 184
```