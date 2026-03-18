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

# Server Metrics 2026-03-18 21:01:24 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 20163.1 (5h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 477868
telemt_connections_bad_total 27412
telemt_handshake_timeouts_total 9594
telemt_upstream_connect_attempt_total 3569
telemt_upstream_connect_success_total 3566
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 3569
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1756
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1757
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 139
telemt_me_reconnect_attempts_total 2547
telemt_me_reconnect_success_total 2531
telemt_me_reader_eof_total 2643
telemt_me_idle_close_by_peer_total 2643
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 195497
telemt_me_route_drop_channel_closed_total 97
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 407509
telemt_me_writer_pick_total{mode="p2c",result="full"} 116
telemt_me_writer_pick_total{mode="p2c",result="closed"} 293
telemt_me_endpoint_quarantine_total 28
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2430
telemt_desync_full_logged_total 721
telemt_desync_suppressed_total 1709
telemt_desync_frames_bucket_total{bucket="1_2"} 561
telemt_desync_frames_bucket_total{bucket="3_10"} 780
telemt_desync_frames_bucket_total{bucket="gt_10"} 1089
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 2577
telemt_me_writer_restored_same_endpoint_total 2513
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 75
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 407327
telemt_user_connections_current{user="hello"} 917
telemt_user_octets_from_client{user="hello"} 7851662440 (7.31 GB)
telemt_user_octets_to_client{user="hello"} 149402595384 (139.14 GB)
telemt_user_unique_ips_current{user="hello"} 338
telemt_user_unique_ips_recent_window{user="hello"} 111
```

## psb.hosting

```
telemt 3.3.22

