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

# Server Metrics 2026-03-18 19:49:50 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 15869.0 (4h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 404304
telemt_connections_bad_total 23840
telemt_handshake_timeouts_total 8883
telemt_upstream_connect_attempt_total 2859
telemt_upstream_connect_success_total 2856
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 2859
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1394
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1422
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 134
telemt_me_reconnect_attempts_total 2052
telemt_me_reconnect_success_total 2040
telemt_me_reader_eof_total 2118
telemt_me_idle_close_by_peer_total 2118
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 170676
telemt_me_route_drop_channel_closed_total 80
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 349545
telemt_me_writer_pick_total{mode="p2c",result="full"} 116
telemt_me_writer_pick_total{mode="p2c",result="closed"} 293
telemt_me_endpoint_quarantine_total 28
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2093
telemt_desync_full_logged_total 590
telemt_desync_suppressed_total 1503
telemt_desync_frames_bucket_total{bucket="1_2"} 501
telemt_desync_frames_bucket_total{bucket="3_10"} 660
telemt_desync_frames_bucket_total{bucket="gt_10"} 932
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 2078
telemt_me_writer_restored_same_endpoint_total 2022
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 75
telemt_me_writer_removed_unexpected_minus_restored_total 38
telemt_user_connections_total{user="hello"} 349426
telemt_user_connections_current{user="hello"} 1083
telemt_user_octets_from_client{user="hello"} 7039377032 (6.56 GB)
telemt_user_octets_to_client{user="hello"} 124695443464 (116.13 GB)
telemt_user_unique_ips_current{user="hello"} 399
telemt_user_unique_ips_recent_window{user="hello"} 133
```

## psb.hosting

```
telemt 3.3.22

