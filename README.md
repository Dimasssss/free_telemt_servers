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

# Server Metrics 2026-03-18 21:16:44 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 21083.2 (5h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 491983
telemt_connections_bad_total 28180
telemt_handshake_timeouts_total 9706
telemt_upstream_connect_attempt_total 3781
telemt_upstream_connect_success_total 3778
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 3781
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1846
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1879
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 143
telemt_me_reconnect_attempts_total 2716
telemt_me_reconnect_success_total 2700
telemt_me_reader_eof_total 2814
telemt_me_idle_close_by_peer_total 2814
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 199582
telemt_me_route_drop_channel_closed_total 97
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 417955
telemt_me_writer_pick_total{mode="p2c",result="full"} 116
telemt_me_writer_pick_total{mode="p2c",result="closed"} 293
telemt_me_endpoint_quarantine_total 30
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2518
telemt_desync_full_logged_total 747
telemt_desync_suppressed_total 1771
telemt_desync_frames_bucket_total{bucket="1_2"} 582
telemt_desync_frames_bucket_total{bucket="3_10"} 806
telemt_desync_frames_bucket_total{bucket="gt_10"} 1130
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 2750
telemt_me_writer_restored_same_endpoint_total 2680
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 75
telemt_me_writer_removed_unexpected_minus_restored_total 50
telemt_user_connections_total{user="hello"} 417774
telemt_user_connections_current{user="hello"} 854
telemt_user_octets_from_client{user="hello"} 8013861152 (7.46 GB)
telemt_user_octets_to_client{user="hello"} 154367644320 (143.77 GB)
telemt_user_unique_ips_current{user="hello"} 325
telemt_user_unique_ips_recent_window{user="hello"} 98
```

## psb.hosting

```
telemt 3.3.22

