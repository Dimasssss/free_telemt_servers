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

# Server Metrics 2026-03-18 20:30:44 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 18323.0 (5h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 448716
telemt_connections_bad_total 25929
telemt_handshake_timeouts_total 9441
telemt_upstream_connect_attempt_total 3251
telemt_upstream_connect_success_total 3248
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 3251
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1603
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1592
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 136
telemt_me_reconnect_attempts_total 2315
telemt_me_reconnect_success_total 2300
telemt_me_reader_eof_total 2401
telemt_me_idle_close_by_peer_total 2401
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 186751
telemt_me_route_drop_channel_closed_total 97
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 384887
telemt_me_writer_pick_total{mode="p2c",result="full"} 116
telemt_me_writer_pick_total{mode="p2c",result="closed"} 293
telemt_me_endpoint_quarantine_total 28
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2300
telemt_desync_full_logged_total 671
telemt_desync_suppressed_total 1629
telemt_desync_frames_bucket_total{bucket="1_2"} 536
telemt_desync_frames_bucket_total{bucket="3_10"} 732
telemt_desync_frames_bucket_total{bucket="gt_10"} 1032
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 2346
telemt_me_writer_restored_same_endpoint_total 2282
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 75
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 384705
telemt_user_connections_current{user="hello"} 921
telemt_user_octets_from_client{user="hello"} 7482163968 (6.97 GB)
telemt_user_octets_to_client{user="hello"} 140017215212 (130.40 GB)
telemt_user_unique_ips_current{user="hello"} 356
telemt_user_unique_ips_recent_window{user="hello"} 98
```

## psb.hosting

```
telemt 3.3.22