telemt_uptime_seconds 20697.2 (5h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1953778
telemt_connections_bad_total 137418
telemt_connections_current 3457
telemt_connections_me_current 3457
telemt_handshake_timeouts_total 33538
telemt_upstream_connect_attempt_total 3263
telemt_upstream_connect_success_total 3247
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 3263
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1708
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1516
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_keepalive_timeout_total 71
telemt_me_reconnect_attempts_total 2226
telemt_me_reconnect_success_total 2209
telemt_me_reader_eof_total 2223
telemt_me_idle_close_by_peer_total 2222
telemt_me_route_drop_no_conn_total 1762359
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1687299
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5844
telemt_desync_full_logged_total 1872
telemt_desync_suppressed_total 3972
telemt_desync_frames_bucket_total{bucket="1_2"} 1007
telemt_desync_frames_bucket_total{bucket="3_10"} 2329
telemt_desync_frames_bucket_total{bucket="gt_10"} 2508
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 2163
telemt_me_writer_restored_same_endpoint_total 2207
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 2874
telemt_user_connections_total{user="hello"} 1682525
telemt_user_connections_current{user="hello"} 3457
telemt_user_octets_from_client{user="hello"} 25976969584 (24.19 GB)
telemt_user_octets_to_client{user="hello"} 555109829356 (516.99 GB)
telemt_user_unique_ips_current{user="hello"} 1134
telemt_user_unique_ips_recent_window{user="hello"} 440
```

## koara.io

```
telemt 3.3.22

telemt_uptime_seconds 20625.7 (5h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1482883
telemt_connections_bad_total 123911
telemt_connections_current 2911
telemt_connections_me_current 2911
telemt_handshake_timeouts_total 32108
telemt_upstream_connect_attempt_total 2945
telemt_upstream_connect_success_total 2929
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 2945
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1538
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1371
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_keepalive_timeout_total 29
telemt_me_reconnect_attempts_total 1904
telemt_me_reconnect_success_total 1887
telemt_me_reader_eof_total 2004
telemt_me_idle_close_by_peer_total 2004
telemt_me_route_drop_no_conn_total 603989
telemt_me_route_drop_channel_closed_total 59
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1187590
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5571
telemt_desync_full_logged_total 1734
telemt_desync_suppressed_total 3837
telemt_desync_frames_bucket_total{bucket="1_2"} 1386
telemt_desync_frames_bucket_total{bucket="3_10"} 2107
telemt_desync_frames_bucket_total{bucket="gt_10"} 2078
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 1935
telemt_me_writer_restored_same_endpoint_total 1870
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 652
telemt_me_writer_removed_unexpected_minus_restored_total 48
telemt_user_connections_total{user="hello"} 1186794
telemt_user_connections_current{user="hello"} 2911
telemt_user_octets_from_client{user="hello"} 25682894184 (23.92 GB)
telemt_user_octets_to_client{user="hello"} 578973798368 (539.21 GB)
telemt_user_unique_ips_current{user="hello"} 962
telemt_user_unique_ips_recent_window{user="hello"} 336
```

## landvps.ru

```
telemt 3.3.22

telemt_uptime_seconds 21340.2 (5h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2127494
telemt_connections_bad_total 55235
telemt_connections_current 2384
telemt_connections_me_current 2384
telemt_handshake_timeouts_total 21618
telemt_upstream_connect_attempt_total 3235
telemt_upstream_connect_success_total 3204
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 3235
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1633
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1524
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 18
telemt_me_reconnect_attempts_total 2136
telemt_me_reconnect_success_total 2110
telemt_me_reader_eof_total 2191
telemt_me_idle_close_by_peer_total 2190
telemt_me_route_drop_no_conn_total 3663763
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1902642
telemt_me_writer_pick_total{mode="p2c",result="full"} 30
telemt_me_writer_pick_total{mode="p2c",result="closed"} 61
telemt_me_endpoint_quarantine_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7064
telemt_desync_full_logged_total 1804
telemt_desync_suppressed_total 5260
telemt_desync_frames_bucket_total{bucket="1_2"} 1545
telemt_desync_frames_bucket_total{bucket="3_10"} 3302
telemt_desync_frames_bucket_total{bucket="gt_10"} 2217
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 2124
telemt_me_writer_restored_same_endpoint_total 2099
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 1000
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 1902550
telemt_user_connections_current{user="hello"} 2384
telemt_user_octets_from_client{user="hello"} 17417936100 (16.22 GB)
telemt_user_octets_to_client{user="hello"} 316679819236 (294.93 GB)
telemt_user_unique_ips_current{user="hello"} 795
telemt_user_unique_ips_recent_window{user="hello"} 277
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 15855.1 (4h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1155481
telemt_connections_bad_total 212500
telemt_handshake_timeouts_total 11110
telemt_upstream_connect_attempt_total 2827
telemt_upstream_connect_success_total 2740
telemt_upstream_connect_fail_total 87
telemt_upstream_connect_attempts_per_request{bucket="1"} 2827
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1450
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1254
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 87
telemt_me_keepalive_timeout_total 69
telemt_me_reconnect_attempts_total 4020
telemt_me_reconnect_success_total 1924
telemt_me_reader_eof_total 2045
telemt_me_idle_close_by_peer_total 2045
telemt_me_route_drop_no_conn_total 494297
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 843557
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2998
telemt_desync_full_logged_total 1075
telemt_desync_suppressed_total 1923
telemt_desync_frames_bucket_total{bucket="1_2"} 562
telemt_desync_frames_bucket_total{bucket="3_10"} 1028
telemt_desync_frames_bucket_total{bucket="gt_10"} 1408
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 2023
telemt_me_refill_failed_total 65
telemt_me_writer_restored_same_endpoint_total 1898
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 786
telemt_me_writer_removed_unexpected_minus_restored_total 99
telemt_user_connections_total{user="hello"} 842927
telemt_user_connections_current{user="hello"} 3182
telemt_user_octets_from_client{user="hello"} 14737056576 (13.72 GB)
telemt_user_octets_to_client{user="hello"} 395848419068 (368.66 GB)
telemt_user_unique_ips_current{user="hello"} 1033
telemt_user_unique_ips_recent_window{user="hello"} 338
```

## hostvds.com

```
telemt 3.3.22

telemt_uptime_seconds 20787.9 (5h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 340980
telemt_connections_bad_total 10658
telemt_connections_current 699
telemt_connections_me_current 699
telemt_relay_adaptive_promotions_total 18
telemt_relay_adaptive_hard_promotions_total 18
telemt_handshake_timeouts_total 3789
telemt_upstream_connect_attempt_total 7618
telemt_upstream_connect_success_total 7586
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 7618
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3876
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3638
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 51
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_reconnect_attempts_total 332164
telemt_me_reconnect_success_total 2694
telemt_me_reader_eof_total 2741
telemt_me_idle_close_by_peer_total 2741
telemt_me_route_drop_no_conn_total 207774
telemt_me_route_drop_channel_closed_total 99
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 302506
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 9
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 600
telemt_desync_full_logged_total 222
telemt_desync_suppressed_total 378
telemt_desync_frames_bucket_total{bucket="1_2"} 122
telemt_desync_frames_bucket_total{bucket="3_10"} 236
telemt_desync_frames_bucket_total{bucket="gt_10"} 242
telemt_pool_swap_total 18
telemt_pool_stale_pick_total 980
telemt_me_writer_removed_unexpected_total 2651
telemt_me_refill_failed_total 10448
telemt_me_writer_restored_same_endpoint_total 2683
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 40876
telemt_user_connections_total{user="hello"} 306190
telemt_user_connections_current{user="hello"} 699
telemt_user_octets_from_client{user="hello"} 5609677065 (5.22 GB)
telemt_user_octets_to_client{user="hello"} 67860444725 (63.20 GB)
telemt_user_msgs_from_client{user="hello"} 38712
telemt_user_msgs_to_client{user="hello"} 31668
telemt_user_unique_ips_current{user="hello"} 250
telemt_user_unique_ips_recent_window{user="hello"} 94
```

## 4vps.su

```
telemt 3.3.22

telemt_uptime_seconds 19859.4 (5h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1180806
telemt_connections_bad_total 97488
telemt_connections_current 2911
telemt_connections_me_current 2911
telemt_handshake_timeouts_total 23482
telemt_upstream_connect_attempt_total 3289
telemt_upstream_connect_success_total 3288
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 3289
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1770
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1494
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 17786
telemt_me_reconnect_success_total 2266
telemt_me_reader_eof_total 2305
telemt_me_idle_close_by_peer_total 2305
telemt_me_route_drop_no_conn_total 539720
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="base"} 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 981517
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4174
telemt_desync_full_logged_total 1413
telemt_desync_suppressed_total 2761
telemt_desync_frames_bucket_total{bucket="1_2"} 935
telemt_desync_frames_bucket_total{bucket="3_10"} 1468
telemt_desync_frames_bucket_total{bucket="gt_10"} 1771
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 2246
telemt_me_refill_failed_total 741
telemt_me_writer_restored_same_endpoint_total 2205
telemt_me_writer_restored_fallback_total 61
telemt_me_async_recovery_trigger_total 9552
telemt_user_connections_total{user="hello"} 980302
telemt_user_connections_current{user="hello"} 2911
telemt_user_octets_from_client{user="hello"} 19761674924 (18.40 GB)
telemt_user_octets_to_client{user="hello"} 560573089880 (522.07 GB)
telemt_user_unique_ips_current{user="hello"} 852
telemt_user_unique_ips_recent_window{user="hello"} 306
```