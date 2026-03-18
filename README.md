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

# Server Metrics 2026-03-18 21:06:31 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 20469.8 (5h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 483662
telemt_connections_bad_total 27658
telemt_handshake_timeouts_total 9648
telemt_upstream_connect_attempt_total 3606
telemt_upstream_connect_success_total 3603
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 3606
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1769
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1781
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 141
telemt_me_reconnect_attempts_total 2584
telemt_me_reconnect_success_total 2568
telemt_me_reader_eof_total 2682
telemt_me_idle_close_by_peer_total 2682
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 197244
telemt_me_route_drop_channel_closed_total 97
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 411347
telemt_me_writer_pick_total{mode="p2c",result="full"} 116
telemt_me_writer_pick_total{mode="p2c",result="closed"} 293
telemt_me_endpoint_quarantine_total 28
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2461
telemt_desync_full_logged_total 730
telemt_desync_suppressed_total 1731
telemt_desync_frames_bucket_total{bucket="1_2"} 571
telemt_desync_frames_bucket_total{bucket="3_10"} 792
telemt_desync_frames_bucket_total{bucket="gt_10"} 1098
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 2616
telemt_me_writer_restored_same_endpoint_total 2550
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 75
telemt_me_writer_removed_unexpected_minus_restored_total 48
telemt_user_connections_total{user="hello"} 411165
telemt_user_connections_current{user="hello"} 940
telemt_user_octets_from_client{user="hello"} 7887232824 (7.35 GB)
telemt_user_octets_to_client{user="hello"} 150863592924 (140.50 GB)
telemt_user_unique_ips_current{user="hello"} 342
telemt_user_unique_ips_recent_window{user="hello"} 110
```

## psb.hosting

```
telemt 3.3.22