telemt_uptime_seconds 25910.8 (7h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2220539
telemt_connections_bad_total 156647
telemt_connections_current 2701
telemt_connections_me_current 2701
telemt_handshake_timeouts_total 36939
telemt_upstream_connect_attempt_total 4008
telemt_upstream_connect_success_total 3983
telemt_upstream_connect_fail_total 25
telemt_upstream_connect_attempts_per_request{bucket="1"} 4008
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2086
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1868
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 25
telemt_me_keepalive_timeout_total 260
telemt_me_reconnect_attempts_total 2702
telemt_me_reconnect_success_total 2683
telemt_me_reader_eof_total 2734
telemt_me_idle_close_by_peer_total 2733
telemt_me_route_drop_no_conn_total 1864339
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1920980
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6941
telemt_desync_full_logged_total 2252
telemt_desync_suppressed_total 4689
telemt_desync_frames_bucket_total{bucket="1_2"} 1207
telemt_desync_frames_bucket_total{bucket="3_10"} 2726
telemt_desync_frames_bucket_total{bucket="gt_10"} 3008
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 2652
telemt_me_writer_restored_same_endpoint_total 2681
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 2874
telemt_user_connections_total{user="hello"} 1916372
telemt_user_connections_current{user="hello"} 2701
telemt_user_octets_from_client{user="hello"} 30914838528 (28.79 GB)
telemt_user_octets_to_client{user="hello"} 675687139572 (629.28 GB)
telemt_user_unique_ips_current{user="hello"} 907
telemt_user_unique_ips_recent_window{user="hello"} 274
```

## koara.io

```
telemt 3.3.22

telemt_uptime_seconds 25839.3 (7h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1699900
telemt_connections_bad_total 140008
telemt_connections_current 2213
telemt_connections_me_current 2213
telemt_handshake_timeouts_total 40769
telemt_upstream_connect_attempt_total 3725
telemt_upstream_connect_success_total 3705
telemt_upstream_connect_fail_total 20
telemt_upstream_connect_attempts_per_request{bucket="1"} 3725
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1934
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1749
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 20
telemt_me_keepalive_timeout_total 29
telemt_me_reconnect_attempts_total 2422
telemt_me_reconnect_success_total 2402
telemt_me_reader_eof_total 2553
telemt_me_idle_close_by_peer_total 2553
telemt_me_route_drop_no_conn_total 686599
telemt_me_route_drop_channel_closed_total 64
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1371573
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6675
telemt_desync_full_logged_total 2040
telemt_desync_suppressed_total 4635
telemt_desync_frames_bucket_total{bucket="1_2"} 1640
telemt_desync_frames_bucket_total{bucket="3_10"} 2497
telemt_desync_frames_bucket_total{bucket="gt_10"} 2538
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 2460
telemt_me_writer_restored_same_endpoint_total 2385
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 652
telemt_me_writer_removed_unexpected_minus_restored_total 58
telemt_user_connections_total{user="hello"} 1370772
telemt_user_connections_current{user="hello"} 2212
telemt_user_octets_from_client{user="hello"} 29536343612 (27.51 GB)
telemt_user_octets_to_client{user="hello"} 702341027304 (654.11 GB)
telemt_user_unique_ips_current{user="hello"} 776
telemt_user_unique_ips_recent_window{user="hello"} 224
```

## landvps.ru

```
telemt 3.3.22

telemt_uptime_seconds 26553.8 (7h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2347862
telemt_connections_bad_total 89540
telemt_connections_current 1785
telemt_connections_me_current 1785
telemt_handshake_timeouts_total 23038
telemt_upstream_connect_attempt_total 4043
telemt_upstream_connect_success_total 4005
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 4043
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2022
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1931
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_keepalive_timeout_total 18
telemt_me_reconnect_attempts_total 2679
telemt_me_reconnect_success_total 2649
telemt_me_reader_eof_total 2768
telemt_me_idle_close_by_peer_total 2767
telemt_me_route_drop_no_conn_total 3748008
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2062385
telemt_me_writer_pick_total{mode="p2c",result="full"} 30
telemt_me_writer_pick_total{mode="p2c",result="closed"} 61
telemt_me_endpoint_quarantine_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7836
telemt_desync_full_logged_total 2062
telemt_desync_suppressed_total 5774
telemt_desync_frames_bucket_total{bucket="1_2"} 1720
telemt_desync_frames_bucket_total{bucket="3_10"} 3574
telemt_desync_frames_bucket_total{bucket="gt_10"} 2542
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 2670
telemt_me_writer_restored_same_endpoint_total 2638
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 1000
telemt_me_writer_removed_unexpected_minus_restored_total 21
telemt_user_connections_total{user="hello"} 2062286
telemt_user_connections_current{user="hello"} 1785
telemt_user_octets_from_client{user="hello"} 21582356536 (20.10 GB)
telemt_user_octets_to_client{user="hello"} 392356287036 (365.41 GB)
telemt_user_unique_ips_current{user="hello"} 637
telemt_user_unique_ips_recent_window{user="hello"} 215
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 21068.6 (5h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1382933
telemt_connections_bad_total 233818
telemt_handshake_timeouts_total 13180
telemt_upstream_connect_attempt_total 3873
telemt_upstream_connect_success_total 3753
telemt_upstream_connect_fail_total 120
telemt_upstream_connect_attempts_per_request{bucket="1"} 3873
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1924
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1783
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 120
telemt_me_keepalive_timeout_total 93
telemt_me_reconnect_attempts_total 7206
telemt_me_reconnect_success_total 2674
telemt_me_reader_eof_total 2886
telemt_me_idle_close_by_peer_total 2886
telemt_me_route_drop_no_conn_total 570148
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1026057
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4006
telemt_desync_full_logged_total 1455
telemt_desync_suppressed_total 2551
telemt_desync_frames_bucket_total{bucket="1_2"} 706
telemt_desync_frames_bucket_total{bucket="3_10"} 1358
telemt_desync_frames_bucket_total{bucket="gt_10"} 1942
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 2860
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 2648
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 786
telemt_me_writer_removed_unexpected_minus_restored_total 186
telemt_user_connections_total{user="hello"} 1025420
telemt_user_connections_current{user="hello"} 2194
telemt_user_octets_from_client{user="hello"} 18341640092 (17.08 GB)
telemt_user_octets_to_client{user="hello"} 506057961504 (471.30 GB)
telemt_user_unique_ips_current{user="hello"} 809
telemt_user_unique_ips_recent_window{user="hello"} 287
```

## hostvds.com

```
telemt 3.3.22

telemt_uptime_seconds 26001.5 (7h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 385238
telemt_connections_bad_total 10715
telemt_connections_current 582
telemt_connections_me_current 582
telemt_relay_adaptive_promotions_total 18
telemt_relay_adaptive_hard_promotions_total 18
telemt_handshake_timeouts_total 4253
telemt_upstream_connect_attempt_total 8512
telemt_upstream_connect_success_total 8476
telemt_upstream_connect_fail_total 36
telemt_upstream_connect_attempts_per_request{bucket="1"} 8512
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4313
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4090
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 51
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 36
telemt_me_reconnect_attempts_total 332821
telemt_me_reconnect_success_total 3349
telemt_me_reader_eof_total 3445
telemt_me_idle_close_by_peer_total 3445
telemt_me_route_drop_no_conn_total 226621
telemt_me_route_drop_channel_closed_total 107
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 343627
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 9
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 816
telemt_desync_full_logged_total 296
telemt_desync_suppressed_total 520
telemt_desync_frames_bucket_total{bucket="1_2"} 207
telemt_desync_frames_bucket_total{bucket="3_10"} 327
telemt_desync_frames_bucket_total{bucket="gt_10"} 282
telemt_pool_swap_total 24
telemt_pool_stale_pick_total 980
telemt_me_writer_removed_unexpected_total 3319
telemt_me_refill_failed_total 10448
telemt_me_writer_restored_same_endpoint_total 3338
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 40876
telemt_user_connections_total{user="hello"} 347147
telemt_user_connections_current{user="hello"} 582
telemt_user_octets_from_client{user="hello"} 7501695213 (6.99 GB)
telemt_user_octets_to_client{user="hello"} 92244149869 (85.91 GB)
telemt_user_msgs_from_client{user="hello"} 38712
telemt_user_msgs_to_client{user="hello"} 31668
telemt_user_unique_ips_current{user="hello"} 199
telemt_user_unique_ips_recent_window{user="hello"} 64
```

## 4vps.su

```
telemt 3.3.22

telemt_uptime_seconds 25073.2 (6h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1376058
telemt_connections_bad_total 107505
telemt_connections_current 2165
telemt_connections_me_current 2165
telemt_handshake_timeouts_total 30636
telemt_upstream_connect_attempt_total 4088
telemt_upstream_connect_success_total 4087
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 4088
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2198
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1860
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 18348
telemt_me_reconnect_success_total 2824
telemt_me_reader_eof_total 2900
telemt_me_idle_close_by_peer_total 2899
telemt_me_route_drop_no_conn_total 609866
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="base"} 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1151201
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5515
telemt_desync_full_logged_total 1792
telemt_desync_suppressed_total 3723
telemt_desync_frames_bucket_total{bucket="1_2"} 1352
telemt_desync_frames_bucket_total{bucket="3_10"} 1847
telemt_desync_frames_bucket_total{bucket="gt_10"} 2316
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 2814
telemt_me_refill_failed_total 741
telemt_me_writer_restored_same_endpoint_total 2763
telemt_me_writer_restored_fallback_total 61
telemt_me_async_recovery_trigger_total 9552
telemt_user_connections_total{user="hello"} 1149883
telemt_user_connections_current{user="hello"} 2165
telemt_user_octets_from_client{user="hello"} 22878881076 (21.31 GB)
telemt_user_octets_to_client{user="hello"} 670273303076 (624.24 GB)
telemt_user_unique_ips_current{user="hello"} 700
telemt_user_unique_ips_recent_window{user="hello"} 205
```