telemt_uptime_seconds 24991.3 (6h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2178871
telemt_connections_bad_total 152419
telemt_connections_current 2918
telemt_connections_me_current 2918
telemt_handshake_timeouts_total 36661
telemt_upstream_connect_attempt_total 3874
telemt_upstream_connect_success_total 3849
telemt_upstream_connect_fail_total 25
telemt_upstream_connect_attempts_per_request{bucket="1"} 3874
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2009
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1811
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 25
telemt_me_keepalive_timeout_total 260
telemt_me_reconnect_attempts_total 2611
telemt_me_reconnect_success_total 2592
telemt_me_reader_eof_total 2638
telemt_me_idle_close_by_peer_total 2637
telemt_me_route_drop_no_conn_total 1849731
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1886509
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6847
telemt_desync_full_logged_total 2213
telemt_desync_suppressed_total 4634
telemt_desync_frames_bucket_total{bucket="1_2"} 1181
telemt_desync_frames_bucket_total{bucket="3_10"} 2688
telemt_desync_frames_bucket_total{bucket="gt_10"} 2978
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 2560
telemt_me_writer_restored_same_endpoint_total 2590
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 2874
telemt_user_connections_total{user="hello"} 1881875
telemt_user_connections_current{user="hello"} 2918
telemt_user_octets_from_client{user="hello"} 29722498016 (27.68 GB)
telemt_user_octets_to_client{user="hello"} 656547899476 (611.46 GB)
telemt_user_unique_ips_current{user="hello"} 953
telemt_user_unique_ips_recent_window{user="hello"} 331
```

## koara.io

```
telemt 3.3.22

telemt_uptime_seconds 24920.1 (6h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1665127
telemt_connections_bad_total 135871
telemt_connections_current 2159
telemt_connections_me_current 2159
telemt_handshake_timeouts_total 40201
telemt_upstream_connect_attempt_total 3583
telemt_upstream_connect_success_total 3566
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 3583
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1859
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1686
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 29
telemt_me_reconnect_attempts_total 2326
telemt_me_reconnect_success_total 2306
telemt_me_reader_eof_total 2451
telemt_me_idle_close_by_peer_total 2451
telemt_me_route_drop_no_conn_total 672679
telemt_me_route_drop_channel_closed_total 64
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1342233
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6497
telemt_desync_full_logged_total 1990
telemt_desync_suppressed_total 4507
telemt_desync_frames_bucket_total{bucket="1_2"} 1604
telemt_desync_frames_bucket_total{bucket="3_10"} 2438
telemt_desync_frames_bucket_total{bucket="gt_10"} 2455
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 2363
telemt_me_writer_restored_same_endpoint_total 2289
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 652
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 1341433
telemt_user_connections_current{user="hello"} 2159
telemt_user_octets_from_client{user="hello"} 28655501992 (26.69 GB)
telemt_user_octets_to_client{user="hello"} 686605131280 (639.45 GB)
telemt_user_unique_ips_current{user="hello"} 795
telemt_user_unique_ips_recent_window{user="hello"} 265
```

## landvps.ru

```
telemt 3.3.22

telemt_uptime_seconds 25634.3 (7h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2300943
telemt_connections_bad_total 74566
telemt_connections_current 1888
telemt_connections_me_current 1888
telemt_handshake_timeouts_total 22774
telemt_upstream_connect_attempt_total 3902
telemt_upstream_connect_success_total 3865
telemt_upstream_connect_fail_total 37
telemt_upstream_connect_attempts_per_request{bucket="1"} 3902
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1953
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1862
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 37
telemt_me_keepalive_timeout_total 18
telemt_me_reconnect_attempts_total 2582
telemt_me_reconnect_success_total 2552
telemt_me_reader_eof_total 2663
telemt_me_idle_close_by_peer_total 2662
telemt_me_route_drop_no_conn_total 3736587
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2039253
telemt_me_writer_pick_total{mode="p2c",result="full"} 30
telemt_me_writer_pick_total{mode="p2c",result="closed"} 61
telemt_me_endpoint_quarantine_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7712
telemt_desync_full_logged_total 2031
telemt_desync_suppressed_total 5681
telemt_desync_frames_bucket_total{bucket="1_2"} 1691
telemt_desync_frames_bucket_total{bucket="3_10"} 3536
telemt_desync_frames_bucket_total{bucket="gt_10"} 2485
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 2571
telemt_me_writer_restored_same_endpoint_total 2541
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 1000
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 2039157
telemt_user_connections_current{user="hello"} 1888
telemt_user_octets_from_client{user="hello"} 21217347092 (19.76 GB)
telemt_user_octets_to_client{user="hello"} 380808215400 (354.66 GB)
telemt_user_unique_ips_current{user="hello"} 686
telemt_user_unique_ips_recent_window{user="hello"} 225
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 20149.0 (5h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1345068
telemt_connections_bad_total 229074
telemt_handshake_timeouts_total 12911
telemt_upstream_connect_attempt_total 3625
telemt_upstream_connect_success_total 3516
telemt_upstream_connect_fail_total 109
telemt_upstream_connect_attempts_per_request{bucket="1"} 3625
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1813
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1660
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 109
telemt_me_keepalive_timeout_total 88
telemt_me_reconnect_attempts_total 7012
telemt_me_reconnect_success_total 2480
telemt_me_reader_eof_total 2690
telemt_me_idle_close_by_peer_total 2690
telemt_me_route_drop_no_conn_total 557864
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 996493
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3888
telemt_desync_full_logged_total 1406
telemt_desync_suppressed_total 2482
telemt_desync_frames_bucket_total{bucket="1_2"} 689
telemt_desync_frames_bucket_total{bucket="3_10"} 1315
telemt_desync_frames_bucket_total{bucket="gt_10"} 1884
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 2664
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 2454
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 786
telemt_me_writer_removed_unexpected_minus_restored_total 184
telemt_user_connections_total{user="hello"} 995858
telemt_user_connections_current{user="hello"} 2403
telemt_user_octets_from_client{user="hello"} 17948115376 (16.72 GB)
telemt_user_octets_to_client{user="hello"} 490370583328 (456.69 GB)
telemt_user_unique_ips_current{user="hello"} 886
telemt_user_unique_ips_recent_window{user="hello"} 300
```

## hostvds.com

```
telemt 3.3.22

telemt_uptime_seconds 25082.4 (6h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 378487
telemt_connections_bad_total 10710
telemt_connections_current 665
telemt_connections_me_current 665
telemt_relay_adaptive_promotions_total 18
telemt_relay_adaptive_hard_promotions_total 18
telemt_handshake_timeouts_total 4234
telemt_upstream_connect_attempt_total 8338
telemt_upstream_connect_success_total 8305
telemt_upstream_connect_fail_total 33
telemt_upstream_connect_attempts_per_request{bucket="1"} 8338
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4234
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3999
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 51
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33
telemt_me_reconnect_attempts_total 332692
telemt_me_reconnect_success_total 3222
telemt_me_reader_eof_total 3306
telemt_me_idle_close_by_peer_total 3306
telemt_me_route_drop_no_conn_total 223081
telemt_me_route_drop_channel_closed_total 107
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 336979
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 9
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 776
telemt_desync_full_logged_total 284
telemt_desync_suppressed_total 492
telemt_desync_frames_bucket_total{bucket="1_2"} 188
telemt_desync_frames_bucket_total{bucket="3_10"} 309
telemt_desync_frames_bucket_total{bucket="gt_10"} 279
telemt_pool_swap_total 23
telemt_pool_stale_pick_total 980
telemt_me_writer_removed_unexpected_total 3188
telemt_me_refill_failed_total 10448
telemt_me_writer_restored_same_endpoint_total 3211
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 40876
telemt_user_connections_total{user="hello"} 340660
telemt_user_connections_current{user="hello"} 665
telemt_user_octets_from_client{user="hello"} 7367306693 (6.86 GB)
telemt_user_octets_to_client{user="hello"} 86500302549 (80.56 GB)
telemt_user_msgs_from_client{user="hello"} 38712
telemt_user_msgs_to_client{user="hello"} 31668
telemt_user_unique_ips_current{user="hello"} 210
telemt_user_unique_ips_recent_window{user="hello"} 80
```

## 4vps.su

```
telemt 3.3.22

telemt_uptime_seconds 24153.7 (6h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1344774
telemt_connections_bad_total 106577
telemt_connections_current 2162
telemt_connections_me_current 2162
telemt_handshake_timeouts_total 29329
telemt_upstream_connect_attempt_total 3951
telemt_upstream_connect_success_total 3950
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 3951
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2126
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1795
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 18254
telemt_me_reconnect_success_total 2731
telemt_me_reader_eof_total 2800
telemt_me_idle_close_by_peer_total 2799
telemt_me_route_drop_no_conn_total 599755
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="base"} 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1123623
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5307
telemt_desync_full_logged_total 1733
telemt_desync_suppressed_total 3574
telemt_desync_frames_bucket_total{bucket="1_2"} 1272
telemt_desync_frames_bucket_total{bucket="3_10"} 1790
telemt_desync_frames_bucket_total{bucket="gt_10"} 2245
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 2718
telemt_me_refill_failed_total 741
telemt_me_writer_restored_same_endpoint_total 2670
telemt_me_writer_restored_fallback_total 61
telemt_me_async_recovery_trigger_total 9552
telemt_user_connections_total{user="hello"} 1122343
telemt_user_connections_current{user="hello"} 2162
telemt_user_octets_from_client{user="hello"} 22526588152 (20.98 GB)
telemt_user_octets_to_client{user="hello"} 650949161832 (606.24 GB)
telemt_user_unique_ips_current{user="hello"} 704
telemt_user_unique_ips_recent_window{user="hello"} 225
```