telemt_uptime_seconds 23151.0 (6h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2093119
telemt_connections_bad_total 148545
telemt_connections_current 2831
telemt_connections_me_current 2831
telemt_handshake_timeouts_total 35753
telemt_upstream_connect_attempt_total 3612
telemt_upstream_connect_success_total 3590
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 3612
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1884
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1679
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_keepalive_timeout_total 260
telemt_me_reconnect_attempts_total 2438
telemt_me_reconnect_success_total 2421
telemt_me_reader_eof_total 2455
telemt_me_idle_close_by_peer_total 2454
telemt_me_route_drop_no_conn_total 1817785
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1809729
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6404
telemt_desync_full_logged_total 2065
telemt_desync_suppressed_total 4339
telemt_desync_frames_bucket_total{bucket="1_2"} 1111
telemt_desync_frames_bucket_total{bucket="3_10"} 2527
telemt_desync_frames_bucket_total{bucket="gt_10"} 2766
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 2385
telemt_me_writer_restored_same_endpoint_total 2419
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 2874
telemt_user_connections_total{user="hello"} 1805106
telemt_user_connections_current{user="hello"} 2831
telemt_user_octets_from_client{user="hello"} 27708146064 (25.81 GB)
telemt_user_octets_to_client{user="hello"} 617976505156 (575.54 GB)
telemt_user_unique_ips_current{user="hello"} 996
telemt_user_unique_ips_recent_window{user="hello"} 331
```

## koara.io

```
telemt 3.3.22

telemt_uptime_seconds 23079.4 (6h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1596428
telemt_connections_bad_total 129441
telemt_connections_current 2643
telemt_connections_me_current 2643
telemt_handshake_timeouts_total 37866
telemt_upstream_connect_attempt_total 3315
telemt_upstream_connect_success_total 3298
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 3315
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1720
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1558
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 29
telemt_me_reconnect_attempts_total 2144
telemt_me_reconnect_success_total 2124
telemt_me_reader_eof_total 2259
telemt_me_idle_close_by_peer_total 2259
telemt_me_route_drop_no_conn_total 647581
telemt_me_route_drop_channel_closed_total 61
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1284481
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6231
telemt_desync_full_logged_total 1899
telemt_desync_suppressed_total 4332
telemt_desync_frames_bucket_total{bucket="1_2"} 1560
telemt_desync_frames_bucket_total{bucket="3_10"} 2338
telemt_desync_frames_bucket_total{bucket="gt_10"} 2333
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 2179
telemt_me_writer_restored_same_endpoint_total 2107
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 652
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 1283680
telemt_user_connections_current{user="hello"} 2643
telemt_user_octets_from_client{user="hello"} 27412657484 (25.53 GB)
telemt_user_octets_to_client{user="hello"} 646784597656 (602.37 GB)
telemt_user_unique_ips_current{user="hello"} 895
telemt_user_unique_ips_recent_window{user="hello"} 306
```

## landvps.ru

```
telemt 3.3.22

telemt_uptime_seconds 23794.0 (6h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2232089
telemt_connections_bad_total 67082
telemt_connections_current 1996
telemt_connections_me_current 1996
telemt_handshake_timeouts_total 22250
telemt_upstream_connect_attempt_total 3590
telemt_upstream_connect_success_total 3554
telemt_upstream_connect_fail_total 36
telemt_upstream_connect_attempts_per_request{bucket="1"} 3590
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1798
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1706
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 36
telemt_me_keepalive_timeout_total 18
telemt_me_reconnect_attempts_total 2357
telemt_me_reconnect_success_total 2329
telemt_me_reader_eof_total 2429
telemt_me_idle_close_by_peer_total 2428
telemt_me_route_drop_no_conn_total 3711853
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1990690
telemt_me_writer_pick_total{mode="p2c",result="full"} 30
telemt_me_writer_pick_total{mode="p2c",result="closed"} 61
telemt_me_endpoint_quarantine_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7560
telemt_desync_full_logged_total 1971
telemt_desync_suppressed_total 5589
telemt_desync_frames_bucket_total{bucket="1_2"} 1638
telemt_desync_frames_bucket_total{bucket="3_10"} 3492
telemt_desync_frames_bucket_total{bucket="gt_10"} 2430
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 2349
telemt_me_writer_restored_same_endpoint_total 2318
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 1000
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 1990597
telemt_user_connections_current{user="hello"} 1996
telemt_user_octets_from_client{user="hello"} 18737470816 (17.45 GB)
telemt_user_octets_to_client{user="hello"} 356152093532 (331.69 GB)
telemt_user_unique_ips_current{user="hello"} 725
telemt_user_unique_ips_recent_window{user="hello"} 226
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 18308.7 (5h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1271543
telemt_connections_bad_total 224123
telemt_handshake_timeouts_total 12121
telemt_upstream_connect_attempt_total 3328
telemt_upstream_connect_success_total 3227
telemt_upstream_connect_fail_total 101
telemt_upstream_connect_attempts_per_request{bucket="1"} 3328
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1668
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 101
telemt_me_keepalive_timeout_total 82
telemt_me_reconnect_attempts_total 6810
telemt_me_reconnect_success_total 2279
telemt_me_reader_eof_total 2484
telemt_me_idle_close_by_peer_total 2484
telemt_me_route_drop_no_conn_total 533925
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 934983
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3487
telemt_desync_full_logged_total 1263
telemt_desync_suppressed_total 2224
telemt_desync_frames_bucket_total{bucket="1_2"} 636
telemt_desync_frames_bucket_total{bucket="3_10"} 1200
telemt_desync_frames_bucket_total{bucket="gt_10"} 1651
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 2462
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 2253
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 786
telemt_me_writer_removed_unexpected_minus_restored_total 183
telemt_user_connections_total{user="hello"} 934350
telemt_user_connections_current{user="hello"} 2466
telemt_user_octets_from_client{user="hello"} 16497712296 (15.36 GB)
telemt_user_octets_to_client{user="hello"} 455071728580 (423.82 GB)
telemt_user_unique_ips_current{user="hello"} 902
telemt_user_unique_ips_recent_window{user="hello"} 315
```

## hostvds.com

```
telemt 3.3.22

telemt_uptime_seconds 23242.6 (6h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 363593
telemt_connections_bad_total 10695
telemt_connections_current 729
telemt_connections_me_current 729
telemt_relay_adaptive_promotions_total 18
telemt_relay_adaptive_hard_promotions_total 18
telemt_handshake_timeouts_total 4133
telemt_upstream_connect_attempt_total 8027
telemt_upstream_connect_success_total 7994
telemt_upstream_connect_fail_total 33
telemt_upstream_connect_attempts_per_request{bucket="1"} 8027
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4091
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3831
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 51
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33
telemt_me_reconnect_attempts_total 332469
telemt_me_reconnect_success_total 2999
telemt_me_reader_eof_total 3068
telemt_me_idle_close_by_peer_total 3068
telemt_me_route_drop_no_conn_total 216928
telemt_me_route_drop_channel_closed_total 103
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 323050
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 9
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 698
telemt_desync_full_logged_total 257
telemt_desync_suppressed_total 441
telemt_desync_frames_bucket_total{bucket="1_2"} 165
telemt_desync_frames_bucket_total{bucket="3_10"} 265
telemt_desync_frames_bucket_total{bucket="gt_10"} 268
telemt_pool_swap_total 21
telemt_pool_stale_pick_total 980
telemt_me_writer_removed_unexpected_total 2961
telemt_me_refill_failed_total 10448
telemt_me_writer_restored_same_endpoint_total 2988
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 40876
telemt_user_connections_total{user="hello"} 326734
telemt_user_connections_current{user="hello"} 729
telemt_user_octets_from_client{user="hello"} 6969995221 (6.49 GB)
telemt_user_octets_to_client{user="hello"} 78938110273 (73.52 GB)
telemt_user_msgs_from_client{user="hello"} 38712
telemt_user_msgs_to_client{user="hello"} 31668
telemt_user_unique_ips_current{user="hello"} 246
telemt_user_unique_ips_recent_window{user="hello"} 93
```

## 4vps.su

```
telemt 3.3.22

telemt_uptime_seconds 22313.3 (6h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1280627
telemt_connections_bad_total 101638
telemt_connections_current 2266
telemt_connections_me_current 2266
telemt_handshake_timeouts_total 26485
telemt_upstream_connect_attempt_total 3679
telemt_upstream_connect_success_total 3678
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 3679
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1978
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1671
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 18068
telemt_me_reconnect_success_total 2547
telemt_me_reader_eof_total 2603
telemt_me_idle_close_by_peer_total 2602
telemt_me_route_drop_no_conn_total 575038
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="base"} 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1070573
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4862
telemt_desync_full_logged_total 1610
telemt_desync_suppressed_total 3252
telemt_desync_frames_bucket_total{bucket="1_2"} 1149
telemt_desync_frames_bucket_total{bucket="3_10"} 1660
telemt_desync_frames_bucket_total{bucket="gt_10"} 2053
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 2531
telemt_me_refill_failed_total 741
telemt_me_writer_restored_same_endpoint_total 2486
telemt_me_writer_restored_fallback_total 61
telemt_me_async_recovery_trigger_total 9552
telemt_user_connections_total{user="hello"} 1069321
telemt_user_connections_current{user="hello"} 2266
telemt_user_octets_from_client{user="hello"} 21149114660 (19.70 GB)
telemt_user_octets_to_client{user="hello"} 621960261052 (579.25 GB)
telemt_user_unique_ips_current{user="hello"} 748
telemt_user_unique_ips_recent_window{user="hello"} 243
```