telemt_uptime_seconds 25298.2 (7h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2192387
telemt_connections_bad_total 152648
telemt_connections_current 2766
telemt_connections_me_current 2766
telemt_handshake_timeouts_total 36775
telemt_upstream_connect_attempt_total 3929
telemt_upstream_connect_success_total 3904
telemt_upstream_connect_fail_total 25
telemt_upstream_connect_attempts_per_request{bucket="1"} 3929
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2046
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1829
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 25
telemt_me_keepalive_timeout_total 260
telemt_me_reconnect_attempts_total 2626
telemt_me_reconnect_success_total 2607
telemt_me_reader_eof_total 2653
telemt_me_idle_close_by_peer_total 2652
telemt_me_route_drop_no_conn_total 1855017
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1898762
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6883
telemt_desync_full_logged_total 2225
telemt_desync_suppressed_total 4658
telemt_desync_frames_bucket_total{bucket="1_2"} 1192
telemt_desync_frames_bucket_total{bucket="3_10"} 2702
telemt_desync_frames_bucket_total{bucket="gt_10"} 2989
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 2575
telemt_me_writer_restored_same_endpoint_total 2605
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 2874
telemt_user_connections_total{user="hello"} 1894145
telemt_user_connections_current{user="hello"} 2766
telemt_user_octets_from_client{user="hello"} 30013738216 (27.95 GB)
telemt_user_octets_to_client{user="hello"} 662720094460 (617.21 GB)
telemt_user_unique_ips_current{user="hello"} 928
telemt_user_unique_ips_recent_window{user="hello"} 285
```

## koara.io

```
telemt 3.3.22

telemt_uptime_seconds 25226.2 (7h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1676871
telemt_connections_bad_total 137341
telemt_connections_current 2345
telemt_connections_me_current 2345
telemt_handshake_timeouts_total 40386
telemt_upstream_connect_attempt_total 3608
telemt_upstream_connect_success_total 3591
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 3608
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1873
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1697
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 29
telemt_me_reconnect_attempts_total 2346
telemt_me_reconnect_success_total 2326
telemt_me_reader_eof_total 2471
telemt_me_idle_close_by_peer_total 2471
telemt_me_route_drop_no_conn_total 677512
telemt_me_route_drop_channel_closed_total 64
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1352104
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6553
telemt_desync_full_logged_total 2006
telemt_desync_suppressed_total 4547
telemt_desync_frames_bucket_total{bucket="1_2"} 1610
telemt_desync_frames_bucket_total{bucket="3_10"} 2457
telemt_desync_frames_bucket_total{bucket="gt_10"} 2486
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 2383
telemt_me_writer_restored_same_endpoint_total 2309
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 652
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 1351303
telemt_user_connections_current{user="hello"} 2345
telemt_user_octets_from_client{user="hello"} 28934997340 (26.95 GB)
telemt_user_octets_to_client{user="hello"} 693287144848 (645.67 GB)
telemt_user_unique_ips_current{user="hello"} 832
telemt_user_unique_ips_recent_window{user="hello"} 256
```

## landvps.ru

```
telemt 3.3.22

telemt_uptime_seconds 25940.9 (7h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2315849
telemt_connections_bad_total 78690
telemt_connections_current 1778
telemt_connections_me_current 1778
telemt_handshake_timeouts_total 22901
telemt_upstream_connect_attempt_total 3925
telemt_upstream_connect_success_total 3888
telemt_upstream_connect_fail_total 37
telemt_upstream_connect_attempts_per_request{bucket="1"} 3925
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1962
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1876
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 37
telemt_me_keepalive_timeout_total 18
telemt_me_reconnect_attempts_total 2605
telemt_me_reconnect_success_total 2575
telemt_me_reader_eof_total 2686
telemt_me_idle_close_by_peer_total 2685
telemt_me_route_drop_no_conn_total 3740334
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2047082
telemt_me_writer_pick_total{mode="p2c",result="full"} 30
telemt_me_writer_pick_total{mode="p2c",result="closed"} 61
telemt_me_endpoint_quarantine_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7743
telemt_desync_full_logged_total 2040
telemt_desync_suppressed_total 5703
telemt_desync_frames_bucket_total{bucket="1_2"} 1702
telemt_desync_frames_bucket_total{bucket="3_10"} 3543
telemt_desync_frames_bucket_total{bucket="gt_10"} 2498
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 2594
telemt_me_writer_restored_same_endpoint_total 2564
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 1000
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 2046986
telemt_user_connections_current{user="hello"} 1778
telemt_user_octets_from_client{user="hello"} 21425998948 (19.95 GB)
telemt_user_octets_to_client{user="hello"} 383975345648 (357.60 GB)
telemt_user_unique_ips_current{user="hello"} 649
telemt_user_unique_ips_recent_window{user="hello"} 190
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 20455.9 (5h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1357119
telemt_connections_bad_total 229433
telemt_handshake_timeouts_total 12980
telemt_upstream_connect_attempt_total 3674
telemt_upstream_connect_success_total 3565
telemt_upstream_connect_fail_total 109
telemt_upstream_connect_attempts_per_request{bucket="1"} 3674
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1835
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1685
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 109
telemt_me_keepalive_timeout_total 89
telemt_me_reconnect_attempts_total 7061
telemt_me_reconnect_success_total 2529
telemt_me_reader_eof_total 2739
telemt_me_idle_close_by_peer_total 2739
telemt_me_route_drop_no_conn_total 562407
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1007026
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3926
telemt_desync_full_logged_total 1423
telemt_desync_suppressed_total 2503
telemt_desync_frames_bucket_total{bucket="1_2"} 694
telemt_desync_frames_bucket_total{bucket="3_10"} 1329
telemt_desync_frames_bucket_total{bucket="gt_10"} 1903
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 2713
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 2503
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 786
telemt_me_writer_removed_unexpected_minus_restored_total 184
telemt_user_connections_total{user="hello"} 1006391
telemt_user_connections_current{user="hello"} 2392
telemt_user_octets_from_client{user="hello"} 18094388576 (16.85 GB)
telemt_user_octets_to_client{user="hello"} 495647299544 (461.61 GB)
telemt_user_unique_ips_current{user="hello"} 868
telemt_user_unique_ips_recent_window{user="hello"} 272
```

## hostvds.com

```
telemt 3.3.22

telemt_uptime_seconds 25388.7 (7h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 380905
telemt_connections_bad_total 10711
telemt_connections_current 621
telemt_connections_me_current 621
telemt_relay_adaptive_promotions_total 18
telemt_relay_adaptive_hard_promotions_total 18
telemt_handshake_timeouts_total 4241
telemt_upstream_connect_attempt_total 8430
telemt_upstream_connect_success_total 8395
telemt_upstream_connect_fail_total 35
telemt_upstream_connect_attempts_per_request{bucket="1"} 8430
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4276
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4047
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 51
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 35
telemt_me_reconnect_attempts_total 332739
telemt_me_reconnect_success_total 3269
telemt_me_reader_eof_total 3361
telemt_me_idle_close_by_peer_total 3361
telemt_me_route_drop_no_conn_total 224033
telemt_me_route_drop_channel_closed_total 107
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 339338
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 9
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 783
telemt_desync_full_logged_total 288
telemt_desync_suppressed_total 495
telemt_desync_frames_bucket_total{bucket="1_2"} 190
telemt_desync_frames_bucket_total{bucket="3_10"} 314
telemt_desync_frames_bucket_total{bucket="gt_10"} 279
telemt_pool_swap_total 24
telemt_pool_stale_pick_total 980
telemt_me_writer_removed_unexpected_total 3235
telemt_me_refill_failed_total 10448
telemt_me_writer_restored_same_endpoint_total 3258
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 40876
telemt_user_connections_total{user="hello"} 343018
telemt_user_connections_current{user="hello"} 621
telemt_user_octets_from_client{user="hello"} 7394085717 (6.89 GB)
telemt_user_octets_to_client{user="hello"} 88238358773 (82.18 GB)
telemt_user_msgs_from_client{user="hello"} 38712
telemt_user_msgs_to_client{user="hello"} 31668
telemt_user_unique_ips_current{user="hello"} 200
telemt_user_unique_ips_recent_window{user="hello"} 60
```

## 4vps.su

```
telemt 3.3.22

telemt_uptime_seconds 24460.4 (6h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1355150
telemt_connections_bad_total 106796
telemt_connections_current 2096
telemt_connections_me_current 2096
telemt_handshake_timeouts_total 29771
telemt_upstream_connect_attempt_total 4029
telemt_upstream_connect_success_total 4028
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 4029
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2168
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1831
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 18289
telemt_me_reconnect_success_total 2765
telemt_me_reader_eof_total 2837
telemt_me_idle_close_by_peer_total 2836
telemt_me_route_drop_no_conn_total 603285
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="base"} 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1132735
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5386
telemt_desync_full_logged_total 1754
telemt_desync_suppressed_total 3632
telemt_desync_frames_bucket_total{bucket="1_2"} 1303
telemt_desync_frames_bucket_total{bucket="3_10"} 1809
telemt_desync_frames_bucket_total{bucket="gt_10"} 2274
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 2754
telemt_me_refill_failed_total 741
telemt_me_writer_restored_same_endpoint_total 2704
telemt_me_writer_restored_fallback_total 61
telemt_me_async_recovery_trigger_total 9552
telemt_user_connections_total{user="hello"} 1131455
telemt_user_connections_current{user="hello"} 2096
telemt_user_octets_from_client{user="hello"} 22649585100 (21.09 GB)
telemt_user_octets_to_client{user="hello"} 657141391424 (612.01 GB)
telemt_user_unique_ips_current{user="hello"} 698
telemt_user_unique_ips_recent_window{user="hello"} 210
```